---
title: GraphKnownFolders
second_title: Aspose.Email for Java API Reference
description: Well-known folders
type: docs
weight: 286
url: /java/com.aspose.email/graphknownfolders/
---

**Inheritance:**
java.lang.Object
```
public class GraphKnownFolders
```

Well-known folders
## Constructors

| Constructor | Description |
| --- | --- |
| [GraphKnownFolders()](#GraphKnownFolders--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Archive](#Archive) | The archive folder messages are sent to when using the One\_Click Archive feature in Outlook clients that support it. |
| [Clutter](#Clutter) | The clutter folder low-priority messages are moved to when using the Clutter feature. |
| [Conflicts](#Conflicts) | The folder that contains conflicting items in the mailbox. |
| [ContactFolders](#ContactFolders) | Mail folders root |
| [ConversationHistory](#ConversationHistory) | The folder where Skype saves IM conversations (if Skype is configured to do so). |
| [DeletedItems](#DeletedItems) | The folder items are moved to when they are deleted. |
| [Drafts](#Drafts) | The folder that contains unsent messages. |
| [Inbox](#Inbox) | The inbox folder. |
| [Junkemail](#Junkemail) | The junk email folder. |
| [LocalFailures](#LocalFailures) | The folder that contains items that exist on the local client but could not be uploaded to the server. |
| [MailFolders](#MailFolders) | Mail folders root |
| [MsgFolderRoot](#MsgFolderRoot) | The "Top of Information Store" folder. |
| [Outbox](#Outbox) | The outbox folder. |
| [RecoverableItemsDeletions](#RecoverableItemsDeletions) | The folder that contains soft-deleted items: deleted either from the Deleted Items folder, or by pressing shift+delete in Outlook. |
| [Scheduled](#Scheduled) | The folder that contains messages that are scheduled to reappear in the inbox using the Schedule feature in Outlook for iOS. |
| [SearchFolders](#SearchFolders) | The parent folder for all search folders defined in the user's mailbox. |
| [SentItems](#SentItems) | The sent items folder. |
| [ServerFailures](#ServerFailures) | The folder that contains items that exist on the server but could not be synchronized to the local client. |
| [SyncIssues](#SyncIssues) | The folder that contains synchronization logs created by Outlook. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GraphKnownFolders() {#GraphKnownFolders--}
```
public GraphKnownFolders()
```


### Archive {#Archive}
```
public static final String Archive
```


The archive folder messages are sent to when using the One\_Click Archive feature in Outlook clients that support it. Note: this is not the same as the Archive Mailbox feature of Exchange online.

### Clutter {#Clutter}
```
public static final String Clutter
```


The clutter folder low-priority messages are moved to when using the Clutter feature.

### Conflicts {#Conflicts}
```
public static final String Conflicts
```


The folder that contains conflicting items in the mailbox.

### ContactFolders {#ContactFolders}
```
public static final String ContactFolders
```


Mail folders root

### ConversationHistory {#ConversationHistory}
```
public static final String ConversationHistory
```


The folder where Skype saves IM conversations (if Skype is configured to do so).

### DeletedItems {#DeletedItems}
```
public static final String DeletedItems
```


The folder items are moved to when they are deleted.

### Drafts {#Drafts}
```
public static final String Drafts
```


The folder that contains unsent messages.

### Inbox {#Inbox}
```
public static final String Inbox
```


The inbox folder.

### Junkemail {#Junkemail}
```
public static final String Junkemail
```


The junk email folder.

### LocalFailures {#LocalFailures}
```
public static final String LocalFailures
```


The folder that contains items that exist on the local client but could not be uploaded to the server.

### MailFolders {#MailFolders}
```
public static final String MailFolders
```


Mail folders root

### MsgFolderRoot {#MsgFolderRoot}
```
public static final String MsgFolderRoot
```


The "Top of Information Store" folder. This folder is the parent folder for folders that are displayed in normal mail clients, such as the inbox.

### Outbox {#Outbox}
```
public static final String Outbox
```


The outbox folder.

### RecoverableItemsDeletions {#RecoverableItemsDeletions}
```
public static final String RecoverableItemsDeletions
```


The folder that contains soft-deleted items: deleted either from the Deleted Items folder, or by pressing shift+delete in Outlook. This folder is not visible in any Outlook email client, but end users can interact with it through the Recover Deleted Items from Server feature in Outlook or Outlook on the web.

### Scheduled {#Scheduled}
```
public static final String Scheduled
```


The folder that contains messages that are scheduled to reappear in the inbox using the Schedule feature in Outlook for iOS.

### SearchFolders {#SearchFolders}
```
public static final String SearchFolders
```


The parent folder for all search folders defined in the user's mailbox.

### SentItems {#SentItems}
```
public static final String SentItems
```


The sent items folder.

### ServerFailures {#ServerFailures}
```
public static final String ServerFailures
```


The folder that contains items that exist on the server but could not be synchronized to the local client.

### SyncIssues {#SyncIssues}
```
public static final String SyncIssues
```


The folder that contains synchronization logs created by Outlook.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

