---
title: Aspose.Email.Clients.Imap
second_title: Aspose.Email for .NET API Reference
description: The Aspose.Email.Clients.Imap namespace provides classes to access and manipulate messages by using the Internet Message Access Protocol IMAP.
type: docs
weight: 220
url: /net/aspose.email.clients.imap/
---
The **Aspose.Email.Clients.Imap** namespace provides classes to access and manipulate messages by using the Internet Message Access Protocol (IMAP).

## Classes

| Class | Description |
| --- | --- |
| [AppendMessagesResult](./appendmessagesresult) | Contains result of operation with messages |
| [BackupSettings](./backupsettings) | Class contains options for backup operation |
| [BaseSearchConditions](./basesearchconditions) | Provides base class for the search conditions. |
| [ESearchOptions](./esearchoptions) | ESEARCH Result Options This method works only if server supports ESEARCH extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [FetchTimeoutException](./fetchtimeoutexception) | Represents the exception that is thrown when a message can not be read within the specified time. |
| [ImapAttachmentInfo](./imapattachmentinfo) | Represents an attachment information. |
| [ImapAttachmentInfoCollection](./imapattachmentinfocollection) | Represents the collection of [`ImapAttachmentInfo`](aspose.email.clients.imap/imapattachmentinfo) |
| [ImapClient](./imapclient) | Allows applications to access and manipulate messages by using the Internet Message Access Protocol (IMAP). |
| [ImapFolderInfo](./imapfolderinfo) | Represents an IMAP folder. |
| [ImapFolderInfoCollection](./imapfolderinfocollection) | Provides a container for a collection of ImapFolderInfo objects. |
| [ImapIdentificationInfo](./imapidentificationinfo) | Represents class-container with identification information to exchange between mail client and server. Please, read more rfc2971 https://tools.ietf.org/html/rfc2971 |
| [ImapMailboxInfo](./imapmailboxinfo) | Contains set of special-use mailboxes |
| [ImapMessageFlags](./imapmessageflags) | Represents the flags associated with the message. |
| [ImapMessageInfo](./imapmessageinfo) | Represents a Imap message object. |
| [ImapMessageInfoCollection](./imapmessageinfocollection) | Provides a container for a collection of [`ImapMessageInfo`](aspose.email.clients.imap/imapmessageinfo) objects |
| [ImapMonitoringErrorEventArgs](./imapmonitoringerroreventargs) | Class contains monitoring error event data. |
| [ImapMonitoringErrorEventHandler](./imapmonitoringerroreventhandler) | Represents the method that will handle an imap monitoring error event |
| [ImapMonitoringEventArgs](./imapmonitoringeventargs) | Class contains monitoring event data. |
| [ImapMonitoringEventHandler](./imapmonitoringeventhandler) | Represents the method that will handle an imap monitoring event |
| [ImapNamespace](./imapnamespace) | Represents IMAP namespace More details: https://tools.ietf.org/html/rfc2342 |
| [ImapPageInfo](./imappageinfo) | Contains information about retrieved page when paging methods are used. |
| [ImapQueryBuilder](./imapquerybuilder) | Represents the builder of search expression that used by IMAP protocol. |
| [ImapQuota](./imapquota) | Contains information about quota for mailbox resource. |
| [ImapQuotaRoot](./imapquotaroot) | Contains information about quota root for mailbox resource. |
| [MessageThreadResult](./messagethreadresult) | Contains result for SORT ot THREAD methods See more: https://tools.ietf.org/html/rfc5256 |
| [ModificationSequenceField](./modificationsequencefield) | Defines set of values for selected field to search. |
| [PageSettings](./pagesettings) | The settings for the ImapClient.ListMessagesByPage method |
| [PageSettingsAsync](./pagesettingsasync) | The settings for the ImapClient.BeginListMessagesByPage async method. |
| [RangeSeqSet](./rangeseqset) | Container with range of values to search. |
| [ReadLinesTimeoutException](./readlinestimeoutexception) | Represents the exception that is thrown when a response from server can not be read within the specified time. |
| [RestoreSettings](./restoresettings) | The settings for the ImapClient.Restore method |
| [RestoreSettingsAsync](./restoresettingsasync) | The settings for the ImapClient.Restore async method. |
| [SequenceSetBaseValue](./sequencesetbasevalue) | Base class for different containers for values to search. |
| [SequenceSetField](./sequencesetfield) | Defines set of values for selected field to search. |
| [SimpleSeqSet](./simpleseqset) | Simple container for value to search. |
| [SortConditions](./sortconditions) | Provides the search conditions for the SORT extension. Compatibles with SORT IMAP extension described at https://tools.ietf.org/html/rfc5256 |
| [ThreadSearchConditions](./threadsearchconditions) | Provides the search conditions to retrieve email thread. Compatibles with THREAD IMAP extension described at https://tools.ietf.org/html/rfc5256 |
| [XGMThreadSearchConditions](./xgmthreadsearchconditions) | Provides the search conditions to retrieve email thread. Compatibles with X-GM-EXT-1 IMAP extension described at https://developers.google.com/gmail/imap/imap-extensions#checking_for_the_presence_of_extensions. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IImapMonitoringState](./iimapmonitoringstate) | Holds folder monitoring state. This can be used to resume folder monitoring from place where it stopped when error occured. Use [`ResumeMonitoring`](aspose.email.clients.imap/imapclient/resumemonitoring) method. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [ImapCommandResult](./imapcommandresult) | Enumerates the imap command results. |
| [ImapKnownAuthenticationType](./imapknownauthenticationtype) |  |
| [ImapListFields](./imaplistfields) | Fields that may be retrieved from the server |
| [ImapNamespaceType](./imapnamespacetype) | Represents IMAP namespace type More details: https://tools.ietf.org/html/rfc2342 |
| [ImapSpecialFolderTypes](./imapspecialfoldertypes) | Represents enumeration of special-use mailboxes More details see in RFC6154 http://tools.ietf.org/html/rfc6154 |
| [ImapStatusCode](./imapstatuscode) | Represents the status responses. |
| [ListFoldersOptions](./listfoldersoptions) | The folder list selection options Please note, this options are supported in case if server supports RFC 5258 "IMAP LIST Command Extensions" See more details in https://tools.ietf.org/html/rfc5258 |
| [ListFoldersReturnOptions](./listfoldersreturnoptions) | Return options for ListFolders operation Please note, this options are supported in case if server supports RFC 5258 "IMAP LIST Command Extensions" See more details in https://tools.ietf.org/html/rfc5258 |
| [SortingKey](./sortingkey) | Sort criterias for "SORT" command See more: https://tools.ietf.org/html/rfc5256 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
