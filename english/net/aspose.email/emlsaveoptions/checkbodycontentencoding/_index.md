---
title: EmlSaveOptions.CheckBodyContentEncoding
second_title: Aspose.Email for .NET API Reference
description: EmlSaveOptions property. Gets or sets a value indicating whether the encoding of the HTML body is checked before saving. The default is false
type: docs
weight: 30
url: /net/aspose.email/emlsaveoptions/checkbodycontentencoding/
---
## EmlSaveOptions.CheckBodyContentEncoding property

Gets or sets a value indicating whether the encoding of the HTML body is checked before saving. The default is `false`.

```csharp
public bool CheckBodyContentEncoding { get; set; }
```

## Remarks

When `true` and the HTML body declares an encoding that differs from [`BodyEncoding`](../../mailmessage/bodyencoding/), both [`BodyEncoding`](../../mailmessage/bodyencoding/) and [`PreferredTextEncoding`](../../mailmessage/preferredtextencoding/) are set to UTF-8.

### See Also

* class [EmlSaveOptions](../)
* namespace [Aspose.Email](../../emlsaveoptions/)
* assembly [Aspose.Email](../../../)


