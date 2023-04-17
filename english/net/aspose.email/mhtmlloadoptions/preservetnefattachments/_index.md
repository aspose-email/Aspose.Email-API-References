---
title: MhtmlLoadOptions.PreserveTnefAttachments
second_title: Aspose.Email for .NET API Reference
description: MhtmlLoadOptions property. Controls loading TNEF attachment behaviour. By default the value is false
type: docs
weight: 20
url: /net/aspose.email/mhtmlloadoptions/preservetnefattachments/
---
## MhtmlLoadOptions.PreserveTnefAttachments property

Controls loading TNEF attachment behaviour. By default the value is false.

```csharp
public bool PreserveTnefAttachments { get; set; }
```

## Remarks

If a message contains a TNEF attachment (winmail.dat) and has the MIME type application/ms-tnef, then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is true.

### See Also

* class [MhtmlLoadOptions](../)
* namespace [Aspose.Email](../../mhtmlloadoptions/)
* assembly [Aspose.Email](../../../)


