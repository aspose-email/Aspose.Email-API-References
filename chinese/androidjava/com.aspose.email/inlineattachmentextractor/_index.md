---
title: InlineAttachmentExtractor
second_title: Aspose.Email for Android via Java API 参考
description: 提供从 MSO 包中提取文件的能力。
type: docs
weight: 164
url: /zh/androidjava/com.aspose.email/inlineattachmentextractor/
---

**Inheritance:**
java.lang.Object
```
public class InlineAttachmentExtractor
```

提供从 MSO 包中提取文件的功能。可用于处理 "oledata.mso" 等通常随 Outlook 创建的邮件附带的文件。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [InlineAttachmentExtractor()](#InlineAttachmentExtractor--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [enumerateMsoPackage(InputStream stream)](#enumerateMsoPackage-java.io.InputStream-) | 枚举 MSO 包并返回包含文件数据的字典。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InlineAttachmentExtractor() {#InlineAttachmentExtractor--}
```
public InlineAttachmentExtractor()
```


### enumerateMsoPackage(InputStream stream) {#enumerateMsoPackage-java.io.InputStream-}
```
public static System.Collections.Generic.IGenericDictionary<String,byte[]> enumerateMsoPackage(InputStream stream)
```


枚举 MSO 包并返回包含文件数据的字典。键是文件标识符，值包含实际数据。文件通常在消息正文中使用提供的标识符进行引用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 要解析的流。 |

--------------------

在评估模式下，仅从给定的 MSO 流中提取一个文件。 |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,byte[]> - 包含文件数据的字典。
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

