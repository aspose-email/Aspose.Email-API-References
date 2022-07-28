---
title: Appointment
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta un calendario in une-mail.
type: docs
weight: 430
url: /it/net/aspose.email.calendar/appointment/
---
## Appointment class

Rappresenta un calendario in un'e-mail.

```csharp
public class Appointment
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Appointment](appointment#constructor)(string, DateTime, DateTime, MailAddress, MailAddressCollection) | Inizializza una nuova istanza di[`Appointment`](../appointment) classe. |
| [Appointment](appointment#constructor_1)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection) | Inizializza una nuova istanza di[`Appointment`](../appointment) classe. |
| [Appointment](appointment#constructor_2)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, RecurrencePattern) | Inizializza una nuova istanza di[`Appointment`](../appointment) classe. |
| [Appointment](appointment#constructor_3)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string) | Inizializza una nuova istanza di[`Appointment`](../appointment) classe. |
| [Appointment](appointment#constructor_4)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string, RecurrencePattern) | Inizializza una nuova istanza di[`Appointment`](../appointment) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Attachments](../../aspose.email.calendar/appointment/attachments) { get; } | Ottiene la raccolta degli allegati di appuntamento. |
| [Attendees](../../aspose.email.calendar/appointment/attendees) { get; set; } | Ottiene o imposta i partecipanti. |
| [Class](../../aspose.email.calendar/appointment/class) { get; set; } | Specifica la classificazione di accesso per l'appuntamento. |
| [CreatedDate](../../aspose.email.calendar/appointment/createddate) { get; set; } | Ottiene o imposta la data e l'ora in cui sono state create le informazioni del calendario. |
| [DateTimeStamp](../../aspose.email.calendar/appointment/datetimestamp) { get; set; } | Ottiene o imposta la data/ora di creazione dell'istanza dell'oggetto iCalendar.. |
| [Description](../../aspose.email.calendar/appointment/description) { get; set; } | Ottiene o imposta la descrizione. |
| [EndDate](../../aspose.email.calendar/appointment/enddate) { get; set; } | Ottiene o imposta la data di fine. |
| [EndTimeZone](../../aspose.email.calendar/appointment/endtimezone) { get; set; } | Fuso orario di fine |
| [Flags](../../aspose.email.calendar/appointment/flags) { get; set; } | Ottiene o imposta i flag degli appuntamenti. |
| [HtmlDescription](../../aspose.email.calendar/appointment/htmldescription) { get; set; } | Ottiene o imposta la rappresentazione html della descrizione. |
| [LastModifiedDate](../../aspose.email.calendar/appointment/lastmodifieddate) { get; set; } | Ottiene o imposta la data e l'ora dell'ultima revisione delle informazioni del calendario. |
| [Location](../../aspose.email.calendar/appointment/location) { get; set; } | Ottiene o imposta la posizione. |
| [MethodType](../../aspose.email.calendar/appointment/methodtype) { get; set; } | Ottiene o imposta il tipo di metodo dell'oggetto iCalendar associato all'oggetto calendario. |
| [MicrosoftBusyStatus](../../aspose.email.calendar/appointment/microsoftbusystatus) { get; set; } | Specifica lo stato BUSY di un appuntamento. |
| [MicrosoftImportance](../../aspose.email.calendar/appointment/microsoftimportance) { get; set; } | Specifica l'importanza di un appuntamento. |
| [MicrosoftIntendedStatus](../../aspose.email.calendar/appointment/microsoftintendedstatus) { get; set; } | Specifica lo stato INTENDED di un appuntamento. |
| [OptionalAttendees](../../aspose.email.calendar/appointment/optionalattendees) { get; } | Ottiene i partecipanti facoltativi. |
| [Organizer](../../aspose.email.calendar/appointment/organizer) { get; set; } | Ottiene o imposta l'organizer. |
| [Recurrence](../../aspose.email.calendar/appointment/recurrence) { get; set; } | Ottiene o imposta il modello di ricorrenza. |
| [Reminders](../../aspose.email.calendar/appointment/reminders) { get; } | Contiene la raccolta di AppointmentReminder[`AppointmentReminder`](../appointmentreminder) oggetti. |
| [SequenceId](../../aspose.email.calendar/appointment/sequenceid) { get; } | Ottiene l'id della sequenza. |
| [StartDate](../../aspose.email.calendar/appointment/startdate) { get; set; } | Ottiene o imposta la data di inizio. |
| [StartTimeZone](../../aspose.email.calendar/appointment/starttimezone) { get; set; } | Fuso orario di inizio |
| [Status](../../aspose.email.calendar/appointment/status) { get; set; } | Ottiene o imposta lo stato generale o la conferma per l'oggetto. |
| [Summary](../../aspose.email.calendar/appointment/summary) { get; set; } | Ottiene o imposta il riepilogo. |
| [Transparency](../../aspose.email.calendar/appointment/transparency) { get; set; } | Specifica se questo appuntamento deve essere visibile o meno nelle ricerche di disponibilità. |
| [UniqueId](../../aspose.email.calendar/appointment/uniqueid) { get; set; } | Ottiene o imposta un valore stringa che contiene il GUID per l'elemento del calendario. In MS Exchange questa è la proprietà mapi PidLidGlobalObjectId. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Load](../../aspose.email.calendar/appointment/load#load)(Stream) | Carichi[`Appointment`](../appointment) dal flusso |
| static [Load](../../aspose.email.calendar/appointment/load#load_3)(string) | Carichi[`Appointment`](../appointment) dal file. Formati di file supportati: iCalendar |
| static [Load](../../aspose.email.calendar/appointment/load#load_1)(Stream, AppointmentLoadOptions) | Carichi[`Appointment`](../appointment) dal flusso |
| static [Load](../../aspose.email.calendar/appointment/load#load_2)(Stream, bool) | Carichi[`Appointment`](../appointment) dal flusso |
| static [Load](../../aspose.email.calendar/appointment/load#load_4)(string, AppointmentLoadOptions) | Carichi[`Appointment`](../appointment) dal file. Formati di file supportati: iCalendar Un percorso di file.Rappresenta le opzioni di caricamento degli appuntamenti[`AppointmentLoadOptions`](../appointmentloadoptions). Una lettura[`Appointment`](../appointment). |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment)() | Annulla l'appuntamento. |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment_1)(int) | Annulla l'appuntamento. |
| [GetAppointmentHtml](../../aspose.email.calendar/appointment/getappointmenthtml)() | Ottiene il calendario HTML. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext)() | Ottiene il testo del calendario. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext_1)(AppointmentFormattingOptions) | Ottiene il testo del calendario. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment)() | Richiede l'appuntamento. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment_1)(int) | Richiede l'appuntamento. |
| [ResetTimeZone](../../aspose.email.calendar/appointment/resettimezone)() | Imposta fuso orario locale |
| [Save](../../aspose.email.calendar/appointment/save#save)(Stream) | Salva l'appuntamento nel file con il formato iCalendar utilizzando le opzioni di salvataggio predefinite |
| [Save](../../aspose.email.calendar/appointment/save#save_3)(string) | Salva l'appuntamento nel file con il formato iCalendar utilizzando le opzioni di salvataggio predefinite |
| [Save](../../aspose.email.calendar/appointment/save#save_1)(Stream, AppointmentSaveFormat) | Salva l'appuntamento nello stream con il formato specificato utilizzando le opzioni di salvataggio predefinite |
| [Save](../../aspose.email.calendar/appointment/save#save_2)(Stream, AppointmentSaveOptions) | Salva l'appuntamento nello stream con le opzioni di salvataggio specificate |
| [Save](../../aspose.email.calendar/appointment/save#save_4)(string, AppointmentSaveFormat) | Salva l'appuntamento nel file con il formato specificato utilizzando le opzioni di salvataggio predefinite |
| [Save](../../aspose.email.calendar/appointment/save#save_5)(string, AppointmentSaveOptions) | Salva l'appuntamento nel file con le opzioni di salvataggio specificate |
| [SetTimeZone](../../aspose.email.calendar/appointment/settimezone)(string) | Imposta fuso orario |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment)() | Aggiorna l'appuntamento. |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment_1)(int) | Aggiorna l'appuntamento. |

### Esempi

In questo esempio viene illustrato come aggiungere un calendario a un messaggio di posta elettronica.

[C#]

[Visual Basic]

```csharp
MailMessage msg = new MailMessage();

//partecipanti all'evento
MailAddressCollection attendees = new MailAddressCollection();
attendees.Add(new MailAddress("person1@domain.com"));
attendees.Add(new MailAddress("person2@domain.com"));
attendees.Add(new MailAddress("person3@domain.com"));

//crea appuntamento
Appointment app = new Appointment("Room 112",new DateTime(2006,7,17,13,0,0),new DateTime(2006,7,17,14,0,0),new MailAddress("somebody@domain.com"), attendees );
cal.Summary = "Release Meetting";
cal.Description = "Discuss for the next release";

//aggiungi calendario al messaggio
msg.AddAlternateView(app.RequestApointment());

//invia il messaggio di posta elettronica
SmtpClient smtp= new SmtpClient("smtp.server.com", 25, "user", "password");
smtp.Send(msg);
```

```csharp
Dim msg As MailMessage =  New MailMessage() 

'partecipanti all'evento
Dim attendees As MailAddressCollection =  New MailAddressCollection() 
attendees.Add(New MailAddress("person1@domain.com"))
attendees.Add(New MailAddress("person2@domain.com"))
attendees.Add(New MailAddress("person3@domain.com"))

'crea calendario
Dim cal As Appointment =  New Appointment("Room 112",New DateTime(2006,7,17,13,0,0),New DateTime(2006,7,17,14,0,0),New MailAddress("somebody@domain.com"),attendees) 
cal.Summary = "Release Meetting"
cal.Description = "Discuss for the next release"

'aggiungi calendario al messaggio
msg.AddAlternateView(app.RequestApointment())
```

### Guarda anche

* spazio dei nomi [Aspose.Email.Calendar](../../aspose.email.calendar)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
