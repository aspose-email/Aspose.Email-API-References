---
title: Class HtmlSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.HtmlSaveOptions class. Provides options for controlling how MailMessage instances are saved to HTML format. This class allows you to customize HTML output formatting resource rendering modes and encoding behavior when converting email messages to HTML files
type: docs
weight: 16300
url: /net/aspose.email/htmlsaveoptions/
---
## HtmlSaveOptions class

Provides options for controlling how [`MailMessage`](../mailmessage/) instances are saved to HTML format. This class allows you to customize HTML output formatting, resource rendering modes, and encoding behavior when converting email messages to HTML files.

```csharp
public class HtmlSaveOptions : HeadersFormattingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/)() | Initializes a new instance of the `HtmlSaveOptions` class with the default options. |

## Properties

| Name | Description |
| --- | --- |
| [AfterHeadersFormat](../../aspose.email/headersformattingoptions/afterheadersformat/) { get; set; } | Gets or sets the HTML written after the block of headers. |
| [BeforeHeadersFormat](../../aspose.email/headersformattingoptions/beforeheadersformat/) { get; set; } | Gets or sets the HTML written before the block of headers. |
| [CheckBodyContentEncoding](../../aspose.email/htmlsaveoptions/checkbodycontentencoding/) { get; set; } | Gets or sets a value indicating whether the encoding of the HTML body is checked before saving. The default is `false`. |
| [CssStyles](../../aspose.email/headersformattingoptions/cssstyles/) { get; set; } | Gets or sets additional CSS styles added to the output. |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler/) { get; set; } | Gets or sets a handler that is called as the saving progresses. |
| [DefaultHeaderFormat](../../aspose.email/headersformattingoptions/defaultheaderformat/) { get; set; } | Gets or sets the HTML format of a header line, from which the template of each header in [`FormatTemplates`](../headersformattingoptions/formattemplates/) is built; `{0}` stands for the name of the header. |
| [DefaultPageHeaderFormat](../../aspose.email/headersformattingoptions/defaultpageheaderformat/) { get; set; } | Gets or sets the HTML format of the page header. |
| [ExtractHTMLBodyResourcesAsAttachments](../../aspose.email/headersformattingoptions/extracthtmlbodyresourcesasattachments/) { get; set; } | Gets or sets a value indicating whether the resources of the HTML body, such as images, are also written as attachments. The default is `false`. |
| [FormatTemplates](../../aspose.email/headersformattingoptions/formattemplates/) { get; } | Gets the formats of individual headers, keyed by the names in [`MhtTemplateName`](../mhttemplatename/). |
| [HtmlFormatOptions](../../aspose.email/htmlsaveoptions/htmlformatoptions/) { get; set; } | Gets or sets options for the HTML output, such as whether the headers are written. The default is `HtmlFormatOptions.None`. |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype/) { get; set; } | Gets or sets the format the options save to. |
| [RenderedContactFields](../../aspose.email/headersformattingoptions/renderedcontactfields/) { get; set; } | Gets or sets the groups of contact fields written for a contact. The default is `ContactFieldsSet.AllExisting`. |
| [RenderingHeaders](../../aspose.email/headersformattingoptions/renderingheaders/) { get; } | Gets the headers written to the output, in order, as names from [`MhtTemplateName`](../mhttemplatename/). By default: From, Sent, To, Cc, Bcc, Subject, Attachments, Importance and Categories. |
| [ResourceRenderingMode](../../aspose.email/htmlsaveoptions/resourcerenderingmode/) { get; set; } | Gets or sets how attachments and other resources are rendered into the HTML. The default is `ResourceRenderingMode.EmbedIntoHtml`. |
| [Timeout](../../aspose.email/headersformattingoptions/timeout/) { get; set; } | Gets or sets the time limit, in milliseconds, for formatting the message. The default is 3000 (3 seconds). |
| [UseRelativePathToResources](../../aspose.email/htmlsaveoptions/userelativepathtoresources/) { get; set; } | Gets or sets a value indicating whether the HTML refers to resources saved to files by relative paths instead of absolute ones. The default is `false`. |

## Events

| Name | Description |
| --- | --- |
| event [ResourceHtmlRendering](../../aspose.email/headersformattingoptions/resourcehtmlrendering/) | Occurs for each attachment rendered into the HTML; set the properties of the event arguments to supply the content, file or caption to use for it. |
| event [TimeoutReached](../../aspose.email/headersformattingoptions/timeoutreached/) | Occurs when formatting the message takes longer than [`Timeout`](../headersformattingoptions/timeout/). |

## Remarks

Use this class with [`Save`](../mailmessage/save/) to save messages in HTML format. The [`HtmlFormatOptions`](./htmlformatoptions/) property controls HTML formatting options, while [`ResourceRenderingMode`](./resourcerenderingmode/) determines how embedded resources (images, attachments) are handled - either embedded directly in HTML or saved as separate files.

## Examples

This example saves a message to HTML with the headers and with the images in a separate folder.

[C#]

```csharp
var msg = MailMessage.Load("message.eml");

var options = new HtmlSaveOptions
{
    HtmlFormatOptions = HtmlFormatOptions.WriteHeader | HtmlFormatOptions.WriteCompleteEmailAddress,
    // the resources go to the "message_files" folder next to the HTML file
    ResourceRenderingMode = ResourceRenderingMode.SaveToFile,
    UseRelativePathToResources = true
};

msg.Save("message.html", options);
```

[Visual Basic]

```csharp
Dim msg = MailMessage.Load("message.eml")

Dim options = New HtmlSaveOptions With {
    .HtmlFormatOptions = HtmlFormatOptions.WriteHeader Or HtmlFormatOptions.WriteCompleteEmailAddress,
    .ResourceRenderingMode = ResourceRenderingMode.SaveToFile,
    .UseRelativePathToResources = True
}

' the resources go to the "message_files" folder next to the HTML file
msg.Save("message.html", options)
```

### See Also

* class [HeadersFormattingOptions](../headersformattingoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


