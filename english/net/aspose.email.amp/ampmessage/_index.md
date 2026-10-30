---
title: Class AmpMessage
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Amp.AmpMessage class. Message which allows senders to include AMP components inside emails
type: docs
weight: 120
url: /net/aspose.email.amp/ampmessage/
---
## AmpMessage class

Message which allows senders to include AMP components inside emails.

```csharp
public class AmpMessage : MailMessage
```

## Constructors

| Name | Description |
| --- | --- |
| [AmpMessage](ampmessage/)() | Initializes a new instance of the [`MailMessage`](../../aspose.email/mailmessage/) class |

## Properties

| Name | Description |
| --- | --- |
| virtual [AlternateViews](../../aspose.email/mailmessage/alternateviews/) { get; } | Gets the alternate views of the body: the plain-text, HTML and other versions. |
| virtual [AmpHtmlBody](../../aspose.email.amp/ampmessage/amphtmlbody/) { get; set; } | Gets the AmpHtml representation of message's body. |
| virtual [Attachments](../../aspose.email/mailmessage/attachments/) { get; } | Gets the attachments of the message. |
| virtual [Bcc](../../aspose.email/mailmessage/bcc/) { get; set; } | Gets or sets the BCC recipients. |
| virtual [Body](../../aspose.email/mailmessage/body/) { get; set; } | Gets or sets the plain-text body. When the message has no plain-text part, the text of [`HtmlBody`](../../aspose.email/mailmessage/htmlbody/) without the HTML markup is returned. |
| virtual [BodyEncoding](../../aspose.email/mailmessage/bodyencoding/) { get; set; } | Gets or sets the character encoding of the body. |
| [BodyType](../../aspose.email/mailmessage/bodytype/) { get; } | Gets the format of the body: plain text, HTML or RTF. |
| virtual [CC](../../aspose.email/mailmessage/cc/) { get; set; } | Gets or sets the CC recipients. |
| virtual [Date](../../aspose.email/mailmessage/date/) { get; set; } | Gets or sets the date and time of the message (the `Date` header). |
| virtual [DeliveryNotificationOptions](../../aspose.email/mailmessage/deliverynotificationoptions/) { get; set; } | Gets or sets when the SMTP server sends a delivery status notification to the sender. |
| [Epilogue](../../aspose.email/mailmessage/epilogue/) { get; set; } | Gets or sets the text after the last MIME boundary of the message. |
| virtual [From](../../aspose.email/mailmessage/from/) { get; set; } | Gets or sets the author of the message (the `From` header). |
| virtual [Headers](../../aspose.email/mailmessage/headers/) { get; } | Gets the headers of the message. |
| virtual [HtmlBody](../../aspose.email/mailmessage/htmlbody/) { get; set; } | Gets or sets the HTML body. |
| virtual [IsBodyHtml](../../aspose.email/mailmessage/isbodyhtml/) { get; set; } | Gets or sets a value indicating whether the body is HTML. |
| virtual [IsDraft](../../aspose.email/mailmessage/isdraft/) { get; set; } | Gets or sets a value indicating whether the message is a draft that has not been sent (the `X-Unsent` header). |
| virtual [IsEncrypted](../../aspose.email/mailmessage/isencrypted/) { get; } | Gets a value indicating whether the message is encrypted (S/MIME). |
| virtual [IsReadOnly](../../aspose.email/mailmessage/isreadonly/) { get; } | Gets a value indicating whether the message is read-only, as a signed copy is. |
| virtual [IsSigned](../../aspose.email/mailmessage/issigned/) { get; } | Gets a value indicating whether the message is digitally signed. |
| virtual [ItemId](../../aspose.email/mailmessage/itemid/) { get; } | Gets the identifiers of the message in the mailbox it was retrieved from. |
| virtual [LinkedResources](../../aspose.email/mailmessage/linkedresources/) { get; } | Gets the resources embedded in the HTML body, such as images. |
| virtual [MessageId](../../aspose.email/mailmessage/messageid/) { get; set; } | Gets or sets the unique identifier of the message (the `Message-ID` header). |
| virtual [OriginalIsTnef](../../aspose.email/mailmessage/originalistnef/) { get; } | Gets a value indicating whether the message was loaded from TNEF data (winmail.dat). |
| [Preamble](../../aspose.email/mailmessage/preamble/) { get; set; } | Gets or sets the text before the first MIME boundary, usually a note for mail clients that do not support MIME. |
| [PreferredTextEncoding](../../aspose.email/mailmessage/preferredtextencoding/) { get; set; } | Gets or sets the encoding used for all text of the message when no other encoding is specified. |
| virtual [Priority](../../aspose.email/mailmessage/priority/) { get; set; } | Gets or sets the priority of the message: normal, low or high. |
| [ReadReceiptTo](../../aspose.email/mailmessage/readreceiptto/) { get; set; } | Gets or sets the addresses a read receipt is requested to (the `Disposition-Notification-To` header). |
| virtual [ReplyToList](../../aspose.email/mailmessage/replytolist/) { get; set; } | Gets or sets the addresses replies should go to (the `Reply-To` header). |
| virtual [ReversePath](../../aspose.email/mailmessage/reversepath/) { get; set; } | Gets or sets the address bounces are returned to (the `Return-Path` header). When the message is sent, it is used as the envelope sender in preference to [`Sender`](../../aspose.email/mailmessage/sender/) and [`From`](../../aspose.email/mailmessage/from/). |
| virtual [Sender](../../aspose.email/mailmessage/sender/) { get; set; } | Gets or sets the agent that sent the message on behalf of the author (the `Sender` header). |
| virtual [Sensitivity](../../aspose.email/mailmessage/sensitivity/) { get; set; } | Gets or sets the sensitivity of the message: personal, private or company confidential. |
| virtual [Subject](../../aspose.email/mailmessage/subject/) { get; set; } | Gets or sets the subject of the message. |
| virtual [SubjectEncoding](../../aspose.email/mailmessage/subjectencoding/) { get; set; } | Gets or sets the character encoding of the subject. |
| [TimeZoneOffset](../../aspose.email/mailmessage/timezoneoffset/) { get; set; } | Gets or sets the offset from UTC that the dates of the message are written with. |
| virtual [To](../../aspose.email/mailmessage/to/) { get; set; } | Gets or sets the To recipients. |
| virtual [XMailer](../../aspose.email/mailmessage/xmailer/) { get; set; } | Gets or sets the software that created the message (the `X-Mailer` header). |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddAlternateView](../../aspose.email/mailmessage/addalternateview/)(AlternateView) | Adds an alternate view of the body to the message. |
| [AddAmpComponent](../../aspose.email.amp/ampmessage/addampcomponent/)(AmpComponent) | Add Amp component to this message. |
| virtual [AddAttachment](../../aspose.email/mailmessage/addattachment/)(Attachment) | Adds an attachment to the message. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature/)(CmsSigner) | Creates a signed copy of the message (S/MIME). The copy is read-only. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature/)(X509Certificate2) | Creates a signed copy of the message (S/MIME). The copy is read-only. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature/)(CmsSigner, bool) | Creates a signed copy of the message (S/MIME). The copy is read-only. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature/)(X509Certificate2, bool) | Creates a signed copy of the message (S/MIME). The copy is read-only. |
| virtual [CheckBounced](../../aspose.email/mailmessage/checkbounced/)() | Checks whether the message is a bounce (a non-delivery report) and, if so, why it bounced. |
| virtual [CheckSignature](../../aspose.email/mailmessage/checksignature/)() | Verifies the signature of the message. |
| virtual [Clone](../../aspose.email/mailmessage/clone/)() | Creates a copy of the message. |
| [CreateReadReceipt](../../aspose.email/mailmessage/createreadreceipt/)(string, string) | Creates a read receipt for the message. |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt/)() | Decrypts the message with a certificate found in the certificate store. |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt/)(X509Certificate2) | Decrypts the message with the specified certificate. |
| [Dispose](../../aspose.email/mailmessage/dispose/)() | Releases the resources used by the message, including its attachments. |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt/)(X509Certificate2) | Creates a copy of the message encrypted for one recipient (S/MIME). |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt/)(X509Certificate2[]) | Creates a copy of the message encrypted for several recipients (S/MIME). |
| override [Equals](../../aspose.email/mailmessage/equals/)(object) | Determines whether the specified object is equal to this message. |
| [GetAlternateViewContent](../../aspose.email/mailmessage/getalternateviewcontent/)(string) | Gets the content of the alternate view of the specified media type. |
| [GetEnumerator](../../aspose.email/mailmessage/getenumerator/)() | Returns an enumerator that iterates through a collection. |
| override [GetHashCode](../../aspose.email/mailmessage/gethashcode/)() | Returns the hash code of the message. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext/)(bool) | Gets the text of the HTML body without the markup. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext/)(HyperlinkRenderingCallback) | Gets the text of the HTML body without the markup, rendering hyperlinks with a custom method. |
| virtual [Import](../../aspose.email/mailmessage/import/)(Stream) | Replaces the content of this message with a message read from a stream in EML format. |
| [RecomposeTnefContent](../../aspose.email/mailmessage/recomposetnefcontent/)() | Rebuilds the TNEF attachment (winmail.dat) of a message that was loaded from TNEF, so that it reflects the changes made to the message. |
| virtual [RemoveSignature](../../aspose.email/mailmessage/removesignature/)() | Returns a copy of a signed message without the signature. |
| virtual [Save](../../aspose.email/mailmessage/save/)(Stream) | Saves the message to a stream in EML format. |
| virtual [Save](../../aspose.email/mailmessage/save/)(string) | Saves the message to a file in EML format, whatever the file extension. |
| override [Save](../../aspose.email.amp/ampmessage/save/#save_1)(Stream, SaveOptions) | Save message as a stream |
| virtual [Save](../../aspose.email/mailmessage/save/)(string, SaveOptions) | Saves the message to a file in the format selected by the options. |
| virtual [SetHtmlBody](../../aspose.email/mailmessage/sethtmlbody/)(string, bool) | Sets the HTML body, optionally detecting its encoding. |
| override [ToString](../../aspose.email/mailmessage/tostring/)() | Returns a string that represents the message. |

### See Also

* class [MailMessage](../../aspose.email/mailmessage/)
* namespace [Aspose.Email.Amp](../../aspose.email.amp/)
* assembly [Aspose.Email](../../)


