---
title: SaveMessageAsync
second_title: Aspose.Email for .NET API 参考
description: 获取消息并将其保存为流
type: docs
weight: 360
url: /zh/net/aspose.email.clients.pop3/pop3client/savemessageasync/
---
## SaveMessageAsync(IConnection, string, Stream) {#savemessageasync_4}

获取消息并将其保存为流

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一 ID |
| outputStream | Stream | 将保存消息的流 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string) {#savemessageasync_6}

获取消息并将其保存到文件中

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一 ID |
| fileName | String | 消息的文件名 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, Stream) {#savemessageasync}

获取消息并将其保存为流

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| outputStream | Stream | 将保存消息的流 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string) {#savemessageasync_2}

获取消息并将其保存到文件中

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| fileName | String | 消息的文件名 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream) {#savemessageasync_12}

获取消息并将其保存为流

```csharp
public Task SaveMessageAsync(string uniqueId, Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一 ID |
| outputStream | Stream | 将保存消息的流 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string) {#savemessageasync_14}

获取消息并将其保存到文件中

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一 ID |
| fileName | String | 消息的文件名 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream) {#savemessageasync_8}

获取消息并将其保存为流

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| outputStream | Stream | 将保存消息的流 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string) {#savemessageasync_10}

获取消息并将其保存到文件中

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| fileName | String | 消息的文件名 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream, CancellationToken) {#savemessageasync_5}

获取消息并将其保存为流

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream outputStream, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一 ID |
| outputStream | Stream | 将保存消息的流 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string, CancellationToken) {#savemessageasync_7}

获取消息并将其保存到文件中

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一 ID |
| fileName | String | 消息的文件名 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, Stream, CancellationToken) {#savemessageasync_1}

获取消息并将其保存为流

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream outputStream, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| outputStream | Stream | 将保存消息的流 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string, CancellationToken) {#savemessageasync_3}

获取消息并将其保存到文件中

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| fileName | String | 消息的文件名 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream, CancellationToken) {#savemessageasync_13}

获取消息并将其保存为流

```csharp
public Task SaveMessageAsync(string uniqueId, Stream outputStream, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一 ID |
| outputStream | Stream | 将保存消息的流 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string, CancellationToken) {#savemessageasync_15}

获取消息并将其保存到文件中

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一 ID |
| fileName | String | 消息的文件名 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream, CancellationToken) {#savemessageasync_9}

获取消息并将其保存为流

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream outputStream, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| outputStream | Stream | 将保存消息的流 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string, CancellationToken) {#savemessageasync_11}

获取消息并将其保存到文件中

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| fileName | String | 消息的文件名 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
