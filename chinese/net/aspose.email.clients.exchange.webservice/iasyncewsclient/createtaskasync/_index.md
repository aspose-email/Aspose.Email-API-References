---
title: CreateTaskAsync
second_title: Aspose.Email for .NET API 参考
description: 在指定文件夹中创建给定任务
type: docs
weight: 140
url: /zh/net/aspose.email.clients.exchange.webservice/iasyncewsclient/createtaskasync/
---
## IAsyncEwsClient.CreateTaskAsync method

在指定文件夹中创建给定任务。

```csharp
public Task<string> CreateTaskAsync(ExchangeTask task, string folder = null, 
    CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| task | ExchangeTask | 要创建的任务。 |
| folder | String | 应在其中创建任务的文件夹。文件夹[`TasksUri`](../../../aspose.email.clients.exchange/exchangemailboxinfo/tasksuri)is 默认使用。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *task*是`无效的`. |

### 也可以看看

* class [ExchangeTask](../../exchangetask)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
