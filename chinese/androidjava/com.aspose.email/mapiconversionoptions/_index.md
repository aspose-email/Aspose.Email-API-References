---
title: MapiConversionOptions
second_title: Aspose.Email for Android via Java API 参考
description: 此类允许用户在将 MailMessage 转换为 MapiMessage 时指定附加选项。
type: docs
weight: 248
url: /zh/androidjava/com.aspose.email/mapiconversionoptions/
---

**Inheritance:**
java.lang.Object
```
public class MapiConversionOptions
```

此类允许用户在将 MailMessage 转换为 MapiMessage 时指定附加选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiConversionOptions()](#MapiConversionOptions--) | 初始化一个新的 [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) 类的实例。 |
| [MapiConversionOptions(int format)](#MapiConversionOptions-int-) | 使用指定的 OutlookMessageFormat 初始化一个新的 [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getASCIIFormat()](#getASCIIFormat--) | 返回 MapiConversionOptions，其中 OutlookMessageFormat 为 ASCII（PreserveSignature 为 False，UseBodyCompression 为 False）。 |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) |  |
| [getForcedRtfBodyForAppointment()](#getForcedRtfBodyForAppointment--) | 获取或设置一个值，指示是否需要对约会使用强制 RTF 正文。 |
| [getFormat()](#getFormat--) | 表示 Outlook 消息格式。 |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | 获取或设置一个值，指示在转换为 MapiMessage 时是否需要保留嵌入消息的 EML 格式。 |
| [getPreserveEmptyDates()](#getPreserveEmptyDates--) | 获取或设置一个值，指示在转换消息时是否需要保留空日期。 |
| [getPreserveOriginalAddresses()](#getPreserveOriginalAddresses--) | 获取或设置一个值，指示是否需要保留邮件地址的原始值（不进行验证）。 |
| [getPreserveOriginalDates()](#getPreserveOriginalDates--) | 获取或设置一个值，指示在转换消息时是否需要生成新的保存和修改日期。 |
| [getPreserveSignature()](#getPreserveSignature--) | 如果需要保留签名，请设置为 true。 |
| [getUnicodeFormat()](#getUnicodeFormat--) | 返回 MapiConversionOptions，其中 OutlookMessageFormat 为 Unicode（PreserveSignature 为 False，UseBodyCompression 为 False）。 |
| [getUseBodyCompression()](#getUseBodyCompression--) | 如果需要 RTF 正文压缩，请设置为 true。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) |  |
| [setForcedRtfBodyForAppointment(boolean value)](#setForcedRtfBodyForAppointment-boolean-) | 获取或设置一个值，指示是否需要对约会使用强制 RTF 正文。 |
| [setFormat(int value)](#setFormat-int-) | 表示 Outlook 消息格式。 |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | 获取或设置一个值，指示在转换为 MapiMessage 时是否需要保留嵌入消息的 EML 格式。 |
| [setPreserveEmptyDates(boolean value)](#setPreserveEmptyDates-boolean-) | 获取或设置一个值，指示在转换消息时是否需要保留空日期。 |
| [setPreserveOriginalAddresses(boolean value)](#setPreserveOriginalAddresses-boolean-) | 获取或设置一个值，指示是否需要保留邮件地址的原始值（不进行验证）。 |
| [setPreserveOriginalDates(boolean value)](#setPreserveOriginalDates-boolean-) | 获取或设置一个值，指示在转换消息时是否需要生成新的保存和修改日期。 |
| [setPreserveSignature(boolean value)](#setPreserveSignature-boolean-) | 如果需要保留签名，请设置为 true。 |
| [setUseBodyCompression(boolean value)](#setUseBodyCompression-boolean-) | 如果需要 RTF 正文压缩，请设置为 true。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiConversionOptions() {#MapiConversionOptions--}
```
public MapiConversionOptions()
```


初始化一个新的 [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) 类的实例。

### MapiConversionOptions(int format) {#MapiConversionOptions-int-}
```
public MapiConversionOptions(int format)
```


使用指定的 OutlookMessageFormat 初始化一个新的 [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | int | MapiMessage 的格式 [OutlookMessageFormat](../../com.aspose.email/outlookmessageformat)。 |

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
### getASCIIFormat() {#getASCIIFormat--}
```
public static MapiConversionOptions getASCIIFormat()
```


返回 MapiConversionOptions，其中 OutlookMessageFormat 为 ASCII（PreserveSignature 为 False，UseBodyCompression 为 False）。

**Returns:**
[MapiConversionOptions](../../com.aspose.email/mapiconversionoptions)
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




**Returns:**
[ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler)
### getForcedRtfBodyForAppointment() {#getForcedRtfBodyForAppointment--}
```
public final boolean getForcedRtfBodyForAppointment()
```


获取或设置一个值，指示是否需要对约会使用强制 RTF 正文。默认值为 true。

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public final int getFormat()
```


表示 Outlook 消息格式。

**Returns:**
int
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


获取或设置一个值，指示在转换为 MapiMessage 时是否需要保留嵌入消息的 EML 格式。默认情况下该值为 false。

--------------------

通常，嵌入的消息与其所在的主消息具有相同的格式（EML 或 MSG）。默认情况下，在 EML 与 MSG 相互转换时，嵌入的消息也会转换为目标格式。将此属性设为 true 可保留嵌入消息的原始格式。

**Returns:**
boolean
### getPreserveEmptyDates() {#getPreserveEmptyDates--}
```
public final boolean getPreserveEmptyDates()
```


获取或设置一个值，指示在转换消息时是否需要保留空日期。

**Returns:**
boolean
### getPreserveOriginalAddresses() {#getPreserveOriginalAddresses--}
```
public final boolean getPreserveOriginalAddresses()
```


获取或设置一个值，指示是否需要保留邮件地址的原始值（不进行验证）。

**Returns:**
boolean
### getPreserveOriginalDates() {#getPreserveOriginalDates--}
```
public final boolean getPreserveOriginalDates()
```


获取或设置一个值，指示在转换消息时是否需要生成新的保存和修改日期。

**Returns:**
boolean
### getPreserveSignature() {#getPreserveSignature--}
```
public final boolean getPreserveSignature()
```


如果需要保留签名，请设置为 true。

**Returns:**
boolean
### getUnicodeFormat() {#getUnicodeFormat--}
```
public static MapiConversionOptions getUnicodeFormat()
```


返回 MapiConversionOptions，其中 OutlookMessageFormat 为 Unicode（PreserveSignature 为 False，UseBodyCompression 为 False）。

**Returns:**
[MapiConversionOptions](../../com.aspose.email/mapiconversionoptions)
### getUseBodyCompression() {#getUseBodyCompression--}
```
public final boolean getUseBodyCompression()
```


如果需要 RTF 正文压缩，请设置为 true。

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




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setForcedRtfBodyForAppointment(boolean value) {#setForcedRtfBodyForAppointment-boolean-}
```
public final void setForcedRtfBodyForAppointment(boolean value)
```


获取或设置一个值，指示是否需要对约会使用强制 RTF 正文。默认值为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


表示 Outlook 消息格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


获取或设置一个值，指示在转换为 MapiMessage 时是否需要保留嵌入消息的 EML 格式。默认情况下该值为 false。

--------------------

通常，嵌入的消息与其所在的主消息具有相同的格式（EML 或 MSG）。默认情况下，在 EML 与 MSG 相互转换时，嵌入的消息也会转换为目标格式。将此属性设为 true 可保留嵌入消息的原始格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setPreserveEmptyDates(boolean value) {#setPreserveEmptyDates-boolean-}
```
public final void setPreserveEmptyDates(boolean value)
```


获取或设置一个值，指示在转换消息时是否需要保留空日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setPreserveOriginalAddresses(boolean value) {#setPreserveOriginalAddresses-boolean-}
```
public final void setPreserveOriginalAddresses(boolean value)
```


获取或设置一个值，指示是否需要保留邮件地址的原始值（不进行验证）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setPreserveOriginalDates(boolean value) {#setPreserveOriginalDates-boolean-}
```
public final void setPreserveOriginalDates(boolean value)
```


获取或设置一个值，指示在转换消息时是否需要生成新的保存和修改日期。

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

### setUseBodyCompression(boolean value) {#setUseBodyCompression-boolean-}
```
public final void setUseBodyCompression(boolean value)
```


如果需要 RTF 正文压缩，请设置为 true。

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

