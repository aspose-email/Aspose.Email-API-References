---
title: SaveMessageAsync
second_title: Aspose.Email for .NET API 参考
description: 下载具有指定序列号的消息并将其数据写入提供的流
type: docs
weight: 1100
url: /zh/net/aspose.email.clients.imap/imapclient/savemessageasync/
---
## SaveMessageAsync(IConnection, int, Stream) {#savemessageasync}

下载具有指定序列号的消息并将其数据写入提供的流

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| resultStream | Stream | 将接收消息的流 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream) {#savemessageasync_4}

下载具有指定序列号 的消息并将其数据写入提供的流

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一 ID |
| resultStream | Stream | 将接收消息的流 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string) {#savemessageasync_6}

下载指定序号 的消息，并将其数据写入本地文件

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一 ID |
| fileName | String | 本地文件的路径。这不能是目录 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string) {#savemessageasync_2}

下载指定序号的消息并将其数据写入本地文件

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| fileName | String | 本地文件的路径。这不能是目录 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream) {#savemessageasync_8}

下载具有指定序列号的消息并将其数据写入提供的流

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| resultStream | Stream | 将接收消息的流 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream) {#savemessageasync_12}

下载具有指定序列号 的消息并将其数据写入提供的流

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一 ID |
| resultStream | Stream | 将接收消息的流 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string) {#savemessageasync_14}

下载指定序号 的消息，并将其数据写入本地文件

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一 ID |
| fileName | String | 本地文件的路径。这不能是目录 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string) {#savemessageasync_10}

下载指定序号的消息并将其数据写入本地文件

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| fileName | String | 本地文件的路径。这不能是目录 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, Stream, CancellationToken) {#savemessageasync_1}

下载具有指定序列号的消息并将其数据写入提供的流

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| resultStream | Stream | 将接收消息的流 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream, CancellationToken) {#savemessageasync_5}

下载具有指定序列号 的消息并将其数据写入提供的流

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一 ID |
| resultStream | Stream | 将接收消息的流 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string, CancellationToken) {#savemessageasync_7}

下载指定序号 的消息，并将其数据写入本地文件

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一 ID |
| fileName | String | 本地文件的路径。这不能是目录 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string, CancellationToken) {#savemessageasync_3}

下载指定序号的消息并将其数据写入本地文件

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| fileName | String | 本地文件的路径。这不能是目录 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream, CancellationToken) {#savemessageasync_9}

下载具有指定序列号的消息并将其数据写入提供的流

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| resultStream | Stream | 将接收消息的流 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream, CancellationToken) {#savemessageasync_13}

下载具有指定序列号 的消息并将其数据写入提供的流

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一 ID |
| resultStream | Stream | 将接收消息的流 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string, CancellationToken) {#savemessageasync_15}

下载指定序号 的消息，并将其数据写入本地文件

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一 ID |
| fileName | String | 本地文件的路径。这不能是目录 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string, CancellationToken) {#savemessageasync_11}

下载指定序号的消息并将其数据写入本地文件

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| fileName | String | 本地文件的路径。这不能是目录 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
