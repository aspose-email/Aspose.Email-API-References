---
title: Class AttachmentBase
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.AttachmentBase class. The base class of attachments alternate views and linked resources a MIME part with its content and headers
type: docs
weight: 340
url: /net/aspose.email/attachmentbase/
---
## AttachmentBase class

The base class of attachments, alternate views and linked resources: a MIME part with its content and headers.

```csharp
public abstract class AttachmentBase : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [ContentId](../../aspose.email/attachmentbase/contentid/) { get; set; } | Gets or sets the content ID of the part, by which HTML refers to it with a `cid:` URL. |
| [ContentStream](../../aspose.email/attachmentbase/contentstream/) { get; set; } | Gets or sets the stream that holds the content. |
| [ContentType](../../aspose.email/attachmentbase/contenttype/) { get; set; } | Gets or sets the content type of the part: its media type, name and character set. |
| virtual [Headers](../../aspose.email/attachmentbase/headers/) { get; } | Gets the MIME headers of the part. |
| [TransferEncoding](../../aspose.email/attachmentbase/transferencoding/) { get; set; } | Gets or sets how the content is encoded for transfer, such as Base64 or quoted-printable. |
| [UniqueId](../../aspose.email/attachmentbase/uniqueid/) { get; } | Gets an identifier of the part that stays the same while the application runs. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.email/attachmentbase/dispose/)() | Releases the resources used by the part, including its content stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/#save)(Stream) | Saves the decoded content of the part to a stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/#save_1)(string) | Saves the decoded content of the part to a file. |

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


