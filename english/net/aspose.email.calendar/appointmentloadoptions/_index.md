---
title: Class AppointmentLoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.AppointmentLoadOptions class. Represents options for loading an appointment from an ICS iCalendar file
type: docs
weight: 480
url: /net/aspose.email.calendar/appointmentloadoptions/
---
## AppointmentLoadOptions class

Represents options for loading an appointment from an ICS (iCalendar) file.

```csharp
public class AppointmentLoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [AppointmentLoadOptions](appointmentloadoptions/)() | Initializes a new instance of the `AppointmentLoadOptions` class with the default settings. |

## Properties

| Name | Description |
| --- | --- |
| [ApplyLocalTZ](../../aspose.email.calendar/appointmentloadoptions/applylocaltz/) { get; set; } | Gets or sets whether to convert the start and end times of the event to the local time zone of the computer. The default is `false`. |
| [DetectEncoding](../../aspose.email.calendar/appointmentloadoptions/detectencoding/) { get; set; } | Gets or sets whether to detect the text encoding of the data from its byte order mark (BOM). The default is `false`. |
| [EventIndex](../../aspose.email.calendar/appointmentloadoptions/eventindex/) { get; set; } | Gets or sets the zero-based index of the event (VEVENT) to load when the calendar contains several. For [`CalendarReader`](../calendarreader/) it is the index of the first event to read. The default is 0. |
| [IgnoreSmtpAddressCheck](../../aspose.email.calendar/appointmentloadoptions/ignoresmtpaddresscheck/) { get; set; } | Gets or sets whether to skip the validation of attendee email addresses. When `false`, an attendee address that is not a valid SMTP address causes an exception. The default is `true`. |

## Remarks

The `AppointmentLoadOptions` class provides configurable options for customizing how appointments are loaded from an iCalendar file. These options include detecting the file encoding, applying the local time zone, and ignoring SMTP address validation during the load process.

## Examples

This example demonstrates how to configure and use `AppointmentLoadOptions` to load an appointment with custom settings.

[C#]

```csharp
// Create an instance of AppointmentLoadOptions with custom settings
var loadOptions = new AppointmentLoadOptions
{
    DetectEncoding = true,
    ApplyLocalTZ = true,
    IgnoreSmtpAddressCheck = true
};

// Load the appointment from the ICS file using the specified load options
var appointment = Appointment.Load("appRequest.ics", loadOptions);
```

[Visual Basic]

```csharp
' Create an instance of AppointmentLoadOptions with custom settings
Dim loadOptions As New AppointmentLoadOptions With {
    .DetectEncoding = True,
    .ApplyLocalTZ = True,
    .IgnoreSmtpAddressCheck = True
}

' Load the appointment from the ICS file using the specified load options
Dim appointment As Appointment = Appointment.Load("appRequest.ics", loadOptions)
```

### See Also

* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


