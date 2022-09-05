---
title: ImapFolderInfo
second_title: Aspose.Email for Java API Reference
description:  Represents an IMAP folder.
type: docs
weight: 307
url: /java/com.aspose.email/imapfolderinfo/
---
**Inheritance:**
java.lang.Object
```
public final class ImapFolderInfo
```

Represents an IMAP folder.
## Fields

| Field | Description |
| --- | --- |
| [IN_BOX](#IN-BOX) | Gets inbox name. |
## Methods

| Method | Description |
| --- | --- |
| [getSelectable()](#getSelectable--) | Gets a value indicating whether it is possible to select this folder. |
| [getMarked()](#getMarked--) | Gets a value indicating whether it is marked this folder. |
| [hasChildren()](#hasChildren--) | Gets value indicating whether folder contains subfolders. |
| [getFolderType()](#getFolderType--) | Gets information about folder purpose in case if it is used as special folder. |
| [getRemote()](#getRemote--) | Gets value indicating that a folder is a remote mailbox. |
| [getSubscribed()](#getSubscribed--) | Gets value that indicates that a folder name is subscribed to. |
| [getNonExistent()](#getNonExistent--) | Gets value indicating whether a folder name is referred to an existing folder. |
| [getNoInferiors()](#getNoInferiors--) | Gets a value indicating whether this folder can have child levels. |
| [getName()](#getName--) | Gets the name of the folder. |
| [getNewMessageCount()](#getNewMessageCount--) | Gets the number of the new messages. |
| [getReadOnly()](#getReadOnly--) | Gets a value indicating whether the folder is read-only. |
| [getRecentMessageCount()](#getRecentMessageCount--) | Gets the number of messages that arrived recently. |
| [getTotalMessageCount()](#getTotalMessageCount--) | Gets the number of messages in the folder. |
| [getValidityId()](#getValidityId--) | Gets the validity ID of the mailbox. |
| [getUidNotSticky()](#getUidNotSticky--) | Gets value which indicates if mail store does not support persistent UIDs This property works only if server supports UIDPLUS extension. |
| [getNoModSeq()](#getNoModSeq--) | Gets value which indicates if mailbox supports mod-sequences. |
| [getHighestModSequence()](#getHighestModSequence--) | Gets value of all messages in the mailbox. |
| [getUIDNext()](#getUIDNext--) | Gets the validity ID of the mailbox. |
| [toString()](#toString--) | Returns a string that represents the current object. |
### IN_BOX {#IN-BOX}
```
public static final String IN_BOX
```


Gets inbox name.

### getSelectable() {#getSelectable--}
```
public final boolean getSelectable()
```


Gets a value indicating whether it is possible to select this folder.

**Returns:**
boolean
### getMarked() {#getMarked--}
```
public final boolean getMarked()
```


Gets a value indicating whether it is marked this folder.

**Returns:**
boolean
### hasChildren() {#hasChildren--}
```
public final boolean hasChildren()
```


Gets value indicating whether folder contains subfolders. This option is accessible only in case if server supports IMAP4 LIST Command Extensions (rfc5258) See more: http://tools.ietf.org/html/rfc5258 If value is \`\`\` true \`\`\`, it indicates that the folder has child sub-folders that are accessible to the currently authenticated user, otherwise false.

**Returns:**
boolean
### getFolderType() {#getFolderType--}
```
public final int getFolderType()
```


Gets information about folder purpose in case if it is used as special folder. This option is accessible only in case if server supports IMAP LIST: Special-Use Mailboxes (rfc6154) See more: http://tools.ietf.org/html/rfc6154

**Returns:**
int
### getRemote() {#getRemote--}
```
public final boolean getRemote()
```


Gets value indicating that a folder is a remote mailbox. This option is accessible only in case if server supports IMAP4 LIST Command Extensions (rfc5258) See more: http://tools.ietf.org/html/rfc5258

**Returns:**
boolean
### getSubscribed() {#getSubscribed--}
```
public final boolean getSubscribed()
```


Gets value that indicates that a folder name is subscribed to. See more: http://tools.ietf.org/html/rfc5258

**Returns:**
boolean
### getNonExistent() {#getNonExistent--}
```
public final boolean getNonExistent()
```


Gets value indicating whether a folder name is referred to an existing folder. See more: http://tools.ietf.org/html/rfc5258

**Returns:**
boolean
### getNoInferiors() {#getNoInferiors--}
```
public final boolean getNoInferiors()
```


Gets a value indicating whether this folder can have child levels. If it is \`\`\` True \`\`\`, then no child levels exist now and none can be created in the future

**Returns:**
boolean
### getName() {#getName--}
```
public final String getName()
```


Gets the name of the folder.

**Returns:**
java.lang.String
### getNewMessageCount() {#getNewMessageCount--}
```
public final int getNewMessageCount()
```


Gets the number of the new messages.

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public final boolean getReadOnly()
```


Gets a value indicating whether the folder is read-only.

**Returns:**
boolean
### getRecentMessageCount() {#getRecentMessageCount--}
```
public final int getRecentMessageCount()
```


Gets the number of messages that arrived recently.

**Returns:**
int
### getTotalMessageCount() {#getTotalMessageCount--}
```
public final int getTotalMessageCount()
```


Gets the number of messages in the folder.

**Returns:**
int
### getValidityId() {#getValidityId--}
```
public final long getValidityId()
```


Gets the validity ID of the mailbox.

**Returns:**
long
### getUidNotSticky() {#getUidNotSticky--}
```
public final boolean getUidNotSticky()
```


Gets value which indicates if mail store does not support persistent UIDs This property works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315

**Returns:**
boolean
### getNoModSeq() {#getNoModSeq--}
```
public final boolean getNoModSeq()
```


Gets value which indicates if mailbox supports mod-sequences. This property works only if server supports CONDSTORE extension. Please, read more https://tools.ietf.org/html/rfc4551\#section-3.1.2

**Returns:**
boolean
### getHighestModSequence() {#getHighestModSequence--}
```
public final long getHighestModSequence()
```


Gets value of all messages in the mailbox. See more: https://tools.ietf.org/html/rfc7162

**Returns:**
long
### getUIDNext() {#getUIDNext--}
```
public final long getUIDNext()
```


Gets the validity ID of the mailbox.

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
