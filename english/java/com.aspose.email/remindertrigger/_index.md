---
title: ReminderTrigger
second_title: Aspose.Email for Java API Reference
description: Specifies when an alarm will trigger.
type: docs
weight: 611
url: /java/com.aspose.email/remindertrigger/
---

**Inheritance:**
java.lang.Object
```
public class ReminderTrigger
```

Specifies when an alarm will trigger.
## Constructors

| Constructor | Description |
| --- | --- |
| [ReminderTrigger(Date dateTime)](#ReminderTrigger-java.util.Date-) | Initialize a new instance of [ReminderTrigger](../../com.aspose.email/remindertrigger) class. |
| [ReminderTrigger(ReminderDuration duration, int related)](#ReminderTrigger-com.aspose.email.ReminderDuration-int-) | Initialize a new instance of [ReminderTrigger](../../com.aspose.email/remindertrigger) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDateTime()](#getDateTime--) | A trigger set to an absolute date/time. |
| [getDuration()](#getDuration--) | Specifies a relative time for the trigger of the alarm. |
| [getRelated()](#getRelated--) | Specify the relationship of the alarm trigger with respect to the start or end of the event. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDateTime(Date value)](#setDateTime-java.util.Date-) | A trigger set to an absolute date/time. |
| [setDuration(ReminderDuration value)](#setDuration-com.aspose.email.ReminderDuration-) | Specifies a relative time for the trigger of the alarm. |
| [setRelated(int value)](#setRelated-int-) | Specify the relationship of the alarm trigger with respect to the start or end of the event. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ReminderTrigger(Date dateTime) {#ReminderTrigger-java.util.Date-}
```
public ReminderTrigger(Date dateTime)
```


Initialize a new instance of [ReminderTrigger](../../com.aspose.email/remindertrigger) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateTime | java.util.Date | Absolute DateTime value. |

### ReminderTrigger(ReminderDuration duration, int related) {#ReminderTrigger-com.aspose.email.ReminderDuration-int-}
```
public ReminderTrigger(ReminderDuration duration, int related)
```


Initialize a new instance of [ReminderTrigger](../../com.aspose.email/remindertrigger) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| duration | [ReminderDuration](../../com.aspose.email/reminderduration) | To specify a relative time for the trigger of the alarm. |
| related | int | To specify the relationship of the alarm trigger with respect to the start or end of the event. |

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
### getDateTime() {#getDateTime--}
```
public final Date getDateTime()
```


A trigger set to an absolute date/time.

**Returns:**
java.util.Date
### getDuration() {#getDuration--}
```
public final ReminderDuration getDuration()
```


Specifies a relative time for the trigger of the alarm.

**Returns:**
[ReminderDuration](../../com.aspose.email/reminderduration)
### getRelated() {#getRelated--}
```
public final int getRelated()
```


Specify the relationship of the alarm trigger with respect to the start or end of the event.

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




### setDateTime(Date value) {#setDateTime-java.util.Date-}
```
public final void setDateTime(Date value)
```


A trigger set to an absolute date/time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setDuration(ReminderDuration value) {#setDuration-com.aspose.email.ReminderDuration-}
```
public final void setDuration(ReminderDuration value)
```


Specifies a relative time for the trigger of the alarm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ReminderDuration](../../com.aspose.email/reminderduration) |  |

### setRelated(int value) {#setRelated-int-}
```
public final void setRelated(int value)
```


Specify the relationship of the alarm trigger with respect to the start or end of the event.

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

