---
title: LoadOptions.PreserveEmbeddedMessageFormat
second_title: Aspose.Email for .NET API Reference
description: LoadOptions property. Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. By default the value is false
type: docs
weight: 30
url: /net/aspose.email/loadoptions/preserveembeddedmessageformat/
---
## LoadOptions.PreserveEmbeddedMessageFormat property

Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. By default the value is false.

```csharp
public bool PreserveEmbeddedMessageFormat { get; set; }
```

## Remarks

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from EML to MSG and vice versa, embedded messages are also converted to the target format. Setting the property to true preserves the original format of embedded messages.

### See Also

* class [LoadOptions](../)
* namespace [Aspose.Email](../../loadoptions/)
* assembly [Aspose.Email](../../../)


