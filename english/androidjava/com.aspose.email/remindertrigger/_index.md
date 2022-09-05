---
title: ReminderTrigger
second_title: Aspose.Email for Android via Java API Reference
description:  Specifies when an alarm will trigger.
type: docs
weight: 368
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
| [getDuration()](#getDuration--) | Specifies a relative time for the trigger of the alarm. |
| [setDuration(ReminderDuration value)](#setDuration-com.aspose.email.ReminderDuration-) | Specifies a relative time for the trigger of the alarm. |
| [getDateTime()](#getDateTime--) | A trigger set to an absolute date/time. |
| [setDateTime(Date value)](#setDateTime-java.util.Date-) | A trigger set to an absolute date/time. |
| [getRelated()](#getRelated--) | Specify the relationship of the alarm trigger with respect to the start or end of the event. |
| [setRelated(int value)](#setRelated-int-) | Specify the relationship of the alarm trigger with respect to the start or end of the event. |
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

### getDuration() {#getDuration--}
```
public final ReminderDuration getDuration()
```


Specifies a relative time for the trigger of the alarm.

**Returns:**
[ReminderDuration](../../com.aspose.email/reminderduration)
### setDuration(ReminderDuration value) {#setDuration-com.aspose.email.ReminderDuration-}
```
public final void setDuration(ReminderDuration value)
```


Specifies a relative time for the trigger of the alarm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ReminderDuration](../../com.aspose.email/reminderduration) |  |

### getDateTime() {#getDateTime--}
```
public final Date getDateTime()
```


A trigger set to an absolute date/time.

**Returns:**
java.util.Date
### setDateTime(Date value) {#setDateTime-java.util.Date-}
```
public final void setDateTime(Date value)
```


A trigger set to an absolute date/time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getRelated() {#getRelated--}
```
public final int getRelated()
```


Specify the relationship of the alarm trigger with respect to the start or end of the event.

**Returns:**
int
### setRelated(int value) {#setRelated-int-}
```
public final void setRelated(int value)
```


Specify the relationship of the alarm trigger with respect to the start or end of the event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

