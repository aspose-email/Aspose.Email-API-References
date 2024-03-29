---
title: GetMessageInfoAsync
second_title: Aspose.Email for .NET API 参考
description: 获取该消息的信息
type: docs
weight: 100
url: /zh/net/aspose.email.clients.pop3/iasyncpop3client/getmessageinfoasync/
---
## GetMessageInfoAsync(string, Pop3ListFields, IConnection, CancellationToken) {#getmessageinfoasync_1}

获取该消息的信息

```csharp
public Task<Pop3MessageInfo> GetMessageInfoAsync(string uniqueId, 
    Pop3ListFields fields = Pop3ListFields.All, IConnection connection = null, 
    CancellationToken token = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | String | 连接到服务器 |
| uniqueId | Pop3ListFields | 消息的唯一标识 |
| fields | IConnection | 我们想要得到的字段 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

消息信息。

### 也可以看看

* class [Pop3MessageInfo](../../pop3messageinfo)
* enum [Pop3ListFields](../../pop3listfields)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncPop3Client](../../iasyncpop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../iasyncpop3client)
* 部件 [Aspose.Email](../../../)

---

## GetMessageInfoAsync(int, Pop3ListFields, IConnection, CancellationToken) {#getmessageinfoasync}

获取该消息的信息

```csharp
public Task<Pop3MessageInfo> GetMessageInfoAsync(int sequenceNumber, 
    Pop3ListFields fields = Pop3ListFields.All, IConnection connection = null, 
    CancellationToken token = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | Int32 | 连接到服务器 |
| sequenceNumber | Pop3ListFields | 消息的序号 |
| fields | IConnection | 我们想要得到的字段 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

消息信息。

### 也可以看看

* class [Pop3MessageInfo](../../pop3messageinfo)
* enum [Pop3ListFields](../../pop3listfields)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncPop3Client](../../iasyncpop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../iasyncpop3client)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
