---
title: Interface IGraphClient
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Graph.IGraphClient interface. Represents the interface for Exchange REST client
type: docs
weight: 14600
url: /net/aspose.email.clients.graph/igraphclient/
---
## IGraphClient interface

Represents the interface for Exchange REST client.

```csharp
public interface IGraphClient : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [EndPoint](../../aspose.email.clients.graph/igraphclient/endpoint/) { get; set; } | Gets or sets Microsoft Graph REST API endpoint. If not specified, the default is "https://graph.microsoft.com". |
| [MultipleServicesTokenProvider](../../aspose.email.clients.graph/igraphclient/multipleservicestokenprovider/) { get; set; } | Gets or sets an object allows to retrieve OAuth access token. |
| [Proxy](../../aspose.email.clients.graph/igraphclient/proxy/) { get; set; } | Gets or sets data to proxy access to Exchange server. |
| [Resource](../../aspose.email.clients.graph/igraphclient/resource/) { get; set; } | Gets or sets resource type. |
| [ResourceId](../../aspose.email.clients.graph/igraphclient/resourceid/) { get; set; } | Gets or sets resource id. For instance for users it may be user principal name (UPN) or user id |
| [TenantId](../../aspose.email.clients.graph/igraphclient/tenantid/) { get; set; } | Gets or sets tenant identifier |
| [Timeout](../../aspose.email.clients.graph/igraphclient/timeout/) { get; set; } | Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds). |
| [TokenProvider](../../aspose.email.clients.graph/igraphclient/tokenprovider/) { get; set; } | Gets or sets an object allows to retrieve OAuth access token. |

## Methods

| Name | Description |
| --- | --- |
| [CopyFolder](../../aspose.email.clients.graph/igraphclient/copyfolder/)(string, string) | Copy a mailfolder and its contents to another mailfolder. |
| [CopyMessage](../../aspose.email.clients.graph/igraphclient/copymessage/)(string, string) | Copy a Message to another mailfolder. |
| [CopyNotebook](../../aspose.email.clients.graph/igraphclient/copynotebook/)(string, string, string) | Copies a notebook to the Notebooks folder in the destination Documents library. The folder is created if it doesn't exist. For Copy operations, you follow an asynchronous calling pattern: First call the Copy action, and then poll the operation endpoint for the result. Permissions One of the following permissions is required to call this API. Delegated(work or school account) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegated(personal Microsoft account) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateAttachment](../../aspose.email.clients.graph/igraphclient/createattachment/)(string, MapiAttachment) | Creates new attachment for specified item |
| [CreateCalendarItem](../../aspose.email.clients.graph/igraphclient/createcalendaritem/)(string, MapiCalendar) | Creates MapiCalendar in specified calendar |
| [CreateCategory](../../aspose.email.clients.graph/igraphclient/createcategory/)(string, CategoryPreset) | Creates an [`OutlookCategory`](../outlookcategory/) object in the user's master list of categories. |
| [CreateContact](../../aspose.email.clients.graph/igraphclient/createcontact/)(string, MapiContact) | Creates contact in specified folder |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder/#createfolder)(string) | Create new folder. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder/#createfolder_1)(string, string) | Create new folder. |
| [CreateMessage](../../aspose.email.clients.graph/igraphclient/createmessage/#createmessage)(string, MailMessage) | Creates message in specified folder |
| [CreateMessage](../../aspose.email.clients.graph/igraphclient/createmessage/#createmessage_1)(string, MapiMessage) | Creates message in specified folder |
| [CreateNotebook](../../aspose.email.clients.graph/igraphclient/createnotebook/)(Notebook) | Create a new OneNote notebook. Permissions One of the following permissions is required to call this API. Delegated (work or school account) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegated (personal Microsoft account) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride/#createorupdateoverride)(ClassificationOverride) | Create an override for a sender identified by an SMTP address. Future messages from that SMTP address will be consistently classified as specified in the override. Note: - If an override already exists with the same SMTP address, then the classifyAs and name fields of that override are updated with the provided values. - The maximum number of overrides supported for a mailbox is 1000, based on unique sender SMTP addresses. Permissions: Delegated(work or school account) Mail.ReadWrite Delegated(personal Microsoft account) Mail.ReadWrite Application Mail.ReadWrite |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride/#createorupdateoverride_1)(MailAddress, ClassificationType) | Create an override for a sender identified by an SMTP address. Future messages from that SMTP address will be consistently classified as specified in the override. Note: - If an override already exists with the same SMTP address, then the classifyAs and name fields of that override are updated with the provided values. - The maximum number of overrides supported for a mailbox is 1000, based on unique sender SMTP addresses. Permissions: Delegated(work or school account) Mail.ReadWrite Delegated(personal Microsoft account) Mail.ReadWrite Application Mail.ReadWrite |
| [CreateRule](../../aspose.email.clients.graph/igraphclient/createrule/)(InboxRule) | Create a message rule by specifying a set of conditions and actions. Outlook carries out those actions if an incoming message in the user's Inbox meets the specified conditions. Permissions: One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) MailboxSettings.ReadWrite Delegated (personal Microsoft account) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |
| [CreateTask](../../aspose.email.clients.graph/igraphclient/createtask/)(MapiTask, string) | Creates Task in specified folder |
| [CreateTaskList](../../aspose.email.clients.graph/igraphclient/createtasklist/)(TaskListInfo) | Creates new TaskList. |
| [Delete](../../aspose.email.clients.graph/igraphclient/delete/)(string) | Delete object. |
| [DeleteAttachment](../../aspose.email.clients.graph/igraphclient/deleteattachment/)(string) | Removes attachment |
| [DeleteTaskList](../../aspose.email.clients.graph/igraphclient/deletetasklist/)(string) | Delete TaskList. |
| [FetchAttachment](../../aspose.email.clients.graph/igraphclient/fetchattachment/)(string) | Gets attachment for specified id |
| [FetchCalendarItem](../../aspose.email.clients.graph/igraphclient/fetchcalendaritem/)(string) | Gets MapiCalendar for specified id |
| [FetchCategory](../../aspose.email.clients.graph/igraphclient/fetchcategory/)(string) | Get the properties and relationships of the specified outlookCategory object. |
| [FetchContact](../../aspose.email.clients.graph/igraphclient/fetchcontact/)(string) | Gets MapiContact for specified id |
| [FetchMessage](../../aspose.email.clients.graph/igraphclient/fetchmessage/)(string) | Gets message in specified id |
| [FetchNotebook](../../aspose.email.clients.graph/igraphclient/fetchnotebook/)(string) | Retrieve the properties and relationships of a notebook object. Permissions One of the following permissions is required to call this API. Delegated (work or school account) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All, Notes.ReadWrite.All Delegated (personal Microsoft account) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [FetchRule](../../aspose.email.clients.graph/igraphclient/fetchrule/)(string) | Get the properties and relationships of a message rule object. Permissions One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) MailboxSettings.Read Delegated (personal Microsoft account) MailboxSettings.Read Application MailboxSettings.Read |
| [FetchTask](../../aspose.email.clients.graph/igraphclient/fetchtask/)(string) | Gets MapiTask for specified id |
| [GetContactFolder](../../aspose.email.clients.graph/igraphclient/getcontactfolder/)() | Gets main contact folder. This method requires that at least one contact exists in the main contacts folder, otherwise it will return null. https://learn.microsoft.com/en-us/answers/questions/854621/how-to-get-folder-id-of-default-contacts-folder-wh |
| [GetFolder](../../aspose.email.clients.graph/igraphclient/getfolder/)(string) | Gets folder by an id. |
| [GetOneNoteOperationStatus](../../aspose.email.clients.graph/igraphclient/getonenoteoperationstatus/)(string) | Get the status of a long-running OneNote operation. This applies to operations that return the Operation-Location header in the response, such as CopyNotebook, CopyToNotebook, CopyToSectionGroup, and CopyToSection. You can poll the Operation-Location endpoint until the status property returns completed or failed. If the status is completed, the resourceLocation property contains the resource endpoint URI. If the status is failed, the error and @api.diagnostics properties provide error information. |
| [GetTaskList](../../aspose.email.clients.graph/igraphclient/gettasklist/)(string) | Gets TaskList by an id. |
| [ListAttachments](../../aspose.email.clients.graph/igraphclient/listattachments/)(string) | List Attachments from the parent message. |
| [ListCalendarItems](../../aspose.email.clients.graph/igraphclient/listcalendaritems/)(string) | List MapiCalendar from the calendar. |
| [ListCalendars](../../aspose.email.clients.graph/igraphclient/listcalendars/)() | List CalendarInfo items. |
| [ListCategories](../../aspose.email.clients.graph/igraphclient/listcategories/)() | Get all the categories that have been defined for the user. |
| [ListContactFolders](../../aspose.email.clients.graph/igraphclient/listcontactfolders/)() | Get a collection of child folders under the root contact folder. |
| [ListContacts](../../aspose.email.clients.graph/igraphclient/listcontacts/)(string) | List MapiContact from the parent folder. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders/#listfolders)() | List folders from the parent folder for folders that are displayed in normal mail clients, such as the inbox. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders/#listfolders_1)(string) | List folders from the parent folder for folders that are displayed in normal mail clients, such as the inbox. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages/#listmessages_1)(string) | List MessageInfo from the parent folder. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages/#listmessages)(string, PageInfo, MailQuery) | List MessageInfo from the parent folder. |
| [ListNotebooks](../../aspose.email.clients.graph/igraphclient/listnotebooks/)() | Retrieve a list of notebook objects. Permissions One of the following permissions is required to call this API. Delegated (work or school account) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All, Notes.ReadWrite.All Delegated (personal Microsoft account) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [ListOverrides](../../aspose.email.clients.graph/igraphclient/listoverrides/)() | Get the overrides that a user has set up to always classify messages from certain senders in specific ways. Each override corresponds to an SMTP address of a sender.Initially, a user does not have any overrides. Permissions: One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) Mail.Read Delegated (personal Microsoft account) Mail.Read Application Mail.Read |
| [ListRules](../../aspose.email.clients.graph/igraphclient/listrules/)() | Get all the messageRule objects defined for the user's Inbox. Permissions One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) MailboxSettings.Read Delegated (personal Microsoft account) MailboxSettings.Read Application MailboxSettings.Read |
| [ListTaskLists](../../aspose.email.clients.graph/igraphclient/listtasklists/)() | List TaskList items. |
| [ListTasks](../../aspose.email.clients.graph/igraphclient/listtasks/)(string) | List MapiTask from the parent TaskList. |
| [MoveFolder](../../aspose.email.clients.graph/igraphclient/movefolder/)(string, string) | Move a mailfolder and its contents to another mailfolder. |
| [MoveMessage](../../aspose.email.clients.graph/igraphclient/movemessage/)(string, string) | Move a message to another mailfolder. |
| [Send](../../aspose.email.clients.graph/igraphclient/send/#send)(MailMessage) | Sends email message |
| [Send](../../aspose.email.clients.graph/igraphclient/send/#send_1)(MapiMessage) | Sends email message |
| [Send](../../aspose.email.clients.graph/igraphclient/send/#send_3)(string) | Send a message in the draft folder. The draft message can be a new message draft, reply draft, reply-all draft, or a forward draft. The message is then saved in the Sent Items folder. |
| [Send](../../aspose.email.clients.graph/igraphclient/send/#send_2)(MapiMessage, bool) | Sends email message |
| [SendAsMime](../../aspose.email.clients.graph/igraphclient/sendasmime/)(MapiMessage) | Sends email message using MIME format |
| [SetRead](../../aspose.email.clients.graph/igraphclient/setread/)(string) | Mark message as read |
| [UpdateCalendarItem](../../aspose.email.clients.graph/igraphclient/updatecalendaritem/#updatecalendaritem)(MapiCalendar) | Updates MapiCalendar |
| [UpdateCalendarItem](../../aspose.email.clients.graph/igraphclient/updatecalendaritem/#updatecalendaritem_1)(MapiCalendar, UpdateSettings) | Updates appointment |
| [UpdateCategory](../../aspose.email.clients.graph/igraphclient/updatecategory/)(OutlookCategory) | Updates pre-set color constant for specified category |
| [UpdateContact](../../aspose.email.clients.graph/igraphclient/updatecontact/)(MapiContact) | Updates contact |
| [UpdateFolder](../../aspose.email.clients.graph/igraphclient/updatefolder/)(FolderInfo) | Updates folder. |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage/#updatemessage)(MailMessage) | Updates message |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage/#updatemessage_2)(MapiMessage) | Updates message |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage/#updatemessage_1)(MailMessage, UpdateSettings) | Updates message |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage/#updatemessage_3)(MapiMessage, UpdateSettings) | Updates message |
| [UpdateOverride](../../aspose.email.clients.graph/igraphclient/updateoverride/)(ClassificationOverride) | Change the classifyAs field of an override as specified. You cannot use this method to change any other fields in an ClassificationOverride instance. If an override exists for a sender and the sender changes his/her display name, you can use CreateOrUpdateOverride to force an update to the name field in the existing override. If an override exists for a sender and the sender changes his/her SMTP address, deleting the existing override and creating a new one with the new SMTP address is the only way to "update" the override for this sender. Permissions: One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) Mail.ReadWrite Delegated (personal Microsoft account) Mail.ReadWrite Application Mail.ReadWrite |
| [UpdateRule](../../aspose.email.clients.graph/igraphclient/updaterule/)(InboxRule) | Change writable properties on a messageRule object and save the changes. Permissions One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) MailboxSettings.ReadWrite Delegated (personal Microsoft account) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |
| [UpdateTask](../../aspose.email.clients.graph/igraphclient/updatetask/#updatetask)(MapiTask) | Updates Task |
| [UpdateTask](../../aspose.email.clients.graph/igraphclient/updatetask/#updatetask_1)(MapiTask, UpdateSettings) | Updates Task |
| [UpdateTaskList](../../aspose.email.clients.graph/igraphclient/updatetasklist/)(TaskListInfo) | Updates TaskList. |

### See Also

* namespace [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph/)
* assembly [Aspose.Email](../../)


