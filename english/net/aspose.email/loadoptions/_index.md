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
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Represents the mail message format.It can be in eml,msg or mhtml format. The default value is Eml. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. By default the value is false. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether signature will be removed while loading. |

## Remarks

This class is designed to be inherited by concrete format-specific classes like [`EmlLoadOptions`](../emlloadoptions/), [`EmlxLoadOptions`](../emlxloadoptions/), and [`HtmlLoadOptions`](../htmlloadoptions/). Do not instantiate this class directly. Use the format-specific subclasses to access format-specific loading options.

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


