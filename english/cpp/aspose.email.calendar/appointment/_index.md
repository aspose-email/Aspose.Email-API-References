---
title: "Aspose::Email::Calendar::Appointment class"
linktitle: "Appointment"
articleTitle: "Appointment"
second_title: "Aspose.Email for C++"
description: "Represents a calendar to an e-mail."
type: docs
weight: 10
url: /cpp/aspose.email.calendar/appointment/
---

## Appointment class

Represents a calendar to an e-mail.

This example demonstrates how to add a calendar to an E-Mail message.

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

```vb
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

## Constructors

| Name | Description |
| --- | --- |
| [Appointment (8 overloads)](./appointment/) | Initialize a new instance of the Appointment class. |

## Methods

| Name | Description |
| --- | --- |
| [CancelAppointment (2 overloads)](./cancelappointment/) | Cancels the appointment. |
| [get_Action](./get_action/) | Gets appointment action |
| [get_Attachments](./get_attachments/) | Gets the collection of attachments of appointment. |
| [get_Attendees](./get_attendees/) | Gets the attendees. |
| [get_Class](./get_class/) | Specifies the access classification for the appointment. |
| [get_CreatedDate](./get_createddate/) | Gets the date and time that calendar information was created. |
| [get_DateTimeStamp](./get_datetimestamp/) | Gets date/time that the instance of the iCalendar object was created.. |
| [get_Description](./get_description/) | Gets the description. |
| [get_EndDate](./get_enddate/) | Gets the end date. |
| [get_EndTimeZone](./get_endtimezone/) | End time zone |
| [get_EndTimeZoneInfo](./get_endtimezoneinfo/) | End time zone |
| [get_ExtendedProperties](./get_extendedproperties/) | Gets extended properties of an item. |
| [get_Flags](./get_flags/) | Gets appointment flags. |
| [get_HtmlDescription](./get_htmldescription/) | Gets html representation of description. |
| [get_Id](./get_id/) | Object identifier |
| [get_IsDescriptionHtml](./get_isdescriptionhtml/) | Gets value which indicates if description is in HTML format |
| [get_LastModifiedDate](./get_lastmodifieddate/) | Gets the date and time that calendar information was last revised. |
| [get_Location](./get_location/) | Gets the location. |
| [get_MethodType](./get_methodtype/) | Gets the iCalendar object method type associated with the calendar object. |
| [get_MicrosoftBusyStatus](./get_microsoftbusystatus/) | Specifies the BUSY status of an appointment. |
| [get_MicrosoftImportance](./get_microsoftimportance/) | Specifies the importance of an appointment. |
| [get_MicrosoftIntendedStatus](./get_microsoftintendedstatus/) | Specifies the INTENDED status of an appointment. |
| [get_OptionalAttendees](./get_optionalattendees/) | Gets the optional attendees. |
| [get_Organizer](./get_organizer/) | Gets the organizer. |
| [get_Recurrence](./get_recurrence/) | Gets the recurrence pattern. |
| [get_Reminders](./get_reminders/) | Contains collection of AppointmentReminder AppointmentReminder objects. |
| [get_SequenceId](./get_sequenceid/) | Gets the sequence id. |
| [get_StartDate](./get_startdate/) | Gets the start date. |
| [get_StartTimeZone](./get_starttimezone/) | Start time zone |
| [get_StartTimeZoneInfo](./get_starttimezoneinfo/) | Start time zone |
| [get_Status](./get_status/) | Gets the overall status or confirmation for the object. |
| [get_Summary](./get_summary/) | Gets the summary. |
| [get_Transparency](./get_transparency/) | Specifies whether or not this appointment is intended to be visible in availability searches. |
| [get_UniqueId](./get_uniqueid/) | Gets a string value that contains the GUID for the calendar item. In MS Exchange this is PidLidGlobalObjectId mapi property. |
| [get_Version](./get_version/) | Gets the version of ICS/VCS file. |
| [GetAppointmentHtml](./getappointmenthtml/) | Gets the calendar HTML. |
| [GetAppointmentText (2 overloads)](./getappointmenttext/) | Gets the calendar text. |
| [GetMediaTypeValue](./getmediatypevalue/) |  |
| [Load (5 overloads)](./load/) | Loads Appointment from the stream |
| [RequestApointment (3 overloads)](./requestapointment/) | Requests the apointment. |
| [ResetTimeZone](./resettimezone/) | Set local time zone |
| [Save (6 overloads)](./save/) | Saves appointment to the file with iCalendar format using te default save options |
| [set_Action](./set_action/) | Sets appointment action |
| [set_Attendees](./set_attendees/) | Sets the attendees. |
| [set_Class](./set_class/) | Specifies the access classification for the appointment. |
| [set_CreatedDate](./set_createddate/) | Sets the date and time that calendar information was created. |
| [set_DateTimeStamp](./set_datetimestamp/) | Sets date/time that the instance of the iCalendar object was created.. |
| [set_Description](./set_description/) | Sets the description. |
| [set_EndDate](./set_enddate/) | Sets the end date. |
| [set_EndTimeZone](./set_endtimezone/) | End time zone |
| [set_EndTimeZoneInfo](./set_endtimezoneinfo/) | End time zone |
| [set_Flags](./set_flags/) | Sets appointment flags. |
| [set_HtmlDescription](./set_htmldescription/) | Sets html representation of description. |
| [set_IsDescriptionHtml](./set_isdescriptionhtml/) | Sets value which indicates if description is in HTML format |
| [set_LastModifiedDate](./set_lastmodifieddate/) | Sets the date and time that calendar information was last revised. |
| [set_Location](./set_location/) | Sets the location. |
| [set_MethodType](./set_methodtype/) | Sets the iCalendar object method type associated with the calendar object. |
| [set_MicrosoftBusyStatus](./set_microsoftbusystatus/) | Specifies the BUSY status of an appointment. |
| [set_MicrosoftImportance](./set_microsoftimportance/) | Specifies the importance of an appointment. |
| [set_MicrosoftIntendedStatus](./set_microsoftintendedstatus/) | Specifies the INTENDED status of an appointment. |
| [set_Organizer](./set_organizer/) | Sets the organizer. |
| [set_Recurrence](./set_recurrence/) | Sets the recurrence pattern. |
| [set_SequenceId](./set_sequenceid/) | Gets the sequence id. |
| [set_StartDate](./set_startdate/) | Sets the start date. |
| [set_StartTimeZone](./set_starttimezone/) | Start time zone |
| [set_StartTimeZoneInfo](./set_starttimezoneinfo/) | Start time zone |
| [set_Status](./set_status/) | Sets the overall status or confirmation for the object. |
| [set_Summary](./set_summary/) | Sets the summary. |
| [set_Transparency](./set_transparency/) | Specifies whether or not this appointment is intended to be visible in availability searches. |
| [set_UniqueId](./set_uniqueid/) | Sets a string value that contains the GUID for the calendar item. In MS Exchange this is PidLidGlobalObjectId mapi property. |
| [set_Version](./set_version/) | Gets the version of ICS/VCS file. |
| [SetTimeZone](./settimezone/) | Set time zone |
| [ToMailMessage (3 overloads)](./tomailmessage/) | �onverts ICalendar item (.ics) to MIME (.eml) message. |
| [ToMapiMessage](./tomapimessage/) | �onverts ICalendar item (.ics) to MAPI (.msg) message. |
| [UpdateAppointment (2 overloads)](./updateappointment/) | Updates the appointment. |
| [Aspose::Email::Clients::Google::Commands::CalendarAPI::V3::Parsers::AppointmentReader](./asposeemailclientsgooglecommandscalendarapiv3parsersappointmentreader/) |  |
| [Aspose::Email::Clients::Google::Commands::CalendarAPI::V3::Parsers::AppointmentWriter](./asposeemailclientsgooglecommandscalendarapiv3parsersappointmentwriter/) |  |
| [Aspose::Email::Storage::Zimbra::ZimbraCalendar](./asposeemailstoragezimbrazimbracalendar/) |  |
| [Aspose::Email::Tools::CalendarConverter](./asposeemailtoolscalendarconverter/) |  |
| [CalendarWriter](./calendarwriter/) |  |
| [categories](./categories/) |  |
| [exDates](./exdates/) |  |
| [extendedProperties](./extendedproperties/) |  |
| [isLoaded](./isloaded/) |  |
| [optionalAttendees](./optionalattendees/) |  |
| [recurrenceSpecialCases](./recurrencespecialcases/) |  |
| [sequence](./sequence/) |  |
| [sequenceId](./sequenceid/) |  |

