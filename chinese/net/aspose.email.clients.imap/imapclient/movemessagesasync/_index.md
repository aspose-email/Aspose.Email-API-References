---
title: MoveMessagesAsync
second_title: Aspose.Email for .NET API 参考
description: 移动消息
type: docs
weight: 960
url: /zh/net/aspose.email.clients.imap/imapclient/movemessagesasync/
---
## MoveMessagesAsync(IConnection, int, int, string, bool) {#movemessagesasync_1}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string, bool) {#movemessagesasync_21}

移动消息

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, int, int, string) {#movemessagesasync}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string) {#movemessagesasync_20}

移动消息

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, bool) {#movemessagesasync_9}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string, bool) {#movemessagesasync_29}

移动消息

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string) {#movemessagesasync_8}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string) {#movemessagesasync_28}

移动消息

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string, bool) {#movemessagesasync_17}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string, bool) {#movemessagesasync_37}

移动消息

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string) {#movemessagesasync_16}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string) {#movemessagesasync_36}

移动消息

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, bool) {#movemessagesasync_13}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string, bool) {#movemessagesasync_33}

移动消息

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string) {#movemessagesasync_12}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string) {#movemessagesasync_32}

移动消息

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessagesasync_5}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessagesasync_25}

移动消息

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessagesasync_4}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessagesasync_24}

移动消息

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, int, int, string, bool, CancellationToken) {#movemessagesasync_2}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string, bool, CancellationToken) {#movemessagesasync_22}

移动消息

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, int, int, string, CancellationToken) {#movemessagesasync_3}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| folderName | String | 要移动消息的文件夹名称 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string, CancellationToken) {#movemessagesasync_23}

移动消息

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startSequence | Int32 | 消息列表的起始序号 |
| endSequence | Int32 | 消息列表的结束序号 |
| folderName | String | 要移动消息的文件夹名称 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, bool, CancellationToken) {#movemessagesasync_10}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string, bool, CancellationToken) {#movemessagesasync_30}

移动消息

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) {#movemessagesasync_11}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| folderName | String | 要移动消息的文件夹名称 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string, CancellationToken) {#movemessagesasync_31}

移动消息

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | 消息的序列号集 |
| folderName | String | 要移动消息的文件夹名称 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string, bool, CancellationToken) {#movemessagesasync_18}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string, bool, CancellationToken) {#movemessagesasync_38}

移动消息

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string, CancellationToken) {#movemessagesasync_19}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| folderName | String | 要移动消息的文件夹名称 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string, CancellationToken) {#movemessagesasync_39}

移动消息

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startUid | String | 消息列表的起始 UID |
| endUid | String | 消息列表的结束 UID |
| folderName | String | 要移动消息的文件夹名称 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, bool, CancellationToken) {#movemessagesasync_14}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string, bool, CancellationToken) {#movemessagesasync_34}

移动消息

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) {#movemessagesasync_15}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| folderName | String | 要移动消息的文件夹名称 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string, CancellationToken) {#movemessagesasync_35}

移动消息

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uidSet | IEnumerable`1 | 消息的 UID 集 |
| folderName | String | 要移动消息的文件夹名称 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) {#movemessagesasync_6}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |
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

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) {#movemessagesasync_26}

移动消息

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#movemessagesasync_7}

移动消息

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| folderName | String | 要移动消息的文件夹名称 |
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

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#movemessagesasync_27}

移动消息

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | ImapMessageInfo 的集合 |
| folderName | String | 要移动消息的文件夹名称 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
