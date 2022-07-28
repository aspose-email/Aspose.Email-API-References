---
title: ListMessagesAsync
second_title: Aspose.Email for .NET API 参考
description: 列出消息 获取搜索消息的信息
type: docs
weight: 300
url: /zh/net/aspose.email.clients.pop3/pop3client/listmessagesasync/
---
## ListMessagesAsync(IConnection) {#listmessagesasync_1}

列出消息。 获取搜索消息的信息

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |

### 返回值

任务对象，具有此操作的委托

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_8}

列出消息。 获取搜索消息的信息

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| closeTransaction | Boolean | 指示在检索列表之前是否必须关闭当前事务。 |

### 返回值

任务对象，具有此操作的委托

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_6}

列出消息。

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| query | MailQuery | 这[`MailQuery`](../../../aspose.email.tools.search/mailquery)目的。 |

### 返回值

Pop3MessageInfo 对象的集合。

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields) {#listmessagesasync_2}

列出消息。

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| fields | Pop3ListFields | 我们想要得到的字段 |

### 返回值

任务对象，具有此操作的委托

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery) {#listmessagesasync_3}

列出消息。

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| fields | Pop3ListFields | 我们想要得到的字段 |
| closeTransaction | Boolean | 指示在检索列表之前是否必须关闭当前事务。 |
| query | MailQuery | 这[`MailQuery`](../../../aspose.email.tools.search/mailquery)目的。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

列出消息。 获取搜索消息的信息

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync()
```

### 返回值

任务对象，具有此操作的委托

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_17}

列出消息。 获取搜索消息的信息

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| closeTransaction | Boolean | 指示在检索列表之前是否必须关闭当前事务。 |

### 返回值

任务对象，具有此操作的委托

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_15}

列出消息。

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| query | MailQuery | 这[`MailQuery`](../../../aspose.email.tools.search/mailquery)目的。 |

### 返回值

Pop3MessageInfo 对象的集合。

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields) {#listmessagesasync_11}

列出消息。

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fields | Pop3ListFields | 我们想要得到的字段 |

### 返回值

任务对象，具有此操作的委托

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery) {#listmessagesasync_12}

列出消息。

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fields | Pop3ListFields | 我们想要得到的字段 |
| closeTransaction | Boolean | 指示在检索列表之前是否必须关闭当前事务。 |
| query | MailQuery | 这[`MailQuery`](../../../aspose.email.tools.search/mailquery)目的。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_10}

列出消息。 获取搜索消息的信息

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_9}

列出消息。 获取搜索消息的信息

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| closeTransaction | Boolean | 指示在检索列表之前是否必须关闭当前事务。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_7}

列出消息。

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| query | MailQuery | 这[`MailQuery`](../../../aspose.email.tools.search/mailquery)目的。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

Pop3MessageInfo 对象的集合。

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, CancellationToken) {#listmessagesasync_5}

列出消息。

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| fields | Pop3ListFields | 我们想要得到的字段 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_4}

列出消息。

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| fields | Pop3ListFields | 我们想要得到的字段 |
| closeTransaction | Boolean | 指示在检索列表之前是否必须关闭当前事务。 |
| query | MailQuery | 这[`MailQuery`](../../../aspose.email.tools.search/mailquery)目的。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_19}

列出消息。 获取搜索消息的信息

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_18}

列出消息。 获取搜索消息的信息

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| closeTransaction | Boolean | 指示在检索列表之前是否必须关闭当前事务。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_16}

列出消息。

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| query | MailQuery | 这[`MailQuery`](../../../aspose.email.tools.search/mailquery)目的。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

Pop3MessageInfo 对象的集合。

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, CancellationToken) {#listmessagesasync_14}

列出消息。

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fields | Pop3ListFields | 我们想要得到的字段 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 评论

请注意，标记为已删除的邮件未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_13}

列出消息。

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fields | Pop3ListFields | 我们想要得到的字段 |
| closeTransaction | Boolean | 指示在检索列表之前是否必须关闭当前事务。 |
| query | MailQuery | 这[`MailQuery`](../../../aspose.email.tools.search/mailquery)目的。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
