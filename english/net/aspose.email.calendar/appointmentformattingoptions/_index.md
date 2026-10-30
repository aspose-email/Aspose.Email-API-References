---
title: Class AppointmentFormattingOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.AppointmentFormattingOptions class. Templates that Appointment.GetAppointmentText uses to render the details of an appointment as plain text or HTML
type: docs
weight: 460
url: /net/aspose.email.calendar/appointmentformattingoptions/
---
## AppointmentFormattingOptions class

Templates that `Appointment.GetAppointmentText` uses to render the details of an appointment as plain text or HTML.

```csharp
public class AppointmentFormattingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [AppointmentFormattingOptions](appointmentformattingoptions/)() | Initializes a new instance of the `AppointmentFormattingOptions` class with the plain-text templates. |

## Properties

| Name | Description |
| --- | --- |
| [CssStyles](../../aspose.email.calendar/appointmentformattingoptions/cssstyles/) { get; set; } | Gets or sets markup to add to the head of the HTML output, typically a `<style>` element. |
| [DescriptionFormat](../../aspose.email.calendar/appointmentformattingoptions/descriptionformat/) { get; set; } | Gets or sets the template for the description. |
| [EndDateFormat](../../aspose.email.calendar/appointmentformattingoptions/enddateformat/) { get; set; } | Gets or sets the template for the end date and time. |
| [IsTextFormat](../../aspose.email.calendar/appointmentformattingoptions/istextformat/) { get; } | Gets a value indicating whether the templates produce plain text rather than HTML. |
| [LocationFormat](../../aspose.email.calendar/appointmentformattingoptions/locationformat/) { get; set; } | Gets or sets the template for the location. |
| [OrganizerFormat](../../aspose.email.calendar/appointmentformattingoptions/organizerformat/) { get; set; } | Gets or sets the template for the organizer. |
| [StartDateFormat](../../aspose.email.calendar/appointmentformattingoptions/startdateformat/) { get; set; } | Gets or sets the template for the start date and time. |
| [TimezoneFormat](../../aspose.email.calendar/appointmentformattingoptions/timezoneformat/) { get; set; } | Gets or sets the template for the time zone. |
| [TitleFormat](../../aspose.email.calendar/appointmentformattingoptions/titleformat/) { get; set; } | Gets or sets the template for the title (the summary of the appointment). |

## Methods

| Name | Description |
| --- | --- |
| static [CreateAsHtml](../../aspose.email.calendar/appointmentformattingoptions/createashtml/)() | Creates formatting options with the HTML templates. |

## Remarks

Each template is a composite format string in which `{0}` is replaced by the value, for example `Location: {0}`. A new instance holds the plain-text templates; `CreateAsHtml` returns one with HTML templates. Setting a template to `null` or an empty string keeps the current one.

### See Also

* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


