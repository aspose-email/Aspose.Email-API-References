---
title: MessageAddedEventArgs
second_title: Aspose.Email for Android via Java API 参考
description: 提供事件的数据。
type: docs
weight: 303
url: /zh/androidjava/com.aspose.email/messageaddedeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class MessageAddedEventArgs extends System.EventArgs
```

提供用于 [FolderInfo.MessageAddedDelegate](../../com.aspose.email/folderinfo\#MessageAddedDelegate) 事件的数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MessageAddedEventArgs(String entryId, MapiMessage message)](#MessageAddedEventArgs-java.lang.String-com.aspose.email.MapiMessage-) | 初始化 [MessageAddedEventArgs](../../com.aspose.email/messageaddedeventargs) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [Empty](#Empty) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEntryId()](#getEntryId--) | 获取表示已添加消息的 EntryId 的字符串。 |
| [getMessage()](#getMessage--) | 获取已添加的消息。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageAddedEventArgs(String entryId, MapiMessage message) {#MessageAddedEventArgs-java.lang.String-com.aspose.email.MapiMessage-}
```
public MessageAddedEventArgs(String entryId, MapiMessage message)
```


初始化 [MessageAddedEventArgs](../../com.aspose.email/messageaddedeventargs) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | java.lang.String | 条目 ID。 |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 消息。 |

### Empty {#Empty}
```
public static final System.EventArgs Empty
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
### getEntryId() {#getEntryId--}
```
public final String getEntryId()
```


获取表示已添加消息的 EntryId 的字符串。

值：条目 ID。

**Returns:**
java.lang.String
### getMessage() {#getMessage--}
```
public final MapiMessage getMessage()
```


获取已添加的消息。

值：消息。

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage)
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

