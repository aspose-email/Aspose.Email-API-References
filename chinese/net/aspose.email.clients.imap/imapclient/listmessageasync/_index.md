---
title: ListMessageAsync
second_title: Aspose.Email for .NET API 参考
description: 获取有关消息的信息
type: docs
weight: 860
url: /zh/net/aspose.email.clients.imap/imapclient/listmessageasync/
---
## ListMessageAsync(IConnection, int, IEnumerable&lt;string&gt;) {#listmessageasync_1}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, int sequenceNumber, 
    IEnumerable<string> messageExtraFields)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 序列号消息 |
| messageExtraFields | IEnumerable`1 | 将请求消息的额外参数列表。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, int) {#listmessageasync}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, int sequenceNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 序列号消息 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(int, IEnumerable&lt;string&gt;) {#listmessageasync_9}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(int sequenceNumber, 
    IEnumerable<string> messageExtraFields)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息序列号 |
| messageExtraFields | IEnumerable`1 | 列表将要求消息的额外参数。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(int) {#listmessageasync_8}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(int sequenceNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序列号 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, string, IEnumerable&lt;string&gt;) {#listmessageasync_5}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, string uniqueId, 
    IEnumerable<string> messageExtraFields)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 唯一 ID消息 |
| messageExtraFields | IEnumerable`1 | 将请求消息的额外参数列表。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, string) {#listmessageasync_4}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, string uniqueId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 唯一 ID消息 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(string) {#listmessageasync_12}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(string uniqueId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一 ID |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(string, IEnumerable&lt;string&gt;) {#listmessageasync_13}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(string uniqueId, 
    IEnumerable<string> messageExtraFields)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一 ID |
| messageExtraFields | IEnumerable`1 | 列表将请求消息的额外参数。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, int, IEnumerable&lt;string&gt;, CancellationToken) {#listmessageasync_2}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, int sequenceNumber, 
    IEnumerable<string> messageExtraFields, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 序列号消息 |
| messageExtraFields | IEnumerable`1 | 将请求消息的额外参数列表。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, int, CancellationToken) {#listmessageasync_3}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, int sequenceNumber, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 序列号消息 |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(int, IEnumerable&lt;string&gt;, CancellationToken) {#listmessageasync_10}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(int sequenceNumber, 
    IEnumerable<string> messageExtraFields, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息序列号 |
| messageExtraFields | IEnumerable`1 | 列表将要求消息的额外参数。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(int, CancellationToken) {#listmessageasync_11}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(int sequenceNumber, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序列号 |
| token | CancellationToken | 传播通知该操作应该被取消。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, string, IEnumerable&lt;string&gt;, CancellationToken) {#listmessageasync_6}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, string uniqueId, 
    IEnumerable<string> messageExtraFields, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 唯一 ID消息 |
| messageExtraFields | IEnumerable`1 | 将请求消息的额外参数列表。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(IConnection, string, CancellationToken) {#listmessageasync_7}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(IConnection connection, string uniqueId, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 唯一 ID消息 |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(string, CancellationToken) {#listmessageasync_15}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(string uniqueId, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一 ID |
| token | CancellationToken | 传播通知应取消操作。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessageAsync(string, IEnumerable&lt;string&gt;, CancellationToken) {#listmessageasync_14}

获取有关消息的信息。

```csharp
public Task<ImapMessageInfo> ListMessageAsync(string uniqueId, 
    IEnumerable<string> messageExtraFields, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一 ID |
| messageExtraFields | IEnumerable`1 | 列表将请求消息的额外参数。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
