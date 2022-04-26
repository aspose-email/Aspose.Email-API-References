---
title: MailMessage
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 15940
url: /net/aspose.email/mailmessage/
---
## MailMessage class

Represents an e-mail message. It allows to access message properties, ex. subject, body, sender and recipients addreses, etc. Also it can be sent and delivered by means of supported mail protocols.

```csharp
public class MailMessage : IDisposable, IEnumerable<MailMessage>, IMessage, 
    IPreferredTextEncodingProvider
```

## Constructors

| Name | Description |
| --- | --- |
| [MailMessage](mailmessage)() | Initializes a new instance of the [`MailMessage`](../mailmessage) class |
| [MailMessage](mailmessage)(bool) | Initializes a new instance of the [`MailMessage`](../mailmessage) class |
| [MailMessage](mailmessage)(MailAddress, MailAddress) | Initializes a new instance of the [`MailMessage`](../mailmessage) class |
| [MailMessage](mailmessage)(string, string) | Initializes a new instance of the [`MailMessage`](../mailmessage) class |
| [MailMessage](mailmessage)(string, string, string, string) | Initializes a new instance of the [`MailMessage`](../mailmessage) class |

## Properties

| Name | Description |
| --- | --- |
| virtual [AlternateViews](alternateviews) { get; } | Gets the collection of alternate views of message |
| virtual [Attachments](attachments) { get; } | Gets the collection of attachments of message |
| virtual [Bcc](bcc) { get; set; } | Gets or sets the address collection that contains the BCC recipients of message |
| virtual [Body](body) { get; set; } | Gets or sets the plain text representation of message's body. If the text/plain part is present in a message, the propery returns its text data. Otherwise, property returns the text content of the HtmlBody property without html markup. |
| virtual [BodyEncoding](bodyencoding) { get; set; } | Gets or sets encoding of body |
| [BodyType](bodytype) { get; } | Gets the type of the body. |
| virtual [CC](cc) { get; set; } | Gets or sets the address collection that contains the CC recipients |
| virtual [Date](date) { get; set; } | Gets or sets the date of message |
| virtual [DeliveryNotificationOptions](deliverynotificationoptions) { get; set; } | Gets or sets the delivery notifications |
| [Epilogue](epilogue) { get; set; } | Gets or sets an epilogue text. It is located after the last boundary. |
| virtual [From](from) { get; set; } | Gets or sets the from address |
| virtual [Headers](headers) { get; } | Gets headers collection of message |
| virtual [HtmlBody](htmlbody) { get; set; } | Gets or sets html body |
| virtual [IsBodyHtml](isbodyhtml) { get; set; } | Gets or sets a value indicating whether the message body is in Html |
| virtual [IsDraft](isdraft) { get; set; } | Gets or sets value that indicates whether or not a message has been sent. |
| virtual [IsEncrypted](isencrypted) { get; } | Gets a value indicating whether the message is encrypted. |
| virtual [IsReadOnly](isreadonly) { get; } | Gets a value indicating whether the message is read only |
| virtual [IsSigned](issigned) { get; } | Gets a value indicating whether the message is signed. |
| virtual [LinkedResources](linkedresources) { get; } | Gets the collection of linked resources of message |
| virtual [MessageId](messageid) { get; set; } | Gets or sets the message id |
| virtual [OriginalIsTnef](originalistnef) { get; } | Gets a value indicating whether original EML message is in TNEF format. |
| [Preamble](preamble) { get; set; } | Gets or sets a preamble text. It is located before the first boundary and generally includes an explanatory note to non-MIME conformant readers. |
| [PreferredTextEncoding](preferredtextencoding) { get; set; } | Gets or sets preferred encoding for all text properties |
| virtual [Priority](priority) { get; set; } | Gets or sets the priority of message |
| [ReadReceiptTo](readreceiptto) { get; set; } | Gets or sets the read receipt address. |
| virtual [ReplyToList](replytolist) { get; set; } | Gets or sets the list of addresses to reply to for the mail message |
| virtual [ReversePath](reversepath) { get; set; } | Gets or sets ReversePath address |
| virtual [Sender](sender) { get; set; } | Gets or sets sender address |
| virtual [Sensitivity](sensitivity) { get; set; } | Gets or sets the sensitivity of message |
| virtual [Subject](subject) { get; set; } | Gets or sets the subject line |
| virtual [SubjectEncoding](subjectencoding) { get; set; } | Gets or sets the encoding of subject |
| [TimeZoneOffset](timezoneoffset) { get; set; } | Gets or sets the Coordinated Universal Time (UTC) offset for the message dates. This property defines the time zone difference, between the local time and UTC. |
| virtual [To](to) { get; set; } | Gets or sets the address collection that contains the recipients of message |
| virtual [XMailer](xmailer) { get; set; } | Gets or sets the X-Mailer the software that created the e-mail message |

## Methods

| Name | Description |
| --- | --- |
| static [Load](load)(Stream) | Load message from stream |
| static [Load](load)(string) | Load message from file |
| static [Load](load)(Stream, LoadOptions) | Load message from stream with additional options. |
| static [Load](load)(string, LoadOptions) | Load message from file with additional options. |
| virtual [AddAlternateView](addalternateview)(AlternateView) | Add an alternate view to message |
| virtual [AddAttachment](addattachment)(Attachment) | Add an attachment to message |
| virtual [AttachSignature](attachsignature)(CmsSigner) | Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it. |
| virtual [AttachSignature](attachsignature)(X509Certificate2) | Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it. |
| virtual [AttachSignature](attachsignature)(CmsSigner, bool) | Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it. |
| virtual [AttachSignature](attachsignature)(X509Certificate2, bool) | Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it. |
| virtual [CheckBounced](checkbounced)() | Checks whether this message can be treated as a bounce message. |
| virtual [CheckSignature](checksignature)() | Checking signature exsisting MailMessage. |
| virtual [Clone](clone)() | Clones this instance |
| [CreateReadReceipt](createreadreceipt)(string, string) | Creates the read receipt. |
| virtual [Decrypt](decrypt)() | Decrypts this message |
| virtual [Decrypt](decrypt)(X509Certificate2) | Decrypts this message |
| [Dispose](dispose)() | Releases all resources used by the MailMessage |
| virtual [Encrypt](encrypt)(X509Certificate2) | Encrypts this message |
| virtual [Encrypt](encrypt)(X509Certificate2[]) | Encrypts this message |
| override [Equals](equals)(object) | Determines whether the specified Object is equal to the current Object. |
| [GetEnumerator](getenumerator)() | Returns an enumerator that iterates through a collection. |
| override [GetHashCode](gethashcode)() | Returns a hash code for object |
| virtual [GetHtmlBodyText](gethtmlbodytext)(bool) | Gets the message html body as plain text. This method parses the HtmlBody property and returns plain text content ignoring the html markup. |
| virtual [GetHtmlBodyText](gethtmlbodytext)(HyperlinkRenderingCallback) | Gets the message htmlbody as plain text. |
| virtual [Import](import)(Stream) | Imports message from stream |
| [RecomposeTnefContent](recomposetnefcontent)() | Composes the TNEF content. Note, that tnef attachment is composed if a message initially contained TNEF and was loaded without FileCompatibilityMode.PreserveTnefAttachments flag, That is this method doesn't create tnef message out of the regular one. |
| virtual [RemoveSignature](removesignature)() | Remove signature |
| virtual [Save](save)(Stream) | Save message as a stream |
| virtual [Save](save)(string) | Save message as a file |
| virtual [Save](save)(Stream, SaveOptions) | Save message as a stream with additional options. |
| virtual [Save](save)(string, SaveOptions) | Save message as a file with additional options. |
| virtual [SetHtmlBody](sethtmlbody)(string, bool) | Sets html body. |
| override [ToString](tostring)() | Returns a string that represents the current object. |
| static [CheckSignature](checksignature)(Stream) | Checks the signature of the specified eml message. |
| static [CheckSignature](checksignature)(string) | Checks the signature of the specified eml file. |
| static [ValidateMessage](validatemessage)(Stream) | Validate eml message for corresponding to mime specification. |
| static [ValidateMessage](validatemessage)(string) | Validate eml message for corresponding to mime specification. |

### See Also

* interface [IMessage](../imessage)
* interface [IPreferredTextEncodingProvider](../ipreferredtextencodingprovider)
* namespace [Aspose.Email](../../aspose.email)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
