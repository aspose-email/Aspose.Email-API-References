---
title: MapiAttachment.OpenRead
second_title: Aspose.Email for .NET API Reference
description: MapiAttachment method. Opens the attachment content for reading
type: docs
weight: 180
url: /net/aspose.email.mapi/mapiattachment/openread/
---
## MapiAttachment.OpenRead method

Opens the attachment content for reading.

```csharp
public Stream OpenRead()
```

### Return Value

An independent, read-only, seekable stream over the attachment content.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | If the attachment has no binary content. |

## Remarks

For attachments added from a stream the content is read from the source on demand and is not copied into memory. Each call returns an independent reader, so several readers may be used at the same time.

### See Also

* class [MapiAttachment](../)
* namespace [Aspose.Email.Mapi](../../mapiattachment/)
* assembly [Aspose.Email](../../../)


