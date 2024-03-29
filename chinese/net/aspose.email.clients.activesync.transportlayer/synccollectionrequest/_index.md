---
title: SyncCollectionRequest
second_title: Aspose.Email for .NET API 参考
description: 类包含适用于特定集合的命令和选项
type: docs
weight: 2190
url: /zh/net/aspose.email.clients.activesync.transportlayer/synccollectionrequest/
---
## SyncCollectionRequest class

类包含适用于特定集合的命令和选项。

```csharp
public class SyncCollectionRequest
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SyncCollectionRequest](synccollectionrequest)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/collectionid) { get; set; } | 指定要同步的文件夹的服务器 ID。 |
| [Commands](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/commands) { get; set; } | 包含适用于集合的操作。 可用的操作是添加、删除、更改、获取和软删除。 |
| [ConversationMode](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/conversationmode) { get; set; } | 指定是否在同步响应的结果中包含对话模式中包含的项目。 将 ConversationMode 元素值设置为 TRUE 会导致检索与指定日期过滤器内收到的对话匹配的所有电子邮件。 但是，虽然不会检索基于时间的过滤器之外的电子邮件正文， 如果请求预览，将检索文本预览。在同步请求中将 ConversationMode 元素值设置为 FALSE 会导致同步符合 FilterType 元素（第 2.2.3.64 节）值标准的项目。 将 ConversationMode 元素值设置为 TRUE 会扩展结果集，使其还包含与 FilterType 结果集中具有相同 email2:ConversationId（[MS-ASEMAIL] 第 2.2.2.14 节）值的任何项目。 ConversationMode 元素值对 CollectionId 元素指定的集合之外的项目没有影响（第 2.2.3.30.5 节）； 结果集始终限于指定集合中的项目。 ConversationMode 元素值仅限制或扩展由 FilterType 元素值确定的结果。 |
| [DeletesAsMoves](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/deletesasmoves) { get; set; } | 指示所有已删除项目都应移动到已删除项目文件夹的请求。 如果 DeletesAsMoves 元素设置为 false，则删除是永久性的。 如果客户端想要永久删除项目，请求必须包含值为 FALSE 的 DeletesAsMoves 元素。 值 TRUE 是默认值，表示所有已删除的项目都被移动到 Deleted Items 文件夹。 |
| [GetChanges](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/getchanges) { get; set; } | 请求服务器在其响应中包含对由 ServerId 元素指定的集合的任何未决更改（第 2.2.3.151.6 节）。 如果自上次同步以来发生了更改，服务器响应包括一个命令元素（第 2.2.3.32 节） 包含添加、删除和更改。 如果客户端不希望服务器返回更改，请求必须包括值为 FALSE 的 GetChanges 元素。 TRUE 值表示客户端希望返回服务器更改。当 GetChanges 元素为空时，假定值为 TRUE。 当请求中不存在 GetChanges 元素时，行为取决于 SyncKey 元素的值，如第 2.2.3.166.4 节中所述。 如果 SyncKey 元素的值为 0，则处理请求，就像 GetChanges 元素设置为 FALSE。 如果 SyncKey 元素具有非零值，则处理请求，就像设置了 GetChanges 元素为真。 |
| [Options](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/options) { get; } | 指定控制同步执行方式的某些方面的选项。允许的数量 0...2. 同步选项使客户端能够指定截断和内容设置。 这些设置被封装在一个 airsyncbase:BodyPreference 子元素中，如 [MS-ASAIRS] 第 2.2.2.7 节中所述。 因为在集合上指定了同步选项，所以客户端可以为正在同步的每个集合指定唯一的 airsyncbase:BodyPreference 元素值。 有关 airsyncbase:BodyPreference 元素的更多详细信息，请参阅 [MS-ASAIRS] 部分 2.2。 2.7. 服务器跨请求保留选项块，使用称为“粘性选项”的概念。 如果请求中不包含选项块，则使用前一个选项块。 每当客户端通过在请求中包含选项块来指定新选项时，服务器必须用新的选项块替换原始选项块。 如果在单个同步命令请求中包含两个选项元素，则选项元素之一必须指定 SMS 类的同步选项，而其他 Options 元素指定给定文件夹的默认类的选项。 |
| [Supported](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/supported) { get; } | Contact 类和Calendar 类中没有幻影的元素可以作为Supported 元素的子元素包含在内。 幻影属性的使用详见2.2.3.154. |
| [SyncKey](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/synckey) { get; set; } | SyncKey 值被服务器用来标记集合的同步状态。 值为 0（零）的同步键初始化服务器上的同步状态并导致集合的完全同步。 |
| [WindowSize](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/windowsize) { get; set; } | 指定集合或请求中应包含在同步响应中的更改项目的最大数量。 如果未定义 WindowSize，则服务器的行为就像提交了值为 100 的 WindowSize 元素一样。 服务器将值 0（零）和高于 512 的值解释为 512. |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
