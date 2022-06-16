---
title: ItemOperationsRequest
second_title: Aspose.Email for .NET API 参考
description: 包含 ItemOperations 请求
type: docs
weight: 1460
url: /zh/net/aspose.email.clients.activesync.transportlayer/itemoperationsrequest/
---
## ItemOperationsRequest class

包含 ItemOperations 请求。

```csharp
public class ItemOperationsRequest
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ItemOperationsRequest](itemoperationsrequest)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [EmptyFolderContents](../../aspose.email.clients.activesync.transportlayer/itemoperationsrequest/emptyfoldercontents) { get; } | 包含有关删除文件夹内容的请求。 EmptyFolderContents 支持 Options 元素的单个子元素 DeleteSubFolders，它决定是否删除文件夹中包含的子文件夹。 如果请求中不包含 DeleteSubFolders 选项，则不会删除指定 CollectionId 的子文件夹。 |
| [Fetch](../../aspose.email.clients.activesync.transportlayer/itemoperationsrequest/fetch) { get; } | 包含有关从服务器检索项目的请求。 |
| [Move](../../aspose.email.clients.activesync.transportlayer/itemoperationsrequest/move) { get; } | 包含有关将对话移动到特定文件夹的请求。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->