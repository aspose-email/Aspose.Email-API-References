---
title: Appointment
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt einen Kalender für eine E-Mail dar.
type: docs
weight: 430
url: /de/net/aspose.email.calendar/appointment/
---
## Appointment class

Stellt einen Kalender für eine E-Mail dar.

```csharp
public class Appointment
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Appointment](appointment#constructor)(string, DateTime, DateTime, MailAddress, MailAddressCollection) | Initialisieren Sie eine neue Instanz von[`Appointment`](../appointment) Klasse. |
| [Appointment](appointment#constructor_1)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection) | Initialisieren Sie eine neue Instanz von[`Appointment`](../appointment) Klasse. |
| [Appointment](appointment#constructor_2)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, RecurrencePattern) | Initialisieren Sie eine neue Instanz von[`Appointment`](../appointment) Klasse. |
| [Appointment](appointment#constructor_3)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string) | Initialisieren Sie eine neue Instanz von[`Appointment`](../appointment) Klasse. |
| [Appointment](appointment#constructor_4)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string, RecurrencePattern) | Initialisieren Sie eine neue Instanz von[`Appointment`](../appointment) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Attachments](../../aspose.email.calendar/appointment/attachments) { get; } | Ruft die Sammlung der Anhänge des Termins ab. |
| [Attendees](../../aspose.email.calendar/appointment/attendees) { get; set; } | Ruft die Teilnehmer ab oder legt sie fest. |
| [Class](../../aspose.email.calendar/appointment/class) { get; set; } | Gibt die Zugangsklassifikation für den Termin an. |
| [CreatedDate](../../aspose.email.calendar/appointment/createddate) { get; set; } | Ruft Datum und Uhrzeit der Erstellung der Kalenderinformationen ab oder legt diese fest. |
| [DateTimeStamp](../../aspose.email.calendar/appointment/datetimestamp) { get; set; } | Ruft Datum/Uhrzeit der Erstellung der Instanz des iCalendar-Objekts ab oder legt es fest.. |
| [Description](../../aspose.email.calendar/appointment/description) { get; set; } | Ruft die Beschreibung ab oder legt sie fest. |
| [EndDate](../../aspose.email.calendar/appointment/enddate) { get; set; } | Ruft das Enddatum ab oder legt es fest. |
| [EndTimeZone](../../aspose.email.calendar/appointment/endtimezone) { get; set; } | Endzeitzone |
| [Flags](../../aspose.email.calendar/appointment/flags) { get; set; } | Holt oder setzt Termin-Flags. |
| [HtmlDescription](../../aspose.email.calendar/appointment/htmldescription) { get; set; } | Ruft die HTML-Darstellung der Beschreibung ab oder legt sie fest. |
| [LastModifiedDate](../../aspose.email.calendar/appointment/lastmodifieddate) { get; set; } | Ruft Datum und Uhrzeit der letzten Überarbeitung der Kalenderinformationen ab oder legt diese fest. |
| [Location](../../aspose.email.calendar/appointment/location) { get; set; } | Ruft den Standort ab oder legt ihn fest. |
| [MethodType](../../aspose.email.calendar/appointment/methodtype) { get; set; } | Ruft den iCalendar-Objektmethodentyp ab oder legt ihn fest, der dem Kalenderobjekt zugeordnet ist. |
| [MicrosoftBusyStatus](../../aspose.email.calendar/appointment/microsoftbusystatus) { get; set; } | Gibt den BESETZT-Status eines Termins an. |
| [MicrosoftImportance](../../aspose.email.calendar/appointment/microsoftimportance) { get; set; } | Gibt die Wichtigkeit eines Termins an. |
| [MicrosoftIntendedStatus](../../aspose.email.calendar/appointment/microsoftintendedstatus) { get; set; } | Gibt den Status BEABSICHTIGT eines Termins an. |
| [OptionalAttendees](../../aspose.email.calendar/appointment/optionalattendees) { get; } | Ruft die optionalen Teilnehmer ab. |
| [Organizer](../../aspose.email.calendar/appointment/organizer) { get; set; } | Ruft den Organisator ab oder legt ihn fest. |
| [Recurrence](../../aspose.email.calendar/appointment/recurrence) { get; set; } | Ruft das Wiederholungsmuster ab oder legt es fest. |
| [Reminders](../../aspose.email.calendar/appointment/reminders) { get; } | Enthält eine Sammlung von AppointmentReminder[`AppointmentReminder`](../appointmentreminder) Objekte. |
| [SequenceId](../../aspose.email.calendar/appointment/sequenceid) { get; } | Ruft die Sequenz-ID ab. |
| [StartDate](../../aspose.email.calendar/appointment/startdate) { get; set; } | Ruft das Startdatum ab oder legt es fest. |
| [StartTimeZone](../../aspose.email.calendar/appointment/starttimezone) { get; set; } | Startzeitzone |
| [Status](../../aspose.email.calendar/appointment/status) { get; set; } | Holt oder setzt den Gesamtstatus oder die Bestätigung für das Objekt. |
| [Summary](../../aspose.email.calendar/appointment/summary) { get; set; } | Ruft die Zusammenfassung ab oder legt sie fest. |
| [Transparency](../../aspose.email.calendar/appointment/transparency) { get; set; } | Gibt an, ob dieser Termin in Verfügbarkeitssuchen sichtbar sein soll oder nicht. |
| [UniqueId](../../aspose.email.calendar/appointment/uniqueid) { get; set; } | Ruft einen Zeichenfolgenwert ab oder legt ihn fest, der die GUID für das Kalenderelement enthält. In MS Exchange ist dies die PidLidGlobalObjectId-Mapi-Eigenschaft. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Load](../../aspose.email.calendar/appointment/load#load)(Stream) | Lädt[`Appointment`](../appointment) aus dem stream |
| static [Load](../../aspose.email.calendar/appointment/load#load_3)(string) | Lädt[`Appointment`](../appointment) aus der Datei. Unterstützte Dateiformate: iCalendar |
| static [Load](../../aspose.email.calendar/appointment/load#load_1)(Stream, AppointmentLoadOptions) | Lädt[`Appointment`](../appointment) aus dem stream |
| static [Load](../../aspose.email.calendar/appointment/load#load_2)(Stream, bool) | Lädt[`Appointment`](../appointment) aus dem stream |
| static [Load](../../aspose.email.calendar/appointment/load#load_4)(string, AppointmentLoadOptions) | Lädt[`Appointment`](../appointment) aus der Datei. Unterstützte Dateiformate: iCalendar Ein Dateipfad.Stellt Optionen zum Laden von Terminen dar[`AppointmentLoadOptions`](../appointmentloadoptions). Eine Lektüre[`Appointment`](../appointment). |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment)() | Storniert den Termin. |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment_1)(int) | Storniert den Termin. |
| [GetAppointmentHtml](../../aspose.email.calendar/appointment/getappointmenthtml)() | Ruft das Kalender-HTML ab. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext)() | Ruft den Kalendertext ab. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext_1)(AppointmentFormattingOptions) | Ruft den Kalendertext ab. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment)() | Fordert den Termin an. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment_1)(int) | Fordert den Termin an. |
| [ResetTimeZone](../../aspose.email.calendar/appointment/resettimezone)() | Lokale Zeitzone einstellen |
| [Save](../../aspose.email.calendar/appointment/save#save)(Stream) | Speichert den Termin in der Datei im iCalendar-Format unter Verwendung der Standardspeicheroptionen |
| [Save](../../aspose.email.calendar/appointment/save#save_3)(string) | Speichert den Termin in der Datei im iCalendar-Format unter Verwendung der Standardspeicheroptionen |
| [Save](../../aspose.email.calendar/appointment/save#save_1)(Stream, AppointmentSaveFormat) | Speichert den Termin im Stream mit dem angegebenen Format unter Verwendung der Standardspeicheroptionen |
| [Save](../../aspose.email.calendar/appointment/save#save_2)(Stream, AppointmentSaveOptions) | Speichert den Termin im Stream mit den angegebenen Speicheroptionen |
| [Save](../../aspose.email.calendar/appointment/save#save_4)(string, AppointmentSaveFormat) | Speichert den Termin in der Datei mit dem angegebenen Format unter Verwendung der Standardspeicheroptionen |
| [Save](../../aspose.email.calendar/appointment/save#save_5)(string, AppointmentSaveOptions) | Speichert den Termin in der Datei mit den angegebenen Speicheroptionen |
| [SetTimeZone](../../aspose.email.calendar/appointment/settimezone)(string) | Zeitzone einstellen |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment)() | Aktualisiert den Termin. |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment_1)(int) | Aktualisiert den Termin. |

### Beispiele

Dieses Beispiel zeigt, wie einer E-Mail-Nachricht ein Kalender hinzugefügt wird.

[C#]

[Visual Basic]

```csharp
MailMessage msg = new MailMessage();

//Teilnehmer für die Veranstaltung
MailAddressCollection attendees = new MailAddressCollection();
attendees.Add(new MailAddress("person1@domain.com"));
attendees.Add(new MailAddress("person2@domain.com"));
attendees.Add(new MailAddress("person3@domain.com"));

//Termin erstellen
Appointment app = new Appointment("Room 112",new DateTime(2006,7,17,13,0,0),new DateTime(2006,7,17,14,0,0),new MailAddress("somebody@domain.com"), attendees );
cal.Summary = "Release Meetting";
cal.Description = "Discuss for the next release";

//Kalender zur Nachricht hinzufügen
msg.AddAlternateView(app.RequestApointment());

// E-Mail-Nachricht senden
SmtpClient smtp= new SmtpClient("smtp.server.com", 25, "user", "password");
smtp.Send(msg);
```

```csharp
Dim msg As MailMessage =  New MailMessage() 

'Teilnehmer für die Veranstaltung
Dim attendees As MailAddressCollection =  New MailAddressCollection() 
attendees.Add(New MailAddress("person1@domain.com"))
attendees.Add(New MailAddress("person2@domain.com"))
attendees.Add(New MailAddress("person3@domain.com"))

'Kalender erstellen
Dim cal As Appointment =  New Appointment("Room 112",New DateTime(2006,7,17,13,0,0),New DateTime(2006,7,17,14,0,0),New MailAddress("somebody@domain.com"),attendees) 
cal.Summary = "Release Meetting"
cal.Description = "Discuss for the next release"

'Fügen Sie der Nachricht einen Kalender hinzu
msg.AddAlternateView(app.RequestApointment())
```

### Siehe auch

* namensraum [Aspose.Email.Calendar](../../aspose.email.calendar)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
