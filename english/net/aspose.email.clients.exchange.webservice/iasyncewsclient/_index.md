---
title: IAsyncEwsClient
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 2410
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/
---
## IAsyncEwsClient interface

```csharp
public interface IAsyncEwsClient : IExchangeClientBase
```

## Properties

| Name | Description |
| --- | --- |
| [MailboxInfo](mailboxinfo) { get; } |  |
| [UseSlashAsFolderSeparator](useslashasfolderseparator) { get; set; } |  |

## Methods

| Name | Description |
| --- | --- |
| [AppendMessagesAsync](appendmessagesasync)(EwsAppendMessage) |  |
| [ArchiveItemsAsync](archiveitemsasync)(EwsArchiveItems) |  |
| [BackupAsync](backupasync)(ExchangeFolderInfoCollection, Stream, BackupOptions, CancellationToken) |  |
| [BackupAsync](backupasync)(ExchangeFolderInfoCollection, string, BackupOptions, CancellationToken) |  |
| [CancelAppointmentAsync](cancelappointmentasync)(string, string, CancellationToken) |  |
| [CopyConversationItemsAsync](copyconversationitemsasync)(string, string, string, CancellationToken) |  |
| [CopyItemAsync](copyitemasync)(string, string, CancellationToken) |  |
| [CreateAppointmentAsync](createappointmentasync)(Appointment, string, CancellationToken) |  |
| [CreateFolderAsync](createfolderasync)(string, string, ExchangeFolderPermissionCollection, string, CancellationToken) |  |
| [CreateItemAsync](createitemasync)(MapiMessageItemBase, string, CancellationToken) |  |
| [CreateItemsAsync](createitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, string, CancellationToken) |  |
| [CreatePublicFolderAsync](createpublicfolderasync)(string, ExchangeFolderPermissionCollection, string, CancellationToken) |  |
| [CreatePublicFolderAsync](createpublicfolderasync)(string, ExchangeFolderPermissionCollection, ExchangeFolderType, string, CancellationToken) |  |
| [CreateTaskAsync](createtaskasync)(ExchangeTask, string, CancellationToken) |  |
| [DeleteConversationItemsAsync](deleteconversationitemsasync)(string, string, CancellationToken) |  |
| [DeleteFolderAsync](deletefolderasync)(string, bool, CancellationToken) |  |
| [DeleteFoldersAsync](deletefoldersasync)(IEnumerable&lt;string&gt;, bool, CancellationToken) |  |
| [DeleteItemAsync](deleteitemasync)(string, DeletionOptions, CancellationToken) |  |
| [DeleteItemsAsync](deleteitemsasync)(IEnumerable&lt;string&gt;, DeletionOptions, CancellationToken) |  |
| [EmptyFolderAsync](emptyfolderasync)(string, EmptyFolderOptions, CancellationToken) |  |
| [ExportItemsAsync](exportitemsasync)(IEnumerable&lt;string&gt;, CancellationToken) |  |
| [FetchAppointmentAsync](fetchappointmentasync)(string, string, CancellationToken) |  |
| [FetchAttachmentAsync](fetchattachmentasync)(string, CancellationToken) |  |
| [FetchConversationMessagesAsync](fetchconversationmessagesasync)(string, CancellationToken) |  |
| [FetchItemAsync](fetchitemasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) |  |
| [FetchItemsAsync](fetchitemsasync)(EwsFetchItems) |  |
| [FetchMessagesAsync](fetchmessagesasync)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) |  |
| [FetchTaskAsync](fetchtaskasync)(string, CancellationToken) |  |
| [FindConversationsAsync](findconversationsasync)(string, CancellationToken) |  |
| [FindPeopleAsync](findpeopleasync)(EwsFindPeople) |  |
| [FolderExistsAsync](folderexistsasync)(string, string, CancellationToken) |  |
| [GetContactAsync](getcontactasync)(string, ExchangeListContactsOptions, CancellationToken) |  |
| [GetContactsAsync](getcontactsasync)(string, ExchangeListContactsOptions, CancellationToken) |  |
| [GetFolderInfoAsync](getfolderinfoasync)(string, CancellationToken) |  |
| [GetFolderPermissionsAsync](getfolderpermissionsasync)(string, CancellationToken) |  |
| [GetMailboxesAsync](getmailboxesasync)(CancellationToken) |  |
| [GetMailboxInfoAsync](getmailboxinfoasync)(string, CancellationToken) |  |
| [GetServerTimeZoneIdsAsync](getservertimezoneidsasync)(IEnumerable&lt;string&gt;, CancellationToken) |  |
| [GetTimezoneIdAsync](gettimezoneidasync)(CancellationToken) |  |
| [ListAppointmentsAsync](listappointmentsasync)(string, MailQuery, bool, CancellationToken) |  |
| [ListAppointmentsByPageAsync](listappointmentsbypageasync)(string, MailQuery, int, int, CancellationToken) |  |
| [ListContactsAsync](listcontactsasync)(string, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) |  |
| [ListItemsAsync](listitemsasync)(string, string, MailQuery, bool, CancellationToken) |  |
| [ListMailboxesAsync](listmailboxesasync)(string, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(IEnumerable&lt;string&gt;, CancellationToken) |  |
| [ListMessagesAsync](listmessagesasync)(string, string, int, MailQuery, bool, IEnumerable&lt;PropertyDescriptor&gt;, CancellationToken) |  |
| [ListMessagesByPageAsync](listmessagesbypageasync)(string, PageInfo, CancellationToken) |  |
| [ListMessagesByPageAsync](listmessagesbypageasync)(string, int, int, MailQuery, CancellationToken) |  |
| [ListPublicFoldersAsync](listpublicfoldersasync)(CancellationToken) |  |
| [ListSubFoldersAsync](listsubfoldersasync)(string, string, CancellationToken) |  |
| [ListSubFoldersByPageAsync](listsubfoldersbypageasync)(string, PageInfo, CancellationToken) |  |
| [ListTasksAsync](listtasksasync)(string, int, MailQuery, bool, CancellationToken) |  |
| [LoadContactPhotoAsync](loadcontactphotoasync)(ContactPhoto, CancellationToken) |  |
| [MailDisablePublicFolderAsync](maildisablepublicfolderasync)(string, CancellationToken) |  |
| [MailEnablePublicFolderAsync](mailenablepublicfolderasync)(string, CancellationToken) |  |
| [MarkAllItemsAsync](markallitemsasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) |  |
| [MarkAsJunkAsync](markasjunkasync)(IEnumerable&lt;string&gt;, bool, bool, CancellationToken) |  |
| [MoveConversationItemsAsync](moveconversationitemsasync)(string, string, string, CancellationToken) |  |
| [MoveItemAsync](moveitemasync)(string, string, CancellationToken) |  |
| [ResolveContactsAsync](resolvecontactsasync)(string, ExchangeListContactsOptions, CancellationToken) |  |
| [ResolveMapiContactsAsync](resolvemapicontactsasync)(string, CancellationToken) |  |
| [RestoreAsync](restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) |  |
| [SendAsync](sendasync)(MailMessage, FollowUpOptions, CancellationToken) |  |
| [SetConversationReadStateAsync](setconversationreadstateasync)(string, bool, string, CancellationToken) |  |
| [SetReadFlagAsync](setreadflagasync)(string, bool, CancellationToken) |  |
| [SetTimezoneIdAsync](settimezoneidasync)(string, CancellationToken) |  |
| [SyncFolderAsync](syncfolderasync)(SyncState, CancellationToken) |  |
| [UpdateAppointmentAsync](updateappointmentasync)(Appointment, string, CancellationToken) |  |
| [UpdateContactAsync](updatecontactasync)(Contact, CancellationToken) |  |
| [UpdateItemAsync](updateitemasync)(EwsUpdateItem) |  |
| [UpdateItemsAsync](updateitemsasync)(IEnumerable&lt;ExchangeStreamedItem&gt;, CancellationToken) |  |
| [UpdateTaskAsync](updatetaskasync)(ExchangeTask, CancellationToken) |  |

### See Also

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
