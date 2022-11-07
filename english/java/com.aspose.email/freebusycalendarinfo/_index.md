---
title: FreebusyCalendarInfo
second_title: Aspose.Email for Java API Reference
description: Defines list of free/busy information for specified calendar.
type: docs
weight: 265
url: /java/com.aspose.email/freebusycalendarinfo/
---
**Inheritance:**
java.lang.Object
```
public class FreebusyCalendarInfo
```

Defines list of free/busy information for specified calendar.
## Constructors

| Constructor | Description |
| --- | --- |
| [FreebusyCalendarInfo()](#FreebusyCalendarInfo--) | Initializes a new instance of the FreebusyCalendarInfo class. |
| [FreebusyCalendarInfo(String calendarId, ErrorDetails[] errors)](#FreebusyCalendarInfo-java.lang.String-com.aspose.email.ErrorDetails---) | Initializes a new instance of the FreebusyCalendarInfo class. |
| [FreebusyCalendarInfo(String calendarId, Range[] busy)](#FreebusyCalendarInfo-java.lang.String-com.aspose.email.Range---) | Initializes a new instance of the FreebusyCalendarInfo class. |
| [FreebusyCalendarInfo(String calendarId, Iterable<ErrorDetails> errors, Iterable<Range> busy)](#FreebusyCalendarInfo-java.lang.String-java.lang.Iterable-com.aspose.email.ErrorDetails--java.lang.Iterable-com.aspose.email.Range--) | Initializes a new instance of the FreebusyCalendarInfo class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBusy()](#getBusy--) | List of time ranges during which this calendar should be regarded as busy. |
| [getCalendarId()](#getCalendarId--) | Calendar Id |
| [getClass()](#getClass--) |  |
| [getErrors()](#getErrors--) | Optional error(s) (if computation for the calendar failed). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendarId(String value)](#setCalendarId-java.lang.String-) | Calendar Id |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FreebusyCalendarInfo() {#FreebusyCalendarInfo--}
```
public FreebusyCalendarInfo()
```


Initializes a new instance of the FreebusyCalendarInfo class.

### FreebusyCalendarInfo(String calendarId, ErrorDetails[] errors) {#FreebusyCalendarInfo-java.lang.String-com.aspose.email.ErrorDetails---}
```
public FreebusyCalendarInfo(String calendarId, ErrorDetails[] errors)
```


Initializes a new instance of the FreebusyCalendarInfo class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar Id |
| errors | [ErrorDetails\[\]](../../com.aspose.email/errordetails) | Optional error(s) (if computation for the calendar failed). |

### FreebusyCalendarInfo(String calendarId, Range[] busy) {#FreebusyCalendarInfo-java.lang.String-com.aspose.email.Range---}
```
public FreebusyCalendarInfo(String calendarId, Range[] busy)
```


Initializes a new instance of the FreebusyCalendarInfo class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar Id |
| busy | [Range\[\]](../../com.aspose.email/range) | List of time ranges during which this calendar should be regarded as busy. |

### FreebusyCalendarInfo(String calendarId, Iterable<ErrorDetails> errors, Iterable<Range> busy) {#FreebusyCalendarInfo-java.lang.String-java.lang.Iterable-com.aspose.email.ErrorDetails--java.lang.Iterable-com.aspose.email.Range--}
```
public FreebusyCalendarInfo(String calendarId, Iterable<ErrorDetails> errors, Iterable<Range> busy)
```


Initializes a new instance of the FreebusyCalendarInfo class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar Id |
| errors | java.lang.Iterable<com.aspose.email.ErrorDetails> | Optional error(s) (if computation for the calendar failed). |
| busy | java.lang.Iterable<com.aspose.email.Range> | List of time ranges during which this calendar should be regarded as busy. |

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
### getBusy() {#getBusy--}
```
public final List<Range> getBusy()
```


List of time ranges during which this calendar should be regarded as busy.

**Returns:**
java.util.List<com.aspose.email.Range>
### getCalendarId() {#getCalendarId--}
```
public final String getCalendarId()
```


Calendar Id

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrors() {#getErrors--}
```
public final List<ErrorDetails> getErrors()
```


Optional error(s) (if computation for the calendar failed).

**Returns:**
java.util.List<com.aspose.email.ErrorDetails>
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




### setCalendarId(String value) {#setCalendarId-java.lang.String-}
```
public final void setCalendarId(String value)
```


Calendar Id

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

