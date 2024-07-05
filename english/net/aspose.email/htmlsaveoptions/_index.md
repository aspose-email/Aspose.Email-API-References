---
title: Class HtmlSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.HtmlSaveOptions class. Allows to specify additional options when saving MailMessage to Html format
type: docs
weight: 17650
url: /net/aspose.email/htmlsaveoptions/
---
## HtmlSaveOptions class

Allows to specify additional options when saving MailMessage to Html format.

```csharp
public class HtmlSaveOptions : HeadersFormattingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/)() | Initializes a new instance of this class that can be used to save a MailMessage in the Html format. |

## Properties

| Name | Description |
| --- | --- |
| [AfterHeadersFormat](../../aspose.email/headersformattingoptions/afterheadersformat/) { get; set; } | After headers format. |
| [BeforeHeadersFormat](../../aspose.email/headersformattingoptions/beforeheadersformat/) { get; set; } | Before headers format. |
| [CheckBodyContentEncoding](../../aspose.email/htmlsaveoptions/checkbodycontentencoding/) { get; set; } | Defines whether need check message body content encoding when saving. By default the value is false. |
| [CssStyles](../../aspose.email/headersformattingoptions/cssstyles/) { get; set; } | Gets or sets the additional css styles for the formatter. |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler/) { get; set; } | Represents method that usually supplied by calling side and handles progress events. |
| [DefaultHeaderFormat](../../aspose.email/headersformattingoptions/defaultheaderformat/) { get; set; } | Default header line format. |
| [DefaultPageHeaderFormat](../../aspose.email/headersformattingoptions/defaultpageheaderformat/) { get; set; } | Default page header format. |
| [FormatTemplates](../../aspose.email/headersformattingoptions/formattemplates/) { get; } | Gets the format templates. |
| [HtmlFormatOptions](../../aspose.email/htmlsaveoptions/htmlformatoptions/) { get; set; } | Gets or sets additional options when saving in HTML format. Default value is HtmlFormatOptions.None. |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype/) { get; set; } | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. The default value is Eml. |
| [RenderedContactFields](../../aspose.email/headersformattingoptions/renderedcontactfields/) { get; set; } | Defines groups of Contact fields which will be included in output mhtml. Default value is ContactFieldsSet.AllExisting. |
| [RenderingHeaders](../../aspose.email/headersformattingoptions/renderingheaders/) { get; } | Gets list of headers for rendering. |
| [ResourceRenderingMode](../../aspose.email/htmlsaveoptions/resourcerenderingmode/) { get; set; } | Provides set various modes of rendering resources in html. Default value EmbedIntoHtml. |
| [UseRelativePathToResources](../../aspose.email/htmlsaveoptions/userelativepathtoresources/) { get; set; } | Default value is false. |

## Events

| Name | Description |
| --- | --- |
| event [ResourceHtmlRendering](../../aspose.email/htmlsaveoptions/resourcehtmlrendering/) | Provides customization of rendering resources in html. |

### See Also

* class [HeadersFormattingOptions](../headersformattingoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


