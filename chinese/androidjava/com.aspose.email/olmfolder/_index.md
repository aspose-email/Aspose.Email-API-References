---
title: OlmFolder
second_title: Aspose.Email for Android via Java API 参考
description: 表示 OLM 存储中的文件夹信息。
type: docs
weight: 337
url: /zh/androidjava/com.aspose.email/olmfolder/
---

**Inheritance:**
java.lang.Object
```
public class OlmFolder
```

表示 OLM 存储中的文件夹信息。
## 方法

| 方法 | 描述 |
| --- | --- |
| [enumerateMapiMessages()](#enumerateMapiMessages--) | 公开枚举器，支持对文件夹中消息的迭代。 |
| [enumerateMessages()](#enumerateMessages--) | 公开枚举器，支持对文件夹中消息的迭代。 |
| [enumerateMessages(MailQuery query)](#enumerateMessages-com.aspose.email.MailQuery-) | 公开枚举器，支持对文件夹中消息的迭代。 |
| [enumerateMessages(int startIndex, int count)](#enumerateMessages-int-int-) | 公开枚举器，支持对文件夹中消息的迭代。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMessageCount()](#getMessageCount--) | 获取消息计数。 |
| [getName()](#getName--) | 获取文件夹名称。 |
| [getPath()](#getPath--) | 获取路径。 |
| [getSubFolder(String subfolderName, boolean ignoreCase)](#getSubFolder-java.lang.String-boolean-) | 按名称获取子文件夹。 |
| [getSubFolders()](#getSubFolders--) | 获取子文件夹列表。 |
| [hasMessages()](#hasMessages--) | 获取一个值，指示当前文件夹是否包含消息。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回表示此实例的 String。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### enumerateMapiMessages() {#enumerateMapiMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MapiMessage> enumerateMapiMessages()
```


公开枚举器，支持对文件夹中消息的迭代。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MapiMessage> -  System.Collections.Generic.IEnumerableltTgt , 表示一个枚举器，用于遍历文件夹中的消息。
### enumerateMessages() {#enumerateMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<OlmMessageInfo> enumerateMessages()
```


公开枚举器，支持对文件夹中消息的迭代。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.OlmMessageInfo> -  System.Collections.Generic.IEnumerableltTgt ，它表示一个枚举器，用于遍历文件夹中的消息。
### enumerateMessages(MailQuery query) {#enumerateMessages-com.aspose.email.MailQuery-}
```
public final System.Collections.Generic.IGenericEnumerable<OlmMessageInfo> enumerateMessages(MailQuery query)
```


公开枚举器，支持对文件夹中消息的迭代。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | 表示搜索查询的 [MailQuery](../../com.aspose.email/mailquery)。 |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.OlmMessageInfo> -  System.Collections.Generic.IEnumerableltTgt ，它表示一个枚举器，用于遍历文件夹中的消息。
### enumerateMessages(int startIndex, int count) {#enumerateMessages-int-int-}
```
public final System.Collections.Generic.IGenericEnumerable<OlmMessageInfo> enumerateMessages(int startIndex, int count)
```


公开枚举器，支持对文件夹中消息的迭代。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 起始消息索引。 |
|  | count | int | 将检索的消息数量。 |

--------------------

如果 "count" 参数小于 0 或大于剩余的消息数，则返回剩余的消息数。 |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.OlmMessageInfo> -  System.Collections.Generic.IEnumerableltTgt ，它表示一个枚举器，用于遍历文件夹中的消息。
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
### getMessageCount() {#getMessageCount--}
```
public final int getMessageCount()
```


获取消息计数。

值：消息计数。

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


获取文件夹名称。

值：名称。

**Returns:**
java.lang.String
### getPath() {#getPath--}
```
public final String getPath()
```


获取路径。

值：文件夹路径。

**Returns:**
java.lang.String
### getSubFolder(String subfolderName, boolean ignoreCase) {#getSubFolder-java.lang.String-boolean-}
```
public final OlmFolder getSubFolder(String subfolderName, boolean ignoreCase)
```


按名称获取子文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subfolderName | java.lang.String | 子文件夹的名称。 |
| ignoreCase | boolean | 一个值，指示要匹配的名称是否不区分大小写。 |

**Returns:**
[OlmFolder](../../com.aspose.email/olmfolder) - An OlmFolder object.
### getSubFolders() {#getSubFolders--}
```
public final List<OlmFolder> getSubFolders()
```


获取子文件夹列表。

值：子文件夹列表。

**Returns:**
java.util.List<com.aspose.email.OlmFolder>
### hasMessages() {#hasMessages--}
```
public final boolean hasMessages()
```


获取一个值，指示当前文件夹是否包含消息。

**Returns:**
boolean - 如果当前文件夹有消息则为 true；否则为 false。
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


返回表示此实例的 String。

**Returns:**
java.lang.String - 表示此实例的 String。
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

