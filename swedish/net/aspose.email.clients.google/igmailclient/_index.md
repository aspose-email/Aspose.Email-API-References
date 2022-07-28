---
title: IGmailClient
second_title: Aspose.Email för .NET API-referens
description: Representerar gränssnittet för Gmail client
type: docs
weight: 15790
url: /sv/net/aspose.email.clients.google/igmailclient/
---
## IGmailClient interface

Representerar gränssnittet för Gmail client

```csharp
public interface IGmailClient : IBaseGmailClient
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| [ClearCalendar](../../aspose.email.clients.google/igmailclient/clearcalendar)(string) | Rensar en kalender. |
| [CreateAccessRule](../../aspose.email.clients.google/igmailclient/createaccessrule)(string, AccessControlRule) | Skapar åtkomstregel |
| [CreateAppointment](../../aspose.email.clients.google/igmailclient/createappointment)(string, Appointment) | Skapar ett möte. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar)(Calendar) | Skapar en kalender. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar_1)(Calendar, bool) | Skapar en kalender. |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact)(Contact) | Skapar kontakt för angiven e-post |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact_1)(Contact, string) | Skapar kontakt för angiven e-post |
| [CreateContactPhoto](../../aspose.email.clients.google/igmailclient/createcontactphoto)(Contact, byte[]) | Skapar kontaktfoto |
| [DeleteAccessRule](../../aspose.email.clients.google/igmailclient/deleteaccessrule)(string, string) | Tar bort åtkomstregel |
| [DeleteAppointment](../../aspose.email.clients.google/igmailclient/deleteappointment)(string, string) | Tar bort ett möte. |
| [DeleteCalendar](../../aspose.email.clients.google/igmailclient/deletecalendar)(string) | Tar bort en kalender. |
| [DeleteContact](../../aspose.email.clients.google/igmailclient/deletecontact)(string) | Tar bort specificerad kontakt |
| [DeleteContactPhoto](../../aspose.email.clients.google/igmailclient/deletecontactphoto)(ContactPhoto) | Tar bort kontaktfoto |
| [FetchAccessRule](../../aspose.email.clients.google/igmailclient/fetchaccessrule)(string, string) | Hämtar åtkomstregel |
| [FetchAppointment](../../aspose.email.clients.google/igmailclient/fetchappointment)(string, string) | Hämtar möte med identifierare. |
| [FetchCalendar](../../aspose.email.clients.google/igmailclient/fetchcalendar)(string) | Hämtar kalender med identifierare. |
| [GetAllContacts](../../aspose.email.clients.google/igmailclient/getallcontacts)() | Hämtar alla kontakter. |
| [GetAllGroups](../../aspose.email.clients.google/igmailclient/getallgroups)() | Hämtar alla kontaktgrupper. |
| [GetColors](../../aspose.email.clients.google/igmailclient/getcolors)() | Får färginformation |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact)(Contact) | Kontakta för att uppdatera[`Contact`](../../aspose.email.personalinfo/contact) objekt, som representerar en kontakt för gmail när driften misslyckas |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact_1)(string) | Hämtar kontakt |
| [GetContactsFromGroup](../../aspose.email.clients.google/igmailclient/getcontactsfromgroup)(string) | Hämtar kontakter som tillhör den angivna gruppen. |
| [GetFreebusyInfo](../../aspose.email.clients.google/igmailclient/getfreebusyinfo)(FreebusyQuery) | Får information om ledig/upptagen |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto)(ContactPhoto) | Hämtar ett kontaktfoto |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto_1)(string) | Hämtar ett kontaktfoto |
| [GetSetting](../../aspose.email.clients.google/igmailclient/getsetting)(string) | Hämtar inställningar med namnet |
| [GetSettings](../../aspose.email.clients.google/igmailclient/getsettings)() | Hämtar inställningsordbok |
| [ImportAppointment](../../aspose.email.clients.google/igmailclient/importappointment)(string, Appointment) | Importerar möte till calendar |
| [ListAccessRules](../../aspose.email.clients.google/igmailclient/listaccessrules)(string) | Får lista över åtkomstregler |
| [ListAppointmentInstances](../../aspose.email.clients.google/igmailclient/listappointmentinstances)(string, string) | Hämtar lista över mötesinstanser för kalender. |
| [ListAppointments](../../aspose.email.clients.google/igmailclient/listappointments)(string) | Hämtar lista över möten för kalender. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars)() | Får en rad kalendrar. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars_1)(AccessRole, bool) | Får en rad kalendrar. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment)(string, string, string) | Flyttar ett möte till en annan kalender. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment_1)(string, string, string, bool) | Flyttar ett möte till en annan kalender. |
| [UpdateAccessRule](../../aspose.email.clients.google/igmailclient/updateaccessrule)(string, AccessControlRule) | Uppdaterar åtkomstregel |
| [UpdateAppointment](../../aspose.email.clients.google/igmailclient/updateappointment)(string, Appointment) | Uppdaterar ett möte. |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar)(Calendar) | Uppdaterar en kalender |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar_1)(Calendar, bool) | Uppdaterar en kalender |
| [UpdateContact](../../aspose.email.clients.google/igmailclient/updatecontact)(Contact) | Uppdateringar kontakt |
| [UpdateContactPhoto](../../aspose.email.clients.google/igmailclient/updatecontactphoto)(ContactPhoto) | Skapar eller uppdaterar kontaktfoto |

### Se även

* interface [IBaseGmailClient](../ibasegmailclient)
* namnutrymme [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
