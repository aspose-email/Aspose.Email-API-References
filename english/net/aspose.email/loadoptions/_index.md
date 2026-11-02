---
title: Class LoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.LoadOptions class. Serves as the abstract base class for formatspecific options when loading MailMessage from various email formats EML EMLX HTML MHTML etc.. This class provides common configuration properties such as text encoding embedded message format preservation and signature handling
type: docs
weight: 16420
url: /net/aspose.email/loadoptions/
---
## LoadOptions class

Serves as the abstract base class for format-specific options when loading [`MailMessage`](../mailmessage/) from various email formats (EML, EMLX, HTML, MHTML, etc.). This class provides common configuration properties such as text encoding, embedded message format preservation, and signature handling.

```csharp
public abstract class LoadOptions
```

## Properties

| Name | Description |
| --- | --- |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Gets the format this options object loads, as determined by its class: EML, MSG, MHTML, HTML and so on. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets the encoding used for the subject and the body regardless of what the message declares. The default is `null`: the declared encoding is used. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. The default is `false`. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether the digital signature is removed from a signed message while it is loaded. |

## Remarks

This class is designed to be inherited by concrete format-specific classes like [`EmlLoadOptions`](../emlloadoptions/), [`EmlxLoadOptions`](../emlxloadoptions/), and [`HtmlLoadOptions`](../htmlloadoptions/). Do not instantiate this class directly. Use the format-specific subclasses to access format-specific loading options.

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


