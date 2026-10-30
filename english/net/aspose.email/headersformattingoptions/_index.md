---
title: Class HeadersFormattingOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.HeadersFormattingOptions class. The base class of the options for saving a message to HTML or MHTML how the headers are formatted which are shown and how embedded resources are rendered
type: docs
weight: 16270
url: /net/aspose.email/headersformattingoptions/
---
## HeadersFormattingOptions class

The base class of the options for saving a message to HTML or MHTML: how the headers are formatted, which are shown, and how embedded resources are rendered.

```csharp
public abstract class HeadersFormattingOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HeadersFormattingOptions](headersformattingoptions/)() | Initializes a new instance of the `HeadersFormattingOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [AfterHeadersFormat](../../aspose.email/headersformattingoptions/afterheadersformat/) { get; set; } | Gets or sets the HTML written after the block of headers. |
| [BeforeHeadersFormat](../../aspose.email/headersformattingoptions/beforeheadersformat/) { get; set; } | Gets or sets the HTML written before the block of headers. |
| [CssStyles](../../aspose.email/headersformattingoptions/cssstyles/) { get; set; } | Gets or sets additional CSS styles added to the output. |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler/) { get; set; } | Gets or sets a handler that is called as the saving progresses. |
| [DefaultHeaderFormat](../../aspose.email/headersformattingoptions/defaultheaderformat/) { get; set; } | Gets or sets the HTML format of a header line, from which the template of each header in [`FormatTemplates`](./formattemplates/) is built; `{0}` stands for the name of the header. |
| [DefaultPageHeaderFormat](../../aspose.email/headersformattingoptions/defaultpageheaderformat/) { get; set; } | Gets or sets the HTML format of the page header. |
| [ExtractHTMLBodyResourcesAsAttachments](../../aspose.email/headersformattingoptions/extracthtmlbodyresourcesasattachments/) { get; set; } | Gets or sets a value indicating whether the resources of the HTML body, such as images, are also written as attachments. The default is `false`. |
| [FormatTemplates](../../aspose.email/headersformattingoptions/formattemplates/) { get; } | Gets the formats of individual headers, keyed by the names in [`MhtTemplateName`](../mhttemplatename/). |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype/) { get; set; } | Gets or sets the format the options save to. |
| [RenderedContactFields](../../aspose.email/headersformattingoptions/renderedcontactfields/) { get; set; } | Gets or sets the groups of contact fields written for a contact. The default is `ContactFieldsSet.AllExisting`. |
| [RenderingHeaders](../../aspose.email/headersformattingoptions/renderingheaders/) { get; } | Gets the headers written to the output, in order, as names from [`MhtTemplateName`](../mhttemplatename/). By default: From, Sent, To, Cc, Bcc, Subject, Attachments, Importance and Categories. |
| [Timeout](../../aspose.email/headersformattingoptions/timeout/) { get; set; } | Gets or sets the time limit, in milliseconds, for formatting the message. The default is 3000 (3 seconds). |

## Events

| Name | Description |
| --- | --- |
| event [ResourceHtmlRendering](../../aspose.email/headersformattingoptions/resourcehtmlrendering/) | Occurs for each attachment rendered into the HTML; set the properties of the event arguments to supply the content, file or caption to use for it. |
| event [TimeoutReached](../../aspose.email/headersformattingoptions/timeoutreached/) | Occurs when formatting the message takes longer than [`Timeout`](./timeout/). |

## Remarks

Use [`HtmlSaveOptions`](../htmlsaveoptions/) or [`MhtSaveOptions`](../mhtsaveoptions/).

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


