---
title: DeleteFoldersAsync
second_title: Aspose.Email for .NET API 参考
description: 删除文件夹
type: docs
weight: 170
url: /zh/net/aspose.email.clients.exchange.webservice/iasyncewsclient/deletefoldersasync/
---
## IAsyncEwsClient.DeleteFoldersAsync method

删除文件夹

```csharp
public Task DeleteFoldersAsync(IEnumerable<string> folderUris, bool deletePermanently = false, 
    CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderUris | IEnumerable`1 | 文件夹 URI 列表 |
| deletePermanently | Boolean | 指示该文件夹是应该永久删除还是应该移动到 DeletedItems 文件夹 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *folderUris*is` null` |

### 也可以看看

* interface [IAsyncEwsClient](../../iasyncewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->