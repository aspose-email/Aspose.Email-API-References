---
title: TaskRegeneratingPattern
second_title: Aspose.Email for Java API Reference
description: Represents the regenerating recurrence pattern that specifies how many days weeks months or years  after the completion of the current task the next occurrence will be due.
type: docs
weight: 709
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
| [getEndDate()](#getEndDate--) | Gets the end date. |
| [getInterval()](#getInterval--) | Gets the number of recurrence units. |
| [getOccurs()](#getOccurs--) | Gets the number of occurrences of the recurrence pattern. |
| [getRegeneratingType()](#getRegeneratingType--) | Gets or sets a type of regenerating pattern. |
| [getWeekStart()](#getWeekStart--) | Gets the week start. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Sets the end date. |
| [setInterval(int value)](#setInterval-int-) | Sets the number of recurrence units. |
| [setOccurs(int value)](#setOccurs-int-) | Sets the number of occurrences of the recurrence pattern. |
| [setRegeneratingType(int value)](#setRegeneratingType-int-) | Gets or sets a type of regenerating pattern. |
| [setWeekStart(int value)](#setWeekStart-int-) | Sets the week start. |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [to_RecurrencePattern(String value)](#to-RecurrencePattern-java.lang.String-) | Converts string representation of recurrence pattern in ICalendar format to object. |
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


Gets the end date.

**Returns:**
java.util.Date - The end date.
### getInterval() {#getInterval--}
```
public final int getInterval()
```


Gets the number of recurrence units.

**Returns:**
int - The number of recurrence units.
### getOccurs() {#getOccurs--}
```
public final int getOccurs()
```


Gets the number of occurrences of the recurrence pattern.

**Returns:**
int - The number of occurrences.
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


Gets the week start.

**Returns:**
int - The week start.
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


Sets the end date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The end date. |

### setInterval(int value) {#setInterval-int-}
```
public final void setInterval(int value)
```


Sets the number of recurrence units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The number of recurrence units. |

### setOccurs(int value) {#setOccurs-int-}
```
public final void setOccurs(int value)
```


Sets the number of occurrences of the recurrence pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The number of occurrences. |

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


Sets the week start.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The week start. |

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


Converts string representation of recurrence pattern in ICalendar format to object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Returns RecurrencePattern object. |

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

