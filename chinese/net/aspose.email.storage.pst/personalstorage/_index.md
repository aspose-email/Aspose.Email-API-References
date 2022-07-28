---
title: PersonalStorage
second_title: Aspose.Email for .NET API 参考
description: 表示个人存储表 .pst 文件
type: docs
weight: 20290
url: /zh/net/aspose.email.storage.pst/personalstorage/
---
## PersonalStorage class

表示个人存储表 (.pst) 文件。

```csharp
public class PersonalStorage : IDisposable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PersonalStorage](personalstorage)(TraversalExceptionsCallback) | 初始化一个新的实例[`PersonalStorage`](../personalstorage)class. 允许设置回调方法来处理 PST 遍历期间发生的异常。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CanWrite](../../aspose.email.storage.pst/personalstorage/canwrite) { get; } | 获取一个值，表示 当前的pst是否支持写入。 |
| [Format](../../aspose.email.storage.pst/personalstorage/format) { get; } | 获取文件格式。 |
| [IsUnicode](../../aspose.email.storage.pst/personalstorage/isunicode) { get; } | 获取表示 PST 文件格式是否为 Unicode 的值。 PST 文件格式有两个版本：Unicode 和 ANSI。 |
| [RootFolder](../../aspose.email.storage.pst/personalstorage/rootfolder) { get; } | 获取 PST 的根文件夹。 |
| [Store](../../aspose.email.storage.pst/personalstorage/store) { get; } | 获取 PST 消息存储。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create)(Stream, FileFormatVersion) | 在流中创建 PST。 |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_4)(string, FileFormatVersion) | 使用指定的文件名创建新的 PST 文件。 |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_1)(Stream, FileFormatVersion, bool) | 在流中创建 PST。 |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_3)(Stream, FileFormatVersion, CancellationToken) | 在流中创建 PST。 |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_5)(string, FileFormatVersion, CancellationToken) | 使用指定的文件名创建新的 PST 文件。 |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_2)(Stream, FileFormatVersion, bool, CancellationToken) | 在流中创建 PST。 |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile)(string) | 从文件中加载 PST。 |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_3)(string, bool) | 从文件中加载 PST。 |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_5)(string, CancellationToken) | 从文件中加载 PST。 |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_1)(string, PersonalStorageLoadOptions) | 从文件中加载 PST。 |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_4)(string, bool, CancellationToken) |  |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_2)(string, PersonalStorageLoadOptions, CancellationToken) | 从文件中加载 PST。 |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream)(Stream) | 从流中加载 PST。 |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_3)(Stream, bool) | 从流中加载 PST。 |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_5)(Stream, CancellationToken) | 从文件中加载 PST。 |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_1)(Stream, PersonalStorageLoadOptions) | 从流中加载 PST。 |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_4)(Stream, bool, CancellationToken) |  |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_2)(Stream, PersonalStorageLoadOptions, CancellationToken) | 从文件中加载 PST。 |
| [ChangeMessage](../../aspose.email.storage.pst/personalstorage/changemessage)(string, MapiPropertyCollection) | 更改消息属性。 |
| [ConvertTo](../../aspose.email.storage.pst/personalstorage/convertto)(FileFormat) | 将当前对象转换为指定格式。 |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder)(string, StandardIpmFolder) | 创建标准人际消息 (IPM) 文件夹。 |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder_1)(string, StandardIpmFolder, bool) | 创建标准人际消息 (IPM) 文件夹。 |
| [Dispose](../../aspose.email.storage.pst/personalstorage/dispose)() | 执行与释放、 释放或重置非托管资源相关的应用程序定义任务。 |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages)(string) | 公开枚举器，它支持文件夹中消息的迭代。 |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages_1)(string, int, int) | 公开枚举器，它支持文件夹中消息的迭代。 |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments)(MessageInfo) | 提取附件。 |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments_1)(string) | 提取附件。 |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_1)(byte[]) | 从 PST 获取消息。 |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage)(MessageInfo) | 从 PST 获取消息。 |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_2)(string) | 从 PST 获取消息。 |
| [ExtractProperty](../../aspose.email.storage.pst/personalstorage/extractproperty)(byte[], long) | 获取item的指定属性，不完全提取item。 |
| [FindMessages](../../aspose.email.storage.pst/personalstorage/findmessages)(string) | 查找当前文件夹的消息标识符。 在 GetContents 和 EnumerateMessages 方法可能引发异常时读取损坏的 pst 可能很有用。 |
| [FindSubfolders](../../aspose.email.storage.pst/personalstorage/findsubfolders)(string) | 查找当前文件夹的子文件夹标识符。 在 GetSubfolders 和 EnumerateFolders 方法可能引发异常时读取损坏的 pst 可能很有用。 |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid)(byte[]) | 从 PST 获取个人文件夹。 |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid_1)(string) | 从 PST 获取个人文件夹。 |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder)(byte[]) | 获取消息的父文件夹。 |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder_1)(string) | 获取消息的父文件夹。 |
| [GetPredefinedFolder](../../aspose.email.storage.pst/personalstorage/getpredefinedfolder)(StandardIpmFolder) | 从 PST 获取标准的人际消息 (IPM) 文件夹。 Outlook 可以创建许多默认文件夹， 例如发件箱、已删除邮件、已发送邮件等。 |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load)(Stream) | 从流中加载 PST。 当使用构造函数创建 PersonalStorage 对象时使用此方法。 |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load_1)(string) | 从文件加载 PST。 当使用构造函数创建 PersonalStorage 对象时使用此方法。 |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith)(Stream[]) | 将 pst 存储与一个或多个其他 pst 流合并。 因此，合并的流是源。 |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith_1)(string[]) | 将 pst 存储与一个或多个其他 pst 文件合并。 因此，合并的文件是源。 |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem)(FolderInfo, FolderInfo) | 将指定文件夹移动到当前 pst 中的新父文件夹。 |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem_1)(MessageInfo, FolderInfo) | 将指定消息移动到当前 pst 中的新文件夹。 |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas)(Stream, FileFormat) | 将当前对象保存为流中指定的文件格式。 |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas_1)(string, FileFormat) | 将当前对象保存为不同文件中的指定文件格式。 |
| [SaveMessageToStream](../../aspose.email.storage.pst/personalstorage/savemessagetostream)(string, Stream) | 将带有指定 entryID 的消息保存到流中。 |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto_1)(IList&lt;MailQuery&gt;, string) | 根据标准拆分 pst 存储。 |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto)(long, string) | 将 pst 存储拆分为较小的部分。 |
| [TryToGetFolderById](../../aspose.email.storage.pst/personalstorage/trytogetfolderbyid)(string, out FolderInfo) | 获取与指定条目 ID 关联的文件夹。 |
| [TryToSaveMessage](../../aspose.email.storage.pst/personalstorage/trytosavemessage)(string, Stream) | 将带有指定 entryID 的消息保存到流中。 |

### 也可以看看

* 命名空间 [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
