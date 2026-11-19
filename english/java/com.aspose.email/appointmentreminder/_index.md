---
title: AppointmentReminder
second_title: Aspose.Email for Java API Reference
description: Represents a reminder of an event the iCalendar VALARM component.
type: docs
weight: 45
url: /java/com.aspose.email/appointmentreminder/
---

**Inheritance:**
java.lang.Object
```
public class AppointmentReminder
```

Represents a reminder of an event (the iCalendar VALARM component).
## Constructors

| Constructor | Description |
| --- | --- |
| [AppointmentReminder()](#AppointmentReminder--) | Initializes a new instance of the [AppointmentReminder](../../com.aspose.email/appointmentreminder) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Gets what happens when the reminder triggers, such as showing a message or sending an email. |
| [getAttachments()](#getAttachments--) | Gets the files attached to the reminder, such as the sound of an audio reminder. |
| [getAttendees()](#getAttendees--) | Gets the recipients of an email reminder. |
| [getClass()](#getClass--) |  |
| [getDefault15MinReminder()](#getDefault15MinReminder--) | Gets a new reminder that shows a message 15 minutes before the event starts. |
| [getDescription()](#getDescription--) | Gets the text of the reminder: the message to show, or the body of an email reminder. |
| [getDuration()](#getDuration--) | Gets the interval between repetitions of the reminder. |
| [getRepeat()](#getRepeat--) | Gets how many more times the reminder repeats after it first triggers. |
| [getSummary()](#getSummary--) | Gets a short summary of the reminder, used as the subject of an email reminder. |
| [getTrigger()](#getTrigger--) | Gets when the reminder triggers. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | Sets what happens when the reminder triggers, such as showing a message or sending an email. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Sets the text of the reminder: the message to show, or the body of an email reminder. |
| [setDuration(ReminderDuration value)](#setDuration-com.aspose.email.ReminderDuration-) | Sets the interval between repetitions of the reminder. |
| [setRepeat(int value)](#setRepeat-int-) | Sets how many more times the reminder repeats after it first triggers. |
| [setSummary(String value)](#setSummary-java.lang.String-) | Sets a short summary of the reminder, used as the subject of an email reminder. |
| [setTrigger(ReminderTrigger value)](#setTrigger-com.aspose.email.ReminderTrigger-) | Sets when the reminder triggers. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AppointmentReminder() {#AppointmentReminder--}
```
public AppointmentReminder()
```


Initializes a new instance of the [AppointmentReminder](../../com.aspose.email/appointmentreminder) class.

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
### getAction() {#getAction--}
```
public final int getAction()
```


Gets what happens when the reminder triggers, such as showing a message or sending an email.

**Returns:**
int
### getAttachments() {#getAttachments--}
```
public final ReminderAttachmentCollection getAttachments()
```


Gets the files attached to the reminder, such as the sound of an audio reminder.

**Returns:**
[ReminderAttachmentCollection](../../com.aspose.email/reminderattachmentcollection)
### getAttendees() {#getAttendees--}
```
public final ReminderAttendeeCollection getAttendees()
```


Gets the recipients of an email reminder.

**Returns:**
[ReminderAttendeeCollection](../../com.aspose.email/reminderattendeecollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault15MinReminder() {#getDefault15MinReminder--}
```
public static AppointmentReminder getDefault15MinReminder()
```


Gets a new reminder that shows a message 15 minutes before the event starts.

**Returns:**
[AppointmentReminder](../../com.aspose.email/appointmentreminder)
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets the text of the reminder: the message to show, or the body of an email reminder.

**Returns:**
java.lang.String
### getDuration() {#getDuration--}
```
public final ReminderDuration getDuration()
```


Gets the interval between repetitions of the reminder. Use it together with \#getRepeat().getRepeat().

**Returns:**
[ReminderDuration](../../com.aspose.email/reminderduration)
### getRepeat() {#getRepeat--}
```
public final int getRepeat()
```


Gets how many more times the reminder repeats after it first triggers. Use it together with \#getDuration().getDuration().

**Returns:**
int
### getSummary() {#getSummary--}
```
public final String getSummary()
```


Gets a short summary of the reminder, used as the subject of an email reminder.

**Returns:**
java.lang.String
### getTrigger() {#getTrigger--}
```
public final ReminderTrigger getTrigger()
```


Gets when the reminder triggers.

**Returns:**
[ReminderTrigger](../../com.aspose.email/remindertrigger)
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




### setAction(int value) {#setAction-int-}
```
public final void setAction(int value)
```


Sets what happens when the reminder triggers, such as showing a message or sending an email.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Sets the text of the reminder: the message to show, or the body of an email reminder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDuration(ReminderDuration value) {#setDuration-com.aspose.email.ReminderDuration-}
```
public final void setDuration(ReminderDuration value)
```


Sets the interval between repetitions of the reminder. Use it together with \#setRepeat(int).setRepeat(int).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ReminderDuration](../../com.aspose.email/reminderduration) |  |

### setRepeat(int value) {#setRepeat-int-}
```
public final void setRepeat(int value)
```


Sets how many more times the reminder repeats after it first triggers. Use it together with \#setDuration(ReminderDuration).setDuration(ReminderDuration).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSummary(String value) {#setSummary-java.lang.String-}
```
public final void setSummary(String value)
```


Sets a short summary of the reminder, used as the subject of an email reminder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTrigger(ReminderTrigger value) {#setTrigger-com.aspose.email.ReminderTrigger-}
```
public final void setTrigger(ReminderTrigger value)
```


Sets when the reminder triggers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ReminderTrigger](../../com.aspose.email/remindertrigger) |  |

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

