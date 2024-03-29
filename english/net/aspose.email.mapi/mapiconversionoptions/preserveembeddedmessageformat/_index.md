---
title: MapiConversionOptions.PreserveEmbeddedMessageFormat
second_title: Aspose.Email for .NET API Reference
description: MapiConversionOptions property. Gets or sets a value indicating whether it is necessary to preserve EML format of embedded message at converting to MapiMessage. By default the value is false
type: docs
weight: 70
url: /net/aspose.email.mapi/mapiconversionoptions/preserveembeddedmessageformat/
---
## MapiConversionOptions.PreserveEmbeddedMessageFormat property

Gets or sets a value indicating whether it is necessary to preserve EML format of embedded message at converting to MapiMessage. By default the value is false.

```csharp
public bool PreserveEmbeddedMessageFormat { get; set; }
```

## Remarks

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from EML to MSG and vice versa, embedded messages are also converted to the target format. Setting the property to true preserves the original format of embedded messages.

### See Also

* class [MapiConversionOptions](../)
* namespace [Aspose.Email.Mapi](../../mapiconversionoptions/)
* assembly [Aspose.Email](../../../)


