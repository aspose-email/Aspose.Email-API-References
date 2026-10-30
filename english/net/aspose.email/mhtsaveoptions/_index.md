---
title: Class MhtSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.MhtSaveOptions class. Provides options for controlling how MailMessage instances are saved to MHTML format. This class allows you to customize MHTML output formatting attachment handling header preservation and resource rendering behavior when converting email messages to MHTML MIME HTML files
type: docs
weight: 17960
url: /net/aspose.email/mhtsaveoptions/
---
## MhtSaveOptions class

Provides options for controlling how [`MailMessage`](../mailmessage/) instances are saved to MHTML format. This class allows you to customize MHTML output formatting, attachment handling, header preservation, and resource rendering behavior when converting email messages to MHTML (MIME HTML) files.

```csharp
public class MhtSaveOptions : HeadersFormattingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MhtSaveOptions](mhtsaveoptions/)() | Initializes a new instance of the `MhtSaveOptions` class with the default options. |

## Properties

| Name | Description |
| --- | --- |
| [AfterHeadersFormat](../../aspose.email/headersformattingoptions/afterheadersformat/) { get; set; } | Gets or sets the HTML written after the block of headers. |
| [BeforeHeadersFormat](../../aspose.email/headersformattingoptions/beforeheadersformat/) { get; set; } | Gets or sets the HTML written before the block of headers. |
| [CheckBodyContentEncoding](../../aspose.email/mhtsaveoptions/checkbodycontentencoding/) { get; set; } | Gets or sets a value indicating whether the encoding of the HTML body is checked before saving. The default is `false`. |
| [CssStyles](../../aspose.email/headersformattingoptions/cssstyles/) { get; set; } | Gets or sets additional CSS styles added to the output. |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler/) { get; set; } | Gets or sets a handler that is called as the saving progresses. |
| [DefaultHeaderFormat](../../aspose.email/headersformattingoptions/defaultheaderformat/) { get; set; } | Gets or sets the HTML format of a header line, from which the template of each header in [`FormatTemplates`](../headersformattingoptions/formattemplates/) is built; `{0}` stands for the name of the header. |
| [DefaultPageHeaderFormat](../../aspose.email/headersformattingoptions/defaultpageheaderformat/) { get; set; } | Gets or sets the HTML format of the page header. |
| [ExtractHTMLBodyResourcesAsAttachments](../../aspose.email/headersformattingoptions/extracthtmlbodyresourcesasattachments/) { get; set; } | Gets or sets a value indicating whether the resources of the HTML body, such as images, are also written as attachments. The default is `false`. |
| [FormatTemplates](../../aspose.email/headersformattingoptions/formattemplates/) { get; } | Gets the formats of individual headers, keyed by the names in [`MhtTemplateName`](../mhttemplatename/). |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype/) { get; set; } | Gets or sets the format the options save to. |
| [MhtFormatOptions](../../aspose.email/mhtsaveoptions/mhtformatoptions/) { get; set; } | Gets or sets options for the MHTML output. The default is `MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments`. |
| [PreserveOriginalBoundaries](../../aspose.email/mhtsaveoptions/preserveoriginalboundaries/) { get; set; } | Gets or sets a value indicating whether the MIME boundaries of the original message are kept. The default is `false`. |
| [PreserveOriginalDate](../../aspose.email/mhtsaveoptions/preserveoriginaldate/) { get; set; } | Gets or sets a value indicating whether the original date of the message is kept. The default is `true`. |
| [RenderedContactFields](../../aspose.email/headersformattingoptions/renderedcontactfields/) { get; set; } | Gets or sets the groups of contact fields written for a contact. The default is `ContactFieldsSet.AllExisting`. |
| [RenderingHeaders](../../aspose.email/headersformattingoptions/renderingheaders/) { get; } | Gets the headers written to the output, in order, as names from [`MhtTemplateName`](../mhttemplatename/). By default: From, Sent, To, Cc, Bcc, Subject, Attachments, Importance and Categories. |
| [SaveAllHeaders](../../aspose.email/mhtsaveoptions/saveallheaders/) { get; set; } | Gets or sets a value indicating whether all headers of the message are written to the output. The default is `false`. |
| [SaveAttachments](../../aspose.email/mhtsaveoptions/saveattachments/) { get; set; } | Gets or sets a value indicating whether the attachments are saved into the MHTML file. |
| [SavedHeaders](../../aspose.email/mhtsaveoptions/savedheaders/) { get; } | Gets the headers of the message that are kept in the MIME headers of the MHTML file; the others are dropped. The list is empty by default. |
| [SkipInlineImages](../../aspose.email/mhtsaveoptions/skipinlineimages/) { get; set; } | Gets or sets a value indicating whether inline images are left out of the output. The default is `false`. |
| [Timeout](../../aspose.email/headersformattingoptions/timeout/) { get; set; } | Gets or sets the time limit, in milliseconds, for formatting the message. The default is 3000 (3 seconds). |

## Events

| Name | Description |
| --- | --- |
| event [ResourceHtmlRendering](../../aspose.email/headersformattingoptions/resourcehtmlrendering/) | Occurs for each attachment rendered into the HTML; set the properties of the event arguments to supply the content, file or caption to use for it. |
| event [TimeoutReached](../../aspose.email/headersformattingoptions/timeoutreached/) | Occurs when formatting the message takes longer than [`Timeout`](../headersformattingoptions/timeout/). |

## Remarks

Use this class with [`Save`](../mailmessage/save/) to save messages in MHTML format. MHTML is a web page archive format that combines HTML content and embedded resources into a single file. The [`MhtFormatOptions`](./mhtformatoptions/) property controls formatting options, [`SaveAttachments`](./saveattachments/) determines whether attachments are included, and [`SavedHeaders`](./savedheaders/) allows you to specify custom headers to include in the output.

## Examples

The following example shows how to save MailMessage as MHTML.

[C#]

```csharp
var eml = MailMessage.Load("Message.eml");
eml.Save("target.mthml", SaveOptions.DefaultMhtml);
```

[Visual Basic]

```csharp
Dim eml = MailMessage.Load("Message.eml")
eml.Save("target.mthml", SaveOptions.DefaultMhtml)
```

### See Also

* class [HeadersFormattingOptions](../headersformattingoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


