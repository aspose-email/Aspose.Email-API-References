---
title: MsgLoadOptions.DeferAttachmentContent
second_title: Aspose.Email for .NET API Reference
description: MsgLoadOptions property. Gets or sets a value indicating whether attachment content is read on demand instead of being loaded into memory while the message is being loaded. The default value is false
type: docs
weight: 20
url: /net/aspose.email/msgloadoptions/deferattachmentcontent/
---
## MsgLoadOptions.DeferAttachmentContent property

Gets or sets a value indicating whether attachment content is read on demand instead of being loaded into memory while the message is being loaded. The default value is false.

```csharp
public bool DeferAttachmentContent { get; set; }
```

## Remarks

This makes the memory needed to load a message independent of the size of its attachments, which matters for messages with large attachments.

The source must stay readable until the message is disposed. For the file based overloads of [`Load`](../../../aspose.email.mapi/mapimessage/load/) the library keeps the file open and closes it in Dispose, so the message must be disposed. For the stream based overloads the caller keeps the stream open. Reading attachment content after the source has been closed throws.

Saving the message back over the file it was loaded from is still supported: the content is materialised first, because the source cannot be read and overwritten at once.

### See Also

* class [MsgLoadOptions](../)
* namespace [Aspose.Email](../../msgloadoptions/)
* assembly [Aspose.Email](../../../)


