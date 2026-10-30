---
title: Class Attachment
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Attachment class. Represents an email attachment that can be added to a MailMessage. This class provides functionality for managing attachment content name content type encoding and content disposition. It supports various attachment types including regular files embedded messages message/rfc822 and TNEF formatted messages
type: docs
weight: 330
url: /net/aspose.email/attachment/
---
## Attachment class

Represents an email attachment that can be added to a [`MailMessage`](../mailmessage/). This class provides functionality for managing attachment content, name, content type, encoding, and content disposition. It supports various attachment types including regular files, embedded messages (message/rfc822), and TNEF formatted messages.

```csharp
public class Attachment : AttachmentBase, IAttachment, IPreferredTextEncodingProvider
```

## Constructors

| Name | Description |
| --- | --- |
| [Attachment](attachment/#constructor_3)(string) | Initializes a new instance of the `Attachment` class with the content of a file. |
| [Attachment](attachment/#constructor)(Stream, ContentType) | Initializes a new instance of the `Attachment` class with the content of a stream. |
| [Attachment](attachment/#constructor_1)(Stream, string) | Initializes a new instance of the `Attachment` class with the content of a stream. |
| [Attachment](attachment/#constructor_4)(string, ContentType) | Initializes a new instance of the `Attachment` class with the content of a file. |
| [Attachment](attachment/#constructor_5)(string, string) | Initializes a new instance of the `Attachment` class with the content of a file. |
| [Attachment](attachment/#constructor_2)(Stream, string, string) | Initializes a new instance of the `Attachment` class with the content of a stream. |

## Properties

| Name | Description |
| --- | --- |
| [ContentDisposition](../../aspose.email/attachment/contentdisposition/) { get; } | Gets the `Content-Disposition` header of the attachment, which tells whether it is shown inline or as a file, and holds its file name and dates. |
| [ContentId](../../aspose.email/attachmentbase/contentid/) { get; set; } | Gets or sets the content ID of the part, by which HTML refers to it with a `cid:` URL. |
| [ContentStream](../../aspose.email/attachmentbase/contentstream/) { get; set; } | Gets or sets the stream that holds the content. |
| [ContentType](../../aspose.email/attachmentbase/contenttype/) { get; set; } | Gets or sets the content type of the part: its media type, name and character set. |
| virtual [Headers](../../aspose.email/attachmentbase/headers/) { get; } | Gets the MIME headers of the part. |
| [IsEmbeddedMessage](../../aspose.email/attachment/isembeddedmessage/) { get; } | Gets a value indicating whether the attachment is an attached e-mail message (`message/rfc822`). |
| [IsTnef](../../aspose.email/attachment/istnef/) { get; } | Gets a value indicating whether the attachment is a TNEF-encoded message (winmail.dat). |
| [IsUri](../../aspose.email/attachment/isuri/) { get; } | Gets a value indicating whether the attachment is a link to content elsewhere rather than the content itself. |
| [Name](../../aspose.email/attachment/name/) { get; set; } | Gets or sets the file name of the attachment. |
| [NameEncoding](../../aspose.email/attachment/nameencoding/) { get; set; } | Gets or sets the encoding used for the file name of the attachment in the headers. |
| [PreferredTextEncoding](../../aspose.email/attachment/preferredtextencoding/) { get; set; } | Gets or sets the encoding used for the text of the attachment when no other encoding is specified. |
| [TransferEncoding](../../aspose.email/attachmentbase/transferencoding/) { get; set; } | Gets or sets how the content is encoded for transfer, such as Base64 or quoted-printable. |
| [UniqueId](../../aspose.email/attachmentbase/uniqueid/) { get; } | Gets an identifier of the part that stays the same while the application runs. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring/#createattachmentfromstring)(string, ContentType) | Creates an attachment from a string with the specified content type. |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring/#createattachmentfromstring_1)(string, string) | Creates a text attachment from a string. |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring/#createattachmentfromstring_2)(string, string, Encoding, string) | Creates an attachment from a string with the specified encoding and media type. |
| [Dispose](../../aspose.email/attachmentbase/dispose/)() | Releases the resources used by the part, including its content stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(Stream) | Saves the decoded content of the part to a stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(string) | Saves the decoded content of the part to a file. |

## Remarks

Use [`CreateAttachmentFromString`](./createattachmentfromstring/) to create attachments from string content. Add attachments to [`Attachments`](../mailmessage/attachments/) to include them in the message.

## Examples

The following example shows how to add and remove an Attachment from MailMessage.

[C#]

```csharp
// Create an instance of MailMessage class
var eml = new MailMessage {From = "sender@sender.com", To = "receiver@gmail.com"};

// Load an attachment
var attachment = new Attachment("1.txt");
eml.Attachments.Add(attachment);

// Remove attachment from your MailMessage
eml.Attachments.Remove(attachment);
```

[Visual Basic]

```csharp
' Create an instance of MailMessage class
Dim eml = New MailMessage With {
  .From = "sender@sender.com",
			.[To] = "receiver@gmail.com"
		}

' Load an attachment
Dim attachment = New Attachment("1.txt")
eml.Attachments.Add(attachment)

' Remove attachment from your MailMessage
eml.Attachments.Remove(attachment)
```

### See Also

* class [AttachmentBase](../attachmentbase/)
* interface [IAttachment](../iattachment/)
* interface [IPreferredTextEncodingProvider](../ipreferredtextencodingprovider/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


