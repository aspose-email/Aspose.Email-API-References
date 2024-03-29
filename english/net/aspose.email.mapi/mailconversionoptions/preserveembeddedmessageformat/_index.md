---
title: MailConversionOptions.PreserveEmbeddedMessageFormat
second_title: Aspose.Email for .NET API Reference
description: MailConversionOptions property. Gets or sets a value indicating whether it is necessary to preserve MSG format of embedded message at converting to MailMessage. By default the value is false
type: docs
weight: 40
url: /net/aspose.email.mapi/mailconversionoptions/preserveembeddedmessageformat/
---
## MailConversionOptions.PreserveEmbeddedMessageFormat property

Gets or sets a value indicating whether it is necessary to preserve MSG format of embedded message at converting to MailMessage. By default the value is false.

```csharp
public bool PreserveEmbeddedMessageFormat { get; set; }
```

## Remarks

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from MSG to EML and vice versa, embedded messages are also converted to the target format. Setting the property to true preserves the original format of the embedded messages.

### See Also

* class [MailConversionOptions](../)
* namespace [Aspose.Email.Mapi](../../mailconversionoptions/)
* assembly [Aspose.Email](../../../)


