---
title: ImapFolderInfo
second_title: Aspose.Email for Java API Reference
description: Represents an IMAP folder.
type: docs
weight: 325
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFolderType()](#getFolderType--) | Gets information about folder purpose in case if it is used as special folder. |
| [getHighestModSequence()](#getHighestModSequence--) | Gets value of all messages in the mailbox. |
| [getMarked()](#getMarked--) | Gets a value indicating whether it is marked this folder. |
| [getName()](#getName--) | Gets the name of the folder. |
| [getNewMessageCount()](#getNewMessageCount--) | Gets the number of the new messages. |
| [getNoInferiors()](#getNoInferiors--) | Gets a value indicating whether this folder can have child levels. |
| [getNoModSeq()](#getNoModSeq--) | Gets value which indicates if mailbox supports mod-sequences. |
| [getNonExistent()](#getNonExistent--) | Gets value indicating whether a folder name is referred to an existing folder. |
| [getReadOnly()](#getReadOnly--) | Gets a value indicating whether the folder is read-only. |
| [getRecentMessageCount()](#getRecentMessageCount--) | Gets the number of messages that arrived recently. |
| [getRemote()](#getRemote--) | Gets value indicating that a folder is a remote mailbox. |
| [getSelectable()](#getSelectable--) | Gets a value indicating whether it is possible to select this folder. |
| [getSubscribed()](#getSubscribed--) | Gets value that indicates that a folder name is subscribed to. |
| [getTotalMessageCount()](#getTotalMessageCount--) | Gets the number of messages in the folder. |
| [getUIDNext()](#getUIDNext--) | Gets the validity ID of the mailbox. |
| [getUidNotSticky()](#getUidNotSticky--) | Gets value which indicates if mail store does not support persistent UIDs This property works only if server supports UIDPLUS extension. |
| [getValidityId()](#getValidityId--) | Gets the validity ID of the mailbox. |
| [hasChildren()](#hasChildren--) | Gets value indicating whether folder contains subfolders. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IN_BOX {#IN-BOX}
```
public static final String IN_BOX
```


Gets inbox name.

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
### getFolderType() {#getFolderType--}
```
public final int getFolderType()
```


Gets information about folder purpose in case if it is used as special folder. This option is accessible only in case if server supports IMAP LIST: Special-Use Mailboxes (rfc6154) See more: http://tools.ietf.org/html/rfc6154

**Returns:**
int
### getHighestModSequence() {#getHighestModSequence--}
```
public final long getHighestModSequence()
```


Gets value of all messages in the mailbox. See more: https://tools.ietf.org/html/rfc7162

**Returns:**
long
### getMarked() {#getMarked--}
```
public final boolean getMarked()
```


Gets a value indicating whether it is marked this folder.

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
### getNoInferiors() {#getNoInferiors--}
```
public final boolean getNoInferiors()
```


Gets a value indicating whether this folder can have child levels. If it is  True , then no child levels exist now and none can be created in the future

**Returns:**
boolean
### getNoModSeq() {#getNoModSeq--}
```
public final boolean getNoModSeq()
```


Gets value which indicates if mailbox supports mod-sequences. This property works only if server supports CONDSTORE extension. Please, read more https://tools.ietf.org/html/rfc4551\#section-3.1.2

**Returns:**
boolean
### getNonExistent() {#getNonExistent--}
```
public final boolean getNonExistent()
```


Gets value indicating whether a folder name is referred to an existing folder. See more: http://tools.ietf.org/html/rfc5258

**Returns:**
boolean
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
### getRemote() {#getRemote--}
```
public final boolean getRemote()
```


Gets value indicating that a folder is a remote mailbox. This option is accessible only in case if server supports IMAP4 LIST Command Extensions (rfc5258) See more: http://tools.ietf.org/html/rfc5258

**Returns:**
boolean
### getSelectable() {#getSelectable--}
```
public final boolean getSelectable()
```


Gets a value indicating whether it is possible to select this folder.

**Returns:**
boolean
### getSubscribed() {#getSubscribed--}
```
public final boolean getSubscribed()
```


Gets value that indicates that a folder name is subscribed to. See more: http://tools.ietf.org/html/rfc5258

**Returns:**
boolean
### getTotalMessageCount() {#getTotalMessageCount--}
```
public final int getTotalMessageCount()
```


Gets the number of messages in the folder.

**Returns:**
int
### getUIDNext() {#getUIDNext--}
```
public final long getUIDNext()
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
### getValidityId() {#getValidityId--}
```
public final long getValidityId()
```


Gets the validity ID of the mailbox.

**Returns:**
long
### hasChildren() {#hasChildren--}
```
public final boolean hasChildren()
```


Gets value indicating whether folder contains subfolders. This option is accessible only in case if server supports IMAP4 LIST Command Extensions (rfc5258) See more: http://tools.ietf.org/html/rfc5258 If value is  true , it indicates that the folder has child sub-folders that are accessible to the currently authenticated user, otherwise false.

**Returns:**
boolean
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


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
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

