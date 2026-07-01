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
| [AppointmentLoadOptions](appointmentloadoptions/)() | Initializes a new instance of the `AppointmentLoadOptions` class |

## Properties

| Name | Description |
| --- | --- |
| [ApplyLocalTZ](../../aspose.email.calendar/appointmentloadoptions/applylocaltz/) { get; set; } | Convert time to local timezone |
| [DetectEncoding](../../aspose.email.calendar/appointmentloadoptions/detectencoding/) { get; set; } | Determines a data encoding by analyzing its byte order mark (BOM) |
| [EventIndex](../../aspose.email.calendar/appointmentloadoptions/eventindex/) { get; set; } | Determines VEVENT index in case multiple events in a single ics file. The starting VEVENT in case reading multiple events by CalendarReader[`CalendarReader`](../calendarreader/). |
| [IgnoreSmtpAddressCheck](../../aspose.email.calendar/appointmentloadoptions/ignoresmtpaddresscheck/) { get; set; } | Defines whether the SMTP address validation is skipped. |

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


