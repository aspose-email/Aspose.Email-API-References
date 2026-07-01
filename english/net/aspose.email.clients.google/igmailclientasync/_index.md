---
title: Interface IGmailClientAsync
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Google.IGmailClientAsync interface. Represents the interface with asynchronous operations for Gmail client
type: docs
weight: 14440
url: /net/aspose.email.clients.google/igmailclientasync/
---
## IGmailClientAsync interface

Represents the interface with asynchronous operations for Gmail client.

```csharp
public interface IGmailClientAsync : IGmailClient
```

## Methods

| Name | Description |
| --- | --- |
| [AppendMessageAsync](../../aspose.email.clients.google/igmailclientasync/appendmessageasync/#appendmessageasync_1)(MailMessage, CancellationToken) | Asynchronously appends a message to the default "INBOX" label. |
| [AppendMessageAsync](../../aspose.email.clients.google/igmailclientasync/appendmessageasync/#appendmessageasync)(MailMessage, string, CancellationToken) | Asynchronously appends a message to the specified label. |
| [ClearCalendarAsync](../../aspose.email.clients.google/igmailclientasync/clearcalendarasync/)(string, CancellationToken) | Asynchronously clears all events from the specified calendar. |
| [CreateAccessRuleAsync](../../aspose.email.clients.google/igmailclientasync/createaccessruleasync/)(string, AccessControlRule, CancellationToken) | Asynchronously creates an access control rule for a calendar. |
| [CreateAppointmentAsync](../../aspose.email.clients.google/igmailclientasync/createappointmentasync/)(string, Appointment, CancellationToken) | Asynchronously creates an appointment in the specified calendar. |
| [CreateCalendarAsync](../../aspose.email.clients.google/igmailclientasync/createcalendarasync/#createcalendarasync)(Calendar, CancellationToken) | Asynchronously creates a calendar. |
| [CreateCalendarAsync](../../aspose.email.clients.google/igmailclientasync/createcalendarasync/#createcalendarasync_1)(Calendar, bool, CancellationToken) | Asynchronously creates a calendar and optionally an extended calendar. |
| [CreateContactAsync](../../aspose.email.clients.google/igmailclientasync/createcontactasync/#createcontactasync_1)(Contact, CancellationToken) | Asynchronously creates a contact using the default email address. |
| [CreateContactAsync](../../aspose.email.clients.google/igmailclientasync/createcontactasync/#createcontactasync)(Contact, string, CancellationToken) | Asynchronously creates a contact with the specified email address. |
| [CreateContactPhotoAsync](../../aspose.email.clients.google/igmailclientasync/createcontactphotoasync/)(Contact, byte[], CancellationToken) | Asynchronously creates a contact photo. |
| [CreateExtCalendarAsync](../../aspose.email.clients.google/igmailclientasync/createextcalendarasync/#createextcalendarasync_1)(ExtendedCalendar, CancellationToken) | Asynchronously creates an extended calendar. |
| [CreateExtCalendarAsync](../../aspose.email.clients.google/igmailclientasync/createextcalendarasync/#createextcalendarasync)(ExtendedCalendar, bool, CancellationToken) | Asynchronously creates an extended calendar with color format option. |
| [CreateFilterAsync](../../aspose.email.clients.google/igmailclientasync/createfilterasync/)(Filter, CancellationToken) | Asynchronously creates a Gmail filter. |
| [DeleteAccessRuleAsync](../../aspose.email.clients.google/igmailclientasync/deleteaccessruleasync/)(string, string, CancellationToken) | Asynchronously deletes an access control rule from a calendar. |
| [DeleteAppointmentAsync](../../aspose.email.clients.google/igmailclientasync/deleteappointmentasync/)(string, string, CancellationToken) | Asynchronously deletes an appointment from the specified calendar. |
| [DeleteCalendarAsync](../../aspose.email.clients.google/igmailclientasync/deletecalendarasync/)(string, CancellationToken) | Asynchronously deletes a calendar by its ID. |
| [DeleteContactAsync](../../aspose.email.clients.google/igmailclientasync/deletecontactasync/)(string, CancellationToken) | Asynchronously deletes a contact by its URI. |
| [DeleteContactPhotoAsync](../../aspose.email.clients.google/igmailclientasync/deletecontactphotoasync/)(ContactPhoto, CancellationToken) | Asynchronously deletes a contact photo. |
| [DeleteExtCalendarAsync](../../aspose.email.clients.google/igmailclientasync/deleteextcalendarasync/)(string, CancellationToken) | Asynchronously deletes an extended calendar by its ID. |
| [DeleteFilterAsync](../../aspose.email.clients.google/igmailclientasync/deletefilterasync/)(string, CancellationToken) | Asynchronously deletes a Gmail filter by its ID. |
| [DeleteMessageAsync](../../aspose.email.clients.google/igmailclientasync/deletemessageasync/#deletemessageasync_1)(string, CancellationToken) | Asynchronously deletes a message by its ID, moving it to trash by default. |
| [DeleteMessageAsync](../../aspose.email.clients.google/igmailclientasync/deletemessageasync/#deletemessageasync)(string, bool, CancellationToken) | Asynchronously deletes a message by its ID, with an option to move to trash. |
| [FetchAccessRuleAsync](../../aspose.email.clients.google/igmailclientasync/fetchaccessruleasync/)(string, string, CancellationToken) | Asynchronously fetches an access control rule by its ID from a calendar. |
| [FetchAppointmentAsync](../../aspose.email.clients.google/igmailclientasync/fetchappointmentasync/)(string, string, CancellationToken) | Asynchronously fetches an appointment by its ID from the specified calendar. |
| [FetchCalendar2Async](../../aspose.email.clients.google/igmailclientasync/fetchcalendar2async/)(string, CancellationToken) | Asynchronously fetches a calendar by its ID. |
| [FetchCalendarAsync](../../aspose.email.clients.google/igmailclientasync/fetchcalendarasync/)(string, CancellationToken) | Asynchronously fetches an extended calendar by its ID. |
| [FetchExtCalendarAsync](../../aspose.email.clients.google/igmailclientasync/fetchextcalendarasync/)(string, CancellationToken) | Asynchronously fetches an extended calendar by its ID. |
| [FetchMessageAsync](../../aspose.email.clients.google/igmailclientasync/fetchmessageasync/)(string, CancellationToken) | Asynchronously fetches a Gmail message by its ID. |
| [GetAllContactsAsync](../../aspose.email.clients.google/igmailclientasync/getallcontactsasync/)(CancellationToken) | Asynchronously retrieves all contacts for the user. |
| [GetAllGroupsAsync](../../aspose.email.clients.google/igmailclientasync/getallgroupsasync/)(CancellationToken) | Asynchronously retrieves all contact groups for the user. |
| [GetColorsAsync](../../aspose.email.clients.google/igmailclientasync/getcolorsasync/)(CancellationToken) | Asynchronously retrieves color information for the user. |
| [GetContactAsync](../../aspose.email.clients.google/igmailclientasync/getcontactasync/#getcontactasync)(Contact, CancellationToken) | Asynchronously retrieves a contact by its object. |
| [GetContactAsync](../../aspose.email.clients.google/igmailclientasync/getcontactasync/#getcontactasync_1)(string, CancellationToken) | Asynchronously retrieves a contact by its URI. |
| [GetContactsFromGroupAsync](../../aspose.email.clients.google/igmailclientasync/getcontactsfromgroupasync/#getcontactsfromgroupasync)(GoogleContactGroup, CancellationToken) | Asynchronously retrieves contacts from a contact group. |
| [GetContactsFromGroupAsync](../../aspose.email.clients.google/igmailclientasync/getcontactsfromgroupasync/#getcontactsfromgroupasync_1)(string, CancellationToken) | Asynchronously retrieves contacts from a contact group by group ID. |
| [GetFilterAsync](../../aspose.email.clients.google/igmailclientasync/getfilterasync/)(string, CancellationToken) | Asynchronously retrieves a Gmail filter by its ID. |
| [GetFreebusyInfoAsync](../../aspose.email.clients.google/igmailclientasync/getfreebusyinfoasync/)(FreebusyQuery, CancellationToken) | Asynchronously retrieves free/busy information for the specified query. |
| [GetSettingAsync](../../aspose.email.clients.google/igmailclientasync/getsettingasync/)(string, CancellationToken) | Asynchronously retrieves a specific setting by name. |
| [GetSettingsAsync](../../aspose.email.clients.google/igmailclientasync/getsettingsasync/)(CancellationToken) | Asynchronously retrieves all settings for the user. |
| [ImportAppointmentAsync](../../aspose.email.clients.google/igmailclientasync/importappointmentasync/)(string, Appointment, CancellationToken) | Asynchronously imports an appointment into the specified calendar. |
| [ListAccessRulesAsync](../../aspose.email.clients.google/igmailclientasync/listaccessrulesasync/)(string, CancellationToken) | Asynchronously retrieves all access control rules for a calendar. |
| [ListAppointmentInstancesAsync](../../aspose.email.clients.google/igmailclientasync/listappointmentinstancesasync/)(string, string, CancellationToken) | Asynchronously retrieves all instances of a recurring appointment. |
| [ListAppointmentsAsync](../../aspose.email.clients.google/igmailclientasync/listappointmentsasync/)(string, CancellationToken) | Asynchronously retrieves all appointments from the specified calendar. |
| [ListCalendarsAsync](../../aspose.email.clients.google/igmailclientasync/listcalendarsasync/#listcalendarsasync_1)(CancellationToken) | Asynchronously retrieves the list of calendars for the user. |
| [ListCalendarsAsync](../../aspose.email.clients.google/igmailclientasync/listcalendarsasync/#listcalendarsasync)(AccessRole, bool, CancellationToken) | Asynchronously retrieves the list of calendars for the user. |
| [ListFiltersAsync](../../aspose.email.clients.google/igmailclientasync/listfiltersasync/)(CancellationToken) | Asynchronously retrieves a list of Gmail filters. |
| [ListMessagesAsync](../../aspose.email.clients.google/igmailclientasync/listmessagesasync/)(CancellationToken) | Asynchronously retrieves a list of Gmail messages. |
| [MoveAppointmentAsync](../../aspose.email.clients.google/igmailclientasync/moveappointmentasync/#moveappointmentasync_1)(string, string, string, CancellationToken) | Asynchronously moves an appointment to another calendar. |
| [MoveAppointmentAsync](../../aspose.email.clients.google/igmailclientasync/moveappointmentasync/#moveappointmentasync)(string, string, string, bool, CancellationToken) | Asynchronously moves an appointment to another calendar with notification option. |
| [SendMessageAsync](../../aspose.email.clients.google/igmailclientasync/sendmessageasync/)(MailMessage, CancellationToken) | Asynchronously sends a Gmail message. |
| [UpdateAccessRuleAsync](../../aspose.email.clients.google/igmailclientasync/updateaccessruleasync/)(string, AccessControlRule, CancellationToken) | Asynchronously updates an access control rule for a calendar. |
| [UpdateAppointmentAsync](../../aspose.email.clients.google/igmailclientasync/updateappointmentasync/)(string, Appointment, CancellationToken) | Asynchronously updates an appointment in the specified calendar. |
| [UpdateCalendarAsync](../../aspose.email.clients.google/igmailclientasync/updatecalendarasync/)(Calendar, CancellationToken) | Asynchronously updates a calendar. |
| [UpdateContactAsync](../../aspose.email.clients.google/igmailclientasync/updatecontactasync/)(Contact, CancellationToken) | Asynchronously updates a contact. |
| [UpdateContactPhotoAsync](../../aspose.email.clients.google/igmailclientasync/updatecontactphotoasync/)(ContactPhoto, CancellationToken) | Asynchronously updates a contact photo. |
| [UpdateExtCalendarAsync](../../aspose.email.clients.google/igmailclientasync/updateextcalendarasync/#updateextcalendarasync_1)(ExtendedCalendar, CancellationToken) | Asynchronously updates an extended calendar. |
| [UpdateExtCalendarAsync](../../aspose.email.clients.google/igmailclientasync/updateextcalendarasync/#updateextcalendarasync)(ExtendedCalendar, bool, CancellationToken) | Asynchronously updates an extended calendar with color format option. |

### See Also

* interface [IGmailClient](../igmailclient/)
* namespace [Aspose.Email.Clients.Google](../../aspose.email.clients.google/)
* assembly [Aspose.Email](../../)


