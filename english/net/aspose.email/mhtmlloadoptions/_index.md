---
title: Class MhtmlLoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.MhtmlLoadOptions class. Allows to specify additional options when loading MailMessage from Mhtml format
type: docs
weight: 19380
url: /net/aspose.email/mhtmlloadoptions/
---
## MhtmlLoadOptions class

Allows to specify additional options when loading MailMessage from Mhtml format.

```csharp
public class MhtmlLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MhtmlLoadOptions](mhtmlloadoptions/)() | Initializes a new instance of this class that can be used to loading MailMessage from Mhtml format. |

## Properties

| Name | Description |
| --- | --- |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Represents the mail message format.It can be in eml,msg or mhtml format. The default value is Eml. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. By default the value is false. |
| [PreserveTnefAttachments](../../aspose.email/mhtmlloadoptions/preservetnefattachments/) { get; set; } | Controls loading TNEF attachment behaviour. By default the value is false. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether signature will be removed while loading. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


