---
title: Class HeaderType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.HeaderType class. Identifies a standard header of an Internet message such as From Subject or ContentType
type: docs
weight: 16260
url: /net/aspose.email/headertype/
---
## HeaderType class

Identifies a standard header of an Internet message, such as `From`, `Subject` or `Content-Type`.

```csharp
public sealed class HeaderType
```

## Properties

| Name | Description |
| --- | --- |
| static [ApparentlyTo](../../aspose.email/headertype/apparentlyto/) { get; } | Gets the `Apparently-To` header: the recipients, added by some servers when a message has no `To` header. Non-standard; it can reveal BCC recipients. |
| static [ApprovedBy](../../aspose.email/headertype/approvedby/) { get; } | Gets the `Approved-By` header: the moderator who approved a message posted to a moderated mailing list (RFC 1036). Non-standard in e-mail. |
| static [Bcc](../../aspose.email/headertype/bcc/) { get; } | Gets the `Bcc` header: the blind carbon copy recipients, which the other recipients do not see. It is removed before the message is delivered. |
| static [CC](../../aspose.email/headertype/cc/) { get; } | Gets the `Cc` header: the carbon copy recipients, which all recipients see. |
| static [Comments](../../aspose.email/headertype/comments/) { get; } | Gets the `Comments` header: free-form text about the message (RFC 2822). |
| static [ContentTransferEncoding](../../aspose.email/headertype/contenttransferencoding/) { get; } | Gets the `Content-Transfer-Encoding` header: how the body is encoded for transfer, such as `7bit`, `8bit`, `base64` or `quoted-printable` (RFC 2045). |
| static [ContentType](../../aspose.email/headertype/contenttype/) { get; } | Gets the `Content-Type` header: the media type of the content and its parameters, such as `text/plain; charset="utf-8"` (RFC 2045). |
| static [Date](../../aspose.email/headertype/date/) { get; } | Gets the `Date` header: the date and time the message was composed, in the form `Tue, 9 Jan 2001 23:40:00 -0800`. It comes from the clock of the sender's computer. |
| static [DispositionNotificationTo](../../aspose.email/headertype/dispositionnotificationto/) { get; } | Gets the `Disposition-Notification-To` header: the address to send a read receipt (message disposition notification) to. The recipient's client may ignore the request. |
| static [FollowupTo](../../aspose.email/headertype/followupto/) { get; } | Gets the `Followup-To` header: the newsgroups that follow-up discussion should go to (RFC 1036). Not standard in e-mail. |
| static [From](../../aspose.email/headertype/from/) { get; } | Gets the `From` header: the author of the message. |
| static [Importance](../../aspose.email/headertype/importance/) { get; } | Gets the `Importance` header: the importance of the message: low, normal or high. |
| static [InReplyTo](../../aspose.email/headertype/inreplyto/) { get; } | Gets the `In-Reply-To` header: the `Message-ID` of the message this one replies to. |
| static [MessageID](../../aspose.email/headertype/messageid/) { get; } | Gets the `Message-ID` header: the unique identifier of the message (RFC 822, RFC 1036). |
| static [MIMEVersion](../../aspose.email/headertype/mimeversion/) { get; } | Gets the `MIME-Version` header: the version of MIME the message is formatted in (RFC 2045). |
| static [Newsgroups](../../aspose.email/headertype/newsgroups/) { get; } | Gets the `Newsgroups` header: the newsgroups a Usenet article was posted to (RFC 1036). Not standard in e-mail, where it is used with different meanings. |
| static [Received](../../aspose.email/headertype/received/) { get; } | Gets the `Received` header: a record added by each mail server the message passes through (RFC 822). |
| static [References](../../aspose.email/headertype/references/) { get; } | Gets the `References` header: the `Message-ID` values of the earlier messages in the conversation. |
| static [ReplyTo](../../aspose.email/headertype/replyto/) { get; } | Gets the `Reply-To` header: the addresses that replies should go to, when they differ from the author. |
| static [ReturnPath](../../aspose.email/headertype/returnpath/) { get; } | Gets the `Return-Path` header: the address that bounces are returned to: the envelope sender (`MAIL FROM`), added on final delivery. |
| static [ReturnReceiptTo](../../aspose.email/headertype/returnreceiptto/) { get; } | Gets the `Return-Receipt-To` header: requests a delivery receipt. Non-standard and rarely supported; use `Disposition-Notification-To` instead. |
| static [Sender](../../aspose.email/headertype/sender/) { get; } | Gets the `Sender` header: the person or agent that submitted the message, when it differs from the author in `From`. |
| static [Sensitivity](../../aspose.email/headertype/sensitivity/) { get; } | Gets the `Sensitivity` header: the sensitivity of the message: personal, private or company confidential. |
| static [Subject](../../aspose.email/headertype/subject/) { get; } | Gets the `Subject` header: the subject of the message. |
| static [To](../../aspose.email/headertype/to/) { get; } | Gets the `To` header: the primary recipients. |
| static [XConfirmReadingTo](../../aspose.email/headertype/xconfirmreadingto/) { get; } | Gets the `X-Confirm-Reading-To` header: requests a read confirmation. Non-standard and usually ignored. |
| static [XMailer](../../aspose.email/headertype/xmailer/) { get; } | Gets the `X-Mailer` header: the software that created the message. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.email/headertype/equals/)(object) | Determines whether the specified object is the same header type. |
| override [GetHashCode](../../aspose.email/headertype/gethashcode/)() | Returns the hash code of the header type. |
| override [ToString](../../aspose.email/headertype/tostring/)() | Returns the name of the header, such as `Return-Path`. |
| [implicit operator](../../aspose.email/headertype/op_implicit/) | Performs an implicit conversion from `HeaderType` to String. |

## Remarks

[`ToString`](./tostring/) returns the name of the header as it appears in a message, such as `Return-Path`.

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


