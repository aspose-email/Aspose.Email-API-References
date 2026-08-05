---
title: "Aspose::Email::Clients::Graph::IGraphClient class"
linktitle: "IGraphClient"
articleTitle: "IGraphClient"
second_title: "Aspose.Email for C++"
description: "Represents the interface for Graph REST client."
type: docs
weight: 10
url: /cpp/aspose.email.clients.graph/igraphclient/
---

## IGraphClient class

Represents the interface for Graph REST client.

## Methods

| Name | Description |
| --- | --- |
| [CopyFolder](./copyfolder/) | Copy a mailfolder and its contents to another mailfolder. |
| [CopyMessage](./copymessage/) | Copy a Message to another mailfolder. |
| [CopyNotebook](./copynotebook/) | Copies a notebook to the Notebooks folder in the destination Documents library. The folder is created if it doesn't exist. For Copy operations, you follow an asynchronous calling pattern: First call the Copy action, and then poll the operation endpoint for the result. Permissions One of the following permissions is required to call this API. Delegated(work or school account) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegated(personal Microsoft account) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateAttachment](./createattachment/) | Creates new attachment for specified item |
| [CreateCalendarItem](./createcalendaritem/) | Creates MapiCalendar in specified calendar |
| [CreateCategory](./createcategory/) | Creates an OutlookCategory object in the user's master list of categories. |
| [CreateContact](./createcontact/) | Creates contact in specified folder |
| [CreateFolder (2 overloads)](./createfolder/) | Create new folder. |
| [CreateMessage (2 overloads)](./createmessage/) | Creates message in specified folder |
| [CreateNotebook](./createnotebook/) | Create a new OneNote notebook. Permissions One of the following permissions is required to call this API. Delegated (work or school account) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegated (personal Microsoft account) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateOrUpdateOverride (2 overloads)](./createorupdateoverride/) | Create an override for a sender identified by an SMTP address. Future messages from that SMTP address will be consistently classified as specified in the override. Note: |
| [CreateRule](./createrule/) | Create a message rule by specifying a set of conditions and actions. Outlook carries out those actions if an incoming message in the user's Inbox meets the specified conditions. Permissions: One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) MailboxSettings.ReadWrite Delegated (personal Microsoft account) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |
| [CreateTask](./createtask/) | Creates Task in specified folder |
| [CreateTaskList](./createtasklist/) | Creates new TaskList. |
| [Delete](./delete/) | Delete object. |
| [DeleteAttachment](./deleteattachment/) | Removes attachment |
| [DeleteTaskList](./deletetasklist/) | Delete TaskList. |
| [FetchAttachment](./fetchattachment/) | Gets attachment for specified id |
| [FetchCalendarItem](./fetchcalendaritem/) | Gets MapiCalendar for specified id |
| [FetchCategory](./fetchcategory/) | Get the properties and relationships of the specified outlookCategory object. |
| [FetchContact](./fetchcontact/) | Gets MapiContact for specified id |
| [FetchMessage](./fetchmessage/) | Gets message in specified id |
| [FetchNotebook](./fetchnotebook/) | Retrieve the properties and relationships of a notebook object. Permissions One of the following permissions is required to call this API. Delegated (work or school account) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All, Notes.ReadWrite.All Delegated (personal Microsoft account) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [FetchRule](./fetchrule/) | Get the properties and relationships of a message rule object. Permissions One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) MailboxSettings.Read Delegated (personal Microsoft account) MailboxSettings.Read Application MailboxSettings.Read |
| [FetchTask](./fetchtask/) | Gets MapiTask for specified id |
| [get_EndPoint](./get_endpoint/) | Gets Microsoft Graph REST API endpoint. If not specified, the default is "https://graph.microsoft.com". |
| [get_MultipleServicesTokenProvider](./get_multipleservicestokenprovider/) | Gets an object allows to retrieve OAuth access token. |
| [get_Proxy](./get_proxy/) | Gets data to proxy access to Exchange server. |
| [get_Resource](./get_resource/) | Gets resource type. |
| [get_ResourceId](./get_resourceid/) | Gets resource id. For instance for users it may be user principal name (UPN) or user id |
| [get_TenantId](./get_tenantid/) | Gets tenant identifier |
| [get_Timeout](./get_timeout/) | Gets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds). |
| [get_TokenProvider](./get_tokenprovider/) | Gets an object allows to retrieve OAuth access token. |
| [GetContactFolder](./getcontactfolder/) | Gets main contact folder. This method requires that at least one contact exists in the main contacts folder, otherwise it will return null. https://learn.microsoft.com/en-us/answers/questions/854621/how-to-get-folder-id-of-default-contacts-folder-wh |
| [GetFolder](./getfolder/) | Gets folder by an id. |
| [GetOneNoteOperationStatus](./getonenoteoperationstatus/) | Get the status of a long-running OneNote operation. This applies to operations that return the Operation-Location header in the response, such as CopyNotebook, CopyToNotebook, CopyToSectionGroup, and CopyToSection. You can poll the Operation-Location endpoint until the status property returns completed or failed. If the status is completed, the resourceLocation property contains the resource endpoint URI. If the status is failed, the error and @api.diagnostics properties provide error information. |
| [GetTaskList](./gettasklist/) | Gets TaskList by an id. |
| [ListAttachments](./listattachments/) | List Attachments from the parent message. |
| [ListCalendarItems](./listcalendaritems/) | List MapiCalendar from the calendar. |
| [ListCalendars](./listcalendars/) | List CalendarInfo items. |
| [ListCategories](./listcategories/) | Get all the categories that have been defined for the user. |
| [ListContactFolders](./listcontactfolders/) | Get a collection of child folders under the root contact folder. |
| [ListContacts](./listcontacts/) | List MapiContact from the parent folder. |
| [ListFolders (2 overloads)](./listfolders/) | List folders from the parent folder for folders that are displayed in normal mail clients, such as the inbox. |
| [ListMessages (2 overloads)](./listmessages/) | List MessageInfo from the parent folder. |
| [ListNotebooks](./listnotebooks/) | Retrieve a list of notebook objects. Permissions One of the following permissions is required to call this API. Delegated (work or school account) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All, Notes.ReadWrite.All Delegated (personal Microsoft account) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [ListOverrides](./listoverrides/) | Get the overrides that a user has set up to always classify messages from certain senders in specific ways. Each override corresponds to an SMTP address of a sender.Initially, a user does not have any overrides. Permissions: One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) Mail.Read Delegated (personal Microsoft account) Mail.Read Application Mail.Read |
| [ListRules](./listrules/) | Get all the messageRule objects defined for the user's Inbox. Permissions One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) MailboxSettings.Read Delegated (personal Microsoft account) MailboxSettings.Read Application MailboxSettings.Read |
| [ListTaskLists](./listtasklists/) | List TaskList items. |
| [ListTasks](./listtasks/) | List MapiTask from the parent TaskList. |
| [MoveFolder](./movefolder/) | Move a mailfolder and its contents to another mailfolder. |
| [MoveMessage](./movemessage/) | Move a message to another mailfolder. |
| [Send (4 overloads)](./send/) | Sends email message |
| [SendAsMime](./sendasmime/) | Sends email message using MIME format |
| [set_EndPoint](./set_endpoint/) | Sets Microsoft Graph REST API endpoint. If not specified, the default is "https://graph.microsoft.com". |
| [set_MultipleServicesTokenProvider](./set_multipleservicestokenprovider/) | Sets an object allows to retrieve OAuth access token. |
| [set_Proxy](./set_proxy/) | Sets data to proxy access to Exchange server. |
| [set_Resource](./set_resource/) | Sets resource type. |
| [set_ResourceId](./set_resourceid/) | Sets resource id. For instance for users it may be user principal name (UPN) or user id |
| [set_TenantId](./set_tenantid/) | Sets tenant identifier |
| [set_Timeout](./set_timeout/) | Sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds). |
| [set_TokenProvider](./set_tokenprovider/) | Sets an object allows to retrieve OAuth access token. |
| [SetRead](./setread/) | Mark message as read |
| [UpdateCalendarItem (2 overloads)](./updatecalendaritem/) | Updates MapiCalendar |
| [UpdateCategory](./updatecategory/) | Updates pre-set color constant for specified category |
| [UpdateContact](./updatecontact/) | Updates contact |
| [UpdateFolder](./updatefolder/) | Updates folder. |
| [UpdateMessage (4 overloads)](./updatemessage/) | Updates message |
| [UpdateOverride](./updateoverride/) | Change the classifyAs field of an override as specified. You cannot use this method to change any other fields in an ClassificationOverride instance. If an override exists for a sender and the sender changes his/her display name, you can use CreateOrUpdateOverride to force an update to the name field in the existing override. If an override exists for a sender and the sender changes his/her SMTP address, deleting the existing override and creating a new one with the new SMTP address is the only way to "update" the override for this sender. Permissions: One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) Mail.ReadWrite Delegated (personal Microsoft account) Mail.ReadWrite Application Mail.ReadWrite |
| [UpdateRule](./updaterule/) | Change writable properties on a messageRule object and save the changes. Permissions One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) MailboxSettings.ReadWrite Delegated (personal Microsoft account) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |
| [UpdateTask (2 overloads)](./updatetask/) | Updates Task |
| [UpdateTaskList](./updatetasklist/) | Updates TaskList. |

