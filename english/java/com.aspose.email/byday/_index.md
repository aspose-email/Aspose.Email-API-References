---
title: ByDay
second_title: Aspose.Email for Java API Reference
description: Represents Nth occurrence or all occurrences of the specified day of the week.
type: docs
weight: 86
url: /java/com.aspose.email/byday/
---

**Inheritance:**
java.lang.Object
```
public class ByDay
```

Represents Nth occurrence (or all occurrences) of the specified day of the week.

--------------------



Corresponds to one day of the week specified in the BYDAY part of a recurrence rule.

 

Can be used in a monthly or yearly recurrence rule to specify Nth occurrence (or all occurrences) of the specified day of the week in a month or year.

 

BYDAY=MO represents all Mondays of the month or year. To represent all occurrences, set NthOccurrence to 0.

 

BYDAY=2MO represents 2nd Monday in a month or year.

 

BYDAY=-1MO represents the last Monday of a month or year.


## Constructors

| Constructor | Description |
| --- | --- |
| [ByDay(int dayOfWeek)](#ByDay-int-) | Initializes a new instance of ByDay class. |
| [ByDay(int nthOccurrence, int dayOfWeek)](#ByDay-int-int-) | Initializes a new instance of ByDay class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to the current Object. |
| [getClass()](#getClass--) |  |
| [getDayOfWeek()](#getDayOfWeek--) | Gets or sets the day of the week. |
| [getNthOccurrence()](#getNthOccurrence--) | Gets or sets the nth occurrence of the day of the week. |
| [hashCode()](#hashCode--) | GetHashCode returns a hash function for this object. |
| [isAllOccurrences()](#isAllOccurrences--) | Returns True when NthOccurrence is zero (meaning all occurrences of this day of week). |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDayOfWeek(int value)](#setDayOfWeek-int-) | Gets or sets the day of the week. |
| [setNthOccurrence(int value)](#setNthOccurrence-int-) | Gets or sets the nth occurrence of the day of the week. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ByDay(int dayOfWeek) {#ByDay-int-}
```
public ByDay(int dayOfWeek)
```


Initializes a new instance of ByDay class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dayOfWeek | int | A day of the week. |

### ByDay(int nthOccurrence, int dayOfWeek) {#ByDay-int-int-}
```
public ByDay(int nthOccurrence, int dayOfWeek)
```


Initializes a new instance of ByDay class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nthOccurrence | int | The nth occurrence of the day of the week. |
| dayOfWeek | int | A day of the week. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDayOfWeek() {#getDayOfWeek--}
```
public final int getDayOfWeek()
```


Gets or sets the day of the week.

**Returns:**
int
### getNthOccurrence() {#getNthOccurrence--}
```
public final int getNthOccurrence()
```


Gets or sets the nth occurrence of the day of the week.

--------------------



Valid range for this property is from -53 to 53.

 

Positive values represent Nth occurrence from the beginning of the period, for example NthOccurrence = 1, represents 1st occurrence of the day of the week.

 

Negative values represent Nth occurrence from the end of the period, for example NthOccurrence = -1, represents last occurrence of the day of the week.

 

When NthOccurrence is zero, it represents all occurrences of the specified day of the week. For example, BYDAY=MO has NthOccurrence zero and represents all Mondays in the set.



**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode returns a hash function for this object.

**Returns:**
int - Returns a hash function for this object.
### isAllOccurrences() {#isAllOccurrences--}
```
public final boolean isAllOccurrences()
```


Returns True when NthOccurrence is zero (meaning all occurrences of this day of week).

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDayOfWeek(int value) {#setDayOfWeek-int-}
```
public final void setDayOfWeek(int value)
```


Gets or sets the day of the week.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setNthOccurrence(int value) {#setNthOccurrence-int-}
```
public final void setNthOccurrence(int value)
```


Gets or sets the nth occurrence of the day of the week.

--------------------



Valid range for this property is from -53 to 53.

 

Positive values represent Nth occurrence from the beginning of the period, for example NthOccurrence = 1, represents 1st occurrence of the day of the week.

 

Negative values represent Nth occurrence from the end of the period, for example NthOccurrence = -1, represents last occurrence of the day of the week.

 

When NthOccurrence is zero, it represents all occurrences of the specified day of the week. For example, BYDAY=MO has NthOccurrence zero and represents all Mondays in the set.



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

