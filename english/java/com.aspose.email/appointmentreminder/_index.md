---
title: AppointmentReminder
second_title: Aspose.Email for Java API Reference
description:  Provides a grouping of component properties that define an alarm.
type: docs
weight: 43
url: /java/com.aspose.email/appointmentreminder/
---
**Inheritance:**
java.lang.Object
```
public class AppointmentReminder
```

Provides a grouping of component properties that define an alarm.
## Constructors

| Constructor | Description |
| --- | --- |
| [AppointmentReminder()](#AppointmentReminder--) | Initialize a new instance of [AppointmentReminder](../../com.aspose.email/appointmentreminder) class. |
## Methods

| Method | Description |
| --- | --- |
| [getAttendees()](#getAttendees--) | Contains collection of ReminderAttendee [ReminderAttendee](../../com.aspose.email/reminderattendee)objects. |
| [getAttachments()](#getAttachments--) | Contains collection of ReminderAttachment [ReminderAttachment](../../com.aspose.email/reminderattachment)objects. |
| [getAction()](#getAction--) | Defines the action to be invoked when an alarm is triggered. |
| [setAction(int value)](#setAction-int-) | Defines the action to be invoked when an alarm is triggered. |
| [getTrigger()](#getTrigger--) | Specifies when an alarm will trigger. |
| [setTrigger(ReminderTrigger value)](#setTrigger-com.aspose.email.ReminderTrigger-) | Specifies when an alarm will trigger. |
| [getDescription()](#getDescription--) | Provides a more complete description of the alarm. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Provides a more complete description of the alarm. |
| [getSummary()](#getSummary--) | Defines a short summary or subject for the alarm. |
| [setSummary(String value)](#setSummary-java.lang.String-) | Defines a short summary or subject for the alarm. |
| [getDuration()](#getDuration--) | Specifies the delay period, after which the alarm will repeat. |
| [setDuration(ReminderDuration value)](#setDuration-com.aspose.email.ReminderDuration-) | Specifies the delay period, after which the alarm will repeat. |
| [getRepeat()](#getRepeat--) | Defines the number of time the alarm should be repeated, after the initial trigger. |
| [setRepeat(int value)](#setRepeat-int-) | Defines the number of time the alarm should be repeated, after the initial trigger. |
| [getDefault15MinReminder()](#getDefault15MinReminder--) | Gets the default 15 min reminder. |
### AppointmentReminder() {#AppointmentReminder--}
```
public AppointmentReminder()
```


Initialize a new instance of [AppointmentReminder](../../com.aspose.email/appointmentreminder) class.

### getAttendees() {#getAttendees--}
```
public final ReminderAttendeeCollection getAttendees()
```


Contains collection of ReminderAttendee [ReminderAttendee](../../com.aspose.email/reminderattendee)objects.

**Returns:**
[ReminderAttendeeCollection](../../com.aspose.email/reminderattendeecollection)
### getAttachments() {#getAttachments--}
```
public final ReminderAttachmentCollection getAttachments()
```


Contains collection of ReminderAttachment [ReminderAttachment](../../com.aspose.email/reminderattachment)objects.

**Returns:**
[ReminderAttachmentCollection](../../com.aspose.email/reminderattachmentcollection)
### getAction() {#getAction--}
```
public final int getAction()
```


Defines the action to be invoked when an alarm is triggered.

**Returns:**
int
### setAction(int value) {#setAction-int-}
```
public final void setAction(int value)
```


Defines the action to be invoked when an alarm is triggered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTrigger() {#getTrigger--}
```
public final ReminderTrigger getTrigger()
```


Specifies when an alarm will trigger.

**Returns:**
[ReminderTrigger](../../com.aspose.email/remindertrigger)
### setTrigger(ReminderTrigger value) {#setTrigger-com.aspose.email.ReminderTrigger-}
```
public final void setTrigger(ReminderTrigger value)
```


Specifies when an alarm will trigger.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ReminderTrigger](../../com.aspose.email/remindertrigger) |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Provides a more complete description of the alarm.

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Provides a more complete description of the alarm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSummary() {#getSummary--}
```
public final String getSummary()
```


Defines a short summary or subject for the alarm.

**Returns:**
java.lang.String
### setSummary(String value) {#setSummary-java.lang.String-}
```
public final void setSummary(String value)
```


Defines a short summary or subject for the alarm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final ReminderDuration getDuration()
```


Specifies the delay period, after which the alarm will repeat.

**Returns:**
[ReminderDuration](../../com.aspose.email/reminderduration)
### setDuration(ReminderDuration value) {#setDuration-com.aspose.email.ReminderDuration-}
```
public final void setDuration(ReminderDuration value)
```


Specifies the delay period, after which the alarm will repeat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ReminderDuration](../../com.aspose.email/reminderduration) |  |

### getRepeat() {#getRepeat--}
```
public final int getRepeat()
```


Defines the number of time the alarm should be repeated, after the initial trigger.

**Returns:**
int
### setRepeat(int value) {#setRepeat-int-}
```
public final void setRepeat(int value)
```


Defines the number of time the alarm should be repeated, after the initial trigger.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefault15MinReminder() {#getDefault15MinReminder--}
```
public static AppointmentReminder getDefault15MinReminder()
```


Gets the default 15 min reminder.

**Returns:**
[AppointmentReminder](../../com.aspose.email/appointmentreminder)
