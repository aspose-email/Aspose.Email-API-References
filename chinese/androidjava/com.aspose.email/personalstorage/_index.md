---
title: PersonalStorage
second_title: Aspose.Email for Android via Java API 参考
description: 表示 Personal Storage Table .pst 文件。
type: docs
weight: 344
url: /zh/androidjava/com.aspose.email/personalstorage/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class PersonalStorage implements System.IDisposable, Closeable
```

表示个人存储表（.pst）文件。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PersonalStorage(TraversalExceptionsCallback callback)](#PersonalStorage-com.aspose.email.TraversalExceptionsCallback-) | 初始化 [PersonalStorage](../../com.aspose.email/personalstorage) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [ItemMoved](#ItemMoved) | 当项目移动到另一个文件夹时发生。 |
| [StorageProcessed](#StorageProcessed) | 在拆分和合并操作中，当创建新的 pst 块或处理下一个文件并进行合并时发生。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [canWrite()](#canWrite--) | 获取一个值，指示当前 pst 是否支持写入。 |
| [changeMessage(String entryId, MapiPropertyCollection updatedProperties)](#changeMessage-java.lang.String-com.aspose.email.MapiPropertyCollection-) | 更改消息属性。 |
| [close()](#close--) |  |
| [convertTo(int format)](#convertTo-int-) | 将当前对象转换为指定的格式。 |
| [create(System.IO.Stream stream, int version)](#create-com.aspose.ms.System.IO.Stream-int-) | 在流中创建 PST。 |
| [create(System.IO.Stream stream, int version, boolean leaveStreamOpen)](#create-com.aspose.ms.System.IO.Stream-int-boolean-) | 在流中创建 PST。 |
| [create(OutputStream stream, int version)](#create-java.io.OutputStream-int-) | 在流中创建 PST。 |
| [create(OutputStream stream, int version, boolean leaveStreamOpen)](#create-java.io.OutputStream-int-boolean-) | 在流中创建 PST。 |
| [create(OutputStream stream, int blockSize, int version)](#create-java.io.OutputStream-int-int-) | 在流中创建 PST。 |
| [create(String fileName, int version)](#create-java.lang.String-int-) | 使用指定的文件名创建新的 PST 文件。 |
| [createPredefinedFolder(String name, int defaultFolder)](#createPredefinedFolder-java.lang.String-int-) | 创建标准的个人间消息 (IPM) 文件夹。 |
| [createPredefinedFolder(String name, int defaultFolder, boolean createHierarchy)](#createPredefinedFolder-java.lang.String-int-boolean-) | 创建标准的个人间消息 (IPM) 文件夹。 |
| [dispose()](#dispose--) | 执行应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [enumerateMessages(String entryId)](#enumerateMessages-java.lang.String-) | 公开枚举器，支持对文件夹中消息的迭代。 |
| [enumerateMessages(String entryId, int startIndex, int count)](#enumerateMessages-java.lang.String-int-int-) | 公开枚举器，支持对文件夹中消息的迭代。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractAttachments(MessageInfo messageInfo)](#extractAttachments-com.aspose.email.MessageInfo-) | 提取附件。 |
| [extractAttachments(String entryId)](#extractAttachments-java.lang.String-) | 提取附件。 |
| [extractMessage(byte[] entryId)](#extractMessage-byte---) | 从 PST 获取消息。 |
| [extractMessage(MessageInfo messageInfo)](#extractMessage-com.aspose.email.MessageInfo-) | 从 PST 获取消息。 |
| [extractMessage(String entryId)](#extractMessage-java.lang.String-) | 从 PST 获取消息。 |
| [extractProperty(byte[] entryId, long tag)](#extractProperty-byte---long-) | 获取项目的指定属性，而不完全提取该项目。 |
| [findMessages(String parentEntryId)](#findMessages-java.lang.String-) | 查找当前文件夹中消息的标识符。 |
| [findSubfolders(String parentEntryId)](#findSubfolders-java.lang.String-) | 查找当前文件夹中子文件夹的标识符。 |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | 从文件加载 PST。 |
| [fromFile(String fileName, boolean writable)](#fromFile-java.lang.String-boolean-) | 从文件加载 PST。 |
| [fromFile(String fileName, PersonalStorageLoadOptions loadOptions)](#fromFile-java.lang.String-com.aspose.email.PersonalStorageLoadOptions-) | 从文件加载 PST。 |
| [fromStream(System.IO.Stream stream)](#fromStream-com.aspose.ms.System.IO.Stream-) | 从流加载 PST。 |
| [fromStream(System.IO.Stream stream, boolean writable)](#fromStream-com.aspose.ms.System.IO.Stream-boolean-) | 从流加载 PST。 |
| [fromStream(System.IO.Stream stream, PersonalStorageLoadOptions loadOptions)](#fromStream-com.aspose.ms.System.IO.Stream-com.aspose.email.PersonalStorageLoadOptions-) | 从流加载 PST。 |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | 从流加载 PST。 |
| [fromStream(InputStream stream, boolean writable)](#fromStream-java.io.InputStream-boolean-) | 从流加载 PST。 |
| [fromStream(InputStream stream, PersonalStorageLoadOptions loadOptions)](#fromStream-java.io.InputStream-com.aspose.email.PersonalStorageLoadOptions-) | 从流加载 PST。 |
| [getClass()](#getClass--) |  |
| [getFolderById(byte[] entryId)](#getFolderById-byte---) | 获取 PST 中的个人文件夹。 |
| [getFolderById(String entryIdString)](#getFolderById-java.lang.String-) | 获取 PST 中的个人文件夹。 |
| [getFormat()](#getFormat--) | 获取文件格式。 |
| [getParentFolder(byte[] entryId)](#getParentFolder-byte---) | 获取消息的父文件夹。 |
| [getParentFolder(String entryIdString)](#getParentFolder-java.lang.String-) | 获取消息的父文件夹。 |
| [getPredefinedFolder(int defaultFolder)](#getPredefinedFolder-int-) | 从 PST 获取标准交互式消息 (IPM) 文件夹。 |
| [getRootFolder()](#getRootFolder--) | 获取 PST 的根文件夹。 |
| [getStore()](#getStore--) | 获取 PST 消息存储。 |
| [hashCode()](#hashCode--) |  |
| [isUnicode()](#isUnicode--) | 获取一个值，指示 PST 文件格式是否为 Unicode。 |
| [load(System.IO.Stream stream)](#load-com.aspose.ms.System.IO.Stream-) | 从流加载 PST。 |
| [load(InputStream stream)](#load-java.io.InputStream-) | 从流加载 PST。 |
| [load(String fileName)](#load-java.lang.String-) | 从文件加载 PST。 |
| [mergeWith(InputStream[] sourceStreams)](#mergeWith-java.io.InputStream---) | 将 pst 存储与一个或多个其他 pst 流合并。 |
| [mergeWith(String[] sourceFileNames)](#mergeWith-java.lang.String---) | 将 pst 存储与一个或多个其他 pst 文件合并。 |
| [moveItem(FolderInfo folder, FolderInfo newFolder)](#moveItem-com.aspose.email.FolderInfo-com.aspose.email.FolderInfo-) | 将指定文件夹移动到当前 pst 中的新父文件夹。 |
| [moveItem(MessageInfo message, FolderInfo newFolder)](#moveItem-com.aspose.email.MessageInfo-com.aspose.email.FolderInfo-) | 将指定消息移动到当前 pst 中的新文件夹。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveAs(OutputStream stream, int format)](#saveAs-java.io.OutputStream-int-) | 将当前对象保存为流中的指定文件格式。 |
| [saveAs(String fileName, int format)](#saveAs-java.lang.String-int-) | 将当前对象保存为不同文件中的指定文件格式。 |
| [saveMessageToFile(String entryId, String fileName)](#saveMessageToFile-java.lang.String-java.lang.String-) | saveMessageToFile。 |
| [saveMessageToStream(String entryId, OutputStream stream)](#saveMessageToStream-java.lang.String-java.io.OutputStream-) | 将消息（使用指定的 entryID）保存到流中。 |
| [splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String path)](#splitInto-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.email.MailQuery--java.lang.String-) | 根据条件拆分 pst 存储。 |
| [splitInto(long chunkSize, String path)](#splitInto-long-java.lang.String-) | 将 pst 存储拆分为更小的部分。 |
| [toString()](#toString--) |  |
| [tryToGetFolderById(String entryIdString, FolderInfo[] folder)](#tryToGetFolderById-java.lang.String-com.aspose.email.FolderInfo---) | 获取与指定 entry ID 关联的文件夹。 |
| [tryToSaveMessage(String entryId, OutputStream stream)](#tryToSaveMessage-java.lang.String-java.io.OutputStream-) | 将消息（使用指定的 entryID）保存到流中。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PersonalStorage(TraversalExceptionsCallback callback) {#PersonalStorage-com.aspose.email.TraversalExceptionsCallback-}
```
public PersonalStorage(TraversalExceptionsCallback callback)
```


初始化 [PersonalStorage](../../com.aspose.email/personalstorage) 类的新实例。允许设置回调方法来处理在 PST 遍历期间发生的异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [TraversalExceptionsCallback](../../com.aspose.email/traversalexceptionscallback) | 异常回调。 |

### ItemMoved {#ItemMoved}
```
public final Event<ItemMovedEventHandler> ItemMoved
```


当项目移动到另一个文件夹时发生。

### StorageProcessed {#StorageProcessed}
```
public final Event<StorageProcessedEventHandler> StorageProcessed
```


在拆分和合并操作中，当创建新的 pst 块或处理下一个文件并进行合并时发生。

### canWrite() {#canWrite--}
```
public final boolean canWrite()
```


获取一个值，指示当前 pst 是否支持写入。

**Returns:**
boolean
### changeMessage(String entryId, MapiPropertyCollection updatedProperties) {#changeMessage-java.lang.String-com.aspose.email.MapiPropertyCollection-}
```
public final void changeMessage(String entryId, MapiPropertyCollection updatedProperties)
```


更改消息属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | java.lang.String | 消息的 entry 标识符。 |
| updatedProperties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | 已更新的属性。 |

### close() {#close--}
```
public void close()
```




### convertTo(int format) {#convertTo-int-}
```
public final void convertTo(int format)
```


将当前对象转换为指定的格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 格式 | int | 要将当前对象转换为的 FileFormat。 |

### create(System.IO.Stream stream, int version) {#create-com.aspose.ms.System.IO.Stream-int-}
```
public static PersonalStorage create(System.IO.Stream stream, int version)
```


在流中创建 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 创建 PST 的流。 |
|  | 版本 | int | PST 文件版本。 |

--------------------

注意，仅支持创建 Unicode 文件版本。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(System.IO.Stream stream, int version, boolean leaveStreamOpen) {#create-com.aspose.ms.System.IO.Stream-int-boolean-}
```
public static PersonalStorage create(System.IO.Stream stream, int version, boolean leaveStreamOpen)
```


在流中创建 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 创建 PST 的流。 |
| 版本 | int | PST 文件版本。 |
|  | leaveStreamOpen | boolean | 在释放 PersonalStorage 时保持流打开。 |

--------------------

注意，仅支持创建 Unicode 文件版本。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(OutputStream stream, int version) {#create-java.io.OutputStream-int-}
```
public static PersonalStorage create(OutputStream stream, int version)
```


在流中创建 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 创建 PST 的流。 |
|  | 版本 | int | PST 文件版本。 |

--------------------

注意，仅支持创建 Unicode 文件版本。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(OutputStream stream, int version, boolean leaveStreamOpen) {#create-java.io.OutputStream-int-boolean-}
```
public static PersonalStorage create(OutputStream stream, int version, boolean leaveStreamOpen)
```


在流中创建 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 创建 PST 的流。 |
| 版本 | int | PST 文件版本。 |
|  | leaveStreamOpen | boolean | 在释放 PersonalStorage 时保持流打开。 |

--------------------

注意，仅支持创建 Unicode 文件版本。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(OutputStream stream, int blockSize, int version) {#create-java.io.OutputStream-int-int-}
```
public static PersonalStorage create(OutputStream stream, int blockSize, int version)
```


在流中创建 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 创建 PST 的流。 |
| blockSize | int | 用于扩展缓存缓冲区的最佳块大小（单位：字节）。 |
|  | 版本 | int | PST 文件版本。 |

--------------------

注意，仅支持创建 Unicode 文件版本。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(String fileName, int version) {#create-java.lang.String-int-}
```
public static PersonalStorage create(String fileName, int version)
```


使用指定的文件名创建新的 PST 文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件的完整名称。 |
|  | 版本 | int | PST 文件版本。 |

--------------------

注意，仅支持创建 Unicode 文件版本。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### createPredefinedFolder(String name, int defaultFolder) {#createPredefinedFolder-java.lang.String-int-}
```
public final FolderInfo createPredefinedFolder(String name, int defaultFolder)
```


创建标准的个人间消息 (IPM) 文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 文件夹的名称。 |
| defaultFolder | int | [StandardIpmFolder](../../com.aspose.email/standardipmfolder) 枚举的值。 |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A [FolderInfo](../../com.aspose.email/folderinfo) object that represents a standard IPM folder.
### createPredefinedFolder(String name, int defaultFolder, boolean createHierarchy) {#createPredefinedFolder-java.lang.String-int-boolean-}
```
public final FolderInfo createPredefinedFolder(String name, int defaultFolder, boolean createHierarchy)
```


创建标准的个人间消息 (IPM) 文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 文件夹的名称。 |
| defaultFolder | int | [StandardIpmFolder](../../com.aspose.email/standardipmfolder) 枚举的值。 |
| createHierarchy | boolean | 如果设置为 true，则可以使用字符串表示法创建文件夹层次结构。反斜杠 ('\\\\') 用作路径分隔符。 |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A [FolderInfo](../../com.aspose.email/folderinfo) object that represents a standard IPM folder.
### dispose() {#dispose--}
```
public final void dispose()
```


执行应用程序定义的任务，以释放、释放或重置非托管资源。

### enumerateMessages(String entryId) {#enumerateMessages-java.lang.String-}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages(String entryId)
```


公开枚举器，支持对文件夹中消息的迭代。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | java.lang.String | 表示父文件夹条目 ID 的字符串。 |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> - System.Collections.Generic.IEnumerableltTgt，表示遍历文件夹中消息的枚举器。
### enumerateMessages(String entryId, int startIndex, int count) {#enumerateMessages-java.lang.String-int-int-}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages(String entryId, int startIndex, int count)
```


公开枚举器，支持对文件夹中消息的迭代。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | java.lang.String | 表示父文件夹条目 ID 的字符串。 |
| startIndex | int | 起始消息索引。 |
| count | int | 将检索的消息数量。 |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> - System.Collections.Generic.IEnumerableltTgt，表示遍历文件夹中消息的枚举器。
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
### extractAttachments(MessageInfo messageInfo) {#extractAttachments-com.aspose.email.MessageInfo-}
```
public final MapiAttachmentCollection extractAttachments(MessageInfo messageInfo)
```


提取附件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| messageInfo | [MessageInfo](../../com.aspose.email/messageinfo) | 消息信息。 |

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) that represents the collection of attachments.
### extractAttachments(String entryId) {#extractAttachments-java.lang.String-}
```
public final MapiAttachmentCollection extractAttachments(String entryId)
```


提取附件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | java.lang.String | 消息 entryId。 |

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) that represents the collection of attachments.
### extractMessage(byte[] entryId) {#extractMessage-byte---}
```
public final MapiMessage extractMessage(byte[] entryId)
```


从 PST 获取消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | byte[] | 消息的 EntryId。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A MapiMessage object.
### extractMessage(MessageInfo messageInfo) {#extractMessage-com.aspose.email.MessageInfo-}
```
public final MapiMessage extractMessage(MessageInfo messageInfo)
```


从 PST 获取消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| messageInfo | [MessageInfo](../../com.aspose.email/messageinfo) | 表示消息信息的 MessageInfo 对象。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A MapiMessage object.
### extractMessage(String entryId) {#extractMessage-java.lang.String-}
```
public final MapiMessage extractMessage(String entryId)
```


从 PST 获取消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | java.lang.String | EntryId 的字符串表示。 |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A MapiMessage object.
### extractProperty(byte[] entryId, long tag) {#extractProperty-byte---long-}
```
public final MapiProperty extractProperty(byte[] entryId, long tag)
```


获取项目的指定属性，而不完全提取该项目。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | byte[] | 项的 entry id。 |
|  | tag | long | 属性标签。 |

--------------------

如果未找到属性，则返回 null。 |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The MapiProperty.
### findMessages(String parentEntryId) {#findMessages-java.lang.String-}
```
public final System.Collections.Generic.IGenericList<String> findMessages(String parentEntryId)
```


查找当前文件夹中消息的标识符。如果在读取损坏的 pst 时 GetContents 和 EnumerateMessages 方法可能抛出异常，这可能会有用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parentEntryId | java.lang.String | 父文件夹的条目 ID。 |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.String> - 条目 ID 的集合。
### findSubfolders(String parentEntryId) {#findSubfolders-java.lang.String-}
```
public final System.Collections.Generic.IGenericList<String> findSubfolders(String parentEntryId)
```


查找当前文件夹中子文件夹的标识符。如果在读取损坏的 pst 时 GetSubfolders 和 EnumerateFolders 方法可能抛出异常，这可能会有用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parentEntryId | java.lang.String | 父文件夹的条目 ID。 |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.String> - 条目 ID 的集合。
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static PersonalStorage fromFile(String fileName)
```


从文件加载 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileName | java.lang.String | .pst 文件的名称。 |

--------------------

默认情况下，pst 将支持写入。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromFile(String fileName, boolean writable) {#fromFile-java.lang.String-boolean-}
```
public static PersonalStorage fromFile(String fileName, boolean writable)
```


从文件加载 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | .pst 文件的名称。 |
| writable | boolean | 如果设置为 true，则 pst 文件将支持写入，否则将以只读模式打开。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromFile(String fileName, PersonalStorageLoadOptions loadOptions) {#fromFile-java.lang.String-com.aspose.email.PersonalStorageLoadOptions-}
```
public static PersonalStorage fromFile(String fileName, PersonalStorageLoadOptions loadOptions)
```


从文件加载 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | .pst 文件的名称。 |
| loadOptions | [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) | 加载选项。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(System.IO.Stream stream) {#fromStream-com.aspose.ms.System.IO.Stream-}
```
public static PersonalStorage fromStream(System.IO.Stream stream)
```


从流加载 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | System.IO.Stream。 |

--------------------

默认情况下，pst 将支持写入。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(System.IO.Stream stream, boolean writable) {#fromStream-com.aspose.ms.System.IO.Stream-boolean-}
```
public static PersonalStorage fromStream(System.IO.Stream stream, boolean writable)
```


从流加载 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | System.IO.Stream。 |
| writable | boolean | 如果设置为 true，则 pst 文件将支持写入，否则将以只读模式打开。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(System.IO.Stream stream, PersonalStorageLoadOptions loadOptions) {#fromStream-com.aspose.ms.System.IO.Stream-com.aspose.email.PersonalStorageLoadOptions-}
```
public static PersonalStorage fromStream(System.IO.Stream stream, PersonalStorageLoadOptions loadOptions)
```


从流加载 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | System.IO.Stream。 |
| loadOptions | [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) | 加载选项。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static PersonalStorage fromStream(InputStream stream)
```


从流加载 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | stream | java.io.InputStream | System.IO.Stream。 |

--------------------

默认情况下，pst 将支持写入。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(InputStream stream, boolean writable) {#fromStream-java.io.InputStream-boolean-}
```
public static PersonalStorage fromStream(InputStream stream, boolean writable)
```


从流加载 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | System.IO.Stream。 |
| writable | boolean | 如果设置为 true，则 pst 文件将支持写入，否则将以只读模式打开。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(InputStream stream, PersonalStorageLoadOptions loadOptions) {#fromStream-java.io.InputStream-com.aspose.email.PersonalStorageLoadOptions-}
```
public static PersonalStorage fromStream(InputStream stream, PersonalStorageLoadOptions loadOptions)
```


从流加载 PST。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | System.IO.Stream。 |
| loadOptions | [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) | 加载选项。 |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFolderById(byte[] entryId) {#getFolderById-byte---}
```
public final FolderInfo getFolderById(byte[] entryId)
```


获取 PST 中的个人文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | byte[] | 条目 ID。 |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A FolderInfo object.
### getFolderById(String entryIdString) {#getFolderById-java.lang.String-}
```
public final FolderInfo getFolderById(String entryIdString)
```


获取 PST 中的个人文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryIdString | java.lang.String | 条目 ID 的字符串表示。 |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A FolderInfo object.
### getFormat() {#getFormat--}
```
public final int getFormat()
```


获取文件格式。

值: [FileFormat](../../com.aspose.email/fileformat) 指定文件格式。

--------------------

现在已支持 .pst 和 .ost 文件格式。

**Returns:**
int
### getParentFolder(byte[] entryId) {#getParentFolder-byte---}
```
public final FolderInfo getParentFolder(byte[] entryId)
```


获取消息的父文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | byte[] | 消息或文件夹的条目 ID。 |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The parent folder[FolderInfo](../../com.aspose.email/folderinfo) of message.
### getParentFolder(String entryIdString) {#getParentFolder-java.lang.String-}
```
public final FolderInfo getParentFolder(String entryIdString)
```


获取消息的父文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryIdString | java.lang.String | 消息或文件夹的条目 ID 的字符串表示。 |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The parent folder[FolderInfo](../../com.aspose.email/folderinfo) of message.
### getPredefinedFolder(int defaultFolder) {#getPredefinedFolder-int-}
```
public final FolderInfo getPredefinedFolder(int defaultFolder)
```


从 PST 获取标准的个人消息 (IPM) 文件夹。Outlook 可以创建多个默认文件夹，例如发件箱、已删除项、已发送项等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| defaultFolder | int | [StandardIpmFolder](../../com.aspose.email/standardipmfolder) 枚举的值。 |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A [FolderInfo](../../com.aspose.email/folderinfo) object that represents a standard IPM folder.
### getRootFolder() {#getRootFolder--}
```
public final FolderInfo getRootFolder()
```


获取 PST 的根文件夹。

值: [FolderInfo](../../com.aspose.email/folderinfo) 表示根文件夹。

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo)
### getStore() {#getStore--}
```
public final MessageStore getStore()
```


获取 PST 消息存储。

值: [MessageStore](../../com.aspose.email/messagestore) 大致相当于邮箱的顶部。

**Returns:**
[MessageStore](../../com.aspose.email/messagestore)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isUnicode() {#isUnicode--}
```
public final boolean isUnicode()
```


获取一个值，指示 PST 文件格式是否为 Unicode。PST 文件格式有两个版本：Unicode 和 ANSI。

**Returns:**
boolean
### load(System.IO.Stream stream) {#load-com.aspose.ms.System.IO.Stream-}
```
public final boolean load(System.IO.Stream stream)
```


从流加载 PST。当使用构造函数创建 PersonalStorage 对象时使用此方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | System.IO.Stream。 |

**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public final boolean load(InputStream stream)
```


从流加载 PST。当使用构造函数创建 PersonalStorage 对象时使用此方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | System.IO.Stream。 |

**Returns:**
boolean - 如果文件已成功加载且可以进一步遍历，则为 'true'；否则为 false。
### load(String fileName) {#load-java.lang.String-}
```
public final boolean load(String fileName)
```


从文件加载 PST。此方法在使用构造函数创建 PersonalStorage 对象时使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | .pst 文件的名称。 |

**Returns:**
boolean - 如果文件已成功加载且可以进一步遍历，则为 'true'；否则为 false。
### mergeWith(InputStream[] sourceStreams) {#mergeWith-java.io.InputStream---}
```
public final void mergeWith(InputStream[] sourceStreams)
```


将 pst 存储与一个或多个其他 pst 流合并。因此，合并后的流是来源。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceStreams | java.io.InputStream[] | 源流。 |

### mergeWith(String[] sourceFileNames) {#mergeWith-java.lang.String---}
```
public final void mergeWith(String[] sourceFileNames)
```


将 pst 存储与一个或多个其他 pst 文件合并。因此，合并后的文件是来源。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFileNames | java.lang.String[] | 源文件名。 |

### moveItem(FolderInfo folder, FolderInfo newFolder) {#moveItem-com.aspose.email.FolderInfo-com.aspose.email.FolderInfo-}
```
public final void moveItem(FolderInfo folder, FolderInfo newFolder)
```


将指定文件夹移动到当前 pst 中的新父文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| folder | [FolderInfo](../../com.aspose.email/folderinfo) | 要移动的文件夹。 |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | 新的父文件夹。 |

### moveItem(MessageInfo message, FolderInfo newFolder) {#moveItem-com.aspose.email.MessageInfo-com.aspose.email.FolderInfo-}
```
public final void moveItem(MessageInfo message, FolderInfo newFolder)
```


将指定消息移动到当前 pst 中的新文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MessageInfo](../../com.aspose.email/messageinfo) | 要移动的邮件。 |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | 邮件的新文件夹。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveAs(OutputStream stream, int format) {#saveAs-java.io.OutputStream-int-}
```
public final void saveAs(OutputStream stream, int format)
```


将当前对象保存为流中的指定文件格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 要保存的流。 |
| format | int | 要使用的 [FileFormat](../../com.aspose.email/fileformat)。 |

### saveAs(String fileName, int format) {#saveAs-java.lang.String-int-}
```
public final void saveAs(String fileName, int format)
```


将当前对象保存为不同文件中的指定文件格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 要保存的文件的名称。 |
| format | int | 在保存文件时要使用的 [FileFormat](../../com.aspose.email/fileformat)。 |

### saveMessageToFile(String entryId, String fileName) {#saveMessageToFile-java.lang.String-java.lang.String-}
```
public void saveMessageToFile(String entryId, String fileName)
```


saveMessageToFile。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | java.lang.String | 一个 java.lang.String 对象。 |
| fileName | java.lang.String | 一个 java.lang.String 对象。 |

### saveMessageToStream(String entryId, OutputStream stream) {#saveMessageToStream-java.lang.String-java.io.OutputStream-}
```
public final void saveMessageToStream(String entryId, OutputStream stream)
```


将消息（使用指定的 entryID）保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | java.lang.String | 条目 ID。 |
| stream | java.io.OutputStream | 用于写入的流。 |

### splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String path) {#splitInto-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.email.MailQuery--java.lang.String-}
```
public final void splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String path)
```


根据条件拆分 pst 存储。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| criteria | com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MailQuery> | 表示 pst 拆分条件的 [MailQuery](../../com.aspose.email/mailquery) 集合。 |
| 路径 | java.lang.String | 块将被创建的文件夹路径。 |

### splitInto(long chunkSize, String path) {#splitInto-long-java.lang.String-}
```
public final void splitInto(long chunkSize, String path)
```


将 pst 存储拆分为更小的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chunkSize | long | 块的大致大小（字节）。 |
| 路径 | java.lang.String | 块将被创建的文件夹路径。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryToGetFolderById(String entryIdString, FolderInfo[] folder) {#tryToGetFolderById-java.lang.String-com.aspose.email.FolderInfo---}
```
public final boolean tryToGetFolderById(String entryIdString, FolderInfo[] folder)
```


获取与指定 entry ID 关联的文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryIdString | java.lang.String | 表示条目 ID 的字符串。 |
| folder | [FolderInfo\[\]](../../com.aspose.email/folderinfo) | 当此方法返回 true 时，包含与指定 ID 关联的 [FolderInfo](../../com.aspose.email/folderinfo) 对象。 |

**Returns:**
boolean - 如果成功找到文件夹则为 true；否则为 false。
### tryToSaveMessage(String entryId, OutputStream stream) {#tryToSaveMessage-java.lang.String-java.io.OutputStream-}
```
public final SaveResult tryToSaveMessage(String entryId, OutputStream stream)
```


将消息（使用指定的 entryID）保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entryId | java.lang.String | 条目 ID。 |
| stream | java.io.OutputStream | 用于写入的流。 |

**Returns:**
[SaveResult](../../com.aspose.email/saveresult) - The [SaveResult](../../com.aspose.email/saveresult) that represents the result of item saving.
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

