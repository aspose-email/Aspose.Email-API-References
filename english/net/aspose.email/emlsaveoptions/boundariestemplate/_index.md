---
title: EmlSaveOptions.BoundariesTemplate
second_title: Aspose.Email for .NET API Reference
description: EmlSaveOptions property. Gets or sets the template for the MIME boundaries of the message null the default uses generated boundaries
type: docs
weight: 20
url: /net/aspose.email/emlsaveoptions/boundariestemplate/
---
## EmlSaveOptions.BoundariesTemplate property

Gets or sets the template for the MIME boundaries of the message; `null` (the default) uses generated boundaries.

```csharp
public string BoundariesTemplate { get; set; }
```

## Remarks

In the template, `{#}` is replaced by the number of the boundary and `{guid}` by a GUID.

## Examples

Example: boundary--{#}-{guid}

### See Also

* class [EmlSaveOptions](../)
* namespace [Aspose.Email](../../emlsaveoptions/)
* assembly [Aspose.Email](../../../)


