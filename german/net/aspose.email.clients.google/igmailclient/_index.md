---
title: IGmailClient
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt die Schnittstelle für Gmail client dar
type: docs
weight: 15790
url: /de/net/aspose.email.clients.google/igmailclient/
---
## IGmailClient interface

Stellt die Schnittstelle für Gmail client dar

```csharp
public interface IGmailClient : IBaseGmailClient
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ClearCalendar](../../aspose.email.clients.google/igmailclient/clearcalendar)(string) | Löscht einen Kalender. |
| [CreateAccessRule](../../aspose.email.clients.google/igmailclient/createaccessrule)(string, AccessControlRule) | Erstellt Zugriffsregel |
| [CreateAppointment](../../aspose.email.clients.google/igmailclient/createappointment)(string, Appointment) | Erstellt einen Termin. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar)(Calendar) | Erstellt einen Kalender. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar_1)(Calendar, bool) | Erstellt einen Kalender. |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact)(Contact) | Erstellt Kontakt für angegebene E-Mail-Adresse |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact_1)(Contact, string) | Erstellt Kontakt für angegebene E-Mail-Adresse |
| [CreateContactPhoto](../../aspose.email.clients.google/igmailclient/createcontactphoto)(Contact, byte[]) | Erstellt Kontaktfoto |
| [DeleteAccessRule](../../aspose.email.clients.google/igmailclient/deleteaccessrule)(string, string) | Löscht Zugriffsregel |
| [DeleteAppointment](../../aspose.email.clients.google/igmailclient/deleteappointment)(string, string) | Löscht einen Termin. |
| [DeleteCalendar](../../aspose.email.clients.google/igmailclient/deletecalendar)(string) | Löscht einen Kalender. |
| [DeleteContact](../../aspose.email.clients.google/igmailclient/deletecontact)(string) | Löscht den angegebenen Kontakt |
| [DeleteContactPhoto](../../aspose.email.clients.google/igmailclient/deletecontactphoto)(ContactPhoto) | Löscht Kontaktfoto |
| [FetchAccessRule](../../aspose.email.clients.google/igmailclient/fetchaccessrule)(string, string) | Ruft Zugriffsregel ab |
| [FetchAppointment](../../aspose.email.clients.google/igmailclient/fetchappointment)(string, string) | Ruft den Termin nach Kennung ab. |
| [FetchCalendar](../../aspose.email.clients.google/igmailclient/fetchcalendar)(string) | Ruft den Kalender nach Kennung ab. |
| [GetAllContacts](../../aspose.email.clients.google/igmailclient/getallcontacts)() | Ruft alle Kontakte ab. |
| [GetAllGroups](../../aspose.email.clients.google/igmailclient/getallgroups)() | Ruft alle Kontaktgruppen ab. |
| [GetColors](../../aspose.email.clients.google/igmailclient/getcolors)() | Ruft Farbinformationen ab |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact)(Contact) | Kontakt zum Auffrischen[`Contact`](../../aspose.email.personalinfo/contact) Objekt, das einen Kontakt von Google Mail darstellt wenn der Betrieb fehlschlägt |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact_1)(string) | Ruft Kontakt ab |
| [GetContactsFromGroup](../../aspose.email.clients.google/igmailclient/getcontactsfromgroup)(string) | Ruft Kontakte ab, die zur angegebenen Gruppe gehören. |
| [GetFreebusyInfo](../../aspose.email.clients.google/igmailclient/getfreebusyinfo)(FreebusyQuery) | Ruft Frei/Gebucht-Informationen ab |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto)(ContactPhoto) | Ruft ein Kontaktfoto ab |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto_1)(string) | Ruft ein Kontaktfoto ab |
| [GetSetting](../../aspose.email.clients.google/igmailclient/getsetting)(string) | Ruft Einstellungen nach dem Namen ab |
| [GetSettings](../../aspose.email.clients.google/igmailclient/getsettings)() | Ruft das Einstellungswörterbuch ab |
| [ImportAppointment](../../aspose.email.clients.google/igmailclient/importappointment)(string, Appointment) | Importiert Termin in Kalender |
| [ListAccessRules](../../aspose.email.clients.google/igmailclient/listaccessrules)(string) | Ruft eine Liste der Zugriffsregeln ab |
| [ListAppointmentInstances](../../aspose.email.clients.google/igmailclient/listappointmentinstances)(string, string) | Ruft eine Liste von Termininstanzen für den Kalender ab. |
| [ListAppointments](../../aspose.email.clients.google/igmailclient/listappointments)(string) | Ruft eine Liste mit Terminen für den Kalender ab. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars)() | Ruft ein Array von Kalendern ab. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars_1)(AccessRole, bool) | Ruft ein Array von Kalendern ab. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment)(string, string, string) | Verschiebt einen Termin in einen anderen Kalender. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment_1)(string, string, string, bool) | Verschiebt einen Termin in einen anderen Kalender. |
| [UpdateAccessRule](../../aspose.email.clients.google/igmailclient/updateaccessrule)(string, AccessControlRule) | Aktualisiert die Zugriffsregel |
| [UpdateAppointment](../../aspose.email.clients.google/igmailclient/updateappointment)(string, Appointment) | Aktualisiert einen Termin. |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar)(Calendar) | Aktualisiert einen Kalender |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar_1)(Calendar, bool) | Aktualisiert einen Kalender |
| [UpdateContact](../../aspose.email.clients.google/igmailclient/updatecontact)(Contact) | aktualisiert Kontakt |
| [UpdateContactPhoto](../../aspose.email.clients.google/igmailclient/updatecontactphoto)(ContactPhoto) | Erstellt oder aktualisiert Kontaktfoto |

### Siehe auch

* interface [IBaseGmailClient](../ibasegmailclient)
* namensraum [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
