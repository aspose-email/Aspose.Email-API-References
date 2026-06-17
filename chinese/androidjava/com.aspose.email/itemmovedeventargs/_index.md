---
title: ItemMovedEventArgs
second_title: Aspose.Email for Android via Java API 参考
description: 提供事件的数据。
type: docs
weight: 169
url: /zh/androidjava/com.aspose.email/itemmovedeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ItemMovedEventArgs extends System.EventArgs
```

提供 [FolderInfo.ItemMovedDelegate](../../com.aspose.email/folderinfo\\#ItemMovedDelegate) 事件的数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ItemMovedEventArgs(MessageInfo message)](#ItemMovedEventArgs-com.aspose.email.MessageInfo-) | 初始化 [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) 类的新实例。 |
| [ItemMovedEventArgs(FolderInfo folder)](#ItemMovedEventArgs-com.aspose.email.FolderInfo-) | 初始化 [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) 类的新实例。 |
| [ItemMovedEventArgs(String entryId, MapiPropertyCollection properties)](#ItemMovedEventArgs-java.lang.String-com.aspose.email.MapiPropertyCollection-) | 初始化 [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [Empty](#Empty) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDestinationFolder()](#getDestinationFolder--) | 获取目标文件夹。 |
| [getEntryId()](#getEntryId--) | 获取表示已移动消息 EntryId 的字符串。 |
| [getItemProperties()](#getItemProperties--) | 获取已移动的项目属性。 |
| [hashCode()](#hashCode--) |  |
| [isFolder()](#isFolder--) | 如果条目引用文件夹，则返回 true |
| [isMessage()](#isMessage--) | 如果条目引用消息，则返回 true |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ItemMovedEventArgs(MessageInfo message) {#ItemMovedEventArgs-com.aspose.email.MessageInfo-}
```
public ItemMovedEventArgs(MessageInfo message)
```


初始化 [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MessageInfo](../../com.aspose.email/messageinfo) | 消息。 |

### ItemMovedEventArgs(FolderInfo folder) {#ItemMovedEventArgs-com.aspose.email.FolderInfo-}
```
public ItemMovedEventArgs(FolderInfo folder)
```


初始化 [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| folder | [FolderInfo](../../com.aspose.email/folderinfo) | 文件夹。 |

### ItemMovedEventArgs(String entryId, MapiPropertyCollection properties) {#ItemMovedEventArgs-java.lang.String-com.aspose.email.MapiPropertyCollection-}
```
public ItemMovedEventArgs(String entryId, MapiPropertyCollection properties)
```


初始化 [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | java.lang.String | 条目标识符。 |
| properties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | 属性。 |

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
### getDestinationFolder() {#getDestinationFolder--}
```
public final FolderInfo getDestinationFolder()
```


获取目标文件夹。

值：目标文件夹。

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo)
### getEntryId() {#getEntryId--}
```
public final String getEntryId()
```


获取表示已移动消息 EntryId 的字符串。

值：条目 ID。

**Returns:**
java.lang.String
### getItemProperties() {#getItemProperties--}
```
public final MapiPropertyCollection getItemProperties()
```


获取已移动的项目属性。

值：消息。

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFolder() {#isFolder--}
```
public final boolean isFolder()
```


如果条目引用文件夹，则返回 true

**Returns:**
boolean
### isMessage() {#isMessage--}
```
public final boolean isMessage()
```


如果条目引用消息，则返回 true

**Returns:**
boolean
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

