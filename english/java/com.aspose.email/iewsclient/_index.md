---
title: IEWSClient
second_title: Aspose.Email for Java API Reference
description: Represents the interface for Exchange client.
type: docs
weight: 743
url: /java/com.aspose.email/iewsclient/
---

**All Implemented Interfaces:**
[com.aspose.email.IExchangeClientBase](../../com.aspose.email/iexchangeclientbase)
```
public interface IEWSClient extends IExchangeClientBase
```

Represents the interface for Exchange client.
## Methods

| Method | Description |
| --- | --- |
| [addHeader(String name, String value)](#addHeader-java.lang.String-java.lang.String-) | Adds name and value to WebHeaderCollection in EWS request. |
| [addToDistributionList(ExchangeDistributionList distributionList, MailAddressCollection members)](#addToDistributionList-com.aspose.email.ExchangeDistributionList-com.aspose.email.MailAddressCollection-) | Appends the members to Distribution List. |
| [appendMapiMessages(String folderUri, Iterable<MapiMessage> messages)](#appendMapiMessages-java.lang.String-java.lang.Iterable-com.aspose.email.MapiMessage--) | Uploads the mapi messages to the specified folder |
| [appendMessage(MailMessage message)](#appendMessage-com.aspose.email.MailMessage-) | Uploads the mail message to the Inbox folder |
| [appendMessage(MapiMessage mapiMessage)](#appendMessage-com.aspose.email.MapiMessage-) | Uploads the mail message to the specified folder |
| [appendMessage(MapiMessage mapiMessage, boolean markAsSent)](#appendMessage-com.aspose.email.MapiMessage-boolean-) | Uploads the mail message to the specified folder |
| [appendMessage(String folderUri, MailMessage message)](#appendMessage-java.lang.String-com.aspose.email.MailMessage-) | Uploads the mail message to the specified folder |
| [appendMessage(String folderUri, MailMessage message, boolean markAsSent)](#appendMessage-java.lang.String-com.aspose.email.MailMessage-boolean-) | Uploads the mail message to the specified folder |
| [appendMessage(String folder, MapiMessage mapiMessage, boolean markAsSent)](#appendMessage-java.lang.String-com.aspose.email.MapiMessage-boolean-) | Uploads the mail message to the specified folder |
| [appendMessages(MailMessage[] messages)](#appendMessages-com.aspose.email.MailMessage...-) | Uploads the mail message to the specified folder |
| [appendMessages(Iterable<MailMessage> messages)](#appendMessages-java.lang.Iterable-com.aspose.email.MailMessage--) | Uploads the mail message to the specified folder |
| [appendMessages(String folderUri, MailMessage[] messages)](#appendMessages-java.lang.String-com.aspose.email.MailMessage...-) | Uploads the mail message to the specified folder |
| [appendMessages(String folderUri, Iterable<MailMessage> messages)](#appendMessages-java.lang.String-java.lang.Iterable-com.aspose.email.MailMessage--) | Uploads the mail message to the specified folder |
| [archiveItem(String sourceFolderUri, Appointment appointment)](#archiveItem-java.lang.String-com.aspose.email.Appointment-) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [archiveItem(String sourceFolderUri, ExchangeTask task)](#archiveItem-java.lang.String-com.aspose.email.ExchangeTask-) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [archiveItem(String sourceFolderUri, MapiMessageItemBase item)](#archiveItem-java.lang.String-com.aspose.email.MapiMessageItemBase-) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [archiveItem(String sourceFolderUri, String uniqueId)](#archiveItem-java.lang.String-java.lang.String-) | The ArchiveItem operation moves an item into the mailbox user's archive mailbox. |
| [backup(ExchangeFolderInfoCollection folders, OutputStream stream, int options)](#backup-com.aspose.email.ExchangeFolderInfoCollection-java.io.OutputStream-int-) | Backups the content of the specified folders |
| [backup(ExchangeFolderInfoCollection folders, String fileName, int options)](#backup-com.aspose.email.ExchangeFolderInfoCollection-java.lang.String-int-) | Backups the content of the specified folders |
| [cancelAppointment(Appointment appointment)](#cancelAppointment-com.aspose.email.Appointment-) | Cancels appointment. |
| [cancelAppointment(Appointment appointment, String folderUri)](#cancelAppointment-com.aspose.email.Appointment-java.lang.String-) | Cancels appointment. |
| [cancelAppointment(MapiCalendar appointment)](#cancelAppointment-com.aspose.email.MapiCalendar-) | Cancels appointment. |
| [cancelAppointment(MapiCalendar appointment, String folderUri)](#cancelAppointment-com.aspose.email.MapiCalendar-java.lang.String-) | Cancels appointment. |
| [cancelAppointment(String uniqueId)](#cancelAppointment-java.lang.String-) | Cancels an exiting meeting on an organizers calendar |
| [cancelAppointment(String uniqueId, String folderUri)](#cancelAppointment-java.lang.String-java.lang.String-) | Cancels an exiting meeting on an organizers calendar |
| [checkUserAvailability(System.Collections.Specialized.StringCollection users, DateRange timeWindow)](#checkUserAvailability-com.aspose.ms.System.Collections.Specialized.StringCollection-com.aspose.email.DateRange-) | Checks users availability within the specified time window. |
| [checkUserAvailability(String user, DateRange timeWindow)](#checkUserAvailability-java.lang.String-com.aspose.email.DateRange-) | Checks user availability within the specified time window. |
| [closeAccess(ExchangeDelegateUser delegateUser, String mailbox)](#closeAccess-com.aspose.email.ExchangeDelegateUser-java.lang.String-) | Closes access on the specified mailbox for the specified user. |
| [closeAccess(ExchangeDelegateUserCollection delegateUsers, String mailbox)](#closeAccess-com.aspose.email.ExchangeDelegateUserCollection-java.lang.String-) | Closes access on the specified mailbox for the specified user. |
| [closeAccess(ExchangeFolderUserInfo userInfo, String mailbox)](#closeAccess-com.aspose.email.ExchangeFolderUserInfo-java.lang.String-) | Closes access on the specified mailbox for the specified user. |
| [closeAccess(String delegateSmtpAddress, String mailbox)](#closeAccess-java.lang.String-java.lang.String-) | Closes access on the specified mailbox for the specified user. |
| [copyConversationItems(String conversationId, String destinationFolderId)](#copyConversationItems-java.lang.String-java.lang.String-) | Copies the conversation items into the specified target folder |
| [copyConversationItems(String conversationId, String contextFolderId, String destinationFolderId)](#copyConversationItems-java.lang.String-java.lang.String-java.lang.String-) | Copies the conversation items, which are located in the specified folder, into the specified target folder |
| [copyItem(String itemUri, String destinationFolderUri)](#copyItem-java.lang.String-java.lang.String-) | Copies the item to specified folder |
| [createAppointment(Appointment appointment)](#createAppointment-com.aspose.email.Appointment-) | Creates appointment. |
| [createAppointment(Appointment appointment, String folderUri)](#createAppointment-com.aspose.email.Appointment-java.lang.String-) | Creates appointment. |
| [createAppointment(MapiCalendar appointment)](#createAppointment-com.aspose.email.MapiCalendar-) | Creates appointment. |
| [createAppointment(MapiCalendar appointment, String folderUri)](#createAppointment-com.aspose.email.MapiCalendar-java.lang.String-) | Creates appointment. |
| [createAppointment(MapiCalendar appointment, String folderUri, boolean suppressInvitations)](#createAppointment-com.aspose.email.MapiCalendar-java.lang.String-boolean-) | Creates appointment. |
| [createCalendarSharingInvitationMessage(String recipient)](#createCalendarSharingInvitationMessage-java.lang.String-) | Create calendar sharing invitation message. |
| [createContact(Contact contact)](#createContact-com.aspose.email.Contact-) | Creates a contact item in the Exchange store. |
| [createContact(MapiContact contact)](#createContact-com.aspose.email.MapiContact-) | Creates a contact item in the Exchange store. |
| [createContact(String folderUri, Contact contact)](#createContact-java.lang.String-com.aspose.email.Contact-) | Creates a contact item in the specified folder. |
| [createContact(String folderUri, MapiContact contact)](#createContact-java.lang.String-com.aspose.email.MapiContact-) | Creates a contact item in the specified folder. |
| [createDistributionList(ExchangeDistributionList distributionList, MailAddressCollection members)](#createDistributionList-com.aspose.email.ExchangeDistributionList-com.aspose.email.MailAddressCollection-) | Creates the private Distribution List. |
| [createFolder(String name)](#createFolder-java.lang.String-) | Creates new folder in the root folder. |
| [createFolder(String name, int folderType)](#createFolder-java.lang.String-int-) | Creates new folder in the root folder. |
| [createFolder(String parentFolderUri, String name)](#createFolder-java.lang.String-java.lang.String-) | Creates the new folder with the specified name in the specified parent folder. |
| [createFolder(String parentFolderUri, String name, ExchangeFolderPermissionCollection permissions)](#createFolder-java.lang.String-java.lang.String-com.aspose.email.ExchangeFolderPermissionCollection-) | Creates the new folder |
| [createFolder(String parentFolderUri, String name, ExchangeFolderPermissionCollection permissions, String folderClass)](#createFolder-java.lang.String-java.lang.String-com.aspose.email.ExchangeFolderPermissionCollection-java.lang.String-) | Creates the new folder |
| [createFolder(String parentFolderUri, String name, int folderType)](#createFolder-java.lang.String-java.lang.String-int-) | Creates the new folder |
| [createInboxRule(InboxRule rule)](#createInboxRule-com.aspose.email.InboxRule-) | Creates the specified inbox rule |
| [createInboxRule(InboxRule rule, String mailbox)](#createInboxRule-com.aspose.email.InboxRule-java.lang.String-) | Creates the specified inbox rule |
| [createItem(MapiMessageItemBase item)](#createItem-com.aspose.email.MapiMessageItemBase-) | Creates the given item in the default item folder. |
| [createItem(String folderUri, MapiMessageItemBase item)](#createItem-java.lang.String-com.aspose.email.MapiMessageItemBase-) | Creates the given item in the specified folder. |
| [createItems(ExchangeStreamedItem[] items, String parentFolderUri)](#createItems-com.aspose.email.ExchangeStreamedItem---java.lang.String-) | Creates the specified items in the speciifed folder |
| [createNote(MapiNote note)](#createNote-com.aspose.email.MapiNote-) | Creates the given note in the default note folder. |
| [createNote(String folder, MapiNote note)](#createNote-java.lang.String-com.aspose.email.MapiNote-) | Creates the given note in the specified folder. |
| [createPublicFolder(String name, ExchangeFolderPermissionCollection permissions)](#createPublicFolder-java.lang.String-com.aspose.email.ExchangeFolderPermissionCollection-) | Creates the specified public folder in the root public folder |
| [createPublicFolder(String name, ExchangeFolderPermissionCollection permissions, int folderType)](#createPublicFolder-java.lang.String-com.aspose.email.ExchangeFolderPermissionCollection-int-) | Creates the specified public folder in the root public folder |
| [createPublicFolder(String parentFolderUri, String name, ExchangeFolderPermissionCollection permissions)](#createPublicFolder-java.lang.String-java.lang.String-com.aspose.email.ExchangeFolderPermissionCollection-) | Creates the specified public folder in the root public folder |
| [createTask(ExchangeTask task)](#createTask-com.aspose.email.ExchangeTask-) | Creates the given task in the default task folder. |
| [createTask(MapiTask task)](#createTask-com.aspose.email.MapiTask-) | Creates the given task in the default task folder. |
| [createTask(String folder, ExchangeTask task)](#createTask-java.lang.String-com.aspose.email.ExchangeTask-) | Creates the given task in the specified folder. |
| [createTask(String folder, MapiTask task)](#createTask-java.lang.String-com.aspose.email.MapiTask-) | Creates the given task in the specified folder. |
| [createUserConfiguration(UserConfiguration userConfiguration)](#createUserConfiguration-com.aspose.email.UserConfiguration-) | Creates the specified user configuration |
| [delegateAccess(ExchangeDelegateUser delegateUser, String mailbox)](#delegateAccess-com.aspose.email.ExchangeDelegateUser-java.lang.String-) | Delegates access on the specified mailbox to the specified user. |
| [delegateAccess(ExchangeDelegateUserCollection delegateUsers, String mailbox)](#delegateAccess-com.aspose.email.ExchangeDelegateUserCollection-java.lang.String-) | Delegates access on the mailbox to the specified users. |
| [delegateAccess(String delegateSmtpAddress, int permissionLevel, String mailbox)](#delegateAccess-java.lang.String-int-java.lang.String-) | Delegates access on the principal mailbox to the specified user. |
| [deleteConversationItems(String conversationId)](#deleteConversationItems-java.lang.String-) | Deletes all items of the specified conversation |
| [deleteConversationItems(String conversationId, String contextFolderId)](#deleteConversationItems-java.lang.String-java.lang.String-) | Deletes the conversation items, which are located in the specified folder |
| [deleteDistributionList(ExchangeDistributionList distributionList, boolean deletePermanently)](#deleteDistributionList-com.aspose.email.ExchangeDistributionList-boolean-) | Deletes the Distribution List. |
| [deleteFolder(String folderUri)](#deleteFolder-java.lang.String-) | Deletes the folder |
| [deleteFolder(String folderUri, boolean deletePermanently)](#deleteFolder-java.lang.String-boolean-) | Deletes the folder |
| [deleteFolders(ExchangeFolderInfoCollection folders)](#deleteFolders-com.aspose.email.ExchangeFolderInfoCollection-) | Deletes the specified folders |
| [deleteFolders(ExchangeFolderInfoCollection folders, boolean deletePermanently)](#deleteFolders-com.aspose.email.ExchangeFolderInfoCollection-boolean-) | Deletes the specified folders |
| [deleteFolders(System.Collections.Specialized.StringCollection folderUris)](#deleteFolders-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Deletes the specified folders |
| [deleteFolders(System.Collections.Specialized.StringCollection folderUris, boolean deletePermanently)](#deleteFolders-com.aspose.ms.System.Collections.Specialized.StringCollection-boolean-) | Deletes the folder |
| [deleteFromDistributionList(ExchangeDistributionList distributionList, MailAddressCollection members)](#deleteFromDistributionList-com.aspose.email.ExchangeDistributionList-com.aspose.email.MailAddressCollection-) | Deletes the members from Distribution List. |
| [deleteInboxRule(String ruleId)](#deleteInboxRule-java.lang.String-) | Deletes the specified inbox rule |
| [deleteInboxRule(String ruleId, String mailbox)](#deleteInboxRule-java.lang.String-java.lang.String-) | Deletes the specified inbox rule |
| [deleteItem(String itemUri, DeletionOptions options)](#deleteItem-java.lang.String-com.aspose.email.DeletionOptions-) | Deletes specified item |
| [deleteItems(Iterable<String> itemUris, DeletionOptions options)](#deleteItems-java.lang.Iterable-java.lang.String--com.aspose.email.DeletionOptions-) | Deletes specified items |
| [deleteUserConfiguration(UserConfigurationName userConfigurationName)](#deleteUserConfiguration-com.aspose.email.UserConfigurationName-) | Deletes the specified user configuration |
| [disconnectPhoneCall(String callId)](#disconnectPhoneCall-java.lang.String-) | Disconnects a phone call specified by id. |
| [emptyFolder(String folderUri)](#emptyFolder-java.lang.String-) | Empties the specified folder. |
| [emptyFolder(String folderUri, int options)](#emptyFolder-java.lang.String-int-) | Empties the specified folder |
| [expandDistributionList(MailAddress mailAddress)](#expandDistributionList-com.aspose.email.MailAddress-) | Expands the public Distribution List members. |
| [exportItems(String[] itemIds)](#exportItems-java.lang.String...-) | Exports the specified items from mailbox |
| [fetchAppointment(String appointmentUri)](#fetchAppointment-java.lang.String-) | Fetch the specified appointment from server. |
| [fetchAppointment(String appointmentUri, String folderUri)](#fetchAppointment-java.lang.String-java.lang.String-) | Fetch the specified appointment from server. |
| [fetchAttachment(String attachmentUri)](#fetchAttachment-java.lang.String-) | Fetches the attachment |
| [fetchContact(String contactUri)](#fetchContact-java.lang.String-) | Fetches [MapiContact](../../com.aspose.email/mapicontact) object |
| [fetchContact(String contactUri, Iterable<PropertyDescriptor> customProperties)](#fetchContact-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Fetches [MapiContact](../../com.aspose.email/mapicontact) object |
| [fetchConversationMessages(String conversationId)](#fetchConversationMessages-java.lang.String-) | Fetches the specified conversation messages |
| [fetchDistributionList(ExchangeDistributionList distributionList)](#fetchDistributionList-com.aspose.email.ExchangeDistributionList-) | Fetches the private Distribution List members. |
| [fetchItem(String uri)](#fetchItem-java.lang.String-) | Retrieves the complete item with attachments. |
| [fetchItem(String uri, Iterable<PropertyDescriptor> extendedProperties)](#fetchItem-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Retrieves the complete item with attachments. |
| [fetchMapiCalendar(Iterable<String> calendarUris)](#fetchMapiCalendar-java.lang.Iterable-java.lang.String--) | Fetch array of [MapiCalendar](../../com.aspose.email/mapicalendar) objects. |
| [fetchMapiCalendar(Iterable<String> calendarUris, Iterable<PropertyDescriptor> customProperties)](#fetchMapiCalendar-java.lang.Iterable-java.lang.String--java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Fetch array of [MapiCalendar](../../com.aspose.email/mapicalendar) objects. |
| [fetchMapiCalendar(String calendarUri)](#fetchMapiCalendar-java.lang.String-) | Fetch [MapiCalendar](../../com.aspose.email/mapicalendar) object. |
| [fetchMapiCalendar(String calendarUri, Iterable<PropertyDescriptor> customProperties)](#fetchMapiCalendar-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Fetch [MapiCalendar](../../com.aspose.email/mapicalendar) object. |
| [fetchMapiMessage(String uri)](#fetchMapiMessage-java.lang.String-) | Fetches the speciifed message |
| [fetchMapiMessage(String uri, Iterable<PropertyDescriptor> extendedProperties)](#fetchMapiMessage-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Fetches the speciifed message |
| [fetchMapiMessages(Iterable<String> uris)](#fetchMapiMessages-java.lang.Iterable-java.lang.String--) | Fetches the speciifed messages |
| [fetchMapiMessages(Iterable<String> uris, Iterable<PropertyDescriptor> extendedProperties)](#fetchMapiMessages-java.lang.Iterable-java.lang.String--java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Fetches the speciifed messages |
| [fetchMapiNote(String noteUri)](#fetchMapiNote-java.lang.String-) | Fetches [MapiNote](../../com.aspose.email/mapinote) object. |
| [fetchMapiNote(String noteUri, Iterable<PropertyDescriptor> customProperties)](#fetchMapiNote-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Fetches [MapiNote](../../com.aspose.email/mapinote) object. |
| [fetchMapiNotes(Iterable<String> noteUris)](#fetchMapiNotes-java.lang.Iterable-java.lang.String--) | Fetch array of [MapiNote](../../com.aspose.email/mapinote) objects. |
| [fetchMapiNotes(Iterable<String> noteUris, Iterable<PropertyDescriptor> customProperties)](#fetchMapiNotes-java.lang.Iterable-java.lang.String--java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Fetch array of [MapiNote](../../com.aspose.email/mapinote) objects. |
| [fetchMapiTask(String taskUri)](#fetchMapiTask-java.lang.String-) | Fetches [MapiTask](../../com.aspose.email/mapitask) object. |
| [fetchMapiTask(String taskUri, Iterable<PropertyDescriptor> customProperties)](#fetchMapiTask-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Fetches [MapiTask](../../com.aspose.email/mapitask) object. |
| [fetchMapiTasks(Iterable<String> taskUris)](#fetchMapiTasks-java.lang.Iterable-java.lang.String--) | Fetch array of [MapiTask](../../com.aspose.email/mapitask) objects. |
| [fetchMapiTasks(Iterable<String> taskUris, Iterable<PropertyDescriptor> customProperties)](#fetchMapiTasks-java.lang.Iterable-java.lang.String--java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Fetch array of [MapiTask](../../com.aspose.email/mapitask) objects. |
| [fetchMessage(String messageUri)](#fetchMessage-java.lang.String-) | Fetches the message. |
| [fetchMessage(String messageUri, Iterable<PropertyDescriptor> extendedProperties)](#fetchMessage-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Fetches the message from server |
| [fetchMessages(ExchangeMessageInfoCollection messageInfos)](#fetchMessages-com.aspose.email.ExchangeMessageInfoCollection-) | Fetches the speciifed messages |
| [fetchMessages(System.Collections.Specialized.StringCollection messageUris)](#fetchMessages-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Fetches the speciifed messages |
| [fetchMessages(Iterable<String> uris)](#fetchMessages-java.lang.Iterable-java.lang.String--) | Fetches the speciifed messages |
| [fetchMessages(Iterable<String> uris, Iterable<PropertyDescriptor> extendedProperties)](#fetchMessages-java.lang.Iterable-java.lang.String--java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Fetches the speciifed messages |
| [fetchTask(String taskUri)](#fetchTask-java.lang.String-) | Fetches the specified task. |
| [findConversations(String folderId)](#findConversations-java.lang.String-) | Finds conversations in the specified folder |
| [findMessageTrackingReport(FindMessageTrackingReportOptions options)](#findMessageTrackingReport-com.aspose.email.FindMessageTrackingReportOptions-) | Finds messages that meet the specified criteria. |
| [findPeople(String folderUri, MailQuery query, int maxNumberOfItems)](#findPeople-java.lang.String-com.aspose.email.MailQuery-int-) | Find contacts located in the specified user's personal mailbox on server. |
| [findPeople(String queryString, int maxNumberOfItems)](#findPeople-java.lang.String-int-) | Find contacts located in the global address list (GAL) on server. |
| [folderExists(String parentFolderUri, String folderName)](#folderExists-java.lang.String-java.lang.String-) | Checks whether the specified folder exists. |
| [folderExists(String parentFolderUri, String folderName, ExchangeFolderInfo[] folder)](#folderExists-java.lang.String-java.lang.String-com.aspose.email.ExchangeFolderInfo---) | Checks whether the specified folder exists. |
| [forward(MailMessage message, ExchangeMessageInfo referencedMessage)](#forward-com.aspose.email.MailMessage-com.aspose.email.ExchangeMessageInfo-) | Forward a message. |
| [forward(MailMessage message, String referencedUri)](#forward-com.aspose.email.MailMessage-java.lang.String-) | Forward a message. |
| [getCalendarFolderEventFilter()](#getCalendarFolderEventFilter--) | Specifies event types for Calendar folder |
| [getCallInfo(String callId)](#getCallInfo-java.lang.String-) | Retrieves phone call information by call id |
| [getContact(ObjectIdentifier contactId)](#getContact-com.aspose.email.ObjectIdentifier-) | Retrieves contact information according to specified identifier. |
| [getContact(ObjectIdentifier contactId, int options)](#getContact-com.aspose.email.ObjectIdentifier-int-) | Retrieves contact information according to specified identifier. |
| [getContact(String contactId)](#getContact-java.lang.String-) | Retrieves contact information according to specified identifier. |
| [getContact(String contactId, int options)](#getContact-java.lang.String-int-) | Retrieves contact information according to specified identifier. |
| [getContacts(String folder)](#getContacts-java.lang.String-) | Lists contacts located in the specified folder on server |
| [getContacts(String folder, int options)](#getContacts-java.lang.String-int-) | Lists contacts located in the specified folder on server |
| [getContactsFolderEventFilter()](#getContactsFolderEventFilter--) | Specifies event types for Contacts folder |
| [getCurrentCalendarFolderUri()](#getCurrentCalendarFolderUri--) | Gets or sets current calendar folder uri |
| [getDeletedItemsFolderEventFilter()](#getDeletedItemsFolderEventFilter--) | Specifies event types for DeletedItems folder |
| [getDraftsFolderEventFilter()](#getDraftsFolderEventFilter--) | Specifies event types for Drafts folder |
| [getEnableDecompression()](#getEnableDecompression--) | Gets or sets a value that indicates whether decompression is enabled |
| [getExchangeType()](#getExchangeType--) | Gets the information about the current version of MS Exchange. |
| [getFolderInfo(String folder)](#getFolderInfo-java.lang.String-) | Gets the folder information |
| [getFolderPermissions(String folderUrl)](#getFolderPermissions-java.lang.String-) | Gets the folder permissions. |
| [getHeaders()](#getHeaders--) | Gets array of name value pairs wich are added to WebHeaderCollection in EWS request. |
| [getInboxFolderEventFilter()](#getInboxFolderEventFilter--) | Specifies event types for Inbox folder |
| [getInboxRules()](#getInboxRules--) | Gets inbox rules |
| [getInboxRules(String mailbox)](#getInboxRules-java.lang.String-) | Gets inbox rules |
| [getJournalFolderEventFilter()](#getJournalFolderEventFilter--) | Specifies event types for Journal folder |
| [getLogFileName()](#getLogFileName--) | Gets or sets log file name |
| [getMailTips(GetMailTipsOptions options)](#getMailTips-com.aspose.email.GetMailTipsOptions-) | Gets mail tips |
| [getMailboxInfo()](#getMailboxInfo--) | Gets the mailbox info. |
| [getMailboxInfo(String mailbox)](#getMailboxInfo-java.lang.String-) | Gets the mailbox information |
| [getMailboxSize()](#getMailboxSize--) | Gets the size of the mailbox. |
| [getMailboxSize(String mailbox)](#getMailboxSize-java.lang.String-) | Gets the size of the mailbox |
| [getMailboxSizeEx(String folderUri)](#getMailboxSizeEx-java.lang.String-) | Gets the size of the mailbox Please, note this operation is performed recursively for all subfolders and make take some time |
| [getMailboxUri()](#getMailboxUri--) | Gets or sets the mailbox uri. |
| [getMailboxes()](#getMailboxes--) | Lists mailboxes having smtp addresses. |
| [getMessageTrackingReport(GetMessageTrackingReportOptions options)](#getMessageTrackingReport-com.aspose.email.GetMessageTrackingReportOptions-) | Gets message tracking report |
| [getNotesFolderEventFilter()](#getNotesFolderEventFilter--) | Specifies event types for Notes folder |
| [getNotificationTimeout()](#getNotificationTimeout--) | Defines timeout for server notifications |
| [getNotificationsCheckInterval()](#getNotificationsCheckInterval--) | Defines interval for notification check |
| [getOutboxFolderEventFilter()](#getOutboxFolderEventFilter--) | Specifies event types for Outbox folder |
| [getReconnectCount()](#getReconnectCount--) | Gets or sets the number of reconnect attempts at connection breaks. |
| [getReturnClientRequestId()](#getReturnClientRequestId--) | Gets or sets a flag to indicate whether the client requires the server side to return the request id. |
| [getRootFolderEventFilter()](#getRootFolderEventFilter--) | Specifies event types for Root folder |
| [getSentItemsFolderEventFilter()](#getSentItemsFolderEventFilter--) | Specifies event types for SentItems folder |
| [getServerTimeZoneIds()](#getServerTimeZoneIds--) | The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server. |
| [getServerTimeZoneIds(Iterable<String> timeZoneIds)](#getServerTimeZoneIds-java.lang.Iterable-java.lang.String--) | The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server. |
| [getServerTimeZoneIds(String[] timeZoneIds)](#getServerTimeZoneIds-java.lang.String...-) | The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server. |
| [getServerVersion()](#getServerVersion--) | Gets the information about the current version of MS Exchange. |
| [getTasksFolderEventFilter()](#getTasksFolderEventFilter--) | Specifies event types for Tasks folder |
| [getTimezoneId()](#getTimezoneId--) | Gets or sets timezone id |
| [getUMConfiguration()](#getUMConfiguration--) | Retrieves unified messaging configuration |
| [getUseDateInLogFileName()](#getUseDateInLogFileName--) | Gets or sets value which indicates if date has to be used in log file name. |
| [getUseSlashAsFolderSeparator()](#getUseSlashAsFolderSeparator--) | Gets or sets value that determines whether the slash '/' is used as folder separator. |
| [getUserConfiguration(UserConfigurationName userConfigurationName)](#getUserConfiguration-com.aspose.email.UserConfigurationName-) | Gets the specified user configuration |
| [getVersionInfo()](#getVersionInfo--) | Returns exchange server version info |
| [impersonateUser(int valueType, String value)](#impersonateUser-int-java.lang.String-) | Impersonates the user. |
| [listAppointments()](#listAppointments--) | Retrieves list of appointments for default calendar folder |
| [listAppointments(boolean recursive)](#listAppointments-boolean-) | Retrieves list of appointments for default calendar folder |
| [listAppointments(MailQuery query)](#listAppointments-com.aspose.email.MailQuery-) | Retrieves list of appointments for default calendar folder |
| [listAppointments(MailQuery query, boolean recursive)](#listAppointments-com.aspose.email.MailQuery-boolean-) | Retrieves list of appointments for default calendar folder |
| [listAppointments(String folderUri)](#listAppointments-java.lang.String-) | Retrieves list of appointments for specified calendar folder |
| [listAppointments(String folderUri, boolean recursive)](#listAppointments-java.lang.String-boolean-) | Retrieves list of appointments for specified calendar folder |
| [listAppointments(String folderUri, MailQuery query)](#listAppointments-java.lang.String-com.aspose.email.MailQuery-) | Retrieves list of appointments for specified calendar folder |
| [listAppointments(String folderUri, MailQuery query, boolean recursive)](#listAppointments-java.lang.String-com.aspose.email.MailQuery-boolean-) | Retrieves list of appointments for specified calendar folder |
| [listAppointmentsByPage(MailQuery query, int itemsPerPage)](#listAppointmentsByPage-com.aspose.email.MailQuery-int-) | Retrieves page with appointments for calendar folder |
| [listAppointmentsByPage(MailQuery query, int itemsPerPage, int itemOffset)](#listAppointmentsByPage-com.aspose.email.MailQuery-int-int-) | Retrieves page with appointments for calendar folder |
| [listAppointmentsByPage(int itemsPerPage)](#listAppointmentsByPage-int-) | Retrieves page with appointments for calendar folder |
| [listAppointmentsByPage(int itemsPerPage, int itemOffset)](#listAppointmentsByPage-int-int-) | Retrieves page with appointments for calendar folder |
| [listAppointmentsByPage(String folderUri, MailQuery query, int itemsPerPage)](#listAppointmentsByPage-java.lang.String-com.aspose.email.MailQuery-int-) | Retrieves page with appointments for specified calendar folder |
| [listAppointmentsByPage(String folderUri, MailQuery query, int itemsPerPage, int itemOffset)](#listAppointmentsByPage-java.lang.String-com.aspose.email.MailQuery-int-int-) | Retrieves page with appointments for specified calendar folder |
| [listAppointmentsByPage(String folderUri, int itemsPerPage)](#listAppointmentsByPage-java.lang.String-int-) | Retrieves page with appointments for specified calendar folder |
| [listAppointmentsByPage(String folderUri, int itemsPerPage, int itemOffset)](#listAppointmentsByPage-java.lang.String-int-int-) | Retrieves page with appointments for specified calendar folder |
| [listContacts(String folderUri)](#listContacts-java.lang.String-) | Lists contacts located in the specified folder on server |
| [listContacts(String folderUri, Iterable<PropertyDescriptor> mapiProperties)](#listContacts-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Lists contacts located in the specified folder on server |
| [listDelegates(String mailbox)](#listDelegates-java.lang.String-) | Lists the users who are granted access on the specified mailbox. |
| [listDistributionLists()](#listDistributionLists--) | List the private Distribution Lists. |
| [listItems(String folder)](#listItems-java.lang.String-) | Retrieve list of item uries in specified folder |
| [listItems(String folder, MailQuery query)](#listItems-java.lang.String-com.aspose.email.MailQuery-) | Retrieve list of item uries in specified folder |
| [listItems(String folder, MailQuery query, boolean recursive)](#listItems-java.lang.String-com.aspose.email.MailQuery-boolean-) | Retrieve list of item uries in specified folder |
| [listItems(String mailbox, String folder)](#listItems-java.lang.String-java.lang.String-) | Retrieve list of item uries in specified folder |
| [listItems(String mailbox, String folder, MailQuery query)](#listItems-java.lang.String-java.lang.String-com.aspose.email.MailQuery-) | Retrieve list of item uries in specified folder |
| [listItems(String mailbox, String folder, MailQuery query, boolean recursive)](#listItems-java.lang.String-java.lang.String-com.aspose.email.MailQuery-boolean-) | Retrieve list of item uries in specified folder |
| [listMailboxes()](#listMailboxes--) | Lists mailboxes. |
| [listMailboxes(String filter)](#listMailboxes-java.lang.String-) | Please pay your attention, this overridden method works with Exchange Server 2013 and higher. |
| [listMessages()](#listMessages--) | List the messages in the inbox folder. |
| [listMessages(Iterable<String> iDs)](#listMessages-java.lang.Iterable-java.lang.String--) | List the messages in the specified folder. |
| [listMessages(String folder)](#listMessages-java.lang.String-) | Lists the messages. |
| [listMessages(String folder, boolean recursive)](#listMessages-java.lang.String-boolean-) | List the messages in the specified folder |
| [listMessages(String folder, MailQuery query)](#listMessages-java.lang.String-com.aspose.email.MailQuery-) | List the messages in the specified folder. |
| [listMessages(String folder, MailQuery query, boolean recursive)](#listMessages-java.lang.String-com.aspose.email.MailQuery-boolean-) | List the messages in the specified folder. |
| [listMessages(String folder, int maxNumberOfMessages)](#listMessages-java.lang.String-int-) | Lists the messages. |
| [listMessages(String folder, int maxNumberOfMessages, MailQuery query)](#listMessages-java.lang.String-int-com.aspose.email.MailQuery-) | List the messages in the specified folder. |
| [listMessages(String folder, int maxNumberOfMessages, MailQuery query, boolean recursive)](#listMessages-java.lang.String-int-com.aspose.email.MailQuery-boolean-) | List the messages in the specified folder. |
| [listMessages(String mailbox, String folder, boolean recursive)](#listMessages-java.lang.String-java.lang.String-boolean-) | List the messages in the specified folder |
| [listMessages(String mailbox, String folder, MailQuery query)](#listMessages-java.lang.String-java.lang.String-com.aspose.email.MailQuery-) | List the messages in the specified folder. |
| [listMessagesByMaxNumberOfMessages(String folder, int maxNumberOfMessages)](#listMessagesByMaxNumberOfMessages-java.lang.String-int-) | Lists the messages. |
| [listMessagesByOption(String folder, int options)](#listMessagesByOption-java.lang.String-int-) | Lists the messages. |
| [listMessagesByOption(String folder, int maxNumberOfMessages, int options)](#listMessagesByOption-java.lang.String-int-int-) | Lists the messages. |
| [listMessagesByPage(String folder, MailQuery query, int itemsPerPage)](#listMessagesByPage-java.lang.String-com.aspose.email.MailQuery-int-) | List the messages in the specified folder. |
| [listMessagesByPage(String folder, MailQuery query, int itemsPerPage, int offset)](#listMessagesByPage-java.lang.String-com.aspose.email.MailQuery-int-int-) | List the messages in the specified folder. |
| [listMessagesByPage(String folder, PageInfo pageInfo)](#listMessagesByPage-java.lang.String-com.aspose.email.PageInfo-) | List the messages in the specified folder. |
| [listMessagesByPage(String folder, PageInfo pageInfo, int options)](#listMessagesByPage-java.lang.String-com.aspose.email.PageInfo-int-) | List the messages in the specified folder. |
| [listMessagesByPage(String folder, int itemsPerPage)](#listMessagesByPage-java.lang.String-int-) | List the messages in the specified folder. |
| [listMessagesByPage(String folder, int itemsPerPage, int offset)](#listMessagesByPage-java.lang.String-int-int-) | List the messages in the specified folder. |
| [listMessagesByPage(String folder, int itemsPerPage, int pageOffset, int options)](#listMessagesByPage-java.lang.String-int-int-int-) | List the messages in the specified folder. |
| [listMessagesByPropertyDescriptor(String folder, int options, Iterable<PropertyDescriptor> extendedProperties)](#listMessagesByPropertyDescriptor-java.lang.String-int-java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | List the messages in the specified folder |
| [listMessagesFromPublicFolder(ExchangeFolderInfo folder)](#listMessagesFromPublicFolder-com.aspose.email.ExchangeFolderInfo-) | Get collection of messages from public folder |
| [listMessagesFromPublicFolder(String folderUri)](#listMessagesFromPublicFolder-java.lang.String-) | Get collection of messages from public folder |
| [listPublicFolders()](#listPublicFolders--) | Gets collection of public folders from root public folder |
| [listSubFolders(ExchangeFolderInfo parentFolder)](#listSubFolders-com.aspose.email.ExchangeFolderInfo-) | Gets collection of child public folders from parent |
| [listSubFolders(String parentFolderUri)](#listSubFolders-java.lang.String-) | Gets collection of child folders from parent |
| [listSubFolders(String mailbox, String parentFolderUri)](#listSubFolders-java.lang.String-java.lang.String-) | Gets collection of child folders from parent |
| [listSubFoldersByPage(String parentFolderUri, PageInfo page)](#listSubFoldersByPage-java.lang.String-com.aspose.email.PageInfo-) | Searches the specified folder in the given parent folder with paging Method supports paging. |
| [listSubFoldersByPage(String parentFolderUri, int itemsPerPage)](#listSubFoldersByPage-java.lang.String-int-) | Searches the specified folder in the given parent folder with paging Method supports paging. |
| [listSubFoldersByPage(String parentFolderUri, int itemsPerPage, int pageOffset)](#listSubFoldersByPage-java.lang.String-int-int-) | Searches the specified folder in the given parent folder with paging Method supports paging. |
| [listTasks()](#listTasks--) | Retrieves lists of exchange tasks for default folder. |
| [listTasks(String folder)](#listTasks-java.lang.String-) | Retrieves lists of exchange tasks. |
| [listTasks(String folder, MailQuery query)](#listTasks-java.lang.String-com.aspose.email.MailQuery-) | Retrieves lists of exchange tasks. |
| [listTasks(String folder, int maxNumberOfItems)](#listTasks-java.lang.String-int-) | Retrieves lists of exchange tasks. |
| [listTasks(String folder, int maxNumberOfItems, MailQuery query)](#listTasks-java.lang.String-int-com.aspose.email.MailQuery-) | Retrieves lists of exchange tasks. |
| [listTasks(String folder, int maxNumberOfItems, MailQuery query, boolean recursive)](#listTasks-java.lang.String-int-com.aspose.email.MailQuery-boolean-) | Retrieves lists of exchange tasks. |
| [loadContactPhoto(ContactPhoto photo)](#loadContactPhoto-com.aspose.email.ContactPhoto-) | Loads contact photo binary data |
| [mailDisablePublicFolder(String folderUri)](#mailDisablePublicFolder-java.lang.String-) | Mail-disable a public folder |
| [mailEnablePublicFolder(String folderUri)](#mailEnablePublicFolder-java.lang.String-) | Mail-enable a public folder |
| [markAllItems(boolean read, boolean suppressReadReceipts, Iterable<String> folderIds)](#markAllItems-boolean-boolean-java.lang.Iterable-java.lang.String--) | Marks all items in specified folders. |
| [markAllItems(boolean read, boolean suppressReadReceipts, String[] folderIds)](#markAllItems-boolean-boolean-java.lang.String...-) | Marks all items in specified folders. |
| [markAllItems(boolean read, String[] folderIds)](#markAllItems-boolean-java.lang.String...-) | Marks all items in specified folders. |
| [markAllItemsAsRead()](#markAllItemsAsRead--) | Marks all items in inbox folder as read without receipts. |
| [markAllItemsAsRead(Iterable<String> folderIds)](#markAllItemsAsRead-java.lang.Iterable-java.lang.String--) | Marks all items in specified folders as read without receipts. |
| [markAllItemsAsRead(String[] folderIds)](#markAllItemsAsRead-java.lang.String...-) | Marks all items in specified folders as read without receipts. |
| [markAllItemsAsUnread()](#markAllItemsAsUnread--) | Marks all items in inbox folder as unread. |
| [markAllItemsAsUnread(Iterable<String> folderIds)](#markAllItemsAsUnread-java.lang.Iterable-java.lang.String--) | Marks all items in specified folders as unread. |
| [markAllItemsAsUnread(String[] folderIds)](#markAllItemsAsUnread-java.lang.String...-) | Marks all items in specified folders as unread. |
| [markAsJunk(boolean isJunk, boolean moveItem, Iterable<String> messageUriEn)](#markAsJunk-boolean-boolean-java.lang.Iterable-java.lang.String--) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [markAsJunk(boolean isJunk, boolean moveItem, Iterable<String> messageUriEn, String[][] movedMessageIds, String[][] failedMessageIds, String[][] errorMessages)](#markAsJunk-boolean-boolean-java.lang.Iterable-java.lang.String--java.lang.String-----java.lang.String-----java.lang.String-----) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [markAsJunk(boolean isJunk, boolean moveItem, String[] messageUriEn)](#markAsJunk-boolean-boolean-java.lang.String...-) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [markAsJunk(boolean isJunk, Iterable<String> messageUriEn)](#markAsJunk-boolean-java.lang.Iterable-java.lang.String--) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [markAsJunk(boolean isJunk, String[] messageUriEn)](#markAsJunk-boolean-java.lang.String...-) | The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender. |
| [moveConversationItems(String conversationId, String destinationFolderId)](#moveConversationItems-java.lang.String-java.lang.String-) | Moves the conversation items into the specified target folder |
| [moveConversationItems(String conversationId, String contextFolderId, String destinationFolderId)](#moveConversationItems-java.lang.String-java.lang.String-java.lang.String-) | Moves the conversation items, which are located in the specified folder, into the specified target folder |
| [moveItem(String itemUri, String destinationFolderUri)](#moveItem-java.lang.String-java.lang.String-) | Moves the item to specified folder |
| [playOnPhone(String messageId, String dialString)](#playOnPhone-java.lang.String-java.lang.String-) | The PlayOnPhone operation initiates an outbound call and plays a message over the telephone. |
| [removeHeader(String name)](#removeHeader-java.lang.String-) | Remove WebHeader from WebHeaderCollection in EWS request. |
| [reply(MailMessage message, ExchangeMessageInfo referencedMessage)](#reply-com.aspose.email.MailMessage-com.aspose.email.ExchangeMessageInfo-) | Reply to the sender's message. |
| [reply(MailMessage message, String referencedUri)](#reply-com.aspose.email.MailMessage-java.lang.String-) | Reply to the sender's message. |
| [replyAll(MailMessage message, ExchangeMessageInfo referencedMessage)](#replyAll-com.aspose.email.MailMessage-com.aspose.email.ExchangeMessageInfo-) | Reply to the sender and all recipients of a message. |
| [resetImpersonation()](#resetImpersonation--) | Makes the impersonation reset. |
| [resetSubscription()](#resetSubscription--) | Reset all subscriptions |
| [resolveContact(String unresolvedEntry)](#resolveContact-java.lang.String-) | Resolves ambiguous mailbox names. |
| [resolveContacts(String unresolvedEntry)](#resolveContacts-java.lang.String-) | Resolves ambiguous mailbox display names. |
| [resolveContacts(String unresolvedEntry, int options)](#resolveContacts-java.lang.String-int-) | Resolves ambiguous e-mail addresses and display names Note: the maximum count of returned contacts is 100. |
| [restore(PersonalStorage pst, RestoreSettings settings)](#restore-com.aspose.email.PersonalStorage-com.aspose.email.RestoreSettings-) | Restores the specified exchange folders from the given personal storage. |
| [saveMessage(String messageUri, OutputStream stream)](#saveMessage-java.lang.String-java.io.OutputStream-) | Saves the message. |
| [saveMessage(String messageUri, String path)](#saveMessage-java.lang.String-java.lang.String-) | Saves the message. |
| [saveMessageInternal(String messageUri, System.IO.Stream stream)](#saveMessageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [send(MailMessage message)](#send-com.aspose.email.MailMessage-) | Sends the specified message. |
| [send(MailMessage message, FollowUpOptions messageOptions)](#send-com.aspose.email.MailMessage-com.aspose.email.FollowUpOptions-) | Sends the message. |
| [send(String from, String to, String subject, String body)](#send-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Sends the specified message |
| [setCalendarFolderEventFilter(int value)](#setCalendarFolderEventFilter-int-) | Specifies event types for Calendar folder |
| [setContactsFolderEventFilter(int value)](#setContactsFolderEventFilter-int-) | Specifies event types for Contacts folder |
| [setConversationReadState(String conversationId, boolean isRead)](#setConversationReadState-java.lang.String-boolean-) | Set read state of the conversation items to the specified value |
| [setConversationReadState(String conversationId, String contextFolderId, boolean isRead)](#setConversationReadState-java.lang.String-java.lang.String-boolean-) | Set read state of the conversation items, which are located in the specified folder, to the specified value |
| [setCurrentCalendarFolderUri(String value)](#setCurrentCalendarFolderUri-java.lang.String-) | Gets or sets current calendar folder uri |
| [setDeletedItemsFolderEventFilter(int value)](#setDeletedItemsFolderEventFilter-int-) | Specifies event types for DeletedItems folder |
| [setDraftsFolderEventFilter(int value)](#setDraftsFolderEventFilter-int-) | Specifies event types for Drafts folder |
| [setEnableDecompression(boolean value)](#setEnableDecompression-boolean-) | Gets or sets a value that indicates whether decompression is enabled |
| [setInboxFolderEventFilter(int value)](#setInboxFolderEventFilter-int-) | Specifies event types for Inbox folder |
| [setJournalFolderEventFilter(int value)](#setJournalFolderEventFilter-int-) | Specifies event types for Journal folder |
| [setLogFileName(String value)](#setLogFileName-java.lang.String-) | Gets or sets log file name |
| [setMailboxUri(String value)](#setMailboxUri-java.lang.String-) | Gets or sets the mailbox uri. |
| [setNotesFolderEventFilter(int value)](#setNotesFolderEventFilter-int-) | Specifies event types for Notes folder |
| [setNotificationTimeout(int value)](#setNotificationTimeout-int-) | Defines timeout for server notifications |
| [setNotificationsCheckInterval(int value)](#setNotificationsCheckInterval-int-) | Defines interval for notification check |
| [setOutboxFolderEventFilter(int value)](#setOutboxFolderEventFilter-int-) | Specifies event types for Outbox folder |
| [setReadFlag(String messageUri)](#setReadFlag-java.lang.String-) | Sets the read flag. |
| [setReadFlag(String messageUri, boolean isRead)](#setReadFlag-java.lang.String-boolean-) | Marks the specifeid message as read. |
| [setReconnectCount(int value)](#setReconnectCount-int-) | Gets or sets the number of reconnect attempts at connection breaks. |
| [setReturnClientRequestId(boolean value)](#setReturnClientRequestId-boolean-) | Gets or sets a flag to indicate whether the client requires the server side to return the request id. |
| [setRootFolderEventFilter(int value)](#setRootFolderEventFilter-int-) | Specifies event types for Root folder |
| [setSentItemsFolderEventFilter(int value)](#setSentItemsFolderEventFilter-int-) | Specifies event types for SentItems folder |
| [setTasksFolderEventFilter(int value)](#setTasksFolderEventFilter-int-) | Specifies event types for Tasks folder |
| [setTimezoneId(String value)](#setTimezoneId-java.lang.String-) | Gets or sets timezone id |
| [setUseDateInLogFileName(boolean value)](#setUseDateInLogFileName-boolean-) | Gets or sets value which indicates if date has to be used in log file name. |
| [setUseSlashAsFolderSeparator(boolean value)](#setUseSlashAsFolderSeparator-boolean-) | Gets or sets value that determines whether the slash '/' is used as folder separator. |
| [syncFolder(SyncState syncState)](#syncFolder-com.aspose.email.SyncState-) | Retrieves changes of the items in a specified folder. |
| [syncFolder(String folderUri)](#syncFolder-java.lang.String-) | Retrieves changes of the items and subfolders in a specified folder. |
| [syncFolder(String folderUri, int syncType)](#syncFolder-java.lang.String-int-) | Retrieves changes of the items and subfolders in a specified folder. |
| [syncFolder(String folderUri, String syncState)](#syncFolder-java.lang.String-java.lang.String-) | Retrieves changes of the items in a specified folder. |
| [syncFolder(String folderUri, String syncState, Iterable<String> ignoreList)](#syncFolder-java.lang.String-java.lang.String-java.lang.Iterable-java.lang.String--) | Retrieves changes of the items in a specified folder. |
| [updateAppointment(Appointment appointment)](#updateAppointment-com.aspose.email.Appointment-) | Updates appointment. |
| [updateAppointment(Appointment appointment, String folderUri)](#updateAppointment-com.aspose.email.Appointment-java.lang.String-) | Updates appointment. |
| [updateAppointment(MapiCalendar appointment)](#updateAppointment-com.aspose.email.MapiCalendar-) | Updates appointment. |
| [updateAppointment(MapiCalendar appointment, String folderUri)](#updateAppointment-com.aspose.email.MapiCalendar-java.lang.String-) | Updates appointment. |
| [updateContact(Contact contact)](#updateContact-com.aspose.email.Contact-) | Updates a contact item in the Exchange store. |
| [updateContact(MapiContact contact)](#updateContact-com.aspose.email.MapiContact-) | Updates a contact item in the Exchange store. |
| [updateDelegate(ExchangeDelegateUser delegateUser, String mailbox)](#updateDelegate-com.aspose.email.ExchangeDelegateUser-java.lang.String-) | Updates the delegate user settings who is granted access on the specified mailbox. |
| [updateDelegates(ExchangeDelegateUserCollection delegateUsers, String mailbox)](#updateDelegates-com.aspose.email.ExchangeDelegateUserCollection-java.lang.String-) | Updates the delegate users settings who are granted access on the specified mailbox. |
| [updateInboxRule(InboxRule rule)](#updateInboxRule-com.aspose.email.InboxRule-) | Updates the specified inbox rule |
| [updateInboxRule(InboxRule rule, String mailbox)](#updateInboxRule-com.aspose.email.InboxRule-java.lang.String-) | Updates the specified inbox rule |
| [updateItems(ExchangeStreamedItem[] items, String parentFolderUri)](#updateItems-com.aspose.email.ExchangeStreamedItem---java.lang.String-) | Updates the specified items in to a mailbox |
| [updateNote(MapiNote note)](#updateNote-com.aspose.email.MapiNote-) | Updates the specified note. |
| [updateNote(String uri, MapiNote note)](#updateNote-java.lang.String-com.aspose.email.MapiNote-) | Updates the specified note. |
| [updateNote(String uri, MapiNote note, Iterable<PropertyDescriptor> additionalProperties)](#updateNote-java.lang.String-com.aspose.email.MapiNote-java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Updates the specified note. |
| [updateSubscription()](#updateSubscription--) | Updates subscriptions |
| [updateTask(ExchangeTask task)](#updateTask-com.aspose.email.ExchangeTask-) | Updates the specified task. |
| [updateTask(ExchangeTask task, int options)](#updateTask-com.aspose.email.ExchangeTask-int-) | Updates the specified task. |
| [updateTask(MapiTask task)](#updateTask-com.aspose.email.MapiTask-) | Updates the specified task. |
| [updateTask(String uri, MapiTask task)](#updateTask-java.lang.String-com.aspose.email.MapiTask-) | Updates the specified task. |
| [updateTask(String uri, MapiTask task, Iterable<PropertyDescriptor> additionalProperties)](#updateTask-java.lang.String-com.aspose.email.MapiTask-java.lang.Iterable-com.aspose.email.PropertyDescriptor--) | Updates the specified task. |
| [updateUserConfiguration(UserConfiguration userConfiguration)](#updateUserConfiguration-com.aspose.email.UserConfiguration-) | Updates the specified user configuration |
### addHeader(String name, String value) {#addHeader-java.lang.String-java.lang.String-}
```
public abstract void addHeader(String name, String value)
```


Adds name and value to WebHeaderCollection in EWS request.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Header name |
| value | java.lang.String | Header value |

### addToDistributionList(ExchangeDistributionList distributionList, MailAddressCollection members) {#addToDistributionList-com.aspose.email.ExchangeDistributionList-com.aspose.email.MailAddressCollection-}
```
public abstract void addToDistributionList(ExchangeDistributionList distributionList, MailAddressCollection members)
```


Appends the members to Distribution List.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| distributionList | [ExchangeDistributionList](../../com.aspose.email/exchangedistributionlist) | A [ExchangeDistributionList](../../com.aspose.email/exchangedistributionlist) containing information about Distribution List to update. |
| members | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | A [MailAddressCollection](../../com.aspose.email/mailaddresscollection) containing the mail addresses to add. |

### appendMapiMessages(String folderUri, Iterable<MapiMessage> messages) {#appendMapiMessages-java.lang.String-java.lang.Iterable-com.aspose.email.MapiMessage--}
```
public abstract String[] appendMapiMessages(String folderUri, Iterable<MapiMessage> messages)
```


Uploads the mapi messages to the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder URI to which message is uploaded |
| messages | java.lang.Iterable<com.aspose.email.MapiMessage> | A messages to upload |

**Returns:**
java.lang.String[] - List of uri of created messages
### appendMessage(MailMessage message) {#appendMessage-com.aspose.email.MailMessage-}
```
public abstract String appendMessage(MailMessage message)
```


Uploads the mail message to the Inbox folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | A message to upload |

**Returns:**
java.lang.String - An uri of created message
### appendMessage(MapiMessage mapiMessage) {#appendMessage-com.aspose.email.MapiMessage-}
```
public abstract String appendMessage(MapiMessage mapiMessage)
```


Uploads the mail message to the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mapiMessage | [MapiMessage](../../com.aspose.email/mapimessage) | A message to upload |

**Returns:**
java.lang.String - An uri of created message
### appendMessage(MapiMessage mapiMessage, boolean markAsSent) {#appendMessage-com.aspose.email.MapiMessage-boolean-}
```
public abstract String appendMessage(MapiMessage mapiMessage, boolean markAsSent)
```


Uploads the mail message to the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mapiMessage | [MapiMessage](../../com.aspose.email/mapimessage) | A message to upload |
| markAsSent | boolean | A value indicating whether the message should be appended as a sent message or a draft. |

**Returns:**
java.lang.String - An uri of created message
### appendMessage(String folderUri, MailMessage message) {#appendMessage-java.lang.String-com.aspose.email.MailMessage-}
```
public abstract String appendMessage(String folderUri, MailMessage message)
```


Uploads the mail message to the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder URI to which message is uploaded |
| message | [MailMessage](../../com.aspose.email/mailmessage) | A message to upload |

**Returns:**
java.lang.String - An uri of created message
### appendMessage(String folderUri, MailMessage message, boolean markAsSent) {#appendMessage-java.lang.String-com.aspose.email.MailMessage-boolean-}
```
public abstract String appendMessage(String folderUri, MailMessage message, boolean markAsSent)
```


Uploads the mail message to the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder URI to which message is uploaded |
| message | [MailMessage](../../com.aspose.email/mailmessage) | A message to upload |
| markAsSent | boolean | A value indicating whether the message should be appended as a sent message or a draft. |

**Returns:**
java.lang.String - An uri of created message
### appendMessage(String folder, MapiMessage mapiMessage, boolean markAsSent) {#appendMessage-java.lang.String-com.aspose.email.MapiMessage-boolean-}
```
public abstract String appendMessage(String folder, MapiMessage mapiMessage, boolean markAsSent)
```


Uploads the mail message to the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to which message is uploaded |
| mapiMessage | [MapiMessage](../../com.aspose.email/mapimessage) | A message to upload |
| markAsSent | boolean | A value indicating whether the message should be appended as a sent message or a draft. |

**Returns:**
java.lang.String - An uri of created message
### appendMessages(MailMessage[] messages) {#appendMessages-com.aspose.email.MailMessage...-}
```
public abstract String[] appendMessages(MailMessage[] messages)
```


Uploads the mail message to the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | [MailMessage\[\]](../../com.aspose.email/mailmessage) | A messages to upload |

**Returns:**
java.lang.String[] - List of uri of created messages
### appendMessages(Iterable<MailMessage> messages) {#appendMessages-java.lang.Iterable-com.aspose.email.MailMessage--}
```
public abstract String[] appendMessages(Iterable<MailMessage> messages)
```


Uploads the mail message to the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | A messages to upload |

**Returns:**
java.lang.String[] - List of uri of created messages
### appendMessages(String folderUri, MailMessage[] messages) {#appendMessages-java.lang.String-com.aspose.email.MailMessage...-}
```
public abstract String[] appendMessages(String folderUri, MailMessage[] messages)
```


Uploads the mail message to the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder URI to which message is uploaded |
| messages | [MailMessage\[\]](../../com.aspose.email/mailmessage) | A messages to upload |

**Returns:**
java.lang.String[] - List of uri of created messages
### appendMessages(String folderUri, Iterable<MailMessage> messages) {#appendMessages-java.lang.String-java.lang.Iterable-com.aspose.email.MailMessage--}
```
public abstract String[] appendMessages(String folderUri, Iterable<MailMessage> messages)
```


Uploads the mail message to the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder URI to which message is uploaded |
| messages | java.lang.Iterable<com.aspose.email.MailMessage> | A messages to upload |

**Returns:**
java.lang.String[] - List of uri of created messages
### archiveItem(String sourceFolderUri, Appointment appointment) {#archiveItem-java.lang.String-com.aspose.email.Appointment-}
```
public abstract void archiveItem(String sourceFolderUri, Appointment appointment)
```


The ArchiveItem operation moves an item into the mailbox user's archive mailbox.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolderUri | java.lang.String |  |
| appointment | [Appointment](../../com.aspose.email/appointment) | Item which will be archived |

### archiveItem(String sourceFolderUri, ExchangeTask task) {#archiveItem-java.lang.String-com.aspose.email.ExchangeTask-}
```
public abstract void archiveItem(String sourceFolderUri, ExchangeTask task)
```


The ArchiveItem operation moves an item into the mailbox user's archive mailbox.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolderUri | java.lang.String |  |
| task | [ExchangeTask](../../com.aspose.email/exchangetask) | Item which will be archived |

### archiveItem(String sourceFolderUri, MapiMessageItemBase item) {#archiveItem-java.lang.String-com.aspose.email.MapiMessageItemBase-}
```
public abstract void archiveItem(String sourceFolderUri, MapiMessageItemBase item)
```


The ArchiveItem operation moves an item into the mailbox user's archive mailbox.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolderUri | java.lang.String |  |
| item | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | Item which will be archived |

### archiveItem(String sourceFolderUri, String uniqueId) {#archiveItem-java.lang.String-java.lang.String-}
```
public abstract void archiveItem(String sourceFolderUri, String uniqueId)
```


The ArchiveItem operation moves an item into the mailbox user's archive mailbox.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolderUri | java.lang.String |  |
| uniqueId | java.lang.String | Item id |

### backup(ExchangeFolderInfoCollection folders, OutputStream stream, int options) {#backup-com.aspose.email.ExchangeFolderInfoCollection-java.io.OutputStream-int-}
```
public abstract void backup(ExchangeFolderInfoCollection folders, OutputStream stream, int options)
```


Backups the content of the specified folders

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folders | [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) | A folders to backup |
| stream | java.io.OutputStream | A stream to write into |
| options | int | A backup options |

### backup(ExchangeFolderInfoCollection folders, String fileName, int options) {#backup-com.aspose.email.ExchangeFolderInfoCollection-java.lang.String-int-}
```
public abstract void backup(ExchangeFolderInfoCollection folders, String fileName, int options)
```


Backups the content of the specified folders

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folders | [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) | A folders to backup |
| fileName | java.lang.String | A path to the presonal storage file |
| options | int | A backup options |

### cancelAppointment(Appointment appointment) {#cancelAppointment-com.aspose.email.Appointment-}
```
public abstract void cancelAppointment(Appointment appointment)
```


Cancels appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [Appointment](../../com.aspose.email/appointment) | Calendar appointment. |

### cancelAppointment(Appointment appointment, String folderUri) {#cancelAppointment-com.aspose.email.Appointment-java.lang.String-}
```
public abstract void cancelAppointment(Appointment appointment, String folderUri)
```


Cancels appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [Appointment](../../com.aspose.email/appointment) | Calendar appointment. |
| folderUri | java.lang.String | An uri of appointments parent folder. |

### cancelAppointment(MapiCalendar appointment) {#cancelAppointment-com.aspose.email.MapiCalendar-}
```
public abstract void cancelAppointment(MapiCalendar appointment)
```


Cancels appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [MapiCalendar](../../com.aspose.email/mapicalendar) | Calendar appointment. |

### cancelAppointment(MapiCalendar appointment, String folderUri) {#cancelAppointment-com.aspose.email.MapiCalendar-java.lang.String-}
```
public abstract void cancelAppointment(MapiCalendar appointment, String folderUri)
```


Cancels appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [MapiCalendar](../../com.aspose.email/mapicalendar) | Calendar appointment. |
| folderUri | java.lang.String | An uri of appointments parent folder. |

### cancelAppointment(String uniqueId) {#cancelAppointment-java.lang.String-}
```
public abstract void cancelAppointment(String uniqueId)
```


Cancels an exiting meeting on an organizers calendar

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | Unique identifier |

### cancelAppointment(String uniqueId, String folderUri) {#cancelAppointment-java.lang.String-java.lang.String-}
```
public abstract void cancelAppointment(String uniqueId, String folderUri)
```


Cancels an exiting meeting on an organizers calendar

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | java.lang.String | Unique identifier |
| folderUri | java.lang.String | An uri of appointments parent folder. |

### checkUserAvailability(System.Collections.Specialized.StringCollection users, DateRange timeWindow) {#checkUserAvailability-com.aspose.ms.System.Collections.Specialized.StringCollection-com.aspose.email.DateRange-}
```
public abstract ExchangeUserAvailabilityCollection checkUserAvailability(System.Collections.Specialized.StringCollection users, DateRange timeWindow)
```


Checks users availability within the specified time window.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| users | com.aspose.ms.System.Collections.Specialized.StringCollection | An users smtp addresses. |
| timeWindow | [DateRange](../../com.aspose.email/daterange) | A time span for the queried user's availability. |

**Returns:**
[ExchangeUserAvailabilityCollection](../../com.aspose.email/exchangeuseravailabilitycollection) - [ExchangeUserAvailabilityCollection](../../com.aspose.email/exchangeuseravailabilitycollection) containing the users availability informaiton.
### checkUserAvailability(String user, DateRange timeWindow) {#checkUserAvailability-java.lang.String-com.aspose.email.DateRange-}
```
public abstract ExchangeUserAvailability checkUserAvailability(String user, DateRange timeWindow)
```


Checks user availability within the specified time window.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| user | java.lang.String | An user smtp address. |
| timeWindow | [DateRange](../../com.aspose.email/daterange) | A time span for the queried user's availability. |

**Returns:**
[ExchangeUserAvailability](../../com.aspose.email/exchangeuseravailability) - [ExchangeUserAvailability](../../com.aspose.email/exchangeuseravailability) containing user availability information.
### closeAccess(ExchangeDelegateUser delegateUser, String mailbox) {#closeAccess-com.aspose.email.ExchangeDelegateUser-java.lang.String-}
```
public abstract void closeAccess(ExchangeDelegateUser delegateUser, String mailbox)
```


Closes access on the specified mailbox for the specified user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegateUser | [ExchangeDelegateUser](../../com.aspose.email/exchangedelegateuser) | A delegate user. |
| mailbox | java.lang.String | A mailbox. |

### closeAccess(ExchangeDelegateUserCollection delegateUsers, String mailbox) {#closeAccess-com.aspose.email.ExchangeDelegateUserCollection-java.lang.String-}
```
public abstract void closeAccess(ExchangeDelegateUserCollection delegateUsers, String mailbox)
```


Closes access on the specified mailbox for the specified user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegateUsers | [ExchangeDelegateUserCollection](../../com.aspose.email/exchangedelegateusercollection) | A delegate users. |
| mailbox | java.lang.String | A mailbox. |

### closeAccess(ExchangeFolderUserInfo userInfo, String mailbox) {#closeAccess-com.aspose.email.ExchangeFolderUserInfo-java.lang.String-}
```
public abstract void closeAccess(ExchangeFolderUserInfo userInfo, String mailbox)
```


Closes access on the specified mailbox for the specified user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userInfo | [ExchangeFolderUserInfo](../../com.aspose.email/exchangefolderuserinfo) | A user information. |
| mailbox | java.lang.String | A mailbox. |

### closeAccess(String delegateSmtpAddress, String mailbox) {#closeAccess-java.lang.String-java.lang.String-}
```
public abstract void closeAccess(String delegateSmtpAddress, String mailbox)
```


Closes access on the specified mailbox for the specified user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegateSmtpAddress | java.lang.String | A primary smtp address of delegate user. |
| mailbox | java.lang.String | A mailbox. |

### copyConversationItems(String conversationId, String destinationFolderId) {#copyConversationItems-java.lang.String-java.lang.String-}
```
public abstract void copyConversationItems(String conversationId, String destinationFolderId)
```


Copies the conversation items into the specified target folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | java.lang.String | Id of conversation to copy |
| destinationFolderId | java.lang.String | Id of folder into which copy items |

### copyConversationItems(String conversationId, String contextFolderId, String destinationFolderId) {#copyConversationItems-java.lang.String-java.lang.String-java.lang.String-}
```
public abstract void copyConversationItems(String conversationId, String contextFolderId, String destinationFolderId)
```


Copies the conversation items, which are located in the specified folder, into the specified target folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | java.lang.String | Id of conversation to copy |
| contextFolderId | java.lang.String | Id of folder in which conversation items are located. Note: If it's set to null(or empty), all conversation items will be copied |
| destinationFolderId | java.lang.String | Id of folder into which copy items |

### copyItem(String itemUri, String destinationFolderUri) {#copyItem-java.lang.String-java.lang.String-}
```
public abstract String copyItem(String itemUri, String destinationFolderUri)
```


Copies the item to specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| itemUri | java.lang.String | The item URI |
| destinationFolderUri | java.lang.String | The destination folder URI |

**Returns:**
java.lang.String - An uri of the copied message
### createAppointment(Appointment appointment) {#createAppointment-com.aspose.email.Appointment-}
```
public abstract String createAppointment(Appointment appointment)
```


Creates appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [Appointment](../../com.aspose.email/appointment) | Calendar appointment. |

**Returns:**
java.lang.String - Returns appointment UID
### createAppointment(Appointment appointment, String folderUri) {#createAppointment-com.aspose.email.Appointment-java.lang.String-}
```
public abstract String createAppointment(Appointment appointment, String folderUri)
```


Creates appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [Appointment](../../com.aspose.email/appointment) | Calendar appointment. |
| folderUri | java.lang.String | An uri of appointments parent folder. |

**Returns:**
java.lang.String - Returns appointment UID
### createAppointment(MapiCalendar appointment) {#createAppointment-com.aspose.email.MapiCalendar-}
```
public abstract String createAppointment(MapiCalendar appointment)
```


Creates appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [MapiCalendar](../../com.aspose.email/mapicalendar) | Calendar appointment. |

**Returns:**
java.lang.String - Returns appointment UID
### createAppointment(MapiCalendar appointment, String folderUri) {#createAppointment-com.aspose.email.MapiCalendar-java.lang.String-}
```
public abstract String createAppointment(MapiCalendar appointment, String folderUri)
```


Creates appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [MapiCalendar](../../com.aspose.email/mapicalendar) | Calendar appointment. |
| folderUri | java.lang.String | An uri of appointments parent folder. |

**Returns:**
java.lang.String - Returns PidLidGlobalObjectId as base64 string
### createAppointment(MapiCalendar appointment, String folderUri, boolean suppressInvitations) {#createAppointment-com.aspose.email.MapiCalendar-java.lang.String-boolean-}
```
public abstract String createAppointment(MapiCalendar appointment, String folderUri, boolean suppressInvitations)
```


Creates appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [MapiCalendar](../../com.aspose.email/mapicalendar) | Calendar appointment. |
| folderUri | java.lang.String | An uri of appointments parent folder. |
| suppressInvitations | boolean | If true, invitations won't be sent to attendees. |

**Returns:**
java.lang.String - Returns PidLidGlobalObjectId as base64 string
### createCalendarSharingInvitationMessage(String recipient) {#createCalendarSharingInvitationMessage-java.lang.String-}
```
public abstract MapiMessage createCalendarSharingInvitationMessage(String recipient)
```


Create calendar sharing invitation message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recipient | java.lang.String | A recipient's address. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A [MapiMessage](../../com.aspose.email/mapimessage) that represents sharing invitation message.
### createContact(Contact contact) {#createContact-com.aspose.email.Contact-}
```
public abstract String createContact(Contact contact)
```


Creates a contact item in the Exchange store.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contact | [Contact](../../com.aspose.email/contact) | Contact item |

**Returns:**
java.lang.String - The contact Uri
### createContact(MapiContact contact) {#createContact-com.aspose.email.MapiContact-}
```
public abstract String createContact(MapiContact contact)
```


Creates a contact item in the Exchange store.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contact | [MapiContact](../../com.aspose.email/mapicontact) | Contact item |

**Returns:**
java.lang.String - The contact Uri
### createContact(String folderUri, Contact contact) {#createContact-java.lang.String-com.aspose.email.Contact-}
```
public abstract String createContact(String folderUri, Contact contact)
```


Creates a contact item in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | Folder uri |
| contact | [Contact](../../com.aspose.email/contact) | Contact item |

**Returns:**
java.lang.String - The contact Uri
### createContact(String folderUri, MapiContact contact) {#createContact-java.lang.String-com.aspose.email.MapiContact-}
```
public abstract String createContact(String folderUri, MapiContact contact)
```


Creates a contact item in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | Folder uri |
| contact | [MapiContact](../../com.aspose.email/mapicontact) | Contact item |

**Returns:**
java.lang.String - The contact Uri
### createDistributionList(ExchangeDistributionList distributionList, MailAddressCollection members) {#createDistributionList-com.aspose.email.ExchangeDistributionList-com.aspose.email.MailAddressCollection-}
```
public abstract String createDistributionList(ExchangeDistributionList distributionList, MailAddressCollection members)
```


Creates the private Distribution List.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| distributionList | [ExchangeDistributionList](../../com.aspose.email/exchangedistributionlist) | A [ExchangeDistributionList](../../com.aspose.email/exchangedistributionlist) containing information about Distribution List to create. |
| members | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | A [MailAddressCollection](../../com.aspose.email/mailaddresscollection) containing the Distribution List mail addresses to create. |

**Returns:**
java.lang.String - A string containing the Distribution List Id.
### createFolder(String name) {#createFolder-java.lang.String-}
```
public abstract ExchangeFolderInfo createFolder(String name)
```


Creates new folder in the root folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of new folder |

**Returns:**
[ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) - Returns folder information
### createFolder(String name, int folderType) {#createFolder-java.lang.String-int-}
```
public abstract ExchangeFolderInfo createFolder(String name, int folderType)
```


Creates new folder in the root folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of new folder |
| folderType | int | Type of folder |

**Returns:**
[ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) - Returns folder information
### createFolder(String parentFolderUri, String name) {#createFolder-java.lang.String-java.lang.String-}
```
public abstract ExchangeFolderInfo createFolder(String parentFolderUri, String name)
```


Creates the new folder with the specified name in the specified parent folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | An uri of parent folder. |
| name | java.lang.String | A name of folder to be created. |

**Returns:**
[ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo)
### createFolder(String parentFolderUri, String name, ExchangeFolderPermissionCollection permissions) {#createFolder-java.lang.String-java.lang.String-com.aspose.email.ExchangeFolderPermissionCollection-}
```
public abstract ExchangeFolderInfo createFolder(String parentFolderUri, String name, ExchangeFolderPermissionCollection permissions)
```


Creates the new folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | The URI of parent folder |
| name | java.lang.String | The name of new folder |
| permissions | [ExchangeFolderPermissionCollection](../../com.aspose.email/exchangefolderpermissioncollection) | A permission on new folder |

**Returns:**
[ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) - Returns folder information
### createFolder(String parentFolderUri, String name, ExchangeFolderPermissionCollection permissions, String folderClass) {#createFolder-java.lang.String-java.lang.String-com.aspose.email.ExchangeFolderPermissionCollection-java.lang.String-}
```
public abstract ExchangeFolderInfo createFolder(String parentFolderUri, String name, ExchangeFolderPermissionCollection permissions, String folderClass)
```


Creates the new folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | The URI of parent folder |
| name | java.lang.String | The name of new folder |
| permissions | [ExchangeFolderPermissionCollection](../../com.aspose.email/exchangefolderpermissioncollection) | A permission on new folder |
| folderClass | java.lang.String | The class of new folder |

**Returns:**
[ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) - Returns folder information
### createFolder(String parentFolderUri, String name, int folderType) {#createFolder-java.lang.String-java.lang.String-int-}
```
public abstract ExchangeFolderInfo createFolder(String parentFolderUri, String name, int folderType)
```


Creates the new folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | The URI of parent folder |
| name | java.lang.String | The name of new folder |
| folderType | int | Type of folder |

**Returns:**
[ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) - Returns folder information
### createInboxRule(InboxRule rule) {#createInboxRule-com.aspose.email.InboxRule-}
```
public abstract void createInboxRule(InboxRule rule)
```


Creates the specified inbox rule

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rule | [InboxRule](../../com.aspose.email/inboxrule) | A inbox rule to create |

### createInboxRule(InboxRule rule, String mailbox) {#createInboxRule-com.aspose.email.InboxRule-java.lang.String-}
```
public abstract void createInboxRule(InboxRule rule, String mailbox)
```


Creates the specified inbox rule

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rule | [InboxRule](../../com.aspose.email/inboxrule) | A inbox rule to create |
| mailbox | java.lang.String | A mailbox to create rule for. Note: if it is set to  null  or  empty , the rule will be created in the default mailbox |

### createItem(MapiMessageItemBase item) {#createItem-com.aspose.email.MapiMessageItemBase-}
```
public abstract String createItem(MapiMessageItemBase item)
```


Creates the given item in the default item folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | An item to create. |

**Returns:**
java.lang.String - The item Uri
### createItem(String folderUri, MapiMessageItemBase item) {#createItem-java.lang.String-com.aspose.email.MapiMessageItemBase-}
```
public abstract String createItem(String folderUri, MapiMessageItemBase item)
```


Creates the given item in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder Uri where item should be created. |
| item | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | An item to create. |

**Returns:**
java.lang.String - The item Uri
### createItems(ExchangeStreamedItem[] items, String parentFolderUri) {#createItems-com.aspose.email.ExchangeStreamedItem---java.lang.String-}
```
public abstract ExchangeUploadItemResult[] createItems(ExchangeStreamedItem[] items, String parentFolderUri)
```


Creates the specified items in the speciifed folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| items | [ExchangeStreamedItem\[\]](../../com.aspose.email/exchangestreameditem) | An items to be uploaded |
| parentFolderUri | java.lang.String | Specifies the folder in which to place the items |

**Returns:**
com.aspose.email.ExchangeUploadItemResult[] - An array of [ExchangeUploadItemResult](../../com.aspose.email/exchangeuploaditemresult)
### createNote(MapiNote note) {#createNote-com.aspose.email.MapiNote-}
```
public abstract String createNote(MapiNote note)
```


Creates the given note in the default note folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| note | [MapiNote](../../com.aspose.email/mapinote) | A note to create. |

**Returns:**
java.lang.String - Note uri.
### createNote(String folder, MapiNote note) {#createNote-java.lang.String-com.aspose.email.MapiNote-}
```
public abstract String createNote(String folder, MapiNote note)
```


Creates the given note in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder where note should be created. |
| note | [MapiNote](../../com.aspose.email/mapinote) | A note to create. |

**Returns:**
java.lang.String - Note uri.
### createPublicFolder(String name, ExchangeFolderPermissionCollection permissions) {#createPublicFolder-java.lang.String-com.aspose.email.ExchangeFolderPermissionCollection-}
```
public abstract ExchangeFolderInfo createPublicFolder(String name, ExchangeFolderPermissionCollection permissions)
```


Creates the specified public folder in the root public folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | A name of new folder |
| permissions | [ExchangeFolderPermissionCollection](../../com.aspose.email/exchangefolderpermissioncollection) | A permission on new folder |

**Returns:**
[ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) - Returns folder information
### createPublicFolder(String name, ExchangeFolderPermissionCollection permissions, int folderType) {#createPublicFolder-java.lang.String-com.aspose.email.ExchangeFolderPermissionCollection-int-}
```
public abstract ExchangeFolderInfo createPublicFolder(String name, ExchangeFolderPermissionCollection permissions, int folderType)
```


Creates the specified public folder in the root public folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | A name of new folder |
| permissions | [ExchangeFolderPermissionCollection](../../com.aspose.email/exchangefolderpermissioncollection) | A permission on new folder |
| folderType | int | Type of folder |

**Returns:**
[ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) - Returns folder information
### createPublicFolder(String parentFolderUri, String name, ExchangeFolderPermissionCollection permissions) {#createPublicFolder-java.lang.String-java.lang.String-com.aspose.email.ExchangeFolderPermissionCollection-}
```
public abstract ExchangeFolderInfo createPublicFolder(String parentFolderUri, String name, ExchangeFolderPermissionCollection permissions)
```


Creates the specified public folder in the root public folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | The URI of parent folder |
| name | java.lang.String | A name of new folder |
| permissions | [ExchangeFolderPermissionCollection](../../com.aspose.email/exchangefolderpermissioncollection) | A permission on new folder |

**Returns:**
[ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) - Returns folder information
### createTask(ExchangeTask task) {#createTask-com.aspose.email.ExchangeTask-}
```
public abstract String createTask(ExchangeTask task)
```


Creates the given task in the default task folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| task | [ExchangeTask](../../com.aspose.email/exchangetask) | A task to create. |

**Returns:**
java.lang.String - A task uri
### createTask(MapiTask task) {#createTask-com.aspose.email.MapiTask-}
```
public abstract String createTask(MapiTask task)
```


Creates the given task in the default task folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| task | [MapiTask](../../com.aspose.email/mapitask) | A task to create. |

**Returns:**
java.lang.String
### createTask(String folder, ExchangeTask task) {#createTask-java.lang.String-com.aspose.email.ExchangeTask-}
```
public abstract String createTask(String folder, ExchangeTask task)
```


Creates the given task in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder where task should be created. |
| task | [ExchangeTask](../../com.aspose.email/exchangetask) | A task to create. |

**Returns:**
java.lang.String - A task uri
### createTask(String folder, MapiTask task) {#createTask-java.lang.String-com.aspose.email.MapiTask-}
```
public abstract String createTask(String folder, MapiTask task)
```


Creates the given task in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder where task should be created. |
| task | [MapiTask](../../com.aspose.email/mapitask) | A task to create. |

**Returns:**
java.lang.String
### createUserConfiguration(UserConfiguration userConfiguration) {#createUserConfiguration-com.aspose.email.UserConfiguration-}
```
public abstract void createUserConfiguration(UserConfiguration userConfiguration)
```


Creates the specified user configuration

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userConfiguration | [UserConfiguration](../../com.aspose.email/userconfiguration) | [UserConfiguration](../../com.aspose.email/userconfiguration) to be created |

### delegateAccess(ExchangeDelegateUser delegateUser, String mailbox) {#delegateAccess-com.aspose.email.ExchangeDelegateUser-java.lang.String-}
```
public abstract void delegateAccess(ExchangeDelegateUser delegateUser, String mailbox)
```


Delegates access on the specified mailbox to the specified user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegateUser | [ExchangeDelegateUser](../../com.aspose.email/exchangedelegateuser) | A [ExchangeDelegateUser](../../com.aspose.email/exchangedelegateuser) containing user information and delegation settings. |
| mailbox | java.lang.String | A mailbox to grant access on. |

### delegateAccess(ExchangeDelegateUserCollection delegateUsers, String mailbox) {#delegateAccess-com.aspose.email.ExchangeDelegateUserCollection-java.lang.String-}
```
public abstract void delegateAccess(ExchangeDelegateUserCollection delegateUsers, String mailbox)
```


Delegates access on the mailbox to the specified users.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegateUsers | [ExchangeDelegateUserCollection](../../com.aspose.email/exchangedelegateusercollection) | A [ExchangeDelegateUserCollection](../../com.aspose.email/exchangedelegateusercollection) containing the users information and delegation settings. |
| mailbox | java.lang.String | A mailbox to grant access on. |

### delegateAccess(String delegateSmtpAddress, int permissionLevel, String mailbox) {#delegateAccess-java.lang.String-int-java.lang.String-}
```
public abstract void delegateAccess(String delegateSmtpAddress, int permissionLevel, String mailbox)
```


Delegates access on the principal mailbox to the specified user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegateSmtpAddress | java.lang.String | A primary smtp address of user. |
| permissionLevel | int | A permission level that is granted to the user on all folders. |
| mailbox | java.lang.String | A mailbox to grant access on. |

### deleteConversationItems(String conversationId) {#deleteConversationItems-java.lang.String-}
```
public abstract void deleteConversationItems(String conversationId)
```


Deletes all items of the specified conversation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | java.lang.String | Id of conversation to delete |

### deleteConversationItems(String conversationId, String contextFolderId) {#deleteConversationItems-java.lang.String-java.lang.String-}
```
public abstract void deleteConversationItems(String conversationId, String contextFolderId)
```


Deletes the conversation items, which are located in the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | java.lang.String | Id of conversation to delete |
| contextFolderId | java.lang.String | Id of folder in which delete conversation items. Note: If it's set to null(or empty), all conversation items will be deleted |

### deleteDistributionList(ExchangeDistributionList distributionList, boolean deletePermanently) {#deleteDistributionList-com.aspose.email.ExchangeDistributionList-boolean-}
```
public abstract void deleteDistributionList(ExchangeDistributionList distributionList, boolean deletePermanently)
```


Deletes the Distribution List.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| distributionList | [ExchangeDistributionList](../../com.aspose.email/exchangedistributionlist) | A [ExchangeDistributionList](../../com.aspose.email/exchangedistributionlist) containing information about Distribution List to delete. |
| deletePermanently | boolean | Indicates whether the specified List should be deleted permanently or should be moved into DeletedItems folder. |

### deleteFolder(String folderUri) {#deleteFolder-java.lang.String-}
```
public abstract void deleteFolder(String folderUri)
```


Deletes the folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | The folder Uri |

### deleteFolder(String folderUri, boolean deletePermanently) {#deleteFolder-java.lang.String-boolean-}
```
public abstract void deleteFolder(String folderUri, boolean deletePermanently)
```


Deletes the folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | The folder Uri |
| deletePermanently | boolean | Indicates whether the folder should be deleted permanently or should be moved into DeletedItems folder |

### deleteFolders(ExchangeFolderInfoCollection folders) {#deleteFolders-com.aspose.email.ExchangeFolderInfoCollection-}
```
public abstract void deleteFolders(ExchangeFolderInfoCollection folders)
```


Deletes the specified folders

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folders | [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) | A [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) containing information about folders to delete |

### deleteFolders(ExchangeFolderInfoCollection folders, boolean deletePermanently) {#deleteFolders-com.aspose.email.ExchangeFolderInfoCollection-boolean-}
```
public abstract void deleteFolders(ExchangeFolderInfoCollection folders, boolean deletePermanently)
```


Deletes the specified folders

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folders | [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) | A [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) containing information about folders to delete |
| deletePermanently | boolean | Indicates whether the folder should be deleted permanently or should be moved into DeletedItems folder |

### deleteFolders(System.Collections.Specialized.StringCollection folderUris) {#deleteFolders-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public abstract void deleteFolders(System.Collections.Specialized.StringCollection folderUris)
```


Deletes the specified folders

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUris | com.aspose.ms.System.Collections.Specialized.StringCollection | The folder uris |

### deleteFolders(System.Collections.Specialized.StringCollection folderUris, boolean deletePermanently) {#deleteFolders-com.aspose.ms.System.Collections.Specialized.StringCollection-boolean-}
```
public abstract void deleteFolders(System.Collections.Specialized.StringCollection folderUris, boolean deletePermanently)
```


Deletes the folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUris | com.aspose.ms.System.Collections.Specialized.StringCollection | The folder Uri |
| deletePermanently | boolean | Indicates whether the folder should be deleted permanently or should be moved into DeletedItems folder |

### deleteFromDistributionList(ExchangeDistributionList distributionList, MailAddressCollection members) {#deleteFromDistributionList-com.aspose.email.ExchangeDistributionList-com.aspose.email.MailAddressCollection-}
```
public abstract void deleteFromDistributionList(ExchangeDistributionList distributionList, MailAddressCollection members)
```


Deletes the members from Distribution List.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| distributionList | [ExchangeDistributionList](../../com.aspose.email/exchangedistributionlist) | A [ExchangeDistributionList](../../com.aspose.email/exchangedistributionlist) containing information about Distribution List to update. |
| members | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | A [MailAddressCollection](../../com.aspose.email/mailaddresscollection) containing the mail addresses to delete. The MailAddress must contain id. |

### deleteInboxRule(String ruleId) {#deleteInboxRule-java.lang.String-}
```
public abstract void deleteInboxRule(String ruleId)
```


Deletes the specified inbox rule

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ruleId | java.lang.String | An id of inbox rule to delete |

### deleteInboxRule(String ruleId, String mailbox) {#deleteInboxRule-java.lang.String-java.lang.String-}
```
public abstract void deleteInboxRule(String ruleId, String mailbox)
```


Deletes the specified inbox rule

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ruleId | java.lang.String | An id of inbox rule to delete |
| mailbox | java.lang.String | A mailbox where rule is located. Note: if it is set to  null  or  empty , the rule will be searched in the default mailbox |

### deleteItem(String itemUri, DeletionOptions options) {#deleteItem-java.lang.String-com.aspose.email.DeletionOptions-}
```
public abstract void deleteItem(String itemUri, DeletionOptions options)
```


Deletes specified item

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| itemUri | java.lang.String | The item uri |
| options | [DeletionOptions](../../com.aspose.email/deletionoptions) | Defines parameters for item deletion |

### deleteItems(Iterable<String> itemUris, DeletionOptions options) {#deleteItems-java.lang.Iterable-java.lang.String--com.aspose.email.DeletionOptions-}
```
public abstract void deleteItems(Iterable<String> itemUris, DeletionOptions options)
```


Deletes specified items

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| itemUris | java.lang.Iterable<java.lang.String> | An items uris |
| options | [DeletionOptions](../../com.aspose.email/deletionoptions) | Defines parameters for items deletion |

### deleteUserConfiguration(UserConfigurationName userConfigurationName) {#deleteUserConfiguration-com.aspose.email.UserConfigurationName-}
```
public abstract void deleteUserConfiguration(UserConfigurationName userConfigurationName)
```


Deletes the specified user configuration

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userConfigurationName | [UserConfigurationName](../../com.aspose.email/userconfigurationname) | Specifies a user configuration to delete |

### disconnectPhoneCall(String callId) {#disconnectPhoneCall-java.lang.String-}
```
public abstract void disconnectPhoneCall(String callId)
```


Disconnects a phone call specified by id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callId | java.lang.String | Phone call id. |

### emptyFolder(String folderUri) {#emptyFolder-java.lang.String-}
```
public abstract void emptyFolder(String folderUri)
```


Empties the specified folder. Subfolders will not be deleted; deleted items will be moved into DeletedItems folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | Specifies the folder to be empty |

### emptyFolder(String folderUri, int options) {#emptyFolder-java.lang.String-int-}
```
public abstract void emptyFolder(String folderUri, int options)
```


Empties the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | Specifies the folder to be empty |
| options | int | Specifies the options of clearing folder |

### expandDistributionList(MailAddress mailAddress) {#expandDistributionList-com.aspose.email.MailAddress-}
```
public abstract MailAddressCollection expandDistributionList(MailAddress mailAddress)
```


Expands the public Distribution List members.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailAddress | [MailAddress](../../com.aspose.email/mailaddress) | A public [MailAddress](../../com.aspose.email/mailaddress) to expand. |

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection) - A [MailAddressCollection](../../com.aspose.email/mailaddresscollection) that contains members from the specified public Distribution List.
### exportItems(String[] itemIds) {#exportItems-java.lang.String...-}
```
public abstract ExchangeStreamedItem[] exportItems(String[] itemIds)
```


Exports the specified items from mailbox

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| itemIds | java.lang.String[] | Ids of itmes to be exported |

**Returns:**
com.aspose.email.ExchangeStreamedItem[] - An array of [ExchangeStreamedItem](../../com.aspose.email/exchangestreameditem)
### fetchAppointment(String appointmentUri) {#fetchAppointment-java.lang.String-}
```
public abstract Appointment fetchAppointment(String appointmentUri)
```


Fetch the specified appointment from server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointmentUri | java.lang.String | An uri of appointment to be fetched. |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A fetched [Appointment](../../com.aspose.email/appointment).
### fetchAppointment(String appointmentUri, String folderUri) {#fetchAppointment-java.lang.String-java.lang.String-}
```
public abstract Appointment fetchAppointment(String appointmentUri, String folderUri)
```


Fetch the specified appointment from server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointmentUri | java.lang.String | An uri of appointment to be fetched. |
| folderUri | java.lang.String | An uri of appointments parent folder. |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A fetched [Appointment](../../com.aspose.email/appointment).
### fetchAttachment(String attachmentUri) {#fetchAttachment-java.lang.String-}
```
public abstract Attachment fetchAttachment(String attachmentUri)
```


Fetches the attachment

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attachmentUri | java.lang.String | The attachment uri |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - [Attachment](../../com.aspose.email/attachment) that represents fetched attachment
### fetchContact(String contactUri) {#fetchContact-java.lang.String-}
```
public abstract MapiContact fetchContact(String contactUri)
```


Fetches [MapiContact](../../com.aspose.email/mapicontact) object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contactUri | java.lang.String | Contact object uri |

**Returns:**
[MapiContact](../../com.aspose.email/mapicontact) - [MapiContact](../../com.aspose.email/mapicontact) object
### fetchContact(String contactUri, Iterable<PropertyDescriptor> customProperties) {#fetchContact-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract MapiContact fetchContact(String contactUri, Iterable<PropertyDescriptor> customProperties)
```


Fetches [MapiContact](../../com.aspose.email/mapicontact) object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contactUri | java.lang.String | Contact object uri |
| customProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | Custom mapi properties to retrieve. |

**Returns:**
[MapiContact](../../com.aspose.email/mapicontact) - [MapiContact](../../com.aspose.email/mapicontact) object
### fetchConversationMessages(String conversationId) {#fetchConversationMessages-java.lang.String-}
```
public abstract MailMessageCollection fetchConversationMessages(String conversationId)
```


Fetches the specified conversation messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | java.lang.String | Id of conversation |

**Returns:**
[MailMessageCollection](../../com.aspose.email/mailmessagecollection)
### fetchDistributionList(ExchangeDistributionList distributionList) {#fetchDistributionList-com.aspose.email.ExchangeDistributionList-}
```
public abstract MailAddressCollection fetchDistributionList(ExchangeDistributionList distributionList)
```


Fetches the private Distribution List members.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| distributionList | [ExchangeDistributionList](../../com.aspose.email/exchangedistributionlist) | A [ExchangeDistributionList](../../com.aspose.email/exchangedistributionlist) containing information about Distribution List to fetch. |

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection) - A [MailAddressCollection](../../com.aspose.email/mailaddresscollection) that contains members from the specified private Distribution List.
### fetchItem(String uri) {#fetchItem-java.lang.String-}
```
public abstract MapiMessage fetchItem(String uri)
```


Retrieves the complete item with attachments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uri | java.lang.String | The item URI. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - [MapiMessage](../../com.aspose.email/mapimessage) object.
### fetchItem(String uri, Iterable<PropertyDescriptor> extendedProperties) {#fetchItem-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract MapiMessage fetchItem(String uri, Iterable<PropertyDescriptor> extendedProperties)
```


Retrieves the complete item with attachments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uri | java.lang.String | The item URI. |
| extendedProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | Specified properties to retrieve. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - [MapiMessage](../../com.aspose.email/mapimessage) object.
### fetchMapiCalendar(Iterable<String> calendarUris) {#fetchMapiCalendar-java.lang.Iterable-java.lang.String--}
```
public abstract System.Collections.Generic.IGenericList<MapiCalendar> fetchMapiCalendar(Iterable<String> calendarUris)
```


Fetch array of [MapiCalendar](../../com.aspose.email/mapicalendar) objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarUris | java.lang.Iterable<java.lang.String> | List of calendar uris to be fetched. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MapiCalendar> - Fetch array of [MapiCalendar](../../com.aspose.email/mapicalendar) objects.
### fetchMapiCalendar(Iterable<String> calendarUris, Iterable<PropertyDescriptor> customProperties) {#fetchMapiCalendar-java.lang.Iterable-java.lang.String--java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract System.Collections.Generic.IGenericList<MapiCalendar> fetchMapiCalendar(Iterable<String> calendarUris, Iterable<PropertyDescriptor> customProperties)
```


Fetch array of [MapiCalendar](../../com.aspose.email/mapicalendar) objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarUris | java.lang.Iterable<java.lang.String> | List of calendar uris to be fetched. |
| customProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | Custom mapi properties to retrieve. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MapiCalendar> - Fetch array of [MapiCalendar](../../com.aspose.email/mapicalendar) objects.
### fetchMapiCalendar(String calendarUri) {#fetchMapiCalendar-java.lang.String-}
```
public abstract MapiCalendar fetchMapiCalendar(String calendarUri)
```


Fetch [MapiCalendar](../../com.aspose.email/mapicalendar) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarUri | java.lang.String | calendar uri to be fetched. |

**Returns:**
[MapiCalendar](../../com.aspose.email/mapicalendar) - Fetch [MapiCalendar](../../com.aspose.email/mapicalendar) object.
### fetchMapiCalendar(String calendarUri, Iterable<PropertyDescriptor> customProperties) {#fetchMapiCalendar-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract MapiCalendar fetchMapiCalendar(String calendarUri, Iterable<PropertyDescriptor> customProperties)
```


Fetch [MapiCalendar](../../com.aspose.email/mapicalendar) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| calendarUri | java.lang.String | calendar uri to be fetched. |
| customProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | Custom mapi properties to retrieve. |

**Returns:**
[MapiCalendar](../../com.aspose.email/mapicalendar) - Fetch [MapiCalendar](../../com.aspose.email/mapicalendar) object.
### fetchMapiMessage(String uri) {#fetchMapiMessage-java.lang.String-}
```
public abstract MapiMessage fetchMapiMessage(String uri)
```


Fetches the speciifed message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uri | java.lang.String | A String containing message uri to be retrieved |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Fetched [MapiMessage](../../com.aspose.email/mapimessage).
### fetchMapiMessage(String uri, Iterable<PropertyDescriptor> extendedProperties) {#fetchMapiMessage-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract MapiMessage fetchMapiMessage(String uri, Iterable<PropertyDescriptor> extendedProperties)
```


Fetches the speciifed message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uri | java.lang.String | A String containing message uri to be retrieved |
| extendedProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | An enumeration of extended properties |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Fetched [MapiMessage](../../com.aspose.email/mapimessage).
### fetchMapiMessages(Iterable<String> uris) {#fetchMapiMessages-java.lang.Iterable-java.lang.String--}
```
public abstract MapiMessage[] fetchMapiMessages(Iterable<String> uris)
```


Fetches the speciifed messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uris | java.lang.Iterable<java.lang.String> | A  IEnumerable\{String\}IEnumerable<string>  "/> containing message uris to be retrieved |

**Returns:**
com.aspose.email.MapiMessage[] - An array of [MapiMessage](../../com.aspose.email/mapimessage) containing fetched messages
### fetchMapiMessages(Iterable<String> uris, Iterable<PropertyDescriptor> extendedProperties) {#fetchMapiMessages-java.lang.Iterable-java.lang.String--java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract MapiMessage[] fetchMapiMessages(Iterable<String> uris, Iterable<PropertyDescriptor> extendedProperties)
```


Fetches the speciifed messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uris | java.lang.Iterable<java.lang.String> | A StringCollection containing message uris to be retrieved |
| extendedProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | An enumeration of extended properties |

**Returns:**
com.aspose.email.MapiMessage[] - An array of [MapiMessage](../../com.aspose.email/mapimessage) containing fetched messages
### fetchMapiNote(String noteUri) {#fetchMapiNote-java.lang.String-}
```
public abstract MapiNote fetchMapiNote(String noteUri)
```


Fetches [MapiNote](../../com.aspose.email/mapinote) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| noteUri | java.lang.String | note uri to be fetched. |

**Returns:**
[MapiNote](../../com.aspose.email/mapinote) - [MapiNote](../../com.aspose.email/mapinote) object.
### fetchMapiNote(String noteUri, Iterable<PropertyDescriptor> customProperties) {#fetchMapiNote-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract MapiNote fetchMapiNote(String noteUri, Iterable<PropertyDescriptor> customProperties)
```


Fetches [MapiNote](../../com.aspose.email/mapinote) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| noteUri | java.lang.String | note uri to be fetched. |
| customProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | Custom mapi properties to retrieve. |

**Returns:**
[MapiNote](../../com.aspose.email/mapinote) - [MapiNote](../../com.aspose.email/mapinote) object.
### fetchMapiNotes(Iterable<String> noteUris) {#fetchMapiNotes-java.lang.Iterable-java.lang.String--}
```
public abstract System.Collections.Generic.IGenericList<MapiNote> fetchMapiNotes(Iterable<String> noteUris)
```


Fetch array of [MapiNote](../../com.aspose.email/mapinote) objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| noteUris | java.lang.Iterable<java.lang.String> | List of note uris to be fetched. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MapiNote> - Fetch array of [MapiNote](../../com.aspose.email/mapinote) objects.
### fetchMapiNotes(Iterable<String> noteUris, Iterable<PropertyDescriptor> customProperties) {#fetchMapiNotes-java.lang.Iterable-java.lang.String--java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract System.Collections.Generic.IGenericList<MapiNote> fetchMapiNotes(Iterable<String> noteUris, Iterable<PropertyDescriptor> customProperties)
```


Fetch array of [MapiNote](../../com.aspose.email/mapinote) objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| noteUris | java.lang.Iterable<java.lang.String> | List of note uris to be fetched. |
| customProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | Custom mapi properties to retrieve. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MapiNote> - Fetch array of [MapiNote](../../com.aspose.email/mapinote) objects.
### fetchMapiTask(String taskUri) {#fetchMapiTask-java.lang.String-}
```
public abstract MapiTask fetchMapiTask(String taskUri)
```


Fetches [MapiTask](../../com.aspose.email/mapitask) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| taskUri | java.lang.String | task uri to be fetched. |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - [MapiTask](../../com.aspose.email/mapitask) object.
### fetchMapiTask(String taskUri, Iterable<PropertyDescriptor> customProperties) {#fetchMapiTask-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract MapiTask fetchMapiTask(String taskUri, Iterable<PropertyDescriptor> customProperties)
```


Fetches [MapiTask](../../com.aspose.email/mapitask) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| taskUri | java.lang.String | task uri to be fetched. |
| customProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | Custom mapi properties to retrieve. |

**Returns:**
[MapiTask](../../com.aspose.email/mapitask) - [MapiTask](../../com.aspose.email/mapitask) object.
### fetchMapiTasks(Iterable<String> taskUris) {#fetchMapiTasks-java.lang.Iterable-java.lang.String--}
```
public abstract System.Collections.Generic.IGenericList<MapiTask> fetchMapiTasks(Iterable<String> taskUris)
```


Fetch array of [MapiTask](../../com.aspose.email/mapitask) objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| taskUris | java.lang.Iterable<java.lang.String> | List of task uris to be fetched. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MapiTask> - Fetch array of [MapiTask](../../com.aspose.email/mapitask) objects.
### fetchMapiTasks(Iterable<String> taskUris, Iterable<PropertyDescriptor> customProperties) {#fetchMapiTasks-java.lang.Iterable-java.lang.String--java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract System.Collections.Generic.IGenericList<MapiTask> fetchMapiTasks(Iterable<String> taskUris, Iterable<PropertyDescriptor> customProperties)
```


Fetch array of [MapiTask](../../com.aspose.email/mapitask) objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| taskUris | java.lang.Iterable<java.lang.String> | List of task uris to be fetched. |
| customProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | Custom mapi properties to retrieve. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MapiTask> - Fetch array of [MapiTask](../../com.aspose.email/mapitask) objects.
### fetchMessage(String messageUri) {#fetchMessage-java.lang.String-}
```
public abstract MailMessage fetchMessage(String messageUri)
```


Fetches the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | The message URI. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Returns a message
### fetchMessage(String messageUri, Iterable<PropertyDescriptor> extendedProperties) {#fetchMessage-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract MailMessage fetchMessage(String messageUri, Iterable<PropertyDescriptor> extendedProperties)
```


Fetches the message from server

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | The URI of the message |
| extendedProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | An enumeration of extended properties |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - [MailMessage](../../com.aspose.email/mailmessage) that represents e-mail message, if custom properties have been found and set you can access them using  MailMessage.Headers ([MailMessage.getHeaders](../../com.aspose.email/mailmessage\#getHeaders)) collection.
### fetchMessages(ExchangeMessageInfoCollection messageInfos) {#fetchMessages-com.aspose.email.ExchangeMessageInfoCollection-}
```
public abstract MailMessageCollection fetchMessages(ExchangeMessageInfoCollection messageInfos)
```


Fetches the speciifed messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfos | [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) | A  IEnumerable\{ExchangeMessageInfo\}IEnumerable<ExchangeMessageInfo>  "/> of messages to be retrieved |

**Returns:**
[MailMessageCollection](../../com.aspose.email/mailmessagecollection) - A [MailMessageCollection](../../com.aspose.email/mailmessagecollection) containing fetched messages
### fetchMessages(System.Collections.Specialized.StringCollection messageUris) {#fetchMessages-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public abstract MailMessageCollection fetchMessages(System.Collections.Specialized.StringCollection messageUris)
```


Fetches the speciifed messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUris | com.aspose.ms.System.Collections.Specialized.StringCollection | A StringCollection containing message uris to be retrieved |

**Returns:**
[MailMessageCollection](../../com.aspose.email/mailmessagecollection) - A [MailMessageCollection](../../com.aspose.email/mailmessagecollection) containing fetched messages
### fetchMessages(Iterable<String> uris) {#fetchMessages-java.lang.Iterable-java.lang.String--}
```
public abstract MailMessageCollection fetchMessages(Iterable<String> uris)
```


Fetches the speciifed messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uris | java.lang.Iterable<java.lang.String> | A StringCollection containing message uris to be retrieved |

**Returns:**
[MailMessageCollection](../../com.aspose.email/mailmessagecollection) - A [MailMessageCollection](../../com.aspose.email/mailmessagecollection) containing fetched messages
### fetchMessages(Iterable<String> uris, Iterable<PropertyDescriptor> extendedProperties) {#fetchMessages-java.lang.Iterable-java.lang.String--java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract MailMessageCollection fetchMessages(Iterable<String> uris, Iterable<PropertyDescriptor> extendedProperties)
```


Fetches the speciifed messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uris | java.lang.Iterable<java.lang.String> | A StringCollection containing message uris to be retrieved |
| extendedProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | An enumeration of extended properties |

**Returns:**
[MailMessageCollection](../../com.aspose.email/mailmessagecollection) - A [MailMessageCollection](../../com.aspose.email/mailmessagecollection) containing fetched messages
### fetchTask(String taskUri) {#fetchTask-java.lang.String-}
```
public abstract ExchangeTask fetchTask(String taskUri)
```


Fetches the specified task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| taskUri | java.lang.String | A task uri. |

**Returns:**
[ExchangeTask](../../com.aspose.email/exchangetask) - A fetched [ExchangeTask](../../com.aspose.email/exchangetask)
### findConversations(String folderId) {#findConversations-java.lang.String-}
```
public abstract ExchangeConversation[] findConversations(String folderId)
```


Finds conversations in the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderId | java.lang.String | An id of folder in which search |

**Returns:**
com.aspose.email.ExchangeConversation[] - An array of found [ExchangeConversation](../../com.aspose.email/exchangeconversation)
### findMessageTrackingReport(FindMessageTrackingReportOptions options) {#findMessageTrackingReport-com.aspose.email.FindMessageTrackingReportOptions-}
```
public abstract MessageTrackingReportInfo[] findMessageTrackingReport(FindMessageTrackingReportOptions options)
```


Finds messages that meet the specified criteria.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [FindMessageTrackingReportOptions](../../com.aspose.email/findmessagetrackingreportoptions) | Options specifying a search criteria |

**Returns:**
com.aspose.email.MessageTrackingReportInfo[] - An array of [MessageTrackingReportInfo](../../com.aspose.email/messagetrackingreportinfo) that represents message tracking report information
### findPeople(String folderUri, MailQuery query, int maxNumberOfItems) {#findPeople-java.lang.String-com.aspose.email.MailQuery-int-}
```
public abstract Contact[] findPeople(String folderUri, MailQuery query, int maxNumberOfItems)
```


Find contacts located in the specified user's personal mailbox on server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | The URI of folder. |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents contact search criteria. |
| maxNumberOfItems | int | Maximum number of items. |

**Returns:**
com.aspose.email.Contact[] - An array of [Contact](../../com.aspose.email/contact) that represents contact information
### findPeople(String queryString, int maxNumberOfItems) {#findPeople-java.lang.String-int-}
```
public abstract Contact[] findPeople(String queryString, int maxNumberOfItems)
```


Find contacts located in the global address list (GAL) on server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| queryString | java.lang.String | Represents contact search criteria. |
| maxNumberOfItems | int | Maximum number of items. |

**Returns:**
com.aspose.email.Contact[] - An array of [Contact](../../com.aspose.email/contact) that represents contact information
### folderExists(String parentFolderUri, String folderName) {#folderExists-java.lang.String-java.lang.String-}
```
public abstract boolean folderExists(String parentFolderUri, String folderName)
```


Checks whether the specified folder exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | An uri of parent folder. |
| folderName | java.lang.String | A folder name. |

**Returns:**
boolean -  true  if the specified folder exists in the specified parent folder; otherwise,  false .
### folderExists(String parentFolderUri, String folderName, ExchangeFolderInfo[] folder) {#folderExists-java.lang.String-java.lang.String-com.aspose.email.ExchangeFolderInfo---}
```
public abstract boolean folderExists(String parentFolderUri, String folderName, ExchangeFolderInfo[] folder)
```


Checks whether the specified folder exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | An uri of parent folder. |
| folderName | java.lang.String | A folder name. |
| folder | [ExchangeFolderInfo\[\]](../../com.aspose.email/exchangefolderinfo) | A [ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) that represents the found folder information, if folder exists. |

**Returns:**
boolean -  true  if the specified folder exists in the specified parent folder; otherwise,  false .
### forward(MailMessage message, ExchangeMessageInfo referencedMessage) {#forward-com.aspose.email.MailMessage-com.aspose.email.ExchangeMessageInfo-}
```
public abstract void forward(MailMessage message, ExchangeMessageInfo referencedMessage)
```


Forward a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The [MailMessage](../../com.aspose.email/mailmessage) that represents the precomposed forward message. |
| referencedMessage | [ExchangeMessageInfo](../../com.aspose.email/exchangemessageinfo) | The [ExchangeMessageInfo](../../com.aspose.email/exchangemessageinfo) that represents the original message. |

### forward(MailMessage message, String referencedUri) {#forward-com.aspose.email.MailMessage-java.lang.String-}
```
public abstract void forward(MailMessage message, String referencedUri)
```


Forward a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The [MailMessage](../../com.aspose.email/mailmessage) that represents the precomposed forward message. |
| referencedUri | java.lang.String | The URI that represents the original message. |

### getCalendarFolderEventFilter() {#getCalendarFolderEventFilter--}
```
public abstract int getCalendarFolderEventFilter()
```


Specifies event types for Calendar folder

**Returns:**
int
### getCallInfo(String callId) {#getCallInfo-java.lang.String-}
```
public abstract CallInformation getCallInfo(String callId)
```


Retrieves phone call information by call id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callId | java.lang.String | call id |

**Returns:**
[CallInformation](../../com.aspose.email/callinformation) - Returns phone call information object
### getContact(ObjectIdentifier contactId) {#getContact-com.aspose.email.ObjectIdentifier-}
```
public abstract Contact getContact(ObjectIdentifier contactId)
```


Retrieves contact information according to specified identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contactId | [ObjectIdentifier](../../com.aspose.email/objectidentifier) | Contact identifier |

**Returns:**
[Contact](../../com.aspose.email/contact) - Contact information
### getContact(ObjectIdentifier contactId, int options) {#getContact-com.aspose.email.ObjectIdentifier-int-}
```
public abstract Contact getContact(ObjectIdentifier contactId, int options)
```


Retrieves contact information according to specified identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contactId | [ObjectIdentifier](../../com.aspose.email/objectidentifier) | Contact identifier |
| options | int | Settings for retrieving contact. |

**Returns:**
[Contact](../../com.aspose.email/contact) - Contact information
### getContact(String contactId) {#getContact-java.lang.String-}
```
public abstract Contact getContact(String contactId)
```


Retrieves contact information according to specified identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contactId | java.lang.String | Contact identifier |

**Returns:**
[Contact](../../com.aspose.email/contact) - Contact information
### getContact(String contactId, int options) {#getContact-java.lang.String-int-}
```
public abstract Contact getContact(String contactId, int options)
```


Retrieves contact information according to specified identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contactId | java.lang.String | Contact identifier |
| options | int | Settings for retrieving contact. |

**Returns:**
[Contact](../../com.aspose.email/contact) - Contact information
### getContacts(String folder) {#getContacts-java.lang.String-}
```
public abstract Contact[] getContacts(String folder)
```


Lists contacts located in the specified folder on server

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search contacts in |

**Returns:**
com.aspose.email.Contact[] - An array of read [Contact](../../com.aspose.email/contact) that represents contact information
### getContacts(String folder, int options) {#getContacts-java.lang.String-int-}
```
public abstract Contact[] getContacts(String folder, int options)
```


Lists contacts located in the specified folder on server

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search contacts in |
| options | int | Enumerates the list contacts options |

**Returns:**
com.aspose.email.Contact[] - An array of read [Contact](../../com.aspose.email/contact) that represents contact information
### getContactsFolderEventFilter() {#getContactsFolderEventFilter--}
```
public abstract int getContactsFolderEventFilter()
```


Specifies event types for Contacts folder

**Returns:**
int
### getCurrentCalendarFolderUri() {#getCurrentCalendarFolderUri--}
```
public abstract String getCurrentCalendarFolderUri()
```


Gets or sets current calendar folder uri

**Returns:**
java.lang.String
### getDeletedItemsFolderEventFilter() {#getDeletedItemsFolderEventFilter--}
```
public abstract int getDeletedItemsFolderEventFilter()
```


Specifies event types for DeletedItems folder

**Returns:**
int
### getDraftsFolderEventFilter() {#getDraftsFolderEventFilter--}
```
public abstract int getDraftsFolderEventFilter()
```


Specifies event types for Drafts folder

**Returns:**
int
### getEnableDecompression() {#getEnableDecompression--}
```
public abstract boolean getEnableDecompression()
```


Gets or sets a value that indicates whether decompression is enabled

**Returns:**
boolean
### getExchangeType() {#getExchangeType--}
```
public abstract int getExchangeType()
```


Gets the information about the current version of MS Exchange.

**Returns:**
int - Returns Exchange server version
### getFolderInfo(String folder) {#getFolderInfo-java.lang.String-}
```
public abstract ExchangeFolderInfo getFolderInfo(String folder)
```


Gets the folder information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder uri or distinguished folder name |

**Returns:**
[ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) - A [ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) that represents the folder information
### getFolderPermissions(String folderUrl) {#getFolderPermissions-java.lang.String-}
```
public abstract ExchangePermissionCollection getFolderPermissions(String folderUrl)
```


Gets the folder permissions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUrl | java.lang.String | The folder URL. |

**Returns:**
[ExchangePermissionCollection](../../com.aspose.email/exchangepermissioncollection) - The [ExchangePermissionCollection](../../com.aspose.email/exchangepermissioncollection)
### getHeaders() {#getHeaders--}
```
public abstract System.Collections.Generic.List<System.Collections.Generic.KeyValuePair<String,String>> getHeaders()
```


Gets array of name value pairs wich are added to WebHeaderCollection in EWS request.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>>
### getInboxFolderEventFilter() {#getInboxFolderEventFilter--}
```
public abstract int getInboxFolderEventFilter()
```


Specifies event types for Inbox folder

**Returns:**
int
### getInboxRules() {#getInboxRules--}
```
public abstract InboxRule[] getInboxRules()
```


Gets inbox rules

**Returns:**
com.aspose.email.InboxRule[] - An array of [InboxRule](../../com.aspose.email/inboxrule)
### getInboxRules(String mailbox) {#getInboxRules-java.lang.String-}
```
public abstract InboxRule[] getInboxRules(String mailbox)
```


Gets inbox rules

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | java.lang.String | A mailbox to read inbox rule from. Note: if it is set to  null  or  empty , the rules will be read from the default mailbox |

**Returns:**
com.aspose.email.InboxRule[] - An array of [InboxRule](../../com.aspose.email/inboxrule)
### getJournalFolderEventFilter() {#getJournalFolderEventFilter--}
```
public abstract int getJournalFolderEventFilter()
```


Specifies event types for Journal folder

**Returns:**
int
### getLogFileName() {#getLogFileName--}
```
public abstract String getLogFileName()
```


Gets or sets log file name

**Returns:**
java.lang.String
### getMailTips(GetMailTipsOptions options) {#getMailTips-com.aspose.email.GetMailTipsOptions-}
```
public abstract MailTips[] getMailTips(GetMailTipsOptions options)
```


Gets mail tips

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [GetMailTipsOptions](../../com.aspose.email/getmailtipsoptions) | Options specifying a search criteria |

**Returns:**
com.aspose.email.MailTips[] - An array of [MailTips](../../com.aspose.email/mailtips)
### getMailboxInfo() {#getMailboxInfo--}
```
public abstract ExchangeMailboxInfo getMailboxInfo()
```


Gets the mailbox info.

**Returns:**
[ExchangeMailboxInfo](../../com.aspose.email/exchangemailboxinfo) - [ExchangeMailboxInfo](../../com.aspose.email/exchangemailboxinfo) that represents mailbox information
### getMailboxInfo(String mailbox) {#getMailboxInfo-java.lang.String-}
```
public abstract ExchangeMailboxInfo getMailboxInfo(String mailbox)
```


Gets the mailbox information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | java.lang.String | A mailbox to read from. |

**Returns:**
[ExchangeMailboxInfo](../../com.aspose.email/exchangemailboxinfo) - [ExchangeMailboxInfo](../../com.aspose.email/exchangemailboxinfo) that represents mailbox information
### getMailboxSize() {#getMailboxSize--}
```
public abstract long getMailboxSize()
```


Gets the size of the mailbox. Please, note this operation is performed recursively for all subfolders and make take some time

**Returns:**
long - size of the mailbox in bytes
### getMailboxSize(String mailbox) {#getMailboxSize-java.lang.String-}
```
public abstract long getMailboxSize(String mailbox)
```


Gets the size of the mailbox

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | java.lang.String | A mailbox. |

**Returns:**
long - size of the mailbox in bytes
### getMailboxSizeEx(String folderUri) {#getMailboxSizeEx-java.lang.String-}
```
public abstract long getMailboxSizeEx(String folderUri)
```


Gets the size of the mailbox Please, note this operation is performed recursively for all subfolders and make take some time

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | Folder uri |

**Returns:**
long - size of the mailbox in bytes
### getMailboxUri() {#getMailboxUri--}
```
public abstract String getMailboxUri()
```


Gets or sets the mailbox uri.

**Returns:**
java.lang.String
### getMailboxes() {#getMailboxes--}
```
public abstract Contact[] getMailboxes()
```


Lists mailboxes having smtp addresses. Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation.

**Returns:**
com.aspose.email.Contact[] - Contacts that represents contact information
### getMessageTrackingReport(GetMessageTrackingReportOptions options) {#getMessageTrackingReport-com.aspose.email.GetMessageTrackingReportOptions-}
```
public abstract MessageTrackingReport getMessageTrackingReport(GetMessageTrackingReportOptions options)
```


Gets message tracking report

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [GetMessageTrackingReportOptions](../../com.aspose.email/getmessagetrackingreportoptions) | Options specifying a search criteria |

**Returns:**
[MessageTrackingReport](../../com.aspose.email/messagetrackingreport) - A found [MessageTrackingReport](../../com.aspose.email/messagetrackingreport) or  null  if no message tracking report was found
### getNotesFolderEventFilter() {#getNotesFolderEventFilter--}
```
public abstract int getNotesFolderEventFilter()
```


Specifies event types for Notes folder

**Returns:**
int
### getNotificationTimeout() {#getNotificationTimeout--}
```
public abstract int getNotificationTimeout()
```


Defines timeout for server notifications

**Returns:**
int
### getNotificationsCheckInterval() {#getNotificationsCheckInterval--}
```
public abstract int getNotificationsCheckInterval()
```


Defines interval for notification check

**Returns:**
int
### getOutboxFolderEventFilter() {#getOutboxFolderEventFilter--}
```
public abstract int getOutboxFolderEventFilter()
```


Specifies event types for Outbox folder

**Returns:**
int
### getReconnectCount() {#getReconnectCount--}
```
public abstract int getReconnectCount()
```


Gets or sets the number of reconnect attempts at connection breaks.

**Returns:**
int
### getReturnClientRequestId() {#getReturnClientRequestId--}
```
public abstract boolean getReturnClientRequestId()
```


Gets or sets a flag to indicate whether the client requires the server side to return the request id.

**Returns:**
boolean
### getRootFolderEventFilter() {#getRootFolderEventFilter--}
```
public abstract int getRootFolderEventFilter()
```


Specifies event types for Root folder

**Returns:**
int
### getSentItemsFolderEventFilter() {#getSentItemsFolderEventFilter--}
```
public abstract int getSentItemsFolderEventFilter()
```


Specifies event types for SentItems folder

**Returns:**
int
### getServerTimeZoneIds() {#getServerTimeZoneIds--}
```
public abstract String[] getServerTimeZoneIds()
```


The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server.

**Returns:**
java.lang.String[] - Returns an array of time zone id that are available on an Exchange server.
### getServerTimeZoneIds(Iterable<String> timeZoneIds) {#getServerTimeZoneIds-java.lang.Iterable-java.lang.String--}
```
public abstract String[] getServerTimeZoneIds(Iterable<String> timeZoneIds)
```


The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeZoneIds | java.lang.Iterable<java.lang.String> | Identifiers of time zones for checking existence on the server. |

**Returns:**
java.lang.String[] - Returns an array of time zone id that are available on an Exchange server.
### getServerTimeZoneIds(String[] timeZoneIds) {#getServerTimeZoneIds-java.lang.String...-}
```
public abstract String[] getServerTimeZoneIds(String[] timeZoneIds)
```


The GetServerTimeZoneIds returns information from time zone id that are available on an Exchange server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeZoneIds | java.lang.String[] | Identifiers of time zones for checking existence on the server. |

**Returns:**
java.lang.String[] - Returns an array of time zone id that are available on an Exchange server.
### getServerVersion() {#getServerVersion--}
```
public abstract int getServerVersion()
```


Gets the information about the current version of MS Exchange.

**Returns:**
int
### getTasksFolderEventFilter() {#getTasksFolderEventFilter--}
```
public abstract int getTasksFolderEventFilter()
```


Specifies event types for Tasks folder

**Returns:**
int
### getTimezoneId() {#getTimezoneId--}
```
public abstract String getTimezoneId()
```


Gets or sets timezone id

**Returns:**
java.lang.String
### getUMConfiguration() {#getUMConfiguration--}
```
public abstract UnifiedMessagingConfiguration getUMConfiguration()
```


Retrieves unified messaging configuration

**Returns:**
[UnifiedMessagingConfiguration](../../com.aspose.email/unifiedmessagingconfiguration) - Returns unified messaging configuration
### getUseDateInLogFileName() {#getUseDateInLogFileName--}
```
public abstract boolean getUseDateInLogFileName()
```


Gets or sets value which indicates if date has to be used in log file name.

**Returns:**
boolean
### getUseSlashAsFolderSeparator() {#getUseSlashAsFolderSeparator--}
```
public abstract boolean getUseSlashAsFolderSeparator()
```


Gets or sets value that determines whether the slash '/' is used as folder separator.

**Returns:**
boolean
### getUserConfiguration(UserConfigurationName userConfigurationName) {#getUserConfiguration-com.aspose.email.UserConfigurationName-}
```
public abstract UserConfiguration getUserConfiguration(UserConfigurationName userConfigurationName)
```


Gets the specified user configuration

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userConfigurationName | [UserConfigurationName](../../com.aspose.email/userconfigurationname) | Specifies a user configuration to search |

**Returns:**
[UserConfiguration](../../com.aspose.email/userconfiguration) - A received [UserConfiguration](../../com.aspose.email/userconfiguration)
### getVersionInfo() {#getVersionInfo--}
```
public abstract String getVersionInfo()
```


Returns exchange server version info

**Returns:**
java.lang.String - Returns exchange server version info
### impersonateUser(int valueType, String value) {#impersonateUser-int-java.lang.String-}
```
public abstract void impersonateUser(int valueType, String value)
```


Impersonates the user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| valueType | int | The ItemChoiceType enumeration value to use for impersonation. |
| value | java.lang.String | The item name. |

### listAppointments() {#listAppointments--}
```
public abstract Appointment[] listAppointments()
```


Retrieves list of appointments for default calendar folder

**Returns:**
com.aspose.email.Appointment[] - Returns array of appointments
### listAppointments(boolean recursive) {#listAppointments-boolean-}
```
public abstract Appointment[] listAppointments(boolean recursive)
```


Retrieves list of appointments for default calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recursive | boolean | Indicates whether recursive listing or not. |

**Returns:**
com.aspose.email.Appointment[] - Returns array of appointments
### listAppointments(MailQuery query) {#listAppointments-com.aspose.email.MailQuery-}
```
public abstract Appointment[] listAppointments(MailQuery query)
```


Retrieves list of appointments for default calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents appointments search criteria. |

**Returns:**
com.aspose.email.Appointment[] - Returns array of appointments
### listAppointments(MailQuery query, boolean recursive) {#listAppointments-com.aspose.email.MailQuery-boolean-}
```
public abstract Appointment[] listAppointments(MailQuery query, boolean recursive)
```


Retrieves list of appointments for default calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents appointments search criteria. |
| recursive | boolean | Indicates whether recursive listing or not. |

**Returns:**
com.aspose.email.Appointment[] - Returns array of appointments
### listAppointments(String folderUri) {#listAppointments-java.lang.String-}
```
public abstract Appointment[] listAppointments(String folderUri)
```


Retrieves list of appointments for specified calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder to search appointments in. |

**Returns:**
com.aspose.email.Appointment[] - Returns array of appointments
### listAppointments(String folderUri, boolean recursive) {#listAppointments-java.lang.String-boolean-}
```
public abstract Appointment[] listAppointments(String folderUri, boolean recursive)
```


Retrieves list of appointments for specified calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder to search appointments in. |
| recursive | boolean | Indicates whether recursive listing or not. |

**Returns:**
com.aspose.email.Appointment[] - Returns array of appointments
### listAppointments(String folderUri, MailQuery query) {#listAppointments-java.lang.String-com.aspose.email.MailQuery-}
```
public abstract Appointment[] listAppointments(String folderUri, MailQuery query)
```


Retrieves list of appointments for specified calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder to search appointments in. |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents appointments search criteria. |

**Returns:**
com.aspose.email.Appointment[] - Returns array of appointments
### listAppointments(String folderUri, MailQuery query, boolean recursive) {#listAppointments-java.lang.String-com.aspose.email.MailQuery-boolean-}
```
public abstract Appointment[] listAppointments(String folderUri, MailQuery query, boolean recursive)
```


Retrieves list of appointments for specified calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder to search appointments in. |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents appointments search criteria. |
| recursive | boolean | Indicates whether recursive listing or not. |

**Returns:**
com.aspose.email.Appointment[] - Returns array of appointments
### listAppointmentsByPage(MailQuery query, int itemsPerPage) {#listAppointmentsByPage-com.aspose.email.MailQuery-int-}
```
public abstract AppointmentPageInfo listAppointmentsByPage(MailQuery query, int itemsPerPage)
```


Retrieves page with appointments for calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents appointments search criteria. |
| itemsPerPage | int | A number of items in page |

**Returns:**
[AppointmentPageInfo](../../com.aspose.email/appointmentpageinfo) - Returns page with appointments
### listAppointmentsByPage(MailQuery query, int itemsPerPage, int itemOffset) {#listAppointmentsByPage-com.aspose.email.MailQuery-int-int-}
```
public abstract AppointmentPageInfo listAppointmentsByPage(MailQuery query, int itemsPerPage, int itemOffset)
```


Retrieves page with appointments for calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents appointments search criteria. |
| itemsPerPage | int | A number of items in page |
| itemOffset | int | An offset of next item in view |

**Returns:**
[AppointmentPageInfo](../../com.aspose.email/appointmentpageinfo) - Returns page with appointments
### listAppointmentsByPage(int itemsPerPage) {#listAppointmentsByPage-int-}
```
public abstract AppointmentPageInfo listAppointmentsByPage(int itemsPerPage)
```


Retrieves page with appointments for calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| itemsPerPage | int | A number of items in page |

**Returns:**
[AppointmentPageInfo](../../com.aspose.email/appointmentpageinfo) - Returns page with appointments
### listAppointmentsByPage(int itemsPerPage, int itemOffset) {#listAppointmentsByPage-int-int-}
```
public abstract AppointmentPageInfo listAppointmentsByPage(int itemsPerPage, int itemOffset)
```


Retrieves page with appointments for calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| itemsPerPage | int | A number of items in page |
| itemOffset | int | An offset of next item in view |

**Returns:**
[AppointmentPageInfo](../../com.aspose.email/appointmentpageinfo) - Returns page with appointments
### listAppointmentsByPage(String folderUri, MailQuery query, int itemsPerPage) {#listAppointmentsByPage-java.lang.String-com.aspose.email.MailQuery-int-}
```
public abstract AppointmentPageInfo listAppointmentsByPage(String folderUri, MailQuery query, int itemsPerPage)
```


Retrieves page with appointments for specified calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder to search appointments in. |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents appointments search criteria. |
| itemsPerPage | int | A number of items in page |

**Returns:**
[AppointmentPageInfo](../../com.aspose.email/appointmentpageinfo) - Returns page with appointments
### listAppointmentsByPage(String folderUri, MailQuery query, int itemsPerPage, int itemOffset) {#listAppointmentsByPage-java.lang.String-com.aspose.email.MailQuery-int-int-}
```
public abstract AppointmentPageInfo listAppointmentsByPage(String folderUri, MailQuery query, int itemsPerPage, int itemOffset)
```


Retrieves page with appointments for specified calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder to search appointments in. |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents appointments search criteria. |
| itemsPerPage | int | A number of items in page |
| itemOffset | int | An offset of next item in view |

**Returns:**
[AppointmentPageInfo](../../com.aspose.email/appointmentpageinfo) - Returns page with appointments
### listAppointmentsByPage(String folderUri, int itemsPerPage) {#listAppointmentsByPage-java.lang.String-int-}
```
public abstract AppointmentPageInfo listAppointmentsByPage(String folderUri, int itemsPerPage)
```


Retrieves page with appointments for specified calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder to search appointments in. |
| itemsPerPage | int | A number of items in page |

**Returns:**
[AppointmentPageInfo](../../com.aspose.email/appointmentpageinfo) - Returns collection of appointments
### listAppointmentsByPage(String folderUri, int itemsPerPage, int itemOffset) {#listAppointmentsByPage-java.lang.String-int-int-}
```
public abstract AppointmentPageInfo listAppointmentsByPage(String folderUri, int itemsPerPage, int itemOffset)
```


Retrieves page with appointments for specified calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder to search appointments in. |
| itemsPerPage | int | A number of items in page |
| itemOffset | int | An offset of next item in view |

**Returns:**
[AppointmentPageInfo](../../com.aspose.email/appointmentpageinfo) - Returns page with appointments
### listContacts(String folderUri) {#listContacts-java.lang.String-}
```
public abstract MapiContact[] listContacts(String folderUri)
```


Lists contacts located in the specified folder on server

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | The URI of folder |

**Returns:**
com.aspose.email.MapiContact[] - An array of read [MapiContact](../../com.aspose.email/mapicontact) that represents contact information
### listContacts(String folderUri, Iterable<PropertyDescriptor> mapiProperties) {#listContacts-java.lang.String-java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract MapiContact[] listContacts(String folderUri, Iterable<PropertyDescriptor> mapiProperties)
```


Lists contacts located in the specified folder on server

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder to search contacts in |
| mapiProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | Required additional mapi properties |

**Returns:**
com.aspose.email.MapiContact[] - An array of read [MapiContact](../../com.aspose.email/mapicontact) that represents contact information
### listDelegates(String mailbox) {#listDelegates-java.lang.String-}
```
public abstract ExchangeDelegateUserCollection listDelegates(String mailbox)
```


Lists the users who are granted access on the specified mailbox.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | java.lang.String | A mailbox. |

**Returns:**
[ExchangeDelegateUserCollection](../../com.aspose.email/exchangedelegateusercollection) - A [ExchangeDelegateUserCollection](../../com.aspose.email/exchangedelegateusercollection) representing the delegate users.
### listDistributionLists() {#listDistributionLists--}
```
public abstract ExchangeDistributionList[] listDistributionLists()
```


List the private Distribution Lists.

**Returns:**
com.aspose.email.ExchangeDistributionList[] - An array of [ExchangeDistributionList](../../com.aspose.email/exchangedistributionlist) that represents Distribution List information.
### listItems(String folder) {#listItems-java.lang.String-}
```
public abstract String[] listItems(String folder)
```


Retrieve list of item uries in specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | folder to search items |

**Returns:**
java.lang.String[] - Returns list of item uries
### listItems(String folder, MailQuery query) {#listItems-java.lang.String-com.aspose.email.MailQuery-}
```
public abstract String[] listItems(String folder, MailQuery query)
```


Retrieve list of item uries in specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | folder to search items |
| query | [MailQuery](../../com.aspose.email/mailquery) | Additional conditions to select items |

**Returns:**
java.lang.String[] - Returns list of item uries
### listItems(String folder, MailQuery query, boolean recursive) {#listItems-java.lang.String-com.aspose.email.MailQuery-boolean-}
```
public abstract String[] listItems(String folder, MailQuery query, boolean recursive)
```


Retrieve list of item uries in specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | folder to search items |
| query | [MailQuery](../../com.aspose.email/mailquery) | Additional conditions to select items |
| recursive | boolean | Specifies whether request should be reqursive. |

**Returns:**
java.lang.String[] - Returns list of item uries
### listItems(String mailbox, String folder) {#listItems-java.lang.String-java.lang.String-}
```
public abstract String[] listItems(String mailbox, String folder)
```


Retrieve list of item uries in specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | java.lang.String | The mailbox that is used to initialize the folder id class. |
| folder | java.lang.String | folder to search items |

**Returns:**
java.lang.String[] - Returns list of item uries
### listItems(String mailbox, String folder, MailQuery query) {#listItems-java.lang.String-java.lang.String-com.aspose.email.MailQuery-}
```
public abstract String[] listItems(String mailbox, String folder, MailQuery query)
```


Retrieve list of item uries in specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | java.lang.String | The mailbox that is used to initialize the folder id class. |
| folder | java.lang.String | folder to search items |
| query | [MailQuery](../../com.aspose.email/mailquery) | Additional conditions to select items |

**Returns:**
java.lang.String[] - Returns list of item uries
### listItems(String mailbox, String folder, MailQuery query, boolean recursive) {#listItems-java.lang.String-java.lang.String-com.aspose.email.MailQuery-boolean-}
```
public abstract String[] listItems(String mailbox, String folder, MailQuery query, boolean recursive)
```


Retrieve list of item uries in specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | java.lang.String | The mailbox that is used to initialize the folder id class. |
| folder | java.lang.String | folder to search items |
| query | [MailQuery](../../com.aspose.email/mailquery) | Additional conditions to select items |
| recursive | boolean | Specifies whether request should be reqursive. |

**Returns:**
java.lang.String[] - Returns list of item uries
### listMailboxes() {#listMailboxes--}
```
public abstract MapiContactCollection listMailboxes()
```


Lists mailboxes.

**Returns:**
[MapiContactCollection](../../com.aspose.email/mapicontactcollection) - A [MapiContactCollection](../../com.aspose.email/mapicontactcollection) that represents contact information.
### listMailboxes(String filter) {#listMailboxes-java.lang.String-}
```
public abstract MapiContactCollection listMailboxes(String filter)
```


Please pay your attention, this overridden method works with Exchange Server 2013 and higher. Lists mailboxes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filter | java.lang.String | filter string |

**Returns:**
[MapiContactCollection](../../com.aspose.email/mapicontactcollection) - A [MapiContactCollection](../../com.aspose.email/mapicontactcollection) that represents contact information.
### listMessages() {#listMessages--}
```
public abstract ExchangeMessageInfoCollection listMessages()
```


List the messages in the inbox folder.

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) from inbox folder.
### listMessages(Iterable<String> iDs) {#listMessages-java.lang.Iterable-java.lang.String--}
```
public abstract ExchangeMessageInfoCollection listMessages(Iterable<String> iDs)
```


List the messages in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| iDs | java.lang.Iterable<java.lang.String> | Enumeration of message ids |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages with.
### listMessages(String folder) {#listMessages-java.lang.String-}
```
public abstract ExchangeMessageInfoCollection listMessages(String folder)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder. |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - A [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection)
### listMessages(String folder, boolean recursive) {#listMessages-java.lang.String-boolean-}
```
public abstract ExchangeMessageInfoCollection listMessages(String folder, boolean recursive)
```


List the messages in the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search messages in |
| recursive | boolean | Indicates whether recursive listing or not |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder
### listMessages(String folder, MailQuery query) {#listMessages-java.lang.String-com.aspose.email.MailQuery-}
```
public abstract ExchangeMessageInfoCollection listMessages(String folder, MailQuery query)
```


List the messages in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search messages in. |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents message search criteria. |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder.
### listMessages(String folder, MailQuery query, boolean recursive) {#listMessages-java.lang.String-com.aspose.email.MailQuery-boolean-}
```
public abstract ExchangeMessageInfoCollection listMessages(String folder, MailQuery query, boolean recursive)
```


List the messages in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search messages in. |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents message search criteria. |
| recursive | boolean | Indicates whether recursive listing or not. |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder.
### listMessages(String folder, int maxNumberOfMessages) {#listMessages-java.lang.String-int-}
```
public abstract ExchangeMessageInfoCollection listMessages(String folder, int maxNumberOfMessages)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder. |
| maxNumberOfMessages | int | Maximum number of messages |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - A [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection)
### listMessages(String folder, int maxNumberOfMessages, MailQuery query) {#listMessages-java.lang.String-int-com.aspose.email.MailQuery-}
```
public abstract ExchangeMessageInfoCollection listMessages(String folder, int maxNumberOfMessages, MailQuery query)
```


List the messages in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search messages in. |
| maxNumberOfMessages | int | Maximum number of messages. |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents message search criteria. |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder.
### listMessages(String folder, int maxNumberOfMessages, MailQuery query, boolean recursive) {#listMessages-java.lang.String-int-com.aspose.email.MailQuery-boolean-}
```
public abstract ExchangeMessageInfoCollection listMessages(String folder, int maxNumberOfMessages, MailQuery query, boolean recursive)
```


List the messages in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search messages in. |
| maxNumberOfMessages | int | Maximum number of messages. |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents message search criteria. |
| recursive | boolean | Indicates whether recursive listing or not. |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder.
### listMessages(String mailbox, String folder, boolean recursive) {#listMessages-java.lang.String-java.lang.String-boolean-}
```
public abstract ExchangeMessageInfoCollection listMessages(String mailbox, String folder, boolean recursive)
```


List the messages in the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | java.lang.String | The mailbox that is used to initialize the folder id class. |
| folder | java.lang.String | A folder to search messages in |
| recursive | boolean | Indicates whether recursive listing or not |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder
### listMessages(String mailbox, String folder, MailQuery query) {#listMessages-java.lang.String-java.lang.String-com.aspose.email.MailQuery-}
```
public abstract ExchangeMessageInfoCollection listMessages(String mailbox, String folder, MailQuery query)
```


List the messages in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | java.lang.String | The mailbox that is used to initialize the folder id class. |
| folder | java.lang.String | A folder to search messages in. |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents message search criteria. |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder.
### listMessagesByMaxNumberOfMessages(String folder, int maxNumberOfMessages) {#listMessagesByMaxNumberOfMessages-java.lang.String-int-}
```
public abstract ExchangeMessageInfoCollection listMessagesByMaxNumberOfMessages(String folder, int maxNumberOfMessages)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder. |
| maxNumberOfMessages | int | Maximum number of messages |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - A [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection)
### listMessagesByOption(String folder, int options) {#listMessagesByOption-java.lang.String-int-}
```
public abstract ExchangeMessageInfoCollection listMessagesByOption(String folder, int options)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder. |
| options | int | Specifies the settings of listing |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - A [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection)
### listMessagesByOption(String folder, int maxNumberOfMessages, int options) {#listMessagesByOption-java.lang.String-int-int-}
```
public abstract ExchangeMessageInfoCollection listMessagesByOption(String folder, int maxNumberOfMessages, int options)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder. |
| maxNumberOfMessages | int | Maximum number of messages |
| options | int | Specifies the settings of listing |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - A  ExchangeMessageInfoCollection 
### listMessagesByPage(String folder, MailQuery query, int itemsPerPage) {#listMessagesByPage-java.lang.String-com.aspose.email.MailQuery-int-}
```
public abstract ExchangeMessagePageInfo listMessagesByPage(String folder, MailQuery query, int itemsPerPage)
```


List the messages in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search messages in. |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents search criteria. |
| itemsPerPage | int | A number of items in page |

**Returns:**
[ExchangeMessagePageInfo](../../com.aspose.email/exchangemessagepageinfo) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder.
### listMessagesByPage(String folder, MailQuery query, int itemsPerPage, int offset) {#listMessagesByPage-java.lang.String-com.aspose.email.MailQuery-int-int-}
```
public abstract ExchangeMessagePageInfo listMessagesByPage(String folder, MailQuery query, int itemsPerPage, int offset)
```


List the messages in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search messages in. |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery) that represents search criteria. |
| itemsPerPage | int | A number of items in page |
| offset | int | An offset of next page in view |

**Returns:**
[ExchangeMessagePageInfo](../../com.aspose.email/exchangemessagepageinfo) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder.
### listMessagesByPage(String folder, PageInfo pageInfo) {#listMessagesByPage-java.lang.String-com.aspose.email.PageInfo-}
```
public abstract ExchangeMessagePageInfo listMessagesByPage(String folder, PageInfo pageInfo)
```


List the messages in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search messages in. |
| pageInfo | [PageInfo](../../com.aspose.email/pageinfo) | A page info |

**Returns:**
[ExchangeMessagePageInfo](../../com.aspose.email/exchangemessagepageinfo) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder.
### listMessagesByPage(String folder, PageInfo pageInfo, int options) {#listMessagesByPage-java.lang.String-com.aspose.email.PageInfo-int-}
```
public abstract ExchangeMessagePageInfo listMessagesByPage(String folder, PageInfo pageInfo, int options)
```


List the messages in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search messages in. |
| pageInfo | [PageInfo](../../com.aspose.email/pageinfo) | A page info |
| options | int | Specifies the settings of listing |

**Returns:**
[ExchangeMessagePageInfo](../../com.aspose.email/exchangemessagepageinfo) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder.
### listMessagesByPage(String folder, int itemsPerPage) {#listMessagesByPage-java.lang.String-int-}
```
public abstract ExchangeMessagePageInfo listMessagesByPage(String folder, int itemsPerPage)
```


List the messages in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search messages in. |
| itemsPerPage | int | A number of items in page |

**Returns:**
[ExchangeMessagePageInfo](../../com.aspose.email/exchangemessagepageinfo) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder.
### listMessagesByPage(String folder, int itemsPerPage, int offset) {#listMessagesByPage-java.lang.String-int-int-}
```
public abstract ExchangeMessagePageInfo listMessagesByPage(String folder, int itemsPerPage, int offset)
```


List the messages in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search messages in. |
| itemsPerPage | int | A number of items in page |
| offset | int | An offset of next page in view |

**Returns:**
[ExchangeMessagePageInfo](../../com.aspose.email/exchangemessagepageinfo) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder.
### listMessagesByPage(String folder, int itemsPerPage, int pageOffset, int options) {#listMessagesByPage-java.lang.String-int-int-int-}
```
public abstract ExchangeMessagePageInfo listMessagesByPage(String folder, int itemsPerPage, int pageOffset, int options)
```


List the messages in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search messages in. |
| itemsPerPage | int | A number of items in page |
| pageOffset | int | An offset of next item in view |
| options | int | Specifies the settings of listing |

**Returns:**
[ExchangeMessagePageInfo](../../com.aspose.email/exchangemessagepageinfo) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder.
### listMessagesByPropertyDescriptor(String folder, int options, Iterable<PropertyDescriptor> extendedProperties) {#listMessagesByPropertyDescriptor-java.lang.String-int-java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract ExchangeMessageInfoCollection listMessagesByPropertyDescriptor(String folder, int options, Iterable<PropertyDescriptor> extendedProperties)
```


List the messages in the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to search messages in |
| options | int | Specifies the settings of listing |
| extendedProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | Extended properties of retrieved messages |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder
### listMessagesFromPublicFolder(ExchangeFolderInfo folder) {#listMessagesFromPublicFolder-com.aspose.email.ExchangeFolderInfo-}
```
public abstract ExchangeMessageInfoCollection listMessagesFromPublicFolder(ExchangeFolderInfo folder)
```


Get collection of messages from public folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | [ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) | [ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) that represents information about folder |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder
### listMessagesFromPublicFolder(String folderUri) {#listMessagesFromPublicFolder-java.lang.String-}
```
public abstract ExchangeMessageInfoCollection listMessagesFromPublicFolder(String folderUri)
```


Get collection of messages from public folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | The uri of folder |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) that contains messages from the specified folder
### listPublicFolders() {#listPublicFolders--}
```
public abstract ExchangeFolderInfoCollection listPublicFolders()
```


Gets collection of public folders from root public folder

**Returns:**
[ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) - [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) that contains subfolders from the root public folder
### listSubFolders(ExchangeFolderInfo parentFolder) {#listSubFolders-com.aspose.email.ExchangeFolderInfo-}
```
public abstract ExchangeFolderInfoCollection listSubFolders(ExchangeFolderInfo parentFolder)
```


Gets collection of child public folders from parent

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | [ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) | The parent [ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) |

**Returns:**
[ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) - [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) that contains subfolders from the parent folder
### listSubFolders(String parentFolderUri) {#listSubFolders-java.lang.String-}
```
public abstract ExchangeFolderInfoCollection listSubFolders(String parentFolderUri)
```


Gets collection of child folders from parent

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | The uri of the parent folder |

**Returns:**
[ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) - [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) that contains subfolders from the parent folder
### listSubFolders(String mailbox, String parentFolderUri) {#listSubFolders-java.lang.String-java.lang.String-}
```
public abstract ExchangeFolderInfoCollection listSubFolders(String mailbox, String parentFolderUri)
```


Gets collection of child folders from parent

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | java.lang.String | The mailbox that is used to initialize the folder id class. |
| parentFolderUri | java.lang.String | A parent folder |

**Returns:**
[ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) - [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) that contains subfolders from the parent folder
### listSubFoldersByPage(String parentFolderUri, PageInfo page) {#listSubFoldersByPage-java.lang.String-com.aspose.email.PageInfo-}
```
public abstract ExchangeFolderPageInfo listSubFoldersByPage(String parentFolderUri, PageInfo page)
```


Searches the specified folder in the given parent folder with paging Method supports paging.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | A parent folder URI |
| page | [PageInfo](../../com.aspose.email/pageinfo) | A page info |

**Returns:**
[ExchangeFolderPageInfo](../../com.aspose.email/exchangefolderpageinfo) - A [ExchangeFolderPageInfo](../../com.aspose.email/exchangefolderpageinfo) containing the found folder if folder name is specified; otherwise, returns all subfolders
### listSubFoldersByPage(String parentFolderUri, int itemsPerPage) {#listSubFoldersByPage-java.lang.String-int-}
```
public abstract ExchangeFolderPageInfo listSubFoldersByPage(String parentFolderUri, int itemsPerPage)
```


Searches the specified folder in the given parent folder with paging Method supports paging. Invokes for the first time in paging cycle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | A parent folder URI |
| itemsPerPage | int | A number of folders in page |

**Returns:**
[ExchangeFolderPageInfo](../../com.aspose.email/exchangefolderpageinfo) - A [ExchangeFolderPageInfo](../../com.aspose.email/exchangefolderpageinfo) containing the found folder if folder name is specified; otherwise, returns all subfolders
### listSubFoldersByPage(String parentFolderUri, int itemsPerPage, int pageOffset) {#listSubFoldersByPage-java.lang.String-int-int-}
```
public abstract ExchangeFolderPageInfo listSubFoldersByPage(String parentFolderUri, int itemsPerPage, int pageOffset)
```


Searches the specified folder in the given parent folder with paging Method supports paging.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | A parent folder URI |
| itemsPerPage | int | A number of folders in page |
| pageOffset | int | An offset of next item in view |

**Returns:**
[ExchangeFolderPageInfo](../../com.aspose.email/exchangefolderpageinfo) - A [ExchangeFolderPageInfo](../../com.aspose.email/exchangefolderpageinfo) containing the found folder if folder name is specified; otherwise, returns all subfolders
### listTasks() {#listTasks--}
```
public abstract TaskCollection listTasks()
```


Retrieves lists of exchange tasks for default folder.

**Returns:**
[TaskCollection](../../com.aspose.email/taskcollection) - Tasks collection
### listTasks(String folder) {#listTasks-java.lang.String-}
```
public abstract TaskCollection listTasks(String folder)
```


Retrieves lists of exchange tasks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | Tasks folder |

**Returns:**
[TaskCollection](../../com.aspose.email/taskcollection) - Tasks collection
### listTasks(String folder, MailQuery query) {#listTasks-java.lang.String-com.aspose.email.MailQuery-}
```
public abstract TaskCollection listTasks(String folder, MailQuery query)
```


Retrieves lists of exchange tasks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | Tasks folder |
| query | [MailQuery](../../com.aspose.email/mailquery) | Mail query |

**Returns:**
[TaskCollection](../../com.aspose.email/taskcollection) - Tasks collection
### listTasks(String folder, int maxNumberOfItems) {#listTasks-java.lang.String-int-}
```
public abstract TaskCollection listTasks(String folder, int maxNumberOfItems)
```


Retrieves lists of exchange tasks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | Tasks folder |
| maxNumberOfItems | int | Maximum number of items |

**Returns:**
[TaskCollection](../../com.aspose.email/taskcollection) - Tasks collection
### listTasks(String folder, int maxNumberOfItems, MailQuery query) {#listTasks-java.lang.String-int-com.aspose.email.MailQuery-}
```
public abstract TaskCollection listTasks(String folder, int maxNumberOfItems, MailQuery query)
```


Retrieves lists of exchange tasks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | Tasks folder |
| maxNumberOfItems | int | Maximum number of items |
| query | [MailQuery](../../com.aspose.email/mailquery) | Mail query |

**Returns:**
[TaskCollection](../../com.aspose.email/taskcollection) - Tasks collection
### listTasks(String folder, int maxNumberOfItems, MailQuery query, boolean recursive) {#listTasks-java.lang.String-int-com.aspose.email.MailQuery-boolean-}
```
public abstract TaskCollection listTasks(String folder, int maxNumberOfItems, MailQuery query, boolean recursive)
```


Retrieves lists of exchange tasks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | Tasks folder |
| maxNumberOfItems | int | Maximum number of items |
| query | [MailQuery](../../com.aspose.email/mailquery) | Mail query |
| recursive | boolean | Retrieve tasks recursivly |

**Returns:**
[TaskCollection](../../com.aspose.email/taskcollection) - Tasks collection
### loadContactPhoto(ContactPhoto photo) {#loadContactPhoto-com.aspose.email.ContactPhoto-}
```
public abstract void loadContactPhoto(ContactPhoto photo)
```


Loads contact photo binary data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| photo | [ContactPhoto](../../com.aspose.email/contactphoto) | contact photo |

### mailDisablePublicFolder(String folderUri) {#mailDisablePublicFolder-java.lang.String-}
```
public abstract void mailDisablePublicFolder(String folderUri)
```


Mail-disable a public folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder uri |

### mailEnablePublicFolder(String folderUri) {#mailEnablePublicFolder-java.lang.String-}
```
public abstract void mailEnablePublicFolder(String folderUri)
```


Mail-enable a public folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder uri |

### markAllItems(boolean read, boolean suppressReadReceipts, Iterable<String> folderIds) {#markAllItems-boolean-boolean-java.lang.Iterable-java.lang.String--}
```
public abstract void markAllItems(boolean read, boolean suppressReadReceipts, Iterable<String> folderIds)
```


Marks all items in specified folders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| read | boolean | Sets the read/unread state to messages in specified folder. True to mark messages in the folder as read. False to mark messages as unread. |
| suppressReadReceipts | boolean | True to suppress sending read receipts for messages; otherwise, false. |
| folderIds | java.lang.Iterable<java.lang.String> | List of folder uri for processing. |

### markAllItems(boolean read, boolean suppressReadReceipts, String[] folderIds) {#markAllItems-boolean-boolean-java.lang.String...-}
```
public abstract void markAllItems(boolean read, boolean suppressReadReceipts, String[] folderIds)
```


Marks all items in specified folders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| read | boolean | Sets the read/unread state to messages in specified folder. True to mark messages in the folder as read. False to mark messages as unread. |
| suppressReadReceipts | boolean | True to suppress sending read receipts for messages; otherwise, false. |
| folderIds | java.lang.String[] | List of folder uri for processing. |

### markAllItems(boolean read, String[] folderIds) {#markAllItems-boolean-java.lang.String...-}
```
public abstract void markAllItems(boolean read, String[] folderIds)
```


Marks all items in specified folders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| read | boolean | Sets the read/unread state to messages in specified folder. True to mark messages in the folder as read. False to mark messages as unread. |
| folderIds | java.lang.String[] | List of folder uri for processing. |

### markAllItemsAsRead() {#markAllItemsAsRead--}
```
public abstract void markAllItemsAsRead()
```


Marks all items in inbox folder as read without receipts.

### markAllItemsAsRead(Iterable<String> folderIds) {#markAllItemsAsRead-java.lang.Iterable-java.lang.String--}
```
public abstract void markAllItemsAsRead(Iterable<String> folderIds)
```


Marks all items in specified folders as read without receipts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderIds | java.lang.Iterable<java.lang.String> | List of folder uri for processing. |

### markAllItemsAsRead(String[] folderIds) {#markAllItemsAsRead-java.lang.String...-}
```
public abstract void markAllItemsAsRead(String[] folderIds)
```


Marks all items in specified folders as read without receipts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderIds | java.lang.String[] | List of folder uri for processing. |

### markAllItemsAsUnread() {#markAllItemsAsUnread--}
```
public abstract void markAllItemsAsUnread()
```


Marks all items in inbox folder as unread.

### markAllItemsAsUnread(Iterable<String> folderIds) {#markAllItemsAsUnread-java.lang.Iterable-java.lang.String--}
```
public abstract void markAllItemsAsUnread(Iterable<String> folderIds)
```


Marks all items in specified folders as unread.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderIds | java.lang.Iterable<java.lang.String> | List of folder uri for processing. |

### markAllItemsAsUnread(String[] folderIds) {#markAllItemsAsUnread-java.lang.String...-}
```
public abstract void markAllItemsAsUnread(String[] folderIds)
```


Marks all items in specified folders as unread.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderIds | java.lang.String[] | List of folder uri for processing. |

### markAsJunk(boolean isJunk, boolean moveItem, Iterable<String> messageUriEn) {#markAsJunk-boolean-boolean-java.lang.Iterable-java.lang.String--}
```
public abstract String[] markAsJunk(boolean isJunk, boolean moveItem, Iterable<String> messageUriEn)
```


The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isJunk | boolean | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| moveItem | boolean | Indicates, whether messages is moved to the junk mail folder. |
| messageUriEn | java.lang.Iterable<java.lang.String> | Enumeration of message uri |

**Returns:**
java.lang.String[] - Returns the array of message ID which are moved to the junk mail folder.
### markAsJunk(boolean isJunk, boolean moveItem, Iterable<String> messageUriEn, String[][] movedMessageIds, String[][] failedMessageIds, String[][] errorMessages) {#markAsJunk-boolean-boolean-java.lang.Iterable-java.lang.String--java.lang.String-----java.lang.String-----java.lang.String-----}
```
public abstract void markAsJunk(boolean isJunk, boolean moveItem, Iterable<String> messageUriEn, String[][] movedMessageIds, String[][] failedMessageIds, String[][] errorMessages)
```


The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isJunk | boolean | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| moveItem | boolean | Indicates, whether messages is moved to the junk mail folder. |
| messageUriEn | java.lang.Iterable<java.lang.String> | Enumeration of message uri |
| movedMessageIds | java.lang.String[][] | Returns the array of message ID which are moved to the junk mail folder. |
| failedMessageIds | java.lang.String[][] | Returns the array of message ID which haven't been moved to the junk mail folder. |
| errorMessages | java.lang.String[][] | Error messages for failed operations |

### markAsJunk(boolean isJunk, boolean moveItem, String[] messageUriEn) {#markAsJunk-boolean-boolean-java.lang.String...-}
```
public abstract String[] markAsJunk(boolean isJunk, boolean moveItem, String[] messageUriEn)
```


The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isJunk | boolean | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| moveItem | boolean | Indicates, whether messages is moved to the junk mail folder. |
| messageUriEn | java.lang.String[] | Array of message uri |

**Returns:**
java.lang.String[] - Returns the array of message ID which are moved to the junk mail folder.
### markAsJunk(boolean isJunk, Iterable<String> messageUriEn) {#markAsJunk-boolean-java.lang.Iterable-java.lang.String--}
```
public abstract String[] markAsJunk(boolean isJunk, Iterable<String> messageUriEn)
```


The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isJunk | boolean | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| messageUriEn | java.lang.Iterable<java.lang.String> | Enumeration of message uri |

**Returns:**
java.lang.String[] - Returns the item ID of the message marked as junk mail.
### markAsJunk(boolean isJunk, String[] messageUriEn) {#markAsJunk-boolean-java.lang.String...-}
```
public abstract String[] markAsJunk(boolean isJunk, String[] messageUriEn)
```


The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isJunk | boolean | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| messageUriEn | java.lang.String[] | Array of message uri |

**Returns:**
java.lang.String[] - Returns the array of message ID which are moved to the junk mail folder.
### moveConversationItems(String conversationId, String destinationFolderId) {#moveConversationItems-java.lang.String-java.lang.String-}
```
public abstract void moveConversationItems(String conversationId, String destinationFolderId)
```


Moves the conversation items into the specified target folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | java.lang.String | Id of conversation to delete |
| destinationFolderId | java.lang.String | Id of folder into which move items |

### moveConversationItems(String conversationId, String contextFolderId, String destinationFolderId) {#moveConversationItems-java.lang.String-java.lang.String-java.lang.String-}
```
public abstract void moveConversationItems(String conversationId, String contextFolderId, String destinationFolderId)
```


Moves the conversation items, which are located in the specified folder, into the specified target folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | java.lang.String | Id of conversation to move |
| contextFolderId | java.lang.String | Id of folder from which move conversation items. Note: If it's set to null(or empty), all conversation items will be moved |
| destinationFolderId | java.lang.String | Id of folder into which move items |

### moveItem(String itemUri, String destinationFolderUri) {#moveItem-java.lang.String-java.lang.String-}
```
public abstract String moveItem(String itemUri, String destinationFolderUri)
```


Moves the item to specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| itemUri | java.lang.String | The item URI |
| destinationFolderUri | java.lang.String | The destination folder URI |

**Returns:**
java.lang.String - An uri of the moved message
### playOnPhone(String messageId, String dialString) {#playOnPhone-java.lang.String-java.lang.String-}
```
public abstract String playOnPhone(String messageId, String dialString)
```


The PlayOnPhone operation initiates an outbound call and plays a message over the telephone.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageId | java.lang.String | Specifies message id. |
| dialString | java.lang.String | Specifies telephone to play message. |

**Returns:**
java.lang.String - Returns phone call id
### removeHeader(String name) {#removeHeader-java.lang.String-}
```
public abstract void removeHeader(String name)
```


Remove WebHeader from WebHeaderCollection in EWS request.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Header name |

### reply(MailMessage message, ExchangeMessageInfo referencedMessage) {#reply-com.aspose.email.MailMessage-com.aspose.email.ExchangeMessageInfo-}
```
public abstract void reply(MailMessage message, ExchangeMessageInfo referencedMessage)
```


Reply to the sender's message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The [MailMessage](../../com.aspose.email/mailmessage) that represents the precomposed reply message. |
| referencedMessage | [ExchangeMessageInfo](../../com.aspose.email/exchangemessageinfo) | The [ExchangeMessageInfo](../../com.aspose.email/exchangemessageinfo) that represents the original message. |

### reply(MailMessage message, String referencedUri) {#reply-com.aspose.email.MailMessage-java.lang.String-}
```
public abstract void reply(MailMessage message, String referencedUri)
```


Reply to the sender's message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The [MailMessage](../../com.aspose.email/mailmessage) that represents the precomposed reply message. |
| referencedUri | java.lang.String | The URI that represents the original message. |

### replyAll(MailMessage message, ExchangeMessageInfo referencedMessage) {#replyAll-com.aspose.email.MailMessage-com.aspose.email.ExchangeMessageInfo-}
```
public abstract void replyAll(MailMessage message, ExchangeMessageInfo referencedMessage)
```


Reply to the sender and all recipients of a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The [MailMessage](../../com.aspose.email/mailmessage) that represents the precomposed reply message. |
| referencedMessage | [ExchangeMessageInfo](../../com.aspose.email/exchangemessageinfo) | The [ExchangeMessageInfo](../../com.aspose.email/exchangemessageinfo) that represents the original message. |

### resetImpersonation() {#resetImpersonation--}
```
public abstract void resetImpersonation()
```


Makes the impersonation reset.

### resetSubscription() {#resetSubscription--}
```
public abstract void resetSubscription()
```


Reset all subscriptions

### resolveContact(String unresolvedEntry) {#resolveContact-java.lang.String-}
```
public abstract MapiContactCollection resolveContact(String unresolvedEntry)
```


Resolves ambiguous mailbox names.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unresolvedEntry | java.lang.String | A name of contact to resolve. |

**Returns:**
[MapiContactCollection](../../com.aspose.email/mapicontactcollection) - A [MapiContactCollection](../../com.aspose.email/mapicontactcollection) that represents contacts information.
### resolveContacts(String unresolvedEntry) {#resolveContacts-java.lang.String-}
```
public abstract Contact[] resolveContacts(String unresolvedEntry)
```


Resolves ambiguous mailbox display names. Note: the maximum count of returned contacts is 100. This is a restriction of used exchange command.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unresolvedEntry | java.lang.String | A name of contact to resolve. |

**Returns:**
com.aspose.email.Contact[] - An array of [Contact](../../com.aspose.email/contact) objects.
### resolveContacts(String unresolvedEntry, int options) {#resolveContacts-java.lang.String-int-}
```
public abstract Contact[] resolveContacts(String unresolvedEntry, int options)
```


Resolves ambiguous e-mail addresses and display names Note: the maximum count of returned contacts is 100. This is a restriction of used EWS operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unresolvedEntry | java.lang.String | A name of contact to resolve |
| options | int | Enumerates the list contacts options |

**Returns:**
com.aspose.email.Contact[] - Contacts that represents contacts information
### restore(PersonalStorage pst, RestoreSettings settings) {#restore-com.aspose.email.PersonalStorage-com.aspose.email.RestoreSettings-}
```
public abstract void restore(PersonalStorage pst, RestoreSettings settings)
```


Restores the specified exchange folders from the given personal storage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pst | [PersonalStorage](../../com.aspose.email/personalstorage) | A personal storage containing the backuped exchange folders. |
| settings | [RestoreSettings](../../com.aspose.email/restoresettings) | The restore settings. |

### saveMessage(String messageUri, OutputStream stream) {#saveMessage-java.lang.String-java.io.OutputStream-}
```
public abstract void saveMessage(String messageUri, OutputStream stream)
```


Saves the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | The message URI. |
| stream | java.io.OutputStream | The stream. |

### saveMessage(String messageUri, String path) {#saveMessage-java.lang.String-java.lang.String-}
```
public abstract void saveMessage(String messageUri, String path)
```


Saves the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | The message URI. |
| path | java.lang.String | The path to save message. |

### saveMessageInternal(String messageUri, System.IO.Stream stream) {#saveMessageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public abstract void saveMessageInternal(String messageUri, System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String |  |
| stream | com.aspose.ms.System.IO.Stream |  |

### send(MailMessage message) {#send-com.aspose.email.MailMessage-}
```
public abstract void send(MailMessage message)
```


Sends the specified message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message. |

### send(MailMessage message, FollowUpOptions messageOptions) {#send-com.aspose.email.MailMessage-com.aspose.email.FollowUpOptions-}
```
public abstract void send(MailMessage message, FollowUpOptions messageOptions)
```


Sends the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The [MailMessage](../../com.aspose.email/mailmessage) to be sent. |
| messageOptions | [FollowUpOptions](../../com.aspose.email/followupoptions) | The [FollowUpOptions](../../com.aspose.email/followupoptions) that represents additional options for using follow-up flags and voting buttons. |

### send(String from, String to, String subject, String body) {#send-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public abstract void send(String from, String to, String subject, String body)
```


Sends the specified message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| from | java.lang.String | From address |
| to | java.lang.String | To address |
| subject | java.lang.String | The subject of message |
| body | java.lang.String | The body of message |

### setCalendarFolderEventFilter(int value) {#setCalendarFolderEventFilter-int-}
```
public abstract void setCalendarFolderEventFilter(int value)
```


Specifies event types for Calendar folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setContactsFolderEventFilter(int value) {#setContactsFolderEventFilter-int-}
```
public abstract void setContactsFolderEventFilter(int value)
```


Specifies event types for Contacts folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setConversationReadState(String conversationId, boolean isRead) {#setConversationReadState-java.lang.String-boolean-}
```
public abstract void setConversationReadState(String conversationId, boolean isRead)
```


Set read state of the conversation items to the specified value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | java.lang.String | Id of conversation to be changed |
| isRead | boolean | A flag that enables setting the read state of items in a conversation. |

### setConversationReadState(String conversationId, String contextFolderId, boolean isRead) {#setConversationReadState-java.lang.String-java.lang.String-boolean-}
```
public abstract void setConversationReadState(String conversationId, String contextFolderId, boolean isRead)
```


Set read state of the conversation items, which are located in the specified folder, to the specified value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | java.lang.String | Id of conversation to be changed |
| contextFolderId | java.lang.String | Id of folder in which conversation items are located. Note: If it's set to null(or empty), all conversation items will be copied |
| isRead | boolean | A flag that enables setting the read state of items in a conversation. |

### setCurrentCalendarFolderUri(String value) {#setCurrentCalendarFolderUri-java.lang.String-}
```
public abstract void setCurrentCalendarFolderUri(String value)
```


Gets or sets current calendar folder uri

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDeletedItemsFolderEventFilter(int value) {#setDeletedItemsFolderEventFilter-int-}
```
public abstract void setDeletedItemsFolderEventFilter(int value)
```


Specifies event types for DeletedItems folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDraftsFolderEventFilter(int value) {#setDraftsFolderEventFilter-int-}
```
public abstract void setDraftsFolderEventFilter(int value)
```


Specifies event types for Drafts folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEnableDecompression(boolean value) {#setEnableDecompression-boolean-}
```
public abstract void setEnableDecompression(boolean value)
```


Gets or sets a value that indicates whether decompression is enabled

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setInboxFolderEventFilter(int value) {#setInboxFolderEventFilter-int-}
```
public abstract void setInboxFolderEventFilter(int value)
```


Specifies event types for Inbox folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setJournalFolderEventFilter(int value) {#setJournalFolderEventFilter-int-}
```
public abstract void setJournalFolderEventFilter(int value)
```


Specifies event types for Journal folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLogFileName(String value) {#setLogFileName-java.lang.String-}
```
public abstract void setLogFileName(String value)
```


Gets or sets log file name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMailboxUri(String value) {#setMailboxUri-java.lang.String-}
```
public abstract void setMailboxUri(String value)
```


Gets or sets the mailbox uri.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNotesFolderEventFilter(int value) {#setNotesFolderEventFilter-int-}
```
public abstract void setNotesFolderEventFilter(int value)
```


Specifies event types for Notes folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setNotificationTimeout(int value) {#setNotificationTimeout-int-}
```
public abstract void setNotificationTimeout(int value)
```


Defines timeout for server notifications

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setNotificationsCheckInterval(int value) {#setNotificationsCheckInterval-int-}
```
public abstract void setNotificationsCheckInterval(int value)
```


Defines interval for notification check

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setOutboxFolderEventFilter(int value) {#setOutboxFolderEventFilter-int-}
```
public abstract void setOutboxFolderEventFilter(int value)
```


Specifies event types for Outbox folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setReadFlag(String messageUri) {#setReadFlag-java.lang.String-}
```
public abstract void setReadFlag(String messageUri)
```


Sets the read flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | The message URI. |

### setReadFlag(String messageUri, boolean isRead) {#setReadFlag-java.lang.String-boolean-}
```
public abstract void setReadFlag(String messageUri, boolean isRead)
```


Marks the specifeid message as read.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | A message uri. |
| isRead | boolean | A value indicating whether the message was read |

### setReconnectCount(int value) {#setReconnectCount-int-}
```
public abstract void setReconnectCount(int value)
```


Gets or sets the number of reconnect attempts at connection breaks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setReturnClientRequestId(boolean value) {#setReturnClientRequestId-boolean-}
```
public abstract void setReturnClientRequestId(boolean value)
```


Gets or sets a flag to indicate whether the client requires the server side to return the request id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRootFolderEventFilter(int value) {#setRootFolderEventFilter-int-}
```
public abstract void setRootFolderEventFilter(int value)
```


Specifies event types for Root folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSentItemsFolderEventFilter(int value) {#setSentItemsFolderEventFilter-int-}
```
public abstract void setSentItemsFolderEventFilter(int value)
```


Specifies event types for SentItems folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTasksFolderEventFilter(int value) {#setTasksFolderEventFilter-int-}
```
public abstract void setTasksFolderEventFilter(int value)
```


Specifies event types for Tasks folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTimezoneId(String value) {#setTimezoneId-java.lang.String-}
```
public abstract void setTimezoneId(String value)
```


Gets or sets timezone id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setUseDateInLogFileName(boolean value) {#setUseDateInLogFileName-boolean-}
```
public abstract void setUseDateInLogFileName(boolean value)
```


Gets or sets value which indicates if date has to be used in log file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUseSlashAsFolderSeparator(boolean value) {#setUseSlashAsFolderSeparator-boolean-}
```
public abstract void setUseSlashAsFolderSeparator(boolean value)
```


Gets or sets value that determines whether the slash '/' is used as folder separator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### syncFolder(SyncState syncState) {#syncFolder-com.aspose.email.SyncState-}
```
public abstract SyncFolderResult syncFolder(SyncState syncState)
```


Retrieves changes of the items in a specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| syncState | [SyncState](../../com.aspose.email/syncstate) | The synchronization state. |

**Returns:**
[SyncFolderResult](../../com.aspose.email/syncfolderresult) - Returns result of SyncFolder operation.
### syncFolder(String folderUri) {#syncFolder-java.lang.String-}
```
public abstract SyncFolderResult syncFolder(String folderUri)
```


Retrieves changes of the items and subfolders in a specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | The folder uri |

**Returns:**
[SyncFolderResult](../../com.aspose.email/syncfolderresult) - Returns result of SyncFolder operation.
### syncFolder(String folderUri, int syncType) {#syncFolder-java.lang.String-int-}
```
public abstract SyncFolderResult syncFolder(String folderUri, int syncType)
```


Retrieves changes of the items and subfolders in a specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | The folder uri |
| syncType | int | Folder synchronization type |

**Returns:**
[SyncFolderResult](../../com.aspose.email/syncfolderresult) - Returns result of SyncFolder operation.
### syncFolder(String folderUri, String syncState) {#syncFolder-java.lang.String-java.lang.String-}
```
public abstract SyncFolderResult syncFolder(String folderUri, String syncState)
```


Retrieves changes of the items in a specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | The folder uri |
| syncState | java.lang.String | The optional synchronization state. Must be null for first synchronization. |

**Returns:**
[SyncFolderResult](../../com.aspose.email/syncfolderresult) - Returns result of SyncFolder operation.
### syncFolder(String folderUri, String syncState, Iterable<String> ignoreList) {#syncFolder-java.lang.String-java.lang.String-java.lang.Iterable-java.lang.String--}
```
public abstract SyncFolderResult syncFolder(String folderUri, String syncState, Iterable<String> ignoreList)
```


Retrieves changes of the items in a specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | The folder uri |
| syncState | java.lang.String | The optional synchronization state. Must be null for first synchronization. |
| ignoreList | java.lang.Iterable<java.lang.String> | The optional list of item uris that should be ignored. |

**Returns:**
[SyncFolderResult](../../com.aspose.email/syncfolderresult) - Returns result of SyncFolder operation.
### updateAppointment(Appointment appointment) {#updateAppointment-com.aspose.email.Appointment-}
```
public abstract void updateAppointment(Appointment appointment)
```


Updates appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [Appointment](../../com.aspose.email/appointment) | Calendar appointment. |

### updateAppointment(Appointment appointment, String folderUri) {#updateAppointment-com.aspose.email.Appointment-java.lang.String-}
```
public abstract void updateAppointment(Appointment appointment, String folderUri)
```


Updates appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [Appointment](../../com.aspose.email/appointment) | Calendar appointment. |
| folderUri | java.lang.String | An uri of appointments parent folder. |

### updateAppointment(MapiCalendar appointment) {#updateAppointment-com.aspose.email.MapiCalendar-}
```
public abstract void updateAppointment(MapiCalendar appointment)
```


Updates appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [MapiCalendar](../../com.aspose.email/mapicalendar) | Calendar appointment. |

### updateAppointment(MapiCalendar appointment, String folderUri) {#updateAppointment-com.aspose.email.MapiCalendar-java.lang.String-}
```
public abstract void updateAppointment(MapiCalendar appointment, String folderUri)
```


Updates appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| appointment | [MapiCalendar](../../com.aspose.email/mapicalendar) | Calendar appointment. |
| folderUri | java.lang.String | An uri of appointments parent folder. |

### updateContact(Contact contact) {#updateContact-com.aspose.email.Contact-}
```
public abstract void updateContact(Contact contact)
```


Updates a contact item in the Exchange store.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contact | [Contact](../../com.aspose.email/contact) | Contact item |

### updateContact(MapiContact contact) {#updateContact-com.aspose.email.MapiContact-}
```
public abstract void updateContact(MapiContact contact)
```


Updates a contact item in the Exchange store.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contact | [MapiContact](../../com.aspose.email/mapicontact) | Contact item |

### updateDelegate(ExchangeDelegateUser delegateUser, String mailbox) {#updateDelegate-com.aspose.email.ExchangeDelegateUser-java.lang.String-}
```
public abstract void updateDelegate(ExchangeDelegateUser delegateUser, String mailbox)
```


Updates the delegate user settings who is granted access on the specified mailbox.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegateUser | [ExchangeDelegateUser](../../com.aspose.email/exchangedelegateuser) | A new settings of delegate user. |
| mailbox | java.lang.String | A mailbox on which the delegate user is granted access. |

### updateDelegates(ExchangeDelegateUserCollection delegateUsers, String mailbox) {#updateDelegates-com.aspose.email.ExchangeDelegateUserCollection-java.lang.String-}
```
public abstract void updateDelegates(ExchangeDelegateUserCollection delegateUsers, String mailbox)
```


Updates the delegate users settings who are granted access on the specified mailbox.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegateUsers | [ExchangeDelegateUserCollection](../../com.aspose.email/exchangedelegateusercollection) | A [ExchangeDelegateUserCollection](../../com.aspose.email/exchangedelegateusercollection) containing the new settings of delegates. |
| mailbox | java.lang.String | A mailbox on which the delegate users are granted access. |

### updateInboxRule(InboxRule rule) {#updateInboxRule-com.aspose.email.InboxRule-}
```
public abstract void updateInboxRule(InboxRule rule)
```


Updates the specified inbox rule

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rule | [InboxRule](../../com.aspose.email/inboxrule) | A inbox rule to update |

### updateInboxRule(InboxRule rule, String mailbox) {#updateInboxRule-com.aspose.email.InboxRule-java.lang.String-}
```
public abstract void updateInboxRule(InboxRule rule, String mailbox)
```


Updates the specified inbox rule

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rule | [InboxRule](../../com.aspose.email/inboxrule) | A inbox rule to update |
| mailbox | java.lang.String | A mailbox where rule is located. Note: if it is set to  null  or  empty , the rule will be searched in the default mailbox |

### updateItems(ExchangeStreamedItem[] items, String parentFolderUri) {#updateItems-com.aspose.email.ExchangeStreamedItem---java.lang.String-}
```
public abstract ExchangeUploadItemResult[] updateItems(ExchangeStreamedItem[] items, String parentFolderUri)
```


Updates the specified items in to a mailbox

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| items | [ExchangeStreamedItem\[\]](../../com.aspose.email/exchangestreameditem) | An items to be updated |
| parentFolderUri | java.lang.String | Specifies the folder that contains the items to update |

**Returns:**
com.aspose.email.ExchangeUploadItemResult[] - An array of [ExchangeUploadItemResult](../../com.aspose.email/exchangeuploaditemresult)
### updateNote(MapiNote note) {#updateNote-com.aspose.email.MapiNote-}
```
public abstract String updateNote(MapiNote note)
```


Updates the specified note.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| note | [MapiNote](../../com.aspose.email/mapinote) | An [MapiNote](../../com.aspose.email/mapinote) containing the note information. |

**Returns:**
java.lang.String - Note uri.
### updateNote(String uri, MapiNote note) {#updateNote-java.lang.String-com.aspose.email.MapiNote-}
```
public abstract String updateNote(String uri, MapiNote note)
```


Updates the specified note.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uri | java.lang.String | Note identifier |
| note | [MapiNote](../../com.aspose.email/mapinote) | An [MapiNote](../../com.aspose.email/mapinote) containing the note information. |

**Returns:**
java.lang.String - Note uri.
### updateNote(String uri, MapiNote note, Iterable<PropertyDescriptor> additionalProperties) {#updateNote-java.lang.String-com.aspose.email.MapiNote-java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract String updateNote(String uri, MapiNote note, Iterable<PropertyDescriptor> additionalProperties)
```


Updates the specified note.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uri | java.lang.String | Note identifier |
| note | [MapiNote](../../com.aspose.email/mapinote) | An [MapiNote](../../com.aspose.email/mapinote) containing the note information. |
| additionalProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | An additional MAPI properties which can be used in MAPI object. |

**Returns:**
java.lang.String - Note uri.
### updateSubscription() {#updateSubscription--}
```
public abstract void updateSubscription()
```


Updates subscriptions

### updateTask(ExchangeTask task) {#updateTask-com.aspose.email.ExchangeTask-}
```
public abstract void updateTask(ExchangeTask task)
```


Updates the specified task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| task | [ExchangeTask](../../com.aspose.email/exchangetask) | An [ExchangeTask](../../com.aspose.email/exchangetask) containing the task information. |

### updateTask(ExchangeTask task, int options) {#updateTask-com.aspose.email.ExchangeTask-int-}
```
public abstract void updateTask(ExchangeTask task, int options)
```


Updates the specified task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| task | [ExchangeTask](../../com.aspose.email/exchangetask) | An [ExchangeTask](../../com.aspose.email/exchangetask) containing the task information. |
| options | int | An updation options. |

### updateTask(MapiTask task) {#updateTask-com.aspose.email.MapiTask-}
```
public abstract String updateTask(MapiTask task)
```


Updates the specified task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| task | [MapiTask](../../com.aspose.email/mapitask) | An [MapiTask](../../com.aspose.email/mapitask) containing the task information. |

**Returns:**
java.lang.String - Task uri.
### updateTask(String uri, MapiTask task) {#updateTask-java.lang.String-com.aspose.email.MapiTask-}
```
public abstract String updateTask(String uri, MapiTask task)
```


Updates the specified task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uri | java.lang.String | Task identifier |
| task | [MapiTask](../../com.aspose.email/mapitask) | An [ExchangeTask](../../com.aspose.email/exchangetask) containing the task information. |

**Returns:**
java.lang.String - Task uri.
### updateTask(String uri, MapiTask task, Iterable<PropertyDescriptor> additionalProperties) {#updateTask-java.lang.String-com.aspose.email.MapiTask-java.lang.Iterable-com.aspose.email.PropertyDescriptor--}
```
public abstract String updateTask(String uri, MapiTask task, Iterable<PropertyDescriptor> additionalProperties)
```


Updates the specified task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uri | java.lang.String | Task identifier |
| task | [MapiTask](../../com.aspose.email/mapitask) | An [ExchangeTask](../../com.aspose.email/exchangetask) containing the task information. |
| additionalProperties | java.lang.Iterable<com.aspose.email.PropertyDescriptor> | An additional MAPI properties which can be used in MAPI object. |

**Returns:**
java.lang.String - Task uri.
### updateUserConfiguration(UserConfiguration userConfiguration) {#updateUserConfiguration-com.aspose.email.UserConfiguration-}
```
public abstract void updateUserConfiguration(UserConfiguration userConfiguration)
```


Updates the specified user configuration

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userConfiguration | [UserConfiguration](../../com.aspose.email/userconfiguration) | [UserConfiguration](../../com.aspose.email/userconfiguration) to update |

