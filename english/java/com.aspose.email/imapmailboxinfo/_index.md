---
title: ImapMailboxInfo
second_title: Aspose.Email for Java API Reference
description: Contains set of special-use mailboxes
type: docs
weight: 314
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllMessages()](#getAllMessages--) | Gets mailbox presents all messages in the user's message store. |
| [getArchivedMessages()](#getArchivedMessages--) | Gets mailbox is used to archive messages. |
| [getClass()](#getClass--) |  |
| [getDraftMessages()](#getDraftMessages--) | Gets mailbox is used to hold draft messages typically, messages that are being composed but have not yet been sent. |
| [getFlaggedMessages()](#getFlaggedMessages--) | Gets mailbox presents all messages marked in some way as "important". |
| [getImportant()](#getImportant--) | Gets mailbox is used to hold messages that have been marked as important. |
| [getInbox()](#getInbox--) | Gets mailbox is used to hold incoming messages. |
| [getJunkMessages()](#getJunkMessages--) | Gets mailbox is where messages deemed to be junk mail are held. |
| [getSentMessages()](#getSentMessages--) | Gets mailbox is used to hold copies of messages that have been sent. |
| [getTrash()](#getTrash--) | Gets mailbox is used to hold messages that have been deleted or marked for deletion. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArray()](#toArray--) | Gets array of existed well-known folders. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toArray() {#toArray--}
```
public final ImapFolderInfo[] toArray()
```


Gets array of existed well-known folders. If well-known folder is null, it won't be included in array.

**Returns:**
com.aspose.email.ImapFolderInfo[] - Array of [ImapFolderInfo](../../com.aspose.email/imapfolderinfo) objects
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

