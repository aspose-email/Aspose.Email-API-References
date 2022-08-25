---
title: FreebusyCalendarInfo
second_title: Aspose.Email for Java API Reference
description:  Defines list of free/busy information for specified calendar.
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
| [getCalendarId()](#getCalendarId--) | Calendar Id |
| [setCalendarId(String value)](#setCalendarId-java.lang.String-) | Calendar Id |
| [getErrors()](#getErrors--) | Optional error(s) (if computation for the calendar failed). |
| [getBusy()](#getBusy--) | List of time ranges during which this calendar should be regarded as busy. |
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
| errors | com.aspose.email.ErrorDetails[] | Optional error(s) (if computation for the calendar failed). |

### FreebusyCalendarInfo(String calendarId, Range[] busy) {#FreebusyCalendarInfo-java.lang.String-com.aspose.email.Range---}
```
public FreebusyCalendarInfo(String calendarId, Range[] busy)
```


Initializes a new instance of the FreebusyCalendarInfo class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarId | java.lang.String | Calendar Id |
| busy | com.aspose.email.Range[] | List of time ranges during which this calendar should be regarded as busy. |

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

### getCalendarId() {#getCalendarId--}
```
public final String getCalendarId()
```


Calendar Id

**Returns:**
java.lang.String
### setCalendarId(String value) {#setCalendarId-java.lang.String-}
```
public final void setCalendarId(String value)
```


Calendar Id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getErrors() {#getErrors--}
```
public final List<ErrorDetails> getErrors()
```


Optional error(s) (if computation for the calendar failed).

**Returns:**
java.util.List<com.aspose.email.ErrorDetails>
### getBusy() {#getBusy--}
```
public final List<Range> getBusy()
```


List of time ranges during which this calendar should be regarded as busy.

**Returns:**
java.util.List<com.aspose.email.Range>
