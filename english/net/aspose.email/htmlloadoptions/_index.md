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


