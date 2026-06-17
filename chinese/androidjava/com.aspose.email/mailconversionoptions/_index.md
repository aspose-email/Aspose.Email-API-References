---
title: MailConversionOptions
second_title: Aspose.Email for Android via Java API 参考
description: 在从 MapiMessage 转换为 MailMessage 时指定其他选项。
type: docs
weight: 190
url: /zh/androidjava/com.aspose.email/mailconversionoptions/
---

**Inheritance:**
java.lang.Object
```
public class MailConversionOptions
```

在从 MapiMessage 转换为 MailMessage 时指定其他选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MailConversionOptions()](#MailConversionOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConvertAsTnef()](#getConvertAsTnef--) | 设置为 true 可将 MapiMessage 信息导入为 MailMessage 对象，并将 MapiMessage 作为 TNEF 附件。 |
| [getKeepOriginalEmailAddresses()](#getKeepOriginalEmailAddresses--) | 获取或设置一个值，指示是否需要保留原始电子邮件地址。 |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | 获取或设置一个值，指示在转换为 MailMessage 时是否需要保留嵌入消息的 MSG 格式。 |
| [getPreserveRtfContent()](#getPreserveRtfContent--) | 获取或设置一个值，指示是否需要在 MailMessage 中保留 RTF 正文。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setConvertAsTnef(boolean value)](#setConvertAsTnef-boolean-) | 设置为 true 可将 MapiMessage 信息导入为 MailMessage 对象，并将 MapiMessage 作为 TNEF 附件。 |
| [setKeepOriginalEmailAddresses(boolean value)](#setKeepOriginalEmailAddresses-boolean-) | 获取或设置一个值，指示是否需要保留原始电子邮件地址。 |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | 获取或设置一个值，指示在转换为 MailMessage 时是否需要保留嵌入消息的 MSG 格式。 |
| [setPreserveRtfContent(boolean value)](#setPreserveRtfContent-boolean-) | 获取或设置一个值，指示是否需要在 MailMessage 中保留 RTF 正文。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailConversionOptions() {#MailConversionOptions--}
```
public MailConversionOptions()
```


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
### getConvertAsTnef() {#getConvertAsTnef--}
```
public final boolean getConvertAsTnef()
```


设置为 true 可将 MapiMessage 信息导入为 MailMessage 对象，并将 MapiMessage 作为 TNEF 附件。

**Returns:**
boolean
### getKeepOriginalEmailAddresses() {#getKeepOriginalEmailAddresses--}
```
public final boolean getKeepOriginalEmailAddresses()
```


获取或设置一个值，指示是否需要保留原始电子邮件地址。

**Returns:**
boolean
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


获取或设置一个值，指示在转换为 MailMessage 时是否需要保留嵌入消息的 MSG 格式。默认值为 false。

--------------------

通常，嵌入的消息与底层消息具有相同的格式（EML 或 MSG）。默认情况下，在 MSG 与 EML 相互转换时，嵌入的消息也会转换为目标格式。将该属性设置为 true 可保留嵌入消息的原始格式。

**Returns:**
boolean
### getPreserveRtfContent() {#getPreserveRtfContent--}
```
public final boolean getPreserveRtfContent()
```


获取或设置一个值，指示是否需要在 MailMessage 中保留 RTF 正文。

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




### setConvertAsTnef(boolean value) {#setConvertAsTnef-boolean-}
```
public final void setConvertAsTnef(boolean value)
```


设置为 true 可将 MapiMessage 信息导入为 MailMessage 对象，并将 MapiMessage 作为 TNEF 附件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setKeepOriginalEmailAddresses(boolean value) {#setKeepOriginalEmailAddresses-boolean-}
```
public final void setKeepOriginalEmailAddresses(boolean value)
```


获取或设置一个值，指示是否需要保留原始电子邮件地址。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


获取或设置一个值，指示在转换为 MailMessage 时是否需要保留嵌入消息的 MSG 格式。默认值为 false。

--------------------

通常，嵌入的消息与底层消息具有相同的格式（EML 或 MSG）。默认情况下，在 MSG 与 EML 相互转换时，嵌入的消息也会转换为目标格式。将该属性设置为 true 可保留嵌入消息的原始格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setPreserveRtfContent(boolean value) {#setPreserveRtfContent-boolean-}
```
public final void setPreserveRtfContent(boolean value)
```


获取或设置一个值，指示是否需要在 MailMessage 中保留 RTF 正文。

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

