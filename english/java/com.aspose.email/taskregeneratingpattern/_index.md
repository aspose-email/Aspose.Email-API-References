---
title: TaskRegeneratingPattern
second_title: Aspose.Email for Java API Reference
description: Represents the regenerating recurrence pattern that specifies how many days weeks months or years  after the completion of the current task the next occurrence will be due.
type: docs
weight: 663
url: /java/com.aspose.email/taskregeneratingpattern/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.RecurrencePattern](../../com.aspose.email/recurrencepattern)
```
public final class TaskRegeneratingPattern extends RecurrencePattern
```

Represents the regenerating recurrence pattern that specifies how many days, weeks, months or years after the completion of the current task the next occurrence will be due.
## Constructors

| Constructor | Description |
| --- | --- |
| [TaskRegeneratingPattern(int type, int interval)](#TaskRegeneratingPattern-int-int-) | Initializes a new instance of the [TaskRegeneratingPattern](../../com.aspose.email/taskregeneratingpattern) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEndDate()](#getEndDate--) | Gets or sets the end date. |
| [getInterval()](#getInterval--) | Gets or sets the number of recurrence units. |
| [getOccurs()](#getOccurs--) | Gets or sets the number of occurrences of the recurrence pattern. |
| [getRegeneratingType()](#getRegeneratingType--) | Gets or sets a type of regenerating pattern. |
| [getWeekStart()](#getWeekStart--) | Gets or sets the week start. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Gets or sets the end date. |
| [setInterval(int value)](#setInterval-int-) | Gets or sets the number of recurrence units. |
| [setOccurs(int value)](#setOccurs-int-) | Gets or sets the number of occurrences of the recurrence pattern. |
| [setRegeneratingType(int value)](#setRegeneratingType-int-) | Gets or sets a type of regenerating pattern. |
| [setWeekStart(int value)](#setWeekStart-int-) | Gets or sets the week start. |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [to_RecurrencePattern(String value)](#to-RecurrencePattern-java.lang.String-) | Converts string representation of recurrence pattern in ICalendar format to object |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TaskRegeneratingPattern(int type, int interval) {#TaskRegeneratingPattern-int-int-}
```
public TaskRegeneratingPattern(int type, int interval)
```


Initializes a new instance of the [TaskRegeneratingPattern](../../com.aspose.email/taskregeneratingpattern) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Specifies the type of regenerating pattern. |
| interval | int | Specifies how many days, weeks, months or years after the completion of the current task the next occurrence will be due. |

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
### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Gets or sets the end date.

Value: The end date.

**Returns:**
java.util.Date
### getInterval() {#getInterval--}
```
public final int getInterval()
```


Gets or sets the number of recurrence units.

Value: The number of recurrence units.

**Returns:**
int
### getOccurs() {#getOccurs--}
```
public final int getOccurs()
```


Gets or sets the number of occurrences of the recurrence pattern.

Value: The number of occurrences.

**Returns:**
int
### getRegeneratingType() {#getRegeneratingType--}
```
public final int getRegeneratingType()
```


Gets or sets a type of regenerating pattern.

**Returns:**
int
### getWeekStart() {#getWeekStart--}
```
public final int getWeekStart()
```


Gets or sets the week start.

Value: The week start.

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




### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Gets or sets the end date.

Value: The end date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setInterval(int value) {#setInterval-int-}
```
public final void setInterval(int value)
```


Gets or sets the number of recurrence units.

Value: The number of recurrence units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setOccurs(int value) {#setOccurs-int-}
```
public final void setOccurs(int value)
```


Gets or sets the number of occurrences of the recurrence pattern.

Value: The number of occurrences.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRegeneratingType(int value) {#setRegeneratingType-int-}
```
public final void setRegeneratingType(int value)
```


Gets or sets a type of regenerating pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setWeekStart(int value) {#setWeekStart-int-}
```
public final void setWeekStart(int value)
```


Gets or sets the week start.

Value: The week start.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
### to_RecurrencePattern(String value) {#to-RecurrencePattern-java.lang.String-}
```
public static RecurrencePattern to_RecurrencePattern(String value)
```


Converts string representation of recurrence pattern in ICalendar format to object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Returns RecurrencePattern object |

**Returns:**
[RecurrencePattern](../../com.aspose.email/recurrencepattern)
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

