---
title: ImapMessageInfo
second_title: Aspose.Email for Java API Reference
description:  Represents a Imap message object.
type: docs
weight: 315
url: /java/com.aspose.email/imapmessageinfo/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MessageInfoBase](../../com.aspose.email/messageinfobase)
```
public final class ImapMessageInfo extends MessageInfoBase
```

Represents a Imap message object.
## Methods

| Method | Description |
| --- | --- |
| [getParentFolder()](#getParentFolder--) | Gets parent folder for message |
| [getInternalDate()](#getInternalDate--) | The internal date and time of the message on the server. |
| [getModificationSequence()](#getModificationSequence--) | Gets the modification sequence of this message. |
| [getFlags()](#getFlags--) | Gets the message flags. |
| [containsKeyword(String flag)](#containsKeyword-java.lang.String-) | Gets a value indicating whether Flags property contains the Keyword flag. |
| [getAnswered()](#getAnswered--) | Gets a value indicating whether Flags property contains the Answered flag. |
| [getDeleted()](#getDeleted--) | Gets a value indicating whether Flags property contains the Deleted flag. |
| [getDraft()](#getDraft--) | Gets a value indicating whether Flags property contains the Draft flag. |
| [getFlagged()](#getFlagged--) | Gets a value indicating whether Flags property contains the Flagged flag. |
| [getRecent()](#getRecent--) | Gets a value indicating whether Flags property contains the Recent flag. |
| [isRead()](#isRead--) | Gets a value indicating whether Flags property contains the Read flag. |
| [getConversationId()](#getConversationId--) | Gets a value indicating conversation id. |
| [getSequenceNumber()](#getSequenceNumber--) | Gets the message sequence number. |
| [getUniqueId()](#getUniqueId--) | Gets the message unique ID. |
| [getExtraParameters()](#getExtraParameters--) | Gets extra parameters of a message. |
| [toString()](#toString--) | Returns a string that represents the current object. |
### getParentFolder() {#getParentFolder--}
```
public final String getParentFolder()
```


Gets parent folder for message

**Returns:**
java.lang.String
### getInternalDate() {#getInternalDate--}
```
public final Date getInternalDate()
```


The internal date and time of the message on the server. This is not the date and time in the [RFC-2822] header, but rather a date and time which reflects when the message was received. - In the case of messages delivered via [SMTP], this SHOULD be the date and time of final delivery of the message as defined by[SMTP]. - In the case of messages delivered by the IMAP4rev1 COPY command, this SHOULD be the internal date and time of the source message. - In the case of messages delivered by the IMAP4rev1 APPEND command, this SHOULD be the date and time as specified in the APPEND command description. - All other cases are implementation defined.

**Returns:**
java.util.Date
### getModificationSequence() {#getModificationSequence--}
```
public final long getModificationSequence()
```


Gets the modification sequence of this message. See more: https://tools.ietf.org/html/rfc7162

**Returns:**
long
### getFlags() {#getFlags--}
```
public final ImapMessageFlags getFlags()
```


Gets the message flags.

Value: The message flags.

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags)
### containsKeyword(String flag) {#containsKeyword-java.lang.String-}
```
public final boolean containsKeyword(String flag)
```


Gets a value indicating whether Flags property contains the Keyword flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flag | java.lang.String | The Keyword flag. |

**Returns:**
boolean
### getAnswered() {#getAnswered--}
```
public final boolean getAnswered()
```


Gets a value indicating whether Flags property contains the Answered flag.

Value: The answered flag.

**Returns:**
boolean
### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


Gets a value indicating whether Flags property contains the Deleted flag.

Value: The deleted flag.

**Returns:**
boolean
### getDraft() {#getDraft--}
```
public final boolean getDraft()
```


Gets a value indicating whether Flags property contains the Draft flag.

Value: The draft flag.

**Returns:**
boolean
### getFlagged() {#getFlagged--}
```
public final boolean getFlagged()
```


Gets a value indicating whether Flags property contains the Flagged flag.

Value: The flagged flag.

**Returns:**
boolean
### getRecent() {#getRecent--}
```
public final boolean getRecent()
```


Gets a value indicating whether Flags property contains the Recent flag.

Value: The recent flag.

**Returns:**
boolean
### isRead() {#isRead--}
```
public final boolean isRead()
```


Gets a value indicating whether Flags property contains the Read flag.

Value: The read flag.

**Returns:**
boolean
### getConversationId() {#getConversationId--}
```
public final String getConversationId()
```


Gets a value indicating conversation id.

**Returns:**
java.lang.String
### getSequenceNumber() {#getSequenceNumber--}
```
public final int getSequenceNumber()
```


Gets the message sequence number.

Value: The sequence number.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


Gets the message unique ID.

Value: The unique id string.

**Returns:**
java.lang.String
### getExtraParameters() {#getExtraParameters--}
```
public final System.Collections.Generic.IGenericDictionary<String,String> getExtraParameters()
```


Gets extra parameters of a message.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,java.lang.String>
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
