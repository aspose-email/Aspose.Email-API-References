---
title: ChangeMessageFlagsAsync
second_title: Aspose.Email for .NET API 参考
description: 更改消息的标志
type: docs
weight: 430
url: /zh/net/aspose.email.clients.imap/imapclient/changemessageflagsasync/
---
## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#changemessageflagsasync_41}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| flags | ImapMessageFlags | 要删除的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#changemessageflagsasync_17}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#changemessageflagsasync_13}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| flags | ImapMessageFlags | 要删除的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#changemessageflagsasync_36}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| flags | ImapMessageFlags | 要更改的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#changemessageflagsasync_8}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| flags | ImapMessageFlags | 要更改的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#changemessageflagsasync_37}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#changemessageflagsasync_9}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_51}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| flags | ImapMessageFlags | 要更改的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_31}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要删除的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_23}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| flags | ImapMessageFlags | 要更改的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_3}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要删除的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_50}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_30}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要删除的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_22}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_2}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要删除的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_55}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| flags | ImapMessageFlags | 要更改的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_35}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| flags | ImapMessageFlags | 要删除的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_27}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| flags | ImapMessageFlags | 要更改的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_7}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| flags | ImapMessageFlags | 要删除的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_54}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_34}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| flags | ImapMessageFlags | 要删除的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_26}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_6}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| flags | ImapMessageFlags | 要删除的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_47}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| flags | ImapMessageFlags | 要更改的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_43}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| flags | ImapMessageFlags | 要删除的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_19}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| flags | ImapMessageFlags | 要更改的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_15}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| flags | ImapMessageFlags | 要删除的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_46}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_42}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| flags | ImapMessageFlags | 要删除的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_18}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_14}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| flags | ImapMessageFlags | 要删除的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_39}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| flags | ImapMessageFlags | 要更改的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_11}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| flags | ImapMessageFlags | 要更改的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_38}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_10}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags) {#changemessageflagsasync_48}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| flags | ImapMessageFlags | 要更改的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags) {#changemessageflagsasync_28}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要删除的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags) {#changemessageflagsasync_20}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| flags | ImapMessageFlags | 要更改的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags) {#changemessageflagsasync}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要删除的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, long) {#changemessageflagsasync_49}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, long) {#changemessageflagsasync_29}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要删除的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, long) {#changemessageflagsasync_21}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, long) {#changemessageflagsasync_1}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要删除的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags) {#changemessageflagsasync_52}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| flags | ImapMessageFlags | 要更改的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags) {#changemessageflagsasync_32}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| flags | ImapMessageFlags | 要删除的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags) {#changemessageflagsasync_24}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| flags | ImapMessageFlags | 要更改的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags) {#changemessageflagsasync_4}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| flags | ImapMessageFlags | 要删除的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, long) {#changemessageflagsasync_53}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, long) {#changemessageflagsasync_33}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| flags | ImapMessageFlags | 要删除的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long) {#changemessageflagsasync_25}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long) {#changemessageflagsasync_5}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| flags | ImapMessageFlags | 要删除的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags) {#changemessageflagsasync_44}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| flags | ImapMessageFlags | 要更改的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags) {#changemessageflagsasync_40}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| flags | ImapMessageFlags | 要删除的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) {#changemessageflagsasync_16}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| flags | ImapMessageFlags | 要更改的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) {#changemessageflagsasync_12}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| flags | ImapMessageFlags | 要删除的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#changemessageflagsasync_45}

更改消息的标志

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| flags | ImapMessageFlags | 要更改的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
