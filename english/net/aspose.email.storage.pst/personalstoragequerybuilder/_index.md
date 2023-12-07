---
title: Class PersonalStorageQueryBuilder
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Pst.PersonalStorageQueryBuilder class. Represents the builder of search expression that used by pst
type: docs
weight: 20450
url: /net/aspose.email.storage.pst/personalstoragequerybuilder/
---
## PersonalStorageQueryBuilder class

Represents the builder of search expression that used by pst.

```csharp
public sealed class PersonalStorageQueryBuilder : MailQueryBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [PersonalStorageQueryBuilder](personalstoragequerybuilder/)() | Initializes a new instance of the `PersonalStorageQueryBuilder` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body/) { get; } | Gets the field that allows to find messages that contain the specified string in the body of the message. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field. |
| [ContainerClass](../../aspose.email.storage.pst/personalstoragequerybuilder/containerclass/) { get; } | Gets folders with an specified message class. |
| [ContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/contentscount/) { get; } | Search folders with an specified contents count. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding/) { get; } | Gets default encoding (charset) for query builder |
| [FolderName](../../aspose.email.storage.pst/personalstoragequerybuilder/foldername/) { get; } | Search folders with an specified display name. |
| [From](../../aspose.email.tools.search/mailquerybuilder/from/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field. |
| [Importance](../../aspose.email.storage.pst/personalstoragequerybuilder/importance/) { get; } | Search messages with an specified importance. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate/) { get; } | Gets the field that allows to find messages by internal date. |
| [MessageClass](../../aspose.email.storage.pst/personalstoragequerybuilder/messageclass/) { get; } | Gets messages with an specified message class. |
| [MessageId](../../aspose.email.storage.pst/personalstoragequerybuilder/messageid/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's MessageId field. |
| [MessageSize](../../aspose.email.storage.pst/personalstoragequerybuilder/messagesize/) { get; } | Search messages with an specified size. |
| [OnlyFoldersCreatedByUser](../../aspose.email.storage.pst/personalstoragequerybuilder/onlyfolderscreatedbyuser/) { get; } | Gets folders that created by user, i.e. excludes all standard IPM folders. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate/) { get; } | Gets the field that allows to find messages by sent date. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text/) { get; } | Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field. |
| [UnreadContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/unreadcontentscount/) { get; } | Search folders with an specified unread contents count. |

## Methods

| Name | Description |
| --- | --- |
| [FindConversationThread](../../aspose.email.storage.pst/personalstoragequerybuilder/findconversationthread/)(MessageInfo) | Finds the conversation thread. |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery/)() | Gets the query. |
| [HasFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasflags/)(MapiMessageFlags) | Search messages with the specified flags. |
| [HasNoFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnoflags/)(MapiMessageFlags) | Search messages with the unspecified flags. |
| [HasNoSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnosubfolders/)() | Search folders which does not contains subfolders. |
| [HasSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hassubfolders/)() | Search folders which contains subfolders. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or/)(MailQuery, MailQuery) | Search messages that match either search key. Provides disjunction between two expressions (OR). |

### See Also

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder/)
* namespace [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst/)
* assembly [Aspose.Email](../../)


