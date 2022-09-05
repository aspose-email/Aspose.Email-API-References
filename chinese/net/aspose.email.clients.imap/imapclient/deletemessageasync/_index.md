---
title: DeleteMessageAsync
second_title: Aspose.Email for .NET API 参考
description: 将具有指定序列号的消息标记为已删除
type: docs
weight: 570
url: /zh/net/aspose.email.clients.imap/imapclient/deletemessageasync/
---
## DeleteMessageAsync(IConnection, int) {#deletemessageasync}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string) {#deletemessageasync_4}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(int) {#deletemessageasync_12}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessageAsync(int sequenceNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(string) {#deletemessageasync_16}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessageAsync(string uniqueId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long) {#deletemessageasync_1}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long) {#deletemessageasync_7}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long) {#deletemessageasync_13}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long) {#deletemessageasync_19}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool) {#deletemessageasync_17}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool) {#deletemessageasync_5}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool) {#deletemessageasync_20}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, bool) {#deletemessageasync_8}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, CancellationToken) {#deletemessageasync_3}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, CancellationToken) {#deletemessageasync_11}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, CancellationToken) {#deletemessageasync_15}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessageAsync(int sequenceNumber, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, CancellationToken) {#deletemessageasync_23}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessageAsync(string uniqueId, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long, CancellationToken) {#deletemessageasync_2}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, CancellationToken) {#deletemessageasync_10}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long, CancellationToken) {#deletemessageasync_14}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, CancellationToken) {#deletemessageasync_22}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool, CancellationToken) {#deletemessageasync_18}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool, CancellationToken) {#deletemessageasync_6}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool, CancellationToken) {#deletemessageasync_21}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, bool, CancellationToken) {#deletemessageasync_9}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
