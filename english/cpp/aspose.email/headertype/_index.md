---
title: "Aspose::Email::HeaderType class"
linktitle: "HeaderType"
articleTitle: "HeaderType"
second_title: "Aspose.Email for C++"
description: "Represents the Internet standards and RFCs define header fields which may occur on Internet Mail Messages ."
type: docs
weight: 10
url: /cpp/aspose.email/headertype/
---

## HeaderType class

Represents the Internet standards and RFCs define header fields which may occur on Internet Mail Messages .

## Methods

| Name | Description |
| --- | --- |
| [Equals](./equals/) | Returns a boolean indicating if the passed in object obj is Equal to this. |
| [get_ApparentlyTo](./get_apparentlyto/) | Inserted by sending e-mail when there is no "To:" recipient in the original message. This causes the recipients derived from the envelope to be listed in the message heading. This behavior is not quite proper, MTAs should not modify headers (except inserting Received lines), and it can in some cases cause Bcc recipients to be wrongly divulged to non-Bcc recipients. Example: Apparently-To: someo .nosp@m. ne@s .nosp@m. omedo .nosp@m. main .nosp@m. .com |
| [get_ApprovedBy](./get_approvedby/) | Name of the moderator of the mailing list to which this message is sent; necessary on a posting sent to a moderated mailing list to allow its distribution to the list members. Example: Approved-By: someo .nosp@m. ne@s .nosp@m. omedo .nosp@m. main .nosp@m. .com |
| [get_Bcc](./get_bcc/) | A copy of the e-mail message that is sent to one or more recipients without the knowledge of the primary recipients. Primary recipients are listed in the To: and Cc: lines. This is useful if you want to copy a message to many people without each of them seeing who the other recipients are. If you see this header on incoming mail, something is wrong because it does not appear in the headers. |
| [get_CC](./get_cc/) | This header can be considered an extension of the "To:" field as it is used to specifiy additional recipients. In this case, the copy of an e-mail message sent to a recipient has the recipient's address appearing in the message. This is useful if you want to copy a message to many people with each of them seeing who the other recipients are; contrast with Bcc above. This header does appear in incoming e-mail. Exmple: Cc: gboyd .nosp@m. @net .nosp@m. com.c .nosp@m. om |
| [get_Comments](./get_comments/) | This is a free-form header field defined in RFC2822. The header is used to place explanatory text into the header portion of an e-mail message. The field may contain arbitrary text. Exmple: Comments: Authenticated sender is someo .nosp@m. ne@s .nosp@m. omedo .nosp@m. nmai .nosp@m. n.com . |
| [get_ContentTransferEncoding](./get_contenttransferencoding/) | The third of the MIME-related headers. Indicates the coding method used in a MIME message body. It has no direct relevance to the delivery of e-mail, but it affects how MIME compliant mail programs interpret the content of the message. |
| [get_ContentType](./get_contenttype/) | The "Content-Type" defines the format of content (character set etc.) Note that the values for this header are defined in different ways in RFC1049 and in MIME (RFC2045). Look for the MIME-version: header to understand if Content-Type is to be interpreted according to RFC1049 or according to MIME (RFC2045). The MIME definition should be used in generating mail. |
| [get_Date](./get_date/) | This header specifies a date (and time), normally the date the message was composed and sent. In X.400 mail systems, the time a message was submitted. Some Internet mail systems also use the date when the message was submitted. If this header is omitted by the sender's computer, it might conceivably be added by a mail server or even by some other machine along the route. What you may not know is that the information in the "Date:" line is supplied by the time on the sender's computer, which may or may not be set correctly. Also, the "Date:" header does not normally indicate when the message was sent, but only when it was composed. The date is in the form 3 character day-of-week (Sun - Sat), day number (1-31) dd, 3-character month name, 4-digit year yyyy, followed by time (24-hour) hh:mm:ss and zone zzz format. Time Zone (zzz) is either the 3-character time zone or the local differential in hours and minutes offset from UTC (Universal Time Coordinated - old Greenwich Mean Time). "-" indicates west and "+" indicates east of UTC. No standard Time Zone definitions seem to exist. Many UNIX versions understand a great range of abbreviations, but the most exhaustive list I found was the GNU tar manual Timezone item and documentation for the Perl date manipulation module TIMEZONES. |
| [get_DispositionNotificationTo](./get_dispositionnotificationto/) | When the DispositionNotificationTo field is set, a request for a MDN (Message Delivery Notification) is made. The recipient's email software (Outlook, Eudora, etc.) may silently ignore the request, or it may prompt the user for permission to send the MDN. There is no guarantee of the "return-receipt". The DispositionNotificationTo field is the de facto standard for requesting return-receipts (i.e. MDN, or message delivery notifications). |
| [get_FollowupTo](./get_followupto/) | Used in Usenet News to indicate that future discussions (=follow-up) on an article should go to a different set of newsgroups than the replied-to article. The most common usage is when an article is posted to several newsgroups, and further discussions is to take place in only one of them. |
| [get_From](./get_from/) | This field contains the identity of the person(s) who wished this message to be sent. The message-creation process should default this field to be a single, authenticated machine address, indicating the AGENT (person, system or process) composing the message. If this is not done, the "Sender:" field MUST be present. If the "From:" field IS defaulted this way, the "Sender:" field is optional and is redundant with the "From:" field. |
| [get_Importance](./get_importance/) | Gets the importance. |
| [get_InReplyTo](./get_inreplyto/) | Reference to message which this message is a reply to. |
| [get_MessageID](./get_messageid/) | Unique ID of this message. Defined In RFC 822: 4.6.1 ,RFC 1036: 2.1.5. |
| [get_MIMEVersion](./get_mimeversion/) | An indicator that this message is formatted according to the MIME standard, and an indication of which version of MIME is utilized. |
| [get_Newsgroups](./get_newsgroups/) | In Usenet News: group(s) to which this article was posted. Some systems provide this header field also in e-mail although it is not standardized there. Unfortunately, the header field can appear in e-mail with three different and contradictory meanings: (a) Indicating the newsgroup recipient of an article/message sent to both e-mail and Usenet News recipients. (b) In a message adressed to some mail to news gateways, indicates the newsgroup(s) that the message is to be posted to. (c) In a personally addressed reply to an article in a news-group, indicating the newsgroup in which this discussion originated. |
| [get_Received](./get_received/) | Trace of MTAs which a message has passed. |
| [get_References](./get_references/) | Reference to other related messages. |
| [get_ReplyTo](./get_replyto/) | This header field is meant to indicate where the sender wants replies to go. Unfortunately, this is ambiguous, since there are different kinds of replies, which the sender may wish to go to different addresses. In particular, there are personal replies intended for only one person, and group replies, intended for the whole group of people who read the replied-to message (often a mailing list, anewsgroup name cannot appear here because of different syntax, see "FollowupTo" .). |
| [get_ReturnPath](./get_returnpath/) | Used to convey the information from the MAIL FROM envelope attribute in final delivery, when the message leaves the SMTP environment in which "MAIL FROM" is used. /// |
| [get_ReturnReceiptTo](./get_returnreceiptto/) | A sender can request a return-receipt by including this header field. The return-receipt is sent to the Return-Path address of the email and not to the address specified in the Return-Receipt-To header field. This header is non-standard and mostly not supported. Use Disposition-Notification-To instead. Even if supported, there is no guarantee of a receipt being sent. |
| [get_Sender](./get_sender/) | The person or agent submitting the message to the network, if other than shown by the From: header field. Should be authenticated, according to RFC 822, but what kind of authentication is not clear. |
| [get_Sensitivity](./get_sensitivity/) | Gets the sensitivity. |
| [get_Subject](./get_subject/) | Title, heading, subject. Often used as thread indicator for messages replying to or commenting on other messages. |
| [get_To](./get_to/) | Primary recipients. |
| [get_XConfirmReadingTo](./get_xconfirmreadingto/) | This header requests an automated confirmation notice when the message is received or read. It is typically ignored; presumably some software acts on it. |
| [get_XMailer](./get_xmailer/) | Information about the client software of the originator. |
| [GetHashCode](./gethashcode/) | Serves as a hash function for a particular type. |
| [to_String](./to_string/) | Performs an implicit conversion from HeaderType to System::String . |
| [ToString](./tostring/) | Returns a T:System::String that represents the current T:System::Object . |

