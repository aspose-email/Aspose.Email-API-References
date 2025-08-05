---
title: Class ImapMailboxInfo
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Imap.ImapMailboxInfo class. Contains set of specialuse mailboxes
type: docs
weight: 15060
url: /net/aspose.email.clients.imap/imapmailboxinfo/
---
## ImapMailboxInfo class

Contains set of special-use mailboxes

```csharp
public class ImapMailboxInfo
```

## Properties

| Name | Description |
| --- | --- |
| [AllMessages](../../aspose.email.clients.imap/imapmailboxinfo/allmessages/) { get; } | Gets mailbox presents all messages in the user's message store. Please note, this value may be null if server does not support rfc6154 or folder has not been created. |
| [ArchivedMessages](../../aspose.email.clients.imap/imapmailboxinfo/archivedmessages/) { get; } | Gets mailbox is used to archive messages. Please note, this value may be null if server does not support rfc6154 or folder has not been created. |
| [DraftMessages](../../aspose.email.clients.imap/imapmailboxinfo/draftmessages/) { get; } | Gets mailbox is used to hold draft messages typically, messages that are being composed but have not yet been sent. Please note, this value may be null if server does not support rfc6154 or folder has not been created. |
| [FlaggedMessages](../../aspose.email.clients.imap/imapmailboxinfo/flaggedmessages/) { get; } | Gets mailbox presents all messages marked in some way as "important". Please note, this value may be null if server does not support rfc6154 or folder has not been created. |
| [Important](../../aspose.email.clients.imap/imapmailboxinfo/important/) { get; } | Gets mailbox is used to hold messages that have been marked as important. Please note, this value may be null if server does not support rfc8457 or folder has not been created. |
| [Inbox](../../aspose.email.clients.imap/imapmailboxinfo/inbox/) { get; } | Gets mailbox is used to hold incoming messages. |
| [JunkMessages](../../aspose.email.clients.imap/imapmailboxinfo/junkmessages/) { get; } | Gets mailbox is where messages deemed to be junk mail are held. Please note, this value may be null if server does not support rfc6154 or folder has not been created. |
| [SentMessages](../../aspose.email.clients.imap/imapmailboxinfo/sentmessages/) { get; } | Gets mailbox is used to hold copies of messages that have been sent. Please note, this value may be null if server does not support rfc6154 or folder has not been created. |
| [Trash](../../aspose.email.clients.imap/imapmailboxinfo/trash/) { get; } | Gets mailbox is used to hold messages that have been deleted or marked for deletion. Please note, this value may be null if server does not support rfc6154 or folder has not been created. |

## Methods

| Name | Description |
| --- | --- |
| [ToArray](../../aspose.email.clients.imap/imapmailboxinfo/toarray/)() | Gets array of existed well-known folders. If well-known folder is null, it won't be included in array. |

### See Also

* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap/)
* assembly [Aspose.Email](../../)


