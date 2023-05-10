---
title: Class Appointment
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.Appointment class. Represents a calendar to an email
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
| [Appointment](appointment/#constructor)(string, DateTime, DateTime, MailAddress, MailAddressCollection) | Initialize a new instance of the `Appointment` class. |
| [Appointment](appointment/#constructor_1)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection) | Initialize a new instance of the `Appointment` class. |
| [Appointment](appointment/#constructor_2)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, RecurrencePattern) | Initialize a new instance of the `Appointment` class. |
| [Appointment](appointment/#constructor_3)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string) | Initialize a new instance of the `Appointment` class. |
| [Appointment](appointment/#constructor_4)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string, RecurrencePattern) | Initialize a new instance of the `Appointment` class. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../aspose.email.calendar/appointment/attachments/) { get; } | Gets the collection of attachments of appointment. |
| [Attendees](../../aspose.email.calendar/appointment/attendees/) { get; set; } | Gets or sets the attendees. |
| [Class](../../aspose.email.calendar/appointment/class/) { get; set; } | Specifies the access classification for the appointment. |
| [CreatedDate](../../aspose.email.calendar/appointment/createddate/) { get; set; } | Gets or sets the date and time that calendar information was created. |
| [DateTimeStamp](../../aspose.email.calendar/appointment/datetimestamp/) { get; set; } | Gets or sets date/time that the instance of the iCalendar object was created.. |
| [Description](../../aspose.email.calendar/appointment/description/) { get; set; } | Gets or sets the description. |
| [EndDate](../../aspose.email.calendar/appointment/enddate/) { get; set; } | Gets or sets the end date. |
| [EndTimeZone](../../aspose.email.calendar/appointment/endtimezone/) { get; set; } | End time zone |
| [Flags](../../aspose.email.calendar/appointment/flags/) { get; set; } | Gets or sets appointment flags. |
| [HtmlDescription](../../aspose.email.calendar/appointment/htmldescription/) { get; set; } | Gets or sets html representation of description. |
| [LastModifiedDate](../../aspose.email.calendar/appointment/lastmodifieddate/) { get; set; } | Gets or sets the date and time that calendar information was last revised. |
| [Location](../../aspose.email.calendar/appointment/location/) { get; set; } | Gets or sets the location. |
| [MethodType](../../aspose.email.calendar/appointment/methodtype/) { get; set; } | Gets or sets the iCalendar object method type associated with the calendar object. |
| [MicrosoftBusyStatus](../../aspose.email.calendar/appointment/microsoftbusystatus/) { get; set; } | Specifies the BUSY status of an appointment. |
| [MicrosoftImportance](../../aspose.email.calendar/appointment/microsoftimportance/) { get; set; } | Specifies the importance of an appointment. |
| [MicrosoftIntendedStatus](../../aspose.email.calendar/appointment/microsoftintendedstatus/) { get; set; } | Specifies the INTENDED status of an appointment. |
| [OptionalAttendees](../../aspose.email.calendar/appointment/optionalattendees/) { get; } | Gets the optional attendees. |
| [Organizer](../../aspose.email.calendar/appointment/organizer/) { get; set; } | Gets or sets the organizer. |
| [Recurrence](../../aspose.email.calendar/appointment/recurrence/) { get; set; } | Gets or sets the recurrence pattern. |
| [Reminders](../../aspose.email.calendar/appointment/reminders/) { get; } | Contains collection of AppointmentReminder [`AppointmentReminder`](../appointmentreminder/) objects. |
| [SequenceId](../../aspose.email.calendar/appointment/sequenceid/) { get; } | Gets the sequence id. |
| [StartDate](../../aspose.email.calendar/appointment/startdate/) { get; set; } | Gets or sets the start date. |
| [StartTimeZone](../../aspose.email.calendar/appointment/starttimezone/) { get; set; } | Start time zone |
| [Status](../../aspose.email.calendar/appointment/status/) { get; set; } | Gets or sets the overall status or confirmation for the object. |
| [Summary](../../aspose.email.calendar/appointment/summary/) { get; set; } | Gets or sets the summary. |
| [Transparency](../../aspose.email.calendar/appointment/transparency/) { get; set; } | Specifies whether or not this appointment is intended to be visible in availability searches. |
| [UniqueId](../../aspose.email.calendar/appointment/uniqueid/) { get; set; } | Gets or sets a string value that contains the GUID for the calendar item. In MS Exchange this is PidLidGlobalObjectId mapi property. |

## Methods

| Name | Description |
| --- | --- |
| static [Load](../../aspose.email.calendar/appointment/load/#load)(Stream) | Loads `Appointment` from the stream |
| static [Load](../../aspose.email.calendar/appointment/load/#load_3)(string) | Loads `Appointment` from the file. Supported file formats: iCalendar |
| static [Load](../../aspose.email.calendar/appointment/load/#load_1)(Stream, AppointmentLoadOptions) | Loads `Appointment` from the stream |
| static [Load](../../aspose.email.calendar/appointment/load/#load_2)(Stream, bool) | Loads `Appointment` from the stream |
| static [Load](../../aspose.email.calendar/appointment/load/#load_4)(string, AppointmentLoadOptions) | Loads `Appointment` from the file. Supported file formats: iCalendar A file path.Represents appointment load options[`AppointmentLoadOptions`](../appointmentloadoptions/).A read `Appointment`. |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment/#cancelappointment)() | Cancels the appointment. |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment/#cancelappointment_1)(int) | Cancels the appointment. |
| [GetAppointmentHtml](../../aspose.email.calendar/appointment/getappointmenthtml/)() | Gets the calendar HTML. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext/#getappointmenttext)() | Gets the calendar text. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext/#getappointmenttext_1)(AppointmentFormattingOptions) | Gets the calendar text. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment/#requestapointment)() | Requests the apointment. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment/#requestapointment_1)(int) | Requests the apointment. |
| [ResetTimeZone](../../aspose.email.calendar/appointment/resettimezone/)() | Set local time zone |
| [Save](../../aspose.email.calendar/appointment/save/#save)(Stream) | Saves appointment to the file with iCalendar format using te default save options |
| [Save](../../aspose.email.calendar/appointment/save/#save_3)(string) | Saves appointment to the file with iCalendar format using te default save options |
| [Save](../../aspose.email.calendar/appointment/save/#save_1)(Stream, AppointmentSaveFormat) | Saves appointment to the stream with specified format using te default save options |
| [Save](../../aspose.email.calendar/appointment/save/#save_2)(Stream, AppointmentSaveOptions) | Saves appointment to the stream with specified save options |
| [Save](../../aspose.email.calendar/appointment/save/#save_4)(string, AppointmentSaveFormat) | Saves appointment to the file with specified format using te default save options |
| [Save](../../aspose.email.calendar/appointment/save/#save_5)(string, AppointmentSaveOptions) | Saves appointment to the file with specified save options |
| [SetTimeZone](../../aspose.email.calendar/appointment/settimezone/)(string) | Set time zone |
| [ToMailMessage](../../aspose.email.calendar/appointment/tomailmessage/#tomailmessage)() | Ñonverts ICalendar item (.ics) to MIME (.eml) message. |
| [ToMailMessage](../../aspose.email.calendar/appointment/tomailmessage/#tomailmessage_1)(AppointmentAction) | Ñonverts ICalendar item (.ics) to MIME (.eml) message. |
| [ToMailMessage](../../aspose.email.calendar/appointment/tomailmessage/#tomailmessage_2)(AppointmentAction, int) | Ñonverts ICalendar item (.ics) to MIME (.eml) message. |
| [ToMapiMessage](../../aspose.email.calendar/appointment/tomapimessage/)() | Ñonverts ICalendar item (.ics) to MAPI (.msg) message. |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment/#updateappointment)() | Updates the appointment. |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment/#updateappointment_1)(int) | Updates the appointment. |

## Examples

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

* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


