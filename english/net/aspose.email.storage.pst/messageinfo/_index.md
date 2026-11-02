---
title: Class MessageInfo
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Pst.MessageInfo class. Summary information about a message in a PST such as its subject recipients and message class available without loading the whole message
type: docs
weight: 19210
url: /net/aspose.email.storage.pst/messageinfo/
---
## MessageInfo class

Summary information about a message in a PST, such as its subject, recipients and message class, available without loading the whole message.

```csharp
public sealed class MessageInfo
```

## Constructors

| Name | Description |
| --- | --- |
| [MessageInfo](messageinfo/)() | Initializes a new instance of the `MessageInfo` class. |

## Properties

| Name | Description |
| --- | --- |
| [DisplayCC](../../aspose.email.storage.pst/messageinfo/displaycc/) { get; } | Gets the display names of the Cc recipients, as shown in the Cc line. |
| [DisplayTo](../../aspose.email.storage.pst/messageinfo/displayto/) { get; } | Gets the display names of the To recipients, as shown in the To line. |
| [EntryId](../../aspose.email.storage.pst/messageinfo/entryid/) { get; } | Gets the entry ID of the message, which identifies it in the PST. |
| [EntryIdString](../../aspose.email.storage.pst/messageinfo/entryidstring/) { get; } | Gets the entry ID of the message as a string. |
| [Importance](../../aspose.email.storage.pst/messageinfo/importance/) { get; } | Gets the importance of the message. |
| [MessageClass](../../aspose.email.storage.pst/messageinfo/messageclass/) { get; } | Gets the message class, which defines the type of the item, for example `IPM.Note` for an email or `IPM.Contact` for a contact. |
| [Properties](../../aspose.email.storage.pst/messageinfo/properties/) { get; } | Gets the MAPI properties of the message that are read with the message list. |
| [SenderRepresentativeName](../../aspose.email.storage.pst/messageinfo/senderrepresentativename/) { get; } | Gets the display name of the user the message was sent on behalf of (the PR_SENT_REPRESENTING_NAME property). |
| [Sensitivity](../../aspose.email.storage.pst/messageinfo/sensitivity/) { get; } | Gets the sensitivity of the message. |
| [Subject](../../aspose.email.storage.pst/messageinfo/subject/) { get; } | Gets the message subject. |

## Remarks

Use `PersonalStorage.ExtractMessage` to load the full message with its body and attachments.

### See Also

* namespace [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst/)
* assembly [Aspose.Email](../../)


