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
| [MhtmlLoadOptions](mhtmlloadoptions/)() | Initializes a new instance of this class that can be used to loading MailMessage from Mhtml format. |

## Properties

| Name | Description |
| --- | --- |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Represents the mail message format.It can be in eml,msg or mhtml format. The default value is Eml. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. By default the value is false. |
| [PreserveTnefAttachments](../../aspose.email/mhtmlloadoptions/preservetnefattachments/) { get; set; } | Controls loading TNEF attachment behaviour. By default the value is false. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether signature will be removed while loading. |

## Remarks

Use this class with [`Load`](../mailmessage/load/) to load MHTML files and control TNEF attachment handling. MHTML is a web page archive format that combines HTML content and embedded resources into a single file. The [`PreserveTnefAttachments`](./preservetnefattachments/) property controls whether TNEF attachments (winmail.dat) are decoded or preserved as-is.

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


