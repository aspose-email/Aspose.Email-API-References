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
| [EmlxLoadOptions](emlxloadoptions/)() | Initializes a new instance of this class that can be used to loading MailMessage from Eml format. |

## Properties

| Name | Description |
| --- | --- |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Represents the mail message format.It can be in eml,msg or mhtml format. The default value is Eml. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. By default the value is false. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether signature will be removed while loading. |

## Remarks

Use this class with [`Load`](../mailmessage/load/) to load Apple Mail EMLX files. The EMLX format is used by Apple Mail on macOS and iOS devices.

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


