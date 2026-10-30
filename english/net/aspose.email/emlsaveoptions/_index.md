---
title: Class EmlSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.EmlSaveOptions class. Provides options for controlling how MailMessage instances are saved to EML and EMLX format. This class allows you to customize the saving behavior for features such as embedded message format preservation TNEF handling signed message integrity and boundary template configuration
type: docs
weight: 16030
url: /net/aspose.email/emlsaveoptions/
---
## EmlSaveOptions class

Provides options for controlling how [`MailMessage`](../mailmessage/) instances are saved to EML and EMLX format. This class allows you to customize the saving behavior for features such as embedded message format preservation, TNEF handling, signed message integrity, and boundary template configuration.

```csharp
public class EmlSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [EmlSaveOptions](emlsaveoptions/)(MailMessageSaveType) | Initializes a new instance of the `EmlSaveOptions` class for the specified format. |

## Properties

| Name | Description |
| --- | --- |
| [BoundariesTemplate](../../aspose.email/emlsaveoptions/boundariestemplate/) { get; set; } | Gets or sets the template for the MIME boundaries of the message; `null` (the default) uses generated boundaries. |
| [CheckBodyContentEncoding](../../aspose.email/emlsaveoptions/checkbodycontentencoding/) { get; set; } | Gets or sets a value indicating whether the encoding of the HTML body is checked before saving. The default is `false`. |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler/) { get; set; } | Gets or sets a handler that is called as the saving progresses. |
| [FileCompatibilityMode](../../aspose.email/emlsaveoptions/filecompatibilitymode/) { get; set; } | Gets or sets conversions applied while saving, such as encoding the TNEF attachment again. The default is `FileCompatibilityMode.None`. |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype/) { get; set; } | Gets or sets the format the options save to. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/emlsaveoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether embedded messages keep their original format (MSG) instead of being converted to EML. The default is `false`. |
| [PreserveSignedContent](../../aspose.email/emlsaveoptions/preservesignedcontent/) { get; set; } | Gets or sets a value indicating whether a signed message is saved exactly as it was loaded, so that its signature stays valid. The default is `false`. |

## Remarks

Use this class with [`Save`](../mailmessage/save/) to specify custom save options. Inherits from [`SaveOptions`](../saveoptions/) and adds EML/EMLX-specific configuration through properties like [`PreserveEmbeddedMessageFormat`](./preserveembeddedmessageformat/), [`PreserveSignedContent`](./preservesignedcontent/), and [`BoundariesTemplate`](./boundariestemplate/).

## Examples

The following example shows how to load and Save an EML message Preserving the embedded message format.

[C#]

```csharp
MailMessage mailMessage = MailMessage.Load("source.eml");
// Save as eml with preserved embedded message format
EmlSaveOptions emlSaveOptions = new EmlSaveOptions(MailMessageSaveType.EmlFormat)
{
     PreserveEmbeddedMessageFormat = true
};
mailMessage.Save("target.eml", emlSaveOptions);
```

[Visual Basic]

```csharp
Dim mailMessage As MailMessage = MailMessage.Load("source.eml")

' Save as eml with preserved embedded message format
Dim emlSaveOptions As EmlSaveOptions = New EmlSaveOptions(MailMessageSaveType.EmlFormat) With {
       .PreserveEmbeddedMessageFormat = True
       }
		}
mailMessage.Save("target.eml", emlSaveOptions)
```

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


