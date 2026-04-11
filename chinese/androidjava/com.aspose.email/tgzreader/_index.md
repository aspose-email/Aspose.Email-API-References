---
title: TgzReader
second_title: Aspose.Email for Android via Java API 参考
description: Zimbra tgz 存储的邮箱项目读取器。
type: docs
weight: 402
url: /zh/androidjava/com.aspose.email/tgzreader/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class TgzReader implements System.IDisposable, Closeable
```

Zimbra tgz 存储的邮箱项目读取器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TgzReader(String fileName)](#TgzReader-java.lang.String-) | 初始化 [TgzReader](../../com.aspose.email/tgzreader) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | 执行应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportTo(String path)](#exportTo-java.lang.String-) | 使用给定路径保存邮件和目录结构。 |
| [getClass()](#getClass--) |  |
| [getCurrentDirectory()](#getCurrentDirectory--) | 获取当前目录名称。 |
| [getCurrentMessage()](#getCurrentMessage--) | 获取当前邮件。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readNextMessage()](#readNextMessage--) | 读取下一封邮件。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TgzReader(String fileName) {#TgzReader-java.lang.String-}
```
public TgzReader(String fileName)
```


初始化 [TgzReader](../../com.aspose.email/tgzreader) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |

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
### exportTo(String path) {#exportTo-java.lang.String-}
```
public final void exportTo(String path)
```


使用给定路径保存邮件和目录结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 用于保存存储结构的主目录路径。 |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrentDirectory() {#getCurrentDirectory--}
```
public final String getCurrentDirectory()
```


获取当前目录名称。

值：目录的名称。

**Returns:**
java.lang.String
### getCurrentMessage() {#getCurrentMessage--}
```
public final MailMessage getCurrentMessage()
```


获取当前邮件。

值：该 [MailMessage](../../com.aspose.email/mailmessage)。

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
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




### readNextMessage() {#readNextMessage--}
```
public final boolean readNextMessage()
```


读取下一封邮件。

**Returns:**
布尔 -
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

