---
title: HeaderType
second_title: Aspose.Email for Java API Reference
description: Identifies a standard header of an Internet message such as From Subject or Content-Type.
type: docs
weight: 312
url: /java/com.aspose.email/headertype/
---

**Inheritance:**
java.lang.Object
```
public final class HeaderType
```

Identifies a standard header of an Internet message, such as  From ,  Subject  or  Content-Type .

\#toString().toString() returns the name of the header as it appears in a message, such as  Return-Path .
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified object is the same header type. |
| [getApparentlyTo()](#getApparentlyTo--) | Gets the  Apparently-To  header: the recipients, added by some servers when a message has no  To  header. |
| [getApprovedBy()](#getApprovedBy--) | Gets the  Approved-By  header: the moderator who approved a message posted to a moderated mailing list (RFC 1036). |
| [getBcc()](#getBcc--) | Gets the  Bcc  header: the blind carbon copy recipients, which the other recipients do not see. |
| [getCC()](#getCC--) | Gets the  Cc  header: the carbon copy recipients, which all recipients see. |
| [getClass()](#getClass--) |  |
| [getComments()](#getComments--) | Gets the  Comments  header: free-form text about the message (RFC 2822). |
| [getContentTransferEncoding()](#getContentTransferEncoding--) | Gets the  Content-Transfer-Encoding  header: how the body is encoded for transfer, such as  7bit ,  8bit ,  base64  or  quoted-printable  (RFC 2045). |
| [getContentType()](#getContentType--) | Gets the  Content-Type  header: the media type of the content and its parameters, such as  text/plain; charset="utf-8"  (RFC 2045). |
| [getDate()](#getDate--) | Gets the  Date  header: the date and time the message was composed, in the form  Tue, 9 Jan 2001 23:40:00 -0800 . |
| [getDispositionNotificationTo()](#getDispositionNotificationTo--) | Gets the  Disposition-Notification-To  header: the address to send a read receipt (message disposition notification) to. |
| [getFollowupTo()](#getFollowupTo--) | Gets the  Followup-To  header: the newsgroups that follow-up discussion should go to (RFC 1036). |
| [getFrom()](#getFrom--) | Gets the  From  header: the author of the message. |
| [getImportance()](#getImportance--) | Gets the  Importance  header: the importance of the message: low, normal or high. |
| [getInReplyTo()](#getInReplyTo--) | Gets the  In-Reply-To  header: the  Message-ID  of the message this one replies to. |
| [getMIMEVersion()](#getMIMEVersion--) | Gets the  MIME-Version  header: the version of MIME the message is formatted in (RFC 2045). |
| [getMessageID()](#getMessageID--) | Gets the  Message-ID  header: the unique identifier of the message (RFC 822, RFC 1036). |
| [getNewsgroups()](#getNewsgroups--) | Gets the  Newsgroups  header: the newsgroups a Usenet article was posted to (RFC 1036). |
| [getReceived()](#getReceived--) | Gets the  Received  header: a record added by each mail server the message passes through (RFC 822). |
| [getReferences()](#getReferences--) | Gets the  References  header: the  Message-ID  values of the earlier messages in the conversation. |
| [getReplyTo()](#getReplyTo--) | Gets the  Reply-To  header: the addresses that replies should go to, when they differ from the author. |
| [getReturnPath()](#getReturnPath--) | Gets the  Return-Path  header: the address that bounces are returned to: the envelope sender ( MAIL FROM ), added on final delivery. |
| [getReturnReceiptTo()](#getReturnReceiptTo--) | Gets the  Return-Receipt-To  header: requests a delivery receipt. |
| [getSender()](#getSender--) | Gets the  Sender  header: the person or agent that submitted the message, when it differs from the author in  From . |
| [getSensitivity()](#getSensitivity--) | Gets the  Sensitivity  header: the sensitivity of the message: personal, private or company confidential. |
| [getSubject()](#getSubject--) | Gets the  Subject  header: the subject of the message. |
| [getTo()](#getTo--) | Gets the  To  header: the primary recipients. |
| [getXConfirmReadingTo()](#getXConfirmReadingTo--) | Gets the  X-Confirm-Reading-To  header: requests a read confirmation. |
| [getXMailer()](#getXMailer--) | Gets the  X-Mailer  header: the software that created the message. |
| [hashCode()](#hashCode--) | Returns the hash code of the header type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returns the name of the header, such as  Return-Path . |
| [toString(HeaderType type)](#toString-com.aspose.email.HeaderType-) | Performs an implicit conversion from [HeaderType](../../com.aspose.email/headertype) to String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified object is the same header type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with. |

**Returns:**
boolean -  true  if  obj  is a [HeaderType](../../com.aspose.email/headertype) for the same header; otherwise,  false .
### getApparentlyTo() {#getApparentlyTo--}
```
public static HeaderType getApparentlyTo()
```


Gets the  Apparently-To  header: the recipients, added by some servers when a message has no  To  header. Non-standard; it can reveal BCC recipients.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getApprovedBy() {#getApprovedBy--}
```
public static HeaderType getApprovedBy()
```


Gets the  Approved-By  header: the moderator who approved a message posted to a moderated mailing list (RFC 1036). Non-standard in e-mail.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getBcc() {#getBcc--}
```
public static HeaderType getBcc()
```


Gets the  Bcc  header: the blind carbon copy recipients, which the other recipients do not see. It is removed before the message is delivered.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getCC() {#getCC--}
```
public static HeaderType getCC()
```


Gets the  Cc  header: the carbon copy recipients, which all recipients see.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComments() {#getComments--}
```
public static HeaderType getComments()
```


Gets the  Comments  header: free-form text about the message (RFC 2822).

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getContentTransferEncoding() {#getContentTransferEncoding--}
```
public static HeaderType getContentTransferEncoding()
```


Gets the  Content-Transfer-Encoding  header: how the body is encoded for transfer, such as  7bit ,  8bit ,  base64  or  quoted-printable  (RFC 2045).

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getContentType() {#getContentType--}
```
public static HeaderType getContentType()
```


Gets the  Content-Type  header: the media type of the content and its parameters, such as  text/plain; charset="utf-8"  (RFC 2045).

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getDate() {#getDate--}
```
public static HeaderType getDate()
```


Gets the  Date  header: the date and time the message was composed, in the form  Tue, 9 Jan 2001 23:40:00 -0800 . It comes from the clock of the sender's computer.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getDispositionNotificationTo() {#getDispositionNotificationTo--}
```
public static HeaderType getDispositionNotificationTo()
```


Gets the  Disposition-Notification-To  header: the address to send a read receipt (message disposition notification) to. The recipient's client may ignore the request.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getFollowupTo() {#getFollowupTo--}
```
public static HeaderType getFollowupTo()
```


Gets the  Followup-To  header: the newsgroups that follow-up discussion should go to (RFC 1036). Not standard in e-mail.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getFrom() {#getFrom--}
```
public static HeaderType getFrom()
```


Gets the  From  header: the author of the message.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getImportance() {#getImportance--}
```
public static HeaderType getImportance()
```


Gets the  Importance  header: the importance of the message: low, normal or high.

**Returns:**
[HeaderType](../../com.aspose.email/headertype) - The importance.
### getInReplyTo() {#getInReplyTo--}
```
public static HeaderType getInReplyTo()
```


Gets the  In-Reply-To  header: the  Message-ID  of the message this one replies to.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getMIMEVersion() {#getMIMEVersion--}
```
public static HeaderType getMIMEVersion()
```


Gets the  MIME-Version  header: the version of MIME the message is formatted in (RFC 2045).

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getMessageID() {#getMessageID--}
```
public static HeaderType getMessageID()
```


Gets the  Message-ID  header: the unique identifier of the message (RFC 822, RFC 1036).

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getNewsgroups() {#getNewsgroups--}
```
public static HeaderType getNewsgroups()
```


Gets the  Newsgroups  header: the newsgroups a Usenet article was posted to (RFC 1036). Not standard in e-mail, where it is used with different meanings.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getReceived() {#getReceived--}
```
public static HeaderType getReceived()
```


Gets the  Received  header: a record added by each mail server the message passes through (RFC 822).

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getReferences() {#getReferences--}
```
public static HeaderType getReferences()
```


Gets the  References  header: the  Message-ID  values of the earlier messages in the conversation.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getReplyTo() {#getReplyTo--}
```
public static HeaderType getReplyTo()
```


Gets the  Reply-To  header: the addresses that replies should go to, when they differ from the author.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getReturnPath() {#getReturnPath--}
```
public static HeaderType getReturnPath()
```


Gets the  Return-Path  header: the address that bounces are returned to: the envelope sender ( MAIL FROM ), added on final delivery.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getReturnReceiptTo() {#getReturnReceiptTo--}
```
public static HeaderType getReturnReceiptTo()
```


Gets the  Return-Receipt-To  header: requests a delivery receipt. Non-standard and rarely supported; use  Disposition-Notification-To  instead.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getSender() {#getSender--}
```
public static HeaderType getSender()
```


Gets the  Sender  header: the person or agent that submitted the message, when it differs from the author in  From .

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getSensitivity() {#getSensitivity--}
```
public static HeaderType getSensitivity()
```


Gets the  Sensitivity  header: the sensitivity of the message: personal, private or company confidential.

**Returns:**
[HeaderType](../../com.aspose.email/headertype) - The sensitivity.
### getSubject() {#getSubject--}
```
public static HeaderType getSubject()
```


Gets the  Subject  header: the subject of the message.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getTo() {#getTo--}
```
public static HeaderType getTo()
```


Gets the  To  header: the primary recipients.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getXConfirmReadingTo() {#getXConfirmReadingTo--}
```
public static HeaderType getXConfirmReadingTo()
```


Gets the  X-Confirm-Reading-To  header: requests a read confirmation. Non-standard and usually ignored.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getXMailer() {#getXMailer--}
```
public static HeaderType getXMailer()
```


Gets the  X-Mailer  header: the software that created the message.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code of the header type.

**Returns:**
int - The hash code.
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


Returns the name of the header, such as  Return-Path .

**Returns:**
java.lang.String - The name of the header.
### toString(HeaderType type) {#toString-com.aspose.email.HeaderType-}
```
public static String toString(HeaderType type)
```


Performs an implicit conversion from [HeaderType](../../com.aspose.email/headertype) to String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | [HeaderType](../../com.aspose.email/headertype) | The 'HeaderType' object to convert. |

**Returns:**
java.lang.String - The result of the conversion.
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

