---
title: Class PersonalStorageQueryBuilder
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Pst.PersonalStorageQueryBuilder class. Builds search queries for the messages and folders of a PST
type: docs
weight: 19280
url: /net/aspose.email.storage.pst/personalstoragequerybuilder/
---
## PersonalStorageQueryBuilder class

Builds search queries for the messages and folders of a PST.

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
| [ContainerClass](../../aspose.email.storage.pst/personalstoragequerybuilder/containerclass/) { get; } | Gets the field to search folders by container class. |
| [ContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/contentscount/) { get; } | Gets the field to search folders by the number of items they contain. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding/) { get; } | Gets default encoding (charset) for query builder |
| [FolderName](../../aspose.email.storage.pst/personalstoragequerybuilder/foldername/) { get; } | Gets the field to search folders by name. |
| [From](../../aspose.email.tools.search/mailquerybuilder/from/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field. |
| [Importance](../../aspose.email.storage.pst/personalstoragequerybuilder/importance/) { get; } | Gets the field to search messages by importance. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate/) { get; } | Gets the field that allows to find messages by internal date. |
| [MessageClass](../../aspose.email.storage.pst/personalstoragequerybuilder/messageclass/) { get; } | Gets the field to search messages by message class. |
| [MessageId](../../aspose.email.storage.pst/personalstoragequerybuilder/messageid/) { get; } | Gets the field to search messages by the Message-ID header. |
| [MessageSize](../../aspose.email.storage.pst/personalstoragequerybuilder/messagesize/) { get; } | Gets the field to search messages by size, in bytes. |
| [OnlyFoldersCreatedByUser](../../aspose.email.storage.pst/personalstoragequerybuilder/onlyfolderscreatedbyuser/) { get; } | Gets the field to search only the folders created by the user, leaving out the standard Outlook folders. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate/) { get; } | Gets the field that allows to find messages by sent date. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text/) { get; } | Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to/) { get; } | Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field. |
| [UnreadContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/unreadcontentscount/) { get; } | Gets the field to search folders by the number of unread items they contain. |

## Methods

| Name | Description |
| --- | --- |
| [FindConversationThread](../../aspose.email.storage.pst/personalstoragequerybuilder/findconversationthread/)(MessageInfo) | Adds a condition that finds the messages of the same conversation as the specified message. |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery/)() | Gets the query. |
| [HasFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasflags/)(MapiMessageFlags) | Adds a condition that finds messages with the specified flags set. |
| [HasNoFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnoflags/)(MapiMessageFlags) | Adds a condition that finds messages with the specified flags not set. |
| [HasNoSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnosubfolders/)() | Adds a condition that finds folders without subfolders. |
| [HasSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hassubfolders/)() | Adds a condition that finds folders with subfolders. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or/)(MailQuery, MailQuery) | Search messages that match either search key. Provides disjunction between two expressions (OR). |

## Remarks

Add conditions through the fields of the builder: for messages, the fields inherited from `MailQueryBuilder`, such as `From` or `Subject`, and fields such as `MessageClass`; for folders, `FolderName`, `ContentsCount` and the like. All conditions are combined. Pass the result of `GetQuery` to `FolderInfo.GetContents` or `FolderInfo.GetSubFolders`.

## Examples

This example finds the unread messages of the Inbox from a given sender whose subject contains "invoice".

[C#]

```csharp
using (var pst = PersonalStorage.FromFile("archive.pst"))
{
    var inbox = pst.GetPredefinedFolder(StandardIpmFolder.Inbox);

    var builder = new PersonalStorageQueryBuilder();
    builder.From.Contains("billing@example.com");
    builder.Subject.Contains("invoice", true);
    builder.HasNoFlags(MapiMessageFlags.MSGFLAG_READ);

    foreach (var messageInfo in inbox.GetContents(builder.GetQuery()))
    {
        Console.WriteLine(messageInfo.Subject);
    }
}
```

[Visual Basic]

```csharp
Using pst As PersonalStorage = PersonalStorage.FromFile("archive.pst")
    Dim inbox As FolderInfo = pst.GetPredefinedFolder(StandardIpmFolder.Inbox)

    Dim builder As New PersonalStorageQueryBuilder()
    builder.From.Contains("billing@example.com")
    builder.Subject.Contains("invoice", True)
    builder.HasNoFlags(MapiMessageFlags.MSGFLAG_READ)

    For Each messageInfo As MessageInfo In inbox.GetContents(builder.GetQuery())
        Console.WriteLine(messageInfo.Subject)
    Next
End Using
```

### See Also

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder/)
* namespace [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst/)
* assembly [Aspose.Email](../../)


