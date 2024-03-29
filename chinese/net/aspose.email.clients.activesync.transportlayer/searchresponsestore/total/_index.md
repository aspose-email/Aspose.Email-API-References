---
title: Total
second_title: Aspose.Email for .NET API 参考
description: 提供与搜索查询值匹配的邮箱条目总数的估计值 Total 的值并不总是等于返回的条目数 要确定 Search 命令返回的条目数请使用 Range 值 Total 表示可用的条目数 在响应 XML 中返回所有结果的情况下Total 元素的值比 Range 元素中提供的结束索引值大一 例如如果 Search 命令返回 15 个条目则 Range 元素的值是 0-14而 Total 的值是 15 Total 被客户端用来确定邮箱中是否找到了更多匹配的条目比搜索命令返回的要多 例如客户端可能会执行初始搜索并指定请求的 04 范围最多返回 5 个条目 如果 Total 元素表明实际上有 25 个匹配项则客户端可以让用户检索完整结果
type: docs
weight: 50
url: /zh/net/aspose.email.clients.activesync.transportlayer/searchresponsestore/total/
---
## SearchResponseStore.Total property

提供与搜索查询值匹配的邮箱条目总数的估计值。 Total 的值并不总是等于返回的条目数。 要确定 Search 命令返回的条目数，请使用 Range 值。 Total 表示可用的条目数。 在响应 XML 中返回所有结果的情况下，Total 元素的值比 Range 元素中提供的结束索引值大一。 例如，如果 Search 命令返回 15 个条目，则 Range 元素的值是 0-14，而 Total 的值是 15。 Total 被客户端用来确定邮箱中是否找到了更多匹配的条目比搜索命令返回的要多。 例如，客户端可能会执行初始搜索并指定请求的 0–4 范围（最多返回 5 个条目）。 如果 Total 元素表明实际上有 25 个匹配项，则客户端可以让用户检索完整结果。

```csharp
public int Total { get; set; }
```

### 也可以看看

* class [SearchResponseStore](../../searchresponsestore)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../searchresponsestore)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
