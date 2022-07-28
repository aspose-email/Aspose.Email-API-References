---
title: DeleteMessagesAsync
second_title: Aspose.Email for .NET API 参考
description: 将具有指定唯一标识符的消息标记为已删除
type: docs
weight: 590
url: /zh/net/aspose.email.clients.imap/imapclient/deletemessagesasync/
---
## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessagesasync_19}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long) {#deletemessagesasync_45}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long) {#deletemessagesasync_51}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_49}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_17}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_52}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_20}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
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

## DeleteMessagesAsync(IConnection, int, int) {#deletemessagesasync}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string) {#deletemessagesasync_24}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int) {#deletemessagesasync_32}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string) {#deletemessagesasync_56}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, long) {#deletemessagesasync_1}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long) {#deletemessagesasync_27}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, long) {#deletemessagesasync_33}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long) {#deletemessagesasync_59}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool) {#deletemessagesasync_57}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool) {#deletemessagesasync_25}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, bool) {#deletemessagesasync_60}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, bool) {#deletemessagesasync_28}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_4}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_36}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_7}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_39}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_37}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_5}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_40}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_8}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_15}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_23}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_47}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_55}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_14}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_22}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
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

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_46}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_54}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_50}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_18}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
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

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_53}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_21}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
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

---

## DeleteMessagesAsync(IConnection, int, int, CancellationToken) {#deletemessagesasync_3}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, CancellationToken) {#deletemessagesasync_31}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, CancellationToken) {#deletemessagesasync_35}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, CancellationToken) {#deletemessagesasync_63}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, int, int, long, CancellationToken) {#deletemessagesasync_2}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
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

## DeleteMessagesAsync(IConnection, string, string, long, CancellationToken) {#deletemessagesasync_30}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
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

## DeleteMessagesAsync(int, int, long, CancellationToken) {#deletemessagesasync_34}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, CancellationToken) {#deletemessagesasync_62}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool, CancellationToken) {#deletemessagesasync_58}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool, CancellationToken) {#deletemessagesasync_26}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
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

## DeleteMessagesAsync(string, string, long, bool, CancellationToken) {#deletemessagesasync_61}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
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

## DeleteMessagesAsync(IConnection, string, string, long, bool, CancellationToken) {#deletemessagesasync_29}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
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

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_11}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_43}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_10}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_42}

将具有指定唯一标识符的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_38}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_6}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_41}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_9}

将具有指定唯一标识符的消息标记为已删除，并在用户指定时提交删除。 此方法仅在服务器支持 UIDPLUS 扩展时有效。请阅读更多 https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | 删除的 ImapMessageInfo 集合 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | 定义是否必须立即提交消息。请阅读更多 https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#deletemessagesasync_12}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#deletemessagesasync_16}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;) {#deletemessagesasync_44}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;) {#deletemessagesasync_48}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessagesasync_13}

将具有指定序列号的消息标记为已删除

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| modificationSequence | Int64 | 修改顺序。请阅读更多 https://tools.ietf.org/html/rfc7162 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
