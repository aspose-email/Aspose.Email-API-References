---
title: AppointmentMsgSaveOptions
second_title: Aspose.Email for Java API Reference
description: Represents options for saving an appointment or calendar event to a message format.
type: docs
weight: 42
url: /java/com.aspose.email/appointmentmsgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AppointmentSaveOptions](../../com.aspose.email/appointmentsaveoptions)
```
public final class AppointmentMsgSaveOptions extends AppointmentSaveOptions
```

Represents options for saving an appointment or calendar event to a message format.

This can be useful for converting iCalendar events to Outlook-compatible message formats while preserving important event details.

This example demonstrates how to load an event from an ICS file and save it as a .msg file using [AppointmentMsgSaveOptions](../../com.aspose.email/appointmentmsgsaveoptions).

```

 // Load the calendar event from an ICS file
 Appointment calendarEvent = Appointment.load("event.ics");

 // Save the event as a .msg file using AppointmentMsgSaveOptions
 calendarEvent.save("event.msg", new AppointmentMsgSaveOptions());
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [AppointmentMsgSaveOptions()](#AppointmentMsgSaveOptions--) | Initializes a new instance of the [MsgSaveOptions](../../com.aspose.email/msgsaveoptions) class |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSaveFormat()](#getSaveFormat--) | Gets a save format |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AppointmentMsgSaveOptions() {#AppointmentMsgSaveOptions--}
```
public AppointmentMsgSaveOptions()
```


Initializes a new instance of the [MsgSaveOptions](../../com.aspose.email/msgsaveoptions) class

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
### getSaveFormat() {#getSaveFormat--}
```
public final int getSaveFormat()
```


Gets a save format

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

