---
title: Interface IGmailClient
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Google.IGmailClient interface. Represents the interface for Gmail client
type: docs
weight: 15790
url: /net/aspose.email.clients.google/igmailclient/
---
## IGmailClient interface

Represents the interface for Gmail client

```csharp
public interface IGmailClient : IBaseGmailClient
```

## Methods

| Name | Description |
| --- | --- |
| [ClearCalendar](../../aspose.email.clients.google/igmailclient/clearcalendar/)(string) | Clears a calendar. |
| [CreateAccessRule](../../aspose.email.clients.google/igmailclient/createaccessrule/)(string, AccessControlRule) | Creates access rule |
| [CreateAppointment](../../aspose.email.clients.google/igmailclient/createappointment/)(string, Appointment) | Creates an appointment. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar/#createcalendar)(Calendar) | Creates a calendar. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar/#createcalendar_1)(Calendar, bool) | Creates a calendar. |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact/#createcontact)(Contact) | Creates contact for specified email |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact/#createcontact_1)(Contact, string) | Creates contact for specified email |
| [CreateContactPhoto](../../aspose.email.clients.google/igmailclient/createcontactphoto/)(Contact, byte[]) | Creates contact photo |
| [DeleteAccessRule](../../aspose.email.clients.google/igmailclient/deleteaccessrule/)(string, string) | Deletes access rule |
| [DeleteAppointment](../../aspose.email.clients.google/igmailclient/deleteappointment/)(string, string) | Deletes an appointment. |
| [DeleteCalendar](../../aspose.email.clients.google/igmailclient/deletecalendar/)(string) | Deletes a calendar. |
| [DeleteContact](../../aspose.email.clients.google/igmailclient/deletecontact/)(string) | Deletes specified contact |
| [DeleteContactPhoto](../../aspose.email.clients.google/igmailclient/deletecontactphoto/)(ContactPhoto) | Deletes contact photo |
| [FetchAccessRule](../../aspose.email.clients.google/igmailclient/fetchaccessrule/)(string, string) | Fetches access rule |
| [FetchAppointment](../../aspose.email.clients.google/igmailclient/fetchappointment/)(string, string) | Fetches appointment by identifier. |
| [FetchCalendar](../../aspose.email.clients.google/igmailclient/fetchcalendar/)(string) | Fetches calendar by identifier. |
| [GetAllContacts](../../aspose.email.clients.google/igmailclient/getallcontacts/)() | Fetches all contacts. |
| [GetAllGroups](../../aspose.email.clients.google/igmailclient/getallgroups/)() | Fetches all contact groups. |
| [GetColors](../../aspose.email.clients.google/igmailclient/getcolors/)() | Gets color information |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact/#getcontact)(Contact) | Contact to refreshContact object, that represents a contact of gmail when operation fails |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact/#getcontact_1)(string) | Fetches contact |
| [GetContactsFromGroup](../../aspose.email.clients.google/igmailclient/getcontactsfromgroup/)(string) | Fetches contacts belonging to the group specified. |
| [GetFreebusyInfo](../../aspose.email.clients.google/igmailclient/getfreebusyinfo/)(FreebusyQuery) | Gets free/busy information |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto/#getphoto)(ContactPhoto) | Fetches a contact photo |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto/#getphoto_1)(string) | Fetches a contact photo |
| [GetSetting](../../aspose.email.clients.google/igmailclient/getsetting/)(string) | Gets settings by the name |
| [GetSettings](../../aspose.email.clients.google/igmailclient/getsettings/)() | Gets settings dictionary |
| [ImportAppointment](../../aspose.email.clients.google/igmailclient/importappointment/)(string, Appointment) | Imports appointment to calendar |
| [ListAccessRules](../../aspose.email.clients.google/igmailclient/listaccessrules/)(string) | Gets list of access rules |
| [ListAppointmentInstances](../../aspose.email.clients.google/igmailclient/listappointmentinstances/)(string, string) | Gets list of an appointment instances for calendar. |
| [ListAppointments](../../aspose.email.clients.google/igmailclient/listappointments/)(string) | Gets list of an appointments for calendar. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars/#listcalendars)() | Gets array of calendars. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars/#listcalendars_1)(AccessRole, bool) | Gets array of calendars. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment/#moveappointment)(string, string, string) | Moves an appointment to another calendar. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment/#moveappointment_1)(string, string, string, bool) | Moves an appointment to another calendar. |
| [UpdateAccessRule](../../aspose.email.clients.google/igmailclient/updateaccessrule/)(string, AccessControlRule) | Updates access rule |
| [UpdateAppointment](../../aspose.email.clients.google/igmailclient/updateappointment/)(string, Appointment) | Updates an appointment. |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar/#updatecalendar)(Calendar) | Updates a calendar |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar/#updatecalendar_1)(Calendar, bool) | Updates a calendar |
| [UpdateContact](../../aspose.email.clients.google/igmailclient/updatecontact/)(Contact) | Updates contact |
| [UpdateContactPhoto](../../aspose.email.clients.google/igmailclient/updatecontactphoto/)(ContactPhoto) | Creates or updates contact photo |

### See Also

* interface [IBaseGmailClient](../ibasegmailclient/)
* namespace [Aspose.Email.Clients.Google](../../aspose.email.clients.google/)
* assembly [Aspose.Email](../../)


