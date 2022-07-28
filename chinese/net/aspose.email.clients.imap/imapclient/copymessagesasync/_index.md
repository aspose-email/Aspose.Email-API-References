---
title: CopyMessagesAsync
second_title: Aspose.Email for .NET API 参考
description: 复制消息
type: docs
weight: 510
url: /zh/net/aspose.email.clients.imap/imapclient/copymessagesasync/
---
## CopyMessagesAsync(IConnection, int, int, string) {#copymessagesasync}

复制消息

```csharp
public Task CopyMessagesAsync(IConnection connection, int startSequence, int endSequence, 
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

## CopyMessagesAsync(int, int, string) {#copymessagesasync_10}

复制消息

```csharp
public Task CopyMessagesAsync(int startSequence, int endSequence, string folderName)
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

## CopyMessagesAsync(IConnection, string, string, string) {#copymessagesasync_8}

复制消息

```csharp
public Task CopyMessagesAsync(IConnection connection, string startUid, string endUid, 
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

## CopyMessagesAsync(string, string, string) {#copymessagesasync_19}

复制消息

```csharp
public Task CopyMessagesAsync(string startUid, string endUid, string folderName)
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

## CopyMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string) {#copymessagesasync_4}

复制消息

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## CopyMessagesAsync(IEnumerable&lt;int&gt;, string) {#copymessagesasync_14}

复制消息

```csharp
public Task CopyMessagesAsync(IEnumerable<int> sequenceSet, string folderName)
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

## CopyMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string) {#copymessagesasync_6}

复制消息

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<string> uidSet, string folderName)
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

## CopyMessagesAsync(IEnumerable&lt;string&gt;, string) {#copymessagesasync_17}

复制消息

```csharp
public Task CopyMessagesAsync(IEnumerable<string> uidSet, string folderName)
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

## CopyMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessagesasync_2}

复制消息

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## CopyMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessagesasync_12}

复制消息

```csharp
public Task CopyMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
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

## CopyMessagesAsync(IConnection, int, int, string, CancellationToken) {#copymessagesasync_1}

复制消息

```csharp
public Task CopyMessagesAsync(IConnection connection, int startSequence, int endSequence, 
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

## CopyMessagesAsync(int, int, string, CancellationToken) {#copymessagesasync_11}

复制消息

```csharp
public Task CopyMessagesAsync(int startSequence, int endSequence, string folderName, 
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

## CopyMessagesAsync(IConnection, string, string, string, CancellationToken) {#copymessagesasync_9}

复制消息

```csharp
public Task CopyMessagesAsync(IConnection connection, string startUid, string endUid, 
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

## CopyMessagesAsync(string, string, string, CancellationToken) {#copymessagesasync_20}

复制消息

```csharp
public Task CopyMessagesAsync(string startUid, string endUid, string folderName, 
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

## CopyMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) {#copymessagesasync_5}

复制消息

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## CopyMessagesAsync(IEnumerable&lt;int&gt;, string, CancellationToken) {#copymessagesasync_16}

复制消息

```csharp
public Task CopyMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
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

## CopyMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) {#copymessagesasync_7}

复制消息

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
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

## CopyMessagesAsync(IEnumerable&lt;string&gt;, string, CancellationToken) {#copymessagesasync_18}

复制消息

```csharp
public Task CopyMessagesAsync(IEnumerable<string> uidSet, string folderName, 
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

## CopyMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#copymessagesasync_3}

复制消息

```csharp
public Task CopyMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## CopyMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#copymessagesasync_13}

复制消息

```csharp
public Task CopyMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
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
