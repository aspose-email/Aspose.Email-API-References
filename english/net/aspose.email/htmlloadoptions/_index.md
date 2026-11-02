---
title: Class HtmlLoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.HtmlLoadOptions class. Provides options for controlling how MailMessage instances are loaded from HTML format. This class allows you to specify resource paths and control the generation of plain text views when converting HTML messages to MailMessage objects
type: docs
weight: 16290
url: /net/aspose.email/htmlloadoptions/
---
## HtmlLoadOptions class

Provides options for controlling how [`MailMessage`](../mailmessage/) instances are loaded from HTML format. This class allows you to specify resource paths and control the generation of plain text views when converting HTML messages to MailMessage objects.

```csharp
public class HtmlLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/)() | Initializes a new instance of the `HtmlLoadOptions` class with the default options. |

## Properties

| Name | Description |
| --- | --- |
| [MessageFormat](../../aspose.email/loadoptions/messageformat/) { get; } | Gets the format this options object loads, as determined by its class: EML, MSG, MHTML, HTML and so on. |
| [PathToResources](../../aspose.email/htmlloadoptions/pathtoresources/) { get; set; } | Gets or sets the folder that relative paths of images and other resources in the HTML are resolved against. |
| [PreferredTextEncoding](../../aspose.email/loadoptions/preferredtextencoding/) { get; set; } | Gets or sets the encoding used for the subject and the body regardless of what the message declares. The default is `null`: the declared encoding is used. |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat/) { get; set; } | Gets or sets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. The default is `false`. |
| [RemoveSignature](../../aspose.email/loadoptions/removesignature/) { get; set; } | Gets or sets a value indicating whether the digital signature is removed from a signed message while it is loaded. |
| [ShouldAddPlainTextView](../../aspose.email/htmlloadoptions/shouldaddplaintextview/) { get; set; } | Gets or sets a value indicating whether a plain-text version of the body is added to the message. The default is `false`. |

## Remarks

Use this class with [`Load`](../mailmessage/load/) to load HTML files and convert them to MailMessage objects. The [`PathToResources`](./pathtoresources/) property enables loading of external resources (images, CSS) referenced in the HTML, while [`ShouldAddPlainTextView`](./shouldaddplaintextview/) controls whether to automatically generate a plain text alternate view.

## Examples

The following example shows how to load an HTML file and preserve external resources.

[C#]

```csharp
// Create HTML load options with path to resources
var loadOptions = new HtmlLoadOptions()
{
    PathToResources = "C:\\resources\\",
    ShouldAddPlainTextView = true
};

// Load HTML file
using (MailMessage message = MailMessage.Load("sample.html", loadOptions))
{
    // Convert to EML format
    message.Save("output.eml", SaveOptions.DefaultEml);
}
```

[Visual Basic]

```csharp
' Create HTML load options with path to resources
Dim loadOptions As New HtmlLoadOptions() With {
    .PathToResources = "C:\resources\",
    .ShouldAddPlainTextView = True
}

' Load HTML file
Using message As MailMessage = MailMessage.Load("sample.html", loadOptions)
    ' Convert to EML format
    message.Save("output.eml", SaveOptions.DefaultEml)
End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


