---
title: HeadersFormattingOptions
second_title: Aspose.Email for Android via Java API 参考
description: 允许在将 MailMessage 保存为 Mhtml 或 Html 格式时指定标题的格式化选项。
type: docs
weight: 158
url: /zh/androidjava/com.aspose.email/headersformattingoptions/
---

**Inheritance:**
java.lang.Object，[com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions)
```
public abstract class HeadersFormattingOptions extends SaveOptions
```

允许在将 MailMessage 保存为 Mhtml 或 Html 格式时指定标题的格式化选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HeadersFormattingOptions()](#HeadersFormattingOptions--) | 初始化此类的一个新实例，可用于将 MailMessage 保存为 Mhtml 格式。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createSaveOptions(MailMessageSaveType saveType)](#createSaveOptions-com.aspose.email.MailMessageSaveType-) | 创建适用于指定保存类型的类的保存选项对象。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAfterHeadersFormat()](#getAfterHeadersFormat--) | 在标题格式之后。 |
| [getBeforeHeadersFormat()](#getBeforeHeadersFormat--) | 在标题格式之前。 |
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
| [getRenderedContactFields()](#getRenderedContactFields--) | 定义将在输出 mhtml 中包含的联系人字段组。 |
| [getRenderingHeaders()](#getRenderingHeaders--) | 获取用于渲染的标题列表。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAfterHeadersFormat(String value)](#setAfterHeadersFormat-java.lang.String-) | 在标题格式之后。 |
| [setBeforeHeadersFormat(String value)](#setBeforeHeadersFormat-java.lang.String-) | 在标题格式之前。 |
| [setCssStyles(String value)](#setCssStyles-java.lang.String-) | 获取或设置格式化程序的附加 CSS 样式。 |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | 表示通常由调用方提供并处理进度事件的方法。 |
| [setDefaultHeaderFormat(String value)](#setDefaultHeaderFormat-java.lang.String-) | 默认标题行格式。 |
| [setDefaultPageHeaderFormat(String value)](#setDefaultPageHeaderFormat-java.lang.String-) | 默认页面标题格式。 |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | 表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。 |
| [setRenderedContactFields(int value)](#setRenderedContactFields-int-) | 定义将在输出 mhtml 中包含的联系人字段组。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HeadersFormattingOptions() {#HeadersFormattingOptions--}
```
public HeadersFormattingOptions()
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

### setRenderedContactFields(int value) {#setRenderedContactFields-int-}
```
public final void setRenderedContactFields(int value)
```


定义将在输出 mhtml 中包含的联系人字段组。默认值为 ContactFieldsSet.AllExisting。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

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

