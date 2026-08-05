---
title: "Aspose::Email::Clients::Imap namespace"
linktitle: "Aspose::Email::Clients::Imap"
articleTitle: "Aspose::Email::Clients::Imap"
second_title: "Aspose.Email for C++"
description: "Provides classes and enums for interacting with IMAP servers, handling messages, attachments, searches, and backup operations."
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/
---

## Aspose::Email::Clients::Imap namespace

The Aspose::Email::Clients::Imap namespace contains the core API for IMAP client functionality in Aspose.Email for C++. It includes types for message appending, monitoring, search criteria, attachment metadata, and backup configuration.


## Classes

| Name | Description |
| --- | --- |
| [AppendMessagesFromFileResult](./appendmessagesfromfileresult/) | Contains result of operation with messages |
| [AppendMessagesFromMessageObjectResult](./appendmessagesfrommessageobjectresult/) | Contains result of operation with messages |
| [AppendMessagesResult](./appendmessagesresult/) | Contains result of operation with messages |
| [BackupSettings](./backupsettings/) | Class contains options for backup operation |
| [BaseSearchConditions](./basesearchconditions/) | Provides base class for the search conditions. |
| [ESearchOptions](./esearchoptions/) | ESEARCH Result Options This method works only if server supports ESEARCH extensi |
| [IImapMonitoringState](./iimapmonitoringstate/) | Holds folder monitoring state. This can be used to resume folder monitoring from |
| [ImapAttachmentInfo](./imapattachmentinfo/) | Represents an attachment information. |
| [ImapAttachmentInfoCollection](./imapattachmentinfocollection/) | Represents the collection of ImapAttachmentInfo |
| [ImapClient](./imapclient/) | Allows applications to access and manipulate messages by using the Internet Mess |
| [ImapFolderInfo](./imapfolderinfo/) | Represents an IMAP folder. |
| [ImapFolderInfoCollection](./imapfolderinfocollection/) | Provides a container for a collection of ImapFolderInfo objects. |
| [ImapFolderInfoCollectionBase](./imapfolderinfocollectionbase/) | Provides a container for a collection of ImapFolderInfo objects |
| [ImapIdentificationInfo](./imapidentificationinfo/) | Represents class-container with identification information to exchange between m |
| [ImapMailboxInfo](./imapmailboxinfo/) | Contains set of special-use mailboxes |
| [ImapMessageFlags](./imapmessageflags/) | Represents the flags associated with the message. |
| [ImapMessageInfo](./imapmessageinfo/) | Represents a Imap message object. |
| [ImapMessageInfoCollection](./imapmessageinfocollection/) | Provides a container for a collection of ImapMessageInfo objects |
| [ImapMessageInfoCollectionBase](./imapmessageinfocollectionbase/) | Provides a container for a collection of ImapMessageInfo objects |
| [ImapMonitoringErrorEventArgs](./imapmonitoringerroreventargs/) | Class contains monitoring error event data. |
| [ImapMonitoringEventArgs](./imapmonitoringeventargs/) | Class contains monitoring event data. |
| [ImapNamespace](./imapnamespace/) | Represents IMAP namespace More details: https://tools.ietf.org/html/rfc2342 |
| [ImapPageInfo](./imappageinfo/) | Contains information about retrieved page when paging methods are used. |
| [ImapQueryBuilder](./imapquerybuilder/) | Represents the builder of search expression that used by IMAP protocol. |
| [ImapQuota](./imapquota/) | Contains information about quota for mailbox resource. |
| [ImapQuotaRoot](./imapquotaroot/) | Contains information about quota root for mailbox resource. |
| [MessageThreadResult](./messagethreadresult/) | Contains result for SORT ot THREAD methods See more: https://tools.ietf.org/html |
| [ModificationSequenceField](./modificationsequencefield/) | Defines set of values for selected field to search. |
| [PageSettings](./pagesettings/) | The settings for the ImapClient.ListMessagesByPage method |
| [PageSettingsAsync](./pagesettingsasync/) | The settings for the ImapClient.BeginListMessagesByPage async method. |
| [RangeSeqSet](./rangeseqset/) | Container with range of values to search. |
| [RestoreSettings](./restoresettings/) | The settings for the ImapClient.Restore method |
| [RestoreSettingsAsync](./restoresettingsasync/) | The settings for the ImapClient.Restore async method. |
| [SequenceSetBaseValue](./sequencesetbasevalue/) | Base class for different containers for values to search. |
| [SequenceSetField](./sequencesetfield/) | Defines set of values for selected field to search. |
| [SimpleSeqSet](./simpleseqset/) | Simple container for value to search. |
| [SortConditions](./sortconditions/) | Provides the search conditions for the SORT extension. Compatibles with SORT IMA |
| [ThreadSearchConditions](./threadsearchconditions/) | Provides the search conditions to retrieve email thread. Compatibles with THREAD |
| [XGMThreadSearchConditions](./xgmthreadsearchconditions/) | Provides the search conditions to retrieve email thread. Compatibles with X-GM-E |

## Enumerations

| Name | Description |
| --- | --- |
| [ImapCommandResult](./imapcommandresult/) | Enumerates the imap command results. |
| [ImapKnownAuthenticationType](./imapknownauthenticationtype/) | None |
| [ImapListFields](./imaplistfields/) | Fields that may be retrieved from the server |
| [ImapNamespaceType](./imapnamespacetype/) | Represents IMAP namespace type More details: https://tools.ietf.org/html/rfc2342 |
| [ImapSpecialFolderTypes](./imapspecialfoldertypes/) | Represents enumeration of special-use mailboxes More details see in RFC6154 http |
| [ImapStatusCode](./imapstatuscode/) | Represents the status responses. |
| [ListFoldersOptions](./listfoldersoptions/) | The folder list selection options Please note, this options are supported in cas |
| [ListFoldersReturnOptions](./listfoldersreturnoptions/) | Return options for ListFolders operation Please note, this options are supported |
| [SortingKey](./sortingkey/) | Sort criterias for "SORT" command See more: https://tools.ietf.org/html/rfc5256 |

