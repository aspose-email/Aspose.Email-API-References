---
title: Class Appointment
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.Appointment class. Represents a calendar event such as a meeting or an appointment that can be read from and saved to iCalendar ICS or Outlook MSG or sent by email as a meeting request
type: docs
weight: 410
url: /net/aspose.email.calendar/appointment/
---
## Appointment class

Represents a calendar event, such as a meeting or an appointment, that can be read from and saved to iCalendar (ICS) or Outlook MSG, or sent by email as a meeting request.

```csharp
public class Appointment
```

## Constructors

| Name | Description |
| --- | --- |
| [Appointment](appointment/#constructor)(string, DateTime, DateTime, MailAddress, MailAddressCollection) | Initializes a new instance of the `Appointment` class with the location, time, organizer and attendees of the event. |
| [Appointment](appointment/#constructor_1)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection) | Initializes a new instance of the `Appointment` class with the location, summary, description, time, organizer and attendees of the event. |
| [Appointment](appointment/#constructor_2)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, RecurrencePattern) | Initializes a new instance of the `Appointment` class for a recurring event. |
| [Appointment](appointment/#constructor_3)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string) | Initializes a new instance of the `Appointment` class with an explicit unique identifier. |
| [Appointment](appointment/#constructor_4)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string, RecurrencePattern) | Initializes a new instance of the `Appointment` class for a recurring event with an explicit unique identifier. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../aspose.email.calendar/appointment/attachments/) { get; } | Gets the files attached to the event. |
| [Attendees](../../aspose.email.calendar/appointment/attendees/) { get; set; } | Gets or sets the attendees of the event, except the optional ones, which are in `OptionalAttendees`. |
| [Class](../../aspose.email.calendar/appointment/class/) { get; set; } | Gets or sets the access classification of the event (the iCalendar CLASS property). |
| [CreatedDate](../../aspose.email.calendar/appointment/createddate/) { get; set; } | Gets or sets the date and time the event was created (the iCalendar CREATED property). |
| [DateTimeStamp](../../aspose.email.calendar/appointment/datetimestamp/) { get; set; } | Gets or sets the date and time the iCalendar object was created (the iCalendar DTSTAMP property). |
| [Description](../../aspose.email.calendar/appointment/description/) { get; set; } | Gets or sets the plain-text description of the event. |
| [EndDate](../../aspose.email.calendar/appointment/enddate/) { get; set; } | Gets or sets the end date and time of the event. |
| [EndTimeZone](../../aspose.email.calendar/appointment/endtimezone/) { get; set; } | Gets or sets the time zone of the end of the event. |
| [Flags](../../aspose.email.calendar/appointment/flags/) { get; set; } | Gets or sets the flags of the event, such as whether it lasts all day. |
| [HtmlDescription](../../aspose.email.calendar/appointment/htmldescription/) { get; set; } | Gets or sets the HTML version of the description. |
| [LastModifiedDate](../../aspose.email.calendar/appointment/lastmodifieddate/) { get; set; } | Gets or sets the date and time the event was last modified (the iCalendar LAST-MODIFIED property). |
| [Location](../../aspose.email.calendar/appointment/location/) { get; set; } | Gets or sets the location of the event. |
| [MethodType](../../aspose.email.calendar/appointment/methodtype/) { get; set; } | Gets or sets the iCalendar METHOD of the event, such as a request or a cancellation. The default for a new appointment is `AppointmentMethodType.Request`. |
| [MicrosoftBusyStatus](../../aspose.email.calendar/appointment/microsoftbusystatus/) { get; set; } | Gets or sets how the time of the event is shown in the calendar of the organizer, such as busy or free (the X-MICROSOFT-CDO-BUSYSTATUS property). |
| [MicrosoftImportance](../../aspose.email.calendar/appointment/microsoftimportance/) { get; set; } | Gets or sets the importance of the event (the X-MICROSOFT-CDO-IMPORTANCE property). |
| [MicrosoftIntendedStatus](../../aspose.email.calendar/appointment/microsoftintendedstatus/) { get; set; } | Gets or sets how the organizer wants attendees to show the time of the meeting, such as busy or free (the X-MICROSOFT-CDO-INTENDEDSTATUS property). |
| [MSProperties](../../aspose.email.calendar/appointment/msproperties/) { get; } | Gets the Microsoft-specific properties of the event (those whose names start with X-MICROSOFT), keyed by property name. |
| [OptionalAttendees](../../aspose.email.calendar/appointment/optionalattendees/) { get; } | Gets the optional attendees of the event (those with ROLE=OPT-PARTICIPANT). |
| [Organizer](../../aspose.email.calendar/appointment/organizer/) { get; set; } | Gets or sets the organizer of the event. |
| [ProductId](../../aspose.email.calendar/appointment/productid/) { get; set; } | Gets or sets the identifier of the product that created the event (the iCalendar PRODID property). |
| [Recurrence](../../aspose.email.calendar/appointment/recurrence/) { get; set; } | Gets or sets the recurrence pattern of the event, or `null` if it does not repeat. |
| [Reminders](../../aspose.email.calendar/appointment/reminders/) { get; } | Gets the reminders (alarms) of the event. |
| [SequenceId](../../aspose.email.calendar/appointment/sequenceid/) { get; } | Gets the revision sequence number of the event (the iCalendar SEQUENCE property), as read from the source. |
| [StartDate](../../aspose.email.calendar/appointment/startdate/) { get; set; } | Gets or sets the start date and time of the event. |
| [StartTimeZone](../../aspose.email.calendar/appointment/starttimezone/) { get; set; } | Gets or sets the time zone of the start of the event. |
| [Status](../../aspose.email.calendar/appointment/status/) { get; set; } | Gets or sets the status of the event, such as tentative or confirmed (the iCalendar STATUS property). The default for a new appointment is `AppointmentStatus.Tentative`. |
| [Summary](../../aspose.email.calendar/appointment/summary/) { get; set; } | Gets or sets the summary (subject) of the event. |
| [Transparency](../../aspose.email.calendar/appointment/transparency/) { get; set; } | Gets or sets whether the event blocks time in free/busy searches (the iCalendar TRANSP property). The default for a new appointment is `AppointmentTransparency.Opaque`. |
| [UniqueId](../../aspose.email.calendar/appointment/uniqueid/) { get; set; } | Gets or sets the unique identifier of the event (the iCalendar UID property). In Microsoft Exchange it corresponds to the PidLidGlobalObjectId MAPI property. |
| [Version](../../aspose.email.calendar/appointment/version/) { get; } | Gets the version of the calendar the event was read from: 2.0 for iCalendar (ICS), 1.0 for vCalendar (VCS). |

## Methods

| Name | Description |
| --- | --- |
| static [Load](../../aspose.email.calendar/appointment/load/#load)(Stream) | Loads an appointment from a stream of iCalendar (ICS) data. |
| static [Load](../../aspose.email.calendar/appointment/load/#load_3)(string) | Loads an appointment from an iCalendar (ICS) file. |
| static [Load](../../aspose.email.calendar/appointment/load/#load_1)(Stream, AppointmentLoadOptions) | Loads an appointment from a stream of iCalendar (ICS) data with the specified options. |
| static [Load](../../aspose.email.calendar/appointment/load/#load_2)(Stream, bool) | Loads an appointment from a stream of iCalendar (ICS) data, optionally converting its times to the local time zone. |
| static [Load](../../aspose.email.calendar/appointment/load/#load_4)(string, AppointmentLoadOptions) | Loads an appointment from an iCalendar (ICS) file with the specified options. |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment/#cancelappointment)() | Creates a cancellation of this meeting (iCalendar METHOD:CANCEL) to send to its attendees. |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment/#cancelappointment_1)(int) | Creates a cancellation of this meeting (iCalendar METHOD:CANCEL) with the specified sequence number. |
| [GetAppointmentHtml](../../aspose.email.calendar/appointment/getappointmenthtml/)() | Returns the details of the appointment as HTML. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext/#getappointmenttext)() | Returns the details of the appointment as plain text. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext/#getappointmenttext_1)(AppointmentFormattingOptions) | Returns the details of the appointment, formatted with the specified templates. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment/#requestapointment)() | Creates a meeting request for this appointment, with the METHOD set in `MethodType` and sequence number 0. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment/#requestapointment_1)(AppointmentMethodType) | Creates a meeting request for this appointment with the specified iCalendar METHOD. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment/#requestapointment_2)(int) | Creates a meeting request for this appointment with the specified sequence number. |
| [ResetTimeZone](../../aspose.email.calendar/appointment/resettimezone/)() | Sets the start and end time zones of the event to the local time zone of the computer. |
| [Save](../../aspose.email.calendar/appointment/save/#save)(Stream) | Saves the appointment to a stream in iCalendar (ICS) format. |
| [Save](../../aspose.email.calendar/appointment/save/#save_3)(string) | Saves the appointment to an iCalendar (ICS) file. |
| [Save](../../aspose.email.calendar/appointment/save/#save_1)(Stream, AppointmentSaveFormat) | Saves the appointment to a stream in the specified format, with default options. |
| [Save](../../aspose.email.calendar/appointment/save/#save_2)(Stream, AppointmentSaveOptions) | Saves the appointment to a stream with the specified options. |
| [Save](../../aspose.email.calendar/appointment/save/#save_4)(string, AppointmentSaveFormat) | Saves the appointment to a file in the specified format, with default options. |
| [Save](../../aspose.email.calendar/appointment/save/#save_5)(string, AppointmentSaveOptions) | Saves the appointment to a file with the specified options. |
| [SetTimeZone](../../aspose.email.calendar/appointment/settimezone/)(string) | Sets both the start and the end time zone of the event. |
| [ToMailMessage](../../aspose.email.calendar/appointment/tomailmessage/#tomailmessage)() | Creates an email message that carries this appointment as a meeting request. |
| [ToMailMessage](../../aspose.email.calendar/appointment/tomailmessage/#tomailmessage_1)(AppointmentAction) | Creates an email message that carries this appointment as a meeting request, update or cancellation. |
| [ToMailMessage](../../aspose.email.calendar/appointment/tomailmessage/#tomailmessage_2)(AppointmentAction, int) | Creates an email message that carries this appointment as a meeting request, update or cancellation. |
| [ToMapiMessage](../../aspose.email.calendar/appointment/tomapimessage/)() | Converts the appointment to an Outlook message, which can then be saved as an .msg file. |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment/#updateappointment)() | Creates an update of this meeting to send to its attendees. |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment/#updateappointment_1)(int) | Creates an update of this meeting with the specified sequence number. |

## Remarks

Use `Load` to read an event from an .ics file or stream and `Save` to write it. To send a meeting request, add the view returned by `RequestApointment` to a [`MailMessage`](../../aspose.email/mailmessage/), or call `ToMailMessage`.

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
app.Summary = "Release Meeting";
app.Description = "Discuss for the next release";

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

'create appointment
Dim app As Appointment =  New Appointment("Room 112",New DateTime(2006,7,17,13,0,0),New DateTime(2006,7,17,14,0,0),New MailAddress("somebody@domain.com"),attendees) 
app.Summary = "Release Meeting"
app.Description = "Discuss for the next release"

'add calendar to the message
msg.AddAlternateView(app.RequestApointment())
```

### See Also

* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


