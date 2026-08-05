---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient class"
linktitle: "IEWSClient"
articleTitle: "IEWSClient"
second_title: "Aspose.Email for C++"
description: "Represents the interface for Exchange client."
type: docs
weight: 10
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/
---

## IEWSClient class

**Inherits:** Aspose::Email::Clients::Exchange::IExchangeClientBase

Represents the interface for Exchange client.

## Methods

| Name | Description |
| --- | --- |
| [AddHeader](./addheader/) | Adds name and value to WebHeaderCollection in EWS request. |
| [AddToDistributionList](./addtodistributionlist/) | Appends the members to Distribution List. |
| [AppendMessage (5 overloads)](./appendmessage/) | Uploads the mail message to the Inbox folder |
| [AppendMessages (5 overloads)](./appendmessages/) | Uploads the mail message to the specified folder |
| [ArchiveItem (4 overloads)](./archiveitem/) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [Backup (2 overloads)](./backup/) | Backups the content of the specified folders |
| [CancelAppointment (6 overloads)](./cancelappointment/) | Cancels appointment. |
| [CheckUserAvailability (2 overloads)](./checkuseravailability/) | Checks users availability within the specified time window. |
| [CloseAccess (4 overloads)](./closeaccess/) | Closes access on the specified mailbox for the specified user. |
| [CopyConversationItems (2 overloads)](./copyconversationitems/) | Copies the conversation items, which are located in the specified folder, into the specified target folder |
| [CopyItem](./copyitem/) | Copies the item to specified folder |
| [CreateAppointment (3 overloads)](./createappointment/) | Creates appointment. |
| [CreateCalendarSharingInvitationMessage](./createcalendarsharinginvitationmessage/) | Create calendar sharing invitation message. |
| [CreateContact (2 overloads)](./createcontact/) | Creates a contact item in the Exchange store. |
| [CreateDistributionList](./createdistributionlist/) | Creates the private Distribution List. |
| [CreateFolder (6 overloads)](./createfolder/) | Fetch the specified appointment from server. |
| [CreateInboxRule (2 overloads)](./createinboxrule/) | Creates the specified inbox rule |
| [CreateItem (2 overloads)](./createitem/) | Creates the given item in the default item folder. |
| [CreateItems](./createitems/) | Creates the specified items in the speciifed folder |
| [CreatePublicFolder (3 overloads)](./createpublicfolder/) | Creates the specified public folder in the root public folder |
| [CreateTask (2 overloads)](./createtask/) | Creates the given task in the default task folder. |
| [CreateUserConfiguration](./createuserconfiguration/) | Creates the specified user configuration |
| [DelegateAccess (3 overloads)](./delegateaccess/) | Delegates access on the specified mailbox to the specified user. |
| [DeleteConversationItems (2 overloads)](./deleteconversationitems/) | Deletes all items of the specified conversation |
| [DeleteDistributionList](./deletedistributionlist/) | Deletes the Distribution List. |
| [DeleteFolder (2 overloads)](./deletefolder/) | Deletes the folder |
| [DeleteFolders (4 overloads)](./deletefolders/) | Deletes the specified folders |
| [DeleteFromDistributionList](./deletefromdistributionlist/) | Deletes the members from Distribution List. |
| [DeleteInboxRule (2 overloads)](./deleteinboxrule/) | Deletes the specified inbox rule |
| [DeleteItem](./deleteitem/) | Deletes specified item |
| [DeleteItems](./deleteitems/) | Deletes specified items |
| [DeleteUserConfiguration](./deleteuserconfiguration/) | Deletes the specified user configuration |
| [DisconnectPhoneCall](./disconnectphonecall/) | Disconnects a phone call specified by id. |
| [EmptyFolder (2 overloads)](./emptyfolder/) | Empties the specified folder. Subfolders will not be deleted; deleted items will be moved into DeletedItems folder |
| [ExpandDistributionList](./expanddistributionlist/) | Expands the public Distribution List members. |
| [ExportItems](./exportitems/) | Exports the specified items from mailbox |
| [FetchAppointment (2 overloads)](./fetchappointment/) | Fetch the specified appointment from server. |
| [FetchAttachment](./fetchattachment/) | Fetches the attachment |
| [FetchConversationMessages](./fetchconversationmessages/) | Fetches the specified conversation messages |
| [FetchDistributionList](./fetchdistributionlist/) | Fetches the private Distribution List members. |
| [FetchItem (2 overloads)](./fetchitem/) | Retrieves the item as MapiMessage . |
| [FetchMapiCalendar (2 overloads)](./fetchmapicalendar/) | Fetch array of MapiCalendar objects. |
| [FetchMapiMessages (2 overloads)](./fetchmapimessages/) | Fetches the speciifed messages |
| [FetchMapiNotes (2 overloads)](./fetchmapinotes/) | Fetch array of MapiNote objects. |
| [FetchMapiTasks (2 overloads)](./fetchmapitasks/) | Fetch array of MapiTask objects. |
| [FetchMessage (2 overloads)](./fetchmessage/) | Fetches the message. |
| [FetchMessages (4 overloads)](./fetchmessages/) | Fetches the speciifed messages |
| [FetchTask](./fetchtask/) | Fetches the specified task. |
| [FindConversations](./findconversations/) | Finds conversations in the specified folder |
| [FindMessageTrackingReport](./findmessagetrackingreport/) | Finds messages that meet the specified criteria. |
| [FindPeople (2 overloads)](./findpeople/) | Find contacts located in the specified user's personal mailbox on server. |
| [FolderExists (2 overloads)](./folderexists/) | Checks whether the specified folder exists. |
| [Forward](./forward/) | Forward a message. |
| [get_CalendarFolderEventFilter](./get_calendarfoldereventfilter/) | Specifies event types for Calendar folder |
| [get_ContactsFolderEventFilter](./get_contactsfoldereventfilter/) | Specifies event types for Contacts folder |
| [get_CurrentCalendarFolderUri](./get_currentcalendarfolderuri/) | Gets current calendar folder uri |
| [get_DeletedItemsFolderEventFilter](./get_deleteditemsfoldereventfilter/) | Specifies event types for DeletedItems folder |
| [get_DraftsFolderEventFilter](./get_draftsfoldereventfilter/) | Specifies event types for Drafts folder |
| [get_EnableDecompression](./get_enabledecompression/) | Gets a value that indicates whether decompression is enabled |
| [get_Headers](./get_headers/) | Gets array of name value pairs wich are added to WebHeaderCollection in EWS request. |
| [get_InboxFolderEventFilter](./get_inboxfoldereventfilter/) | Specifies event types for Inbox folder |
| [get_JournalFolderEventFilter](./get_journalfoldereventfilter/) | Specifies event types for Journal folder |
| [get_MailboxInfo](./get_mailboxinfo/) | Gets the mailbox info. |
| [get_NotesFolderEventFilter](./get_notesfoldereventfilter/) | Specifies event types for Notes folder |
| [get_NotificationsCheckInterval](./get_notificationscheckinterval/) | Defines interval for notification check |
| [get_NotificationTimeout](./get_notificationtimeout/) | Defines timeout for server notifications |
| [get_OutboxFolderEventFilter](./get_outboxfoldereventfilter/) | Specifies event types for Outbox folder |
| [get_ReconnectCount](./get_reconnectcount/) | Gets the number of reconnect attempts at connection breaks. |
| [get_ReturnClientRequestId](./get_returnclientrequestid/) | Gets a flag to indicate whether the client requires the server side to return the request id. |
| [get_RootFolderEventFilter](./get_rootfoldereventfilter/) | Specifies event types for Root folder |
| [get_SentItemsFolderEventFilter](./get_sentitemsfoldereventfilter/) | Specifies event types for SentItems folder |
| [get_ServerVersion](./get_serverversion/) | Gets the information about the current version of MS Exchange . |
| [get_TasksFolderEventFilter](./get_tasksfoldereventfilter/) | Specifies event types for Tasks folder |
| [get_TimezoneId](./get_timezoneid/) | Gets timezone id |
| [get_UseSlashAsFolderSeparator](./get_useslashasfolderseparator/) | Gets value that determines whether the slash '/' is used as folder separator. |
| [GetCallInfo](./getcallinfo/) | Retrieves phone call information by call id |
| [GetContact (4 overloads)](./getcontact/) | Retrieves contact information according to specified identifier. |
| [GetContacts (2 overloads)](./getcontacts/) | Lists contacts located in the specified folder on server |
| [GetExchangeType](./getexchangetype/) | Gets the information about the current version of MS Exchange . |
| [GetFolderInfo](./getfolderinfo/) | Gets the folder information |
| [GetFolderPermissions](./getfolderpermissions/) | Gets the folder permissions. |
| [GetInboxRules (2 overloads)](./getinboxrules/) | Gets inbox rules |
| [GetMailboxes](./getmailboxes/) | Lists mailboxes having smtp addresses. Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation. |
| [GetMailboxInfo (2 overloads)](./getmailboxinfo/) | Gets the mailbox info. |
| [GetMailboxSize](./getmailboxsize/) | Gets the size of the mailbox. Please, note this operation is performed recursively for all subfolders and make take some time |
| [GetMailboxSizeEx](./getmailboxsizeex/) | Gets the size of the mailbox Please, note this operation is performed recursively for all subfolders and make take some time |
| [GetMailTips](./getmailtips/) | Gets mail tips |
| [GetMessageTrackingReport](./getmessagetrackingreport/) | Gets message tracking report |
| [GetServerTimeZoneIds (3 overloads)](./getservertimezoneids/) | The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server. |
| [GetUMConfiguration](./getumconfiguration/) | Retrieves unified messaging configuration |
| [GetUserConfiguration](./getuserconfiguration/) | Gets the specified user configuration |
| [GetVersionInfo](./getversioninfo/) | Returns exchange server version info |
| [ImpersonateUser](./impersonateuser/) | Impersonates the user. |
| [ListAppointments (8 overloads)](./listappointments/) | Retrieves list of appointments for default calendar folder |
| [ListAppointmentsByPage (8 overloads)](./listappointmentsbypage/) | Retrieves page with appointments for calendar folder |
| [ListContacts (2 overloads)](./listcontacts/) | Lists contacts located in the specified folder on server |
| [ListDelegates](./listdelegates/) | Lists the users who are granted access on the specified mailbox. |
| [ListDistributionLists](./listdistributionlists/) | List the private Distribution Lists. |
| [ListItems (6 overloads)](./listitems/) | Retrieve list of item uries in specified folder |
| [ListMailboxes (2 overloads)](./listmailboxes/) | Lists mailboxes. |
| [ListMessages (14 overloads)](./listmessages/) | List the messages in the inbox folder. |
| [ListMessagesByPage (7 overloads)](./listmessagesbypage/) | List the messages in the specified folder. |
| [ListMessagesFromPublicFolder (2 overloads)](./listmessagesfrompublicfolder/) | Get collection of messages from public folder |
| [ListPublicFolders](./listpublicfolders/) | Gets collection of public folders from root public folder |
| [ListSubFolders (3 overloads)](./listsubfolders/) | Gets collection of child public folders from parent |
| [ListSubFoldersByPage (3 overloads)](./listsubfoldersbypage/) | Searches the specified folder in the given parent folder with paging Method supports paging. Invokes for the first time in paging cycle. |
| [ListTasks (6 overloads)](./listtasks/) | Retrieves lists of exchange tasks for default folder. |
| [LoadContactPhoto](./loadcontactphoto/) | Loads contact photo binary data |
| [MailDisablePublicFolder](./maildisablepublicfolder/) | Mail-disable a public folder |
| [MailEnablePublicFolder](./mailenablepublicfolder/) | Mail-enable a public folder |
| [MarkAllItems (3 overloads)](./markallitems/) | Marks all items in specified folders. |
| [MarkAllItemsAsRead (3 overloads)](./markallitemsasread/) | Marks all items in inbox folder as read without receipts. |
| [MarkAllItemsAsUnread (3 overloads)](./markallitemsasunread/) | Marks all items in inbox folder as unread. |
| [MarkAsJunk (5 overloads)](./markasjunk/) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [MoveConversationItems (2 overloads)](./moveconversationitems/) | Moves the conversation items, which are located in the specified folder, into the specified target folder |
| [MoveItem](./moveitem/) | Moves the item to specified folder |
| [PlayOnPhone](./playonphone/) | The PlayOnPhone operation initiates an outbound call and plays a message over the telephone. |
| [RemoveHeader](./removeheader/) | Remove WebHeader from WebHeaderCollection in EWS request. |
| [Reply](./reply/) | Reply to the sender's message. |
| [ReplyAll](./replyall/) | Reply to the sender and all recipients of a message. |
| [ResetImpersonation](./resetimpersonation/) | Makes the impersonation reset. |
| [ResetSubscription](./resetsubscription/) | Reset all subscriptions |
| [ResolveContact](./resolvecontact/) | Resolves ambiguous mailbox names. |
| [ResolveContacts (2 overloads)](./resolvecontacts/) | Resolves ambiguous mailbox display names. Note: the maximum count of returned contacts is 100. This is a restriction of used exchange command. |
| [Restore](./restore/) | Restores the specified exchange folders from the given personal storage. |
| [SaveMessage (2 overloads)](./savemessage/) | Saves the message. |
| [Send (3 overloads)](./send/) | Sends the specified message. |
| [set_CalendarFolderEventFilter](./set_calendarfoldereventfilter/) | Specifies event types for Calendar folder |
| [set_ContactsFolderEventFilter](./set_contactsfoldereventfilter/) | Specifies event types for Contacts folder |
| [set_CurrentCalendarFolderUri](./set_currentcalendarfolderuri/) | Sets current calendar folder uri |
| [set_DeletedItemsFolderEventFilter](./set_deleteditemsfoldereventfilter/) | Specifies event types for DeletedItems folder |
| [set_DraftsFolderEventFilter](./set_draftsfoldereventfilter/) | Specifies event types for Drafts folder |
| [set_EnableDecompression](./set_enabledecompression/) | Sets a value that indicates whether decompression is enabled |
| [set_InboxFolderEventFilter](./set_inboxfoldereventfilter/) | Specifies event types for Inbox folder |
| [set_JournalFolderEventFilter](./set_journalfoldereventfilter/) | Specifies event types for Journal folder |
| [set_NotesFolderEventFilter](./set_notesfoldereventfilter/) | Specifies event types for Notes folder |
| [set_NotificationsCheckInterval](./set_notificationscheckinterval/) | Defines interval for notification check |
| [set_NotificationTimeout](./set_notificationtimeout/) | Defines timeout for server notifications |
| [set_OutboxFolderEventFilter](./set_outboxfoldereventfilter/) | Specifies event types for Outbox folder |
| [set_ReconnectCount](./set_reconnectcount/) | Sets the number of reconnect attempts at connection breaks. |
| [set_ReturnClientRequestId](./set_returnclientrequestid/) | Sets a flag to indicate whether the client requires the server side to return the request id. |
| [set_RootFolderEventFilter](./set_rootfoldereventfilter/) | Specifies event types for Root folder |
| [set_SentItemsFolderEventFilter](./set_sentitemsfoldereventfilter/) | Specifies event types for SentItems folder |
| [set_TasksFolderEventFilter](./set_tasksfoldereventfilter/) | Specifies event types for Tasks folder |
| [set_TimezoneId](./set_timezoneid/) | Sets timezone id |
| [set_UseSlashAsFolderSeparator](./set_useslashasfolderseparator/) | Sets value that determines whether the slash '/' is used as folder separator. |
| [SetConversationReadState (2 overloads)](./setconversationreadstate/) | Set read state of the conversation items to the specified value |
| [SetReadFlag (2 overloads)](./setreadflag/) | Sets the read flag. |
| [SyncFolder (5 overloads)](./syncfolder/) | Retrieves changes of the items in a specified folder. |
| [UpdateAppointment (4 overloads)](./updateappointment/) | Updates appointment. |
| [UpdateContact (2 overloads)](./updatecontact/) | Updates a contact item in the Exchange store. |
| [UpdateDelegate](./updatedelegate/) | Updates the delegate user settings who is granted access on the specified mailbox. |
| [UpdateDelegates](./updatedelegates/) | Updates the delegate users settings who are granted access on the specified mailbox. |
| [UpdateInboxRule (2 overloads)](./updateinboxrule/) | Updates the specified inbox rule |
| [UpdateItems](./updateitems/) | Updates the specified items in to a mailbox |
| [UpdateNote (3 overloads)](./updatenote/) | Updates the specified note. |
| [UpdateSubscription](./updatesubscription/) | Updates subscriptions |
| [UpdateTask (5 overloads)](./updatetask/) | Updates the specified task. |
| [UpdateUserConfiguration](./updateuserconfiguration/) | Updates the specified user configuration |
| [CalendarFolderServerNotifications](./calendarfolderservernotifications/) | Occurs when arises specified event type for Calendar folder. |
| [ContactsFolderServerNotifications](./contactsfolderservernotifications/) | Occurs when arises specified event type for Contacts folder. |
| [DeletedItemsFolderServerNotifications](./deleteditemsfolderservernotifications/) | Occurs when arises specified event type for DeletedItems folder. |
| [DraftsFolderServerNotifications](./draftsfolderservernotifications/) | Occurs when arises specified event type for Drafts folder. |
| [InboxFolderServerNotifications](./inboxfolderservernotifications/) | Occurs when arises specified event type for Inbox folder. |
| [ItemSent](./itemsent/) | Raised when an item is sent and save in Sent Items folder. |
| [JournalFolderServerNotifications](./journalfolderservernotifications/) | Occurs when arises specified event type for Journal folder. |
| [NotesFolderServerNotifications](./notesfolderservernotifications/) | Occurs when arises specified event type for Notes folder. |
| [OutboxFolderServerNotifications](./outboxfolderservernotifications/) | Occurs when arises specified event type for Outbox folder. |
| [RootFolderServerNotifications](./rootfolderservernotifications/) | Occurs when arises specified event type for Root folder. |
| [SentItemsFolderServerNotifications](./sentitemsfolderservernotifications/) | Occurs when arises specified event type for SentItems folder. |
| [TasksFolderServerNotifications](./tasksfolderservernotifications/) | Occurs when arises specified event type for Tasks folder. |

