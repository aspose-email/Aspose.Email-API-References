---
title: EmlLoadOptions.PreserveTnefAttachments
second_title: Aspose.Email for .NET API Reference
description: EmlLoadOptions property. Controls TNEF attachment loading behaviour. By default the value is false
type: docs
weight: 20
url: /net/aspose.email/emlloadoptions/preservetnefattachments/
---
## EmlLoadOptions.PreserveTnefAttachments property

Controls TNEF attachment loading behaviour. By default the value is false.

```csharp
public bool PreserveTnefAttachments { get; set; }
```

## Remarks

If a message contains a TNEF attachment (winmail.dat) and has the MIME type application/ms-tnef, then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is true.

### See Also

* class [EmlLoadOptions](../)
* namespace [Aspose.Email](../../emlloadoptions/)
* assembly [Aspose.Email](../../../)


