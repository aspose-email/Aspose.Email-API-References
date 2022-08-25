---
title: ImapMailboxInfo
second_title: Aspose.Email for Java API Reference
description:  Contains set of special-use mailboxes
type: docs
weight: 313
url: /java/com.aspose.email/imapmailboxinfo/
---
**Inheritance:**
java.lang.Object
```
public class ImapMailboxInfo
```

Contains set of special-use mailboxes
## Methods

| Method | Description |
| --- | --- |
| [getAllMessages()](#getAllMessages--) | Gets mailbox presents all messages in the user's message store. |
| [getArchivedMessages()](#getArchivedMessages--) | Gets mailbox is used to archive messages. |
| [getDraftMessages()](#getDraftMessages--) | Gets mailbox is used to hold draft messages typically, messages that are being composed but have not yet been sent. |
| [getFlaggedMessages()](#getFlaggedMessages--) | Gets mailbox presents all messages marked in some way as "important". |
| [getJunkMessages()](#getJunkMessages--) | Gets mailbox is where messages deemed to be junk mail are held. |
| [getSentMessages()](#getSentMessages--) | Gets mailbox is used to hold copies of messages that have been sent. |
| [getTrash()](#getTrash--) | Gets mailbox is used to hold messages that have been deleted or marked for deletion. |
| [getImportant()](#getImportant--) | Gets mailbox is used to hold messages that have been marked as important. |
| [getInbox()](#getInbox--) | Gets mailbox is used to hold incoming messages. |
| [toArray()](#toArray--) | Gets array of existed well-known folders. |
### getAllMessages() {#getAllMessages--}
```
public final ImapFolderInfo getAllMessages()
```


Gets mailbox presents all messages in the user's message store. Please note, this value may be null if server does not support rfc6154 or folder has not been created.

**Returns:**
[ImapFolderInfo](../../com.aspose.email/imapfolderinfo)
### getArchivedMessages() {#getArchivedMessages--}
```
public final ImapFolderInfo getArchivedMessages()
```


Gets mailbox is used to archive messages. Please note, this value may be null if server does not support rfc6154 or folder has not been created.

**Returns:**
[ImapFolderInfo](../../com.aspose.email/imapfolderinfo)
### getDraftMessages() {#getDraftMessages--}
```
public final ImapFolderInfo getDraftMessages()
```


Gets mailbox is used to hold draft messages typically, messages that are being composed but have not yet been sent. Please note, this value may be null if server does not support rfc6154 or folder has not been created.

**Returns:**
[ImapFolderInfo](../../com.aspose.email/imapfolderinfo)
### getFlaggedMessages() {#getFlaggedMessages--}
```
public final ImapFolderInfo getFlaggedMessages()
```


Gets mailbox presents all messages marked in some way as "important". Please note, this value may be null if server does not support rfc6154 or folder has not been created.

**Returns:**
[ImapFolderInfo](../../com.aspose.email/imapfolderinfo)
### getJunkMessages() {#getJunkMessages--}
```
public final ImapFolderInfo getJunkMessages()
```


Gets mailbox is where messages deemed to be junk mail are held. Please note, this value may be null if server does not support rfc6154 or folder has not been created.

**Returns:**
[ImapFolderInfo](../../com.aspose.email/imapfolderinfo)
### getSentMessages() {#getSentMessages--}
```
public final ImapFolderInfo getSentMessages()
```


Gets mailbox is used to hold copies of messages that have been sent. Please note, this value may be null if server does not support rfc6154 or folder has not been created.

**Returns:**
[ImapFolderInfo](../../com.aspose.email/imapfolderinfo)
### getTrash() {#getTrash--}
```
public final ImapFolderInfo getTrash()
```


Gets mailbox is used to hold messages that have been deleted or marked for deletion. Please note, this value may be null if server does not support rfc6154 or folder has not been created.

**Returns:**
[ImapFolderInfo](../../com.aspose.email/imapfolderinfo)
### getImportant() {#getImportant--}
```
public final ImapFolderInfo getImportant()
```


Gets mailbox is used to hold messages that have been marked as important. Please note, this value may be null if server does not support rfc8457 or folder has not been created.

**Returns:**
[ImapFolderInfo](../../com.aspose.email/imapfolderinfo)
### getInbox() {#getInbox--}
```
public final ImapFolderInfo getInbox()
```


Gets mailbox is used to hold incoming messages.

**Returns:**
[ImapFolderInfo](../../com.aspose.email/imapfolderinfo)
### toArray() {#toArray--}
```
public final ImapFolderInfo[] toArray()
```


Gets array of existed well-known folders. If well-known folder is null, it won't be included in array.

**Returns:**
com.aspose.email.ImapFolderInfo[] - Array of [ImapFolderInfo](../../com.aspose.email/imapfolderinfo) objects
