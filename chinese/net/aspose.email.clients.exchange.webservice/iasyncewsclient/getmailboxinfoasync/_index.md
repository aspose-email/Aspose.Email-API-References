---
title: GetMailboxInfoAsync
second_title: Aspose.Email for .NET API 参考
description: 获取邮箱信息
type: docs
weight: 370
url: /zh/net/aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxinfoasync/
---
## IAsyncEwsClient.GetMailboxInfoAsync method

获取邮箱信息

```csharp
public Task<ExchangeMailboxInfo> GetMailboxInfoAsync(string mailbox = null, 
    CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mailbox | String | 要读取的邮箱。注意：如果邮箱设置为`无效的`或者`空的`将使用 default 邮箱 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

[`ExchangeMailboxInfo`](../../../aspose.email.clients.exchange/exchangemailboxinfo)代表邮箱信息

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [ExchangeException](../../../aspose.email/exchangeexception) | 无法读取邮箱信息。 |

### 也可以看看

* class [ExchangeMailboxInfo](../../../aspose.email.clients.exchange/exchangemailboxinfo)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
