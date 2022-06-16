---
title: RebuildResults
second_title: Aspose.Email for .NET API 参考
description: 强制服务器重建与给定查询对应的搜索文件夹 2 搜索结果即结果集存储在服务器上的搜索文件夹中 这样当客户端返回相同的查询但新的行范围时将从当前存储在搜索文件夹中的结果集中提取行 不必重建整个结果集 搜索文件夹保持不变直到客户端执行以下操作之一来更新结果集 - 发送搜索请求指定新查询在这种情况下搜索文件夹会自动重建 不必包括 RebuildResults 节点 - 发送包含 RebuildResults 节点的搜索请求在这种情况下服务器被迫重建搜索文件夹 如果添加了新项则该项不会出现在结果集中直到结果集更新 如果一个项目被删除服务器会将删除的项目从结果集中过滤掉 客户端应该使用给定的查询发送一个新的搜索请求并每隔几天包含 RebuildResults 选项以确保该查询的准确结果
type: docs
weight: 90
url: /zh/net/aspose.email.clients.activesync.transportlayer/searchoptions/rebuildresults/
---
## SearchOptions.RebuildResults property

强制服务器重建与给定查询对应的搜索文件夹 (2)。 搜索结果（即结果集）存储在服务器上的搜索文件夹中。 这样，当客户端返回相同的查询但新的行范围时，将从当前存储在搜索文件夹中的结果集中提取行。 不必重建整个结果集。 搜索文件夹保持不变，直到客户端执行以下操作之一来更新结果集: - 发送搜索请求，指定新查询。在这种情况下，搜索文件夹会自动重建。 不必包括 RebuildResults 节点。 - 发送包含 RebuildResults 节点的搜索请求。在这种情况下，服务器被迫重建搜索文件夹。 如果添加了新项，则该项不会出现在结果集中，直到结果集更新。 如果一个项目被删除，服务器会将删除的项目从结果集中过滤掉。 客户端应该使用给定的查询发送一个新的搜索请求，并每隔几天包含 RebuildResults 选项以确保该查询的准确结果。

```csharp
public bool RebuildResults { get; set; }
```

### 也可以看看

* class [SearchOptions](../../searchoptions)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../searchoptions)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->