---
title: MessageInfoBase
second_title: Aspose.Email for Java API Reference
description: The MessageInfo represents the E-Mail message info fetched from the mail server.
type: docs
weight: 494
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
| [close()](#close--) |  |
| [dispose()](#dispose--) | Performs tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBcc()](#getBcc--) | Gets blind carbon copy of the E-Mail message. |
| [getCC()](#getCC--) | Gets CC of the E-Mail message. |
| [getClass()](#getClass--) |  |
| [getDate()](#getDate--) | The origination date specifies the date and time at which the creator of the message indicated that the message was complete and ready to enter the mail delivery system. |
| [getFrom()](#getFrom--) | Gets the list of authors of this message. |
| [getHeaders()](#getHeaders--) | Gets the Headers of the E-Mail message. |
| [getListUnsubscribe()](#getListUnsubscribe--) | The List-Unsubscribe field describes the command (preferably using mail) to directly unsubscribe the user(removing them from the list). |
| [getMessageId()](#getMessageId--) | Gets the message ID. |
| [getProperties()](#getProperties--) | Gets a mapi properties. |
| [getReplyTo()](#getReplyTo--) | Gets the list of addresses that should receive replies to this message. |
| [getSender()](#getSender--) | Gets the sender of this message. |
| [getSize()](#getSize--) | Gets the size of the E-Mail message. |
| [getSubject()](#getSubject--) | Gets the Subject of the E-Mail message. |
| [getTo()](#getTo--) | Gets the receiptants of the E-Mail message. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | A string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageInfoBase() {#MessageInfoBase--}
```
public MessageInfoBase()
```


Initializes a new instance of the [MessageInfoBase](../../com.aspose.email/messageinfobase) class.

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
### getListUnsubscribe() {#getListUnsubscribe--}
```
public final String getListUnsubscribe()
```


The List-Unsubscribe field describes the command (preferably using mail) to directly unsubscribe the user(removing them from the list). For more details please see https://tools.ietf.org/html/rfc2369

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

