---
title: ExchangeMessageInfo
second_title: Aspose.Email for Java API Reference
description: The ExchangeMessageInfo represents the E-Mail message info fetched from the Exchange Store.
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
| [close()](#close--) |  |
| [dispose()](#dispose--) | Performs tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachments()](#getAttachments--) | Gets message attachments |
| [getBcc()](#getBcc--) | Gets blind carbon copy of the E-Mail message. |
| [getCC()](#getCC--) | Gets CC of the E-Mail message. |
| [getClass()](#getClass--) |  |
| [getDate()](#getDate--) | The origination date specifies the date and time at which the creator of the message indicated that the message was complete and ready to enter the mail delivery system. |
| [getFrom()](#getFrom--) | Gets the list of authors of this message. |
| [getHeaders()](#getHeaders--) | Gets the Headers of the E-Mail message. |
| [getInternalDate()](#getInternalDate--) | The internal date and time of the message on the server. |
| [getListUnsubscribe()](#getListUnsubscribe--) | The List-Unsubscribe field describes the command (preferably using mail) to directly unsubscribe the user(removing them from the list). |
| [getMessageClass()](#getMessageClass--) | Gets a string representing the class for the message. |
| [getMessageId()](#getMessageId--) | Gets the message ID. |
| [getMessageInfoType()](#getMessageInfoType--) | Gets the type of the message |
| [getProperties()](#getProperties--) | Gets a mapi properties. |
| [getReplyTo()](#getReplyTo--) | Gets the list of addresses that should receive replies to this message. |
| [getSender()](#getSender--) | Gets the sender of this message. |
| [getSize()](#getSize--) | Gets the size of the E-Mail message. |
| [getSubject()](#getSubject--) | Gets the Subject of the E-Mail message. |
| [getTo()](#getTo--) | Gets the receiptants of the E-Mail message. |
| [getUniqueUri()](#getUniqueUri--) | Gets the unique URI of message. |
| [hasAttachments()](#hasAttachments--) | Gets a value indicating whether the message contains at least one attachment. |
| [hashCode()](#hashCode--) |  |
| [isRead()](#isRead--) | Gets a value indicating whether the message has been read |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | A string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public void dispose()
```


Performs tasks associated with freeing, releasing, or resetting unmanaged resources.

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
### getAttachments() {#getAttachments--}
```
public ExchangeAttachmentInfoCollection getAttachments()
```


Gets message attachments

**Returns:**
[ExchangeAttachmentInfoCollection](../../com.aspose.email/exchangeattachmentinfocollection)
### getBcc() {#getBcc--}
```
public MailAddressCollection getBcc()
```


Gets blind carbon copy of the E-Mail message.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getCC() {#getCC--}
```
public MailAddressCollection getCC()
```


Gets CC of the E-Mail message.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDate() {#getDate--}
```
public Date getDate()
```


The origination date specifies the date and time at which the creator of the message indicated that the message was complete and ready to enter the mail delivery system. For instance, this might be the time that a user pushes the "send" or "submit" button in an application program. In any case, it is specifically not intended to convey the time that the message is actually transported, but rather the time at which the human or other creator of the message has put the message into its final form, ready for transport. (For example, a portable computer user who is not connected to a network might queue a message for delivery. The origination date is intended to contain the date and time that the user queued the message, not the time when the user connected to the network to send the message.)

**Returns:**
java.util.Date
### getFrom() {#getFrom--}
```
public final MailAddress getFrom()
```


Gets the list of authors of this message.

Value: The list of authors of this message.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getHeaders() {#getHeaders--}
```
public final HeaderCollection getHeaders()
```


Gets the Headers of the E-Mail message.

Value: The headers.

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getInternalDate() {#getInternalDate--}
```
public Date getInternalDate()
```


The internal date and time of the message on the server. This is not the date and time in the [RFC-2822] header, but rather a date and time which reflects when the message was received. - In the case of messages delivered via [SMTP], this SHOULD be the date and time of final delivery of the message as defined by[SMTP]. - In the case of messages delivered by the IMAP4rev1 COPY command, this SHOULD be the internal date and time of the source message. - In the case of messages delivered by the IMAP4rev1 APPEND command, this SHOULD be the date and time as specified in the APPEND command description. - All other cases are implementation defined.

**Returns:**
java.util.Date
### getListUnsubscribe() {#getListUnsubscribe--}
```
public final String getListUnsubscribe()
```


The List-Unsubscribe field describes the command (preferably using mail) to directly unsubscribe the user(removing them from the list). For more details please see https://tools.ietf.org/html/rfc2369

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
### getMessageId() {#getMessageId--}
```
public final String getMessageId()
```


Gets the message ID.

Value: The message id string.

**Returns:**
java.lang.String
### getMessageInfoType() {#getMessageInfoType--}
```
public int getMessageInfoType()
```


Gets the type of the message

**Returns:**
int
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


Gets a mapi properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getReplyTo() {#getReplyTo--}
```
public final MailAddressCollection getReplyTo()
```


Gets the list of addresses that should receive replies to this message.

Value: The list of addresses.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getSender() {#getSender--}
```
public final MailAddress getSender()
```


Gets the sender of this message.

Value: The sender of this message.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getSize() {#getSize--}
```
public final long getSize()
```


Gets the size of the E-Mail message.

Value: The size of the E-Mail message.

**Returns:**
long
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the Subject of the E-Mail message.

**Returns:**
java.lang.String
### getTo() {#getTo--}
```
public MailAddressCollection getTo()
```


Gets the receiptants of the E-Mail message.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getUniqueUri() {#getUniqueUri--}
```
public String getUniqueUri()
```


Gets the unique URI of message. The Exchange Id is a unique tag that specifies an email/folder combination.

Value: The string that represents the unique URI.

**Returns:**
java.lang.String
### hasAttachments() {#hasAttachments--}
```
public boolean hasAttachments()
```


Gets a value indicating whether the message contains at least one attachment.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isRead() {#isRead--}
```
public boolean isRead()
```


Gets a value indicating whether the message has been read

**Returns:**
boolean
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


A string that represents the current object.

**Returns:**
java.lang.String - Returns a string that represents the current object.
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

