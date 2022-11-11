---
title: AppointmentQueryBuilder
second_title: Aspose.Email for Java API Reference
description: Represents the builder of search expression that used by Exchange protocol.
type: docs
weight: 42
url: /java/com.aspose.email/appointmentquerybuilder/
---
**Inheritance:**
java.lang.Object
```
public final class AppointmentQueryBuilder
```

Represents the builder of search expression that used by Exchange protocol.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEnd()](#getEnd--) | Gets the field that allows to find items with a specified End field. |
| [getEndTimeZoneId()](#getEndTimeZoneId--) | Gets the field that allows to find items with a specified EndTimeZoneId. |
| [getLocation()](#getLocation--) | Gets the field that allows to find items with a specified Location. |
| [getOriginalStart()](#getOriginalStart--) | Gets the field that allows to find items with a specified OriginalStart field. |
| [getStart()](#getStart--) | Gets the field that allows to find items with a specified Start field. |
| [getStartTimeZoneId()](#getStartTimeZoneId--) | Gets the field that allows to find items with a specified StartTimeZoneId. |
| [hashCode()](#hashCode--) |  |
| [isAllDayEvent()](#isAllDayEvent--) | Gets the field that allows to find AllDayEvent items. |
| [isCancelled()](#isCancelled--) | Gets the field that allows to find cancelled items. |
| [isMeeting()](#isMeeting--) | Gets the field that allows to find Meeting items. |
| [isOrganizer()](#isOrganizer--) | Gets the field that allows to find items where user is organizer. |
| [isRecurring()](#isRecurring--) | Gets the field that allows to find recurring items. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendarView(Date startDate, Date endDate, int maxEntriesReturned)](#setCalendarView-java.util.Date-java.util.Date-int-) | If the CalendarView is specified, the service returns a list of single calendar items and occurrences of recurring calendar items within the range specified by StartDate and EndDate. |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnd() {#getEnd--}
```
public final DateComparisonField getEnd()
```


Gets the field that allows to find items with a specified End field.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getEndTimeZoneId() {#getEndTimeZoneId--}
```
public final StringComparisonField getEndTimeZoneId()
```


Gets the field that allows to find items with a specified EndTimeZoneId.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getLocation() {#getLocation--}
```
public final StringComparisonField getLocation()
```


Gets the field that allows to find items with a specified Location.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getOriginalStart() {#getOriginalStart--}
```
public final DateComparisonField getOriginalStart()
```


Gets the field that allows to find items with a specified OriginalStart field.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getStart() {#getStart--}
```
public final DateComparisonField getStart()
```


Gets the field that allows to find items with a specified Start field.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getStartTimeZoneId() {#getStartTimeZoneId--}
```
public final StringComparisonField getStartTimeZoneId()
```


Gets the field that allows to find items with a specified StartTimeZoneId.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAllDayEvent() {#isAllDayEvent--}
```
public final BoolComparisonField isAllDayEvent()
```


Gets the field that allows to find AllDayEvent items.

**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
### isCancelled() {#isCancelled--}
```
public final BoolComparisonField isCancelled()
```


Gets the field that allows to find cancelled items.

**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
### isMeeting() {#isMeeting--}
```
public final BoolComparisonField isMeeting()
```


Gets the field that allows to find Meeting items.

**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
### isOrganizer() {#isOrganizer--}
```
public final BoolComparisonField isOrganizer()
```


Gets the field that allows to find items where user is organizer.

**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
### isRecurring() {#isRecurring--}
```
public final BoolComparisonField isRecurring()
```


Gets the field that allows to find recurring items.

**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCalendarView(Date startDate, Date endDate, int maxEntriesReturned) {#setCalendarView-java.util.Date-java.util.Date-int-}
```
public final void setCalendarView(Date startDate, Date endDate, int maxEntriesReturned)
```


If the CalendarView is specified, the service returns a list of single calendar items and occurrences of recurring calendar items within the range specified by StartDate and EndDate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startDate | java.util.Date | Identifies the start of a time span queried for calendar items. |
| endDate | java.util.Date | Identifies the end of a time span queried for calendar items. |
| maxEntriesReturned | int | Describes the maximum number of results. (Value <= 0 for all results) |

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

