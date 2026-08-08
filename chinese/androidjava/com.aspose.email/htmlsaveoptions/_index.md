---
title: HtmlSaveOptions
second_title: Aspose.Email for Android via Java API 参考
description: 允许在将 MailMessage 保存为 Html 格式时指定其他选项。
type: docs
weight: 161
url: /zh/androidjava/com.aspose.email/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions), [com.aspose.email.HeadersFormattingOptions](../../com.aspose.email/headersformattingoptions)
```
public class HtmlSaveOptions extends HeadersFormattingOptions
```

允许在将 MailMessage 保存为 Html 格式时指定其他选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) | 初始化此类的新实例，可用于以 Html 格式保存 MailMessage。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createSaveOptions(MailMessageSaveType saveType)](#createSaveOptions-com.aspose.email.MailMessageSaveType-) | 创建适用于指定保存类型的类的保存选项对象。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAfterHeadersFormat()](#getAfterHeadersFormat--) | 在标题格式之后。 |
| [getBeforeHeadersFormat()](#getBeforeHeadersFormat--) | 在标题格式之前。 |
| [getCheckBodyContentEncoding()](#getCheckBodyContentEncoding--) | 定义在保存时是否需要检查消息正文内容的编码。 |
| [getClass()](#getClass--) |  |
| [getCssStyles()](#getCssStyles--) | 获取或设置格式化程序的附加 CSS 样式。 |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | 表示通常由调用方提供并处理进度事件的方法。 |
| [getDefaultEml()](#getDefaultEml--) | 获取用于将消息保存为 Eml 格式的默认值选项。 |
| [getDefaultHeaderFormat()](#getDefaultHeaderFormat--) | 默认标题行格式。 |
| [getDefaultHtml()](#getDefaultHtml--) | 获取用于将消息保存为 Html 格式的默认值选项。 |
| [getDefaultMhtml()](#getDefaultMhtml--) | 获取用于将消息保存为 Mhtml 格式的默认值选项。 |
| [getDefaultMsg()](#getDefaultMsg--) | 获取用于将消息保存为 Msg（ASCII）格式的默认值选项。 |
| [getDefaultMsgUnicode()](#getDefaultMsgUnicode--) | 获取用于将消息保存为 Msg（Unicode）格式的默认值选项。 |
| [getDefaultPageHeaderFormat()](#getDefaultPageHeaderFormat--) | 默认页面标题格式。 |
| [getEmbedResources()](#getEmbedResources--) | 定义在保存时是否需要在 HTML 内容中嵌入资源。 |
| [getFormatTemplates()](#getFormatTemplates--) | 获取格式模板。 |
| [getHtmlFormatOptions()](#getHtmlFormatOptions--) | 获取或设置以 HTML 格式保存时的附加选项。 |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | 表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。 |
| [getRenderedContactFields()](#getRenderedContactFields--) | 定义将在输出 mhtml 中包含的联系人字段组。 |
| [getRenderingHeaders()](#getRenderingHeaders--) | 获取用于渲染的标题列表。 |
| [getResourceHtmlRenderingHandler()](#getResourceHtmlRenderingHandler--) | 提供在 HTML 中自定义渲染资源的功能。 |
| [getResourceRenderingMode()](#getResourceRenderingMode--) | 提供设置在 HTML 中渲染资源的各种模式。 |
| [getSaveResourceHandler()](#getSaveResourceHandler--) | 如果 EmbedResources 为 false，则调用此处理程序来保存所有消息附件。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAfterHeadersFormat(String value)](#setAfterHeadersFormat-java.lang.String-) | 在标题格式之后。 |
| [setBeforeHeadersFormat(String value)](#setBeforeHeadersFormat-java.lang.String-) | 在标题格式之前。 |
| [setCheckBodyContentEncoding(boolean value)](#setCheckBodyContentEncoding-boolean-) | 定义在保存时是否需要检查消息正文内容的编码。 |
| [setCssStyles(String value)](#setCssStyles-java.lang.String-) | 获取或设置格式化程序的附加 CSS 样式。 |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | 表示通常由调用方提供并处理进度事件的方法。 |
| [setDefaultHeaderFormat(String value)](#setDefaultHeaderFormat-java.lang.String-) | 默认标题行格式。 |
| [setDefaultPageHeaderFormat(String value)](#setDefaultPageHeaderFormat-java.lang.String-) | 默认页面标题格式。 |
| [setEmbedResources(boolean value)](#setEmbedResources-boolean-) | 定义在保存时是否需要在 HTML 内容中嵌入资源。 |
| [setHtmlFormatOptions(int value)](#setHtmlFormatOptions-int-) | 获取或设置以 HTML 格式保存时的附加选项。 |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | 表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。 |
| [setRenderedContactFields(int value)](#setRenderedContactFields-int-) | 定义将在输出 mhtml 中包含的联系人字段组。 |
| [setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value)](#setResourceHtmlRenderingHandler-com.aspose.email.ResourceHtmlRenderingHandler-) | 提供在 HTML 中自定义渲染资源的功能。 |
| [setResourceRenderingMode(int value)](#setResourceRenderingMode-int-) | 提供设置在 HTML 中渲染资源的各种模式。 |
| [setSaveResourceHandler(SaveResourceHandler value)](#setSaveResourceHandler-com.aspose.email.SaveResourceHandler-) | 如果 EmbedResources 为 false，则调用此处理程序来保存所有消息附件。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


初始化此类的新实例，可用于以 Html 格式保存 MailMessage。

### createSaveOptions(MailMessageSaveType saveType) {#createSaveOptions-com.aspose.email.MailMessageSaveType-}
```
public static SaveOptions createSaveOptions(MailMessageSaveType saveType)
```


创建适用于指定保存类型的类的保存选项对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| saveType | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) | 用于创建保存选项对象的 MailMessageSaveType 保存类型（\\#getMailMessageSaveType.getMailMessageSaveType/\\#setMailMessageSaveType(MailMessageSaveType).setMailMessageSaveType(MailMessageSaveType)）。 |

**Returns:**
[SaveOptions](../../com.aspose.email/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.email/saveoptions).
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAfterHeadersFormat() {#getAfterHeadersFormat--}
```
public final String getAfterHeadersFormat()
```


在标题格式之后。

值：要注入到生成的 html 正文中的样式。

**Returns:**
java.lang.String
### getBeforeHeadersFormat() {#getBeforeHeadersFormat--}
```
public final String getBeforeHeadersFormat()
```


在标题格式之前。

值：要注入到生成的 html 正文中的样式。

**Returns:**
java.lang.String
### getCheckBodyContentEncoding() {#getCheckBodyContentEncoding--}
```
public final boolean getCheckBodyContentEncoding()
```


定义在保存时是否需要检查消息正文内容的编码。默认值为 false。

--------------------

如果为 true，则会检查 MailMessage.HtmlBody（[MailMessage.getHtmlBody](../../com.aspose.email/mailmessage\\#getHtmlBody)/[MailMessage.setHtmlBody(String)](../../com.aspose.email/mailmessage\\#setHtmlBody-String-)）的内容编码是否与 MailMessage.BodyEncoding（[MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\\#setBodyEncoding-Encoding-)）属性指定的编码匹配。如果 HtmlBody 的内容编码与 BodyEncoding 属性不匹配，则 MailMessage.BodyEncoding（[MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\\#setBodyEncoding-Encoding-)）和 MailMessage.PreferredTextEncoding（[MailMessage.getPreferredTextEncoding](../../com.aspose.email/mailmessage\\#getPreferredTextEncoding)/[MailMessage.setPreferredTextEncoding(Encoding)](../../com.aspose.email/mailmessage\\#setPreferredTextEncoding-Encoding-)）属性将被更改为默认的 System.Text.Encoding.UTF8（java.nio.charset.Charset\\#getUTF8.getUTF8）。

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCssStyles() {#getCssStyles--}
```
public final String getCssStyles()
```


获取或设置格式化程序的附加 CSS 样式。

值：要注入到生成的 html 正文中的样式。

**Returns:**
java.lang.String
### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public final ConversionProgressEventHandler getCustomProgressHandler()
```


表示通常由调用方提供并处理进度事件的方法。

**Returns:**
[ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler)
### getDefaultEml() {#getDefaultEml--}
```
public static EmlSaveOptions getDefaultEml()
```


获取用于将消息保存为 Eml 格式的默认值选项。

**Returns:**
[EmlSaveOptions](../../com.aspose.email/emlsaveoptions)
### getDefaultHeaderFormat() {#getDefaultHeaderFormat--}
```
public final String getDefaultHeaderFormat()
```


默认标题行格式。

值：要注入到生成的 html 正文中的样式。

**Returns:**
java.lang.String
### getDefaultHtml() {#getDefaultHtml--}
```
public static HtmlSaveOptions getDefaultHtml()
```


获取用于将消息保存为 Html 格式的默认值选项。

**Returns:**
[HtmlSaveOptions](../../com.aspose.email/htmlsaveoptions)
### getDefaultMhtml() {#getDefaultMhtml--}
```
public static MhtSaveOptions getDefaultMhtml()
```


获取用于将消息保存为 Mhtml 格式的默认值选项。

**Returns:**
[MhtSaveOptions](../../com.aspose.email/mhtsaveoptions)
### getDefaultMsg() {#getDefaultMsg--}
```
public static MsgSaveOptions getDefaultMsg()
```


获取用于将消息保存为 Msg（ASCII）格式的默认值选项。

**Returns:**
[MsgSaveOptions](../../com.aspose.email/msgsaveoptions)
### getDefaultMsgUnicode() {#getDefaultMsgUnicode--}
```
public static MsgSaveOptions getDefaultMsgUnicode()
```


获取用于将消息保存为 Msg（Unicode）格式的默认值选项。

**Returns:**
[MsgSaveOptions](../../com.aspose.email/msgsaveoptions)
### getDefaultPageHeaderFormat() {#getDefaultPageHeaderFormat--}
```
public final String getDefaultPageHeaderFormat()
```


默认页面标题格式。

值：要注入到生成的 html 正文中的样式。

**Returns:**
java.lang.String
### getEmbedResources() {#getEmbedResources--}
```
public final boolean getEmbedResources()
```


定义在保存时是否需要在 html 内容中嵌入资源。默认值为 true。

**Returns:**
boolean
### getFormatTemplates() {#getFormatTemplates--}
```
public final System.Collections.Specialized.StringDictionary getFormatTemplates()
```


获取格式模板。

值：格式模板。

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringDictionary
### getHtmlFormatOptions() {#getHtmlFormatOptions--}
```
public final int getHtmlFormatOptions()
```


获取或设置以 HTML 格式保存时的其他选项。默认值为 HtmlFormatOptions.None。

**Returns:**
int
### getMailMessageSaveType() {#getMailMessageSaveType--}
```
public final MailMessageSaveType getMailMessageSaveType()
```


表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。默认值为 Eml。

**Returns:**
[MailMessageSaveType](../../com.aspose.email/mailmessagesavetype)
### getRenderedContactFields() {#getRenderedContactFields--}
```
public final int getRenderedContactFields()
```


定义将在输出 mhtml 中包含的联系人字段组。默认值为 ContactFieldsSet.AllExisting。

**Returns:**
int
### getRenderingHeaders() {#getRenderingHeaders--}
```
public final List<String> getRenderingHeaders()
```


获取用于渲染的标题列表。

**Returns:**
java.util.List<java.lang.String>
### getResourceHtmlRenderingHandler() {#getResourceHtmlRenderingHandler--}
```
public final ResourceHtmlRenderingHandler getResourceHtmlRenderingHandler()
```


提供在 HTML 中自定义渲染资源的功能。

**Returns:**
[ResourceHtmlRenderingHandler](../../com.aspose.email/resourcehtmlrenderinghandler)
### getResourceRenderingMode() {#getResourceRenderingMode--}
```
public final int getResourceRenderingMode()
```


提供设置在 html 中渲染资源的各种模式。默认值为 EmbedIntoHtml。

**Returns:**
int
### getSaveResourceHandler() {#getSaveResourceHandler--}
```
public final SaveResourceHandler getSaveResourceHandler()
```


如果 EmbedResources 为 false，则调用此处理程序来保存所有消息附件。

**Returns:**
[SaveResourceHandler](../../com.aspose.email/saveresourcehandler)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAfterHeadersFormat(String value) {#setAfterHeadersFormat-java.lang.String-}
```
public final void setAfterHeadersFormat(String value)
```


在标题格式之后。

值：要注入到生成的 html 正文中的样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setBeforeHeadersFormat(String value) {#setBeforeHeadersFormat-java.lang.String-}
```
public final void setBeforeHeadersFormat(String value)
```


在标题格式之前。

值：要注入到生成的 html 正文中的样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCheckBodyContentEncoding(boolean value) {#setCheckBodyContentEncoding-boolean-}
```
public final void setCheckBodyContentEncoding(boolean value)
```


定义在保存时是否需要检查消息正文内容的编码。默认值为 false。

--------------------

如果为 true，则会检查 MailMessage.HtmlBody（[MailMessage.getHtmlBody](../../com.aspose.email/mailmessage\\#getHtmlBody)/[MailMessage.setHtmlBody(String)](../../com.aspose.email/mailmessage\\#setHtmlBody-String-)）的内容编码是否与 MailMessage.BodyEncoding（[MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\\#setBodyEncoding-Encoding-)）属性指定的编码匹配。如果 HtmlBody 的内容编码与 BodyEncoding 属性不匹配，则 MailMessage.BodyEncoding（[MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\\#setBodyEncoding-Encoding-)）和 MailMessage.PreferredTextEncoding（[MailMessage.getPreferredTextEncoding](../../com.aspose.email/mailmessage\\#getPreferredTextEncoding)/[MailMessage.setPreferredTextEncoding(Encoding)](../../com.aspose.email/mailmessage\\#setPreferredTextEncoding-Encoding-)）属性将被更改为默认的 System.Text.Encoding.UTF8（java.nio.charset.Charset\\#getUTF8.getUTF8）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setCssStyles(String value) {#setCssStyles-java.lang.String-}
```
public final void setCssStyles(String value)
```


获取或设置格式化程序的附加 CSS 样式。

值：要注入到生成的 html 正文中的样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCustomProgressHandler(ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(ConversionProgressEventHandler value)
```


表示通常由调用方提供并处理进度事件的方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setDefaultHeaderFormat(String value) {#setDefaultHeaderFormat-java.lang.String-}
```
public final void setDefaultHeaderFormat(String value)
```


默认标题行格式。

值：要注入到生成的 html 正文中的样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setDefaultPageHeaderFormat(String value) {#setDefaultPageHeaderFormat-java.lang.String-}
```
public final void setDefaultPageHeaderFormat(String value)
```


默认页面标题格式。

值：要注入到生成的 html 正文中的样式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setEmbedResources(boolean value) {#setEmbedResources-boolean-}
```
public final void setEmbedResources(boolean value)
```


定义在保存时是否需要在 html 内容中嵌入资源。默认值为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setHtmlFormatOptions(int value) {#setHtmlFormatOptions-int-}
```
public final void setHtmlFormatOptions(int value)
```


获取或设置以 HTML 格式保存时的其他选项。默认值为 HtmlFormatOptions.None。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setMailMessageSaveType(MailMessageSaveType value) {#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-}
```
public final void setMailMessageSaveType(MailMessageSaveType value)
```


表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。默认值为 Eml。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### setRenderedContactFields(int value) {#setRenderedContactFields-int-}
```
public final void setRenderedContactFields(int value)
```


定义将在输出 mhtml 中包含的联系人字段组。默认值为 ContactFieldsSet.AllExisting。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value) {#setResourceHtmlRenderingHandler-com.aspose.email.ResourceHtmlRenderingHandler-}
```
public final void setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value)
```


提供在 HTML 中自定义渲染资源的功能。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ResourceHtmlRenderingHandler](../../com.aspose.email/resourcehtmlrenderinghandler) |  |

### setResourceRenderingMode(int value) {#setResourceRenderingMode-int-}
```
public final void setResourceRenderingMode(int value)
```


提供设置在 html 中渲染资源的各种模式。默认值为 EmbedIntoHtml。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setSaveResourceHandler(SaveResourceHandler value) {#setSaveResourceHandler-com.aspose.email.SaveResourceHandler-}
```
public final void setSaveResourceHandler(SaveResourceHandler value)
```


如果 EmbedResources 为 false，则调用此处理程序来保存所有消息附件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SaveResourceHandler](../../com.aspose.email/saveresourcehandler) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

