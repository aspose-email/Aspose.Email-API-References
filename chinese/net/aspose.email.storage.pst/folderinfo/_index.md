---
title: FolderInfo
second_title: Aspose.Email for .NET API 参考
description: 代表关于 PST 中个人文件夹的信息 
type: docs
weight: 20160
url: /zh/net/aspose.email.storage.pst/folderinfo/
---
## FolderInfo class

代表关于 PST 中个人文件夹的信息 。

```csharp
public sealed class FolderInfo
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [FolderInfo](folderinfo)() | 初始化[`FolderInfo`](../folderinfo)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ContainerClass](../../aspose.email.storage.pst/folderinfo/containerclass) { get; } | 获取文件夹对象的容器类。 |
| [ContentCount](../../aspose.email.storage.pst/folderinfo/contentcount) { get; } | 获取文件夹中的项目总数。 |
| [ContentUnreadCount](../../aspose.email.storage.pst/folderinfo/contentunreadcount) { get; } | 获取文件夹中未读项目的数量。 |
| [DisplayName](../../aspose.email.storage.pst/folderinfo/displayname) { get; } | 获取文件夹的显示名称。 |
| [EntryId](../../aspose.email.storage.pst/folderinfo/entryid) { get; } | 获取条目 ID。 |
| [EntryIdString](../../aspose.email.storage.pst/folderinfo/entryidstring) { get; } | 获取条目 ID 的字符串表示形式。 |
| [HasSubFolders](../../aspose.email.storage.pst/folderinfo/hassubfolders) { get; } | 获取一个值，该值指示文件夹对象是否有任何子文件夹。 |
| [LastModificationTime](../../aspose.email.storage.pst/folderinfo/lastmodificationtime) { get; } | 获取最后修改时间。 |
| [Properties](../../aspose.email.storage.pst/folderinfo/properties) { get; } | 获取文件夹属性。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddFile](../../aspose.email.storage.pst/folderinfo/addfile)(string, string) | 将文件添加到 pst 文件夹中。 |
| [AddMapiMessageItem](../../aspose.email.storage.pst/folderinfo/addmapimessageitem)(IMapiMessageItem) | 将 IMapiMessageItem 对象添加到文件夹中。 |
| [AddMessage](../../aspose.email.storage.pst/folderinfo/addmessage)(MapiMessage) | 将新消息添加到文件夹中。 |
| [AddMessages](../../aspose.email.storage.pst/folderinfo/addmessages)(IEnumerable&lt;MapiMessage&gt;) | 以批量模式提供消息添加。 |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder)(string) | 添加新的子文件夹。 |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_1)(string, bool) | 添加新的子文件夹。 |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_2)(string, string) | 添加新的子文件夹。 |
| [ChangeContainerClass](../../aspose.email.storage.pst/folderinfo/changecontainerclass)(string) | 更改容器类。 |
| [ChangeDisplayName](../../aspose.email.storage.pst/folderinfo/changedisplayname)(string) | 更改显示名称。 |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages)(MapiPropertyCollection) | 更改文件夹中的所有邮件。 |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages_1)(IEnumerable&lt;string&gt;, MapiPropertyCollection) | 更改文件夹中的消息。 |
| [DeleteChildItem](../../aspose.email.storage.pst/folderinfo/deletechilditem)(byte[]) | 按其 entryId 删除项目（文件夹或消息）。 |
| [DeleteChildItems](../../aspose.email.storage.pst/folderinfo/deletechilditems)(IEnumerable&lt;string&gt;) | 删除子消息。 |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders)() | 公开枚举器，它支持文件夹中子文件夹的迭代。 |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders_1)(FolderKind) | 公开枚举器，它支持文件夹中子文件夹的迭代。 |
| [EnumerateMapiMessages](../../aspose.email.storage.pst/folderinfo/enumeratemapimessages)() | 公开枚举器，它支持文件夹中消息的迭代。 |
| [EnumerateMessageObjects](../../aspose.email.storage.pst/folderinfo/enumeratemessageobjects)() | 公开枚举器，它支持文件夹中消息的迭代。 |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages)() | 公开枚举器，它支持文件夹中消息的迭代。 |
| [EnumerateMessagesEntryId](../../aspose.email.storage.pst/folderinfo/enumeratemessagesentryid)() | 枚举消息的 entryID。 |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents)() | 获取消息集合。 |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_3)(bool) | 获取消息集合。 |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_2)(MailQuery) | 获取消息集合。 |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_1)(MessageKind) | 获取消息集合。 |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_4)(int, int) | 获取消息的集合。 |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder)(string) | 获取子文件夹。 |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder_1)(string, bool) | 获取子文件夹。 |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders)() | 获取子文件夹的集合。 |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_1)(FolderKind) | 获取子文件夹的集合。 |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_2)(MailQuery) | 获取子文件夹的集合。 |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith)(FolderInfo) | 将文件夹与另一个 pst 中的文件夹合并。 |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith_1)(FolderInfo, bool) | 将文件夹与另一个 pst 中的文件夹合并。 OnItemMoved 事件在消息和目录上都被调用。 |
| [MoveContents](../../aspose.email.storage.pst/folderinfo/movecontents)(FolderInfo) | 将内容移动到新文件夹。 |
| [MoveSubfolders](../../aspose.email.storage.pst/folderinfo/movesubfolders)(FolderInfo) | 将子文件夹移动到新的父文件夹。 |
| [RetrieveFullPath](../../aspose.email.storage.pst/folderinfo/retrievefullpath)() | 检索 PST 文件中文件夹的完整路径。 |
| [UpdateMessage](../../aspose.email.storage.pst/folderinfo/updatemessage)(string, MapiMessageItemBase) | 更新文件夹中的消息。 |

### 也可以看看

* 命名空间 [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
