---
title: Class MailMessage
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.MailMessage class. Represents an email message its headers body attachments and recipients. Load it from or save it to EML MSG MHTML HTML and other formats and send it with the mail clients
type: docs
weight: 16490
url: /net/aspose.email/mailmessage/
---
## MailMessage class

Represents an e-mail message: its headers, body, attachments and recipients. Load it from or save it to EML, MSG, MHTML, HTML and other formats, and send it with the mail clients.

```csharp
public class MailMessage : IDisposable, IEnumerable<MailMessage>, IMessage, 
    IPreferredTextEncodingProvider
```

## Constructors

| Name | Description |
| --- | --- |
| [MailMessage](mailmessage/#constructor)() | Initializes a new instance of the `MailMessage` class: an empty message. |
| [MailMessage](mailmessage/#constructor_1)(MailAddress, MailAddress) | Initializes a new instance of the `MailMessage` class with a sender and a recipient. |
| [MailMessage](mailmessage/#constructor_2)(string, string) | Initializes a new instance of the `MailMessage` class with a sender and recipients. |
| [MailMessage](mailmessage/#constructor_3)(string, string, string, string) | Initializes a new instance of the `MailMessage` class with a sender, recipients, a subject and a plain-text body. |

## Properties

| Name | Description |
| --- | --- |
| virtual [AlternateViews](../../aspose.email/mailmessage/alternateviews/) { get; } | Gets the alternate views of the body: the plain-text, HTML and other versions. |
| virtual [Attachments](../../aspose.email/mailmessage/attachments/) { get; } | Gets the attachments of the message. |
| virtual [Bcc](../../aspose.email/mailmessage/bcc/) { get; set; } | Gets or sets the BCC recipients. |
| virtual [Body](../../aspose.email/mailmessage/body/) { get; set; } | Gets or sets the plain-text body. When the message has no plain-text part, the text of [`HtmlBody`](./htmlbody/) without the HTML markup is returned. |
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
| virtual [ReversePath](../../aspose.email/mailmessage/reversepath/) { get; set; } | Gets or sets the address bounces are returned to (the `Return-Path` header). When the message is sent, it is used as the envelope sender in preference to [`Sender`](./sender/) and [`From`](./from/). |
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
| static [Load](../../aspose.email/mailmessage/load/#load)(Stream) | Loads a message from a stream. MSG is recognized automatically; any other data is read as EML. |
| static [Load](../../aspose.email/mailmessage/load/#load_2)(string) | Loads a message from a file. MSG is recognized automatically; any other file is read as EML. |
| static [Load](../../aspose.email/mailmessage/load/#load_1)(Stream, LoadOptions) | Loads a message from a stream in the format selected by the options. |
| static [Load](../../aspose.email/mailmessage/load/#load_3)(string, LoadOptions) | Loads a message from a file in the format selected by the options. |
| virtual [AddAlternateView](../../aspose.email/mailmessage/addalternateview/)(AlternateView) | Adds an alternate view of the body to the message. |
| virtual [AddAttachment](../../aspose.email/mailmessage/addattachment/)(Attachment) | Adds an attachment to the message. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature/#attachsignature)(CmsSigner) | Creates a signed copy of the message (S/MIME). The copy is read-only. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature/#attachsignature_2)(X509Certificate2) | Creates a signed copy of the message (S/MIME). The copy is read-only. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature/#attachsignature_1)(CmsSigner, bool) | Creates a signed copy of the message (S/MIME). The copy is read-only. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature/#attachsignature_3)(X509Certificate2, bool) | Creates a signed copy of the message (S/MIME). The copy is read-only. |
| virtual [CheckBounced](../../aspose.email/mailmessage/checkbounced/)() | Checks whether the message is a bounce (a non-delivery report) and, if so, why it bounced. |
| virtual [CheckSignature](../../aspose.email/mailmessage/checksignature/)() | Verifies the signature of the message. |
| virtual [Clone](../../aspose.email/mailmessage/clone/)() | Creates a copy of the message. |
| [CreateReadReceipt](../../aspose.email/mailmessage/createreadreceipt/)(string, string) | Creates a read receipt for the message. |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt/#decrypt)() | Decrypts the message with a certificate found in the certificate store. |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt/#decrypt_1)(X509Certificate2) | Decrypts the message with the specified certificate. |
| [Dispose](../../aspose.email/mailmessage/dispose/)() | Releases the resources used by the message, including its attachments. |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt/#encrypt)(X509Certificate2) | Creates a copy of the message encrypted for one recipient (S/MIME). |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt/#encrypt_1)(X509Certificate2[]) | Creates a copy of the message encrypted for several recipients (S/MIME). |
| override [Equals](../../aspose.email/mailmessage/equals/)(object) | Determines whether the specified object is equal to this message. |
| [GetAlternateViewContent](../../aspose.email/mailmessage/getalternateviewcontent/)(string) | Gets the content of the alternate view of the specified media type. |
| [GetEnumerator](../../aspose.email/mailmessage/getenumerator/)() | Returns an enumerator that iterates through a collection. |
| override [GetHashCode](../../aspose.email/mailmessage/gethashcode/)() | Returns the hash code of the message. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext/#gethtmlbodytext_1)(bool) | Gets the text of the HTML body without the markup. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext/#gethtmlbodytext)(HyperlinkRenderingCallback) | Gets the text of the HTML body without the markup, rendering hyperlinks with a custom method. |
| virtual [Import](../../aspose.email/mailmessage/import/)(Stream) | Replaces the content of this message with a message read from a stream in EML format. |
| [RecomposeTnefContent](../../aspose.email/mailmessage/recomposetnefcontent/)() | Rebuilds the TNEF attachment (winmail.dat) of a message that was loaded from TNEF, so that it reflects the changes made to the message. |
| virtual [RemoveSignature](../../aspose.email/mailmessage/removesignature/)() | Returns a copy of a signed message without the signature. |
| virtual [Save](../../aspose.email/mailmessage/save/#save)(Stream) | Saves the message to a stream in EML format. |
| virtual [Save](../../aspose.email/mailmessage/save/#save_2)(string) | Saves the message to a file in EML format, whatever the file extension. |
| virtual [Save](../../aspose.email/mailmessage/save/#save_1)(Stream, SaveOptions) | Saves the message to a stream in the format selected by the options. |
| virtual [Save](../../aspose.email/mailmessage/save/#save_3)(string, SaveOptions) | Saves the message to a file in the format selected by the options. |
| virtual [SetHtmlBody](../../aspose.email/mailmessage/sethtmlbody/)(string, bool) | Sets the HTML body, optionally detecting its encoding. |
| override [ToString](../../aspose.email/mailmessage/tostring/)() | Returns a string that represents the message. |
| static [CheckSignature](../../aspose.email/mailmessage/checksignature/#checksignature)(Stream) | Verifies the signature of a message read from a stream in EML format. |
| static [CheckSignature](../../aspose.email/mailmessage/checksignature/#checksignature_1)(string) | Verifies the signature of a message in an EML file. |

## Remarks

Load a message with [`Load`](./load/), save it with [`Save`](./save/). Without options, [`Load`](./load/) recognizes MSG and otherwise reads EML, and [`Save`](./save/) writes EML; pass a [`LoadOptions`](../loadoptions/) or [`SaveOptions`](../saveoptions/) object for other formats. To work with Outlook-specific properties, convert the message to a [`MapiMessage`](../../aspose.email.mapi/mapimessage/).

## Examples

The following example shows how to create a new Email Message and save with SaveOptions.

[C#]

```csharp
var message = new MailMessage
{
    // Set subject of the message, Html body and sender information
    Subject = "New message created by Aspose.Email for .NET",
    HtmlBody = "<b>This line is in bold.</b> <br/> <br/>" +
               "<font color=blue>This line is in blue color</font>",
    From = new MailAddress("from@domain.com", "Sender Name", false)
};

// Add TO recipients and Add CC recipients
message.To.Add(new MailAddress("to1@domain.com", "Recipient 1", false));
message.To.Add(new MailAddress("to2@domain.com", "Recipient 2", false));
message.CC.Add(new MailAddress("cc1@domain.com", "Recipient 3", false));
message.CC.Add(new MailAddress("cc2@domain.com", "Recipient 4", false));

// Save message to EML, EMLX, MSG and MHTML formats
message.Save("CreateNewMailMessage_out.eml", SaveOptions.DefaultEml);
message.Save("CreateNewMailMessage_out.emlx", SaveOptions.CreateSaveOptions(MailMessageSaveType.EmlxFormat));
message.Save("CreateNewMailMessage_out.msg", SaveOptions.DefaultMsgUnicode);
message.Save("CreateNewMailMessage_out.mhtml", SaveOptions.DefaultMhtml);
```

[Visual Basic]

```csharp
' Create a new instance of MailMessage class
Dim message As MailMessage = New MailMessage()

' Set subject of the message, Html body and sender information
message.Subject = "New message created by Aspose.Email for .NET"
message.HtmlBody = "<b>This line is in bold.</b> <br/> <br/>" & "<font color=blue>This line is in blue color</font>"
message.From = New MailAddress("from@domain.com", "Sender Name", False)

' Add TO recipients and Add CC recipients
message.[To].Add(New MailAddress("to1@domain.com", "Recipient 1", False))
message.[To].Add(New MailAddress("to2@domain.com", "Recipient 2", False))
message.CC.Add(New MailAddress("cc1@domain.com", "Recipient 3", False))
message.CC.Add(New MailAddress("cc2@domain.com", "Recipient 4", False))

' Save message in EML, EMLX, MSG and MHTML formats
message.Save("CreateNewMailMessage_out.eml", SaveOptions.DefaultEml)
message.Save("CreateNewMailMessage_out.emlx", SaveOptions.CreateSaveOptions(MailMessageSaveType.EmlxFormat))
message.Save("CreateNewMailMessage_out.msg", SaveOptions.DefaultMsgUnicode)
message.Save("CreateNewMailMessage_out.mhtml", SaveOptions.DefaultMhtml)
```

### See Also

* interface [IMessage](../imessage/)
* interface [IPreferredTextEncodingProvider](../ipreferredtextencodingprovider/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


