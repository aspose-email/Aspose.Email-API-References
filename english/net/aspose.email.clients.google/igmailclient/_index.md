---
title: Interface IGmailClient
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Google.IGmailClient interface. Represents the interface for Gmail client
type: docs
weight: 14390
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
| [AppendMessage](../../aspose.email.clients.google/igmailclient/appendmessage/#appendmessage)(MailMessage) | Directly appends a message into INBOX similar to IMAP APPEND, bypassing most scanning and classification. Does not send a message. |
| [AppendMessage](../../aspose.email.clients.google/igmailclient/appendmessage/#appendmessage_1)(MailMessage, string) | Directly appends a message into only this user's mailbox similar to IMAP APPEND, bypassing most scanning and classification. Does not send a message. |
| [ClearCalendar](../../aspose.email.clients.google/igmailclient/clearcalendar/)(string) | Clears a calendar. |
| [CreateAccessRule](../../aspose.email.clients.google/igmailclient/createaccessrule/)(string, AccessControlRule) | Creates access rule |
| [CreateAppointment](../../aspose.email.clients.google/igmailclient/createappointment/)(string, Appointment) | Creates an appointment. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar/#createcalendar)(Calendar) | Creates a calendar. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar/#createcalendar_1)(Calendar, bool) | Creates a calendar. |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact/#createcontact)(Contact) | Creates contact for specified email |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact/#createcontact_1)(Contact, string) | Creates contact for specified email |
| [CreateContactPhoto](../../aspose.email.clients.google/igmailclient/createcontactphoto/)(Contact, byte[]) | Creates contact photo |
| [CreateFilter](../../aspose.email.clients.google/igmailclient/createfilter/)(Filter) | Creates a filter. |
| [DeleteAccessRule](../../aspose.email.clients.google/igmailclient/deleteaccessrule/)(string, string) | Deletes access rule |
| [DeleteAppointment](../../aspose.email.clients.google/igmailclient/deleteappointment/)(string, string) | Deletes an appointment. |
| [DeleteCalendar](../../aspose.email.clients.google/igmailclient/deletecalendar/)(string) | Deletes a calendar. |
| [DeleteContact](../../aspose.email.clients.google/igmailclient/deletecontact/)(string) | Deletes specified contact |
| [DeleteContactPhoto](../../aspose.email.clients.google/igmailclient/deletecontactphoto/)(ContactPhoto) | Deletes contact photo |
| [DeleteFilter](../../aspose.email.clients.google/igmailclient/deletefilter/)(string) | Immediately and permanently deletes the specified filter. |
| [DeleteMessage](../../aspose.email.clients.google/igmailclient/deletemessage/#deletemessage)(string) | Immediately and permanently deletes the specified message. This operation cannot be undone. Prefer overriding method DeleteMessage with parameter moveToTrash instead. |
| [DeleteMessage](../../aspose.email.clients.google/igmailclient/deletemessage/#deletemessage_1)(string, bool) | Moves the specified message to the trash if moveToTrash true, or permanently deletes if false. |
| [FetchAccessRule](../../aspose.email.clients.google/igmailclient/fetchaccessrule/)(string, string) | Fetches access rule |
| [FetchAppointment](../../aspose.email.clients.google/igmailclient/fetchappointment/)(string, string) | Fetches appointment by identifier. |
| [FetchCalendar](../../aspose.email.clients.google/igmailclient/fetchcalendar/)(string) | Fetches calendar by identifier. |
| [FetchMessage](../../aspose.email.clients.google/igmailclient/fetchmessage/)(string) | Gets the specified message. |
| [GetAllContacts](../../aspose.email.clients.google/igmailclient/getallcontacts/)() | Fetches all contacts. |
| [GetAllGroups](../../aspose.email.clients.google/igmailclient/getallgroups/)() | Fetches all contact groups. |
| [GetColors](../../aspose.email.clients.google/igmailclient/getcolors/)() | Gets color information |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact/#getcontact)(Contact) | Contact to refresh[`Contact`](../../aspose.email.personalinfo/contact/) object, that represents a contact of gmail when operation fails |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact/#getcontact_1)(string) | Fetches contact |
| [GetContactsFromGroup](../../aspose.email.clients.google/igmailclient/getcontactsfromgroup/)(string) | Fetches contacts belonging to the group specified. |
| [GetFilter](../../aspose.email.clients.google/igmailclient/getfilter/)(string) | Gets a filter. |
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
| [ListFilters](../../aspose.email.clients.google/igmailclient/listfilters/)() | Lists the message filters of a Gmail user. |
| [ListMessages](../../aspose.email.clients.google/igmailclient/listmessages/)() | Lists the messages in the user's mailbox. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment/#moveappointment)(string, string, string) | Moves an appointment to another calendar. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment/#moveappointment_1)(string, string, string, bool) | Moves an appointment to another calendar. |
| [SendMessage](../../aspose.email.clients.google/igmailclient/sendmessage/)(MailMessage) | Sends the specified message to the recipients in the To, Cc, and Bcc headers. |
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


