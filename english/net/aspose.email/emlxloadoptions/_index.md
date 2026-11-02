---
title: Class EmlxLoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.EmlxLoadOptions class. Provides options for controlling how MailMessage instances are loaded from EMLX format. This class inherits from LoadOptions and is specifically designed for Apple Mail EMLX file format
type: docs
weight: 16070
url: /net/aspose.email/emlxloadoptions/
---
## EmlxLoadOptions class

Provides options for controlling how [`MailMessage`](../mailmessage/) instances are loaded from EMLX format. This class inherits from [`LoadOptions`](../loadoptions/) and is specifically designed for Apple Mail EMLX file format.

```csharp
public class EmlxLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [EmlxLoadOptions](emlxloadoptions/)() | Initializes a new instance of the `EmlxLoadOptions` class with the default options. |

## Properties

| Name | Description |
| --- | --- |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Gets the format this options object loads, as determined by its class: EML, MSG, MHTML, HTML and so on. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets the encoding used for the subject and the body regardless of what the message declares. The default is `null`: the declared encoding is used. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. The default is `false`. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether the digital signature is removed from a signed message while it is loaded. |

## Remarks

Use this class with [`Load`](../mailmessage/load/) to load Apple Mail EMLX files. The EMLX format is used by Apple Mail on macOS and iOS devices.

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


