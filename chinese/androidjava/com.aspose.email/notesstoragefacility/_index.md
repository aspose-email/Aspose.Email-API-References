---
title: NotesStorageFacility
second_title: Aspose.Email for Android via Java API 参考
description: Notes Storage Facility NSF 数据库文件由 IBM Lotus Notes 和 Domino 用于存储各种对象，例如电子邮件、约会和文档，还包括应用表单和视图。
type: docs
weight: 331
url: /zh/androidjava/com.aspose.email/notesstoragefacility/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class NotesStorageFacility implements System.IDisposable, Closeable
```

Notes Storage Facility (NSF) 数据库文件被 (IBM) Lotus Notes 和 Domino 用于存储各种对象，如电子邮件、约会和文档，还包括应用程序表单和视图。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [NotesStorageFacility(String fileName)](#NotesStorageFacility-java.lang.String-) | 初始化一个新的 [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) 类实例。 |
| [NotesStorageFacility(InputStream stream)](#NotesStorageFacility-java.io.InputStream-) | 初始化一个新的 [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) 类实例。 |
| [NotesStorageFacility(String fileName, NsfLoadOptions options)](#NotesStorageFacility-java.lang.String-com.aspose.email.NsfLoadOptions-) | 初始化一个新的 [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) 类实例。 |
| [NotesStorageFacility(InputStream stream, NsfLoadOptions options)](#NotesStorageFacility-java.io.InputStream-com.aspose.email.NsfLoadOptions-) | 初始化一个新的 [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | 执行应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [enumerateMessages()](#enumerateMessages--) | 公开枚举器，支持对存储中消息的迭代。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NotesStorageFacility(String fileName) {#NotesStorageFacility-java.lang.String-}
```
public NotesStorageFacility(String fileName)
```


初始化一个新的 [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |

### NotesStorageFacility(InputStream stream) {#NotesStorageFacility-java.io.InputStream-}
```
public NotesStorageFacility(InputStream stream)
```


初始化一个新的 [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 流。 |

### NotesStorageFacility(String fileName, NsfLoadOptions options) {#NotesStorageFacility-java.lang.String-com.aspose.email.NsfLoadOptions-}
```
public NotesStorageFacility(String fileName, NsfLoadOptions options)
```


初始化一个新的 [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |
| options | [NsfLoadOptions](../../com.aspose.email/nsfloadoptions) | 附加加载选项。 |

### NotesStorageFacility(InputStream stream, NsfLoadOptions options) {#NotesStorageFacility-java.io.InputStream-com.aspose.email.NsfLoadOptions-}
```
public NotesStorageFacility(InputStream stream, NsfLoadOptions options)
```


初始化一个新的 [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 流。 |
| options | [NsfLoadOptions](../../com.aspose.email/nsfloadoptions) | 附加加载选项。 |

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


执行应用程序定义的任务，以释放、释放或重置非托管资源。

### enumerateMessages() {#enumerateMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MailMessage> enumerateMessages()
```


公开枚举器，支持对存储中消息的迭代。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MailMessage> -  System.Collections.Generic.IEnumerableltTgt，表示遍历存储中消息的枚举器。
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

