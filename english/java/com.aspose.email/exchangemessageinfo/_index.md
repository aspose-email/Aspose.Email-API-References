---
title: ExchangeMessageInfo
second_title: Aspose.Email for Java API Reference
description:  The ExchangeMessageInfo represents the E-Mail message info fetched from the Exchange Store.
type: docs
weight: 221
url: /java/com.aspose.email/exchangemessageinfo/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MessageInfoBase](../../com.aspose.email/messageinfobase)
```
public abstract class ExchangeMessageInfo extends MessageInfoBase
```

The ExchangeMessageInfo represents the E-Mail message info fetched from the Exchange Store.
## Methods

| Method | Description |
| --- | --- |
| [getInternalDate()](#getInternalDate--) | The internal date and time of the message on the server. |
| [getAttachments()](#getAttachments--) | Gets message attachments |
| [getUniqueUri()](#getUniqueUri--) | Gets the unique URI of message. |
| [getMessageClass()](#getMessageClass--) | Gets a string representing the class for the message. |
| [isRead()](#isRead--) | Gets a value indicating whether the message has been read |
| [hasAttachments()](#hasAttachments--) | Gets a value indicating whether the message contains at least one attachment. |
| [getMessageInfoType()](#getMessageInfoType--) | Gets the type of the message |
### getInternalDate() {#getInternalDate--}
```
public Date getInternalDate()
```


The internal date and time of the message on the server. This is not the date and time in the [RFC-2822] header, but rather a date and time which reflects when the message was received. - In the case of messages delivered via [SMTP], this SHOULD be the date and time of final delivery of the message as defined by[SMTP]. - In the case of messages delivered by the IMAP4rev1 COPY command, this SHOULD be the internal date and time of the source message. - In the case of messages delivered by the IMAP4rev1 APPEND command, this SHOULD be the date and time as specified in the APPEND command description. - All other cases are implementation defined.

**Returns:**
java.util.Date
### getAttachments() {#getAttachments--}
```
public ExchangeAttachmentInfoCollection getAttachments()
```


Gets message attachments

**Returns:**
[ExchangeAttachmentInfoCollection](../../com.aspose.email/exchangeattachmentinfocollection)
### getUniqueUri() {#getUniqueUri--}
```
public String getUniqueUri()
```


Gets the unique URI of message. The Exchange Id is a unique tag that specifies an email/folder combination.

Value: The string that represents the unique URI.

**Returns:**
java.lang.String
### getMessageClass() {#getMessageClass--}
```
public String getMessageClass()
```


Gets a string representing the class for the message. The property corresponds to the PidTagMessageClass MAPI property.

Value: The string that represents the message class.

**Returns:**
java.lang.String
### isRead() {#isRead--}
```
public boolean isRead()
```


Gets a value indicating whether the message has been read

**Returns:**
boolean
### hasAttachments() {#hasAttachments--}
```
public boolean hasAttachments()
```


Gets a value indicating whether the message contains at least one attachment.

**Returns:**
boolean
### getMessageInfoType() {#getMessageInfoType--}
```
public int getMessageInfoType()
```


Gets the type of the message

**Returns:**
int
