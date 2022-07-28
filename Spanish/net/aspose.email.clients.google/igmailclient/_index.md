---
title: IGmailClient
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa la interfaz para Gmail client
type: docs
weight: 15790
url: /es/net/aspose.email.clients.google/igmailclient/
---
## IGmailClient interface

Representa la interfaz para Gmail client

```csharp
public interface IGmailClient : IBaseGmailClient
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ClearCalendar](../../aspose.email.clients.google/igmailclient/clearcalendar)(string) | Borra un calendario. |
| [CreateAccessRule](../../aspose.email.clients.google/igmailclient/createaccessrule)(string, AccessControlRule) | Crea regla de acceso |
| [CreateAppointment](../../aspose.email.clients.google/igmailclient/createappointment)(string, Appointment) | Crea una cita. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar)(Calendar) | Crea un calendario. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar_1)(Calendar, bool) | Crea un calendario. |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact)(Contact) | Crea contacto para el correo electrónico especificado |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact_1)(Contact, string) | Crea contacto para el correo electrónico especificado |
| [CreateContactPhoto](../../aspose.email.clients.google/igmailclient/createcontactphoto)(Contact, byte[]) | Crea foto de contacto |
| [DeleteAccessRule](../../aspose.email.clients.google/igmailclient/deleteaccessrule)(string, string) | Borra regla de acceso |
| [DeleteAppointment](../../aspose.email.clients.google/igmailclient/deleteappointment)(string, string) | Elimina una cita. |
| [DeleteCalendar](../../aspose.email.clients.google/igmailclient/deletecalendar)(string) | Elimina un calendario. |
| [DeleteContact](../../aspose.email.clients.google/igmailclient/deletecontact)(string) | Elimina el contacto especificado |
| [DeleteContactPhoto](../../aspose.email.clients.google/igmailclient/deletecontactphoto)(ContactPhoto) | Elimina foto de contacto |
| [FetchAccessRule](../../aspose.email.clients.google/igmailclient/fetchaccessrule)(string, string) | Obtiene la regla de acceso |
| [FetchAppointment](../../aspose.email.clients.google/igmailclient/fetchappointment)(string, string) | Obtiene cita por identificador. |
| [FetchCalendar](../../aspose.email.clients.google/igmailclient/fetchcalendar)(string) | Obtiene calendario por identificador. |
| [GetAllContacts](../../aspose.email.clients.google/igmailclient/getallcontacts)() | Obtiene todos los contactos. |
| [GetAllGroups](../../aspose.email.clients.google/igmailclient/getallgroups)() | Obtiene todos los grupos de contactos. |
| [GetColors](../../aspose.email.clients.google/igmailclient/getcolors)() | Obtiene información de color |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact)(Contact) | Contacto para actualizar[`Contact`](../../aspose.email.personalinfo/contact) objeto, que representa un contacto de gmail cuando la operación falla |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact_1)(string) | Obtiene contacto |
| [GetContactsFromGroup](../../aspose.email.clients.google/igmailclient/getcontactsfromgroup)(string) | Obtiene contactos pertenecientes al grupo especificado. |
| [GetFreebusyInfo](../../aspose.email.clients.google/igmailclient/getfreebusyinfo)(FreebusyQuery) | Obtiene información de libre/ocupado |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto)(ContactPhoto) | Obtiene una foto de contacto |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto_1)(string) | Obtiene una foto de contacto |
| [GetSetting](../../aspose.email.clients.google/igmailclient/getsetting)(string) | Obtiene la configuración por el nombre |
| [GetSettings](../../aspose.email.clients.google/igmailclient/getsettings)() | Obtiene el diccionario de configuración |
| [ImportAppointment](../../aspose.email.clients.google/igmailclient/importappointment)(string, Appointment) | Importa cita al calendario |
| [ListAccessRules](../../aspose.email.clients.google/igmailclient/listaccessrules)(string) | Obtiene la lista de reglas de acceso |
| [ListAppointmentInstances](../../aspose.email.clients.google/igmailclient/listappointmentinstances)(string, string) | Obtiene una lista de instancias de citas para el calendario. |
| [ListAppointments](../../aspose.email.clients.google/igmailclient/listappointments)(string) | Obtiene una lista de citas para el calendario. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars)() | Obtiene una matriz de calendarios. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars_1)(AccessRole, bool) | Obtiene una matriz de calendarios. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment)(string, string, string) | Mueve una cita a otro calendario. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment_1)(string, string, string, bool) | Mueve una cita a otro calendario. |
| [UpdateAccessRule](../../aspose.email.clients.google/igmailclient/updateaccessrule)(string, AccessControlRule) | Regla de acceso a actualizaciones |
| [UpdateAppointment](../../aspose.email.clients.google/igmailclient/updateappointment)(string, Appointment) | Actualiza una cita. |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar)(Calendar) | Actualiza un calendario |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar_1)(Calendar, bool) | Actualiza un calendario |
| [UpdateContact](../../aspose.email.clients.google/igmailclient/updatecontact)(Contact) | Actualizaciones contacto |
| [UpdateContactPhoto](../../aspose.email.clients.google/igmailclient/updatecontactphoto)(ContactPhoto) | Crea o actualiza foto de contacto |

### Ver también

* interface [IBaseGmailClient](../ibasegmailclient)
* espacio de nombres [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
