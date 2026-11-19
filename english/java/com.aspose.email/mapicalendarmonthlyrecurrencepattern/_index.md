---
title: MapiCalendarMonthlyRecurrencePattern
second_title: Aspose.Email for Java API Reference
description: A recurrence on a given day of every N months such as the 15th of every month.
type: docs
weight: 419
url: /java/com.aspose.email/mapicalendarmonthlyrecurrencepattern/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern), [com.aspose.email.MapiCalendarYearlyAndMonthlyRecurrencePattern](../../com.aspose.email/mapicalendaryearlyandmonthlyrecurrencepattern)
```
public class MapiCalendarMonthlyRecurrencePattern extends MapiCalendarYearlyAndMonthlyRecurrencePattern
```

A recurrence on a given day of every N months, such as "the 15th of every month".

Set the day with [MapiCalendarYearlyAndMonthlyRecurrencePattern.getDay()](../../com.aspose.email/mapicalendaryearlyandmonthlyrecurrencepattern\#getDay--) and the interval in months with [MapiCalendarYearlyAndMonthlyRecurrencePattern.getPeriod()](../../com.aspose.email/mapicalendaryearlyandmonthlyrecurrencepattern\#getPeriod--).
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiCalendarMonthlyRecurrencePattern()](#MapiCalendarMonthlyRecurrencePattern--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendarType()](#getCalendarType--) | Gets the calendar system of the recurrence. |
| [getClass()](#getClass--) |  |
| [getDay()](#getDay--) | Gets the day of the month the event occurs on. |
| [getDayOfWeek()](#getDayOfWeek--) | Gets the days of the week the event occurs on, for a recurrence on the Nth weekday of the month. |
| [getDeletedInstanceDates()](#getDeletedInstanceDates--) | Gets the original dates of the occurrences that were deleted or changed. |
| [getEndDate()](#getEndDate--) | Gets the date of the last occurrence, used when \#getEndType().getEndType() is  EndAfterDate . |
| [getEndType()](#getEndType--) | Gets how the series ends. |
| [getExceptions()](#getExceptions--) | Gets the exceptions of the series: the occurrences whose details were changed. |
| [getFrequency()](#getFrequency--) | Gets how often the series repeats:  Yearly  when [MapiCalendarWeeklyRecurrencePattern.getPeriod()](../../com.aspose.email/mapicalendarweeklyrecurrencepattern\#getPeriod--) is a multiple of 12, otherwise  Monthly . |
| [getModifiedInstanceDates()](#getModifiedInstanceDates--) | Gets the dates of the occurrences that were changed. |
| [getOccurrenceCount()](#getOccurrenceCount--) | Gets the number of occurrences, used when \#getEndType().getEndType() is  EndAfterNOccurrences . |
| [getPatternType()](#getPatternType--) | Gets the type of the recurrence pattern. |
| [getPeriod()](#getPeriod--) | Gets the interval of the recurrence, in months: 12 for a yearly recurrence. |
| [getPosition()](#getPosition--) | Gets which occurrence of [MapiCalendarWeeklyRecurrencePattern.getDayOfWeek()](../../com.aspose.email/mapicalendarweeklyrecurrencepattern\#getDayOfWeek--) in the month the event falls on, such as the second or the last. |
| [getSlidingFlag()](#getSlidingFlag--) | Gets a value indicating whether the next occurrence is calculated from the completion of the previous one rather than from a fixed schedule. |
| [getStartDate()](#getStartDate--) | Gets the date of the first occurrence. |
| [getWeekStartDay()](#getWeekStartDay--) | Gets the first day of the week. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendarType(int value)](#setCalendarType-int-) | Sets the calendar system of the recurrence. |
| [setDay(long value)](#setDay-long-) | Sets the day of the month the event occurs on. |
| [setDayOfWeek(int value)](#setDayOfWeek-int-) | Sets the days of the week the event occurs on, for a recurrence on the Nth weekday of the month. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Sets the date of the last occurrence, used when \#getEndType().getEndType() is  EndAfterDate . |
| [setEndType(int value)](#setEndType-int-) | Sets how the series ends. |
| [setOccurrenceCount(long value)](#setOccurrenceCount-long-) | Sets the number of occurrences, used when \#getEndType().getEndType() is  EndAfterNOccurrences . |
| [setPatternType(int value)](#setPatternType-int-) | Sets the type of the recurrence pattern. |
| [setPeriod(long value)](#setPeriod-long-) | Sets the interval of the recurrence, in months: 12 for a yearly recurrence. |
| [setPosition(int value)](#setPosition-int-) | Sets which occurrence of [MapiCalendarWeeklyRecurrencePattern.getDayOfWeek()](../../com.aspose.email/mapicalendarweeklyrecurrencepattern\#getDayOfWeek--) in the month the event falls on, such as the second or the last. |
| [setSlidingFlag(boolean value)](#setSlidingFlag-boolean-) | Sets a value indicating whether the next occurrence is calculated from the completion of the previous one rather than from a fixed schedule. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Sets the date of the first occurrence. |
| [setWeekStartDay(int value)](#setWeekStartDay-int-) | Sets the first day of the week. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendarMonthlyRecurrencePattern() {#MapiCalendarMonthlyRecurrencePattern--}
```
public MapiCalendarMonthlyRecurrencePattern()
```


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
### getCalendarType() {#getCalendarType--}
```
public final int getCalendarType()
```


Gets the calendar system of the recurrence.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDay() {#getDay--}
```
public final long getDay()
```


Gets the day of the month the event occurs on.

**Returns:**
long
### getDayOfWeek() {#getDayOfWeek--}
```
public final int getDayOfWeek()
```


Gets the days of the week the event occurs on, for a recurrence on the Nth weekday of the month.

**Returns:**
int
### getDeletedInstanceDates() {#getDeletedInstanceDates--}
```
public System.Collections.Generic.IGenericList<Date> getDeletedInstanceDates()
```


Gets the original dates of the occurrences that were deleted or changed.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.util.Date>
### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Gets the date of the last occurrence, used when \#getEndType().getEndType() is  EndAfterDate .

**Returns:**
java.util.Date
### getEndType() {#getEndType--}
```
public final int getEndType()
```


Gets how the series ends.

**Returns:**
int
### getExceptions() {#getExceptions--}
```
public final System.Collections.Generic.IGenericList<MapiCalendarExceptionInfo> getExceptions()
```


Gets the exceptions of the series: the occurrences whose details were changed.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MapiCalendarExceptionInfo>
### getFrequency() {#getFrequency--}
```
public int getFrequency()
```


Gets how often the series repeats:  Yearly  when [MapiCalendarWeeklyRecurrencePattern.getPeriod()](../../com.aspose.email/mapicalendarweeklyrecurrencepattern\#getPeriod--) is a multiple of 12, otherwise  Monthly .

**Returns:**
int
### getModifiedInstanceDates() {#getModifiedInstanceDates--}
```
public System.Collections.Generic.IGenericList<Date> getModifiedInstanceDates()
```


Gets the dates of the occurrences that were changed.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.util.Date>
### getOccurrenceCount() {#getOccurrenceCount--}
```
public final long getOccurrenceCount()
```


Gets the number of occurrences, used when \#getEndType().getEndType() is  EndAfterNOccurrences .

**Returns:**
long
### getPatternType() {#getPatternType--}
```
public final int getPatternType()
```


Gets the type of the recurrence pattern.

**Returns:**
int
### getPeriod() {#getPeriod--}
```
public long getPeriod()
```


Gets the interval of the recurrence, in months: 12 for a yearly recurrence.

**Returns:**
long
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Gets which occurrence of [MapiCalendarWeeklyRecurrencePattern.getDayOfWeek()](../../com.aspose.email/mapicalendarweeklyrecurrencepattern\#getDayOfWeek--) in the month the event falls on, such as the second or the last.

**Returns:**
int
### getSlidingFlag() {#getSlidingFlag--}
```
public final boolean getSlidingFlag()
```


Gets a value indicating whether the next occurrence is calculated from the completion of the previous one rather than from a fixed schedule. Used by recurring tasks.

**Returns:**
boolean
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets the date of the first occurrence.

**Returns:**
java.util.Date
### getWeekStartDay() {#getWeekStartDay--}
```
public final int getWeekStartDay()
```


Gets the first day of the week.

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




### setCalendarType(int value) {#setCalendarType-int-}
```
public final void setCalendarType(int value)
```


Sets the calendar system of the recurrence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDay(long value) {#setDay-long-}
```
public final void setDay(long value)
```


Sets the day of the month the event occurs on.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setDayOfWeek(int value) {#setDayOfWeek-int-}
```
public final void setDayOfWeek(int value)
```


Sets the days of the week the event occurs on, for a recurrence on the Nth weekday of the month.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Sets the date of the last occurrence, used when \#getEndType().getEndType() is  EndAfterDate .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setEndType(int value) {#setEndType-int-}
```
public final void setEndType(int value)
```


Sets how the series ends.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setOccurrenceCount(long value) {#setOccurrenceCount-long-}
```
public final void setOccurrenceCount(long value)
```


Sets the number of occurrences, used when \#getEndType().getEndType() is  EndAfterNOccurrences .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setPatternType(int value) {#setPatternType-int-}
```
public final void setPatternType(int value)
```


Sets the type of the recurrence pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPeriod(long value) {#setPeriod-long-}
```
public void setPeriod(long value)
```


Sets the interval of the recurrence, in months: 12 for a yearly recurrence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Sets which occurrence of [MapiCalendarWeeklyRecurrencePattern.getDayOfWeek()](../../com.aspose.email/mapicalendarweeklyrecurrencepattern\#getDayOfWeek--) in the month the event falls on, such as the second or the last.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSlidingFlag(boolean value) {#setSlidingFlag-boolean-}
```
public final void setSlidingFlag(boolean value)
```


Sets a value indicating whether the next occurrence is calculated from the completion of the previous one rather than from a fixed schedule. Used by recurring tasks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Sets the date of the first occurrence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setWeekStartDay(int value) {#setWeekStartDay-int-}
```
public final void setWeekStartDay(int value)
```


Sets the first day of the week.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

