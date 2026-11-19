---
title: ReminderTrigger
second_title: Aspose.Email for Java API Reference
description: Defines when a reminder triggers at an absolute date and time or at a time relative to the start or end of the event.
type: docs
weight: 637
url: /java/com.aspose.email/remindertrigger/
---

**Inheritance:**
java.lang.Object
```
public class ReminderTrigger
```

Defines when a reminder triggers: at an absolute date and time, or at a time relative to the start or end of the event.
## Constructors

| Constructor | Description |
| --- | --- |
| [ReminderTrigger(Date dateTime)](#ReminderTrigger-java.util.Date-) | Initializes a new instance of the [ReminderTrigger](../../com.aspose.email/remindertrigger) class that triggers at an absolute date and time. |
| [ReminderTrigger(ReminderDuration duration, int related)](#ReminderTrigger-com.aspose.email.ReminderDuration-int-) | Initializes a new instance of the [ReminderTrigger](../../com.aspose.email/remindertrigger) class that triggers at a time relative to the event. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDateTime()](#getDateTime--) | Gets the absolute date and time of the trigger. |
| [getDuration()](#getDuration--) | Gets the time of the trigger relative to the start or end of the event. |
| [getRelated()](#getRelated--) | Gets whether \#getDuration().getDuration() is measured from the start or from the end of the event. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDateTime(Date value)](#setDateTime-java.util.Date-) | Sets the absolute date and time of the trigger. |
| [setDuration(ReminderDuration value)](#setDuration-com.aspose.email.ReminderDuration-) | Sets the time of the trigger relative to the start or end of the event. |
| [setRelated(int value)](#setRelated-int-) | Sets whether \#getDuration().getDuration() is measured from the start or from the end of the event. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ReminderTrigger(Date dateTime) {#ReminderTrigger-java.util.Date-}
```
public ReminderTrigger(Date dateTime)
```


Initializes a new instance of the [ReminderTrigger](../../com.aspose.email/remindertrigger) class that triggers at an absolute date and time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateTime | java.util.Date | The date and time of the trigger. |

### ReminderTrigger(ReminderDuration duration, int related) {#ReminderTrigger-com.aspose.email.ReminderDuration-int-}
```
public ReminderTrigger(ReminderDuration duration, int related)
```


Initializes a new instance of the [ReminderTrigger](../../com.aspose.email/remindertrigger) class that triggers at a time relative to the event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| duration | [ReminderDuration](../../com.aspose.email/reminderduration) | The offset from the start or end of the event; negative for a time before it. |
| related | int | Whether  duration  is measured from the start or from the end of the event. |

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


Gets the absolute date and time of the trigger. Setting it clears \#getDuration().getDuration();  DateTime.MinValue  means it is not set.

**Returns:**
java.util.Date
### getDuration() {#getDuration--}
```
public final ReminderDuration getDuration()
```


Gets the time of the trigger relative to the start or end of the event. Setting it clears \#getDateTime().getDateTime().

**Returns:**
[ReminderDuration](../../com.aspose.email/reminderduration)
### getRelated() {#getRelated--}
```
public final int getRelated()
```


Gets whether \#getDuration().getDuration() is measured from the start or from the end of the event. It is not used with an absolute \#getDateTime().getDateTime().

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


Sets the absolute date and time of the trigger. Setting it clears \#getDuration().getDuration();  DateTime.MinValue  means it is not set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setDuration(ReminderDuration value) {#setDuration-com.aspose.email.ReminderDuration-}
```
public final void setDuration(ReminderDuration value)
```


Sets the time of the trigger relative to the start or end of the event. Setting it clears \#getDateTime().getDateTime().

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ReminderDuration](../../com.aspose.email/reminderduration) |  |

### setRelated(int value) {#setRelated-int-}
```
public final void setRelated(int value)
```


Sets whether \#getDuration().getDuration() is measured from the start or from the end of the event. It is not used with an absolute \#getDateTime().getDateTime().

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

