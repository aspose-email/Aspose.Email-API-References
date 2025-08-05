---
title: Interface IEWSClient
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Exchange.WebService.IEWSClient interface. Represents the interface for Exchange client
type: docs
weight: 2520
url: /net/aspose.email.clients.exchange.webservice/iewsclient/
---
## IEWSClient interface

Represents the interface for Exchange client.

```csharp
public interface IEWSClient : IExchangeClientBase
```

## Properties

| Name | Description |
| --- | --- |
| [CalendarFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/calendarfoldereventfilter/) { get; set; } | Specifies event types for Calendar folder |
| [ContactsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/contactsfoldereventfilter/) { get; set; } | Specifies event types for Contacts folder |
| [CurrentCalendarFolderUri](../../aspose.email.clients.exchange.webservice/iewsclient/currentcalendarfolderuri/) { get; set; } | Gets or sets current calendar folder uri |
| [DeletedItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/deleteditemsfoldereventfilter/) { get; set; } | Specifies event types for DeletedItems folder |
| [DraftsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/draftsfoldereventfilter/) { get; set; } | Specifies event types for Drafts folder |
| [EnableDecompression](../../aspose.email.clients.exchange.webservice/iewsclient/enabledecompression/) { get; set; } | Gets or sets a value that indicates whether decompression is enabled |
| [Headers](../../aspose.email.clients.exchange.webservice/iewsclient/headers/) { get; } | Gets array of name value pairs wich are added to WebHeaderCollection in EWS request. |
| [InboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/inboxfoldereventfilter/) { get; set; } | Specifies event types for Inbox folder |
| [JournalFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/journalfoldereventfilter/) { get; set; } | Specifies event types for Journal folder |
| [MailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/mailboxinfo/) { get; } | Gets the mailbox info. |
| [NotesFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/notesfoldereventfilter/) { get; set; } | Specifies event types for Notes folder |
| [NotificationsCheckInterval](../../aspose.email.clients.exchange.webservice/iewsclient/notificationscheckinterval/) { get; set; } | Defines interval for notification check |
| [NotificationTimeout](../../aspose.email.clients.exchange.webservice/iewsclient/notificationtimeout/) { get; set; } | Defines timeout for server notifications |
| [OutboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/outboxfoldereventfilter/) { get; set; } | Specifies event types for Outbox folder |
| [ReconnectCount](../../aspose.email.clients.exchange.webservice/iewsclient/reconnectcount/) { get; set; } | Gets or sets the number of reconnect attempts at connection breaks. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange.webservice/iewsclient/returnclientrequestid/) { get; set; } | Gets or sets a flag to indicate whether the client requires the server side to return the request id. |
| [RootFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/rootfoldereventfilter/) { get; set; } | Specifies event types for Root folder |
| [SentItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/sentitemsfoldereventfilter/) { get; set; } | Specifies event types for SentItems folder |
| [ServerVersion](../../aspose.email.clients.exchange.webservice/iewsclient/serverversion/) { get; } | Gets the information about the current version of MS Exchange. |
| [TasksFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/tasksfoldereventfilter/) { get; set; } | Specifies event types for Tasks folder |
| [TimezoneId](../../aspose.email.clients.exchange.webservice/iewsclient/timezoneid/) { get; set; } | Gets or sets timezone id |
| [UseSlashAsFolderSeparator](../../aspose.email.clients.exchange.webservice/iewsclient/useslashasfolderseparator/) { get; set; } | Gets or sets value that determines whether the slash '/' is used as folder separator. |

## Methods

| Name | Description |
| --- | --- |
| [AddHeader](../../aspose.email.clients.exchange.webservice/iewsclient/addheader/)(string, string) | Adds name and value to WebHeaderCollection in EWS request. |
| [AddToDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/addtodistributionlist/)(ExchangeDistributionList, MailAddressCollection) | Appends the members to Distribution List. |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage/#appendmessage)(MailMessage) | Uploads the mail message to the Inbox folder |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage/#appendmessage_1)(MapiMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage/#appendmessage_2)(MapiMessage, bool) | Uploads the mail message to the specified folder |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage/#appendmessage_3)(string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage/#appendmessage_4)(string, MapiMessage, bool) | Uploads the mail message to the specified folder |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages/#appendmessages_1)(IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the specified folder |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages/#appendmessages)(params MailMessage[]) | Uploads the mail message to the specified folder |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages/#appendmessages_3)(string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail messages to the specified folder |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages/#appendmessages_4)(string, IEnumerable&lt;MapiMessage&gt;) | Uploads the mapi messages to the specified folder |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages/#appendmessages_2)(string, params MailMessage[]) | Uploads the mail message to the specified folder |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem/#archiveitem)(string, Appointment) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem/#archiveitem_1)(string, ExchangeTask) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem/#archiveitem_2)(string, MapiMessageItemBase) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem/#archiveitem_3)(string, string) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup/#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Backups the content of the specified folders |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup/#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | Backups the content of the specified folders |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment/#cancelappointment)(Appointment) | Cancels appointment. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment/#cancelappointment_2)(MapiCalendar) | Cancels appointment. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment/#cancelappointment_4)(string) | Cancels an exiting meeting on an organizers calendar |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment/#cancelappointment_1)(Appointment, string) | Cancels appointment. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment/#cancelappointment_3)(MapiCalendar, string) | Cancels appointment. |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment/#cancelappointment_5)(string, string) | Cancels an exiting meeting on an organizers calendar |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability/#checkuseravailability)(string, DateRange) | Checks user availability within the specified time window. |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability/#checkuseravailability_1)(StringCollection, DateRange) | Checks users availability within the specified time window. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess/#closeaccess_1)(ExchangeDelegateUser, string) | Closes access on the specified mailbox for the specified user. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess/#closeaccess_2)(ExchangeDelegateUserCollection, string) | Closes access on the specified mailbox for the specified user. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess/#closeaccess)(ExchangeFolderUserInfo, string) | Closes access on the specified mailbox for the specified user. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess/#closeaccess_3)(string, string) | Closes access on the specified mailbox for the specified user. |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems/#copyconversationitems)(string, string) | Copies the conversation items into the specified target folder |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems/#copyconversationitems_1)(string, string, string) | Copies the conversation items, which are located in the specified folder, into the specified target folder |
| [CopyItem](../../aspose.email.clients.exchange.webservice/iewsclient/copyitem/)(string, string) | Copies the item to specified folder |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment/#createappointment)(Appointment) | Creates appointment. |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment/#createappointment_1)(Appointment, string) | Creates appointment. |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment/#createappointment_2)(MapiCalendar, string, bool) | Creates appointment. |
| [CreateCalendarSharingInvitationMessage](../../aspose.email.clients.exchange.webservice/iewsclient/createcalendarsharinginvitationmessage/)(string) | Create calendar sharing invitation message. |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact/#createcontact)(Contact) | Creates a contact item in the Exchange store. |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact/#createcontact_1)(string, Contact) | Creates a contact item in the specified folder. |
| [CreateDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/createdistributionlist/)(ExchangeDistributionList, MailAddressCollection) | Creates the private Distribution List. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder/#createfolder)(string) | Creates new folder in the root folder. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder/#createfolder_1)(string, ExchangeFolderType) | Creates new folder in the root folder. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder/#createfolder_2)(string, string) | Creates the new folder with the specified name in the specified parent folder. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder/#createfolder_3)(string, string, ExchangeFolderPermissionCollection) | Creates the new folder |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder/#createfolder_5)(string, string, ExchangeFolderType) | Creates the new folder |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder/#createfolder_4)(string, string, ExchangeFolderPermissionCollection, string) | Creates the new folder |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule/#createinboxrule)(InboxRule) | Creates the specified inbox rule |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule/#createinboxrule_1)(InboxRule, string) | Creates the specified inbox rule |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem/#createitem)(MapiMessageItemBase) | Creates the given item in the default item folder. |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem/#createitem_1)(string, MapiMessageItemBase) | Creates the given item in the specified folder. |
| [CreateItems](../../aspose.email.clients.exchange.webservice/iewsclient/createitems/)(ExchangeStreamedItem[], string) | Creates the specified items in the speciifed folder |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder/#createpublicfolder)(string, ExchangeFolderPermissionCollection) | Creates the specified public folder in the root public folder |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder/#createpublicfolder_1)(string, ExchangeFolderPermissionCollection, ExchangeFolderType) | Creates the specified public folder in the root public folder |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder/#createpublicfolder_2)(string, string, ExchangeFolderPermissionCollection) | Creates the specified public folder in the root public folder |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask/#createtask)(ExchangeTask) | Creates the given task in the default task folder. |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask/#createtask_1)(string, ExchangeTask) | Creates the given task in the specified folder. |
| [CreateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/createuserconfiguration/)(UserConfiguration) | Creates the specified user configuration |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess/#delegateaccess)(ExchangeDelegateUser, string) | Delegates access on the specified mailbox to the specified user. |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess/#delegateaccess_1)(ExchangeDelegateUserCollection, string) | Delegates access on the mailbox to the specified users. |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess/#delegateaccess_2)(string, ExchangeDelegateFolderPermissionLevel, string) | Delegates access on the principal mailbox to the specified user. |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems/#deleteconversationitems)(string) | Deletes all items of the specified conversation |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems/#deleteconversationitems_1)(string, string) | Deletes the conversation items, which are located in the specified folder |
| [DeleteDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletedistributionlist/)(ExchangeDistributionList, bool) | Deletes the Distribution List. |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder/#deletefolder)(string) | Deletes the folder |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder/#deletefolder_1)(string, bool) | Deletes the folder |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders/#deletefolders)(ExchangeFolderInfoCollection) | Deletes the specified folders |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders/#deletefolders_2)(StringCollection) | Deletes the specified folders |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders/#deletefolders_1)(ExchangeFolderInfoCollection, bool) | Deletes the specified folders |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders/#deletefolders_3)(StringCollection, bool) | Deletes the folder |
| [DeleteFromDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletefromdistributionlist/)(ExchangeDistributionList, MailAddressCollection) | Deletes the members from Distribution List. |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule/#deleteinboxrule)(string) | Deletes the specified inbox rule |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule/#deleteinboxrule_1)(string, string) | Deletes the specified inbox rule |
| [DeleteItem](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitem/)(string, DeletionOptions) | Deletes specified item |
| [DeleteItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitems/)(IEnumerable&lt;string&gt;, DeletionOptions) | Deletes specified items |
| [DeleteUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/deleteuserconfiguration/)(UserConfigurationName) | Deletes the specified user configuration |
| [DisconnectPhoneCall](../../aspose.email.clients.exchange.webservice/iewsclient/disconnectphonecall/)(string) | Disconnects a phone call specified by id. |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder/#emptyfolder)(string) | Empties the specified folder. Subfolders will not be deleted; deleted items will be moved into DeletedItems folder |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder/#emptyfolder_1)(string, EmptyFolderOptions) | Empties the specified folder |
| [ExpandDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/expanddistributionlist/)(MailAddress) | Expands the public Distribution List members. |
| [ExportItems](../../aspose.email.clients.exchange.webservice/iewsclient/exportitems/)(params string[]) | Exports the specified items from mailbox |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment/#fetchappointment)(string) | Fetch the specified appointment from server. |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment/#fetchappointment_1)(string, string) | Fetch the specified appointment from server. |
| [FetchAttachment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchattachment/)(string) | Fetches the attachment |
| [FetchConversationMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchconversationmessages/)(string) | Fetches the specified conversation messages |
| [FetchDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/fetchdistributionlist/)(ExchangeDistributionList) | Fetches the private Distribution List members. |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem/#fetchitem)(string) | Retrieves the item as [`MapiMessage`](../../aspose.email.mapi/mapimessage/). |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem/#fetchitem_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Retrieves the item as [`MapiMessage`](../../aspose.email.mapi/mapimessage/). |
| [FetchItems](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitems/)(EwsFetchItems) | Retrieves the items. |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar/#fetchmapicalendar)(IEnumerable&lt;string&gt;) | Fetch array of [`MapiCalendar`](../../aspose.email.mapi/mapicalendar/) objects. |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar/#fetchmapicalendar_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Fetch array of [`MapiCalendar`](../../aspose.email.mapi/mapicalendar/) objects. |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages/#fetchmapimessages)(IEnumerable&lt;string&gt;) | Fetches the speciifed messages |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages/#fetchmapimessages_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Fetches the speciifed messages |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes/#fetchmapinotes)(IEnumerable&lt;string&gt;) | Fetch array of [`MapiNote`](../../aspose.email.mapi/mapinote/) objects. |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes/#fetchmapinotes_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Fetch array of [`MapiNote`](../../aspose.email.mapi/mapinote/) objects. |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks/#fetchmapitasks)(IEnumerable&lt;string&gt;) | Fetch array of [`MapiTask`](../../aspose.email.mapi/mapitask/) objects. |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks/#fetchmapitasks_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Fetch array of [`MapiTask`](../../aspose.email.mapi/mapitask/) objects. |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage/#fetchmessage)(string) | Fetches the message. |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage/#fetchmessage_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Fetches the message from server |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages/#fetchmessages)(IEnumerable&lt;ExchangeMessageInfo&gt;) | Fetches the speciifed messages |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages/#fetchmessages_1)(IEnumerable&lt;string&gt;) | Fetches the speciifed messages |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages/#fetchmessages_3)(StringCollection) | Fetches the speciifed messages |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages/#fetchmessages_2)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Fetches the speciifed messages |
| [FetchTask](../../aspose.email.clients.exchange.webservice/iewsclient/fetchtask/)(string) | Fetches the specified task. |
| [FindConversations](../../aspose.email.clients.exchange.webservice/iewsclient/findconversations/)(string) | Finds conversations in the specified folder |
| [FindMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/findmessagetrackingreport/)(FindMessageTrackingReportOptions) | Finds messages that meet the specified criteria. |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople/#findpeople_1)(string, int) | Find contacts located in the global address list (GAL) on server. |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople/#findpeople)(string, MailQuery, int) | Find contacts located in the specified user's personal mailbox on server. |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists/#folderexists)(string, string) | Checks whether the specified folder exists. |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists/#folderexists_1)(string, string, out ExchangeFolderInfo) | Checks whether the specified folder exists. |
| [Forward](../../aspose.email.clients.exchange.webservice/iewsclient/forward/)(MailMessage, ExchangeMessageInfo) | Forward a message. |
| [GetCallInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getcallinfo/)(string) | Retrieves phone call information by call id |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact/#getcontact)(ObjectIdentifier) | Retrieves contact information according to specified identifier. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact/#getcontact_2)(string) | Retrieves contact information according to specified identifier. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact/#getcontact_1)(ObjectIdentifier, ExchangeListContactsOptions) | Retrieves contact information according to specified identifier. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact/#getcontact_3)(string, ExchangeListContactsOptions) | Retrieves contact information according to specified identifier. |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts/#getcontacts)(string) | Lists contacts located in the specified folder on server |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts/#getcontacts_1)(string, ExchangeListContactsOptions) | Lists contacts located in the specified folder on server |
| [GetExchangeType](../../aspose.email.clients.exchange.webservice/iewsclient/getexchangetype/)() | Gets the information about the current version of MS Exchange. |
| [GetFolderInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderinfo/)(string) | Gets the folder information |
| [GetFolderPermissions](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderpermissions/)(string) | Gets the folder permissions. |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules/#getinboxrules)() | Gets inbox rules |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules/#getinboxrules_1)(string) | Gets inbox rules |
| [GetMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxes/)() | Lists mailboxes having smtp addresses. Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo/#getmailboxinfo)() | Gets the mailbox info. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo/#getmailboxinfo_1)(string) | Gets the mailbox information |
| [GetMailboxSize](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsize/)() | Gets the size of the mailbox. Please, note this operation is performed recursively for all subfolders and make take some time |
| [GetMailboxSizeEx](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsizeex/)(string) | Gets the size of the mailbox Please, note this operation is performed recursively for all subfolders and make take some time |
| [GetMailTips](../../aspose.email.clients.exchange.webservice/iewsclient/getmailtips/)(GetMailTipsOptions) | Gets mail tips |
| [GetMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/getmessagetrackingreport/)(GetMessageTrackingReportOptions) | Gets message tracking report |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids/#getservertimezoneids)() | The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server. |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids/#getservertimezoneids_1)(IEnumerable&lt;string&gt;) | The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server. |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids/#getservertimezoneids_2)(params string[]) | The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server. |
| [GetUMConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getumconfiguration/)() | Retrieves unified messaging configuration |
| [GetUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getuserconfiguration/)(UserConfigurationName) | Gets the specified user configuration |
| [GetVersionInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getversioninfo/)() | Returns exchange server version info |
| [ImpersonateUser](../../aspose.email.clients.exchange.webservice/iewsclient/impersonateuser/)(ItemChoice, string) | Impersonates the user. |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments/#listappointments)() | Retrieves list of appointments for default calendar folder |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments/#listappointments_3)(bool) | Retrieves list of appointments for default calendar folder |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments/#listappointments_1)(MailQuery) | Retrieves list of appointments for default calendar folder |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments/#listappointments_4)(string) | Retrieves list of appointments for specified calendar folder |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments/#listappointments_2)(MailQuery, bool) | Retrieves list of appointments for default calendar folder |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments/#listappointments_7)(string, bool) | Retrieves list of appointments for specified calendar folder |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments/#listappointments_5)(string, MailQuery) | Retrieves list of appointments for specified calendar folder |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments/#listappointments_6)(string, MailQuery, bool) | Retrieves list of appointments for specified calendar folder |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage/#listappointmentsbypage_2)(int) | Retrieves page with appointments for calendar folder |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage/#listappointmentsbypage_3)(int, int) | Retrieves page with appointments for calendar folder |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage/#listappointmentsbypage)(MailQuery, int) | Retrieves page with appointments for calendar folder |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage/#listappointmentsbypage_6)(string, int) | Retrieves page with appointments for specified calendar folder |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage/#listappointmentsbypage_1)(MailQuery, int, int) | Retrieves page with appointments for calendar folder |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage/#listappointmentsbypage_7)(string, int, int) | Retrieves page with appointments for specified calendar folder |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage/#listappointmentsbypage_4)(string, MailQuery, int) | Retrieves page with appointments for specified calendar folder |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage/#listappointmentsbypage_5)(string, MailQuery, int, int) | Retrieves page with appointments for specified calendar folder |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts/#listcontacts)(string) | Lists contacts located in the specified folder on server |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts/#listcontacts_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Lists contacts located in the specified folder on server |
| [ListDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/listdelegates/)(string) | Lists the users who are granted access on the specified mailbox. |
| [ListDistributionLists](../../aspose.email.clients.exchange.webservice/iewsclient/listdistributionlists/)() | List the private Distribution Lists. |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems/#listitems)(string) | Retrieve list of item uries in specified folder |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems/#listitems_1)(string, MailQuery) | Retrieve list of item uries in specified folder |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems/#listitems_3)(string, string) | Retrieve list of item uries in specified folder |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems/#listitems_2)(string, MailQuery, bool) | Retrieve list of item uries in specified folder |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems/#listitems_4)(string, string, MailQuery) | Retrieve list of item uries in specified folder |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems/#listitems_5)(string, string, MailQuery, bool) | Retrieve list of item uries in specified folder |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes/#listmailboxes)() | Lists mailboxes. |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes/#listmailboxes_1)(string) | Please pay your attention, this overridden method works with Exchange Server 2013 and higher. Lists mailboxes. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages)() | List the messages in the inbox folder. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages_1)(IEnumerable&lt;string&gt;) | List the messages in the specified folder. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages_2)(string) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages_7)(string, bool) | List the messages in the specified folder |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages_3)(string, ExchangeListMessagesOptions) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages_8)(string, int) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages_5)(string, MailQuery) | List the messages in the specified folder. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages_4)(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) | List the messages in the specified folder |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages_9)(string, int, ExchangeListMessagesOptions) | Lists the messages. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages_10)(string, int, MailQuery) | List the messages in the specified folder. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages_6)(string, MailQuery, bool) | List the messages in the specified folder. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages_13)(string, string, bool) | List the messages in the specified folder |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages_12)(string, string, MailQuery) | List the messages in the specified folder. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages/#listmessages_11)(string, int, MailQuery, bool) | List the messages in the specified folder. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/#listmessagesbypage_4)(string, int) | List the messages in the specified folder. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/#listmessagesbypage)(string, PageInfo) | List the messages in the specified folder. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/#listmessagesbypage_5)(string, int, int) | List the messages in the specified folder. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/#listmessagesbypage_2)(string, MailQuery, int) | List the messages in the specified folder. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/#listmessagesbypage_1)(string, PageInfo, ExchangeListMessagesOptions) | List the messages in the specified folder. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/#listmessagesbypage_6)(string, int, int, ExchangeListMessagesOptions) | List the messages in the specified folder. |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/#listmessagesbypage_3)(string, MailQuery, int, int) | List the messages in the specified folder. |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder/#listmessagesfrompublicfolder)(ExchangeFolderInfo) | Get collection of messages from public folder |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder/#listmessagesfrompublicfolder_1)(string) | Get collection of messages from public folder |
| [ListPublicFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listpublicfolders/)() | Gets collection of public folders from root public folder |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders/#listsubfolders)(ExchangeFolderInfo) | Gets collection of child public folders from parent |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders/#listsubfolders_1)(string) | Gets collection of child folders from parent |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders/#listsubfolders_2)(string, string) | Gets collection of child folders from parent |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage/#listsubfoldersbypage_1)(string, int) | Searches the specified folder in the given parent folder with paging Method supports paging. Invokes for the first time in paging cycle. |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage/#listsubfoldersbypage)(string, PageInfo) | Searches the specified folder in the given parent folder with paging Method supports paging. |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage/#listsubfoldersbypage_2)(string, int, int) | Searches the specified folder in the given parent folder with paging Method supports paging. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks/#listtasks)() | Retrieves lists of exchange tasks for default folder. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks/#listtasks_1)(string) | Retrieves lists of exchange tasks. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks/#listtasks_3)(string, int) | Retrieves lists of exchange tasks. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks/#listtasks_2)(string, MailQuery) | Retrieves lists of exchange tasks. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks/#listtasks_4)(string, int, MailQuery) | Retrieves lists of exchange tasks. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks/#listtasks_5)(string, int, MailQuery, bool) | Retrieves lists of exchange tasks. |
| [LoadContactPhoto](../../aspose.email.clients.exchange.webservice/iewsclient/loadcontactphoto/)(ContactPhoto) | Loads contact photo binary data |
| [MailDisablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/maildisablepublicfolder/)(string) | Mail-disable a public folder |
| [MailEnablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/mailenablepublicfolder/)(string) | Mail-enable a public folder |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems/#markallitems_2)(bool, params string[]) | Marks all items in specified folders. |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems/#markallitems)(bool, bool, IEnumerable&lt;string&gt;) | Marks all items in specified folders. |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems/#markallitems_1)(bool, bool, params string[]) | Marks all items in specified folders. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread/#markallitemsasread)() | Marks all items in inbox folder as read without receipts. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread/#markallitemsasread_1)(IEnumerable&lt;string&gt;) | Marks all items in specified folders as read without receipts. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread/#markallitemsasread_2)(params string[]) | Marks all items in specified folders as read without receipts. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread/#markallitemsasunread)() | Marks all items in inbox folder as unread. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread/#markallitemsasunread_1)(IEnumerable&lt;string&gt;) | Marks all items in specified folders as unread. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread/#markallitemsasunread_2)(params string[]) | Marks all items in specified folders as unread. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk/#markasjunk_2)(bool, IEnumerable&lt;string&gt;) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk/#markasjunk_3)(bool, params string[]) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk/#markasjunk)(bool, bool, IEnumerable&lt;string&gt;) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk/#markasjunk_1)(bool, bool, params string[]) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk/#markasjunk_4)(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems/#moveconversationitems)(string, string) | Moves the conversation items into the specified target folder |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems/#moveconversationitems_1)(string, string, string) | Moves the conversation items, which are located in the specified folder, into the specified target folder |
| [MoveItem](../../aspose.email.clients.exchange.webservice/iewsclient/moveitem/)(string, string) | Moves the item to specified folder |
| [PlayOnPhone](../../aspose.email.clients.exchange.webservice/iewsclient/playonphone/)(string, string) | The PlayOnPhone operation initiates an outbound call and plays a message over the telephone. |
| [RemoveHeader](../../aspose.email.clients.exchange.webservice/iewsclient/removeheader/)(string) | Remove WebHeader from WebHeaderCollection in EWS request. |
| [Reply](../../aspose.email.clients.exchange.webservice/iewsclient/reply/)(MailMessage, ExchangeMessageInfo) | Reply to the sender's message. |
| [ReplyAll](../../aspose.email.clients.exchange.webservice/iewsclient/replyall/)(MailMessage, ExchangeMessageInfo) | Reply to the sender and all recipients of a message. |
| [ResetImpersonation](../../aspose.email.clients.exchange.webservice/iewsclient/resetimpersonation/)() | Makes the impersonation reset. |
| [ResetSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/resetsubscription/)() | Reset all subscriptions |
| [ResolveContact](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontact/)(string) | Resolves ambiguous mailbox names. |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts/#resolvecontacts)(string) | Resolves ambiguous mailbox display names. Note: the maximum count of returned contacts is 100. This is a restriction of used exchange command. |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts/#resolvecontacts_1)(string, ExchangeListContactsOptions) | Resolves ambiguous e-mail addresses and display names Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation. |
| [Restore](../../aspose.email.clients.exchange.webservice/iewsclient/restore/)(PersonalStorage, RestoreSettings) | Restores the specified exchange folders from the given personal storage. |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage/#savemessage)(string, Stream) | Saves the message. |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage/#savemessage_1)(string, string) | Saves the message. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send/#send)(MailMessage) | Sends the specified message. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send/#send_1)(MailMessage, FollowUpOptions) | Sends the message. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send/#send_2)(string, string, string, string) | Sends the specified message |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate/#setconversationreadstate)(string, bool) | Set read state of the conversation items to the specified value |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate/#setconversationreadstate_1)(string, string, bool) | Set read state of the conversation items, which are located in the specified folder, to the specified value |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag/#setreadflag)(string) | Sets the read flag. |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag/#setreadflag_1)(string, bool) | Marks the specifeid message as read. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder/#syncfolder_1)(string) | Retrieves changes of the items and subfolders in a specified folder. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder/#syncfolder)(SyncState) | Retrieves changes of the items in a specified folder. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder/#syncfolder_3)(string, string) | Retrieves changes of the items in a specified folder. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder/#syncfolder_2)(string, SyncFolderType) | Retrieves changes of the items and subfolders in a specified folder. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder/#syncfolder_4)(string, string, IEnumerable&lt;string&gt;) | Retrieves changes of the items in a specified folder. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment/#updateappointment)(Appointment) | Updates appointment. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment/#updateappointment_2)(MapiCalendar) | Updates appointment. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment/#updateappointment_1)(Appointment, string) | Updates appointment. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment/#updateappointment_3)(MapiCalendar, string) | Updates appointment. |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact/#updatecontact_1)(Contact) | Updates a contact item in the Exchange store. |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact/#updatecontact)(MapiContact) | Updates a contact item in the Exchange store. |
| [UpdateDelegate](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegate/)(ExchangeDelegateUser, string) | Updates the delegate user settings who is granted access on the specified mailbox. |
| [UpdateDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegates/)(ExchangeDelegateUserCollection, string) | Updates the delegate users settings who are granted access on the specified mailbox. |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule/#updateinboxrule)(InboxRule) | Updates the specified inbox rule |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule/#updateinboxrule_1)(InboxRule, string) | Updates the specified inbox rule |
| [UpdateItems](../../aspose.email.clients.exchange.webservice/iewsclient/updateitems/)(ExchangeStreamedItem[], string) | Updates the specified items in to a mailbox |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote/#updatenote)(MapiNote) | Updates the specified note. |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote/#updatenote_1)(string, MapiNote) | Updates the specified note. |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote/#updatenote_2)(string, MapiNote, IEnumerable&lt;PropertyDescriptor&gt;) | Updates the specified note. |
| [UpdateSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/updatesubscription/)() | Updates subscriptions |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask/#updatetask_3)(ExchangeTask) | Updates the specified task. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask/#updatetask)(MapiTask) | Updates the specified task. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask/#updatetask_4)(ExchangeTask, UpdateTaskOptions) | Updates the specified task. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask/#updatetask_1)(string, MapiTask) | Updates the specified task. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask/#updatetask_2)(string, MapiTask, IEnumerable&lt;PropertyDescriptor&gt;) | Updates the specified task. |
| [UpdateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/updateuserconfiguration/)(UserConfiguration) | Updates the specified user configuration |

## Events

| Name | Description |
| --- | --- |
| event [CalendarFolderServerNotifications](../../aspose.email.clients.exchange.webservice/iewsclient/calendarfolderservernotifications/) | Occurs when arises specified event type for Calendar folder. |
| event [ContactsFolderServerNotifications](../../aspose.email.clients.exchange.webservice/iewsclient/contactsfolderservernotifications/) | Occurs when arises specified event type for Contacts folder. |
| event [DeletedItemsFolderServerNotifications](../../aspose.email.clients.exchange.webservice/iewsclient/deleteditemsfolderservernotifications/) | Occurs when arises specified event type for DeletedItems folder. |
| event [DraftsFolderServerNotifications](../../aspose.email.clients.exchange.webservice/iewsclient/draftsfolderservernotifications/) | Occurs when arises specified event type for Drafts folder. |
| event [InboxFolderServerNotifications](../../aspose.email.clients.exchange.webservice/iewsclient/inboxfolderservernotifications/) | Occurs when arises specified event type for Inbox folder. |
| event [ItemSent](../../aspose.email.clients.exchange.webservice/iewsclient/itemsent/) | Raised when an item is sent and save in Sent Items folder. |
| event [JournalFolderServerNotifications](../../aspose.email.clients.exchange.webservice/iewsclient/journalfolderservernotifications/) | Occurs when arises specified event type for Journal folder. |
| event [NotesFolderServerNotifications](../../aspose.email.clients.exchange.webservice/iewsclient/notesfolderservernotifications/) | Occurs when arises specified event type for Notes folder. |
| event [OutboxFolderServerNotifications](../../aspose.email.clients.exchange.webservice/iewsclient/outboxfolderservernotifications/) | Occurs when arises specified event type for Outbox folder. |
| event [RootFolderServerNotifications](../../aspose.email.clients.exchange.webservice/iewsclient/rootfolderservernotifications/) | Occurs when arises specified event type for Root folder. |
| event [SentItemsFolderServerNotifications](../../aspose.email.clients.exchange.webservice/iewsclient/sentitemsfolderservernotifications/) | Occurs when arises specified event type for SentItems folder. |
| event [TasksFolderServerNotifications](../../aspose.email.clients.exchange.webservice/iewsclient/tasksfolderservernotifications/) | Occurs when arises specified event type for Tasks folder. |

### See Also

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase/)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice/)
* assembly [Aspose.Email](../../)


