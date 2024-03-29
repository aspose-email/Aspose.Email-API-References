---
title: CopyItemAsync
second_title: Aspose.Email for .NET API 参考
description: 将项目复制到指定文件夹
type: docs
weight: 80
url: /zh/net/aspose.email.clients.exchange.webservice/iasyncewsclient/copyitemasync/
---
## IAsyncEwsClient.CopyItemAsync method

将项目复制到指定文件夹

```csharp
public Task<string> CopyItemAsync(string itemUri, string destinationFolderUri, 
    CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| itemUri | String | 项目 URI |
| destinationFolderUri | String | 目标文件夹 URI |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

复制消息的 uri

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *itemUri*是`无效的`或者`空的` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderUri*是`无效的`或者`空的` |

### 也可以看看

* interface [IAsyncEwsClient](../../iasyncewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
