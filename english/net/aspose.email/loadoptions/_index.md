---
title: Class LoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.LoadOptions class. This is an abstract base class for classes that allow the user to specify additional options when loading a MailMessage from a particular format
type: docs
weight: 17670
url: /net/aspose.email/loadoptions/
---
## LoadOptions class

This is an abstract base class for classes that allow the user to specify additional options when loading a MailMessage from a particular format.

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

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


