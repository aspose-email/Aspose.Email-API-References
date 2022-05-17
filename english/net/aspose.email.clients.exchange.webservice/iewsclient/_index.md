---
title: IEWSClient
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 3960
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
| [CalendarFolderEventFilter](calendarfoldereventfilter) { get; set; } | Specifies event types for Calendar folder |
| [ContactsFolderEventFilter](contactsfoldereventfilter) { get; set; } | Specifies event types for Contacts folder |
| [CurrentCalendarFolderUri](currentcalendarfolderuri) { get; set; } | Gets or sets current calendar folder uri |
| [DeletedItemsFolderEventFilter](deleteditemsfoldereventfilter) { get; set; } | Specifies event types for DeletedItems folder |
| [DraftsFolderEventFilter](draftsfoldereventfilter) { get; set; } | Specifies event types for Drafts folder |
| [EnableDecompression](enabledecompression) { get; set; } | Gets or sets a value that indicates whether decompression is enabled |
| [Headers](headers) { get; } | Gets array of name value pairs wich are added to WebHeaderCollection in EWS request. |
| [InboxFolderEventFilter](inboxfoldereventfilter) { get; set; } | Specifies event types for Inbox folder |
| [JournalFolderEventFilter](journalfoldereventfilter) { get; set; } | Specifies event types for Journal folder |
| [MailboxInfo](mailboxinfo) { get; } | Gets the mailbox info. |
| [NotesFolderEventFilter](notesfoldereventfilter) { get; set; } | Specifies event types for Notes folder |
| [NotificationsCheckInterval](notificationscheckinterval) { get; set; } | Defines interval for notification check |
| [NotificationTimeout](notificationtimeout) { get; set; } | Defines timeout for server notifications |
| [OutboxFolderEventFilter](outboxfoldereventfilter) { get; set; } | Specifies event types for Outbox folder |
| [ReconnectCount](reconnectcount) { get; set; } | Gets or sets the number of reconnect attempts at connection breaks. |
| [ReturnClientRequestId](returnclientrequestid) { get; set; } | Gets or sets a flag to indicate whether the client requires the server side to return the request id. |
| [RootFolderEventFilter](rootfoldereventfilter) { get; set; } | Specifies event types for Root folder |
| [SentItemsFolderEventFilter](sentitemsfoldereventfilter) { get; set; } | Specifies event types for SentItems folder |
| [ServerVersion](serverversion) { get; } | Gets the information about the current version of MS Exchange. |
| [TasksFolderEventFilter](tasksfoldereventfilter) { get; set; } | Specifies event types for Tasks folder |
| [TimezoneId](timezoneid) { get; set; } | Gets or sets timezone id |
| [UseSlashAsFolderSeparator](useslashasfolderseparator) { get; set; } | Gets or sets value that determines whether the slash '/' is used as folder separator. |

## Methods

| Name | Description |
| --- | --- |
| [AddHeader](addheader)(string, string) | Adds name and value to WebHeaderCollection in EWS request. |
| [AddToDistributionList](addtodistributionlist)(ExchangeDistributionList, MailAddressCollection) | Appends the members to Distribution List. |
| [AppendMessage](appendmessage)(MailMessage) | Uploads the mail message to the Inbox folder |
| [AppendMessage](appendmessage)(MapiMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](appendmessage)(MapiMessage, bool) | Uploads the mail message to the specified folder |
| [AppendMessage](appendmessage)(string, MailMessage) | Uploads the mail message to the specified folder |
| [AppendMessage](appendmessage)(string, MapiMessage, bool) | Uploads the mail message to the specified folder |
| [AppendMessages](appendmessages)(IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the specified folder |
| [AppendMessages](appendmessages)(params MailMessage[]) | Uploads the mail message to the specified folder |
| [AppendMessages](appendmessages)(string, IEnumerable&lt;MailMessage&gt;) | Uploads the mail message to the specified folder |
| [AppendMessages](appendmessages)(string, params MailMessage[]) | Uploads the mail message to the specified folder |
| [ArchiveItem](archiveitem)(string, Appointment) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [ArchiveItem](archiveitem)(string, ExchangeTask) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [ArchiveItem](archiveitem)(string, MapiMessageItemBase) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [ArchiveItem](archiveitem)(string, string) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [Backup](backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Backups the content of the specified folders |
| [Backup](backup)(ExchangeFolderInfoCollection, string, BackupOptions) | Backups the content of the specified folders |
| [CancelAppointment](cancelappointment)(Appointment) | Cancels appointment. |
| [CancelAppointment](cancelappointment)(MapiCalendar) | Cancels appointment. |
| [CancelAppointment](cancelappointment)(string) | Cancels an exiting meeting on an organizers calendar |
| [CancelAppointment](cancelappointment)(Appointment, string) | Cancels appointment. |
| [CancelAppointment](cancelappointment)(MapiCalendar, string) | Cancels appointment. |
| [CancelAppointment](cancelappointment)(string, string) | Cancels an exiting meeting on an organizers calendar |
| [CheckUserAvailability](checkuseravailability)(string, DateRange) | Checks user availability within the specified time window. |
| [CheckUserAvailability](checkuseravailability)(StringCollection, DateRange) | Checks users availability within the specified time window. |
| [CloseAccess](closeaccess)(ExchangeDelegateUser, string) | Closes access on the specified mailbox for the specified user. |
| [CloseAccess](closeaccess)(ExchangeDelegateUserCollection, string) | Closes access on the specified mailbox for the specified user. |
| [CloseAccess](closeaccess)(ExchangeFolderUserInfo, string) | Closes access on the specified mailbox for the specified user. |
| [CloseAccess](closeaccess)(string, string) | Closes access on the specified mailbox for the specified user. |
| [CopyConversationItems](copyconversationitems)(string, string) | Copies the conversation items into the specified target folder |
| [CopyConversationItems](copyconversationitems)(string, string, string) | Copies the conversation items, which are located in the specified folder, into the specified target folder |
| [CopyItem](copyitem)(string, string) | Copies the item to specified folder |
| [CreateAppointment](createappointment)(Appointment) | Creates appointment. |
| [CreateAppointment](createappointment)(Appointment, string) | Creates appointment. |
| [CreateAppointment](createappointment)(MapiCalendar, string, bool) | Creates appointment. |
| [CreateCalendarSharingInvitationMessage](createcalendarsharinginvitationmessage)(string) | Create calendar sharing invitation message. |
| [CreateContact](createcontact)(Contact) | Creates a contact item in the Exchange store. |
| [CreateContact](createcontact)(string, Contact) | Creates a contact item in the specified folder. |
| [CreateDistributionList](createdistributionlist)(ExchangeDistributionList, MailAddressCollection) | Creates the private Distribution List. |
| [CreateFolder](createfolder)(string) | Creates new folder in the root folder. |
| [CreateFolder](createfolder)(string, ExchangeFolderType) | Creates new folder in the root folder. |
| [CreateFolder](createfolder)(string, string) | Creates the new folder with the specified name in the specified parent folder. |
| [CreateFolder](createfolder)(string, string, ExchangeFolderPermissionCollection) | Creates the new folder |
| [CreateFolder](createfolder)(string, string, ExchangeFolderType) | Creates the new folder |
| [CreateFolder](createfolder)(string, string, ExchangeFolderPermissionCollection, string) | Creates the new folder |
| [CreateInboxRule](createinboxrule)(InboxRule) | Creates the specified inbox rule |
| [CreateInboxRule](createinboxrule)(InboxRule, string) | Creates the specified inbox rule |
| [CreateItem](createitem)(MapiMessageItemBase) | Creates the given item in the default item folder. |
| [CreateItem](createitem)(string, MapiMessageItemBase) | Creates the given item in the specified folder. |
| [CreateItems](createitems)(ExchangeStreamedItem[], string) | Creates the specified items in the speciifed folder |
| [CreatePublicFolder](createpublicfolder)(string, ExchangeFolderPermissionCollection) | Creates the specified public folder in the root public folder |
| [CreatePublicFolder](createpublicfolder)(string, ExchangeFolderPermissionCollection, ExchangeFolderType) | Creates the specified public folder in the root public folder |
| [CreatePublicFolder](createpublicfolder)(string, string, ExchangeFolderPermissionCollection) | Creates the specified public folder in the root public folder |
| [CreateTask](createtask)(ExchangeTask) | Creates the given task in the default task folder. |
| [CreateTask](createtask)(string, ExchangeTask) | Creates the given task in the specified folder. |
| [CreateUserConfiguration](createuserconfiguration)(UserConfiguration) | Creates the specified user configuration |
| [DelegateAccess](delegateaccess)(ExchangeDelegateUser, string) | Delegates access on the specified mailbox to the specified user. |
| [DelegateAccess](delegateaccess)(ExchangeDelegateUserCollection, string) | Delegates access on the mailbox to the specified users. |
| [DelegateAccess](delegateaccess)(string, ExchangeDelegateFolderPermissionLevel, string) | Delegates access on the principal mailbox to the specified user. |
| [DeleteConversationItems](deleteconversationitems)(string) | Deletes all items of the specified conversation |
| [DeleteConversationItems](deleteconversationitems)(string, string) | Deletes the conversation items, which are located in the specified folder |
| [DeleteDistributionList](deletedistributionlist)(ExchangeDistributionList, bool) | Deletes the Distribution List. |
| [DeleteFolder](deletefolder)(string) | Deletes the folder |
| [DeleteFolder](deletefolder)(string, bool) | Deletes the folder |
| [DeleteFolders](deletefolders)(ExchangeFolderInfoCollection) | Deletes the specified folders |
| [DeleteFolders](deletefolders)(StringCollection) | Deletes the specified folders |
| [DeleteFolders](deletefolders)(ExchangeFolderInfoCollection, bool) | Deletes the specified folders |
| [DeleteFolders](deletefolders)(StringCollection, bool) | Deletes the folder |
| [DeleteFromDistributionList](deletefromdistributionlist)(ExchangeDistributionList, MailAddressCollection) | Deletes the members from Distribution List. |
| [DeleteInboxRule](deleteinboxrule)(string) | Deletes the specified inbox rule |
| [DeleteInboxRule](deleteinboxrule)(string, string) | Deletes the specified inbox rule |
| [DeleteItem](deleteitem)(string, DeletionOptions) | Deletes specified item |
| [DeleteItems](deleteitems)(IEnumerable&lt;string&gt;, DeletionOptions) | Deletes specified items |
| [DeleteUserConfiguration](deleteuserconfiguration)(UserConfigurationName) | Deletes the specified user configuration |
| [DisconnectPhoneCall](disconnectphonecall)(string) | Disconnects a phone call specified by id. |
| [EmptyFolder](emptyfolder)(string) | Empties the specified folder. Subfolders will not be deleted; deleted items will be moved into DeletedItems folder |
| [EmptyFolder](emptyfolder)(string, EmptyFolderOptions) | Empties the specified folder |
| [ExpandDistributionList](expanddistributionlist)(MailAddress) | Expands the public Distribution List members. |
| [ExportItems](exportitems)(params string[]) | Exports the specified items from mailbox |
| [FetchAppointment](fetchappointment)(string) | Fetch the specified appointment from server. |
| [FetchAppointment](fetchappointment)(string, string) | Fetch the specified appointment from server. |
| [FetchAttachment](fetchattachment)(string) | Fetches the attachment |
| [FetchConversationMessages](fetchconversationmessages)(string) | Fetches the specified conversation messages |
| [FetchDistributionList](fetchdistributionlist)(ExchangeDistributionList) | Fetches the private Distribution List members. |
| [FetchItem](fetchitem)(string) | Retrieves the item as [`MapiMessage`](../../aspose.email.mapi/mapimessage). |
| [FetchItem](fetchitem)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Retrieves the item as [`MapiMessage`](../../aspose.email.mapi/mapimessage). |
| [FetchItems](fetchitems)(EwsFetchItems) | Retrieves the items. |
| [FetchMapiCalendar](fetchmapicalendar)(IEnumerable&lt;string&gt;) | Fetch array of [`MapiCalendar`](../../aspose.email.mapi/mapicalendar) objects. |
| [FetchMapiCalendar](fetchmapicalendar)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Fetch array of [`MapiCalendar`](../../aspose.email.mapi/mapicalendar) objects. |
| [FetchMapiMessages](fetchmapimessages)(IEnumerable&lt;string&gt;) | Fetches the speciifed messages |
| [FetchMapiMessages](fetchmapimessages)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Fetches the speciifed messages |
| [FetchMapiNotes](fetchmapinotes)(IEnumerable&lt;string&gt;) | Fetch array of [`MapiNote`](../../aspose.email.mapi/mapinote) objects. |
| [FetchMapiNotes](fetchmapinotes)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Fetch array of [`MapiNote`](../../aspose.email.mapi/mapinote) objects. |
| [FetchMapiTasks](fetchmapitasks)(IEnumerable&lt;string&gt;) | Fetch array of [`MapiTask`](../../aspose.email.mapi/mapitask) objects. |
| [FetchMapiTasks](fetchmapitasks)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Fetch array of [`MapiTask`](../../aspose.email.mapi/mapitask) objects. |
| [FetchMessage](fetchmessage)(string) | Fetches the message. |
| [FetchMessage](fetchmessage)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Fetches the message from server |
| [FetchMessages](fetchmessages)(IEnumerable&lt;ExchangeMessageInfo&gt;) | Fetches the speciifed messages |
| [FetchMessages](fetchmessages)(IEnumerable&lt;string&gt;) | Fetches the speciifed messages |
| [FetchMessages](fetchmessages)(StringCollection) | Fetches the speciifed messages |
| [FetchMessages](fetchmessages)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | Fetches the speciifed messages |
| [FetchTask](fetchtask)(string) | Fetches the specified task. |
| [FindConversations](findconversations)(string) | Finds conversations in the specified folder |
| [FindMessageTrackingReport](findmessagetrackingreport)(FindMessageTrackingReportOptions) | Finds messages that meet the specified criteria. |
| [FindPeople](findpeople)(string, int) | Find contacts located in the global address list (GAL) on server. |
| [FindPeople](findpeople)(string, MailQuery, int) | Find contacts located in the specified user's personal mailbox on server. |
| [FolderExists](folderexists)(string, string) | Checks whether the specified folder exists. |
| [FolderExists](folderexists)(string, string, out ExchangeFolderInfo) | Checks whether the specified folder exists. |
| [Forward](forward)(MailMessage, ExchangeMessageInfo) | Forward a message. |
| [GetCallInfo](getcallinfo)(string) | Retrieves phone call information by call id |
| [GetContact](getcontact)(ObjectIdentifier) | Retrieves contact information according to specified identifier. |
| [GetContact](getcontact)(string) | Retrieves contact information according to specified identifier. |
| [GetContact](getcontact)(ObjectIdentifier, ExchangeListContactsOptions) | Retrieves contact information according to specified identifier. |
| [GetContact](getcontact)(string, ExchangeListContactsOptions) | Retrieves contact information according to specified identifier. |
| [GetContacts](getcontacts)(string) | Lists contacts located in the specified folder on server |
| [GetContacts](getcontacts)(string, ExchangeListContactsOptions) | Lists contacts located in the specified folder on server |
| [GetExchangeType](getexchangetype)() | Gets the information about the current version of MS Exchange. |
| [GetFolderInfo](getfolderinfo)(string) | Gets the folder information |
| [GetFolderPermissions](getfolderpermissions)(string) | Gets the folder permissions. |
| [GetInboxRules](getinboxrules)() | Gets inbox rules |
| [GetInboxRules](getinboxrules)(string) | Gets inbox rules |
| [GetMailboxes](getmailboxes)() | Lists mailboxes having smtp addresses. Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation. |
| [GetMailboxInfo](getmailboxinfo)() | Gets the mailbox info. |
| [GetMailboxInfo](getmailboxinfo)(string) | Gets the mailbox information |
| [GetMailboxSize](getmailboxsize)() | Gets the size of the mailbox. Please, note this operation is performed recursively for all subfolders and make take some time |
| [GetMailboxSizeEx](getmailboxsizeex)(string) | Gets the size of the mailbox Please, note this operation is performed recursively for all subfolders and make take some time |
| [GetMailTips](getmailtips)(GetMailTipsOptions) | Gets mail tips |
| [GetMessageTrackingReport](getmessagetrackingreport)(GetMessageTrackingReportOptions) | Gets message tracking report |
| [GetServerTimeZoneIds](getservertimezoneids)() | The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server. |
| [GetServerTimeZoneIds](getservertimezoneids)(IEnumerable&lt;string&gt;) | The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server. |
| [GetServerTimeZoneIds](getservertimezoneids)(params string[]) | The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server. |
| [GetUMConfiguration](getumconfiguration)() | Retrieves unified messaging configuration |
| [GetUserConfiguration](getuserconfiguration)(UserConfigurationName) | Gets the specified user configuration |
| [GetVersionInfo](getversioninfo)() | Returns exchange server version info |
| [ImpersonateUser](impersonateuser)(ItemChoice, string) | Impersonates the user. |
| [ListAppointments](listappointments)() | Retrieves list of appointments for default calendar folder |
| [ListAppointments](listappointments)(bool) | Retrieves list of appointments for default calendar folder |
| [ListAppointments](listappointments)(MailQuery) | Retrieves list of appointments for default calendar folder |
| [ListAppointments](listappointments)(string) | Retrieves list of appointments for specified calendar folder |
| [ListAppointments](listappointments)(MailQuery, bool) | Retrieves list of appointments for default calendar folder |
| [ListAppointments](listappointments)(string, bool) | Retrieves list of appointments for specified calendar folder |
| [ListAppointments](listappointments)(string, MailQuery) | Retrieves list of appointments for specified calendar folder |
| [ListAppointments](listappointments)(string, MailQuery, bool) | Retrieves list of appointments for specified calendar folder |
| [ListAppointmentsByPage](listappointmentsbypage)(int) | Retrieves page with appointments for calendar folder |
| [ListAppointmentsByPage](listappointmentsbypage)(int, int) | Retrieves page with appointments for calendar folder |
| [ListAppointmentsByPage](listappointmentsbypage)(MailQuery, int) | Retrieves page with appointments for calendar folder |
| [ListAppointmentsByPage](listappointmentsbypage)(string, int) | Retrieves page with appointments for specified calendar folder |
| [ListAppointmentsByPage](listappointmentsbypage)(MailQuery, int, int) | Retrieves page with appointments for calendar folder |
| [ListAppointmentsByPage](listappointmentsbypage)(string, int, int) | Retrieves page with appointments for specified calendar folder |
| [ListAppointmentsByPage](listappointmentsbypage)(string, MailQuery, int) | Retrieves page with appointments for specified calendar folder |
| [ListAppointmentsByPage](listappointmentsbypage)(string, MailQuery, int, int) | Retrieves page with appointments for specified calendar folder |
| [ListContacts](listcontacts)(string) | Lists contacts located in the specified folder on server |
| [ListContacts](listcontacts)(string, IEnumerable&lt;PropertyDescriptor&gt;) | Lists contacts located in the specified folder on server |
| [ListDelegates](listdelegates)(string) | Lists the users who are granted access on the specified mailbox. |
| [ListDistributionLists](listdistributionlists)() | List the private Distribution Lists. |
| [ListItems](listitems)(string) | Retrieve list of item uries in specified folder |
| [ListItems](listitems)(string, MailQuery) | Retrieve list of item uries in specified folder |
| [ListItems](listitems)(string, string) | Retrieve list of item uries in specified folder |
| [ListItems](listitems)(string, MailQuery, bool) | Retrieve list of item uries in specified folder |
| [ListItems](listitems)(string, string, MailQuery) | Retrieve list of item uries in specified folder |
| [ListItems](listitems)(string, string, MailQuery, bool) | Retrieve list of item uries in specified folder |
| [ListMailboxes](listmailboxes)() | Lists mailboxes. |
| [ListMailboxes](listmailboxes)(string) | Please pay your attention, this overridden method works with Exchange Server 2013 and higher. Lists mailboxes. |
| [ListMessages](listmessages)() | List the messages in the inbox folder. |
| [ListMessages](listmessages)(IEnumerable&lt;string&gt;) | List the messages in the specified folder. |
| [ListMessages](listmessages)(string) | Lists the messages. |
| [ListMessages](listmessages)(string, bool) | List the messages in the specified folder |
| [ListMessages](listmessages)(string, ExchangeListMessagesOptions) | Lists the messages. |
| [ListMessages](listmessages)(string, int) | Lists the messages. |
| [ListMessages](listmessages)(string, MailQuery) | List the messages in the specified folder. |
| [ListMessages](listmessages)(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) | List the messages in the specified folder |
| [ListMessages](listmessages)(string, int, ExchangeListMessagesOptions) | Lists the messages. |
| [ListMessages](listmessages)(string, int, MailQuery) | List the messages in the specified folder. |
| [ListMessages](listmessages)(string, MailQuery, bool) | List the messages in the specified folder. |
| [ListMessages](listmessages)(string, string, bool) | List the messages in the specified folder |
| [ListMessages](listmessages)(string, string, MailQuery) | List the messages in the specified folder. |
| [ListMessages](listmessages)(string, int, MailQuery, bool) | List the messages in the specified folder. |
| [ListMessagesByPage](listmessagesbypage)(string, int) | List the messages in the specified folder. |
| [ListMessagesByPage](listmessagesbypage)(string, PageInfo) | List the messages in the specified folder. |
| [ListMessagesByPage](listmessagesbypage)(string, int, int) | List the messages in the specified folder. |
| [ListMessagesByPage](listmessagesbypage)(string, MailQuery, int) | List the messages in the specified folder. |
| [ListMessagesByPage](listmessagesbypage)(string, PageInfo, ExchangeListMessagesOptions) | List the messages in the specified folder. |
| [ListMessagesByPage](listmessagesbypage)(string, int, int, ExchangeListMessagesOptions) | List the messages in the specified folder. |
| [ListMessagesByPage](listmessagesbypage)(string, MailQuery, int, int) | List the messages in the specified folder. |
| [ListMessagesFromPublicFolder](listmessagesfrompublicfolder)(ExchangeFolderInfo) | Get collection of messages from public folder |
| [ListMessagesFromPublicFolder](listmessagesfrompublicfolder)(string) | Get collection of messages from public folder |
| [ListPublicFolders](listpublicfolders)() | Gets collection of public folders from root public folder |
| [ListSubFolders](listsubfolders)(ExchangeFolderInfo) | Gets collection of child public folders from parent |
| [ListSubFolders](listsubfolders)(string) | Gets collection of child folders from parent |
| [ListSubFolders](listsubfolders)(string, string) | Gets collection of child folders from parent |
| [ListSubFoldersByPage](listsubfoldersbypage)(string, int) | Searches the specified folder in the given parent folder with paging Method supports paging. Invokes for the first time in paging cycle. |
| [ListSubFoldersByPage](listsubfoldersbypage)(string, PageInfo) | Searches the specified folder in the given parent folder with paging Method supports paging. |
| [ListSubFoldersByPage](listsubfoldersbypage)(string, int, int) | Searches the specified folder in the given parent folder with paging Method supports paging. |
| [ListTasks](listtasks)() | Retrieves lists of exchange tasks for default folder. |
| [ListTasks](listtasks)(string) | Retrieves lists of exchange tasks. |
| [ListTasks](listtasks)(string, int) | Retrieves lists of exchange tasks. |
| [ListTasks](listtasks)(string, MailQuery) | Retrieves lists of exchange tasks. |
| [ListTasks](listtasks)(string, int, MailQuery) | Retrieves lists of exchange tasks. |
| [ListTasks](listtasks)(string, int, MailQuery, bool) | Retrieves lists of exchange tasks. |
| [LoadContactPhoto](loadcontactphoto)(ContactPhoto) | Loads contact photo binary data |
| [MailDisablePublicFolder](maildisablepublicfolder)(string) | Mail-disable a public folder |
| [MailEnablePublicFolder](mailenablepublicfolder)(string) | Mail-enable a public folder |
| [MarkAllItems](markallitems)(bool, params string[]) | Marks all items in specified folders. |
| [MarkAllItems](markallitems)(bool, bool, IEnumerable&lt;string&gt;) | Marks all items in specified folders. |
| [MarkAllItems](markallitems)(bool, bool, params string[]) | Marks all items in specified folders. |
| [MarkAllItemsAsRead](markallitemsasread)() | Marks all items in inbox folder as read without receipts. |
| [MarkAllItemsAsRead](markallitemsasread)(IEnumerable&lt;string&gt;) | Marks all items in specified folders as read without receipts. |
| [MarkAllItemsAsRead](markallitemsasread)(params string[]) | Marks all items in specified folders as read without receipts. |
| [MarkAllItemsAsUnread](markallitemsasunread)() | Marks all items in inbox folder as unread. |
| [MarkAllItemsAsUnread](markallitemsasunread)(IEnumerable&lt;string&gt;) | Marks all items in specified folders as unread. |
| [MarkAllItemsAsUnread](markallitemsasunread)(params string[]) | Marks all items in specified folders as unread. |
| [MarkAsJunk](markasjunk)(bool, IEnumerable&lt;string&gt;) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [MarkAsJunk](markasjunk)(bool, params string[]) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [MarkAsJunk](markasjunk)(bool, bool, IEnumerable&lt;string&gt;) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [MarkAsJunk](markasjunk)(bool, bool, params string[]) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [MarkAsJunk](markasjunk)(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [MoveConversationItems](moveconversationitems)(string, string) | Moves the conversation items into the specified target folder |
| [MoveConversationItems](moveconversationitems)(string, string, string) | Moves the conversation items, which are located in the specified folder, into the specified target folder |
| [MoveItem](moveitem)(string, string) | Moves the item to specified folder |
| [PlayOnPhone](playonphone)(string, string) | The PlayOnPhone operation initiates an outbound call and plays a message over the telephone. |
| [RemoveHeader](removeheader)(string) | Remove WebHeader from WebHeaderCollection in EWS request. |
| [Reply](reply)(MailMessage, ExchangeMessageInfo) | Reply to the sender's message. |
| [ReplyAll](replyall)(MailMessage, ExchangeMessageInfo) | Reply to the sender and all recipients of a message. |
| [ResetImpersonation](resetimpersonation)() | Makes the impersonation reset. |
| [ResetSubscription](resetsubscription)() | Reset all subscriptions |
| [ResolveContact](resolvecontact)(string) | Resolves ambiguous mailbox names. |
| [ResolveContacts](resolvecontacts)(string) | Resolves ambiguous mailbox display names. Note: the maximum count of returned contacts is 100. This is a restriction of used exchange command. |
| [ResolveContacts](resolvecontacts)(string, ExchangeListContactsOptions) | Resolves ambiguous e-mail addresses and display names Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation. |
| [Restore](restore)(PersonalStorage, RestoreSettings) | Restores the specified exchange folders from the given personal storage. |
| [SaveMessage](savemessage)(string, Stream) | Saves the message. |
| [SaveMessage](savemessage)(string, string) | Saves the message. |
| [Send](send)(MailMessage) | Sends the specified message. |
| [Send](send)(MailMessage, FollowUpOptions) | Sends the message. |
| [Send](send)(string, string, string, string) | Sends the specified message |
| [SetConversationReadState](setconversationreadstate)(string, bool) | Set read state of the conversation items to the specified value |
| [SetConversationReadState](setconversationreadstate)(string, string, bool) | Set read state of the conversation items, which are located in the specified folder, to the specified value |
| [SetReadFlag](setreadflag)(string) | Sets the read flag. |
| [SetReadFlag](setreadflag)(string, bool) | Marks the specifeid message as read. |
| [SyncFolder](syncfolder)(string) | Retrieves changes of the items and subfolders in a specified folder. |
| [SyncFolder](syncfolder)(SyncState) | Retrieves changes of the items in a specified folder. |
| [SyncFolder](syncfolder)(string, string) | Retrieves changes of the items in a specified folder. |
| [SyncFolder](syncfolder)(string, SyncFolderType) | Retrieves changes of the items and subfolders in a specified folder. |
| [SyncFolder](syncfolder)(string, string, IEnumerable&lt;string&gt;) | Retrieves changes of the items in a specified folder. |
| [UpdateAppointment](updateappointment)(Appointment) | Updates appointment. |
| [UpdateAppointment](updateappointment)(MapiCalendar) | Updates appointment. |
| [UpdateAppointment](updateappointment)(Appointment, string) | Updates appointment. |
| [UpdateAppointment](updateappointment)(MapiCalendar, string) | Updates appointment. |
| [UpdateContact](updatecontact)(Contact) | Updates a contact item in the Exchange store. |
| [UpdateContact](updatecontact)(MapiContact) | Updates a contact item in the Exchange store. |
| [UpdateDelegate](updatedelegate)(ExchangeDelegateUser, string) | Updates the delegate user settings who is granted access on the specified mailbox. |
| [UpdateDelegates](updatedelegates)(ExchangeDelegateUserCollection, string) | Updates the delegate users settings who are granted access on the specified mailbox. |
| [UpdateInboxRule](updateinboxrule)(InboxRule) | Updates the specified inbox rule |
| [UpdateInboxRule](updateinboxrule)(InboxRule, string) | Updates the specified inbox rule |
| [UpdateItems](updateitems)(ExchangeStreamedItem[], string) | Updates the specified items in to a mailbox |
| [UpdateNote](updatenote)(MapiNote) | Updates the specified note. |
| [UpdateNote](updatenote)(string, MapiNote) | Updates the specified note. |
| [UpdateNote](updatenote)(string, MapiNote, IEnumerable&lt;PropertyDescriptor&gt;) | Updates the specified note. |
| [UpdateSubscription](updatesubscription)() | Updates subscriptions |
| [UpdateTask](updatetask)(ExchangeTask) | Updates the specified task. |
| [UpdateTask](updatetask)(MapiTask) | Updates the specified task. |
| [UpdateTask](updatetask)(ExchangeTask, UpdateTaskOptions) | Updates the specified task. |
| [UpdateTask](updatetask)(string, MapiTask) | Updates the specified task. |
| [UpdateTask](updatetask)(string, MapiTask, IEnumerable&lt;PropertyDescriptor&gt;) | Updates the specified task. |
| [UpdateUserConfiguration](updateuserconfiguration)(UserConfiguration) | Updates the specified user configuration |

## Other Members

| Name | Description |
| --- | --- |
| event [CalendarFolderServerNotifications](calendarfolderservernotifications) | Occurs when arises specified event type for Calendar folder. |
| event [ContactsFolderServerNotifications](contactsfolderservernotifications) | Occurs when arises specified event type for Contacts folder. |
| event [DeletedItemsFolderServerNotifications](deleteditemsfolderservernotifications) | Occurs when arises specified event type for DeletedItems folder. |
| event [DraftsFolderServerNotifications](draftsfolderservernotifications) | Occurs when arises specified event type for Drafts folder. |
| event [InboxFolderServerNotifications](inboxfolderservernotifications) | Occurs when arises specified event type for Inbox folder. |
| event [ItemSent](itemsent) | Raised when an item is sent and save in Sent Items folder. |
| event [JournalFolderServerNotifications](journalfolderservernotifications) | Occurs when arises specified event type for Journal folder. |
| event [NotesFolderServerNotifications](notesfolderservernotifications) | Occurs when arises specified event type for Notes folder. |
| event [OutboxFolderServerNotifications](outboxfolderservernotifications) | Occurs when arises specified event type for Outbox folder. |
| event [RootFolderServerNotifications](rootfolderservernotifications) | Occurs when arises specified event type for Root folder. |
| event [SentItemsFolderServerNotifications](sentitemsfolderservernotifications) | Occurs when arises specified event type for SentItems folder. |
| event [TasksFolderServerNotifications](tasksfolderservernotifications) | Occurs when arises specified event type for Tasks folder. |

### See Also

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
