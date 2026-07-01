---
title: Class AttachmentBase
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.AttachmentBase class. Provides the base class for mail attachments and inline views. This abstract class supplies core functionality for managing attachment content MIME parts content identifiers and resource disposal
type: docs
weight: 340
url: /net/aspose.email/attachmentbase/
---
## AttachmentBase class

Provides the base class for mail attachments and inline views. This abstract class supplies core functionality for managing attachment content, MIME parts, content identifiers, and resource disposal.

```csharp
public abstract class AttachmentBase : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [ContentId](../../aspose.email/attachmentbase/contentid/) { get; set; } | Gets or sets the content id. |
| [ContentStream](../../aspose.email/attachmentbase/contentstream/) { get; set; } | Gets or sets the content stream. |
| [ContentType](../../aspose.email/attachmentbase/contenttype/) { get; set; } | Gets or sets the type of the content. |
| virtual [Headers](../../aspose.email/attachmentbase/headers/) { get; } | Gets headers collection of attachment. |
| [TransferEncoding](../../aspose.email/attachmentbase/transferencoding/) { get; set; } | Gets or sets the transfer encoding. |
| [UniqueId](../../aspose.email/attachmentbase/uniqueid/) { get; } | Gets or sets a unique identifier for the attachment that will be constant for each application run. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.email/attachmentbase/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [Save](../../aspose.email/attachmentbase/save/#save)(Stream) | Saves the specified stream. |
| virtual [Save](../../aspose.email/attachmentbase/save/#save_1)(string) | Saves the specified file name. |

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


