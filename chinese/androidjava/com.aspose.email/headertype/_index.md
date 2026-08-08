---
title: HeaderType
second_title: Aspose.Email for Android via Java API 参考
description: 表示互联网标准和 RFC 定义的可能出现在互联网邮件消息中的标题字段。
type: docs
weight: 157
url: /zh/androidjava/com.aspose.email/headertype/
---

**Inheritance:**
java.lang.Object
```
public final class HeaderType
```

表示互联网标准和 RFC 定义的可能出现在互联网邮件消息中的标题字段。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个布尔值，指示传入的对象 obj 是否等于此对象。 |
| [getApparentlyTo()](#getApparentlyTo--) | 当原始邮件中没有 'To:' 收件人时，通过发送电子邮件进行插入。 |
| [getApprovedBy()](#getApprovedBy--) | 发送此消息的邮件列表的版主名称；在发送到受监管的邮件列表的帖子中，这是必要的，以允许其分发给列表成员。 |
| [getBcc()](#getBcc--) | 一份发送给一个或多个收件人但主收件人未知的电子邮件副本。 |
| [getCC()](#getCC--) | 此标头可视为 'To:' 字段的扩展，因为它用于指定额外的收件人。 |
| [getClass()](#getClass--) |  |
| [getComments()](#getComments--) | 这是在 RFC2822 中定义的自由格式标头字段。 |
| [getContentTransferEncoding()](#getContentTransferEncoding--) | MIME 相关标头中的第三个。 |
| [getContentType()](#getContentType--) | ‘Content-Type’ 定义了内容的格式（字符集等）。请注意，此标头的取值在 RFC1049 和 MIME（RFC2045）中有不同的定义方式。 |
| [getDate()](#getDate--) | 此标头指定日期（和时间），通常是消息撰写并发送的日期。 |
| [getDispositionNotificationTo()](#getDispositionNotificationTo--) | 当设置 DispositionNotificationTo 字段时，会发出对 MDN（消息投递通知）的请求。 |
| [getFollowupTo()](#getFollowupTo--) | 在 Usenet 新闻中使用，以指示对文章的后续讨论（=follow-up）应发送到与被回复文章不同的一组新闻组。 |
| [getFrom()](#getFrom--) | 此字段包含希望发送此消息的人员身份。 |
| [getImportance()](#getImportance--) | 获取重要性。 |
| [getInReplyTo()](#getInReplyTo--) | 指向此消息所回复的消息。 |
| [getMIMEVersion()](#getMIMEVersion--) | 指示此消息符合 MIME 标准格式，并指明使用的 MIME 版本。 |
| [getMessageID()](#getMessageID--) | 此消息的唯一标识符。 |
| [getNewsgroups()](#getNewsgroups--) | 在 Usenet 新闻中：此文章发布到的组（或多个组）。 |
| [getReceived()](#getReceived--) | 消息经过的 MTA 路径追踪。 |
| [getReferences()](#getReferences--) | 指向其他相关消息的引用。 |
| [getReplyTo()](#getReplyTo--) | 此标头字段用于指示发送者希望回复发送到何处。 |
| [getReturnPath()](#getReturnPath--) | 在消息离开使用 'MAIL FROM' 的 SMTP 环境进行最终投递时，用于传递 MAIL FROM 信封属性中的信息。 |
| [getReturnReceiptTo()](#getReturnReceiptTo--) | 发送者可以通过包含此标头字段来请求回执。 |
| [getSender()](#getSender--) | 如果与 From: 标头字段显示的不同，则为提交消息到网络的人员或代理。 |
| [getSensitivity()](#getSensitivity--) | 获取敏感度。 |
| [getSubject()](#getSubject--) | Title, heading, subject. |
| [getTo()](#getTo--) | Primary recipients. |
| [getXConfirmReadingTo()](#getXConfirmReadingTo--) | This header requests an automated confirmation notice when the message is received or read. |
| [getXMailer()](#getXMailer--) | Information about the client software of the originator. |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回表示当前 Object 的 String。 |
| [toString(HeaderType type)](#toString-com.aspose.email.HeaderType-) | Performs an implicit conversion from [HeaderType](../../com.aspose.email/headertype) to String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个布尔值，指示传入的对象 obj 是否等于此对象。

**Parameters:**
| 参数 | 类型 | 描述 |
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


获取重要性。

值：重要性。

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getInReplyTo() {#getInReplyTo--}
```
public static HeaderType getInReplyTo()
```


指向此消息所回复的消息。

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


指向其他相关消息的引用。

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


提交消息到网络的人员或代理，如果与 From: 标头字段显示的不同。应根据 RFC 822 进行身份验证，但具体哪种身份验证方式尚不明确。

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getSensitivity() {#getSensitivity--}
```
public static HeaderType getSensitivity()
```


获取敏感度。

值：敏感度。

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getSubject() {#getSubject--}
```
public static HeaderType getSubject()
```


标题、标题行、主题。通常用作对其他消息进行回复或评论的线程指示器。

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getTo() {#getTo--}
```
public static HeaderType getTo()
```


主要收件人。例如：To: someone@somedomain.com

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getXConfirmReadingTo() {#getXConfirmReadingTo--}
```
public static HeaderType getXConfirmReadingTo()
```


此标头请求在消息收到或阅读时发送自动确认通知。通常会被忽略；可能有某些软件会对此进行处理。

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### getXMailer() {#getXMailer--}
```
public static HeaderType getXMailer()
```


关于发件人客户端软件的信息。例如：X-Mailer: Aspose.Email

**Returns:**
[HeaderType](../../com.aspose.email/headertype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


作为特定类型的哈希函数。

**Returns:**
int - 当前 Object 的哈希码。
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


返回表示当前 Object 的 String。

**Returns:**
java.lang.String - 表示当前 Object 的 String。
### toString(HeaderType type) {#toString-com.aspose.email.HeaderType-}
```
public static String toString(HeaderType type)
```


Performs an implicit conversion from [HeaderType](../../com.aspose.email/headertype) to String.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [HeaderType](../../com.aspose.email/headertype) | 要转换的 'HeaderType' 对象。 |

**Returns:**
java.lang.String - 转换的结果。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

