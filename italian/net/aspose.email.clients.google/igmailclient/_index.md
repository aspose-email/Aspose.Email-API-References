---
title: IGmailClient
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta linterfaccia per il client Gmail
type: docs
weight: 15790
url: /it/net/aspose.email.clients.google/igmailclient/
---
## IGmailClient interface

Rappresenta l'interfaccia per il client Gmail

```csharp
public interface IGmailClient : IBaseGmailClient
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ClearCalendar](../../aspose.email.clients.google/igmailclient/clearcalendar)(string) | Cancella un calendario. |
| [CreateAccessRule](../../aspose.email.clients.google/igmailclient/createaccessrule)(string, AccessControlRule) | Crea la regola di accesso |
| [CreateAppointment](../../aspose.email.clients.google/igmailclient/createappointment)(string, Appointment) | Crea un appuntamento. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar)(Calendar) | Crea un calendario. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar_1)(Calendar, bool) | Crea un calendario. |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact)(Contact) | Crea un contatto per l'e-mail specificata |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact_1)(Contact, string) | Crea un contatto per l'e-mail specificata |
| [CreateContactPhoto](../../aspose.email.clients.google/igmailclient/createcontactphoto)(Contact, byte[]) | Crea foto di contatto |
| [DeleteAccessRule](../../aspose.email.clients.google/igmailclient/deleteaccessrule)(string, string) | Elimina la regola di accesso |
| [DeleteAppointment](../../aspose.email.clients.google/igmailclient/deleteappointment)(string, string) | Elimina un appuntamento. |
| [DeleteCalendar](../../aspose.email.clients.google/igmailclient/deletecalendar)(string) | Elimina un calendario. |
| [DeleteContact](../../aspose.email.clients.google/igmailclient/deletecontact)(string) | Elimina il contatto specificato |
| [DeleteContactPhoto](../../aspose.email.clients.google/igmailclient/deletecontactphoto)(ContactPhoto) | Elimina la foto del contatto |
| [FetchAccessRule](../../aspose.email.clients.google/igmailclient/fetchaccessrule)(string, string) | Recupera la regola di accesso |
| [FetchAppointment](../../aspose.email.clients.google/igmailclient/fetchappointment)(string, string) | Recupera l'appuntamento in base all'identificatore. |
| [FetchCalendar](../../aspose.email.clients.google/igmailclient/fetchcalendar)(string) | Recupera il calendario in base all'identificatore. |
| [GetAllContacts](../../aspose.email.clients.google/igmailclient/getallcontacts)() | Recupera tutti i contatti. |
| [GetAllGroups](../../aspose.email.clients.google/igmailclient/getallgroups)() | Recupera tutti i gruppi di contatti. |
| [GetColors](../../aspose.email.clients.google/igmailclient/getcolors)() | Ottiene informazioni sul colore |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact)(Contact) | Contattare per aggiornare[`Contact`](../../aspose.email.personalinfo/contact) oggetto, che rappresenta un contatto di gmail quando l'operazione fallisce |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact_1)(string) | Recupera il contatto |
| [GetContactsFromGroup](../../aspose.email.clients.google/igmailclient/getcontactsfromgroup)(string) | Recupera i contatti appartenenti al gruppo specificato. |
| [GetFreebusyInfo](../../aspose.email.clients.google/igmailclient/getfreebusyinfo)(FreebusyQuery) | Ottiene informazioni sulla disponibilità |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto)(ContactPhoto) | Recupera una foto di contatto |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto_1)(string) | Recupera una foto di contatto |
| [GetSetting](../../aspose.email.clients.google/igmailclient/getsetting)(string) | Ottiene le impostazioni con il nome |
| [GetSettings](../../aspose.email.clients.google/igmailclient/getsettings)() | Ottiene il dizionario delle impostazioni |
| [ImportAppointment](../../aspose.email.clients.google/igmailclient/importappointment)(string, Appointment) | Importa appuntamento nel calendario |
| [ListAccessRules](../../aspose.email.clients.google/igmailclient/listaccessrules)(string) | Ottiene l'elenco delle regole di accesso |
| [ListAppointmentInstances](../../aspose.email.clients.google/igmailclient/listappointmentinstances)(string, string) | Ottiene l'elenco delle istanze di un appuntamento per il calendario. |
| [ListAppointments](../../aspose.email.clients.google/igmailclient/listappointments)(string) | Ottiene l'elenco di un appuntamento per il calendario. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars)() | Ottiene una matrice di calendari. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars_1)(AccessRole, bool) | Ottiene una matrice di calendari. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment)(string, string, string) | Sposta un appuntamento in un altro calendario. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment_1)(string, string, string, bool) | Sposta un appuntamento in un altro calendario. |
| [UpdateAccessRule](../../aspose.email.clients.google/igmailclient/updateaccessrule)(string, AccessControlRule) | Aggiorna la regola di accesso |
| [UpdateAppointment](../../aspose.email.clients.google/igmailclient/updateappointment)(string, Appointment) | Aggiorna un appuntamento. |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar)(Calendar) | Aggiorna un calendario |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar_1)(Calendar, bool) | Aggiorna un calendario |
| [UpdateContact](../../aspose.email.clients.google/igmailclient/updatecontact)(Contact) | Aggiorna il contatto |
| [UpdateContactPhoto](../../aspose.email.clients.google/igmailclient/updatecontactphoto)(ContactPhoto) | Crea o aggiorna la foto del contatto |

### Guarda anche

* interface [IBaseGmailClient](../ibasegmailclient)
* spazio dei nomi [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
