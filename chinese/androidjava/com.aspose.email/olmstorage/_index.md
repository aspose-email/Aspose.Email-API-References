---
title: OlmStorage
second_title: Aspose.Email for Android via Java API 参考
description: 表示 Outlook for Mac 存储的 .OLM 文件。
type: docs
weight: 339
url: /zh/androidjava/com.aspose.email/olmstorage/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class OlmStorage implements System.IDisposable, Closeable
```

表示 Outlook for Mac 存储（.OLM）文件。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OlmStorage(TraversalExceptionsCallback callback)](#OlmStorage-com.aspose.email.TraversalExceptionsCallback-) | 初始化一个新的 [OlmStorage](../../com.aspose.email/olmstorage) 类实例。 |
| [OlmStorage(String fileName)](#OlmStorage-java.lang.String-) | 初始化一个新的 [OlmStorage](../../com.aspose.email/olmstorage) 类实例。 |
| [OlmStorage(InputStream stream)](#OlmStorage-java.io.InputStream-) | 初始化一个新的 [OlmStorage](../../com.aspose.email/olmstorage) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | 执行应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [enumerateMessages(OlmFolder folder)](#enumerateMessages-com.aspose.email.OlmFolder-) | 公开枚举器，支持对文件夹中消息的迭代。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractMapiMessage(OlmMessageInfo messageInfo)](#extractMapiMessage-com.aspose.email.OlmMessageInfo-) | 从 OLM 存储中获取消息。 |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | 从文件加载 OLM 存储。 |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | 从流加载 OLM。 |
| [getClass()](#getClass--) |  |
| [getFolder(String name, boolean ignoreCase)](#getFolder-java.lang.String-boolean-) | 按名称获取文件夹。 |
| [getFolderHierarchy()](#getFolderHierarchy--) | 获取文件夹层次结构。 |
| [getFolders()](#getFolders--) | 获取文件夹集合。 |
| [hashCode()](#hashCode--) |  |
| [load(InputStream stream)](#load-java.io.InputStream-) | 从流加载 OLM 存储。 |
| [load(String fileName)](#load-java.lang.String-) | 从文件加载 OLM 存储。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OlmStorage(TraversalExceptionsCallback callback) {#OlmStorage-com.aspose.email.TraversalExceptionsCallback-}
```
public OlmStorage(TraversalExceptionsCallback callback)
```


初始化一个新的 [OlmStorage](../../com.aspose.email/olmstorage) 类实例。允许设置回调方法以处理在 OLM 存储遍历期间发生的异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [TraversalExceptionsCallback](../../com.aspose.email/traversalexceptionscallback) | 异常回调。 |

### OlmStorage(String fileName) {#OlmStorage-java.lang.String-}
```
public OlmStorage(String fileName)
```


初始化一个新的 [OlmStorage](../../com.aspose.email/olmstorage) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | OLM 文件名。 |

### OlmStorage(InputStream stream) {#OlmStorage-java.io.InputStream-}
```
public OlmStorage(InputStream stream)
```


初始化一个新的 [OlmStorage](../../com.aspose.email/olmstorage) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含 OLM 存储数据的源流 java.io.InputStream。 |

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


执行应用程序定义的任务，以释放、释放或重置非托管资源。

### enumerateMessages(OlmFolder folder) {#enumerateMessages-com.aspose.email.OlmFolder-}
```
public final System.Collections.Generic.IGenericEnumerable<MapiMessage> enumerateMessages(OlmFolder folder)
```


公开枚举器，支持对文件夹中消息的迭代。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| folder | [OlmFolder](../../com.aspose.email/olmfolder) | 表示 OLM 存储中文件夹信息的 [OlmFolder](../../com.aspose.email/olmfolder)。 |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MapiMessage> -  System.Collections.Generic.IEnumerableltTgt , 表示一个枚举器，用于遍历文件夹中的消息。
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
### extractMapiMessage(OlmMessageInfo messageInfo) {#extractMapiMessage-com.aspose.email.OlmMessageInfo-}
```
public final MapiMessage extractMapiMessage(OlmMessageInfo messageInfo)
```


从 OLM 存储中获取消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| messageInfo | [OlmMessageInfo](../../com.aspose.email/olmmessageinfo) | 表示消息信息的 OlmMessageInfo 对象。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A MapiMessage object.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static OlmStorage fromFile(String fileName)
```


从文件加载 OLM 存储。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | .olm 文件的名称。 |

**Returns:**
[OlmStorage](../../com.aspose.email/olmstorage) - An OlmStorage object that represents the current OLM file.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static OlmStorage fromStream(InputStream stream)
```


从流加载 OLM。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | System.IO.Stream。 |

**Returns:**
[OlmStorage](../../com.aspose.email/olmstorage) - An OlmStorage object that represents the current OLM storage.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFolder(String name, boolean ignoreCase) {#getFolder-java.lang.String-boolean-}
```
public final OlmFolder getFolder(String name, boolean ignoreCase)
```


按名称获取文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 文件夹的名称。 |
| ignoreCase | boolean | 一个值，指示要匹配的名称是否不区分大小写。 |

**Returns:**
[OlmFolder](../../com.aspose.email/olmfolder) - An OlmFolder object.
### getFolderHierarchy() {#getFolderHierarchy--}
```
public final List<OlmFolder> getFolderHierarchy()
```


获取文件夹层次结构。

值：文件夹层次结构。

**Returns:**
java.util.List<com.aspose.email.OlmFolder>
### getFolders() {#getFolders--}
```
public final List<OlmFolder> getFolders()
```


获取文件夹集合。

**Returns:**
java.util.List<com.aspose.email.OlmFolder> - 属于存储的文件夹集合，即当前 OLMStorage 对象的子文件夹。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### load(InputStream stream) {#load-java.io.InputStream-}
```
public final boolean load(InputStream stream)
```


从流加载 OLM 存储。当使用带有 TraversalExceptionsCallback 参数的构造函数创建 OlmStorage 对象时使用此方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 流。 |

**Returns:**
boolean - 如果文件已成功加载且可以进一步遍历，则为 'true'；否则为 false。
### load(String fileName) {#load-java.lang.String-}
```
public final boolean load(String fileName)
```


从文件加载 OLM 存储。当使用带有 TraversalExceptionsCallback 参数的构造函数创建 OlmStorage 对象时使用此方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件名。 |

**Returns:**
boolean - 如果文件已成功加载且可以进一步遍历，则为 'true'；否则为 false。
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

