---
title: Class Attachment
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Attachment class. Represents an email attachment
type: docs
weight: 330
url: /net/aspose.email/attachment/
---
## Attachment class

Represents an e-mail attachment.

```csharp
public class Attachment : AttachmentBase, IAttachment, IPreferredTextEncodingProvider
```

## Constructors

| Name | Description |
| --- | --- |
| [Attachment](attachment/#constructor_3)(string) | Initializes a new instance of the `Attachment` class. |
| [Attachment](attachment/#constructor)(Stream, ContentType) | Initializes a new instance of the `Attachment` class. |
| [Attachment](attachment/#constructor_1)(Stream, string) | Initializes a new instance of the `Attachment` class. |
| [Attachment](attachment/#constructor_4)(string, ContentType) | Initializes a new instance of the `Attachment` class. |
| [Attachment](attachment/#constructor_5)(string, string) | Initializes a new instance of the `Attachment` class. |
| [Attachment](attachment/#constructor_2)(Stream, string, string) | Initializes a new instance of the `Attachment` class. |

## Properties

| Name | Description |
| --- | --- |
| [ContentDisposition](../../aspose.email/attachment/contentdisposition/) { get; } | Gets Content-Disposition header |
| [ContentId](../../aspose.email/attachmentbase/contentid/) { get; set; } | Gets or sets the content id. |
| [ContentStream](../../aspose.email/attachmentbase/contentstream/) { get; set; } | Gets or sets the content stream. |
| [ContentType](../../aspose.email/attachmentbase/contenttype/) { get; set; } | Gets or sets the type of the content. |
| virtual [Headers](../../aspose.email/attachmentbase/headers/) { get; } | Gets headers collection of attachment. |
| [IsEmbeddedMessage](../../aspose.email/attachment/isembeddedmessage/) { get; } | Gets a value indicating whether the attachment is an embedded message. |
| [IsTnef](../../aspose.email/attachment/istnef/) { get; } | Gets a value indicating whether the attachment is TNEF formatted message. |
| [IsUri](../../aspose.email/attachment/isuri/) { get; } | Gets a value indicating whether attachment is URI-attachment. |
| [Name](../../aspose.email/attachment/name/) { get; set; } | Gets or sets an attachment name |
| [NameEncoding](../../aspose.email/attachment/nameencoding/) { get; set; } | Gets or sets an encoding of attachment name |
| [PreferredTextEncoding](../../aspose.email/attachment/preferredtextencoding/) { get; set; } | Gets or sets a preferred text encoding |
| [TransferEncoding](../../aspose.email/attachmentbase/transferencoding/) { get; set; } | Gets or sets the transfer encoding. |
| [UniqueId](../../aspose.email/attachment/uniqueid/) { get; } | Gets or sets a unique identifier for the attachment that will be constant for each application run. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring/#createattachmentfromstring)(string, ContentType) | Creates the attachment from string. |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring/#createattachmentfromstring_1)(string, string) | Creates the attachment from string. |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring/#createattachmentfromstring_2)(string, string, Encoding, string) | Creates the attachment from string. |
| [Dispose](../../aspose.email/attachmentbase/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(Stream) | Saves the specified stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/)(string) | Saves the specified file name. |

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


