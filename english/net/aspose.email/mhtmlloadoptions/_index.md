---
title: Class MhtmlLoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.MhtmlLoadOptions class. Provides options for controlling how MailMessage instances are loaded from MHTML format. This class allows you to customize the loading behavior for MHTML MIME HTML files particularly for handling TNEF attachments that may be embedded in the message
type: docs
weight: 18000
url: /net/aspose.email/mhtmlloadoptions/
---
## MhtmlLoadOptions class

Provides options for controlling how [`MailMessage`](../mailmessage/) instances are loaded from MHTML format. This class allows you to customize the loading behavior for MHTML (MIME HTML) files, particularly for handling TNEF attachments that may be embedded in the message.

```csharp
public class MhtmlLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MhtmlLoadOptions](mhtmlloadoptions/)() | Initializes a new instance of the `MhtmlLoadOptions` class with the default options. |

## Properties

| Name | Description |
| --- | --- |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Gets the format this options object loads, as determined by its class: EML, MSG, MHTML, HTML and so on. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets the encoding used for the subject and the body regardless of what the message declares. The default is `null`: the declared encoding is used. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. The default is `false`. |
| [PreserveTnefAttachments](../../aspose.email/mhtmlloadoptions/preservetnefattachments/) { get; set; } | Gets or sets a value indicating whether a TNEF attachment (winmail.dat) is kept as it is instead of being decoded into its files. The default is `false`. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether the digital signature is removed from a signed message while it is loaded. |

## Remarks

Use this class with [`Load`](../mailmessage/load/) to load MHTML files and control TNEF attachment handling. MHTML is a web page archive format that combines HTML content and embedded resources into a single file. The [`PreserveTnefAttachments`](./preservetnefattachments/) property controls whether TNEF attachments (winmail.dat) are decoded or preserved as-is.

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


