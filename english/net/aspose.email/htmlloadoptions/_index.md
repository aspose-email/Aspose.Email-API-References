---
title: Class HtmlLoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.HtmlLoadOptions class. Allows to specify additional options when loading MailMessage from Html format
type: docs
weight: 16190
url: /net/aspose.email/htmlloadoptions/
---
## HtmlLoadOptions class

Allows to specify additional options when loading MailMessage from Html format.

```csharp
public class HtmlLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/)() | Initializes a new instance of this class that can be used to loading MailMessage from Html format. |

## Properties

| Name | Description |
| --- | --- |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Represents the mail message format.It can be in eml,msg or mhtml format. The default value is Eml. |
| [PathToResources](../../aspose.email/htmlloadoptions/pathtoresources/) { get; set; } | Path to directory with resources files. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. By default the value is false. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether signature will be removed while loading. |
| [ShouldAddPlainTextView](../../aspose.email/htmlloadoptions/shouldaddplaintextview/) { get; set; } | Specifies whether to add a text representation of the body or not. Default value is false. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


