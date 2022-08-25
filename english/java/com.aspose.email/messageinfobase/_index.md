---
title: MessageInfoBase
second_title: Aspose.Email for Java API Reference
description:  The MessageInfo represents the E-Mail message info fetched from the mail server.
type: docs
weight: 490
url: /java/com.aspose.email/messageinfobase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public abstract class MessageInfoBase implements System.IDisposable, Closeable
```

The MessageInfo represents the E-Mail message info fetched from the mail server.
## Constructors

| Constructor | Description |
| --- | --- |
| [MessageInfoBase()](#MessageInfoBase--) | Initializes a new instance of the [MessageInfoBase](../../com.aspose.email/messageinfobase) class. |
## Methods

| Method | Description |
| --- | --- |
| [getHeaders()](#getHeaders--) | Gets the Headers of the E-Mail message. |
| [getSubject()](#getSubject--) | Gets the Subject of the E-Mail message. |
| [getMessageId()](#getMessageId--) | Gets the message ID. |
| [getTo()](#getTo--) | Gets the receiptants of the E-Mail message. |
| [getCC()](#getCC--) | Gets CC of the E-Mail message. |
| [getBcc()](#getBcc--) | Gets blind carbon copy of the E-Mail message. |
| [getReplyTo()](#getReplyTo--) | Gets the list of addresses that should receive replies to this message. |
| [getFrom()](#getFrom--) | Gets the list of authors of this message. |
| [getSender()](#getSender--) | Gets the sender of this message. |
| [getSize()](#getSize--) | Gets the size of the E-Mail message. |
| [getDate()](#getDate--) | The origination date specifies the date and time at which the creator of the message indicated that the message was complete and ready to enter the mail delivery system. |
| [getListUnsubscribe()](#getListUnsubscribe--) | The List-Unsubscribe field describes the command (preferably using mail) to directly unsubscribe the user(removing them from the list). |
| [dispose()](#dispose--) | Performs tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [close()](#close--) |  |
| [getProperties()](#getProperties--) | Gets a mapi properties. |
| [toString()](#toString--) | A string that represents the current object. |
### MessageInfoBase() {#MessageInfoBase--}
```
public MessageInfoBase()
```


Initializes a new instance of the [MessageInfoBase](../../com.aspose.email/messageinfobase) class.

### getHeaders() {#getHeaders--}
```
public final HeaderCollection getHeaders()
```


Gets the Headers of the E-Mail message.

Value: The headers.

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the Subject of the E-Mail message.

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
### getTo() {#getTo--}
```
public MailAddressCollection getTo()
```


Gets the receiptants of the E-Mail message.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getCC() {#getCC--}
```
public MailAddressCollection getCC()
```


Gets CC of the E-Mail message.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getBcc() {#getBcc--}
```
public MailAddressCollection getBcc()
```


Gets blind carbon copy of the E-Mail message.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getReplyTo() {#getReplyTo--}
```
public final MailAddressCollection getReplyTo()
```


Gets the list of addresses that should receive replies to this message.

Value: The list of addresses.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getFrom() {#getFrom--}
```
public final MailAddress getFrom()
```


Gets the list of authors of this message.

Value: The list of authors of this message.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
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
### getDate() {#getDate--}
```
public Date getDate()
```


The origination date specifies the date and time at which the creator of the message indicated that the message was complete and ready to enter the mail delivery system. For instance, this might be the time that a user pushes the "send" or "submit" button in an application program. In any case, it is specifically not intended to convey the time that the message is actually transported, but rather the time at which the human or other creator of the message has put the message into its final form, ready for transport. (For example, a portable computer user who is not connected to a network might queue a message for delivery. The origination date is intended to contain the date and time that the user queued the message, not the time when the user connected to the network to send the message.)

**Returns:**
java.util.Date
### getListUnsubscribe() {#getListUnsubscribe--}
```
public final String getListUnsubscribe()
```


The List-Unsubscribe field describes the command (preferably using mail) to directly unsubscribe the user(removing them from the list). For more details please see https://tools.ietf.org/html/rfc2369

**Returns:**
java.lang.String
### dispose() {#dispose--}
```
public void dispose()
```


Performs tasks associated with freeing, releasing, or resetting unmanaged resources.

### close() {#close--}
```
public void close()
```




### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


Gets a mapi properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### toString() {#toString--}
```
public String toString()
```


A string that represents the current object.

**Returns:**
java.lang.String - Returns a string that represents the current object.
