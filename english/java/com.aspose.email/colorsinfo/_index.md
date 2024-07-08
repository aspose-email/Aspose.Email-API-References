---
title: ColorsInfo
second_title: Aspose.Email for Java API Reference
description: Contains colors definition for calendars and events
type: docs
weight: 109
url: /java/com.aspose.email/colorsinfo/
---

**Inheritance:**
java.lang.Object
```
public class ColorsInfo
```

Contains colors definition for calendars and events
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorsInfo()](#ColorsInfo--) | Initializes a new instance of the ColorsInfo class. |
| [ColorsInfo(Date updated, System.Collections.Generic.Dictionary<String,Colors> calendar, System.Collections.Generic.Dictionary<String,Colors> evnt)](#ColorsInfo-java.util.Date-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.email.Colors--com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.email.Colors--) | Initializes a new instance of the ColorsInfo class. |
## Fields

| Field | Description |
| --- | --- |
| [KIND](#KIND) | Type of the resource 'calendar\#colors'. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Palette of calendar colors, mapping from the color ID to its definition. |
| [getClass()](#getClass--) |  |
| [getEvent()](#getEvent--) | Palette of event colors, mapping from the color ID to its definition. |
| [getUpdated()](#getUpdated--) | Last modification time of the color palette. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setUpdated(Date value)](#setUpdated-java.util.Date-) | Last modification time of the color palette. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorsInfo() {#ColorsInfo--}
```
public ColorsInfo()
```


Initializes a new instance of the ColorsInfo class.

### ColorsInfo(Date updated, System.Collections.Generic.Dictionary<String,Colors> calendar, System.Collections.Generic.Dictionary<String,Colors> evnt) {#ColorsInfo-java.util.Date-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.email.Colors--com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.email.Colors--}
```
public ColorsInfo(Date updated, System.Collections.Generic.Dictionary<String,Colors> calendar, System.Collections.Generic.Dictionary<String,Colors> evnt)
```


Initializes a new instance of the ColorsInfo class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| updated | java.util.Date | Last modification time of the color palette. |
| calendar | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.email.Colors> | Palette of calendar colors, mapping from the color ID to its definition. |
| evnt | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.email.Colors> | Palette of event colors, mapping from the color ID to its definition. |

### KIND {#KIND}
```
public static final String KIND
```


Type of the resource 'calendar\#colors'.

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
### getCalendar() {#getCalendar--}
```
public final System.Collections.Generic.Dictionary<String,Colors> getCalendar()
```


Palette of calendar colors, mapping from the color ID to its definition. An 'calendarListEntry' resource refers to one of these color IDs in its 'color' field.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.email.Colors>
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEvent() {#getEvent--}
```
public final System.Collections.Generic.Dictionary<String,Colors> getEvent()
```


Palette of event colors, mapping from the color ID to its definition. An 'event' resource may refer to one of these color IDs in its 'color' field.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.email.Colors>
### getUpdated() {#getUpdated--}
```
public final Date getUpdated()
```


Last modification time of the color palette.

**Returns:**
java.util.Date
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




### setUpdated(Date value) {#setUpdated-java.util.Date-}
```
public final void setUpdated(Date value)
```


Last modification time of the color palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

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

