---
title: EmlSaveOptions
second_title: Aspose.Email for Android via Java API 参考
description: 允许在将 MailMessage 保存为 Eml 和 Emlx 格式时指定附加选项。
type: docs
weight: 118
url: /zh/androidjava/com.aspose.email/emlsaveoptions/
---

**Inheritance:**
java.lang.Object，[com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions)
```
public class EmlSaveOptions extends SaveOptions
```

允许在将 MailMessage 保存为 Eml 和 Emlx 格式时指定附加选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmlSaveOptions(MailMessageSaveType saveType)](#EmlSaveOptions-com.aspose.email.MailMessageSaveType-) | 初始化此类的新实例，可用于以 Eml 和 Emlx 格式保存 MailMessage。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createSaveOptions(MailMessageSaveType saveType)](#createSaveOptions-com.aspose.email.MailMessageSaveType-) | 创建适用于指定保存类型的类的保存选项对象。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCheckBodyContentEncoding()](#getCheckBodyContentEncoding--) | 定义在保存时是否需要检查消息正文内容的编码。 |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | 表示通常由调用方提供并处理进度事件的方法。 |
| [getDefaultEml()](#getDefaultEml--) | 获取用于将消息保存为 Eml 格式的默认值选项。 |
| [getDefaultHtml()](#getDefaultHtml--) | 获取用于将消息保存为 Html 格式的默认值选项。 |
| [getDefaultMhtml()](#getDefaultMhtml--) | 获取用于将消息保存为 Mhtml 格式的默认值选项。 |
| [getDefaultMsg()](#getDefaultMsg--) | 获取用于将消息保存为 Msg（ASCII）格式的默认值选项。 |
| [getDefaultMsgUnicode()](#getDefaultMsgUnicode--) | 获取用于将消息保存为 Msg（Unicode）格式的默认值选项。 |
| [getFileCompatibilityMode()](#getFileCompatibilityMode--) | 定义在保存消息时必须进行的内部转换。 |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | 表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。 |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | 获取或设置一个值，指示在转换为 MailMessage 时是否需要保留嵌入消息的 MSG 格式。 |
| [getPreserveSignedContent()](#getPreserveSignedContent--) | 获取或设置一个值，指示是否需要在不更改内容的情况下保存已签名的邮件，以提供正确的数字签名结构。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCheckBodyContentEncoding(boolean value)](#setCheckBodyContentEncoding-boolean-) | 定义在保存时是否需要检查消息正文内容的编码。 |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | 表示通常由调用方提供并处理进度事件的方法。 |
| [setFileCompatibilityMode(int value)](#setFileCompatibilityMode-int-) | 定义在保存消息时必须进行的内部转换。 |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | 表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。 |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | 获取或设置一个值，指示在转换为 MailMessage 时是否需要保留嵌入消息的 MSG 格式。 |
| [setPreserveSignedContent(boolean value)](#setPreserveSignedContent-boolean-) | 获取或设置一个值，指示是否需要在不更改内容的情况下保存已签名的邮件，以提供正确的数字签名结构。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmlSaveOptions(MailMessageSaveType saveType) {#EmlSaveOptions-com.aspose.email.MailMessageSaveType-}
```
public EmlSaveOptions(MailMessageSaveType saveType)
```


初始化此类的新实例，可用于以 Eml 和 Emlx 格式保存 MailMessage。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| saveType | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

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
### getCheckBodyContentEncoding() {#getCheckBodyContentEncoding--}
```
public final boolean getCheckBodyContentEncoding()
```


定义在保存时是否需要检查消息正文内容的编码。默认值为 false。

--------------------

如果为 true，则会检查 MailMessage.HtmlBody ([MailMessage.getHtmlBody](../../com.aspose.email/mailmessage\#getHtmlBody)/[MailMessage.setHtmlBody(String)](../../com.aspose.email/mailmessage\#setHtmlBody-String-)) 的内容编码是否与 MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) 属性指定的编码匹配。如果 HtmlBody 的内容编码与 BodyEncoding 属性不匹配，则 MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) 和 MailMessage.PreferredTextEncoding ([MailMessage.getPreferredTextEncoding](../../com.aspose.email/mailmessage\#getPreferredTextEncoding)/[MailMessage.setPreferredTextEncoding(Encoding)](../../com.aspose.email/mailmessage\#setPreferredTextEncoding-Encoding-)) 将被更改为默认的 System.Text.Encoding.UTF8 (java.nio.charset.Charset\#getUTF8.getUTF8)。

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getFileCompatibilityMode() {#getFileCompatibilityMode--}
```
public final int getFileCompatibilityMode()
```


定义在保存邮件时必须进行的内部转换。默认值为 FileCompatibilityMode.None。

**Returns:**
int
### getMailMessageSaveType() {#getMailMessageSaveType--}
```
public final MailMessageSaveType getMailMessageSaveType()
```


表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。默认值为 Eml。

**Returns:**
[MailMessageSaveType](../../com.aspose.email/mailmessagesavetype)
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


获取或设置一个值，指示在转换为 MailMessage 时是否需要保留嵌入消息的 MSG 格式。默认值为 false。

--------------------

通常，嵌入的消息与其所在的消息具有相同的格式（EML 或 MSG）。默认情况下，在从 MSG 转换为 EML 或反向转换时，嵌入的消息也会转换为目标格式。将此属性设置为 true 可保留嵌入消息的原始格式。

**Returns:**
boolean
### getPreserveSignedContent() {#getPreserveSignedContent--}
```
public final boolean getPreserveSignedContent()
```


获取或设置一个值，指示是否需要在不更改内容的情况下保存已签名的邮件，以提供正确的数字签名结构。默认值为 false。

--------------------

此属性仅对已签名的邮件有意义；对未签名的邮件没有影响。该属性旨在处理一些由其他客户端生成的、带有分离签名的复杂已签名邮件，由于实现差异导致 Aspose.Email 无法完全复制它们的 MIME 内容生成。如果在保存此类邮件时不使用 PreserveSignedContent，保存的邮件中的签名将会失败。某些简单的邮件以及带有附加签名的邮件可以在不使用此属性的情况下正确保存。

**Returns:**
boolean
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




### setCheckBodyContentEncoding(boolean value) {#setCheckBodyContentEncoding-boolean-}
```
public final void setCheckBodyContentEncoding(boolean value)
```


定义在保存时是否需要检查消息正文内容的编码。默认值为 false。

--------------------

如果为 true，则会检查 MailMessage.HtmlBody ([MailMessage.getHtmlBody](../../com.aspose.email/mailmessage\#getHtmlBody)/[MailMessage.setHtmlBody(String)](../../com.aspose.email/mailmessage\#setHtmlBody-String-)) 的内容编码是否与 MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) 属性指定的编码匹配。如果 HtmlBody 的内容编码与 BodyEncoding 属性不匹配，则 MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) 和 MailMessage.PreferredTextEncoding ([MailMessage.getPreferredTextEncoding](../../com.aspose.email/mailmessage\#getPreferredTextEncoding)/[MailMessage.setPreferredTextEncoding(Encoding)](../../com.aspose.email/mailmessage\#setPreferredTextEncoding-Encoding-)) 将被更改为默认的 System.Text.Encoding.UTF8 (java.nio.charset.Charset\#getUTF8.getUTF8)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setCustomProgressHandler(ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(ConversionProgressEventHandler value)
```


表示通常由调用方提供并处理进度事件的方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setFileCompatibilityMode(int value) {#setFileCompatibilityMode-int-}
```
public final void setFileCompatibilityMode(int value)
```


定义在保存邮件时必须进行的内部转换。默认值为 FileCompatibilityMode.None。

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

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


获取或设置一个值，指示在转换为 MailMessage 时是否需要保留嵌入消息的 MSG 格式。默认值为 false。

--------------------

通常，嵌入的消息与其所在的消息具有相同的格式（EML 或 MSG）。默认情况下，在从 MSG 转换为 EML 或反向转换时，嵌入的消息也会转换为目标格式。将此属性设置为 true 可保留嵌入消息的原始格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setPreserveSignedContent(boolean value) {#setPreserveSignedContent-boolean-}
```
public final void setPreserveSignedContent(boolean value)
```


获取或设置一个值，指示是否需要在不更改内容的情况下保存已签名的邮件，以提供正确的数字签名结构。默认值为 false。

--------------------

此属性仅对已签名的邮件有意义；对未签名的邮件没有影响。该属性旨在处理一些由其他客户端生成的、带有分离签名的复杂已签名邮件，由于实现差异导致 Aspose.Email 无法完全复制它们的 MIME 内容生成。如果在保存此类邮件时不使用 PreserveSignedContent，保存的邮件中的签名将会失败。某些简单的邮件以及带有附加签名的邮件可以在不使用此属性的情况下正确保存。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

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

