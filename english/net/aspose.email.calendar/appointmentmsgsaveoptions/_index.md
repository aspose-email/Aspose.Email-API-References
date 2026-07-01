---
title: Class AppointmentMsgSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.AppointmentMsgSaveOptions class. Represents options for saving an appointment or calendar event to a message format
type: docs
weight: 500
url: /net/aspose.email.calendar/appointmentmsgsaveoptions/
---
## AppointmentMsgSaveOptions class

Represents options for saving an appointment or calendar event to a message format.

```csharp
public sealed class AppointmentMsgSaveOptions : AppointmentSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [AppointmentMsgSaveOptions](appointmentmsgsaveoptions/)() | Initializes a new instance of the [`MsgSaveOptions`](../../aspose.email/msgsaveoptions/) class |

## Properties

| Name | Description |
| --- | --- |
| [SaveFormat](../../aspose.email.calendar/appointmentsaveoptions/saveformat/) { get; } | Gets a save format |

## Remarks

This can be useful for converting iCalendar events to Outlook-compatible message formats while preserving important event details.

## Examples

This example demonstrates how to load an event from an ICS file and save it as a .msg file using `AppointmentMsgSaveOptions`.

[C#]

```csharp
// Load the calendar event from an ICS file
var calendarEvent = Appointment.Load("event.ics");

// Save the event as a .msg file using AppointmentMsgSaveOptions
calendarEvent.Save("event.msg", new AppointmentMsgSaveOptions());
```

[Visual Basic]

```csharp
' Load the calendar event from an ICS file
Dim calendarEvent As Appointment = Appointment.Load("event.ics")

' Save the event as a .msg file using AppointmentMsgSaveOptions
calendarEvent.Save("event.msg", New AppointmentMsgSaveOptions())
```

### See Also

* class [AppointmentSaveOptions](../appointmentsaveoptions/)
* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


