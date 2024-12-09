---
title: MapiAttachment.IsReference
second_title: Aspose.Email for .NET API Reference
description: MapiAttachment property. Gets a value indicating whether the attachment is stored as a reference rather than being embedded in the email
type: docs
weight: 70
url: /net/aspose.email.mapi/mapiattachment/isreference/
---
## MapiAttachment.IsReference property

Gets a value indicating whether the attachment is stored as a reference rather than being embedded in the email.

```csharp
public bool IsReference { get; }
```

### Property Value

`true` if the attachment is stored as a reference; otherwise, `false`.

## Remarks

This property determines if the attachment is referenced by its file path or a web link based on the `PidTagAttachMethod` MAPI property. The following values indicate a reference-based attachment:

* `0x00000002` - `afByReference`: The attachment is identified by a fully qualified file path, accessible to recipients with shared access to the file server.
* `0x00000004` - `afByReferenceOnly`: The attachment is identified solely by its fully qualified file path.
* `0x00000007` - `afByWebReference`: The attachment is identified by a web link, with the `PidNameAttachmentProviderType` specifying the web service API handling the attachment.

If the attachment does not match these criteria, this property returns `false`.

### See Also

* class [MapiAttachment](../)
* namespace [Aspose.Email.Mapi](../../mapiattachment/)
* assembly [Aspose.Email](../../../)


