---
title: Class HeadersFormattingOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.HeadersFormattingOptions class. Serves as the abstract base class for formatspecific options when saving MailMessage to HTMLbased formats MHTML HTML. This class provides configuration properties for controlling header formatting CSS styles timeout settings and resource rendering behavior
type: docs
weight: 16270
url: /net/aspose.email/headersformattingoptions/
---
## HeadersFormattingOptions class

Serves as the abstract base class for format-specific options when saving [`MailMessage`](../mailmessage/) to HTML-based formats (MHTML, HTML). This class provides configuration properties for controlling header formatting, CSS styles, timeout settings, and resource rendering behavior.

```csharp
public abstract class HeadersFormattingOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HeadersFormattingOptions](headersformattingoptions/)() | Initializes a new instance of this class that can be used to save a MailMessage in the Mhtml format. |

## Properties

| Name | Description |
| --- | --- |
| [AfterHeadersFormat](../../aspose.email/headersformattingoptions/afterheadersformat/) { get; set; } | After headers format. |
| [BeforeHeadersFormat](../../aspose.email/headersformattingoptions/beforeheadersformat/) { get; set; } | Before headers format. |
| [CssStyles](../../aspose.email/headersformattingoptions/cssstyles/) { get; set; } | Gets or sets the additional css styles for the formatter. |
| [CustomProgressHandler](../../aspose.email/saveoptions/customprogresshandler/) { get; set; } | Represents method that usually supplied by calling side and handles progress events. |
| [DefaultHeaderFormat](../../aspose.email/headersformattingoptions/defaultheaderformat/) { get; set; } | Default header line format. |
| [DefaultPageHeaderFormat](../../aspose.email/headersformattingoptions/defaultpageheaderformat/) { get; set; } | Default page header format. |
| [ExtractHTMLBodyResourcesAsAttachments](../../aspose.email/headersformattingoptions/extracthtmlbodyresourcesasattachments/) { get; set; } | Defines whether extract HTML body resources as attachments or not. Default value is false. |
| [FormatTemplates](../../aspose.email/headersformattingoptions/formattemplates/) { get; } | Gets the format templates. |
| [MailMessageSaveType](../../aspose.email/saveoptions/mailmessagesavetype/) { get; set; } | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. The default value is Eml. |
| [RenderedContactFields](../../aspose.email/headersformattingoptions/renderedcontactfields/) { get; set; } | Defines groups of Contact fields which will be included in output mhtml. Default value is ContactFieldsSet.AllExisting. |
| [RenderingHeaders](../../aspose.email/headersformattingoptions/renderingheaders/) { get; } | Gets list of headers for rendering. |
| [Timeout](../../aspose.email/headersformattingoptions/timeout/) { get; set; } | Limits the time in milliseconds of formatting message while saving in Mht. Default value 3 sec. |

## Events

| Name | Description |
| --- | --- |
| event [ResourceHtmlRendering](../../aspose.email/headersformattingoptions/resourcehtmlrendering/) | Provides customization of rendering resources in html. |
| event [TimeoutReached](../../aspose.email/headersformattingoptions/timeoutreached/) | Raised if timed out while saving to Mhtml. |

## Remarks

This class is designed to be inherited by concrete format-specific classes like [`HtmlSaveOptions`](../htmlsaveoptions/) and [`MhtSaveOptions`](../mhtsaveoptions/). Do not instantiate this class directly. Use the format-specific subclasses to access format-specific saving options. The class provides extensive customization for email header presentation, CSS styling, and resource extraction behavior.

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


