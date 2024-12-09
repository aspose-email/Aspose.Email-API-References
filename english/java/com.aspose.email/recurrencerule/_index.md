---
title: RecurrenceRule
second_title: Aspose.Email for Java API Reference
description: Represents one recurrence or exception rule in a recurrence pattern.
type: docs
weight: 609
url: /java/com.aspose.email/recurrencerule/
---

**Inheritance:**
java.lang.Object
```
public class RecurrenceRule
```

Represents one recurrence or exception rule in a recurrence pattern.

--------------------

```
Corresponds to RRULE or EXRULE part in iCalendar.
 To construct a recurrence rule, you typically need to:
 1. Specify the type of the rule in ```
Frequency
```.
 2. Specify how the recurrence pattern ends using ```
EndType
```,
 ```
Count
``` or ```
Until
```.
 3. Specify values in one or more ByXXX collections.
 Note, that if ByXXX rule part values are found which are beyond the available
 scope (ie, BYMONTHDAY=30 in February), they are simply ignored.

 Information, not contained in the rule, necessary to determine the various recurrence instance 
 start time and dates are derived from ```
CalendarRecurrence.StartDate
```. For example,
 "FREQ=YEARLY;BYMONTH=1" doesn't specify a specific day within the month or a time. This information 
 would be the same as what is specified for DTSTART.

 ByXXX rule parts modify the recurrence in some manner. ByXXX rule parts for a period of time which is 
 the same or greater than the frequency generally reduce or limit the number of occurrences of the
 recurrence generated. For example, "FREQ=DAILY;BYMONTH=1" reduces the number of recurrence instances 
 from all days (if BYMONTH tag is not present) to all days in January. ByXXX rule parts for a period of
 time less than the frequency generally increase or expand the number of occurrences of the recurrence. 
 For example, "FREQ=YEARLY;BYMONTH=1,2" increases the number of days within the yearly recurrence set 
 from 1 (if BYMONTH tag is not present) to 2.

 If multiple ByXXX rule parts are specified, then after evaluating the specified Frequency and Interval
 rule parts, the ByXXX rule parts are applied to the current set of evaluated occurrences in the following
 order: ```
ByMonth
```, ```
ByWeekNo
```, ```
ByYearDay
```, ```
ByMonthDay
```, 
 ```
ByDay
```, ```
ByHour
```, ```
ByMinute
```, ```
BySecond
``` and 
 ```
BySetPos
```; then ```
Count
``` and ```
Until
``` are evaluated.
```
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
| [getCount()](#getCount--) | Gets or sets the count. |
| [getEndType()](#getEndType--) | Gets or sets the end type. |
| [getFrequency()](#getFrequency--) | Gets or sets the type of the recurrence rule. |
| [getFriendlyText()](#getFriendlyText--) | Gets user friendly text of rule. |
| [getInterval()](#getInterval--) | Gets or sets the interval. |
| [getUntil()](#getUntil--) | Gets or sets the until. |
| [getWeekStart()](#getWeekStart--) | Gets or sets the starting day of the week. |
| [hashCode()](#hashCode--) | GetHashCode returns a hash function for this object. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | Gets or sets the count. |
| [setEndType(int value)](#setEndType-int-) | Gets or sets the end type. |
| [setFrequency(int value)](#setFrequency-int-) | Gets or sets the type of the recurrence rule. |
| [setInterval(int value)](#setInterval-int-) | Gets or sets the interval. |
| [setUntil(Date value)](#setUntil-java.util.Date-) | Gets or sets the until. |
| [setWeekStart(int value)](#setWeekStart-int-) | Gets or sets the starting day of the week. |
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

Value: The by day.

**Returns:**
[ByDayCollection](../../com.aspose.email/bydaycollection)
### getByHour() {#getByHour--}
```
public final ByNumberCollection getByHour()
```


Gets the by hour.

Value: The by hour.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection)
### getByMinute() {#getByMinute--}
```
public final ByNumberCollection getByMinute()
```


Gets the by minute.

Value: The by minute.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection)
### getByMonth() {#getByMonth--}
```
public final ByNumberCollection getByMonth()
```


Gets the by month.

Value: The by month.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection)
### getByMonthDay() {#getByMonthDay--}
```
public final ByNumberCollection getByMonthDay()
```


Gets the by month day.

Value: The by month day.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection)
### getBySecond() {#getBySecond--}
```
public final ByNumberCollection getBySecond()
```


Gets the by second.

Value: The by second.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection)
### getBySetPos() {#getBySetPos--}
```
public final ByNumberCollection getBySetPos()
```


Gets the by set pos.

Value: The by set pos.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection)
### getByWeekNo() {#getByWeekNo--}
```
public final ByNumberCollection getByWeekNo()
```


Gets the by week no.

Value: The by week no.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection)
### getByYearDay() {#getByYearDay--}
```
public final ByNumberCollection getByYearDay()
```


Gets the by year day.

Value: The by year day.

**Returns:**
[ByNumberCollection](../../com.aspose.email/bynumbercollection)
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


Gets or sets the count.

Value: The count.

**Returns:**
int
### getEndType() {#getEndType--}
```
public final int getEndType()
```


Gets or sets the end type.

Value: The end type.

**Returns:**
int
### getFrequency() {#getFrequency--}
```
public final int getFrequency()
```


Gets or sets the type of the recurrence rule.

Value: The frequency.

**Returns:**
int
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


Gets or sets the interval.

Value: The interval.

**Returns:**
int
### getUntil() {#getUntil--}
```
public final Date getUntil()
```


Gets or sets the until.

Value: The until.

**Returns:**
java.util.Date
### getWeekStart() {#getWeekStart--}
```
public final int getWeekStart()
```


Gets or sets the starting day of the week.

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


Gets or sets the count.

Value: The count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEndType(int value) {#setEndType-int-}
```
public final void setEndType(int value)
```


Gets or sets the end type.

Value: The end type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setFrequency(int value) {#setFrequency-int-}
```
public final void setFrequency(int value)
```


Gets or sets the type of the recurrence rule.

Value: The frequency.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setInterval(int value) {#setInterval-int-}
```
public final void setInterval(int value)
```


Gets or sets the interval.

Value: The interval.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUntil(Date value) {#setUntil-java.util.Date-}
```
public final void setUntil(Date value)
```


Gets or sets the until.

Value: The until.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setWeekStart(int value) {#setWeekStart-int-}
```
public final void setWeekStart(int value)
```


Gets or sets the starting day of the week.

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

