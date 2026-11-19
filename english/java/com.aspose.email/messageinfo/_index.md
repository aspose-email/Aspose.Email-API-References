---
title: MessageInfo
second_title: Aspose.Email for Java API Reference
description: Summary information about a message in a PST such as its subject recipients and message class available without loading the whole message.
type: docs
weight: 519
url: /java/com.aspose.email/messageinfo/
---

**Inheritance:**
java.lang.Object
```
public final class MessageInfo
```

Summary information about a message in a PST, such as its subject, recipients and message class, available without loading the whole message.

Use  PersonalStorage.extractMessage  to load the full message with its body and attachments.
## Constructors

| Constructor | Description |
| --- | --- |
| [MessageInfo()](#MessageInfo--) | Initializes a new instance of the [MessageInfo](../../com.aspose.email/messageinfo) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisplayCC()](#getDisplayCC--) | Gets the display names of the Cc recipients, as shown in the Cc line. |
| [getDisplayTo()](#getDisplayTo--) | Gets the display names of the To recipients, as shown in the To line. |
| [getEntryId()](#getEntryId--) | Gets the entry ID of the message, which identifies it in the PST. |
| [getEntryIdString()](#getEntryIdString--) | Gets the entry ID of the message as a string. |
| [getImportance()](#getImportance--) | Gets the importance of the message. |
| [getMessageClass()](#getMessageClass--) | Gets the message class, which defines the type of the item, for example  IPM.Note  for an email or  IPM.Contact  for a contact. |
| [getProperties()](#getProperties--) | Gets the MAPI properties of the message that are read with the message list. |
| [getSenderRepresentativeName()](#getSenderRepresentativeName--) | Gets the display name of the user the message was sent on behalf of (the PR\_SENT\_REPRESENTING\_NAME property). |
| [getSensitivity()](#getSensitivity--) | Gets the sensitivity of the message. |
| [getSubject()](#getSubject--) | Gets the message subject. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageInfo() {#MessageInfo--}
```
public MessageInfo()
```


Initializes a new instance of the [MessageInfo](../../com.aspose.email/messageinfo) class.

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
### getDisplayCC() {#getDisplayCC--}
```
public final String getDisplayCC()
```


Gets the display names of the Cc recipients, as shown in the Cc line.

**Returns:**
java.lang.String - The Cc line.
### getDisplayTo() {#getDisplayTo--}
```
public final String getDisplayTo()
```


Gets the display names of the To recipients, as shown in the To line.

**Returns:**
java.lang.String - The To line.
### getEntryId() {#getEntryId--}
```
public final byte[] getEntryId()
```


Gets the entry ID of the message, which identifies it in the PST.

**Returns:**
byte[] - The entry ID as a byte array.
### getEntryIdString() {#getEntryIdString--}
```
public final String getEntryIdString()
```


Gets the entry ID of the message as a string.

**Returns:**
java.lang.String - The entry ID in the string form accepted by  PersonalStorage.extractMessage .
### getImportance() {#getImportance--}
```
public final int getImportance()
```


Gets the importance of the message.

**Returns:**
int - The importance.
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Gets the message class, which defines the type of the item, for example  IPM.Note  for an email or  IPM.Contact  for a contact.

**Returns:**
java.lang.String - The message class.
### getProperties() {#getProperties--}
```
public final MapiPropertyCollection getProperties()
```


Gets the MAPI properties of the message that are read with the message list.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The properties of the message.
### getSenderRepresentativeName() {#getSenderRepresentativeName--}
```
public final String getSenderRepresentativeName()
```


Gets the display name of the user the message was sent on behalf of (the PR\_SENT\_REPRESENTING\_NAME property).

**Returns:**
java.lang.String - The sender representative name.
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets the sensitivity of the message.

**Returns:**
int - The sensitivity.
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the message subject.

**Returns:**
java.lang.String - The subject.
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

