---
title: MhtSaveOptions.CheckBodyContentEncoding
second_title: Aspose.Email for .NET API Reference
description: MhtSaveOptions property. Defines whether need check message body content encoding when saving. By default the value is false
type: docs
weight: 20
url: /net/aspose.email/mhtsaveoptions/checkbodycontentencoding/
---
## MhtSaveOptions.CheckBodyContentEncoding property

Defines whether need check message body content encoding when saving. By default the value is false.

```csharp
public bool CheckBodyContentEncoding { get; set; }
```

## Remarks

If true, it will be check whether the [`HtmlBody`](../../mailmessage/htmlbody/) content encoding matches to the encoding specified by the [`BodyEncoding`](../../mailmessage/bodyencoding/) property. If the HtmlBody content encoding doesn't match BodyEncoding property, the [`BodyEncoding`](../../mailmessage/bodyencoding/) and [`PreferredTextEncoding`](../../mailmessage/preferredtextencoding/) properties will be changed to default UTF8.

### See Also

* class [MhtSaveOptions](../)
* namespace [Aspose.Email](../../mhtsaveoptions/)
* assembly [Aspose.Email](../../../)


