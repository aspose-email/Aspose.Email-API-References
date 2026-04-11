---
title: SaveOptions
second_title: Aspose.Email for Android via Java API 参考
description: 这是一个抽象基类，供允许用户在将 MailMessage 保存为特定格式时指定附加选项的类使用。
type: docs
weight: 378
url: /zh/androidjava/com.aspose.email/saveoptions/
---

**Inheritance:**
java.lang.Object
```
public abstract class SaveOptions
```

这是一个抽象基类，供允许用户在将 MailMessage 保存为特定格式时指定附加选项的类使用。
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
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | 表示通常由调用方提供并处理进度事件的方法。 |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | 表示邮件消息的保存类型。它可以是 eml、msg（ASCII 或 Unicode）、mhtml 或 html 格式。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

