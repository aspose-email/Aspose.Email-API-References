---
title: Appointment
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 430
url: /net/aspose.email.calendar/appointment/
---
## Appointment class

Represents a calendar to an e-mail.

```csharp
public class Appointment
```

## Constructors

| Name | Description |
| --- | --- |
| [Appointment](appointment)(string, DateTime, DateTime, MailAddress, MailAddressCollection) | Initialize a new instance of the [`Appointment`](../appointment) class. |
| [Appointment](appointment)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection) | Initialize a new instance of the [`Appointment`](../appointment) class. |
| [Appointment](appointment)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, RecurrencePattern) | Initialize a new instance of the [`Appointment`](../appointment) class. |
| [Appointment](appointment)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string) | Initialize a new instance of the [`Appointment`](../appointment) class. |
| [Appointment](appointment)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string, RecurrencePattern) | Initialize a new instance of the [`Appointment`](../appointment) class. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](attachments) { get; } | Gets the collection of attachments of appointment. |
| [Attendees](attendees) { get; set; } | Gets or sets the attendees. |
| [Class](class) { get; set; } | Specifies the access classification for the appointment. |
| [CreatedDate](createddate) { get; set; } | Gets or sets the date and time that calendar information was created. |
| [Description](description) { get; set; } | Gets or sets the description. |
| [EndDate](enddate) { get; set; } | Gets or sets the end date. |
| [EndTimeZone](endtimezone) { get; set; } | End time zone |
| [Flags](flags) { get; set; } | Gets or sets appointment flags. |
| [HtmlDescription](htmldescription) { get; set; } | Gets or sets html representation of description. |
| [LastModifiedDate](lastmodifieddate) { get; set; } | Gets or sets the date and time that calendar information was last revised. |
| [Location](location) { get; set; } | Gets or sets the location. |
| [MethodType](methodtype) { get; set; } | Gets or sets the iCalendar object method type associated with the calendar object. |
| [MicrosoftBusyStatus](microsoftbusystatus) { get; set; } | Specifies the BUSY status of an appointment. |
| [MicrosoftImportance](microsoftimportance) { get; set; } | Specifies the importance of an appointment. |
| [MicrosoftIntendedStatus](microsoftintendedstatus) { get; set; } | Specifies the INTENDED status of an appointment. |
| [OptionalAttendees](optionalattendees) { get; } | Gets the optional attendees. |
| [Organizer](organizer) { get; set; } | Gets or sets the organizer. |
| [Recurrence](recurrence) { get; set; } | Gets or sets the recurrence pattern. |
| [Reminders](reminders) { get; } | Contains collection of AppointmentReminder [`AppointmentReminder`](../appointmentreminder) objects. |
| [SequenceId](sequenceid) { get; } | Gets the sequence id. |
| [StartDate](startdate) { get; set; } | Gets or sets the start date. |
| [StartTimeZone](starttimezone) { get; set; } | Start time zone |
| [Status](status) { get; set; } | Gets or sets the overall status or confirmation for the object. |
| [Summary](summary) { get; set; } | Gets or sets the summary. |
| [Transparency](transparency) { get; set; } | Specifies whether or not this appointment is intended to be visible in availability searches. |
| [UniqueId](uniqueid) { get; set; } | Gets or sets a string value that contains the GUID for the calendar item. In MS Exchange this is PidLidGlobalObjectId mapi property. |

## Methods

| Name | Description |
| --- | --- |
| static [Load](load)(Stream) | Loads [`Appointment`](../appointment) from the stream |
| static [Load](load)(string) | Loads [`Appointment`](../appointment) from the file. Supported file formats: iCalendar |
| static [Load](load)(Stream, AppointmentLoadOptions) | Loads [`Appointment`](../appointment) from the stream |
| static [Load](load)(Stream, bool) | Loads [`Appointment`](../appointment) from the stream |
| static [Load](load)(string, AppointmentLoadOptions) | Loads [`Appointment`](../appointment) from the file. Supported file formats: iCalendar A file path.Represents appointment load options[`AppointmentLoadOptions`](../appointmentloadoptions).A read [`Appointment`](../appointment). |
| [CancelAppointment](cancelappointment)() | Cancels the appointment. |
| [CancelAppointment](cancelappointment)(int) | Cancels the appointment. |
| [GetAppointmentHtml](getappointmenthtml)() | Gets the calendar HTML. |
| [GetAppointmentText](getappointmenttext)() | Gets the calendar text. |
| [GetAppointmentText](getappointmenttext)(AppointmentFormattingOptions) | Gets the calendar text. |
| [RequestApointment](requestapointment)() | Requests the apointment. |
| [RequestApointment](requestapointment)(int) | Requests the apointment. |
| [ResetTimeZone](resettimezone)() | Set local time zone |
| [Save](save)(Stream) | Saves appointment to the file with iCalendar format using te default save options |
| [Save](save)(string) | Saves appointment to the file with iCalendar format using te default save options |
| [Save](save)(Stream, AppointmentSaveFormat) | Saves appointment to the stream with specified format using te default save options |
| [Save](save)(Stream, AppointmentSaveOptions) | Saves appointment to the stream with specified save options |
| [Save](save)(string, AppointmentSaveFormat) | Saves appointment to the file with specified format using te default save options |
| [Save](save)(string, AppointmentSaveOptions) | Saves appointment to the file with specified save options |
| [SetTimeZone](settimezone)(string) | Set time zone |
| [UpdateAppointment](updateappointment)() | Updates the appointment. |
| [UpdateAppointment](updateappointment)(int) | Updates the appointment. |

### Examples

This example demonstrates how to add a calendar to an E-Mail message.

[C#]

```csharp
MailMessage msg = new MailMessage();

//attendees for the event
MailAddressCollection attendees = new MailAddressCollection();
attendees.Add(new MailAddress("person1@domain.com"));
attendees.Add(new MailAddress("person2@domain.com"));
attendees.Add(new MailAddress("person3@domain.com"));

//create appointment
Appointment app = new Appointment("Room 112",new DateTime(2006,7,17,13,0,0),new DateTime(2006,7,17,14,0,0),new MailAddress("somebody@domain.com"), attendees );
cal.Summary = "Release Meetting";
cal.Description = "Discuss for the next release";

//add calendar to the message
msg.AddAlternateView(app.RequestApointment());

//send the email message
SmtpClient smtp= new SmtpClient("smtp.server.com", 25, "user", "password");
smtp.Send(msg);
```

[Visual Basic]

```csharp
Dim msg As MailMessage =  New MailMessage() 

'attendees for the event
Dim attendees As MailAddressCollection =  New MailAddressCollection() 
attendees.Add(New MailAddress("person1@domain.com"))
attendees.Add(New MailAddress("person2@domain.com"))
attendees.Add(New MailAddress("person3@domain.com"))

'create calendar
Dim cal As Appointment =  New Appointment("Room 112",New DateTime(2006,7,17,13,0,0),New DateTime(2006,7,17,14,0,0),New MailAddress("somebody@domain.com"),attendees) 
cal.Summary = "Release Meetting"
cal.Description = "Discuss for the next release"

'add calendar to the message
msg.AddAlternateView(app.RequestApointment())
```

### See Also

* namespace [Aspose.Email.Calendar](../../aspose.email.calendar)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
