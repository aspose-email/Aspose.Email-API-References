---
title: IGraphClient
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 14390
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
| [MultipleServicesTokenProvider](multipleservicestokenprovider) { get; set; } | Gets or sets an object allows to retrieve OAuth access token. |
| [Proxy](proxy) { get; set; } | Gets or sets data to proxy access to Exchange server. |
| [Resource](resource) { get; set; } | Gets or sets resource type. |
| [ResourceId](resourceid) { get; set; } | Gets or sets resource id. For instance for users it may be user principal name (UPN) or user id |
| [TenantId](tenantid) { get; set; } | Gets or sets tenant identifier |
| [Timeout](timeout) { get; set; } | Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds). |
| [TokenProvider](tokenprovider) { get; set; } | Gets or sets an object allows to retrieve OAuth access token. |

## Methods

| Name | Description |
| --- | --- |
| [CopyFolder](copyfolder)(string, string) | Copy a mailfolder and its contents to another mailfolder. |
| [CopyMessage](copymessage)(string, string) | Copy a Message to another mailfolder. |
| [CopyNotebook](copynotebook)(string, string, string) | Copies a notebook to the Notebooks folder in the destination Documents library. The folder is created if it doesn't exist. For Copy operations, you follow an asynchronous calling pattern: First call the Copy action, and then poll the operation endpoint for the result. Permissions One of the following permissions is required to call this API. Delegated(work or school account) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegated(personal Microsoft account) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateAttachment](createattachment)(string, MapiAttachment) | Creates new attachment for specified item |
| [CreateCategory](createcategory)(string, CategoryPreset) | Creates an [`OutlookCategory`](../outlookcategory) object in the user's master list of categories. |
| [CreateFolder](createfolder)(string) | Create new folder. |
| [CreateFolder](createfolder)(string, string) | Create new folder. |
| [CreateMessage](createmessage)(string, MapiMessage) | Creates message in specified folder |
| [CreateNotebook](createnotebook)(Notebook) | Create a new OneNote notebook. Permissions One of the following permissions is required to call this API. Delegated (work or school account) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegated (personal Microsoft account) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateOrUpdateOverride](createorupdateoverride)(ClassificationOverride) | Create an override for a sender identified by an SMTP address. Future messages from that SMTP address will be consistently classified as specified in the override. Note: - If an override already exists with the same SMTP address, then the classifyAs and name fields of that override are updated with the provided values. - The maximum number of overrides supported for a mailbox is 1000, based on unique sender SMTP addresses. Permissions: Delegated(work or school account) Mail.ReadWrite Delegated(personal Microsoft account) Mail.ReadWrite Application Mail.ReadWrite |
| [CreateOrUpdateOverride](createorupdateoverride)(MailAddress, ClassificationType) | Create an override for a sender identified by an SMTP address. Future messages from that SMTP address will be consistently classified as specified in the override. Note: - If an override already exists with the same SMTP address, then the classifyAs and name fields of that override are updated with the provided values. - The maximum number of overrides supported for a mailbox is 1000, based on unique sender SMTP addresses. Permissions: Delegated(work or school account) Mail.ReadWrite Delegated(personal Microsoft account) Mail.ReadWrite Application Mail.ReadWrite |
| [CreateRule](createrule)(InboxRule) | Create a message rule by specifying a set of conditions and actions. Outlook carries out those actions if an incoming message in the user's Inbox meets the specified conditions. Permissions: One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) MailboxSettings.ReadWrite Delegated (personal Microsoft account) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |
| [Delete](delete)(string) | Delete object. |
| [DeleteAttachment](deleteattachment)(string) | Removes attachment |
| [FetchAttachment](fetchattachment)(string) | Gets attachment for specified id |
| [FetchCategory](fetchcategory)(string) | Get the properties and relationships of the specified outlookCategory object. |
| [FetchMessage](fetchmessage)(string) | Gets message in specified id |
| [FetchNotebook](fetchnotebook)(string) | Retrieve the properties and relationships of a notebook object. Permissions One of the following permissions is required to call this API. Delegated (work or school account) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All, Notes.ReadWrite.All Delegated (personal Microsoft account) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [FetchRule](fetchrule)(string) | Get the properties and relationships of a message rule object. Permissions One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) MailboxSettings.Read Delegated (personal Microsoft account) MailboxSettings.Read Application MailboxSettings.Read |
| [GetFolder](getfolder)(string) | Gets folder by an id. |
| [GetOneNoteOperationStatus](getonenoteoperationstatus)(string) | Get the status of a long-running OneNote operation. This applies to operations that return the Operation-Location header in the response, such as CopyNotebook, CopyToNotebook, CopyToSectionGroup, and CopyToSection. You can poll the Operation-Location endpoint until the status property returns completed or failed. If the status is completed, the resourceLocation property contains the resource endpoint URI. If the status is failed, the error and @api.diagnostics properties provide error information. |
| [ListAttachments](listattachments)(string) | List Attachments from the parent message. |
| [ListCategories](listcategories)() | Get all the categories that have been defined for the user. |
| [ListFolders](listfolders)() | List folders from the parent folder for folders that are displayed in normal mail clients, such as the inbox. |
| [ListFolders](listfolders)(string) | List folders from the parent folder for folders that are displayed in normal mail clients, such as the inbox. |
| [ListMessages](listmessages)(string) | List MessageInfo from the parent folder. |
| [ListNotebooks](listnotebooks)() | Retrieve a list of notebook objects. Permissions One of the following permissions is required to call this API. Delegated (work or school account) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All, Notes.ReadWrite.All Delegated (personal Microsoft account) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [ListOverrides](listoverrides)() | Get the overrides that a user has set up to always classify messages from certain senders in specific ways. Each override corresponds to an SMTP address of a sender.Initially, a user does not have any overrides. Permissions: One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) Mail.Read Delegated (personal Microsoft account) Mail.Read Application Mail.Read |
| [ListRules](listrules)() | Get all the messageRule objects defined for the user's Inbox. Permissions One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) MailboxSettings.Read Delegated (personal Microsoft account) MailboxSettings.Read Application MailboxSettings.Read |
| [MoveFolder](movefolder)(string, string) | Move a mailfolder and its contents to another mailfolder. |
| [MoveMessage](movemessage)(string, string) | Move a message to another mailfolder. |
| [Send](send)(MapiMessage) | Sends email message |
| [Send](send)(string) | Send a message in the draft folder. The draft message can be a new message draft, reply draft, reply-all draft, or a forward draft. The message is then saved in the Sent Items folder. |
| [Send](send)(MapiMessage, bool) | Sends email message |
| [UpdateCategory](updatecategory)(OutlookCategory) | Updates pre-set color constant for specified category |
| [UpdateFolder](updatefolder)(FolderInfo) | Updates folder. |
| [UpdateMessage](updatemessage)(MapiMessage) | Updates message |
| [UpdateMessage](updatemessage)(MapiMessage, UpdateSettings) | Updates message |
| [UpdateOverride](updateoverride)(ClassificationOverride) | Change the classifyAs field of an override as specified. You cannot use this method to change any other fields in an ClassificationOverride instance. If an override exists for a sender and the sender changes his/her display name, you can use CreateOrUpdateOverride to force an update to the name field in the existing override. If an override exists for a sender and the sender changes his/her SMTP address, deleting the existing override and creating a new one with the new SMTP address is the only way to "update" the override for this sender. Permissions: One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) Mail.ReadWrite Delegated (personal Microsoft account) Mail.ReadWrite Application Mail.ReadWrite |
| [UpdateRule](updaterule)(InboxRule) | Change writable properties on a messageRule object and save the changes. Permissions One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) MailboxSettings.ReadWrite Delegated (personal Microsoft account) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |

### See Also

* namespace [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
