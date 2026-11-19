---
title: RecurrenceRule
second_title: Aspose.Email for Java API Reference
description: Represents one recurrence or exception rule in a recurrence pattern.
type: docs
weight: 625
url: /java/com.aspose.email/recurrencerule/
---

**Inheritance:**
java.lang.Object
```
public class RecurrenceRule
```

Represents one recurrence or exception rule in a recurrence pattern.

Corresponds to RRULE or EXRULE part in iCalendar.

To construct a recurrence rule, you typically need to:

1. Specify the type of the rule in [Frequency](../../com.aspose.email/frequency).

2. Specify how the recurrence pattern ends using [EndType](../../com.aspose.email/endtype), \#getCount().getCount() or \#getUntil().getUntil().

3. Specify values in one or more ByXXX collections.

Note, that if ByXXX rule part values are found which are beyond the available scope (ie, BYMONTHDAY=30 in February), they are simply ignored.

Information, not contained in the rule, necessary to determine the various recurrence instance start time and dates are derived from [CalendarRecurrence.getStartDate()](../../com.aspose.email/calendarrecurrence\#getStartDate--). For example, "FREQ=YEARLY;BYMONTH=1" doesn't specify a specific day within the month or a time. This information would be the same as what is specified for DTSTART.

ByXXX rule parts modify the recurrence in some manner. ByXXX rule parts for a period of time which is the same or greater than the frequency generally reduce or limit the number of occurrences of the recurrence generated. For example, "FREQ=DAILY;BYMONTH=1" reduces the number of recurrence instances from all days (if BYMONTH tag is not present) to all days in January. ByXXX rule parts for a period of time less than the frequency generally increase or expand the number of occurrences of the recurrence. For example, "FREQ=YEARLY;BYMONTH=1,2" increases the number of days within the yearly recurrence set from 1 (if BYMONTH tag is not present) to 2.

If multiple ByXXX rule parts are specified, then after evaluating the specified Frequency and Interval rule parts, the ByXXX rule parts are applied to the current set of evaluated occurrences in the following order: \#getByMonth().getByMonth(), \#getByWeekNo().getByWeekNo(), \#getByYearDay().getByYearDay(), \#getByMonthDay().getByMonthDay(), [ByDay](../../com.aspose.email/byday), \#getByHour().getByHour(), \#getByMinute().getByMinute(), \#getBySecond().getBySecond() and \#getBySetPos().getBySetPos(); then \#getCount().getCount() and \#getUntil().getUntil() are evaluated.
## Constructors

| Constructor | Description |
| --- | --- |
| [RecurrenceRule()](#RecurrenceRule--) | Initializes a new instance of the [RecurrenceRule](../../com.aspose.email/recurrencerule) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(RecurrenceRule other)](#equals-com.aspose.email.RecurrenceRule-) | Determines whether the specified [RecurrenceRule](../../com.aspose.email/recurrencerule) is equal to this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to the current Object. |
| [getByDay()](#getByDay--) | Gets the by day. |
| [getByHour()](#getByHour--) | Gets the by hour. |
| [getByMinute()](#getByMinute--) | Gets the by minute. |
| [getByMonth()](#getByMonth--) | Gets the by month. |
| [getByMonthDay()](#getByMonthDay--) | Gets the by month day. |
| [getBySecond()](#getBySecond--) | Gets the by second. |
| [getBySetPos()](#getBySetPos--) | Gets the by set pos. |
| [getByWeekNo()](#getByWeekNo--) | Gets the by week no. |
| [getByYearDay()](#getByYearDay--) | Gets the by year day. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the count. |
| [getEndType()](#getEndType--) | Gets the end type. |
| [getFrequency()](#getFrequency--) | Gets the type of the recurrence rule. |
| [getFriendlyText()](#getFriendlyText--) | Gets user friendly text of rule. |
| [getInterval()](#getInterval--) | Gets the interval. |
| [getUntil()](#getUntil--) | Gets the until. |
| [getWeekStart()](#getWeekStart--) | Gets the starting day of the week. |
| [hashCode()](#hashCode--) | GetHashCode returns a hash function for this object. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | Sets the count. |
| [setEndType(int value)](#setEndType-int-) | Sets the end type. |
| [setFrequency(int value)](#setFrequency-int-) | Sets the type of the recurrence rule. |
| [setInterval(int value)](#setInterval-int-) | Sets the interval. |
| [setUntil(Date value)](#setUntil-java.util.Date-) | Sets the until. |
| [setWeekStart(int value)](#setWeekStart-int-) | Sets the starting day of the week. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RecurrenceRule() {#RecurrenceRule--}
```
public RecurrenceRule()
```


Initializes a new instance of the [RecurrenceRule](../../com.aspose.email/recurrencerule) class.

### equals(RecurrenceRule other) {#equals-com.aspose.email.RecurrenceRule-}
```
public boolean equals(RecurrenceRule other)
```


Determines whether the specified [RecurrenceRule](../../com.aspose.email/recurrencerule) is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [RecurrenceRule](../../com.aspose.email/recurrencerule) | The [RecurrenceRule](../../com.aspose.email/recurrencerule) to compare with this instance. |

**Returns:**
boolean -  true  if the specified [RecurrenceRule](../../com.aspose.email/recurrencerule) is equal to this instance; otherwise,  false .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified Object is equal to the current Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Object to compare with the current Object. |

**Returns:**
boolean - Returns a boolean indicating if the passed in object obj is Equal to this.
### getByDay() {#getByDay--}
```
public final ByDayCollection getByDay()
```


Gets the by day.

**Returns:**
[ByDayCollection](../../com.aspose.email/bydaycollection) - The by day.
### getByHour() {#getByHour--}
```
public final ByNumberCollection getByHour()
```


Gets the by hour.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection) - The by hour.
### getByMinute() {#getByMinute--}
```
public final ByNumberCollection getByMinute()
```


Gets the by minute.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection) - The by minute.
### getByMonth() {#getByMonth--}
```
public final ByNumberCollection getByMonth()
```


Gets the by month.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection) - The by month.
### getByMonthDay() {#getByMonthDay--}
```
public final ByNumberCollection getByMonthDay()
```


Gets the by month day.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection) - The by month day.
### getBySecond() {#getBySecond--}
```
public final ByNumberCollection getBySecond()
```


Gets the by second.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection) - The by second.
### getBySetPos() {#getBySetPos--}
```
public final ByNumberCollection getBySetPos()
```


Gets the by set pos.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection) - The by set pos.
### getByWeekNo() {#getByWeekNo--}
```
public final ByNumberCollection getByWeekNo()
```


Gets the by week no.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection) - The by week no.
### getByYearDay() {#getByYearDay--}
```
public final ByNumberCollection getByYearDay()
```


Gets the by year day.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection) - The by year day.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public final int getCount()
```


Gets the count.

**Returns:**
int - The count.
### getEndType() {#getEndType--}
```
public final int getEndType()
```


Gets the end type.

**Returns:**
int - The end type.
### getFrequency() {#getFrequency--}
```
public final int getFrequency()
```


Gets the type of the recurrence rule.

**Returns:**
int - The frequency.
### getFriendlyText() {#getFriendlyText--}
```
public final String getFriendlyText()
```


Gets user friendly text of rule.

**Returns:**
java.lang.String
### getInterval() {#getInterval--}
```
public final int getInterval()
```


Gets the interval.

**Returns:**
int - The interval.
### getUntil() {#getUntil--}
```
public final Date getUntil()
```


Gets the until.

**Returns:**
java.util.Date - The until.
### getWeekStart() {#getWeekStart--}
```
public final int getWeekStart()
```


Gets the starting day of the week.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode returns a hash function for this object.

**Returns:**
int - Returns a hash function for this object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCount(int value) {#setCount-int-}
```
public final void setCount(int value)
```


Sets the count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The count. |

### setEndType(int value) {#setEndType-int-}
```
public final void setEndType(int value)
```


Sets the end type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The end type. |

### setFrequency(int value) {#setFrequency-int-}
```
public final void setFrequency(int value)
```


Sets the type of the recurrence rule.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The frequency. |

### setInterval(int value) {#setInterval-int-}
```
public final void setInterval(int value)
```


Sets the interval.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The interval. |

### setUntil(Date value) {#setUntil-java.util.Date-}
```
public final void setUntil(Date value)
```


Sets the until.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The until. |

### setWeekStart(int value) {#setWeekStart-int-}
```
public final void setWeekStart(int value)
```


Sets the starting day of the week.

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

