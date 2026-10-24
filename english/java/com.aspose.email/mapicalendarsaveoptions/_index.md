---
title: MapiCalendarSaveOptions
second_title: Aspose.Email for Java API Reference
description: Serves as the abstract base class for format-specific options when saving  objects to various formats ICS MSG.
type: docs
weight: 428
url: /java/com.aspose.email/mapicalendarsaveoptions/
---

**Inheritance:**
java.lang.Object
```
public abstract class MapiCalendarSaveOptions
```

Serves as the abstract base class for format-specific options when saving [MapiCalendar](../../com.aspose.email/mapicalendar) objects to various formats (ICS, MSG). This class provides common configuration properties such as save format and factory methods for creating format-specific save options.

--------------------

This class is designed to be inherited by concrete format-specific classes like [MapiCalendarIcsSaveOptions](../../com.aspose.email/mapicalendaricssaveoptions) and [MapiCalendarMsgSaveOptions](../../com.aspose.email/mapicalendarmsgsaveoptions). Do not instantiate this class directly. Use the format-specific subclasses or the static factory methods like  DefaultIcs ([getDefaultIcs](../../com.aspose.email/mapicalendarsaveoptions\#getDefaultIcs)),  DefaultMsg ([getDefaultMsg](../../com.aspose.email/mapicalendarsaveoptions\#getDefaultMsg)), and [fromSaveFormat(int)](../../com.aspose.email/mapicalendarsaveoptions\#fromSaveFormat-int-) to create appropriate save options for your target format.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromSaveFormat(int saveFormat)](#fromSaveFormat-int-) | Gets the MapiCalendarSaveOptions from SaveFormat. |
| [getClass()](#getClass--) |  |
| [getDefaultIcs()](#getDefaultIcs--) | Gets the default Ics save options. |
| [getDefaultMsg()](#getDefaultMsg--) | Gets the default Msg save options. |
| [getProductIdentifier()](#getProductIdentifier--) | Gets or sets the product identifier. |
| [getSaveFormat()](#getSaveFormat--) | Gets a save format. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setProductIdentifier(String value)](#setProductIdentifier-java.lang.String-) | Gets or sets the product identifier. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

