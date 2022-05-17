---
title: IAsyncEwsClient
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 3950
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/
---
## IAsyncEwsClient interface

Represents the async interface for Exchange client.

```csharp
public interface IAsyncEwsClient : IExchangeClientBase
```

## Properties

| Name | Description |
| --- | --- |
| [MailboxInfo](mailboxinfo) { get; } | Gets the mailbox info. |
| [UseSlashAsFolderSeparator](useslashasfolderseparator) { get; set; } | Gets or sets value that determines whether the slash '/' is used as folder separator. |

## Methods

| Name | Description |
| --- | --- |
| [AppendMessagesAsync](appendmessagesasync)(EwsAppendMessage) | Uploads mail messages to the specified folder. |
| [ArchiveItemsAsync](archiveitemsasync)(EwsArchiveItems) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [BackupAsync](backupasync)(ExchangeFolderInfoCollection, Stream, BackupOptions, CancellationToken) | Backups the content of the specified folders. |
| [BackupAsync](backupasync)(ExchangeFolderInfoCollection, string, BackupOptions, CancellationToken) | Backups the content of the specified folders. |
| [CancelAppointmentAsync](cancelappointmentasync)(string, string, CancellationToken) | Cancels an exiting meeting on an organizers calendar |
| [CopyConversationItemsAsync](copyconversationitemsasync)(string, string, string, CancellationToken) | Copies the conversation items, which are located in the specified folder, into the specified target folder |
| [CopyItemAsync](copyitemasync)(string, string, CancellationToken) | Copies the item to specified folder |
| [CreateAppointmentAsync](createappointmentasync)(Appointment, string, CancellationToken) | Creates appointment. |
| [CreateFolderAsync](createfolderasync)(string, string, ExchangeFolderPermissionCollection, string, CancellationToken) | Creates the new folder |
| [CreateItemAsync](createitemasync)(MapiMessageItemBase, string, CancellationToken) | Creates the given item in the specified folder. |
| [CreateItemsAsync](createitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, string, CancellationToken) | Creates the specified items in the specified folder |
| [CreatePublicFolderAsync](createpublicfolderasync)(string, ExchangeFolderPermissionCollection, string, CancellationToken) | Creates the specified public folder in the root public folder |
| [CreatePublicFolderAsync](createpublicfolderasync)(string, ExchangeFolderPermissionCollection, ExchangeFolderType, string, CancellationToken) | Creates the specified public folder in the root public folder |
| [CreateTaskAsync](createtaskasync)(ExchangeTask, string, CancellationToken) | Creates the given task in the specified folder. |
| [DeleteConversationItemsAsync](deleteconversationitemsasync)(string, string, CancellationToken) | Deletes the conversation items, which are located in the specified folder |
| [DeleteFolderAsync](deletefolderasync)(string, bool, CancellationToken) | Deletes the folder |
| [DeleteFoldersAsync](deletefoldersasync)(IEnumerable&lt;string&gt;, bool, CancellationToken) | Deletes the folders |
| [DeleteItemAsync](deleteitemasync)(string, DeletionOptions, CancellationToken) | Deletes specified item |
| [DeleteItemsAsync](deleteitemsasync)(IEnumerable&lt;string&gt;, DeletionOptions, CancellationToken) | Deletes specified items |
| [EmptyFolderAsync](emptyfolderasync)(string, EmptyFolderOptions, CancellationToken) | Empties the specified folder |
| [ExportItemsAsync](exportitemsasync)(IEnumerable&lt;string&gt;, CancellationToken) | Exports the specified items from mailbox |
| [FetchAppointmentAsync](fetchappointmentasync)(string, string, CancellationToken) | Fetch the specified appointment from server. |
| [FetchAttachmentAsync](fetchattachmentasync)(string, CancellationToken) | Fetches the attachment |
| [FetchConversationMessagesAsync](fetchconversationmessagesasync)(string, CancellationToken) | Fetches the specified conversation messages |
| [FetchItemAsync](fetchitemasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Retrieves the complete item with attachments. |
| [FetchItemsAsync](fetchitemsasync)(EwsFetchItems) | Fetches the specified items. |
| [FetchMessagesAsync](fetchmessagesasync)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Fetches the specified messages. |
| [FetchTaskAsync](fetchtaskasync)(string, CancellationToken) | Fetches the specified task. |
| [FindConversationsAsync](findconversationsasync)(string, CancellationToken) | Finds conversations in the specified folder |
| [FindPeopleAsync](findpeopleasync)(EwsFindPeople) | Find contacts. |
| [FolderExistsAsync](folderexistsasync)(string, string, CancellationToken) | Checks whether the specified folder exists. |
| [GetContactAsync](getcontactasync)(string, ExchangeListContactsOptions, CancellationToken) | Retrieves contact information according to specified identifier. |
| [GetContactsAsync](getcontactsasync)(string, ExchangeListContactsOptions, CancellationToken) | Lists contacts located in the specified folder on server |
| [GetFolderInfoAsync](getfolderinfoasync)(string, CancellationToken) | Gets the folder information |
| [GetFolderPermissionsAsync](getfolderpermissionsasync)(string, CancellationToken) | Gets the folder permissions. |
| [GetMailboxesAsync](getmailboxesasync)(CancellationToken) | Lists mailboxes having smtp addresses. Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation. |
| [GetMailboxInfoAsync](getmailboxinfoasync)(string, CancellationToken) | Gets the mailbox information |
| [GetServerTimeZoneIdsAsync](getservertimezoneidsasync)(IEnumerable&lt;string&gt;, CancellationToken) | The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server. |
| [GetTimezoneIdAsync](gettimezoneidasync)(CancellationToken) | Gets timezone id. |
| [ListAppointmentsAsync](listappointmentsasync)(string, MailQuery, bool, CancellationToken) | Retrieves list of appointments for specified calendar folder |
| [ListAppointmentsByPageAsync](listappointmentsbypageasync)(string, MailQuery, int, int, CancellationToken) | Retrieves page with appointments for specified calendar folder |
| [ListContactsAsync](listcontactsasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | Lists contacts located in the specified folder on server. |
| [ListItemsAsync](listitemsasync)(string, string, MailQuery, bool, CancellationToken) | Retrieve list of item URIes in specified folder |
| [ListMailboxesAsync](listmailboxesasync)(string, CancellationToken) | Lists mailboxes having smtp addresses. Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation. |
| [ListMessagesAsync](listmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) | List the messages in the specified folder. |
| [ListMessagesAsync](listmessagesasync)(string, string, int, MailQuery, bool, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) | List the messages in the specified folder. |
| [ListMessagesByPageAsync](listmessagesbypageasync)(string, PageInfo, CancellationToken) | List the messages in the specified folder. |
| [ListMessagesByPageAsync](listmessagesbypageasync)(string, int, int, MailQuery, CancellationToken) | List the messages in the specified folder. |
| [ListPublicFoldersAsync](listpublicfoldersasync)(CancellationToken) | Gets collection of public folders from root public folder |
| [ListSubFoldersAsync](listsubfoldersasync)(string, string, CancellationToken) | Gets collection of child folders from parent |
| [ListSubFoldersByPageAsync](listsubfoldersbypageasync)(string, PageInfo, CancellationToken) | Searches the specified folder in the given parent folder with paging Method supports paging. |
| [ListTasksAsync](listtasksasync)(string, int, MailQuery, bool, CancellationToken) | Retrieves lists of exchange tasks. |
| [LoadContactPhotoAsync](loadcontactphotoasync)(ContactPhoto, CancellationToken) | Loads contact photo binary data |
| [MailDisablePublicFolderAsync](maildisablepublicfolderasync)(string, CancellationToken) | Mail-disable a public folder |
| [MailEnablePublicFolderAsync](mailenablepublicfolderasync)(string, CancellationToken) | Mail-enable a public folder |
| [MarkAllItemsAsync](markallitemsasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) | Marks all items in specified folders. |
| [MarkAsJunkAsync](markasjunkasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [MoveConversationItemsAsync](moveconversationitemsasync)(string, string, string, CancellationToken) | Moves the conversation items, which are located in the specified folder, into the specified target folder |
| [MoveItemAsync](moveitemasync)(string, string, CancellationToken) | Moves the item to specified folder |
| [ResolveContactsAsync](resolvecontactsasync)(string, ExchangeListContactsOptions, CancellationToken) | Resolves ambiguous e-mail addresses and display names Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation. |
| [ResolveMapiContactsAsync](resolvemapicontactsasync)(string, CancellationToken) | Resolves ambiguous e-mail addresses and display names Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation. |
| [RestoreAsync](restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Restores the specified exchange folders from the given personal storage. |
| [SendAsync](sendasync)(MailMessage, FollowUpOptions, CancellationToken) | Sends the message. |
| [SetConversationReadStateAsync](setconversationreadstateasync)(string, bool, string, CancellationToken) | Set read state of the conversation items, which are located in the specified folder, to the specified value |
| [SetReadFlagAsync](setreadflagasync)(string, bool, CancellationToken) | Marks the specified message as read. |
| [SetTimezoneIdAsync](settimezoneidasync)(string, CancellationToken) | Sets timezone id. |
| [SyncFolderAsync](syncfolderasync)(SyncState, CancellationToken) | Retrieves changes of the items in a specified folder. |
| [UpdateAppointmentAsync](updateappointmentasync)(Appointment, string, CancellationToken) | Updates appointment. |
| [UpdateContactAsync](updatecontactasync)(Contact, CancellationToken) | Updates a contact item in the Exchange store. |
| [UpdateItemAsync](updateitemasync)(EwsUpdateItem) | Updates the item. |
| [UpdateItemsAsync](updateitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, CancellationToken) | Updates the specified items in to a mailbox. |
| [UpdateTaskAsync](updatetaskasync)(ExchangeTask, CancellationToken) | Updates the specified task. |

### See Also

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
