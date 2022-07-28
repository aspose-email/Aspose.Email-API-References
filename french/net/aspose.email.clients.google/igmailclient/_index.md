---
title: IGmailClient
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente linterface pour le client Gmail
type: docs
weight: 15790
url: /fr/net/aspose.email.clients.google/igmailclient/
---
## IGmailClient interface

Représente l'interface pour le client Gmail

```csharp
public interface IGmailClient : IBaseGmailClient
```

## Méthodes

| Nom | La description |
| --- | --- |
| [ClearCalendar](../../aspose.email.clients.google/igmailclient/clearcalendar)(string) | Efface un calendrier. |
| [CreateAccessRule](../../aspose.email.clients.google/igmailclient/createaccessrule)(string, AccessControlRule) | Crée une règle d'accès |
| [CreateAppointment](../../aspose.email.clients.google/igmailclient/createappointment)(string, Appointment) | Crée un rendez-vous. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar)(Calendar) | Crée un calendrier. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar_1)(Calendar, bool) | Crée un calendrier. |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact)(Contact) | Crée un contact pour l'e-mail spécifié |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact_1)(Contact, string) | Crée un contact pour l'e-mail spécifié |
| [CreateContactPhoto](../../aspose.email.clients.google/igmailclient/createcontactphoto)(Contact, byte[]) | Crée une photo de contact |
| [DeleteAccessRule](../../aspose.email.clients.google/igmailclient/deleteaccessrule)(string, string) | Supprime la règle d'accès |
| [DeleteAppointment](../../aspose.email.clients.google/igmailclient/deleteappointment)(string, string) | Supprime un rendez-vous. |
| [DeleteCalendar](../../aspose.email.clients.google/igmailclient/deletecalendar)(string) | Supprime un calendrier. |
| [DeleteContact](../../aspose.email.clients.google/igmailclient/deletecontact)(string) | Supprime le contact spécifié |
| [DeleteContactPhoto](../../aspose.email.clients.google/igmailclient/deletecontactphoto)(ContactPhoto) | Supprime la photo du contact |
| [FetchAccessRule](../../aspose.email.clients.google/igmailclient/fetchaccessrule)(string, string) | Récupère la règle d'accès |
| [FetchAppointment](../../aspose.email.clients.google/igmailclient/fetchappointment)(string, string) | Récupère le rendez-vous par identifiant. |
| [FetchCalendar](../../aspose.email.clients.google/igmailclient/fetchcalendar)(string) | Récupère le calendrier par identifiant. |
| [GetAllContacts](../../aspose.email.clients.google/igmailclient/getallcontacts)() | Récupère tous les contacts. |
| [GetAllGroups](../../aspose.email.clients.google/igmailclient/getallgroups)() | Récupère tous les groupes de contacts. |
| [GetColors](../../aspose.email.clients.google/igmailclient/getcolors)() | Obtient les informations de couleur |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact)(Contact) | Contact pour rafraichir[`Contact`](../../aspose.email.personalinfo/contact) objet, qui représente un contact de gmail lorsque l'opération échoue |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact_1)(string) | Récupère le contact |
| [GetContactsFromGroup](../../aspose.email.clients.google/igmailclient/getcontactsfromgroup)(string) | Récupère les contacts appartenant au groupe spécifié. |
| [GetFreebusyInfo](../../aspose.email.clients.google/igmailclient/getfreebusyinfo)(FreebusyQuery) | Obtient des informations de disponibilité |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto)(ContactPhoto) | Récupère une photo de contact |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto_1)(string) | Récupère une photo de contact |
| [GetSetting](../../aspose.email.clients.google/igmailclient/getsetting)(string) | Obtient les paramètres par le nom |
| [GetSettings](../../aspose.email.clients.google/igmailclient/getsettings)() | Récupère le dictionnaire des paramètres |
| [ImportAppointment](../../aspose.email.clients.google/igmailclient/importappointment)(string, Appointment) | Importe le rendez-vous dans le calendrier |
| [ListAccessRules](../../aspose.email.clients.google/igmailclient/listaccessrules)(string) | Obtient la liste des règles d'accès |
| [ListAppointmentInstances](../../aspose.email.clients.google/igmailclient/listappointmentinstances)(string, string) | Obtient la liste des instances de rendez-vous pour le calendrier. |
| [ListAppointments](../../aspose.email.clients.google/igmailclient/listappointments)(string) | Obtient la liste d'un rendez-vous pour le calendrier. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars)() | Obtient un tableau de calendriers. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars_1)(AccessRole, bool) | Obtient un tableau de calendriers. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment)(string, string, string) | Déplace un rendez-vous vers un autre calendrier. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment_1)(string, string, string, bool) | Déplace un rendez-vous vers un autre calendrier. |
| [UpdateAccessRule](../../aspose.email.clients.google/igmailclient/updateaccessrule)(string, AccessControlRule) | Met à jour la règle d'accès |
| [UpdateAppointment](../../aspose.email.clients.google/igmailclient/updateappointment)(string, Appointment) | Met à jour un rendez-vous. |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar)(Calendar) | Met à jour un calendrier |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar_1)(Calendar, bool) | Met à jour un calendrier |
| [UpdateContact](../../aspose.email.clients.google/igmailclient/updatecontact)(Contact) | Met à jour le contact |
| [UpdateContactPhoto](../../aspose.email.clients.google/igmailclient/updatecontactphoto)(ContactPhoto) | Crée ou met à jour la photo de contact |

### Voir également

* interface [IBaseGmailClient](../ibasegmailclient)
* espace de noms [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
