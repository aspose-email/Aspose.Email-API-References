---
title: HtmlLoadOptions
second_title: Aspose.Email for Android via Java API 参考
description: 允许在从 Html 格式加载 MailMessage 时指定其他选项。
type: docs
weight: 160
url: /zh/androidjava/com.aspose.email/htmlloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.LoadOptions](../../com.aspose.email/loadoptions)
```
public class HtmlLoadOptions extends LoadOptions
```

允许在从 Html 格式加载 MailMessage 时指定其他选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlLoadOptions()](#HtmlLoadOptions--) | 初始化此类的新实例，可用于从 Html 格式加载 MailMessage。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMessageFormat()](#getMessageFormat--) | 表示邮件的格式。它可以是 eml、msg 或 mhtml 格式。 |
| [getPathToResources()](#getPathToResources--) | 资源文件目录的路径。 |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | 获取或设置消息的首选编码。 |
| [getPrefferedTextEncoding()](#getPrefferedTextEncoding--) | 获取或设置消息的首选编码。 |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | 获取或设置一个值，指示在加载时是否需要保留嵌入消息的格式。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPathToResources(String value)](#setPathToResources-java.lang.String-) | 资源文件目录的路径。 |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | 获取或设置消息的首选编码。 |
| [setPrefferedTextEncoding(Charset value)](#setPrefferedTextEncoding-java.nio.charset.Charset-) | 获取或设置消息的首选编码。 |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | 获取或设置一个值，指示在加载时是否需要保留嵌入消息的格式。 |
| [shouldAddPlainTextView()](#shouldAddPlainTextView--) | 指定是否添加正文的文本表示。 |
| [shouldAddPlainTextView(boolean value)](#shouldAddPlainTextView-boolean-) | 指定是否添加正文的文本表示。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlLoadOptions() {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```


初始化此类的新实例，可用于从 Html 格式加载 MailMessage。

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
### getMessageFormat() {#getMessageFormat--}
```
public final MessageFormat getMessageFormat()
```


表示邮件消息的格式。它可以是 eml、msg 或 mhtml 格式。默认值为 Eml。

**Returns:**
[MessageFormat](../../com.aspose.email/messageformat)
### getPathToResources() {#getPathToResources--}
```
public final String getPathToResources()
```


资源文件目录的路径。

**Returns:**
java.lang.String
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


获取或设置消息的首选编码。强制设置消息主题和正文的首选编码。默认值为 null。

**Returns:**
java.nio.charset.Charset
### getPrefferedTextEncoding() {#getPrefferedTextEncoding--}
```
public final Charset getPrefferedTextEncoding()
```


获取或设置消息的首选编码。强制设置消息主题和正文的首选编码。默认值为 null。

**Returns:**
java.nio.charset.Charset
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


获取或设置一个值，指示在加载时是否需要保留嵌入消息的格式。默认值为 false。

--------------------

通常，嵌入的消息与其所在的主消息具有相同的格式（EML 或 MSG）。默认情况下，在 EML 与 MSG 相互转换时，嵌入的消息也会转换为目标格式。将此属性设为 true 可保留嵌入消息的原始格式。

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




### setPathToResources(String value) {#setPathToResources-java.lang.String-}
```
public final void setPathToResources(String value)
```


资源文件目录的路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


获取或设置消息的首选编码。强制设置消息主题和正文的首选编码。默认值为 null。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPrefferedTextEncoding(Charset value) {#setPrefferedTextEncoding-java.nio.charset.Charset-}
```
public final void setPrefferedTextEncoding(Charset value)
```


获取或设置消息的首选编码。强制设置消息主题和正文的首选编码。默认值为 null。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


获取或设置一个值，指示在加载时是否需要保留嵌入消息的格式。默认值为 false。

--------------------

通常，嵌入的消息与其所在的主消息具有相同的格式（EML 或 MSG）。默认情况下，在 EML 与 MSG 相互转换时，嵌入的消息也会转换为目标格式。将此属性设为 true 可保留嵌入消息的原始格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### shouldAddPlainTextView() {#shouldAddPlainTextView--}
```
public final boolean shouldAddPlainTextView()
```


指定是否添加正文的文本表示。默认值为 false。

**Returns:**
boolean
### shouldAddPlainTextView(boolean value) {#shouldAddPlainTextView-boolean-}
```
public final void shouldAddPlainTextView(boolean value)
```


指定是否添加正文的文本表示。默认值为 false。

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

