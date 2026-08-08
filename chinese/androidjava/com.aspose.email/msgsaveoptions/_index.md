---
title: MsgSaveOptions
second_title: Aspose.Email for Android via Java API 参考
description: 此类允许用户在以 MsgASCII 和 MsgUnicode 格式保存 MailMessage 时指定其他设置。
type: docs
weight: 327
url: /zh/androidjava/com.aspose.email/msgsaveoptions/
---

**Inheritance:**
java.lang.Object，[com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions)
```
public class MsgSaveOptions extends SaveOptions
```

此类允许用户在将 MailMessage 保存为 Msg(ASCII) 和 Msg(Unicode) 格式时指定其他设置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MsgSaveOptions(MailMessageSaveType saveType)](#MsgSaveOptions-com.aspose.email.MailMessageSaveType-) | 初始化此类的新实例，可用于以 Msg(ASCII) 和 Msg(Unicode) 格式保存 MailMessage。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createSaveOptions(MailMessageSaveType saveType)](#createSaveOptions-com.aspose.email.MailMessageSaveType-) | 创建适用于指定保存类型的类的保存选项对象。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | 表示通常由调用方提供并处理进度事件的方法。 |
| [getDefaultEml()](#getDefaultEml--) | 获取用于将消息保存为 Eml 格式的默认值选项。 |
| [getDefaultHtml()](#getDefaultHtml--) | 获取用于将消息保存为 Html 格式的默认值选项。 |
| [getDefaultMhtml()](#getDefaultMhtml--) | 获取用于将消息保存为 Mhtml 格式的默认值选项。 |
| [getDefaultMsg()](#getDefaultMsg--) | 获取用于将消息保存为 Msg（ASCII）格式的默认值选项。 |
| [getDefaultMsgUnicode()](#getDefaultMsgUnicode--) | 获取用于将消息保存为 Msg（Unicode）格式的默认值选项。 |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | 表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。 |
| [getPreserveOriginalDates()](#getPreserveOriginalDates--) | 获取或设置一个值，指示在保存消息时是否需要生成新的保存和修改日期。 |
| [getPreserveSignature()](#getPreserveSignature--) | 如果需要保留签名，请设置为 true。 |
| [getSaveAsTemplate()](#getSaveAsTemplate--) | 如果需要保存为 Outlook 文件模板（OFT 格式），请设置为 true。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | 表示通常由调用方提供并处理进度事件的方法。 |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | 表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。 |
| [setPreserveOriginalDates(boolean value)](#setPreserveOriginalDates-boolean-) | 获取或设置一个值，指示在保存消息时是否需要生成新的保存和修改日期。 |
| [setPreserveSignature(boolean value)](#setPreserveSignature-boolean-) | 如果需要保留签名，请设置为 true。 |
| [setSaveAsTemplate(boolean value)](#setSaveAsTemplate-boolean-) | 如果需要保存为 Outlook 文件模板（OFT 格式），请设置为 true。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MsgSaveOptions(MailMessageSaveType saveType) {#MsgSaveOptions-com.aspose.email.MailMessageSaveType-}
```
public MsgSaveOptions(MailMessageSaveType saveType)
```


初始化此类的新实例，可用于以 Msg(ASCII) 和 Msg(Unicode) 格式保存 MailMessage。

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
### getMailMessageSaveType() {#getMailMessageSaveType--}
```
public final MailMessageSaveType getMailMessageSaveType()
```


表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。默认值为 Eml。

**Returns:**
[MailMessageSaveType](../../com.aspose.email/mailmessagesavetype)
### getPreserveOriginalDates() {#getPreserveOriginalDates--}
```
public final boolean getPreserveOriginalDates()
```


获取或设置一个值，指示在保存消息时是否需要生成新的保存和修改日期。默认情况下，该值为 false，表示创建和修改日期将设置为 DateTime.Now。

**Returns:**
boolean
### getPreserveSignature() {#getPreserveSignature--}
```
public final boolean getPreserveSignature()
```


如果需要保留签名，请设置为 true。

**Returns:**
boolean
### getSaveAsTemplate() {#getSaveAsTemplate--}
```
public final boolean getSaveAsTemplate()
```


如果需要保存为 Outlook 文件模板（OFT 格式），请设置为 true。

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




### setCustomProgressHandler(ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(ConversionProgressEventHandler value)
```


表示通常由调用方提供并处理进度事件的方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setMailMessageSaveType(MailMessageSaveType value) {#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-}
```
public final void setMailMessageSaveType(MailMessageSaveType value)
```


表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。默认值为 Eml。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### setPreserveOriginalDates(boolean value) {#setPreserveOriginalDates-boolean-}
```
public final void setPreserveOriginalDates(boolean value)
```


获取或设置一个值，指示在保存消息时是否需要生成新的保存和修改日期。默认情况下，该值为 false，表示创建和修改日期将设置为 DateTime.Now。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setPreserveSignature(boolean value) {#setPreserveSignature-boolean-}
```
public final void setPreserveSignature(boolean value)
```


如果需要保留签名，请设置为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setSaveAsTemplate(boolean value) {#setSaveAsTemplate-boolean-}
```
public final void setSaveAsTemplate(boolean value)
```


如果需要保存为 Outlook 文件模板（OFT 格式），请设置为 true。

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

