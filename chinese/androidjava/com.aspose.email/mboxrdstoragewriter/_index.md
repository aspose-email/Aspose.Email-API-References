---
title: MboxrdStorageWriter
second_title: Aspose.Email for Android via Java API 参考
description: 表示 mboxrd 格式的存储写入器，该格式被 Thunderbird 和其他邮件客户端使用。
type: docs
weight: 300
url: /zh/androidjava/com.aspose.email/mboxrdstoragewriter/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MboxStorageWriter](../../com.aspose.email/mboxstoragewriter)
```
public final class MboxrdStorageWriter extends MboxStorageWriter
```

表示 mboxrd 格式的存储写入器，该格式被 Thunderbird 和其他邮件客户端使用。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MboxrdStorageWriter(OutputStream stream, boolean leaveOpen)](#MboxrdStorageWriter-java.io.OutputStream-boolean-) | 初始化 [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter) 类的新实例。 |
| [MboxrdStorageWriter(System.IO.Stream stream, boolean leaveOpen)](#MboxrdStorageWriter-com.aspose.ms.System.IO.Stream-boolean-) | 初始化 [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter) 类的新实例。 |
| [MboxrdStorageWriter(String fileName, boolean leaveOpen)](#MboxrdStorageWriter-java.lang.String-boolean-) | 初始化 [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter) 类的新实例。 |
| [MboxrdStorageWriter(String fileName)](#MboxrdStorageWriter-java.lang.String-) | MboxrdStorageWriter 的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | 执行应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | 刷新。 |
| [getBaseStream()](#getBaseStream--) | 获取基础流。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeMessage(MailMessage message)](#writeMessage-com.aspose.email.MailMessage-) | 将消息写入底层存储流。 |
| [writeMessage(MailMessage message, String[] fromMarker)](#writeMessage-com.aspose.email.MailMessage-java.lang.String---) | 将消息写入底层存储流。 |
### MboxrdStorageWriter(OutputStream stream, boolean leaveOpen) {#MboxrdStorageWriter-java.io.OutputStream-boolean-}
```
public MboxrdStorageWriter(OutputStream stream, boolean leaveOpen)
```


初始化 [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 流。 |
| leaveOpen | boolean | 如果设置为 true，则在释放后保持底层流打开。 |

### MboxrdStorageWriter(System.IO.Stream stream, boolean leaveOpen) {#MboxrdStorageWriter-com.aspose.ms.System.IO.Stream-boolean-}
```
public MboxrdStorageWriter(System.IO.Stream stream, boolean leaveOpen)
```


初始化 [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 流。 |
| leaveOpen | boolean | 如果设置为 true，则在释放后保持底层流打开。 |

### MboxrdStorageWriter(String fileName, boolean leaveOpen) {#MboxrdStorageWriter-java.lang.String-boolean-}
```
public MboxrdStorageWriter(String fileName, boolean leaveOpen)
```


初始化 [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |
| leaveOpen | boolean | 如果设置为 true，则在释放后保持底层流打开。 |

### MboxrdStorageWriter(String fileName) {#MboxrdStorageWriter-java.lang.String-}
```
public MboxrdStorageWriter(String fileName)
```


MboxrdStorageWriter 的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 一个 java.lang.String 对象。 |

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


执行应用程序定义的任务，以释放、释放或重置非托管资源。

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
### flush() {#flush--}
```
public void flush()
```


刷新。

### getBaseStream() {#getBaseStream--}
```
public InputStream getBaseStream()
```


获取基础流。

值：基础流。

**Returns:**
java.io.InputStream
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

### writeMessage(MailMessage message) {#writeMessage-com.aspose.email.MailMessage-}
```
public void writeMessage(MailMessage message)
```


将消息写入底层存储流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | 要写入的消息。 |

### writeMessage(MailMessage message, String[] fromMarker) {#writeMessage-com.aspose.email.MailMessage-java.lang.String---}
```
public void writeMessage(MailMessage message, String[] fromMarker)
```


将消息写入底层存储流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | 要写入的消息。 |
| fromMarker | java.lang.String[] | 在写入 MBox 存储文件时获取 From 标记。 |

