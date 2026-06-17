---
title: MapiMessageReader
second_title: Aspose.Email for Android via Java API 参考
description: 表示可以读取 Microsoft Outlook 消息格式文档的读取器。
type: docs
weight: 265
url: /zh/androidjava/com.aspose.email/mapimessagereader/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public final class MapiMessageReader implements System.IDisposable, Closeable
```

表示可以读取 Microsoft Outlook 消息格式文档的读取器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MapiMessageReader(String path)](#MapiMessageReader-java.lang.String-) | 为指定的文件名初始化 MapiMessageReader 类的新实例。 |
| [MapiMessageReader(InputStream stream)](#MapiMessageReader-java.io.InputStream-) | 为指定的流初始化 MapiMessageReader 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | 释放 MapiMessageReader 使用的非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readAttachments()](#readAttachments--) | 从 Outlook 消息文件中提取附件。 |
| [readMessage()](#readMessage--) | 解析当前流并将数据返回为 MapiMessage。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiMessageReader(String path) {#MapiMessageReader-java.lang.String-}
```
public MapiMessageReader(String path)
```


为指定的文件名初始化 MapiMessageReader 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 要读取的完整文件路径。 |

### MapiMessageReader(InputStream stream) {#MapiMessageReader-java.io.InputStream-}
```
public MapiMessageReader(InputStream stream)
```


为指定的流初始化 MapiMessageReader 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要读取的流。 |

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


释放 MapiMessageReader 使用的非托管资源。

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




### readAttachments() {#readAttachments--}
```
public final MapiAttachmentCollection readAttachments()
```


从 Outlook 消息文件中提取附件。

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The Attachment collection.
### readMessage() {#readMessage--}
```
public final MapiMessage readMessage()
```


解析当前流并将数据返回为 MapiMessage。

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The MapiMessage from the input stream.
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

