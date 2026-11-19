---
title: MapiCalendarMsgSaveOptions
second_title: Aspose.Email for Java API Reference
description: Options for saving a  to Outlook MSG format.
type: docs
weight: 420
url: /java/com.aspose.email/mapicalendarmsgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiCalendarSaveOptions](../../com.aspose.email/mapicalendarsaveoptions)
```
public class MapiCalendarMsgSaveOptions extends MapiCalendarSaveOptions
```

Options for saving a [MapiCalendar](../../com.aspose.email/mapicalendar) to Outlook MSG format.

Pass an instance to [MapiCalendar.save(String, MapiCalendarSaveOptions)](../../com.aspose.email/mapicalendar\#save-String--MapiCalendarSaveOptions-). MSG keeps all Outlook properties of the item.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiCalendarMsgSaveOptions()](#MapiCalendarMsgSaveOptions--) | Initializes a new instance of the [MapiCalendarMsgSaveOptions](../../com.aspose.email/mapicalendarmsgsaveoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromSaveFormat(int saveFormat)](#fromSaveFormat-int-) | Gets the default save options for the specified format. |
| [getClass()](#getClass--) |  |
| [getDefaultIcs()](#getDefaultIcs--) | Gets new iCalendar save options with the default settings. |
| [getDefaultMsg()](#getDefaultMsg--) | Gets new MSG save options with the default settings. |
| [getProductIdentifier()](#getProductIdentifier--) | Gets the identifier of the product that created the iCalendar file, written to its  PRODID  property. |
| [getSaveFormat()](#getSaveFormat--) | Gets the format these options save to. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setProductIdentifier(String value)](#setProductIdentifier-java.lang.String-) | Sets the identifier of the product that created the iCalendar file, written to its  PRODID  property. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendarMsgSaveOptions() {#MapiCalendarMsgSaveOptions--}
```
public MapiCalendarMsgSaveOptions()
```


Initializes a new instance of the [MapiCalendarMsgSaveOptions](../../com.aspose.email/mapicalendarmsgsaveoptions) class.

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


Gets the default save options for the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveFormat | int | The format: ICS or MSG. |

**Returns:**
[MapiCalendarSaveOptions](../../com.aspose.email/mapicalendarsaveoptions) - A [MapiCalendarIcsSaveOptions](../../com.aspose.email/mapicalendaricssaveoptions) or [MapiCalendarMsgSaveOptions](../../com.aspose.email/mapicalendarmsgsaveoptions) object.
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


Gets new iCalendar save options with the default settings.

**Returns:**
[MapiCalendarIcsSaveOptions](../../com.aspose.email/mapicalendaricssaveoptions)
### getDefaultMsg() {#getDefaultMsg--}
```
public static MapiCalendarMsgSaveOptions getDefaultMsg()
```


Gets new MSG save options with the default settings.

**Returns:**
[MapiCalendarMsgSaveOptions](../../com.aspose.email/mapicalendarmsgsaveoptions)
### getProductIdentifier() {#getProductIdentifier--}
```
public final String getProductIdentifier()
```


Gets the identifier of the product that created the iCalendar file, written to its  PRODID  property.

When the value is  null ,  -//Aspose Ltd//iCalendar Builder (v3.0)//EN  is written.

**Returns:**
java.lang.String - The product identifier.
### getSaveFormat() {#getSaveFormat--}
```
public final int getSaveFormat()
```


Gets the format these options save to.

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




### setProductIdentifier(String value) {#setProductIdentifier-java.lang.String-}
```
public final void setProductIdentifier(String value)
```


Sets the identifier of the product that created the iCalendar file, written to its  PRODID  property.

When the value is  null ,  -//Aspose Ltd//iCalendar Builder (v3.0)//EN  is written.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The product identifier. |

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

