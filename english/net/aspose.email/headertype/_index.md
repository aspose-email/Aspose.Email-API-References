---
title: Class HeaderType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.HeaderType class. Represents the Internet standards and RFCs define header fields which may occur on Internet Mail Messages 
type: docs
weight: 17620
url: /net/aspose.email/headertype/
---
## HeaderType class

Represents the Internet standards and RFCs define header fields which may occur on Internet Mail Messages .

```csharp
public sealed class HeaderType
```

## Properties

| Name | Description |
| --- | --- |
| static [ApparentlyTo](../../aspose.email/headertype/apparentlyto/) { get; } | Inserted by sending e-mail when there is no "To:" recipient in the original message. This causes the recipients derived from the envelope to be listed in the message heading. This behavior is not quite proper, MTAs should not modify headers (except inserting Received lines), and it can in some cases cause Bcc recipients to be wrongly divulged to non-Bcc recipients. Example: Apparently-To: someone@somedomain.com Non-standard header that is discouraged in use, mentioned in RFC1211. |
| static [ApprovedBy](../../aspose.email/headertype/approvedby/) { get; } | Name of the moderator of the mailing list to which this message is sent; necessary on a posting sent to a moderated mailing list to allow its distribution to the list members. Example: Approved-By: someone@somedomain.com Non-standard for use in e-mail. Defined in RFC1036. |
| static [Bcc](../../aspose.email/headertype/bcc/) { get; } | A copy of the e-mail message that is sent to one or more recipients without the knowledge of the primary recipients. Primary recipients are listed in the To: and Cc: lines. This is useful if you want to copy a message to many people without each of them seeing who the other recipients are. If you see this header on incoming mail, something is wrong because it does not appear in the headers. |
| static [CC](../../aspose.email/headertype/cc/) { get; } | This header can be considered an extension of the "To:" field as it is used to specifiy additional recipients. In this case, the copy of an e-mail message sent to a recipient has the recipient's address appearing in the message. This is useful if you want to copy a message to many people with each of them seeing who the other recipients are; contrast with Bcc above. This header does appear in incoming e-mail. Exmple: Cc: gboyd@netcom.com |
| static [Comments](../../aspose.email/headertype/comments/) { get; } | This is a free-form header field defined in RFC2822. The header is used to place explanatory text into the header portion of an e-mail message. The field may contain arbitrary text. Exmple: Comments: Authenticated sender is someone@somedonmain.com. |
| static [ContentTransferEncoding](../../aspose.email/headertype/contenttransferencoding/) { get; } | The third of the MIME-related headers. Indicates the coding method used in a MIME message body. It has no direct relevance to the delivery of e-mail, but it affects how MIME compliant mail programs interpret the content of the message. Defined in RFC2045. Content-Transfer-Encoding: 8bit Content-transfer-encoding: 7BIT Content-Transfer-Encoding: 7bit Content-Transfer-Encoding: base64 Content-Transfer-Encoding: quoted-printable |
| static [ContentType](../../aspose.email/headertype/contenttype/) { get; } | The "Content-Type" defines the format of content (character set etc.) Note that the values for this header are defined in different ways in RFC1049 and in MIME (RFC2045). Look for the MIME-version: header to understand if Content-Type is to be interpreted according to RFC1049 or according to MIME (RFC2045). The MIME definition should be used in generating mail. Historically, Content-Type field was proposed in RFC1049. In it, Content-Type did not distinguish type and subtype like RFC2045 does. Example: Content-Type: text/plain; charset="us-ascii" Content-type: text/plain; charset=US-ASCII Content-Type: text/plain; charset="iso-8859-1" Content-Type: text/plain; charset=koi8-r Content-Type: text/plain; charset=unknown-8bit |
| static [Date](../../aspose.email/headertype/date/) { get; } | This header specifies a date (and time), normally the date the message was composed and sent. In X.400 mail systems, the time a message was submitted. Some Internet mail systems also use the date when the message was submitted. If this header is omitted by the sender's computer, it might conceivably be added by a mail server or even by some other machine along the route. What you may not know is that the information in the "Date:" line is supplied by the time on the sender's computer, which may or may not be set correctly. Also, the "Date:" header does not normally indicate when the message was sent, but only when it was composed. The date is in the form 3 character day-of-week (Sun - Sat), day number (1-31) dd, 3-character month name, 4-digit year yyyy, followed by time (24-hour) hh:mm:ss and zone zzz format. Time Zone (zzz) is either the 3-character time zone or the local differential in hours and minutes offset from UTC (Universal Time Coordinated - old Greenwich Mean Time). "-" indicates west and "+" indicates east of UTC. No standard Time Zone definitions seem to exist. Many UNIX versions understand a great range of abbreviations, but the most exhaustive list I found was the GNU tar manual Timezone item and documentation for the Perl date manipulation module TIMEZONES. Example: Date: Tue, 9 Jan 2001 23:40:00 -0800 Date: Sun, 1 Apr 2001 22:52:04 EDT Date: Mon, 2 Apr 2001 16:02:19 +0200 Date: Fri, 30 Mar 2001 10:47:15 -0800 |
| static [DispositionNotificationTo](../../aspose.email/headertype/dispositionnotificationto/) { get; } | When the DispositionNotificationTo field is set, a request for a MDN (Message Delivery Notification) is made. The recipient's email software (Outlook, Eudora, etc.) may silently ignore the request, or it may prompt the user for permission to send the MDN. There is no guarantee of the "return-receipt". The DispositionNotificationTo field is the de facto standard for requesting return-receipts (i.e. MDN, or message delivery notifications). |
| static [FollowupTo](../../aspose.email/headertype/followupto/) { get; } | Used in Usenet News to indicate that future discussions (=follow-up) on an article should go to a different set of newsgroups than the replied-to article. The most common usage is when an article is posted to several newsgroups, and further discussions is to take place in only one of them. Defined in RFC 1036: 2.2.3, not standardized for use in e-mail. |
| static [From](../../aspose.email/headertype/from/) { get; } | This field contains the identity of the person(s) who wished this message to be sent. The message-creation process should default this field to be a single, authenticated machine address, indicating the AGENT (person, system or process) composing the message. If this is not done, the "Sender:" field MUST be present. If the "From:" field IS defaulted this way, the "Sender:" field is optional and is redundant with the "From:" field. Example: From: "Mr. Some One" someone@somedomain.com |
| static [Importance](../../aspose.email/headertype/importance/) { get; } | Gets the importance. |
| static [InReplyTo](../../aspose.email/headertype/inreplyto/) { get; } | Reference to message which this message is a reply to. |
| static [MessageID](../../aspose.email/headertype/messageid/) { get; } | Unique ID of this message. Defined In RFC 822: 4.6.1 ,RFC 1036: 2.1.5. |
| static [MIMEVersion](../../aspose.email/headertype/mimeversion/) { get; } | An indicator that this message is formatted according to the MIME standard, and an indication of which version of MIME is utilized. Defined in RFC 2045 |
| static [Newsgroups](../../aspose.email/headertype/newsgroups/) { get; } | In Usenet News: group(s) to which this article was posted. Some systems provide this header field also in e-mail although it is not standardized there. Unfortunately, the header field can appear in e-mail with three different and contradictory meanings: (a) Indicating the newsgroup recipient of an article/message sent to both e-mail and Usenet News recipients. (b) In a message adressed to some mail to news gateways, indicates the newsgroup(s) that the message is to be posted to. (c) In a personally addressed reply to an article in a news-group, indicating the newsgroup in which this discussion originated. Defined in RFC 1036: 2.1.3, not standardized and controversial for use in e-mail. |
| static [Received](../../aspose.email/headertype/received/) { get; } | Trace of MTAs which a message has passed. Defined in RFC 822 |
| static [References](../../aspose.email/headertype/references/) { get; } | Reference to other related messages. |
| static [ReplyTo](../../aspose.email/headertype/replyto/) { get; } | This header field is meant to indicate where the sender wants replies to go. Unfortunately, this is ambiguous, since there are different kinds of replies, which the sender may wish to go to different addresses. In particular, there are personal replies intended for only one person, and group replies, intended for the whole group of people who read the replied-to message (often a mailing list, anewsgroup name cannot appear here because of different syntax, see "FollowupTo" .). |
| static [ReturnPath](../../aspose.email/headertype/returnpath/) { get; } | Used to convey the information from the MAIL FROM envelope attribute in final delivery, when the message leaves the SMTP environment in which "MAIL FROM" is used. /// |
| static [ReturnReceiptTo](../../aspose.email/headertype/returnreceiptto/) { get; } | A sender can request a return-receipt by including this header field. The return-receipt is sent to the Return-Path address of the email and not to the address specified in the Return-Receipt-To header field. This header is non-standard and mostly not supported. Use Disposition-Notification-To instead. Even if supported, there is no guarantee of a receipt being sent. |
| static [Sender](../../aspose.email/headertype/sender/) { get; } | The person or agent submitting the message to the network, if other than shown by the From: header field. Should be authenticated, according to RFC 822, but what kind of authentication is not clear. |
| static [Sensitivity](../../aspose.email/headertype/sensitivity/) { get; } | Gets the sensitivity. |
| static [Subject](../../aspose.email/headertype/subject/) { get; } | Title, heading, subject. Often used as thread indicator for messages replying to or commenting on other messages. |
| static [To](../../aspose.email/headertype/to/) { get; } | Primary recipients. Example: To: someone@somedomain.com |
| static [XConfirmReadingTo](../../aspose.email/headertype/xconfirmreadingto/) { get; } | This header requests an automated confirmation notice when the message is received or read. It is typically ignored; presumably some software acts on it. |
| static [XMailer](../../aspose.email/headertype/xmailer/) { get; } | Information about the client software of the originator. Example: X-Mailer: Aspose.Email |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.email/headertype/equals/)(object) | Returns a boolean indicating if the passed in object obj is Equal to this. |
| override [GetHashCode](../../aspose.email/headertype/gethashcode/)() | Serves as a hash function for a particular type. |
| override [ToString](../../aspose.email/headertype/tostring/)() | Returns a String that represents the current Object. |
| [implicit operator](../../aspose.email/headertype/op_implicit/) | Performs an implicit conversion from `HeaderType` to String. |

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


