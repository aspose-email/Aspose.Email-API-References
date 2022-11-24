---
title: HeaderType
second_title: Aspose.Email for Java API Reference
description: Represents the Internet standards and RFCs define header fields which may occur on Internet Mail Messages .
type: docs
weight: 290
url: /java/com.aspose.email/headertype/
---

**Inheritance:**
java.lang.Object
```
public final class HeaderType
```

Represents the Internet standards and RFCs define header fields which may occur on Internet Mail Messages .
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a boolean indicating if the passed in object obj is Equal to this. |
| [getApparentlyTo()](#getApparentlyTo--) | Inserted by sending e-mail when there is no 'To:' recipient in the original message. |
| [getApprovedBy()](#getApprovedBy--) | Name of the moderator of the mailing list to which this message is sent; necessary on a posting sent to a moderated mailing list to allow its distribution to the list members. |
| [getBcc()](#getBcc--) | A copy of the e-mail message that is sent to one or more recipients without the knowledge of the primary recipients. |
| [getCC()](#getCC--) | This header can be considered an extension of the 'To:' field as it is used to specifiy additional recipients. |
| [getClass()](#getClass--) |  |
| [getComments()](#getComments--) | This is a free-form header field defined in RFC2822. |
| [getContentTransferEncoding()](#getContentTransferEncoding--) | The third of the MIME-related headers. |
| [getContentType()](#getContentType--) | The 'Content-Type' defines the format of content (character set etc.) Note that the values for this header are defined in different ways in RFC1049 and in MIME (RFC2045). |
| [getDate()](#getDate--) | This header specifies a date (and time), normally the date the message was composed and sent. |
| [getDispositionNotificationTo()](#getDispositionNotificationTo--) | When the DispositionNotificationTo field is set, a request for a MDN (Message Delivery Notification) is made. |
| [getFollowupTo()](#getFollowupTo--) | Used in Usenet News to indicate that future discussions (=follow-up) on an article should go to a different set of newsgroups than the replied-to article. |
| [getFrom()](#getFrom--) | This field contains the identity of the person(s) who wished this message to be sent. |
| [getImportance()](#getImportance--) | Gets the importance. |
| [getInReplyTo()](#getInReplyTo--) | Reference to message which this message is a reply to. |
| [getMIMEVersion()](#getMIMEVersion--) | An indicator that this message is formatted according to the MIME standard, and an indication of which version of MIME is utilized. |
| [getMessageID()](#getMessageID--) | Unique ID of this message. |
| [getNewsgroups()](#getNewsgroups--) | In Usenet News: group(s) to which this article was posted. |
| [getReceived()](#getReceived--) | Trace of MTAs which a message has passed. |
| [getReferences()](#getReferences--) | Reference to other related messages. |
| [getReplyTo()](#getReplyTo--) | This header field is meant to indicate where the sender wants replies to go. |
| [getReturnPath()](#getReturnPath--) | Used to convey the information from the MAIL FROM envelope attribute in final delivery, when the message leaves the SMTP environment in which 'MAIL FROM' is used. |
| [getReturnReceiptTo()](#getReturnReceiptTo--) | A sender can request a return-receipt by including this header field. |
| [getSender()](#getSender--) | The person or agent submitting the message to the network, if other than shown by the From: header field. |
| [getSensitivity()](#getSensitivity--) | Gets the sensitivity. |
| [getSubject()](#getSubject--) | Title, heading, subject. |
| [getTo()](#getTo--) | Primary recipients. |
| [getXConfirmReadingTo()](#getXConfirmReadingTo--) | This header requests an automated confirmation notice when the message is received or read. |
| [getXMailer()](#getXMailer--) | Information about the client software of the originator. |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returns a String that represents the current Object. |
| [toString(HeaderType type)](#toString-com.aspose.email.HeaderType-) | Performs an implicit conversion from [HeaderType](../../com.aspose.email/headertype) to String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a boolean indicating if the passed in object obj is Equal to this.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The HeaderType object to compare. |

**Returns:**
boolean - Returns true if objects are equal, otherwise returns false
### getApparentlyTo() {#getApparentlyTo--}
```
public static HeaderType getApparentlyTo()
```


Inserted by sending e-mail when there is no 'To:' recipient in the original message. This causes the recipients derived from the envelope to be listed in the message heading. This behavior is not quite proper, MTAs should not modify headers (except inserting Received lines), and it can in some cases cause Bcc recipients to be wrongly divulged to non-Bcc recipients. Example: Apparently-To: someone@somedomain.com Non-standard header that is discouraged in use, mentioned in RFC1211.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getApprovedBy() {#getApprovedBy--}
```
public static HeaderType getApprovedBy()
```


Name of the moderator of the mailing list to which this message is sent; necessary on a posting sent to a moderated mailing list to allow its distribution to the list members. Example: Approved-By: someone@somedomain.com Non-standard for use in e-mail. Defined in RFC1036.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getBcc() {#getBcc--}
```
public static HeaderType getBcc()
```


A copy of the e-mail message that is sent to one or more recipients without the knowledge of the primary recipients. Primary recipients are listed in the To: and Cc: lines. This is useful if you want to copy a message to many people without each of them seeing who the other recipients are. If you see this header on incoming mail, something is wrong because it does not appear in the headers.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getCC() {#getCC--}
```
public static HeaderType getCC()
```


This header can be considered an extension of the 'To:' field as it is used to specifiy additional recipients. In this case, the copy of an e-mail message sent to a recipient has the recipient's address appearing in the message. This is useful if you want to copy a message to many people with each of them seeing who the other recipients are; contrast with Bcc above. This header does appear in incoming e-mail. Exmple: Cc: gboyd@netcom.com

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


This is a free-form header field defined in RFC2822. The header is used to place explanatory text into the header portion of an e-mail message. The field may contain arbitrary text. Exmple: Comments: Authenticated sender is someone@somedonmain.com.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getContentTransferEncoding() {#getContentTransferEncoding--}
```
public static HeaderType getContentTransferEncoding()
```


The third of the MIME-related headers. Indicates the coding method used in a MIME message body. It has no direct relevance to the delivery of e-mail, but it affects how MIME compliant mail programs interpret the content of the message. Defined in RFC2045. Content-Transfer-Encoding: 8bit Content-transfer-encoding: 7BIT Content-Transfer-Encoding: 7bit Content-Transfer-Encoding: base64 Content-Transfer-Encoding: quoted-printable

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getContentType() {#getContentType--}
```
public static HeaderType getContentType()
```


The 'Content-Type' defines the format of content (character set etc.) Note that the values for this header are defined in different ways in RFC1049 and in MIME (RFC2045). Look for the MIME-version: header to understand if Content-Type is to be interpreted according to RFC1049 or according to MIME (RFC2045). The MIME definition should be used in generating mail. Historically, Content-Type field was proposed in RFC1049. In it, Content-Type did not distinguish type and subtype like RFC2045 does. Example: Content-Type: text/plain; charset='us-ascii' Content-type: text/plain; charset=US-ASCII Content-Type: text/plain; charset='iso-8859-1' Content-Type: text/plain; charset=koi8-r Content-Type: text/plain; charset=unknown-8bit

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getDate() {#getDate--}
```
public static HeaderType getDate()
```


This header specifies a date (and time), normally the date the message was composed and sent. In X.400 mail systems, the time a message was submitted. Some Internet mail systems also use the date when the message was submitted. If this header is omitted by the sender's computer, it might conceivably be added by a mail server or even by some other machine along the route. What you may not know is that the information in the 'Date:' line is supplied by the time on the sender's computer, which may or may not be set correctly. Also, the 'Date:' header does not normally indicate when the message was sent, but only when it was composed. The date is in the form 3 character day-of-week (Sun - Sat), day number (1-31) dd, 3-character month name, 4-digit year yyyy, followed by time (24-hour) hh:mm:ss and zone zzz format. Time Zone (zzz) is either the 3-character time zone or the local differential in hours and minutes offset from UTC (Universal Time Coordinated - old Greenwich Mean Time). '-' indicates west and '+' indicates east of UTC. No standard Time Zone definitions seem to exist. Many UNIX versions understand a great range of abbreviations, but the most exhaustive list I found was the GNU tar manual Timezone item and documentation for the Perl date manipulation module TIMEZONES. Example: Date: Tue, 9 Jan 2001 23:40:00 -0800 Date: Sun, 1 Apr 2001 22:52:04 EDT Date: Mon, 2 Apr 2001 16:02:19 +0200 Date: Fri, 30 Mar 2001 10:47:15 -0800

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getDispositionNotificationTo() {#getDispositionNotificationTo--}
```
public static HeaderType getDispositionNotificationTo()
```


When the DispositionNotificationTo field is set, a request for a MDN (Message Delivery Notification) is made. The recipient's email software (Outlook, Eudora, etc.) may silently ignore the request, or it may prompt the user for permission to send the MDN. There is no guarantee of the 'return-receipt'. The DispositionNotificationTo field is the de facto standard for requesting return-receipts (i.e. MDN, or message delivery notifications).

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getFollowupTo() {#getFollowupTo--}
```
public static HeaderType getFollowupTo()
```


Used in Usenet News to indicate that future discussions (=follow-up) on an article should go to a different set of newsgroups than the replied-to article. The most common usage is when an article is posted to several newsgroups, and further discussions is to take place in only one of them. Defined in RFC 1036: 2.2.3, not standardized for use in e-mail.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getFrom() {#getFrom--}
```
public static HeaderType getFrom()
```


This field contains the identity of the person(s) who wished this message to be sent. The message-creation process should default this field to be a single, authenticated machine address, indicating the AGENT (person, system or process) composing the message. If this is not done, the 'Sender:' field MUST be present. If the 'From:' field IS defaulted this way, the 'Sender:' field is optional and is redundant with the 'From:' field. Example: From: 'Mr. Some One' someone@somedomain.com

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getImportance() {#getImportance--}
```
public static HeaderType getImportance()
```


Gets the importance.

Value: The importance.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getInReplyTo() {#getInReplyTo--}
```
public static HeaderType getInReplyTo()
```


Reference to message which this message is a reply to.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getMIMEVersion() {#getMIMEVersion--}
```
public static HeaderType getMIMEVersion()
```


An indicator that this message is formatted according to the MIME standard, and an indication of which version of MIME is utilized. Defined in RFC 2045

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getMessageID() {#getMessageID--}
```
public static HeaderType getMessageID()
```


Unique ID of this message. Defined In RFC 822: 4.6.1 ,RFC 1036: 2.1.5.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getNewsgroups() {#getNewsgroups--}
```
public static HeaderType getNewsgroups()
```


In Usenet News: group(s) to which this article was posted. Some systems provide this header field also in e-mail although it is not standardized there. Unfortunately, the header field can appear in e-mail with three different and contradictory meanings: (a) Indicating the newsgroup recipient of an article/message sent to both e-mail and Usenet News recipients. (b) In a message adressed to some mail to news gateways, indicates the newsgroup(s) that the message is to be posted to. (c) In a personally addressed reply to an article in a news-group, indicating the newsgroup in which this discussion originated. Defined in RFC 1036: 2.1.3, not standardized and controversial for use in e-mail.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getReceived() {#getReceived--}
```
public static HeaderType getReceived()
```


Trace of MTAs which a message has passed. Defined in RFC 822

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getReferences() {#getReferences--}
```
public static HeaderType getReferences()
```


Reference to other related messages.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getReplyTo() {#getReplyTo--}
```
public static HeaderType getReplyTo()
```


This header field is meant to indicate where the sender wants replies to go. Unfortunately, this is ambiguous, since there are different kinds of replies, which the sender may wish to go to different addresses. In particular, there are personal replies intended for only one person, and group replies, intended for the whole group of people who read the replied-to message (often a mailing list, anewsgroup name cannot appear here because of different syntax, see 'FollowupTo' .).

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getReturnPath() {#getReturnPath--}
```
public static HeaderType getReturnPath()
```


Used to convey the information from the MAIL FROM envelope attribute in final delivery, when the message leaves the SMTP environment in which 'MAIL FROM' is used. ///

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getReturnReceiptTo() {#getReturnReceiptTo--}
```
public static HeaderType getReturnReceiptTo()
```


A sender can request a return-receipt by including this header field. The return-receipt is sent to the Return-Path address of the email and not to the address specified in the Return-Receipt-To header field. This header is non-standard and mostly not supported. Use Disposition-Notification-To instead. Even if supported, there is no guarantee of a receipt being sent.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getSender() {#getSender--}
```
public static HeaderType getSender()
```


The person or agent submitting the message to the network, if other than shown by the From: header field. Should be authenticated, according to RFC 822, but what kind of authentication is not clear.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getSensitivity() {#getSensitivity--}
```
public static HeaderType getSensitivity()
```


Gets the sensitivity.

Value: The sensitivity.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getSubject() {#getSubject--}
```
public static HeaderType getSubject()
```


Title, heading, subject. Often used as thread indicator for messages replying to or commenting on other messages.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getTo() {#getTo--}
```
public static HeaderType getTo()
```


Primary recipients. Example: To: someone@somedomain.com

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getXConfirmReadingTo() {#getXConfirmReadingTo--}
```
public static HeaderType getXConfirmReadingTo()
```


This header requests an automated confirmation notice when the message is received or read. It is typically ignored; presumably some software acts on it.

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getXMailer() {#getXMailer--}
```
public static HeaderType getXMailer()
```


Information about the client software of the originator. Example: X-Mailer: Aspose.Email

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current Object.
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


Returns a String that represents the current Object.

**Returns:**
java.lang.String - A String that represents the current Object.
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

