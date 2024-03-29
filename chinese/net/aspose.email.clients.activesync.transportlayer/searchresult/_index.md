---
title: SearchResult
second_title: Aspose.Email for .NET API 参考
description: 单个匹配邮箱项目的容器 当正在搜索的商店是邮箱时 - 邮箱中找到的每个匹配项都有一个 Result 元素 如果未找到匹配项则响应 XML 的 Store 容器元素中存在一个空的 Result 元素 - 在 Result 元素中Properties 元素包含邮箱项目的请求属性列表 当存储正在搜索的是文档库 - 搜索响应中返回的第一个结果是 LinkId 值指向的根文件夹或项目的元数据 如果不需要客户端可以选择忽略此条目 - 如果请求中的 documentlibraryLinkId 元素值指向一个文件夹则该文件夹的元数据属性作为第一项返回其内容为该文件夹作为后续结果返回 Range 适用于这些结果没有区别例如索引 0 将始终用于链接指向的根项目 - 如果请求中的 documentlibraryLinkId 元素值指向一个项目则只返回一个结果该项目的元数据 - 在 Result 元素中Properties 元素包含邮箱项目的请求属性列表
type: docs
weight: 2010
url: /zh/net/aspose.email.clients.activesync.transportlayer/searchresult/
---
## SearchResult class

单个匹配邮箱项目的容器。 当正在搜索的商店是邮箱时： - 邮箱中找到的每个匹配项都有一个 Result 元素。 如果未找到匹配项，则响应 XML 的 Store 容器元素中存在一个空的 Result 元素。 - 在 Result 元素中，Properties 元素包含邮箱项目的请求属性列表。 当存储正在搜索的是文档库： - 搜索响应中返回的第一个结果是 LinkId 值指向的根文件夹或项目的元数据。 如果不需要，客户端可以选择忽略此条目。 - 如果请求中的 documentlibrary:LinkId 元素值指向一个文件夹，则该文件夹的元数据属性作为第一项返回，其内容为该文件夹作为后续结果返回。 Range 适用于这些结果，没有区别；例如，索引 0 将始终用于链接指向的根项目。 - 如果请求中的 documentlibrary:LinkId 元素值指向一个项目，则只返回一个结果：该项目的元数据。 - 在 Result 元素中，Properties 元素包含邮箱项目的请求属性列表。

```csharp
public class SearchResult
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SearchResult](searchresult)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/searchresult/class) { get; set; } | 标识项目的类别。 |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/searchresult/collectionid) { get; } | 指定找到该项目的文件夹。 |
| [LongId](../../aspose.email.clients.activesync.transportlayer/searchresult/longid) { get; set; } | 指定服务器为返回的每个结果集分配的唯一标识符。 LongId 的值可以用作 ItemOperations 命令请求、SmartReply 命令请求、SmartForward 命令请求或MeetingResponse 命令请求引用结果集。 客户端必须将 LongId 的值存储为最多 256 个字符的不透明字符串。 |
| [Properties](../../aspose.email.clients.activesync.transportlayer/searchresult/properties) { get; set; } | 搜索命令响应属性是属性的容器，适用于与查询元素搜索字符串匹配的单个条目。 例如，Properties 元素包含每个附加到匹配 GAL 条目的非空文本值 GAL 属性的元素。 仅返回那些附加到特定 GAL 条目的属性；因此，对于不同的匹配 GAL 条目，可以在响应 XML 中返回不同的属性集。 属性容器中的每个元素的范围都限定在顶级搜索元素中指定的适当命名空间。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
