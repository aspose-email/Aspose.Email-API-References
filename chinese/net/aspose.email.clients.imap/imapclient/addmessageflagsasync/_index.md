---
title: AddMessageFlagsAsync
second_title: Aspose.Email for .NET API 参考
description: 添加消息的标志
type: docs
weight: 350
url: /zh/net/aspose.email.clients.imap/imapclient/addmessageflagsasync/
---
## AddMessageFlagsAsync(int, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_35}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
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

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_27}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
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

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_7}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
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

## AddMessageFlagsAsync(string, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_54}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
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

## AddMessageFlagsAsync(int, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_34}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
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

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_26}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
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

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_6}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
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

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_47}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
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

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_43}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
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

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_19}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
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

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_15}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_46}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
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

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_42}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
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

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_18}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
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

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_14}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_39}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_11}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
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

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_38}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_10}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
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

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags) {#addmessageflagsasync}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要添加的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags) {#addmessageflagsasync_20}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一标识符 |
| flags | ImapMessageFlags | 要添加的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags) {#addmessageflagsasync_28}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要添加的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags) {#addmessageflagsasync_48}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一标识符 |
| flags | ImapMessageFlags | 要添加的标志 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, long) {#addmessageflagsasync_1}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要添加的标志 |
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

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, long) {#addmessageflagsasync_21}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一标识符 |
| flags | ImapMessageFlags | 要添加的标志 |
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

## AddMessageFlagsAsync(int, ImapMessageFlags, long) {#addmessageflagsasync_29}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要添加的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, long) {#addmessageflagsasync_49}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一标识符 |
| flags | ImapMessageFlags | 要添加的标志 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags) {#addmessageflagsasync_52}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags)
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

## AddMessageFlagsAsync(int, int, ImapMessageFlags) {#addmessageflagsasync_32}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags)
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

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags) {#addmessageflagsasync_24}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
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

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags) {#addmessageflagsasync_4}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
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

## AddMessageFlagsAsync(string, string, ImapMessageFlags, long) {#addmessageflagsasync_53}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
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

## AddMessageFlagsAsync(int, int, ImapMessageFlags, long) {#addmessageflagsasync_33}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
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

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long) {#addmessageflagsasync_25}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
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

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long) {#addmessageflagsasync_5}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
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

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags) {#addmessageflagsasync_44}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags)
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

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags) {#addmessageflagsasync_40}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
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

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) {#addmessageflagsasync_16}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
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

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) {#addmessageflagsasync_12}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#addmessageflagsasync_45}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
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

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#addmessageflagsasync_41}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
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

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#addmessageflagsasync_17}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
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

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#addmessageflagsasync_13}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#addmessageflagsasync_36}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#addmessageflagsasync_8}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
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

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#addmessageflagsasync_37}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#addmessageflagsasync_9}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
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

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_3}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要添加的标志 |
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

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_23}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一标识符 |
| flags | ImapMessageFlags | 要添加的标志 |
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

## AddMessageFlagsAsync(int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_31}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要添加的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_51}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一标识符 |
| flags | ImapMessageFlags | 要添加的标志 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_2}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要添加的标志 |
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

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_22}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一标识符 |
| flags | ImapMessageFlags | 要添加的标志 |
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

## AddMessageFlagsAsync(int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_30}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| flags | ImapMessageFlags | 要添加的标志 |
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

## AddMessageFlagsAsync(string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_50}

将标志添加到消息

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一标识符 |
| flags | ImapMessageFlags | 要添加的标志 |
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

## AddMessageFlagsAsync(string, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_55}

添加消息的标志

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
