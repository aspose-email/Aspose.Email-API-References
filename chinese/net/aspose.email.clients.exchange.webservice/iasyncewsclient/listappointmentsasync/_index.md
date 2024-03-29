---
title: ListAppointmentsAsync
second_title: Aspose.Email for .NET API 参考
description: 检索指定日历文件夹的约会列表
type: docs
weight: 400
url: /zh/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listappointmentsasync/
---
## IAsyncEwsClient.ListAppointmentsAsync method

检索指定日历文件夹的约会列表

```csharp
public Task<Appointment[]> ListAppointmentsAsync(string folderUri, MailQuery query, bool recursive, 
    CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderUri | String | 用于搜索约会的文件夹。 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示约会搜索条件。 |
| recursive | Boolean | 指示是否递归列表。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

返回约会数组

### 也可以看看

* class [Appointment](../../../aspose.email.calendar/appointment)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
