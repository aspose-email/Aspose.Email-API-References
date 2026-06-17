---
title: MhtSaveOptions
second_title: Aspose.Email for Android via Java API 参考
description: 允许在将 MailMessage 保存为 Mhtml 格式时指定其他选项。
type: docs
weight: 321
url: /zh/androidjava/com.aspose.email/mhtsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions), [com.aspose.email.HeadersFormattingOptions](../../com.aspose.email/headersformattingoptions)
```
public class MhtSaveOptions extends HeadersFormattingOptions
```

允许在将 MailMessage 保存为 Mhtml 格式时指定其他选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MhtSaveOptions()](#MhtSaveOptions--) | 初始化此类的一个新实例，可用于将 MailMessage 保存为 Mhtml 格式。 |
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
| [getFormatTemplates()](#getFormatTemplates--) | 获取格式模板。 |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | 表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。 |
| [getMhtFormatOptions()](#getMhtFormatOptions--) | 定义以 MHTML 格式保存时的附加选项。 |
| [getPreserveOriginalBoundaries()](#getPreserveOriginalBoundaries--) | 定义在保存时是否需要保留邮件消息的原始边界。 |
| [getPreserveOriginalDate()](#getPreserveOriginalDate--) | 定义在保存邮件时是否需要保留原始日期。 |
| [getRenderedContactFields()](#getRenderedContactFields--) | 定义将在输出 mhtml 中包含的联系人字段组。 |
| [getRenderingHeaders()](#getRenderingHeaders--) | 获取用于渲染的标题列表。 |
| [getSaveAttachments()](#getSaveAttachments--) | 获取或设置指示是否保存附件的值。 |
| [getSkipInlineImages()](#getSkipInlineImages--) | 定义在保存为 mhtml 时是否跳过图像的引用。 |
| [getTimeout()](#getTimeout--) | 限制在以 Mht 格式保存时对消息进行格式化的时间（毫秒）。 |
| [getTimeoutReachedHandler()](#getTimeoutReachedHandler--) | 在保存为 Mhtml 时超时将引发此异常。 |
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
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | 表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。 |
| [setMhtFormatOptions(int value)](#setMhtFormatOptions-int-) | 定义以 MHTML 格式保存时的附加选项。 |
| [setPreserveOriginalBoundaries(boolean value)](#setPreserveOriginalBoundaries-boolean-) | 定义在保存时是否需要保留邮件消息的原始边界。 |
| [setPreserveOriginalDate(boolean value)](#setPreserveOriginalDate-boolean-) | 定义在保存邮件时是否需要保留原始日期。 |
| [setRenderedContactFields(int value)](#setRenderedContactFields-int-) | 定义将在输出 mhtml 中包含的联系人字段组。 |
| [setSaveAttachments(boolean value)](#setSaveAttachments-boolean-) | 获取或设置指示是否保存附件的值。 |
| [setSkipInlineImages(boolean value)](#setSkipInlineImages-boolean-) | 定义在保存为 mhtml 时是否跳过图像的引用。 |
| [setTimeout(int value)](#setTimeout-int-) | 限制在以 Mht 格式保存时对消息进行格式化的时间（毫秒）。 |
| [setTimeoutReachedHandler(TimeoutReachedHandler value)](#setTimeoutReachedHandler-com.aspose.email.TimeoutReachedHandler-) | 在保存为 Mhtml 时超时将引发此异常。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MhtSaveOptions() {#MhtSaveOptions--}
```
public MhtSaveOptions()
```


初始化此类的一个新实例，可用于将 MailMessage 保存为 Mhtml 格式。

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
### getFormatTemplates() {#getFormatTemplates--}
```
public final System.Collections.Specialized.StringDictionary getFormatTemplates()
```


获取格式模板。

值：格式模板。

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringDictionary
### getMailMessageSaveType() {#getMailMessageSaveType--}
```
public final MailMessageSaveType getMailMessageSaveType()
```


表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。默认值为 Eml。

**Returns:**
[MailMessageSaveType](../../com.aspose.email/mailmessagesavetype)
### getMhtFormatOptions() {#getMhtFormatOptions--}
```
public final int getMhtFormatOptions()
```


定义以 MHTML 格式保存时的附加选项。默认值为 MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments。

**Returns:**
int
### getPreserveOriginalBoundaries() {#getPreserveOriginalBoundaries--}
```
public final boolean getPreserveOriginalBoundaries()
```


定义在保存时是否需要保留邮件消息的原始边界。

**Returns:**
boolean
### getPreserveOriginalDate() {#getPreserveOriginalDate--}
```
public final boolean getPreserveOriginalDate()
```


定义在保存邮件时是否需要保留原始日期。默认值为 true。

**Returns:**
boolean
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
### getSaveAttachments() {#getSaveAttachments--}
```
public final boolean getSaveAttachments()
```


获取或设置指示是否保存附件的值。

值：如果应保存附件则为 true；否则为 false。

**Returns:**
boolean
### getSkipInlineImages() {#getSkipInlineImages--}
```
public final boolean getSkipInlineImages()
```


定义在保存为 mhtml 时是否跳过图像的引用。默认值为 false。

**Returns:**
boolean
### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


限制在以 Mht 格式保存时对消息进行格式化的时间（毫秒）。默认值为 3 秒。

**Returns:**
int
### getTimeoutReachedHandler() {#getTimeoutReachedHandler--}
```
public final TimeoutReachedHandler getTimeoutReachedHandler()
```


在保存为 Mhtml 时超时将引发此异常。

**Returns:**
[TimeoutReachedHandler](../../com.aspose.email/timeoutreachedhandler)
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

### setMailMessageSaveType(MailMessageSaveType value) {#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-}
```
public final void setMailMessageSaveType(MailMessageSaveType value)
```


表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。默认值为 Eml。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### setMhtFormatOptions(int value) {#setMhtFormatOptions-int-}
```
public final void setMhtFormatOptions(int value)
```


定义以 MHTML 格式保存时的附加选项。默认值为 MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setPreserveOriginalBoundaries(boolean value) {#setPreserveOriginalBoundaries-boolean-}
```
public final void setPreserveOriginalBoundaries(boolean value)
```


定义在保存时是否需要保留邮件消息的原始边界。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setPreserveOriginalDate(boolean value) {#setPreserveOriginalDate-boolean-}
```
public final void setPreserveOriginalDate(boolean value)
```


定义在保存邮件时是否需要保留原始日期。默认值为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setRenderedContactFields(int value) {#setRenderedContactFields-int-}
```
public final void setRenderedContactFields(int value)
```


定义将在输出 mhtml 中包含的联系人字段组。默认值为 ContactFieldsSet.AllExisting。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setSaveAttachments(boolean value) {#setSaveAttachments-boolean-}
```
public final void setSaveAttachments(boolean value)
```


获取或设置指示是否保存附件的值。

值：如果应保存附件则为 true；否则为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setSkipInlineImages(boolean value) {#setSkipInlineImages-boolean-}
```
public final void setSkipInlineImages(boolean value)
```


定义在保存为 mhtml 时是否跳过图像的引用。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


限制在以 Mht 格式保存时对消息进行格式化的时间（毫秒）。默认值为 3 秒。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setTimeoutReachedHandler(TimeoutReachedHandler value) {#setTimeoutReachedHandler-com.aspose.email.TimeoutReachedHandler-}
```
public final void setTimeoutReachedHandler(TimeoutReachedHandler value)
```


在保存为 Mhtml 时超时将引发此异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TimeoutReachedHandler](../../com.aspose.email/timeoutreachedhandler) |  |

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

