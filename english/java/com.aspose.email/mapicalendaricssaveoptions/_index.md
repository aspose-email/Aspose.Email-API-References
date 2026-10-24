---
title: MapiCalendarIcsSaveOptions
second_title: Aspose.Email for Java API Reference
description: Provides options for controlling how  instances are saved to iCalendar ICS format.
type: docs
weight: 417
url: /java/com.aspose.email/mapicalendaricssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiCalendarSaveOptions](../../com.aspose.email/mapicalendarsaveoptions)
```
public class MapiCalendarIcsSaveOptions extends MapiCalendarSaveOptions
```

Provides options for controlling how [MapiCalendar](../../com.aspose.email/mapicalendar) instances are saved to iCalendar (ICS) format. This class extends [MapiCalendarSaveOptions](../../com.aspose.email/mapicalendarsaveoptions) and adds iCalendar-specific configuration options for date/time handling and product identification.

--------------------

Use this class with [MapiCalendar.save(String,MapiCalendarSaveOptions)](../../com.aspose.email/mapicalendar\#save-String-MapiCalendarSaveOptions-) to save calendar items in iCalendar format. The  KeepOriginalDateTimeStamp ([getKeepOriginalDateTimeStamp](../../com.aspose.email/mapicalendaricssaveoptions\#getKeepOriginalDateTimeStamp)/[setKeepOriginalDateTimeStamp(boolean)](../../com.aspose.email/mapicalendaricssaveoptions\#setKeepOriginalDateTimeStamp-boolean-)) property controls whether original date/time stamps are preserved, and  ProductIdentifier ([MapiCalendarSaveOptions.getProductIdentifier](../../com.aspose.email/mapicalendarsaveoptions\#getProductIdentifier)/[MapiCalendarSaveOptions.setProductIdentifier(String)](../../com.aspose.email/mapicalendarsaveoptions\#setProductIdentifier-String-)) allows you to specify the product identifier for the generated iCalendar object.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiCalendarIcsSaveOptions()](#MapiCalendarIcsSaveOptions--) | Initializes a new instance of the [MapiCalendarSaveOptions](../../com.aspose.email/mapicalendarsaveoptions) class |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromSaveFormat(int saveFormat)](#fromSaveFormat-int-) | Gets the MapiCalendarSaveOptions from SaveFormat. |
| [getClass()](#getClass--) |  |
| [getDefaultIcs()](#getDefaultIcs--) | Gets the default Ics save options. |
| [getDefaultMsg()](#getDefaultMsg--) | Gets the default Msg save options. |
| [getKeepOriginalDateTimeStamp()](#getKeepOriginalDateTimeStamp--) | Gets or sets a value indicating whether to keep the original date and time stamps when saving to iCalendar format. |
| [getProductIdentifier()](#getProductIdentifier--) | Gets or sets the product identifier. |
| [getSaveFormat()](#getSaveFormat--) | Gets a save format. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setKeepOriginalDateTimeStamp(boolean value)](#setKeepOriginalDateTimeStamp-boolean-) | Gets or sets a value indicating whether to keep the original date and time stamps when saving to iCalendar format. |
| [setProductIdentifier(String value)](#setProductIdentifier-java.lang.String-) | Gets or sets the product identifier. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendarIcsSaveOptions() {#MapiCalendarIcsSaveOptions--}
```
public MapiCalendarIcsSaveOptions()
```


Initializes a new instance of the [MapiCalendarSaveOptions](../../com.aspose.email/mapicalendarsaveoptions) class

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromSaveFormat(int saveFormat) {#fromSaveFormat-int-}
```
public static MapiCalendarSaveOptions fromSaveFormat(int saveFormat)
```


Gets the MapiCalendarSaveOptions from SaveFormat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveFormat | int |  |

**Returns:**
[MapiCalendarSaveOptions](../../com.aspose.email/mapicalendarsaveoptions)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultIcs() {#getDefaultIcs--}
```
public static MapiCalendarIcsSaveOptions getDefaultIcs()
```


Gets the default Ics save options.

**Returns:**
[MapiCalendarIcsSaveOptions](../../com.aspose.email/mapicalendaricssaveoptions)
### getDefaultMsg() {#getDefaultMsg--}
```
public static MapiCalendarMsgSaveOptions getDefaultMsg()
```


Gets the default Msg save options.

**Returns:**
[MapiCalendarMsgSaveOptions](../../com.aspose.email/mapicalendarmsgsaveoptions)
### getKeepOriginalDateTimeStamp() {#getKeepOriginalDateTimeStamp--}
```
public final boolean getKeepOriginalDateTimeStamp()
```


Gets or sets a value indicating whether to keep the original date and time stamps when saving to iCalendar format. When set to true, the original timestamp information is preserved in the output ICS file.

Value:  true  to keep original date/time stamps; otherwise,  false . The default value is  false .

**Returns:**
boolean
### getProductIdentifier() {#getProductIdentifier--}
```
public final String getProductIdentifier()
```


Gets or sets the product identifier.

Value: The product identifier. This property specifies the identifier for the product that created the iCalendar object.

--------------------

If the property is not set or equal to null, the default PRODID is -//Aspose Ltd//iCalendar Builder (v3.0)//EN

**Returns:**
java.lang.String
### getSaveFormat() {#getSaveFormat--}
```
public final int getSaveFormat()
```


Gets a save format.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setKeepOriginalDateTimeStamp(boolean value) {#setKeepOriginalDateTimeStamp-boolean-}
```
public final void setKeepOriginalDateTimeStamp(boolean value)
```


Gets or sets a value indicating whether to keep the original date and time stamps when saving to iCalendar format. When set to true, the original timestamp information is preserved in the output ICS file.

Value:  true  to keep original date/time stamps; otherwise,  false . The default value is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setProductIdentifier(String value) {#setProductIdentifier-java.lang.String-}
```
public final void setProductIdentifier(String value)
```


Gets or sets the product identifier.

Value: The product identifier. This property specifies the identifier for the product that created the iCalendar object.

--------------------

If the property is not set or equal to null, the default PRODID is -//Aspose Ltd//iCalendar Builder (v3.0)//EN

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

