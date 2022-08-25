---
title: MapiCalendarRecurrencePattern
second_title: Aspose.Email for Android via Java API Reference
description:  Represents the mapi recurrence pattern
type: docs
weight: 218
url: /java/com.aspose.email/mapicalendarrecurrencepattern/
---
**Inheritance:**
java.lang.Object
```
public abstract class MapiCalendarRecurrencePattern
```

Represents the mapi recurrence pattern
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiCalendarRecurrencePattern()](#MapiCalendarRecurrencePattern--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getStartDate()](#getStartDate--) | Gets or sets the start date of an item recurrence pattern. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Gets or sets the start date of an item recurrence pattern. |
| [getEndDate()](#getEndDate--) | Gets or sets Defines the end date of an item recurrence pattern. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Gets or sets Defines the end date of an item recurrence pattern. |
| [getPeriod()](#getPeriod--) | Gets or sets interval at which the meeting pattern repeats |
| [setPeriod(long value)](#setPeriod-long-) | Gets or sets interval at which the meeting pattern repeats |
| [getFrequency()](#getFrequency--) | Gets or sets the frequency of the recurring series. |
| [getWeekStartDay()](#getWeekStartDay--) | Gets or sets the first day of the calendar week. |
| [setWeekStartDay(int value)](#setWeekStartDay-int-) | Gets or sets the first day of the calendar week. |
| [getOccurrenceCount()](#getOccurrenceCount--) | Gets or sets the number of occurrences in a recurrence. |
| [setOccurrenceCount(long value)](#setOccurrenceCount-long-) | Gets or sets the number of occurrences in a recurrence. |
| [getPatternType()](#getPatternType--) | Gets or sets the type of recurrence pattern |
| [setPatternType(int value)](#setPatternType-int-) | Gets or sets the type of recurrence pattern |
| [getCalendarType()](#getCalendarType--) | Gets or sets the type of calendar that is used |
| [setCalendarType(int value)](#setCalendarType-int-) | Gets or sets the type of calendar that is used |
| [getEndType()](#getEndType--) | Gets or sets the ending type for the recurrence. |
| [setEndType(int value)](#setEndType-int-) | Gets or sets the ending type for the recurrence. |
| [getSlidingFlag()](#getSlidingFlag--) | Defines whether pattern is sliding or not. |
| [setSlidingFlag(boolean value)](#setSlidingFlag-boolean-) | Defines whether pattern is sliding or not. |
| [getExceptions()](#getExceptions--) | An exception specifies changes to an instance of a recurring series. |
| [getDeletedInstanceDates()](#getDeletedInstanceDates--) | An array of dates, each of which is the original instance date of either a deleted instance or a modified instance for this recurrence. |
| [getModifiedInstanceDates()](#getModifiedInstanceDates--) | An array of dates, each of which is the date of a modified instance. |
### MapiCalendarRecurrencePattern() {#MapiCalendarRecurrencePattern--}
```
public MapiCalendarRecurrencePattern()
```


### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets or sets the start date of an item recurrence pattern.

**Returns:**
java.util.Date
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Gets or sets the start date of an item recurrence pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Gets or sets Defines the end date of an item recurrence pattern.

**Returns:**
java.util.Date
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Gets or sets Defines the end date of an item recurrence pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getPeriod() {#getPeriod--}
```
public abstract long getPeriod()
```


Gets or sets interval at which the meeting pattern repeats

**Returns:**
long
### setPeriod(long value) {#setPeriod-long-}
```
public abstract void setPeriod(long value)
```


Gets or sets interval at which the meeting pattern repeats

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getFrequency() {#getFrequency--}
```
public int getFrequency()
```


Gets or sets the frequency of the recurring series.

**Returns:**
int
### getWeekStartDay() {#getWeekStartDay--}
```
public final int getWeekStartDay()
```


Gets or sets the first day of the calendar week.

**Returns:**
int
### setWeekStartDay(int value) {#setWeekStartDay-int-}
```
public final void setWeekStartDay(int value)
```


Gets or sets the first day of the calendar week.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getOccurrenceCount() {#getOccurrenceCount--}
```
public final long getOccurrenceCount()
```


Gets or sets the number of occurrences in a recurrence.

**Returns:**
long
### setOccurrenceCount(long value) {#setOccurrenceCount-long-}
```
public final void setOccurrenceCount(long value)
```


Gets or sets the number of occurrences in a recurrence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getPatternType() {#getPatternType--}
```
public final int getPatternType()
```


Gets or sets the type of recurrence pattern

**Returns:**
int
### setPatternType(int value) {#setPatternType-int-}
```
public final void setPatternType(int value)
```


Gets or sets the type of recurrence pattern

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCalendarType() {#getCalendarType--}
```
public final int getCalendarType()
```


Gets or sets the type of calendar that is used

**Returns:**
int
### setCalendarType(int value) {#setCalendarType-int-}
```
public final void setCalendarType(int value)
```


Gets or sets the type of calendar that is used

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEndType() {#getEndType--}
```
public final int getEndType()
```


Gets or sets the ending type for the recurrence.

**Returns:**
int
### setEndType(int value) {#setEndType-int-}
```
public final void setEndType(int value)
```


Gets or sets the ending type for the recurrence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlidingFlag() {#getSlidingFlag--}
```
public final boolean getSlidingFlag()
```


Defines whether pattern is sliding or not.

**Returns:**
boolean
### setSlidingFlag(boolean value) {#setSlidingFlag-boolean-}
```
public final void setSlidingFlag(boolean value)
```


Defines whether pattern is sliding or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExceptions() {#getExceptions--}
```
public final System.Collections.Generic.IGenericList<MapiCalendarExceptionInfo> getExceptions()
```


An exception specifies changes to an instance of a recurring series.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MapiCalendarExceptionInfo>
### getDeletedInstanceDates() {#getDeletedInstanceDates--}
```
public System.Collections.Generic.IGenericList<Date> getDeletedInstanceDates()
```


An array of dates, each of which is the original instance date of either a deleted instance or a modified instance for this recurrence.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.util.Date>
### getModifiedInstanceDates() {#getModifiedInstanceDates--}
```
public System.Collections.Generic.IGenericList<Date> getModifiedInstanceDates()
```


An array of dates, each of which is the date of a modified instance.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.util.Date>
