---
title: Class EmlLoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.EmlLoadOptions class. Provides options for controlling how MailMessage instances are loaded from EML format. This class allows you to customize the loading behavior for specific EML features such as TNEF attachment handling and embedded message preservation
type: docs
weight: 16020
url: /net/aspose.email/emlloadoptions/
---
## EmlLoadOptions class

Provides options for controlling how [`MailMessage`](../mailmessage/) instances are loaded from EML format. This class allows you to customize the loading behavior for specific EML features such as TNEF attachment handling and embedded message preservation.

```csharp
public class EmlLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [EmlLoadOptions](emlloadoptions/)() | Initializes a new instance of the `EmlLoadOptions` class with the default options. |

## Properties

| Name | Description |
| --- | --- |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Gets the format this options object loads, as determined by its class: EML, MSG, MHTML, HTML and so on. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets the encoding used for the subject and the body regardless of what the message declares. The default is `null`: the declared encoding is used. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. The default is `false`. |
| [PreserveTnefAttachments](../../aspose.email/emlloadoptions/preservetnefattachments/) { get; set; } | Gets or sets a value indicating whether a TNEF attachment (winmail.dat) is kept as it is instead of being decoded into its files. The default is `false`. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether the digital signature is removed from a signed message while it is loaded. |

## Remarks

Use this class with [`Load`](../mailmessage/load/) to specify custom loading options. Inherits from [`LoadOptions`](../loadoptions/) and adds EML-specific configuration through properties like [`PreserveTnefAttachments`](./preservetnefattachments/).

## Examples

The following example shows how to convert EML to MSG.

[C#]

```csharp
// Initialize EmlLoadOptions
var emlLoadOptions = new EmlLoadOptions()
       {
               PreserveTnefAttachments = true,
               PreserveEmbeddedMessageFormat = true
       };

// Initialize MailMessage with EmlLoadOptions
using (MailMessage message = MailMessage.Load("TestEml.eml", emlLoadOptions))
{
	// Convert EML to MSG
	message.Save("output.msg", SaveOptions.DefaultMsg);
}
```

[Visual Basic]

```csharp
' Initialize EmlLoadOptions
Dim emlLoadOptions = New EmlLoadOptions() With
{
             .PreserveTnefAttachments = True,
             .PreserveEmbeddedMessageFormat = True
       }

' Initialize MailMessage with EmlLoadOptions
Using message As MailMessage = MailMessage.Load("TestEml.eml", emlLoadOptions)
	' Convert EML to MSG
	message.Save("output.msg", SaveOptions.DefaultMsg)
End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


