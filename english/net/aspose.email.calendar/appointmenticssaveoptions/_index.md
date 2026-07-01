---
title: Class AppointmentIcsSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.AppointmentIcsSaveOptions class. Represents options for saving an appointment or meeting to an ICS iCalendar file
type: docs
weight: 470
url: /net/aspose.email.calendar/appointmenticssaveoptions/
---
## AppointmentIcsSaveOptions class

Represents options for saving an appointment or meeting to an ICS (iCalendar) file.

```csharp
public sealed class AppointmentIcsSaveOptions : AppointmentSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [AppointmentIcsSaveOptions](appointmenticssaveoptions/#constructor)() | Initializes a new instance of the `AppointmentIcsSaveOptions` class |
| [AppointmentIcsSaveOptions](appointmenticssaveoptions/#constructor_1)(AppointmentAction) | Initializes a new instance of the `AppointmentIcsSaveOptions` class |

## Properties

| Name | Description |
| --- | --- |
| static [Default](../../aspose.email.calendar/appointmenticssaveoptions/default/) { get; } | Gets the default Ics save options |
| [Action](../../aspose.email.calendar/appointmenticssaveoptions/action/) { get; set; } | Gets or sets appointment Action |
| [CreateNew](../../aspose.email.calendar/appointmenticssaveoptions/createnew/) { get; set; } | Gets or sets value indicating whether need create new calendar or append events in existing calendar. Default value is true. |
| [EndTimeZone](../../aspose.email.calendar/appointmenticssaveoptions/endtimezone/) { get; set; } | Gets or sets the End time zone. |
| [MethodType](../../aspose.email.calendar/appointmenticssaveoptions/methodtype/) { get; set; } | Gets or sets the iCalendar object method type associated with the calendar object. |
| [ProductId](../../aspose.email.calendar/appointmenticssaveoptions/productid/) { get; set; } | Gets or sets the product identifier that created iCalendar object. |
| [SaveFormat](../../aspose.email.calendar/appointmentsaveoptions/saveformat/) { get; } | Gets a save format |
| [SequenceId](../../aspose.email.calendar/appointmenticssaveoptions/sequenceid/) { get; set; } | Gets or sets the sequence id. |
| [StartTimeZone](../../aspose.email.calendar/appointmenticssaveoptions/starttimezone/) { get; set; } | Gets or sets the Start time zone. |

## Remarks

The `AppointmentIcsSaveOptions` class allows specifying various settings for controlling how appointments or meetings are saved to an iCalendar file. These options include setting the creation mode, specifying the method type, product identifier, and action to be taken when saving the file.

## Examples

This example demonstrates how to create and save a meeting to an ICS file using `AppointmentIcsSaveOptions`.

[C#]

```csharp
// Create a new appointment for a meeting
var meeting = new Appointment(
    "Meeting Room 3 at Office Headquarters",  // Location
    "Monthly Meeting",                        // Summary
    "Please confirm your availability.",      // Description
    new DateTime(2015, 2, 8, 13, 0, 0),       // Start date
    new DateTime(2015, 2, 8, 14, 0, 0),       // End date
    "from@domain.com",                        // Organizer
    "attendees@domain.com");                  // Attendees

// Set the save options for ICS file
var saveOptions = new AppointmentIcsSaveOptions
{
    CreateNew = true,
    MethodType = AppointmentMethodType.Add,
    ProductId = "Aspose.Email",
    Action = AppointmentAction.Create
};

// Save the meeting to an ICS file
meeting.Save("meeting.ics", saveOptions);
```

[Visual Basic]

```csharp
' Create a new appointment for a meeting
Dim meeting As New Appointment(
    "Meeting Room 3 at Office Headquarters",  ' Location
    "Monthly Meeting",                        ' Summary
    "Please confirm your availability.",      ' Description
    New DateTime(2015, 2, 8, 13, 0, 0),       ' Start date
    New DateTime(2015, 2, 8, 14, 0, 0),       ' End date
    "from@domain.com",                        ' Organizer
    "attendees@domain.com")                   ' Attendees

' Set the save options for ICS file
Dim saveOptions As New AppointmentIcsSaveOptions With {
    .CreateNew = True,
    .MethodType = AppointmentMethodType.Add,
    .ProductId = "Aspose.Email",
    .Action = AppointmentAction.Create
}

' Save the meeting to an ICS file
meeting.Save("meeting.ics", saveOptions)
```

### See Also

* class [AppointmentSaveOptions](../appointmentsaveoptions/)
* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


