---
title: CommitDeletesAsync
second_title: Aspose.Email for .NET API 参考
description: 提交删除
type: docs
weight: 470
url: /zh/net/aspose.email.clients.imap/imapclient/commitdeletesasync/
---
## CommitDeletesAsync(IConnection) {#commitdeletesasync_1}

提交删除

```csharp
public Task CommitDeletesAsync(IConnection connection)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, int) {#commitdeletesasync_2}

提交删除

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sleep | Int32 | 等待时间以毫秒为单位完成操作 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync() {#commitdeletesasync}

提交删除

```csharp
public Task CommitDeletesAsync()
```

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(int) {#commitdeletesasync_11}

提交删除

```csharp
public Task CommitDeletesAsync(int sleep)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sleep | Int32 | 等待时间以毫秒为单位完成操作 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(IEnumerable&lt;string&gt;) {#commitdeletesasync_13}

提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的唯一标识符集 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(string) {#commitdeletesasync_15}

提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的 uid |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, string) {#commitdeletesasync_16}

提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, IEnumerable&lt;string&gt;) {#commitdeletesasync_4}

提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的唯一标识符集 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string) {#commitdeletesasync_6}

提交删除

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的 uid |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, string) {#commitdeletesasync_7}

提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, CancellationToken) {#commitdeletesasync_10}

提交删除

```csharp
public Task CommitDeletesAsync(IConnection connection, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, int, CancellationToken) {#commitdeletesasync_3}

提交删除

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sleep | Int32 | 等待时间以毫秒为单位完成操作 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(CancellationToken) {#commitdeletesasync_19}

提交删除

```csharp
public Task CommitDeletesAsync(CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| token | CancellationToken | 传播应该取消操作的通知. |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(int, CancellationToken) {#commitdeletesasync_12}

提交删除

```csharp
public Task CommitDeletesAsync(int sleep, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sleep | Int32 | 等待时间以毫秒为单位完成操作 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#commitdeletesasync_14}

提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的唯一标识符集 |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, CancellationToken) {#commitdeletesasync_18}

提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的 uid |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, string, CancellationToken) {#commitdeletesasync_17}

提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#commitdeletesasync_5}

提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的唯一标识符集 |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, CancellationToken) {#commitdeletesasync_9}

提交删除

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的 uid |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, string, CancellationToken) {#commitdeletesasync_8}

提交删除 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
