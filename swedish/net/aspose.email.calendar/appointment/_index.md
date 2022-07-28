---
title: Appointment
second_title: Aspose.Email för .NET API-referens
description: Representerar en kalender för ett e-postmeddelande.
type: docs
weight: 430
url: /sv/net/aspose.email.calendar/appointment/
---
## Appointment class

Representerar en kalender för ett e-postmeddelande.

```csharp
public class Appointment
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Appointment](appointment#constructor)(string, DateTime, DateTime, MailAddress, MailAddressCollection) | Initiera en ny instans av[`Appointment`](../appointment) class. |
| [Appointment](appointment#constructor_1)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection) | Initiera en ny instans av[`Appointment`](../appointment) class. |
| [Appointment](appointment#constructor_2)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, RecurrencePattern) | Initiera en ny instans av[`Appointment`](../appointment) class. |
| [Appointment](appointment#constructor_3)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string) | Initiera en ny instans av[`Appointment`](../appointment) class. |
| [Appointment](appointment#constructor_4)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string, RecurrencePattern) | Initiera en ny instans av[`Appointment`](../appointment) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Attachments](../../aspose.email.calendar/appointment/attachments) { get; } | Hämtar samlingen av bilagor för möte. |
| [Attendees](../../aspose.email.calendar/appointment/attendees) { get; set; } | Får eller ställer in deltagarna. |
| [Class](../../aspose.email.calendar/appointment/class) { get; set; } | Anger åtkomstklassificeringen för mötet. |
| [CreatedDate](../../aspose.email.calendar/appointment/createddate) { get; set; } | Hämtar eller ställer in datum och tid då kalenderinformationen skapades. |
| [DateTimeStamp](../../aspose.email.calendar/appointment/datetimestamp) { get; set; } | Hämtar eller ställer in datum/tid då instansen av iCalendar-objektet skapades.. |
| [Description](../../aspose.email.calendar/appointment/description) { get; set; } | Hämtar eller ställer in beskrivningen. |
| [EndDate](../../aspose.email.calendar/appointment/enddate) { get; set; } | Hämtar eller ställer in slutdatumet. |
| [EndTimeZone](../../aspose.email.calendar/appointment/endtimezone) { get; set; } | Sluttidszon |
| [Flags](../../aspose.email.calendar/appointment/flags) { get; set; } | Får eller sätter mötesflaggor. |
| [HtmlDescription](../../aspose.email.calendar/appointment/htmldescription) { get; set; } | Hämtar eller ställer in HTML-representation av beskrivning. |
| [LastModifiedDate](../../aspose.email.calendar/appointment/lastmodifieddate) { get; set; } | Hämtar eller ställer in datum och tid då kalenderinformationen senast reviderades. |
| [Location](../../aspose.email.calendar/appointment/location) { get; set; } | Hämtar eller ställer in platsen. |
| [MethodType](../../aspose.email.calendar/appointment/methodtype) { get; set; } | Hämtar eller ställer in iCalendar-objektmetodtypen associerad med kalenderobjektet. |
| [MicrosoftBusyStatus](../../aspose.email.calendar/appointment/microsoftbusystatus) { get; set; } | Anger statusen UPPTAGEN för ett möte. |
| [MicrosoftImportance](../../aspose.email.calendar/appointment/microsoftimportance) { get; set; } | Anger vikten av ett möte. |
| [MicrosoftIntendedStatus](../../aspose.email.calendar/appointment/microsoftintendedstatus) { get; set; } | Anger AVSEDDA status för ett möte. |
| [OptionalAttendees](../../aspose.email.calendar/appointment/optionalattendees) { get; } | Får de valfria deltagarna. |
| [Organizer](../../aspose.email.calendar/appointment/organizer) { get; set; } | Hämtar eller ställer in arrangören. |
| [Recurrence](../../aspose.email.calendar/appointment/recurrence) { get; set; } | Hämtar eller ställer in återkommande mönstret. |
| [Reminders](../../aspose.email.calendar/appointment/reminders) { get; } | Innehåller samling av mötespåminnelse[`AppointmentReminder`](../appointmentreminder) objekt. |
| [SequenceId](../../aspose.email.calendar/appointment/sequenceid) { get; } | Hämtar sekvens-id. |
| [StartDate](../../aspose.email.calendar/appointment/startdate) { get; set; } | Hämtar eller ställer in startdatum. |
| [StartTimeZone](../../aspose.email.calendar/appointment/starttimezone) { get; set; } | Starttidszon |
| [Status](../../aspose.email.calendar/appointment/status) { get; set; } | Hämtar eller ställer in den övergripande statusen eller bekräftelsen för objektet. |
| [Summary](../../aspose.email.calendar/appointment/summary) { get; set; } | Hämtar eller ställer in sammanfattningen. |
| [Transparency](../../aspose.email.calendar/appointment/transparency) { get; set; } | Anger om det här mötet är avsett att synas i tillgänglighetssökningar. |
| [UniqueId](../../aspose.email.calendar/appointment/uniqueid) { get; set; } | Hämtar eller ställer in ett strängvärde som innehåller GUID för kalenderobjektet. I MS Exchange är detta PidLidGlobalObjectId mapi property. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Load](../../aspose.email.calendar/appointment/load#load)(Stream) | Laddar[`Appointment`](../appointment) från stream |
| static [Load](../../aspose.email.calendar/appointment/load#load_3)(string) | Laddar[`Appointment`](../appointment) från filen. Filformat som stöds: iCalendar |
| static [Load](../../aspose.email.calendar/appointment/load#load_1)(Stream, AppointmentLoadOptions) | Laddar[`Appointment`](../appointment) från stream |
| static [Load](../../aspose.email.calendar/appointment/load#load_2)(Stream, bool) | Laddar[`Appointment`](../appointment) från stream |
| static [Load](../../aspose.email.calendar/appointment/load#load_4)(string, AppointmentLoadOptions) | Laddar[`Appointment`](../appointment) från filen. Filformat som stöds: iCalendar En filsökväg.Representerar laddningsalternativ för möten[`AppointmentLoadOptions`](../appointmentloadoptions). En läsning[`Appointment`](../appointment). |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment)() | Avbryter mötet. |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment_1)(int) | Avbryter mötet. |
| [GetAppointmentHtml](../../aspose.email.calendar/appointment/getappointmenthtml)() | Hämtar kalenderns HTML. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext)() | Hämtar kalendertexten. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext_1)(AppointmentFormattingOptions) | Hämtar kalendertexten. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment)() | Begär mötet. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment_1)(int) | Begär mötet. |
| [ResetTimeZone](../../aspose.email.calendar/appointment/resettimezone)() | Ställ in lokal tidszon |
| [Save](../../aspose.email.calendar/appointment/save#save)(Stream) | Sparar möte i filen med iCalendar-format med standardalternativen för spara |
| [Save](../../aspose.email.calendar/appointment/save#save_3)(string) | Sparar möte i filen med iCalendar-format med standardalternativen för spara |
| [Save](../../aspose.email.calendar/appointment/save#save_1)(Stream, AppointmentSaveFormat) | Sparar möte i strömmen med angivet format med standardinställningarna för spara |
| [Save](../../aspose.email.calendar/appointment/save#save_2)(Stream, AppointmentSaveOptions) | Sparar ett möte i strömmen med angivna sparalternativ |
| [Save](../../aspose.email.calendar/appointment/save#save_4)(string, AppointmentSaveFormat) | Sparar möte i filen med angivet format med standardinställningarna för spara |
| [Save](../../aspose.email.calendar/appointment/save#save_5)(string, AppointmentSaveOptions) | Sparar möte i filen med angivna sparalternativ |
| [SetTimeZone](../../aspose.email.calendar/appointment/settimezone)(string) | Ställ in tidszon |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment)() | Uppdaterar mötet. |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment_1)(int) | Uppdaterar mötet. |

### Exempel

Det här exemplet visar hur man lägger till en kalender i ett e-postmeddelande.

[C#]

[Visual Basic]

```csharp
MailMessage msg = new MailMessage();

//deltagare till evenemanget
MailAddressCollection attendees = new MailAddressCollection();
attendees.Add(new MailAddress("person1@domain.com"));
attendees.Add(new MailAddress("person2@domain.com"));
attendees.Add(new MailAddress("person3@domain.com"));

//skapa möte
Appointment app = new Appointment("Room 112",new DateTime(2006,7,17,13,0,0),new DateTime(2006,7,17,14,0,0),new MailAddress("somebody@domain.com"), attendees );
cal.Summary = "Release Meetting";
cal.Description = "Discuss for the next release";

//lägg till kalender i meddelandet
msg.AddAlternateView(app.RequestApointment());

//skicka e-postmeddelandet
SmtpClient smtp= new SmtpClient("smtp.server.com", 25, "user", "password");
smtp.Send(msg);
```

```csharp
Dim msg As MailMessage =  New MailMessage() 

'deltagare till evenemanget
Dim attendees As MailAddressCollection =  New MailAddressCollection() 
attendees.Add(New MailAddress("person1@domain.com"))
attendees.Add(New MailAddress("person2@domain.com"))
attendees.Add(New MailAddress("person3@domain.com"))

'skapa kalender
Dim cal As Appointment =  New Appointment("Room 112",New DateTime(2006,7,17,13,0,0),New DateTime(2006,7,17,14,0,0),New MailAddress("somebody@domain.com"),attendees) 
cal.Summary = "Release Meetting"
cal.Description = "Discuss for the next release"

'lägg till kalender i meddelandet
msg.AddAlternateView(app.RequestApointment())
```

### Se även

* namnutrymme [Aspose.Email.Calendar](../../aspose.email.calendar)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
