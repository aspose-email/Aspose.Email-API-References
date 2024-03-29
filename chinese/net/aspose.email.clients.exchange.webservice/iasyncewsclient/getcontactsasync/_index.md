---
title: GetContactsAsync
second_title: Aspose.Email for .NET API 参考
description: 列出服务器上指定文件夹中的联系人
type: docs
weight: 330
url: /zh/net/aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactsasync/
---
## IAsyncEwsClient.GetContactsAsync method

列出服务器上指定文件夹中的联系人

```csharp
public Task<Contact[]> GetContactsAsync(string folder, 
    ExchangeListContactsOptions options = ExchangeListContactsOptions.FetchPhoto, 
    CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于搜索联系人的文件夹 |
| options | ExchangeListContactsOptions | 枚举列表联系人选项 |
| cancellationToken | CancellationToken | 取消令牌 |

### 返回值

读取的数组[`Contact`](../../../aspose.email.personalinfo/contact)代表联系信息

### 也可以看看

* class [Contact](../../../aspose.email.personalinfo/contact)
* enum [ExchangeListContactsOptions](../../exchangelistcontactsoptions)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
