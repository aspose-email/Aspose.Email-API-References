---
title: SearchResponseStore
second_title: Aspose.Email for .NET API 参考
description: 包含返回邮箱条目的状态结果范围和总计元素
type: docs
weight: 2000
url: /zh/net/aspose.email.clients.activesync.transportlayer/searchresponsestore/
---
## SearchResponseStore class

包含返回邮箱条目的状态、结果、范围和总计元素。

```csharp
public class SearchResponseStore
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SearchResponseStore](searchresponsestore)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Range](../../aspose.email.clients.activesync.transportlayer/searchresponsestore/range) { get; set; } | 指定正在返回的匹配条目的数量。 Range 元素值的格式是从零开始的索引说明符的形式，由零、连字符和另一个数值组成:“mn”。 m 表示从零开始的数组的最低索引，该数组将保存项目。 n 表示从零开始的数组的最高索引，该数组将保存项目。 例如，Range 元素值 0-9 表示 10 项，0-10 表示 11 项。 Range 元素值为 0–0 表示 1 个项目。 如果 Range 为 null，则使用每个 Store 类型的默认 Range 值。 下表标识了每种存储类型的默认范围值和返回的最大结果: 邮箱 - 默认范围值:0-99 - 返回的最大结果:100 DocumentLibrary - 默认范围值:0-999 - 返回的最大结果:1000 GAL - 默认范围值:0-99 - 最大结果Returned:100 如果请求中指定的 Range 值超出默认范围值，则返回 Status 值 12 表示已超出最大范围。 在 Search 命令响应中，Total 属性指示与 Query 值匹配的条目总数的估计值。 搜索结果存储在服务器上的搜索文件夹中。 这样，当客户端返回相同的查询但新的行范围时，将从当前存储在搜索文件夹中的结果集中提取行。 不必重建整个结果集。 |
| [Result](../../aspose.email.clients.activesync.transportlayer/searchresponsestore/result) { get; } | 匹配项列表。 |
| [Status](../../aspose.email.clients.activesync.transportlayer/searchresponsestore/status) { get; set; } | 表示操作的结果。 |
| [Total](../../aspose.email.clients.activesync.transportlayer/searchresponsestore/total) { get; set; } | 提供与搜索查询值匹配的邮箱条目总数的估计值。 Total 的值并不总是等于返回的条目数。 要确定 Search 命令返回的条目数，请使用 Range 值。 Total 表示可用的条目数。 在响应 XML 中返回所有结果的情况下，Total 元素的值比 Range 元素中提供的结束索引值大一。 例如，如果 Search 命令返回 15 个条目，则 Range 元素的值是 0-14，而 Total 的值是 15。 Total 用于客户端来确定在邮箱中找到的匹配条目是否多于搜索命令返回的条目。 例如，客户端可能执行初始搜索并指定请求的 0–4 范围（最多返回 5 个条目）。 如果 Total 元素表明实际上有 25 个匹配项，则客户端可以让用户检索完整的结果。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->