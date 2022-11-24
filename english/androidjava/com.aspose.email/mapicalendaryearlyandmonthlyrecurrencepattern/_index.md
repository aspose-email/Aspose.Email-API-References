---
title: MapiCalendarYearlyAndMonthlyRecurrencePattern
second_title: Aspose.Email for Android via Java API Reference
description: Represents the yearly and monthly recurrence pattern of the mapi calendar
type: docs
weight: 232
url: /androidjava/com.aspose.email/mapicalendaryearlyandmonthlyrecurrencepattern/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiCalendarRecurrencePattern](../../com.aspose.email/mapicalendarrecurrencepattern)
```
public class MapiCalendarYearlyAndMonthlyRecurrencePattern extends MapiCalendarRecurrencePattern
```

Represents the yearly and monthly recurrence pattern of the mapi calendar
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiCalendarYearlyAndMonthlyRecurrencePattern()](#MapiCalendarYearlyAndMonthlyRecurrencePattern--) | Initializes a new instance of the [MapiCalendarYearlyAndMonthlyRecurrencePattern](../../com.aspose.email/mapicalendaryearlyandmonthlyrecurrencepattern) class |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendarType()](#getCalendarType--) | Gets or sets the type of calendar that is used |
| [getClass()](#getClass--) |  |
| [getDay()](#getDay--) | Gets or sets day of the month on which the recurrence falls. |
| [getDayOfWeek()](#getDayOfWeek--) | Gets or sets the days of week at which the event occurs |
| [getDeletedInstanceDates()](#getDeletedInstanceDates--) | An array of dates, each of which is the original instance date of either a deleted instance or a modified instance for this recurrence. |
| [getEndDate()](#getEndDate--) | Gets or sets Defines the end date of an item recurrence pattern. |
| [getEndType()](#getEndType--) | Gets or sets the ending type for the recurrence. |
| [getExceptions()](#getExceptions--) | An exception specifies changes to an instance of a recurring series. |
| [getFrequency()](#getFrequency--) | Gets or sets the frequency of the recurring series. |
| [getModifiedInstanceDates()](#getModifiedInstanceDates--) | An array of dates, each of which is the date of a modified instance. |
| [getOccurrenceCount()](#getOccurrenceCount--) | Gets or sets the number of occurrences in a recurrence. |
| [getPatternType()](#getPatternType--) | Gets or sets the type of recurrence pattern |
| [getPeriod()](#getPeriod--) | Gets or sets interval (in months) at which the meeting pattern repeats |
| [getPosition()](#getPosition--) | Gets or sets the occurrence of the recurrence's days in each month in which the recurrence falls. |
| [getSlidingFlag()](#getSlidingFlag--) | Defines whether pattern is sliding or not. |
| [getStartDate()](#getStartDate--) | Gets or sets the start date of an item recurrence pattern. |
| [getWeekStartDay()](#getWeekStartDay--) | Gets or sets the first day of the calendar week. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendarType(int value)](#setCalendarType-int-) | Gets or sets the type of calendar that is used |
| [setDay(long value)](#setDay-long-) | Gets or sets day of the month on which the recurrence falls. |
| [setDayOfWeek(int value)](#setDayOfWeek-int-) | Gets or sets the days of week at which the event occurs |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Gets or sets Defines the end date of an item recurrence pattern. |
| [setEndType(int value)](#setEndType-int-) | Gets or sets the ending type for the recurrence. |
| [setOccurrenceCount(long value)](#setOccurrenceCount-long-) | Gets or sets the number of occurrences in a recurrence. |
| [setPatternType(int value)](#setPatternType-int-) | Gets or sets the type of recurrence pattern |
| [setPeriod(long value)](#setPeriod-long-) | Gets or sets interval (in months) at which the meeting pattern repeats |
| [setPosition(int value)](#setPosition-int-) | Gets or sets the occurrence of the recurrence's days in each month in which the recurrence falls. |
| [setSlidingFlag(boolean value)](#setSlidingFlag-boolean-) | Defines whether pattern is sliding or not. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Gets or sets the start date of an item recurrence pattern. |
| [setWeekStartDay(int value)](#setWeekStartDay-int-) | Gets or sets the first day of the calendar week. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendarYearlyAndMonthlyRecurrencePattern() {#MapiCalendarYearlyAndMonthlyRecurrencePattern--}
```
public MapiCalendarYearlyAndMonthlyRecurrencePattern()
```


Initializes a new instance of the [MapiCalendarYearlyAndMonthlyRecurrencePattern](../../com.aspose.email/mapicalendaryearlyandmonthlyrecurrencepattern) class

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


Gets or sets the type of calendar that is used

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


Gets or sets day of the month on which the recurrence falls.

**Returns:**
long
### getDayOfWeek() {#getDayOfWeek--}
```
public final int getDayOfWeek()
```


Gets or sets the days of week at which the event occurs

**Returns:**
int
### getDeletedInstanceDates() {#getDeletedInstanceDates--}
```
public System.Collections.Generic.IGenericList<Date> getDeletedInstanceDates()
```


An array of dates, each of which is the original instance date of either a deleted instance or a modified instance for this recurrence.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.util.Date>
### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Gets or sets Defines the end date of an item recurrence pattern.

**Returns:**
java.util.Date
### getEndType() {#getEndType--}
```
public final int getEndType()
```


Gets or sets the ending type for the recurrence.

**Returns:**
int
### getExceptions() {#getExceptions--}
```
public final System.Collections.Generic.IGenericList<MapiCalendarExceptionInfo> getExceptions()
```


An exception specifies changes to an instance of a recurring series.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MapiCalendarExceptionInfo>
### getFrequency() {#getFrequency--}
```
public int getFrequency()
```


Gets or sets the frequency of the recurring series.

**Returns:**
int
### getModifiedInstanceDates() {#getModifiedInstanceDates--}
```
public System.Collections.Generic.IGenericList<Date> getModifiedInstanceDates()
```


An array of dates, each of which is the date of a modified instance.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.util.Date>
### getOccurrenceCount() {#getOccurrenceCount--}
```
public final long getOccurrenceCount()
```


Gets or sets the number of occurrences in a recurrence.

**Returns:**
long
### getPatternType() {#getPatternType--}
```
public final int getPatternType()
```


Gets or sets the type of recurrence pattern

**Returns:**
int
### getPeriod() {#getPeriod--}
```
public long getPeriod()
```


Gets or sets interval (in months) at which the meeting pattern repeats

**Returns:**
long
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Gets or sets the occurrence of the recurrence's days in each month in which the recurrence falls.

**Returns:**
int
### getSlidingFlag() {#getSlidingFlag--}
```
public final boolean getSlidingFlag()
```


Defines whether pattern is sliding or not.

**Returns:**
boolean
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets or sets the start date of an item recurrence pattern.

**Returns:**
java.util.Date
### getWeekStartDay() {#getWeekStartDay--}
```
public final int getWeekStartDay()
```


Gets or sets the first day of the calendar week.

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


Gets or sets the type of calendar that is used

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDay(long value) {#setDay-long-}
```
public final void setDay(long value)
```


Gets or sets day of the month on which the recurrence falls.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setDayOfWeek(int value) {#setDayOfWeek-int-}
```
public final void setDayOfWeek(int value)
```


Gets or sets the days of week at which the event occurs

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | Flags attribute [MapiCalendarDayOfWeek](../../com.aspose.email/mapicalendardayofweek).

*For example:*
 MapiCalendarDayOfWeek.Wednesday | MapiCalendarDayOfWeek.Thursday  |

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Gets or sets Defines the end date of an item recurrence pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setEndType(int value) {#setEndType-int-}
```
public final void setEndType(int value)
```


Gets or sets the ending type for the recurrence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setOccurrenceCount(long value) {#setOccurrenceCount-long-}
```
public final void setOccurrenceCount(long value)
```


Gets or sets the number of occurrences in a recurrence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setPatternType(int value) {#setPatternType-int-}
```
public final void setPatternType(int value)
```


Gets or sets the type of recurrence pattern

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPeriod(long value) {#setPeriod-long-}
```
public void setPeriod(long value)
```


Gets or sets interval (in months) at which the meeting pattern repeats

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Gets or sets the occurrence of the recurrence's days in each month in which the recurrence falls.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSlidingFlag(boolean value) {#setSlidingFlag-boolean-}
```
public final void setSlidingFlag(boolean value)
```


Defines whether pattern is sliding or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Gets or sets the start date of an item recurrence pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setWeekStartDay(int value) {#setWeekStartDay-int-}
```
public final void setWeekStartDay(int value)
```


Gets or sets the first day of the calendar week.

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

