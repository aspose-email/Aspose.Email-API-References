---
title: Aspose.Email.Clients.Imap
second_title: Aspose.Email for .NET API Reference
description: The **Aspose.Email.Clients.Imap** namespace provides classes to access and manipulate messages by using the Internet Message Access Protocol (IMAP).
type: docs
weight: 180
url: /net/aspose.email.clients.imap/
---
The **Aspose.Email.Clients.Imap** namespace provides classes to access and manipulate messages by using the Internet Message Access Protocol (IMAP).

## Classes

| Class | Description |
| --- | --- |
| class [AppendMessagesResult](./appendmessagesresult) | Contains result of operation with messages |
| class [BackupSettings](./backupsettings) | Class contains options for backup operation |
| abstract class [BaseSearchConditions](./basesearchconditions) | Provides base class for the search conditions. |
| class [ESearchOptions](./esearchoptions) | ESEARCH Result Options This method works only if server supports ESEARCH extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| class [FetchTimeoutException](./fetchtimeoutexception) | Represents the exception that is thrown when a message can not be read within the specified time. |
| class [ImapAttachmentInfo](./imapattachmentinfo) | Represents an attachment information. |
| class [ImapAttachmentInfoCollection](./imapattachmentinfocollection) | Represents the collection of [`ImapAttachmentInfo`](aspose.email.clients.imap/imapattachmentinfo) |
| class [ImapClient](./imapclient) | Allows applications to access and manipulate messages by using the Internet Message Access Protocol (IMAP). |
| class [ImapFolderInfo](./imapfolderinfo) | Represents an IMAP folder. |
| class [ImapFolderInfoCollection](./imapfolderinfocollection) | Provides a container for a collection of ImapFolderInfo objects. |
| class [ImapIdentificationInfo](./imapidentificationinfo) | Represents class-container with identification information to exchange between mail client and server. Please, read more rfc2971 https://tools.ietf.org/html/rfc2971 |
| class [ImapMailboxInfo](./imapmailboxinfo) | Contains set of special-use mailboxes |
| class [ImapMessageFlags](./imapmessageflags) | Represents the flags associated with the message. |
| class [ImapMessageInfo](./imapmessageinfo) | Represents a Imap message object. |
| class [ImapMessageInfoCollection](./imapmessageinfocollection) | Provides a container for a collection of [`ImapMessageInfo`](aspose.email.clients.imap/imapmessageinfo) objects |
| class [ImapMonitoringErrorEventArgs](./imapmonitoringerroreventargs) | Class contains monitoring error event data. |
| delegate [ImapMonitoringErrorEventHandler](./imapmonitoringerroreventhandler) | Represents the method that will handle an imap monitoring error event |
| class [ImapMonitoringEventArgs](./imapmonitoringeventargs) | Class contains monitoring event data. |
| delegate [ImapMonitoringEventHandler](./imapmonitoringeventhandler) | Represents the method that will handle an imap monitoring event |
| class [ImapNamespace](./imapnamespace) | Represents IMAP namespace More details: https://tools.ietf.org/html/rfc2342 |
| class [ImapPageInfo](./imappageinfo) | Contains information about retrieved page when paging methods are used. |
| class [ImapQueryBuilder](./imapquerybuilder) | Represents the builder of search expression that used by IMAP protocol. |
| class [ImapQuota](./imapquota) | Contains information about quota for mailbox resource. |
| class [ImapQuotaRoot](./imapquotaroot) | Contains information about quota root for mailbox resource. |
| class [MessageThreadResult](./messagethreadresult) | Contains result for SORT ot THREAD methods See more: https://tools.ietf.org/html/rfc5256 |
| class [ModificationSequenceField](./modificationsequencefield) | Defines set of values for selected field to search. |
| class [PageSettings](./pagesettings) | The settings for the ImapClient.ListMessagesByPage method |
| class [PageSettingsAsync](./pagesettingsasync) | The settings for the ImapClient.BeginListMessagesByPage async method. |
| class [RangeSeqSet](./rangeseqset) | Container with range of values to search. |
| class [RestoreSettings](./restoresettings) | The settings for the ImapClient.Restore method |
| class [RestoreSettingsAsync](./restoresettingsasync) | The settings for the ImapClient.Restore async method. |
| abstract class [SequenceSetBaseValue](./sequencesetbasevalue) | Base class for different containers for values to search. |
| class [SequenceSetField](./sequencesetfield) | Defines set of values for selected field to search. |
| class [SimpleSeqSet](./simpleseqset) | Simple container for value to search. |
| class [SortConditions](./sortconditions) | Provides the search conditions for the SORT extension. Compatibles with SORT IMAP extension described at https://tools.ietf.org/html/rfc5256 |
| class [ThreadSearchConditions](./threadsearchconditions) | Provides the search conditions to retrieve email thread. Compatibles with THREAD IMAP extension described at https://tools.ietf.org/html/rfc5256 |
| class [XGMThreadSearchConditions](./xgmthreadsearchconditions) | Provides the search conditions to retrieve email thread. Compatibles with X-GM-EXT-1 IMAP extension described at https://developers.google.com/gmail/imap/imap-extensions#checking_for_the_presence_of_extensions. |
## Interfaces

| Interface | Description |
| --- | --- |
| interface [IImapMonitoringState](./iimapmonitoringstate) | Holds folder monitoring state. This can be used to resume folder monitoring from place where it stopped when error occured. Use [`ResumeMonitoring`](aspose.email.clients.imap/imapclient/resumemonitoring) method. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| enum [ImapCommandResult](./imapcommandresult) | Enumerates the imap command results. |
| enum [ImapKnownAuthenticationType](./imapknownauthenticationtype) |  |
| enum [ImapListFields](./imaplistfields) | Fields that may be retrieved from the server |
| enum [ImapNamespaceType](./imapnamespacetype) | Represents IMAP namespace type More details: https://tools.ietf.org/html/rfc2342 |
| enum [ImapSpecialFolderTypes](./imapspecialfoldertypes) | Represents enumeration of special-use mailboxes More details see in RFC6154 http://tools.ietf.org/html/rfc6154 |
| enum [ImapStatusCode](./imapstatuscode) | Represents the status responses. |
| enum [ListFoldersOptions](./listfoldersoptions) | The folder list selection options Please note, this options are supported in case if server supports RFC 5258 "IMAP LIST Command Extensions" See more details in https://tools.ietf.org/html/rfc5258 |
| enum [ListFoldersReturnOptions](./listfoldersreturnoptions) | Return options for ListFolders operation Please note, this options are supported in case if server supports RFC 5258 "IMAP LIST Command Extensions" See more details in https://tools.ietf.org/html/rfc5258 |
| enum [SortingKey](./sortingkey) | Sort criterias for "SORT" command See more: https://tools.ietf.org/html/rfc5256 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
