---
title: "Aspose::Email::Clients::Imap::ImapMailboxInfo::ImapMailboxInfo constructor"
linktitle: "ImapMailboxInfo"
articleTitle: "ImapMailboxInfo"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of ImapMailboxInfo class"
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/imapmailboxinfo/imapmailboxinfo/
---

## ImapMailboxInfo {#imapmailboxinfo}

Initializes a new instance of ImapMailboxInfo class

**Returns:** Aspose::Email::Clients::Imap::

```cpp
ImapMailboxInfo(System::SharedPtr < ImapFolderInfo > allMessages, System::SharedPtr < ImapFolderInfo > archivedMessages, System::SharedPtr < ImapFolderInfo > draftMessages, System::SharedPtr < ImapFolderInfo > flaggedMessages, System::SharedPtr < ImapFolderInfo > junkMessages, System::SharedPtr < ImapFolderInfo > sentMessages, System::SharedPtr < ImapFolderInfo > trash, System::SharedPtr < ImapFolderInfo > important, System::SharedPtr < ImapFolderInfo > inbox)
```

| Parameter | Description |
| --- | --- |
| allMessages | This mailbox presents all messages in the user's message store. |
| archivedMessages | This mailbox is used to archive messages. |
| draftMessages | This mailbox is used to hold draft messages typically, messages that are being composed but have not yet been sent. |
| flaggedMessages | This mailbox presents all messages marked in some way as "important". |
| junkMessages | This mailbox is where messages deemed to be junk mail are held. |
| sentMessages | This mailbox is used to hold copies of messages that have been sent. |
| trash | This mailbox is used to hold messages that have been deleted or marked for deletion. |
| important | This mailbox is used to hold messages that have been marked as important. |
| inbox | This mailbox is used to hold incoming messages. |

