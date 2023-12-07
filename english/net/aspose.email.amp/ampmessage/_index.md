---
title: Class AmpMessage
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Amp.AmpMessage class. Message which allows senders to include AMP components inside emails
type: docs
weight: 140
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
| virtual [AlternateViews](../../aspose.email/mailmessage/alternateviews/) { get; } | Gets the collection of alternate views of message |
| virtual [AmpHtmlBody](../../aspose.email.amp/ampmessage/amphtmlbody/) { get; set; } | Gets the AmpHtml representation of message's body. |
| virtual [Attachments](../../aspose.email/mailmessage/attachments/) { get; } | Gets the collection of attachments of message |
| virtual [Bcc](../../aspose.email/mailmessage/bcc/) { get; set; } | Gets or sets the address collection that contains the BCC recipients of message |
| virtual [Body](../../aspose.email/mailmessage/body/) { get; set; } | Gets or sets the plain text representation of message's body. If the text/plain part is present in a message, the propery returns its text data. Otherwise, property returns the text content of the HtmlBody property without html markup. |
| virtual [BodyEncoding](../../aspose.email/mailmessage/bodyencoding/) { get; set; } | Gets or sets encoding of body |
| [BodyType](../../aspose.email/mailmessage/bodytype/) { get; } | Gets the type of the body. |
| virtual [CC](../../aspose.email/mailmessage/cc/) { get; set; } | Gets or sets the address collection that contains the CC recipients |
| virtual [Date](../../aspose.email/mailmessage/date/) { get; set; } | Gets or sets the date of message |
| virtual [DeliveryNotificationOptions](../../aspose.email/mailmessage/deliverynotificationoptions/) { get; set; } | Gets or sets the delivery notifications |
| [Epilogue](../../aspose.email/mailmessage/epilogue/) { get; set; } | Gets or sets an epilogue text. It is located after the last boundary. |
| virtual [From](../../aspose.email/mailmessage/from/) { get; set; } | Gets or sets the from address |
| virtual [Headers](../../aspose.email/mailmessage/headers/) { get; } | Gets headers collection of message |
| virtual [HtmlBody](../../aspose.email/mailmessage/htmlbody/) { get; set; } | Gets or sets html body |
| virtual [IsBodyHtml](../../aspose.email/mailmessage/isbodyhtml/) { get; set; } | Gets or sets a value indicating whether the message body is in Html |
| virtual [IsDraft](../../aspose.email/mailmessage/isdraft/) { get; set; } | Gets or sets value that indicates whether or not a message has been sent. |
| virtual [IsEncrypted](../../aspose.email/mailmessage/isencrypted/) { get; } | Gets a value indicating whether the message is encrypted. |
| virtual [IsReadOnly](../../aspose.email/mailmessage/isreadonly/) { get; } | Gets a value indicating whether the message is read only |
| virtual [IsSigned](../../aspose.email/mailmessage/issigned/) { get; } | Gets a value indicating whether the message is signed. |
| virtual [ItemId](../../aspose.email/mailmessage/itemid/) { get; } | Represents identification information about message in a mailbox. |
| virtual [LinkedResources](../../aspose.email/mailmessage/linkedresources/) { get; } | Gets the collection of linked resources of message |
| virtual [MessageId](../../aspose.email/mailmessage/messageid/) { get; set; } | Gets or sets the message id |
| virtual [OriginalIsTnef](../../aspose.email/mailmessage/originalistnef/) { get; } | Gets a value indicating whether original EML message is in TNEF format. |
| [Preamble](../../aspose.email/mailmessage/preamble/) { get; set; } | Gets or sets a preamble text. It is located before the first boundary and generally includes an explanatory note to non-MIME conformant readers. |
| [PreferredTextEncoding](../../aspose.email/mailmessage/preferredtextencoding/) { get; set; } | Gets or sets preferred encoding for all text properties |
| virtual [Priority](../../aspose.email/mailmessage/priority/) { get; set; } | Gets or sets the priority of message |
| [ReadReceiptTo](../../aspose.email/mailmessage/readreceiptto/) { get; set; } | Gets or sets the read receipt address. |
| virtual [ReplyToList](../../aspose.email/mailmessage/replytolist/) { get; set; } | Gets or sets the list of addresses to reply to for the mail message |
| virtual [ReversePath](../../aspose.email/mailmessage/reversepath/) { get; set; } | Gets or sets ReversePath address |
| virtual [Sender](../../aspose.email/mailmessage/sender/) { get; set; } | Gets or sets sender address |
| virtual [Sensitivity](../../aspose.email/mailmessage/sensitivity/) { get; set; } | Gets or sets the sensitivity of message |
| virtual [Subject](../../aspose.email/mailmessage/subject/) { get; set; } | Gets or sets the subject line |
| virtual [SubjectEncoding](../../aspose.email/mailmessage/subjectencoding/) { get; set; } | Gets or sets the encoding of subject |
| [TimeZoneOffset](../../aspose.email/mailmessage/timezoneoffset/) { get; set; } | Gets or sets the Coordinated Universal Time (UTC) offset for the message dates. This property defines the time zone difference, between the local time and UTC. |
| virtual [To](../../aspose.email/mailmessage/to/) { get; set; } | Gets or sets the address collection that contains the recipients of message |
| virtual [XMailer](../../aspose.email/mailmessage/xmailer/) { get; set; } | Gets or sets the X-Mailer the software that created the e-mail message |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddAlternateView](../../aspose.email/mailmessage/addalternateview/)(AlternateView) | Add an alternate view to message |
| [AddAmpComponent](../../aspose.email.amp/ampmessage/addampcomponent/)(AmpComponent) | Add Amp component to this message. |
| virtual [AddAttachment](../../aspose.email/mailmessage/addattachment/)(Attachment) | Add an attachment to message |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature/)(CmsSigner) | Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature/)(X509Certificate2) | Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature/)(CmsSigner, bool) | Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature/)(X509Certificate2, bool) | Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it. |
| virtual [CheckBounced](../../aspose.email/mailmessage/checkbounced/)() | Checks whether this message can be treated as a bounce message. |
| virtual [CheckSignature](../../aspose.email/mailmessage/checksignature/)() | Checking signature exsisting MailMessage. |
| virtual [Clone](../../aspose.email/mailmessage/clone/)() | Clones this instance |
| [CreateReadReceipt](../../aspose.email/mailmessage/createreadreceipt/)(string, string) | Creates the read receipt. |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt/)() | Decrypts this message |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt/)(X509Certificate2) | Decrypts this message |
| [Dispose](../../aspose.email/mailmessage/dispose/)() | Releases all resources used by the MailMessage |
| virtual [DKIMSign](../../aspose.email/mailmessage/dkimsign/)(RSACryptoServiceProvider, DKIMSignatureInfo) | Signs this message using DKIM (DomainKeys Identified Mail) signature. |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt/)(X509Certificate2) | Encrypts this message |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt/)(X509Certificate2[]) | Encrypts this message |
| override [Equals](../../aspose.email/mailmessage/equals/)(object) | Determines whether the specified Object is equal to the current Object. |
| [GetAlternateViewContent](../../aspose.email/mailmessage/getalternateviewcontent/)(string) | Gets the content as a string from the specified AlternateView. |
| [GetEnumerator](../../aspose.email/mailmessage/getenumerator/)() | Returns an enumerator that iterates through a collection. |
| override [GetHashCode](../../aspose.email/mailmessage/gethashcode/)() | Returns a hash code for object |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext/)(bool) | Gets the message html body as plain text. This method parses the HtmlBody property and returns plain text content ignoring the html markup. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext/)(HyperlinkRenderingCallback) | Gets the message htmlbody as plain text. |
| virtual [GetObjectData](../../aspose.email/mailmessage/getobjectdata/)(SerializationInfo, StreamingContext) | Populates a SerializationInfo with the data needed to serialize the target object. |
| virtual [Import](../../aspose.email/mailmessage/import/)(Stream) | Imports message from stream |
| [RecomposeTnefContent](../../aspose.email/mailmessage/recomposetnefcontent/)() | Composes the TNEF content. Note, that tnef attachment is composed if a message initially contained TNEF and was loaded without FileCompatibilityMode.PreserveTnefAttachments flag, That is this method doesn't create tnef message out of the regular one. |
| virtual [RemoveSignature](../../aspose.email/mailmessage/removesignature/)() | Remove signature |
| virtual [Save](../../aspose.email/mailmessage/save/)(Stream) | Save message as a stream |
| virtual [Save](../../aspose.email/mailmessage/save/)(string) | Save message as a file |
| override [Save](../../aspose.email.amp/ampmessage/save/#save_1)(Stream, SaveOptions) | Save message as a stream |
| virtual [Save](../../aspose.email/mailmessage/save/)(string, SaveOptions) | Save message as a file with additional options. |
| virtual [SetHtmlBody](../../aspose.email/mailmessage/sethtmlbody/)(string, bool) | Sets html body. |
| override [ToString](../../aspose.email/mailmessage/tostring/)() | Returns a string that represents the current object. |

### See Also

* class [MailMessage](../../aspose.email/mailmessage/)
* namespace [Aspose.Email.Amp](../../aspose.email.amp/)
* assembly [Aspose.Email](../../)


