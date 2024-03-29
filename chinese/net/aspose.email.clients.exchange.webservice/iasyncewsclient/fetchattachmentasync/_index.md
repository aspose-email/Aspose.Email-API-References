---
title: FetchAttachmentAsync
second_title: Aspose.Email for .NET API 参考
description: 获取附件
type: docs
weight: 230
url: /zh/net/aspose.email.clients.exchange.webservice/iasyncewsclient/fetchattachmentasync/
---
## IAsyncEwsClient.FetchAttachmentAsync method

获取附件

```csharp
public Task<Attachment> FetchAttachmentAsync(string attachmentUri, 
    CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| attachmentUri | String | 附件uri. （可以使用ListMessages（文件夹，ExchangeListMessagesOptions.FetchAttachmentInformation）方法检索附件uri） |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

[`Attachment`](../../../aspose.email/attachment)表示获取的附件

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *attachmentUri*为空或为空 |

### 也可以看看

* class [Attachment](../../../aspose.email/attachment)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
