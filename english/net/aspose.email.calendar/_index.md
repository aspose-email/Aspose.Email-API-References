---
title: Aspose.Email.Calendar
second_title: Aspose.Email for .NET API Reference
description: Create read and save appointments tasks and reminders in iCalendar ICS and Outlook MSG formats and turn them into email meeting requests
type: docs
weight: 50
url: /net/aspose.email.calendar/
---
Create, read and save appointments, tasks and reminders in iCalendar (ICS) and Outlook MSG formats, and turn them into email meeting requests.

## Classes

| Class | Description |
| --- | --- |
| [Appointment](./appointment/) | Represents a calendar event, such as a meeting or an appointment, that can be read from and saved to iCalendar (ICS) or Outlook MSG, or sent by email as a meeting request. |
| [AppointmentCollection](./appointmentcollection/) | A list of [`Appointment`](../aspose.email.calendar/appointment/) objects. |
| [AppointmentFormattingOptions](./appointmentformattingoptions/) | Templates that `Appointment.GetAppointmentText` uses to render the details of an appointment as plain text or HTML. |
| [AppointmentIcsSaveOptions](./appointmenticssaveoptions/) | Represents options for saving an appointment or meeting to an ICS (iCalendar) file. |
| [AppointmentLoadOptions](./appointmentloadoptions/) | Represents options for loading an appointment from an ICS (iCalendar) file. |
| [AppointmentMsgSaveOptions](./appointmentmsgsaveoptions/) | Options for saving an appointment as an Outlook message (MSG). |
| [AppointmentReminder](./appointmentreminder/) | Represents a reminder of an event (the iCalendar VALARM component). |
| [AppointmentReminderCollection](./appointmentremindercollection/) | A list of [`AppointmentReminder`](../aspose.email.calendar/appointmentreminder/) objects. |
| [AppointmentSaveOptions](./appointmentsaveoptions/) | The base class for appointment save options; use [`AppointmentIcsSaveOptions`](../aspose.email.calendar/appointmenticssaveoptions/) or [`AppointmentMsgSaveOptions`](../aspose.email.calendar/appointmentmsgsaveoptions/). |
| [CalendarReader](./calendarreader/) | Reads the events of an iCalendar (ICS) file or stream one by one. |
| [CalendarWriter](./calendarwriter/) | Writes events to an iCalendar (ICS) file or stream, one after another. |
| [ReminderAttachment](./reminderattachment/) | A file attached to a reminder, such as the sound of an audio reminder, given either as inline data or as a URI. |
| [ReminderAttachmentCollection](./reminderattachmentcollection/) | A list of [`ReminderAttachment`](../aspose.email.calendar/reminderattachment/) objects. |
| [ReminderAttendee](./reminderattendee/) | A recipient of an email reminder. |
| [ReminderAttendeeCollection](./reminderattendeecollection/) | A list of [`ReminderAttendee`](../aspose.email.calendar/reminderattendee/) objects. |
| [ReminderDuration](./reminderduration/) | A length of time used by a reminder trigger or as a repetition interval. |
| [ReminderTrigger](./remindertrigger/) | Defines when a reminder triggers: at an absolute date and time, or at a time relative to the start or end of the event. |
| [Task](./task/) | Represents a task (an iCalendar VTODO component) that can be read from iCalendar and saved to iCalendar or Outlook MSG. |
| [TaskCollection](./taskcollection/) | A collection of [`Task`](../aspose.email.calendar/task/) objects. |
| [TaskIcsSaveOptions](./taskicssaveoptions/) | Options for saving a task in iCalendar (ICS) format. |
| [TaskMsgSaveOptions](./taskmsgsaveoptions/) | Options for saving a task as an Outlook message (MSG). |
| [TaskSaveOptions](./tasksaveoptions/) | The base class for task save options; use [`TaskIcsSaveOptions`](../aspose.email.calendar/taskicssaveoptions/) or [`TaskMsgSaveOptions`](../aspose.email.calendar/taskmsgsaveoptions/). |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [AppointmentAction](./appointmentaction/) | Specifies whether a calendar message creates, updates or cancels an event. |
| [AppointmentClass](./appointmentclass/) | Defines the access classification of an event (the iCalendar CLASS property). |
| [AppointmentFlags](./appointmentflags/) | Flags that describe an appointment. |
| [AppointmentMethodType](./appointmentmethodtype/) | Defines the iCalendar METHOD of a calendar object, as specified by iTIP (RFC 5546). |
| [AppointmentSaveFormat](./appointmentsaveformat/) | Formats an appointment can be saved in. |
| [AppointmentStatus](./appointmentstatus/) | Defines the status of an event (the iCalendar STATUS property). |
| [AppointmentTransparency](./appointmenttransparency/) | Defines whether an event blocks time in free/busy searches (the iCalendar TRANSP property). |
| [MSBusyStatus](./msbusystatus/) | Defines how the time of an event is shown in a calendar, as used by Microsoft Outlook and Exchange (the X-MICROSOFT-CDO-BUSYSTATUS property). |
| [MSImportance](./msimportance/) | Defines the importance of an event, as used by Microsoft Outlook and Exchange (the X-MICROSOFT-CDO-IMPORTANCE property). |
| [MSIntendedStatus](./msintendedstatus/) | Defines how the organizer wants attendees to show the time of a meeting, as used by Microsoft Outlook and Exchange (the X-MICROSOFT-CDO-INTENDEDSTATUS property). |
| [ReminderAction](./reminderaction/) | Defines what happens when a reminder triggers (the iCalendar ACTION property). |
| [ReminderRelated](./reminderrelated/) | Defines whether a relative reminder trigger is measured from the start or from the end of the event. |
| [TaskStatus](./taskstatus/) | Defines how far work on a task has progressed. |
| [TIPMethod](./tipmethod/) | Defines the iTIP (iCalendar Transport-Independent Interoperability Protocol) methods associated with an object. |


