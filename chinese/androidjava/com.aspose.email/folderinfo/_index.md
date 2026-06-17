---
title: FolderInfo
second_title: Aspose.Email for Android via Java API 参考
description: 表示 PST 中个人文件夹的信息。
type: docs
weight: 141
url: /zh/androidjava/com.aspose.email/folderinfo/
---

**Inheritance:**
java.lang.Object
```
public final class FolderInfo
```

表示 PST 中个人文件夹的信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FolderInfo()](#FolderInfo--) | 初始化 [FolderInfo](../../com.aspose.email/folderinfo) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [ItemMoved](#ItemMoved) | 当项目移动到另一个文件夹时发生。 |
| [MessageAdded](#MessageAdded) | 当消息被添加到当前文件夹时触发。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addFile(String fileName, String messageClass)](#addFile-java.lang.String-java.lang.String-) | 向 pst 文件夹中添加文件。 |
| [addMapiMessageItem(IMapiMessageItem item)](#addMapiMessageItem-com.aspose.email.IMapiMessageItem-) | 将 IMapiMessageItem 对象添加到文件夹中。 |
| [addMessage(MapiMessage message)](#addMessage-com.aspose.email.MapiMessage-) | 向文件夹中添加新消息。 |
| [addMessages(Iterable<MapiMessage> messages)](#addMessages-java.lang.Iterable-com.aspose.email.MapiMessage--) | 提供批量模式下的消息添加。 |
| [addSubFolder(String name)](#addSubFolder-java.lang.String-) | 添加新的子文件夹。 |
| [addSubFolder(String name, boolean createHierarchy)](#addSubFolder-java.lang.String-boolean-) | 添加新的子文件夹。 |
| [addSubFolder(String name, String containerClass)](#addSubFolder-java.lang.String-java.lang.String-) | 添加新的子文件夹。 |
| [changeContainerClass(String containerClass)](#changeContainerClass-java.lang.String-) | 更改容器类。 |
| [changeDisplayName(String newName)](#changeDisplayName-java.lang.String-) | 更改显示名称。 |
| [changeMessages(MapiPropertyCollection updatedProperties)](#changeMessages-com.aspose.email.MapiPropertyCollection-) | 更改文件夹中的所有消息。 |
| [changeMessages(Iterable<String> entryIdCollection, MapiPropertyCollection updatedProperties)](#changeMessages-java.lang.Iterable-java.lang.String--com.aspose.email.MapiPropertyCollection-) | 更改文件夹中的消息。 |
| [deleteChildItem(byte[] entryId)](#deleteChildItem-byte---) | 根据其 entryId 删除项目（文件夹或消息）。 |
| [deleteChildItems(Iterable<String> entryIdCollection)](#deleteChildItems-java.lang.Iterable-java.lang.String--) | 删除子消息。 |
| [enumerateFolders()](#enumerateFolders--) | 公开枚举器，支持遍历文件夹中的子文件夹。 |
| [enumerateFolders(int kind)](#enumerateFolders-int-) | 公开枚举器，支持遍历文件夹中的子文件夹。 |
| [enumerateMapiMessages()](#enumerateMapiMessages--) | 公开枚举器，支持对文件夹中消息的迭代。 |
| [enumerateMessageObjects()](#enumerateMessageObjects--) | 公开枚举器，支持对文件夹中消息的迭代。 |
| [enumerateMessages()](#enumerateMessages--) | 公开枚举器，支持对文件夹中消息的迭代。 |
| [enumerateMessagesEntryId()](#enumerateMessagesEntryId--) | 枚举消息的 entryID。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainerClass()](#getContainerClass--) | 获取文件夹对象的容器类。 |
| [getContentCount()](#getContentCount--) | 获取文件夹中项目的总数。 |
| [getContentUnreadCount()](#getContentUnreadCount--) | 获取文件夹中未读项目的数量。 |
|  | [getContents()](#getContents--) | 获取消息集合。 |
此方法用于显示简要的消息信息 [MessageInfo](../../com.aspose.email/messageinfo)，如主题、发件人、收件人。 |
|  | [getContents(boolean tryToReadCorruptedContents)](#getContents-boolean-) | 获取消息集合。 |
此方法用于显示简要的消息信息 [MessageInfo](../../com.aspose.email/messageinfo)，如主题、发件人、收件人。 |
|  | [getContents(MailQuery query)](#getContents-com.aspose.email.MailQuery-) | 获取消息集合。 |
此方法用于显示简要的消息信息 [MessageInfo](../../com.aspose.email/messageinfo)，如主题、发件人、收件人。 |
|  | [getContents(int kind)](#getContents-int-) | 获取消息集合。 |
此方法用于显示简要的消息信息 [MessageInfo](../../com.aspose.email/messageinfo)，如主题、发件人、收件人。 |
|  | [getContents(int startIndex, int count)](#getContents-int-int-) | 获取消息集合。 |
此方法用于显示简要的消息信息 [MessageInfo](../../com.aspose.email/messageinfo)，如主题、发件人、收件人。 |
| [getDisplayName()](#getDisplayName--) | 获取文件夹的显示名称。 |
| [getEntryId()](#getEntryId--) | 获取条目 ID。 |
| [getEntryIdString()](#getEntryIdString--) | 获取条目 ID 的字符串表示形式。 |
| [getLastModificationTime()](#getLastModificationTime--) | 获取最后修改时间。 |
| [getProperties()](#getProperties--) | 获取文件夹属性。 |
| [getSubFolder(String name)](#getSubFolder-java.lang.String-) | 获取子文件夹。 |
| [getSubFolder(String name, boolean ignoreCase)](#getSubFolder-java.lang.String-boolean-) | 获取子文件夹。 |
| [getSubFolders()](#getSubFolders--) | 获取子文件夹集合。 |
| [getSubFolders(MailQuery query)](#getSubFolders-com.aspose.email.MailQuery-) | 获取子文件夹集合。 |
| [getSubFolders(int kind)](#getSubFolders-int-) | 获取子文件夹集合。 |
| [hasSubFolders()](#hasSubFolders--) | 获取一个值，指示 Folder 对象是否具有任何子文件夹。 |
| [hashCode()](#hashCode--) |  |
| [mergeWith(FolderInfo sourceFolder)](#mergeWith-com.aspose.email.FolderInfo-) | 将文件夹与另一个 pst 中的文件夹合并。 |
| [mergeWith(FolderInfo sourceFolder, boolean recursiveHandler)](#mergeWith-com.aspose.email.FolderInfo-boolean-) | 将文件夹与另一个 pst 中的文件夹合并。 |
| [moveContents(FolderInfo newFolder)](#moveContents-com.aspose.email.FolderInfo-) | 将内容移动到新的文件夹。 |
| [moveSubfolders(FolderInfo newFolder)](#moveSubfolders-com.aspose.email.FolderInfo-) | 将子文件夹移动到新的父文件夹。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [retrieveFullPath()](#retrieveFullPath--) | 检索 PST 文件中文件夹的完整路径。 |
| [toString()](#toString--) |  |
| [updateMessage(String entryId, MapiMessageItemBase updatedMessage)](#updateMessage-java.lang.String-com.aspose.email.MapiMessageItemBase-) | 更新文件夹中的消息。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FolderInfo() {#FolderInfo--}
```
public FolderInfo()
```


初始化 [FolderInfo](../../com.aspose.email/folderinfo) 类的新实例。

### ItemMoved {#ItemMoved}
```
public Event<ItemMovedEventHandler> ItemMoved
```


当项目移动到另一个文件夹时发生。

### MessageAdded {#MessageAdded}
```
public final Event<MessageAddedEventHandler> MessageAdded
```


当消息被添加到当前文件夹时触发。

### addFile(String fileName, String messageClass) {#addFile-java.lang.String-java.lang.String-}
```
public final String addFile(String fileName, String messageClass)
```


向 pst 文件夹中添加文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 需要添加的文件名。 |
| messageClass | java.lang.String | 消息类。 |

**Returns:**
java.lang.String - 表示已添加消息的 EntryId 的字符串。
### addMapiMessageItem(IMapiMessageItem item) {#addMapiMessageItem-com.aspose.email.IMapiMessageItem-}
```
public final String addMapiMessageItem(IMapiMessageItem item)
```


将 IMapiMessageItem 对象添加到文件夹中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMapiMessageItem](../../com.aspose.email/imapimessageitem) | 需要添加的项。 |

**Returns:**
java.lang.String - 表示已添加项的 EntryId 的字符串。
### addMessage(MapiMessage message) {#addMessage-com.aspose.email.MapiMessage-}
```
public final String addMessage(MapiMessage message)
```


向文件夹中添加新消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | 需要添加的消息。 |

**Returns:**
java.lang.String - 表示已添加消息的 EntryId 的字符串。
### addMessages(Iterable<MapiMessage> messages) {#addMessages-java.lang.Iterable-com.aspose.email.MapiMessage--}
```
public final void addMessages(Iterable<MapiMessage> messages)
```


提供批量模式下的消息添加。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MapiMessage> | 表示枚举器的 IEnumerator，支持遍历 [MapiMessage](../../com.aspose.email/mapimessage) 的集合。 |

### addSubFolder(String name) {#addSubFolder-java.lang.String-}
```
public final FolderInfo addSubFolder(String name)
```


添加新的子文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 子文件夹的名称。 |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new sub-folder.
### addSubFolder(String name, boolean createHierarchy) {#addSubFolder-java.lang.String-boolean-}
```
public final FolderInfo addSubFolder(String name, boolean createHierarchy)
```


添加新的子文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 子文件夹的名称。 |
| createHierarchy | boolean | 如果设置为 true，则可以使用字符串表示法创建文件夹层次结构。反斜杠 ('\\\\') 用作路径分隔符。 |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new sub-folder.
### addSubFolder(String name, String containerClass) {#addSubFolder-java.lang.String-java.lang.String-}
```
public final FolderInfo addSubFolder(String name, String containerClass)
```


添加新的子文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 子文件夹的名称。 |
| containerClass | java.lang.String | 子文件夹对象的容器类。 |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new subfolder.
### changeContainerClass(String containerClass) {#changeContainerClass-java.lang.String-}
```
public final void changeContainerClass(String containerClass)
```


更改容器类。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| containerClass | java.lang.String | 文件夹对象的容器类。 |

### changeDisplayName(String newName) {#changeDisplayName-java.lang.String-}
```
public final void changeDisplayName(String newName)
```


更改显示名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newName | java.lang.String | 一个新名称。 |

### changeMessages(MapiPropertyCollection updatedProperties) {#changeMessages-com.aspose.email.MapiPropertyCollection-}
```
public final void changeMessages(MapiPropertyCollection updatedProperties)
```


更改文件夹中的所有消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| updatedProperties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | 已更新的属性。 |

### changeMessages(Iterable<String> entryIdCollection, MapiPropertyCollection updatedProperties) {#changeMessages-java.lang.Iterable-java.lang.String--com.aspose.email.MapiPropertyCollection-}
```
public final void changeMessages(Iterable<String> entryIdCollection, MapiPropertyCollection updatedProperties)
```


更改文件夹中的消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryIdCollection | java.lang.Iterable<java.lang.String> | 条目标识符集合。 |
| updatedProperties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | 已更新的属性。 |

### deleteChildItem(byte[] entryId) {#deleteChildItem-byte---}
```
public final void deleteChildItem(byte[] entryId)
```


根据其 entryId 删除项目（文件夹或消息）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | entryId | byte[] | 条目 ID。 |

--------------------

该项必须包含在文件夹中。 |

### deleteChildItems(Iterable<String> entryIdCollection) {#deleteChildItems-java.lang.Iterable-java.lang.String--}
```
public final void deleteChildItems(Iterable<String> entryIdCollection)
```


删除子消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryIdCollection | java.lang.Iterable<java.lang.String> | 条目 ID 集合。 |

### enumerateFolders() {#enumerateFolders--}
```
public final System.Collections.Generic.IGenericEnumerable<FolderInfo> enumerateFolders()
```


公开枚举器，支持遍历文件夹中的子文件夹。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.FolderInfo> -  System.Collections.Generic.IEnumerableltTgt , 表示一个枚举器，用于遍历文件夹中的子文件夹。
### enumerateFolders(int kind) {#enumerateFolders-int-}
```
public final System.Collections.Generic.IGenericEnumerable<FolderInfo> enumerateFolders(int kind)
```


公开枚举器，支持遍历文件夹中的子文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| kind | int | 表示文件夹种类的 [FolderKind](../../com.aspose.email/folderkind)。 |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.FolderInfo> -  System.Collections.Generic.IEnumerableltTgt , 表示一个枚举器，用于遍历文件夹中的子文件夹。
### enumerateMapiMessages() {#enumerateMapiMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MapiMessage> enumerateMapiMessages()
```


公开枚举器，支持对文件夹中消息的迭代。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MapiMessage> -  System.Collections.Generic.IEnumerableltTgt , 表示一个枚举器，用于遍历文件夹中的消息。
### enumerateMessageObjects() {#enumerateMessageObjects--}
```
public final System.Collections.Generic.IGenericEnumerable<MessageObject> enumerateMessageObjects()
```


公开枚举器，支持对文件夹中消息的迭代。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageObject> -  System.Collections.Generic.IEnumerableltTgt , 表示一个枚举器，用于遍历文件夹中的消息。
### enumerateMessages() {#enumerateMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages()
```


公开枚举器，支持对文件夹中消息的迭代。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> - System.Collections.Generic.IEnumerableltTgt，表示遍历文件夹中消息的枚举器。
### enumerateMessagesEntryId() {#enumerateMessagesEntryId--}
```
public final System.Collections.Generic.IGenericEnumerable<String> enumerateMessagesEntryId()
```


枚举消息的 entryID。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<java.lang.String> -  System.Collections.Generic.IEnumerableltTgt , 表示一个枚举器，用于遍历文件夹中消息的 entryID。
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
### getContainerClass() {#getContainerClass--}
```
public final String getContainerClass()
```


获取文件夹对象的容器类。

值：容器类。

**Returns:**
java.lang.String
### getContentCount() {#getContentCount--}
```
public final int getContentCount()
```


获取文件夹中项目的总数。

值：内容计数。

**Returns:**
int
### getContentUnreadCount() {#getContentUnreadCount--}
```
public final int getContentUnreadCount()
```


获取文件夹中未读项目的数量。

值：未读内容计数。

**Returns:**
int
### getContents() {#getContents--}
```
public final MessageInfoCollection getContents()
```


获取消息集合。
此方法用于显示简要的消息信息 [MessageInfo](../../com.aspose.email/messageinfo)，如主题、发件人、收件人。就性能而言，这是获取消息主要信息的最合适选项。若要提取完整的消息数据，提供了 [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-) 方法。

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getContents(boolean tryToReadCorruptedContents) {#getContents-boolean-}
```
public final MessageInfoCollection getContents(boolean tryToReadCorruptedContents)
```


获取消息集合。
此方法用于显示简要的消息信息 [MessageInfo](../../com.aspose.email/messageinfo)，如主题、发件人、收件人。就性能而言，这是获取消息主要信息的最合适选项。若要提取完整的消息数据，提供了 [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-) 方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tryToReadCorruptedContents | boolean | 如果此参数的值为 true，方法将在文件损坏的情况下仍尝试读取内容。如果 GetContents() 方法因文件损坏抛出异常，可使用此值。如果此参数的值为 false，方法的行为与不带参数的 GetContents() 方法相同。 |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getContents(MailQuery query) {#getContents-com.aspose.email.MailQuery-}
```
public final MessageInfoCollection getContents(MailQuery query)
```


获取消息集合。
此方法用于显示简要的消息信息 [MessageInfo](../../com.aspose.email/messageinfo)，如主题、发件人、收件人。就性能而言，这是获取消息主要信息的最合适选项。若要提取完整的消息数据，提供了 [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-) 方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | 表示搜索查询的 [MailQuery](../../com.aspose.email/mailquery)。 |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getContents(int kind) {#getContents-int-}
```
public final MessageInfoCollection getContents(int kind)
```


获取消息集合。
此方法用于显示简要的消息信息 [MessageInfo](../../com.aspose.email/messageinfo)，如主题、发件人、收件人。就性能而言，这是获取消息主要信息的最合适选项。若要提取完整的消息数据，提供了 [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-) 方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 种类 | int | 消息类型。 |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getContents(int startIndex, int count) {#getContents-int-int-}
```
public final MessageInfoCollection getContents(int startIndex, int count)
```


获取消息集合。
此方法用于显示简要的消息信息 [MessageInfo](../../com.aspose.email/messageinfo)，如主题、发件人、收件人。就性能而言，这是获取消息主要信息的最合适选项。若要提取完整的消息数据，提供了 [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-) 方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 起始消息索引。 |
|  | count | int | 将检索的消息数量。 |

--------------------

如果 "count" 参数小于 0 或大于剩余的消息数，则返回剩余的消息数。 |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


获取文件夹的显示名称。

值：显示名称。

**Returns:**
java.lang.String
### getEntryId() {#getEntryId--}
```
public final byte[] getEntryId()
```


获取条目 ID。

值：条目 ID。

**Returns:**
byte[]
### getEntryIdString() {#getEntryIdString--}
```
public final String getEntryIdString()
```


获取条目 ID 的字符串表示形式。

值：条目 ID 字符串。

**Returns:**
java.lang.String
### getLastModificationTime() {#getLastModificationTime--}
```
public final Date getLastModificationTime()
```


获取最后修改时间。

值：最后修改时间。如果文件夹没有 PR\_LAST\_MODIFICATION\_TIME 属性，则返回 DateTime.MinValue。

**Returns:**
java.util.Date
### getProperties() {#getProperties--}
```
public final MapiPropertyCollection getProperties()
```


获取文件夹属性。

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getSubFolder(String name) {#getSubFolder-java.lang.String-}
```
public final FolderInfo getSubFolder(String name)
```


获取子文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 子文件夹的名称。 |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A FolderInfo object.
### getSubFolder(String name, boolean ignoreCase) {#getSubFolder-java.lang.String-boolean-}
```
public final FolderInfo getSubFolder(String name, boolean ignoreCase)
```


获取子文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 子文件夹的名称。 |
| ignoreCase | boolean | 指示在匹配文件夹名称时搜索应忽略大小写敏感性。 |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A FolderInfo object.
### getSubFolders() {#getSubFolders--}
```
public final FolderInfoCollection getSubFolders()
```


获取子文件夹集合。

**Returns:**
[FolderInfoCollection](../../com.aspose.email/folderinfocollection) - The FolderInfo collection.
### getSubFolders(MailQuery query) {#getSubFolders-com.aspose.email.MailQuery-}
```
public final FolderInfoCollection getSubFolders(MailQuery query)
```


获取子文件夹集合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | 表示搜索查询的 [MailQuery](../../com.aspose.email/mailquery)。 |

**Returns:**
[FolderInfoCollection](../../com.aspose.email/folderinfocollection) - The FolderInfo collection.
### getSubFolders(int kind) {#getSubFolders-int-}
```
public final FolderInfoCollection getSubFolders(int kind)
```


获取子文件夹集合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| kind | int | 表示文件夹种类的 [FolderKind](../../com.aspose.email/folderkind)。 |

**Returns:**
[FolderInfoCollection](../../com.aspose.email/folderinfocollection) - The FolderInfo collection.
### hasSubFolders() {#hasSubFolders--}
```
public final boolean hasSubFolders()
```


获取一个值，指示 Folder 对象是否具有任何子文件夹。

值：该文件夹有子文件夹。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mergeWith(FolderInfo sourceFolder) {#mergeWith-com.aspose.email.FolderInfo-}
```
public final void mergeWith(FolderInfo sourceFolder)
```


将文件夹与另一个 pst 中的文件夹合并。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFolder | [FolderInfo](../../com.aspose.email/folderinfo) | 源文件夹。 |

### mergeWith(FolderInfo sourceFolder, boolean recursiveHandler) {#mergeWith-com.aspose.email.FolderInfo-boolean-}
```
public final void mergeWith(FolderInfo sourceFolder, boolean recursiveHandler)
```


将文件夹与另一个 pst 中的文件夹合并。OnItemMoved 事件将在消息和目录上均被调用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFolder | [FolderInfo](../../com.aspose.email/folderinfo) | 源文件夹。 |
| recursiveHandler | boolean | 如果为 true，OnItemMoved 将在所有消息上被调用，包括子目录中的消息；否则，OnItemMoved 仅在当前目录中的消息上被调用。 |

### moveContents(FolderInfo newFolder) {#moveContents-com.aspose.email.FolderInfo-}
```
public final void moveContents(FolderInfo newFolder)
```


将内容移动到新的文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | 新文件夹。 |

### moveSubfolders(FolderInfo newFolder) {#moveSubfolders-com.aspose.email.FolderInfo-}
```
public final void moveSubfolders(FolderInfo newFolder)
```


将子文件夹移动到新的父文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | 新的父文件夹。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### retrieveFullPath() {#retrieveFullPath--}
```
public final String retrieveFullPath()
```


检索 PST 文件中文件夹的完整路径。

**Returns:**
java.lang.String - 表示完整路径的字符串。
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateMessage(String entryId, MapiMessageItemBase updatedMessage) {#updateMessage-java.lang.String-com.aspose.email.MapiMessageItemBase-}
```
public final void updateMessage(String entryId, MapiMessageItemBase updatedMessage)
```


更新文件夹中的消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | java.lang.String | 消息条目标识符。 |
| updatedMessage | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | 已更新的消息。 |

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

