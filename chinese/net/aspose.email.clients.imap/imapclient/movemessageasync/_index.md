---
title: MoveMessageAsync
second_title: Aspose.Email for .NET API 参考
description: 移动消息
type: docs
weight: 940
url: /zh/net/aspose.email.clients.imap/imapclient/movemessageasync/
---
## MoveMessageAsync(IConnection, int, string) {#movemessageasync}

移动消息

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序列号 |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string) {#movemessageasync_4}

移动消息

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string) {#movemessageasync_8}

移动消息

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序列号 |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string) {#movemessageasync_12}

移动消息

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| folderName | String | 要移动消息的文件夹名称 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool, CancellationToken) {#movemessageasync_2}

移动消息

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序列号 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool, CancellationToken) {#movemessageasync_6}

移动消息

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string, bool, CancellationToken) {#movemessageasync_10}

移动消息

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序列号 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除. |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool, CancellationToken) {#movemessageasync_14}

移动消息

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, CancellationToken) {#movemessageasync_3}

移动消息

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序列号 |
| folderName | String | 要移动消息的文件夹名称 |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, CancellationToken) {#movemessageasync_7}

移动消息

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| folderName | String | 要移动消息的文件夹名称 |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string, CancellationToken) {#movemessageasync_11}

移动消息

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序列号 |
| folderName | String | 要移动消息的文件夹名称 |
| token | CancellationToken | 传播操作应该是的通知取消。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, CancellationToken) {#movemessageasync_15}

移动消息

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| folderName | String | 要移动消息的文件夹名称 |
| token | CancellationToken | 传播应该取消操作的通知. |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool) {#movemessageasync_1}

移动消息

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序列号 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool) {#movemessageasync_5}

移动消息

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的uid |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string, bool) {#movemessageasync_9}

移动消息

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序列号 |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除. |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool) {#movemessageasync_13}

移动消息

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的uid |
| folderName | String | 要移动消息的文件夹名称 |
| commitDeletions | Boolean | 指定是否应提交删除。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
