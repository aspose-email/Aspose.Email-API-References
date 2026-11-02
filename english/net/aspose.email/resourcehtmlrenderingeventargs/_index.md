---
title: Class ResourceHtmlRenderingEventArgs
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.ResourceHtmlRenderingEventArgs class. Provides data for the ResourceHtmlRendering event what to render for an attachment in the HTML
type: docs
weight: 18780
url: /net/aspose.email/resourcehtmlrenderingeventargs/
---
## ResourceHtmlRenderingEventArgs class

Provides data for the [`ResourceHtmlRendering`](../headersformattingoptions/resourcehtmlrendering/) event: what to render for an attachment in the HTML.

```csharp
public class ResourceHtmlRenderingEventArgs : EventArgs
```

## Constructors

| Name | Description |
| --- | --- |
| [ResourceHtmlRenderingEventArgs](resourcehtmlrenderingeventargs/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Caption](../../aspose.email/resourcehtmlrenderingeventargs/caption/) { get; set; } | Gets or sets the caption shown for the resource. |
| [Exception](../../aspose.email/resourcehtmlrenderingeventargs/exception/) { get; set; } | Gets or sets the exception that occurred while rendering the resource. |
| [PathToResourceFile](../../aspose.email/resourcehtmlrenderingeventargs/pathtoresourcefile/) { get; set; } | Gets or sets the path of the file to use for the resource, with `ResourceRenderingMode.SaveToFile` or `ResourceRenderingMode.SubstituteFromFile`. |
| [ResourceStream](../../aspose.email/resourcehtmlrenderingeventargs/resourcestream/) { get; set; } | Gets or sets the content to embed for the resource, with `ResourceRenderingMode.EmbedIntoHtml`; it has no effect in the other modes. |

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


