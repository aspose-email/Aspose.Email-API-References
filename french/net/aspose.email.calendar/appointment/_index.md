---
title: Appointment
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente un calendrier pour un e-mail.
type: docs
weight: 430
url: /fr/net/aspose.email.calendar/appointment/
---
## Appointment class

Représente un calendrier pour un e-mail.

```csharp
public class Appointment
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Appointment](appointment#constructor)(string, DateTime, DateTime, MailAddress, MailAddressCollection) | Initialiser une nouvelle instance du[`Appointment`](../appointment) classe. |
| [Appointment](appointment#constructor_1)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection) | Initialiser une nouvelle instance du[`Appointment`](../appointment) classe. |
| [Appointment](appointment#constructor_2)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, RecurrencePattern) | Initialiser une nouvelle instance du[`Appointment`](../appointment) classe. |
| [Appointment](appointment#constructor_3)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string) | Initialiser une nouvelle instance du[`Appointment`](../appointment) classe. |
| [Appointment](appointment#constructor_4)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string, RecurrencePattern) | Initialiser une nouvelle instance du[`Appointment`](../appointment) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Attachments](../../aspose.email.calendar/appointment/attachments) { get; } | Obtient la collection de pièces jointes du rendez-vous. |
| [Attendees](../../aspose.email.calendar/appointment/attendees) { get; set; } | Obtient ou définit les participants. |
| [Class](../../aspose.email.calendar/appointment/class) { get; set; } | Spécifie la classification d'accès pour le rendez-vous. |
| [CreatedDate](../../aspose.email.calendar/appointment/createddate) { get; set; } | Obtient ou définit la date et l'heure auxquelles les informations de calendrier ont été créées. |
| [DateTimeStamp](../../aspose.email.calendar/appointment/datetimestamp) { get; set; } | Obtient ou définit la date/heure de création de l'instance de l'objet iCalendar.. |
| [Description](../../aspose.email.calendar/appointment/description) { get; set; } | Obtient ou définit la description. |
| [EndDate](../../aspose.email.calendar/appointment/enddate) { get; set; } | Obtient ou définit la date de fin. |
| [EndTimeZone](../../aspose.email.calendar/appointment/endtimezone) { get; set; } | Fuseau horaire de fin |
| [Flags](../../aspose.email.calendar/appointment/flags) { get; set; } | Obtient ou définit des indicateurs de rendez-vous. |
| [HtmlDescription](../../aspose.email.calendar/appointment/htmldescription) { get; set; } | Obtient ou définit la représentation html de la description. |
| [LastModifiedDate](../../aspose.email.calendar/appointment/lastmodifieddate) { get; set; } | Obtient ou définit la date et l'heure auxquelles les informations de calendrier ont été révisées pour la dernière fois. |
| [Location](../../aspose.email.calendar/appointment/location) { get; set; } | Obtient ou définit l'emplacement. |
| [MethodType](../../aspose.email.calendar/appointment/methodtype) { get; set; } | Obtient ou définit le type de méthode d'objet iCalendar associé à l'objet calendrier. |
| [MicrosoftBusyStatus](../../aspose.email.calendar/appointment/microsoftbusystatus) { get; set; } | Spécifie l'état OCCUPÉ d'un rendez-vous. |
| [MicrosoftImportance](../../aspose.email.calendar/appointment/microsoftimportance) { get; set; } | Spécifie l'importance d'un rendez-vous. |
| [MicrosoftIntendedStatus](../../aspose.email.calendar/appointment/microsoftintendedstatus) { get; set; } | Spécifie le statut INTENDED d'un rendez-vous. |
| [OptionalAttendees](../../aspose.email.calendar/appointment/optionalattendees) { get; } | Obtient les participants facultatifs. |
| [Organizer](../../aspose.email.calendar/appointment/organizer) { get; set; } | Obtient ou définit l'organisateur. |
| [Recurrence](../../aspose.email.calendar/appointment/recurrence) { get; set; } | Obtient ou définit le modèle de récurrence. |
| [Reminders](../../aspose.email.calendar/appointment/reminders) { get; } | Contient une collection de AppointmentReminder[`AppointmentReminder`](../appointmentreminder) objets. |
| [SequenceId](../../aspose.email.calendar/appointment/sequenceid) { get; } | Obtient l'identifiant de la séquence. |
| [StartDate](../../aspose.email.calendar/appointment/startdate) { get; set; } | Obtient ou définit la date de début. |
| [StartTimeZone](../../aspose.email.calendar/appointment/starttimezone) { get; set; } | Fuseau horaire de début |
| [Status](../../aspose.email.calendar/appointment/status) { get; set; } | Obtient ou définit l'état global ou la confirmation de l'objet. |
| [Summary](../../aspose.email.calendar/appointment/summary) { get; set; } | Obtient ou définit le résumé. |
| [Transparency](../../aspose.email.calendar/appointment/transparency) { get; set; } | Spécifie si ce rendez-vous est destiné ou non à être visible dans les recherches de disponibilité. |
| [UniqueId](../../aspose.email.calendar/appointment/uniqueid) { get; set; } | Obtient ou définit une valeur de chaîne contenant le GUID de l'élément de calendrier. Dans MS Exchange, il s'agit de la propriété PidLidGlobalObjectId mapi. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [Load](../../aspose.email.calendar/appointment/load#load)(Stream) | Charges[`Appointment`](../appointment) du stream |
| static [Load](../../aspose.email.calendar/appointment/load#load_3)(string) | Charges[`Appointment`](../appointment) à partir du fichier. Formats de fichiers pris en charge : iCalendar |
| static [Load](../../aspose.email.calendar/appointment/load#load_1)(Stream, AppointmentLoadOptions) | Charges[`Appointment`](../appointment) du stream |
| static [Load](../../aspose.email.calendar/appointment/load#load_2)(Stream, bool) | Charges[`Appointment`](../appointment) du stream |
| static [Load](../../aspose.email.calendar/appointment/load#load_4)(string, AppointmentLoadOptions) | Charges[`Appointment`](../appointment) à partir du fichier. Formats de fichiers pris en charge : iCalendar Un chemin de fichier.Représente les options de chargement de rendez-vous[`AppointmentLoadOptions`](../appointmentloadoptions). Une lecture[`Appointment`](../appointment). |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment)() | Annule le rendez-vous. |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment_1)(int) | Annule le rendez-vous. |
| [GetAppointmentHtml](../../aspose.email.calendar/appointment/getappointmenthtml)() | Obtient le calendrier HTML. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext)() | Obtient le texte du calendrier. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext_1)(AppointmentFormattingOptions) | Obtient le texte du calendrier. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment)() | Demande le rendez-vous. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment_1)(int) | Demande le rendez-vous. |
| [ResetTimeZone](../../aspose.email.calendar/appointment/resettimezone)() | Définir le fuseau horaire local |
| [Save](../../aspose.email.calendar/appointment/save#save)(Stream) | Enregistre le rendez-vous dans le fichier au format iCalendar en utilisant les options d'enregistrement par défaut |
| [Save](../../aspose.email.calendar/appointment/save#save_3)(string) | Enregistre le rendez-vous dans le fichier au format iCalendar en utilisant les options d'enregistrement par défaut |
| [Save](../../aspose.email.calendar/appointment/save#save_1)(Stream, AppointmentSaveFormat) | Enregistre le rendez-vous dans le flux avec le format spécifié à l'aide des options d'enregistrement par défaut |
| [Save](../../aspose.email.calendar/appointment/save#save_2)(Stream, AppointmentSaveOptions) | Enregistre le rendez-vous dans le flux avec les options d'enregistrement spécifiées |
| [Save](../../aspose.email.calendar/appointment/save#save_4)(string, AppointmentSaveFormat) | Enregistre le rendez-vous dans le fichier au format spécifié à l'aide des options d'enregistrement par défaut |
| [Save](../../aspose.email.calendar/appointment/save#save_5)(string, AppointmentSaveOptions) | Enregistre le rendez-vous dans le fichier avec les options d'enregistrement spécifiées |
| [SetTimeZone](../../aspose.email.calendar/appointment/settimezone)(string) | Définir le fuseau horaire |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment)() | Met à jour le rendez-vous. |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment_1)(int) | Met à jour le rendez-vous. |

### Exemples

Cet exemple montre comment ajouter un calendrier à un message électronique.

[C#]

[Visual Basic]

```csharp
MailMessage msg = new MailMessage();

//participants à l'événement
MailAddressCollection attendees = new MailAddressCollection();
attendees.Add(new MailAddress("person1@domain.com"));
attendees.Add(new MailAddress("person2@domain.com"));
attendees.Add(new MailAddress("person3@domain.com"));

// créer un rendez-vous
Appointment app = new Appointment("Room 112",new DateTime(2006,7,17,13,0,0),new DateTime(2006,7,17,14,0,0),new MailAddress("somebody@domain.com"), attendees );
cal.Summary = "Release Meetting";
cal.Description = "Discuss for the next release";

//ajoute un calendrier au message
msg.AddAlternateView(app.RequestApointment());

// envoie le message électronique
SmtpClient smtp= new SmtpClient("smtp.server.com", 25, "user", "password");
smtp.Send(msg);
```

```csharp
Dim msg As MailMessage =  New MailMessage() 

'participants à l'événement
Dim attendees As MailAddressCollection =  New MailAddressCollection() 
attendees.Add(New MailAddress("person1@domain.com"))
attendees.Add(New MailAddress("person2@domain.com"))
attendees.Add(New MailAddress("person3@domain.com"))

'créer un calendrier
Dim cal As Appointment =  New Appointment("Room 112",New DateTime(2006,7,17,13,0,0),New DateTime(2006,7,17,14,0,0),New MailAddress("somebody@domain.com"),attendees) 
cal.Summary = "Release Meetting"
cal.Description = "Discuss for the next release"

'ajouter un calendrier au message
msg.AddAlternateView(app.RequestApointment())
```

### Voir également

* espace de noms [Aspose.Email.Calendar](../../aspose.email.calendar)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
