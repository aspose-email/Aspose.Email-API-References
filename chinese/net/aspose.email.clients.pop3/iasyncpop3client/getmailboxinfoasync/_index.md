---
title: GetMailboxInfoAsync
second_title: Aspose.Email for .NET API 参考
description: 获取邮箱状态信息
type: docs
weight: 60
url: /zh/net/aspose.email.clients.pop3/iasyncpop3client/getmailboxinfoasync/
---
## IAsyncPop3Client.GetMailboxInfoAsync method

获取邮箱状态信息

```csharp
public Task<Pop3MailboxInfo> GetMailboxInfoAsync(bool closeTransaction = false, 
    IConnection connection = null, CancellationToken token = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | Boolean | 连接到服务器 |
| closeTransaction | IConnection | 指示在检索列表之前是否必须关闭当前事务。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

邮箱信息。

### 也可以看看

* class [Pop3MailboxInfo](../../pop3mailboxinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncPop3Client](../../iasyncpop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../iasyncpop3client)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
