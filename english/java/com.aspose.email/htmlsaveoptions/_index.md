---
title: HtmlSaveOptions
second_title: Aspose.Email for Java API Reference
description:  Allows to specify additional options when saving MailMessage to Html format.
type: docs
weight: 294
url: /java/com.aspose.email/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions), [com.aspose.email.HeadersFormattingOptions](../../com.aspose.email/headersformattingoptions)
```
public class HtmlSaveOptions extends HeadersFormattingOptions
```

Allows to specify additional options when saving MailMessage to Html format.
## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) | Initializes a new instance of this class that can be used to save a MailMessage in the Html format. |
## Methods

| Method | Description |
| --- | --- |
| [getEmbedResources()](#getEmbedResources--) | Defines whether need embed resources in html content when saving or not. |
| [setEmbedResources(boolean value)](#setEmbedResources-boolean-) | Defines whether need embed resources in html content when saving or not. |
| [getHtmlFormatOptions()](#getHtmlFormatOptions--) | Gets or sets additional options when saving in HTML format. |
| [setHtmlFormatOptions(int value)](#setHtmlFormatOptions-int-) | Gets or sets additional options when saving in HTML format. |
| [getCheckBodyContentEncoding()](#getCheckBodyContentEncoding--) | Defines whether need check message body content encoding when saving. |
| [setCheckBodyContentEncoding(boolean value)](#setCheckBodyContentEncoding-boolean-) | Defines whether need check message body content encoding when saving. |
| [getSaveResourceHandler()](#getSaveResourceHandler--) | This handler is called for saving all message attachments if EmbedResources is false. |
| [setSaveResourceHandler(SaveResourceHandler value)](#setSaveResourceHandler-com.aspose.email.SaveResourceHandler-) | This handler is called for saving all message attachments if EmbedResources is false. |
| [getResourceHtmlRenderingHandler()](#getResourceHtmlRenderingHandler--) | Provides customization of rendering resources in html. |
| [setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value)](#setResourceHtmlRenderingHandler-com.aspose.email.ResourceHtmlRenderingHandler-) | Provides customization of rendering resources in html. |
| [getResourceRenderingMode()](#getResourceRenderingMode--) | Provides set various modes of rendering resources in html. |
| [setResourceRenderingMode(int value)](#setResourceRenderingMode-int-) | Provides set various modes of rendering resources in html. |
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


Initializes a new instance of this class that can be used to save a MailMessage in the Html format.

### getEmbedResources() {#getEmbedResources--}
```
public final boolean getEmbedResources()
```


Defines whether need embed resources in html content when saving or not. Default value is true.

**Returns:**
boolean
### setEmbedResources(boolean value) {#setEmbedResources-boolean-}
```
public final void setEmbedResources(boolean value)
```


Defines whether need embed resources in html content when saving or not. Default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatOptions() {#getHtmlFormatOptions--}
```
public final int getHtmlFormatOptions()
```


Gets or sets additional options when saving in HTML format. Default value is HtmlFormatOptions.None.

**Returns:**
int
### setHtmlFormatOptions(int value) {#setHtmlFormatOptions-int-}
```
public final void setHtmlFormatOptions(int value)
```


Gets or sets additional options when saving in HTML format. Default value is HtmlFormatOptions.None.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCheckBodyContentEncoding() {#getCheckBodyContentEncoding--}
```
public final boolean getCheckBodyContentEncoding()
```


Defines whether need check message body content encoding when saving. By default the value is false.

--------------------

If true, it will be check whether the \`\`\` MailMessage.HtmlBody \`\`\`([MailMessage\#getHtmlBody](../../com.aspose.email/mailmessage\#getHtmlBody)/[MailMessage\#setHtmlBody(String)](../../com.aspose.email/mailmessage\#setHtmlBody-String-)) content encoding matches to the encoding specified by the \`\`\` MailMessage.BodyEncoding \`\`\`([MailMessage\#getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage\#setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) property. If the HtmlBody content encoding doesn't match BodyEncoding property, the \`\`\` MailMessage.BodyEncoding \`\`\`([MailMessage\#getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage\#setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) and \`\`\` MailMessage.PreferredTextEncoding \`\`\`([MailMessage\#getPreferredTextEncoding](../../com.aspose.email/mailmessage\#getPreferredTextEncoding)/[MailMessage\#setPreferredTextEncoding(Encoding)](../../com.aspose.email/mailmessage\#setPreferredTextEncoding-Encoding-)) properties will be changed to default \`\`\` System.Text.Encoding.UTF8 \`\`\`(java.nio.charset.Charset\#getUTF8).

**Returns:**
boolean
### setCheckBodyContentEncoding(boolean value) {#setCheckBodyContentEncoding-boolean-}
```
public final void setCheckBodyContentEncoding(boolean value)
```


Defines whether need check message body content encoding when saving. By default the value is false.

--------------------

If true, it will be check whether the \`\`\` MailMessage.HtmlBody \`\`\`([MailMessage\#getHtmlBody](../../com.aspose.email/mailmessage\#getHtmlBody)/[MailMessage\#setHtmlBody(String)](../../com.aspose.email/mailmessage\#setHtmlBody-String-)) content encoding matches to the encoding specified by the \`\`\` MailMessage.BodyEncoding \`\`\`([MailMessage\#getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage\#setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) property. If the HtmlBody content encoding doesn't match BodyEncoding property, the \`\`\` MailMessage.BodyEncoding \`\`\`([MailMessage\#getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage\#setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) and \`\`\` MailMessage.PreferredTextEncoding \`\`\`([MailMessage\#getPreferredTextEncoding](../../com.aspose.email/mailmessage\#getPreferredTextEncoding)/[MailMessage\#setPreferredTextEncoding(Encoding)](../../com.aspose.email/mailmessage\#setPreferredTextEncoding-Encoding-)) properties will be changed to default \`\`\` System.Text.Encoding.UTF8 \`\`\`(java.nio.charset.Charset\#getUTF8).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSaveResourceHandler() {#getSaveResourceHandler--}
```
public final SaveResourceHandler getSaveResourceHandler()
```


This handler is called for saving all message attachments if EmbedResources is false.

**Returns:**
[SaveResourceHandler](../../com.aspose.email/saveresourcehandler)
### setSaveResourceHandler(SaveResourceHandler value) {#setSaveResourceHandler-com.aspose.email.SaveResourceHandler-}
```
public final void setSaveResourceHandler(SaveResourceHandler value)
```


This handler is called for saving all message attachments if EmbedResources is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SaveResourceHandler](../../com.aspose.email/saveresourcehandler) |  |

### getResourceHtmlRenderingHandler() {#getResourceHtmlRenderingHandler--}
```
public final ResourceHtmlRenderingHandler getResourceHtmlRenderingHandler()
```


Provides customization of rendering resources in html.

**Returns:**
[ResourceHtmlRenderingHandler](../../com.aspose.email/resourcehtmlrenderinghandler)
### setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value) {#setResourceHtmlRenderingHandler-com.aspose.email.ResourceHtmlRenderingHandler-}
```
public final void setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value)
```


Provides customization of rendering resources in html.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ResourceHtmlRenderingHandler](../../com.aspose.email/resourcehtmlrenderinghandler) |  |

### getResourceRenderingMode() {#getResourceRenderingMode--}
```
public final int getResourceRenderingMode()
```


Provides set various modes of rendering resources in html. Default value EmbedIntoHtml.

**Returns:**
int
### setResourceRenderingMode(int value) {#setResourceRenderingMode-int-}
```
public final void setResourceRenderingMode(int value)
```


Provides set various modes of rendering resources in html. Default value EmbedIntoHtml.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

