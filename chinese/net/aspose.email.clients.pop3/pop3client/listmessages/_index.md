---
title: ListMessages
second_title: Aspose.Email for .NET API 参考
description: 列出消息 获取每个搜索消息的信息
type: docs
weight: 290
url: /zh/net/aspose.email.clients.pop3/pop3client/listmessages/
---
## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_13}

列出消息。 获取每个搜索消息的信息

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<string> uniqueIdLst)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueIdLst | IEnumerable`1 | Pop3MessageInfo从服务器检索。 |

### 返回值

Pop3MessageInfoCollection

### 评论

注意标记为已删除的消息未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;int&gt;) {#listmessages_12}

列出消息。 获取每个搜索消息的信息

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<int> sequenceNumberLst)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumberLst | IEnumerable`1 | Pop3MessageInfo从服务器检索。 |

### 返回值

Pop3MessageInfoCollection

### 评论

注意标记为已删除的消息未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;string&gt;) {#listmessages_7}

列出消息。 获取每条消息的信息

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<string> uniqueIdLst)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueIdLst | IEnumerable`1 | UniqueId 列表用于[`Pop3MessageInfo`](../../pop3messageinfo)从服务器检索。 |

### 返回值

Pop3MessageInfoCollection

### 评论

注意标记为已删除的消息未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;int&gt;) {#listmessages_6}

列出消息。 获取每条消息的信息

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<int> sequenceNumberLst)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumberLst | IEnumerable`1 | sequenceNumber 列表用于[`Pop3MessageInfo`](../../pop3messageinfo)从服务器检索。 |

### 返回值

Pop3MessageInfoCollection

### 评论

注意标记为已删除的消息未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

列出消息。 获取每条消息的信息

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |

### 返回值

Pop3MessageInfoCollection

### 评论

请注意，标记为已删除的消息未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_5}

列出消息。 获取每条消息的信息

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, bool closeTransaction)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| closeTransaction | Boolean | 指示在检索列表之前是否必须关闭当前事务。 |

### 返回值

Pop3MessageInfoCollection

### 评论

请注意，标记为已删除的消息未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_4}

列出消息。

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)对象。 |

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

## ListMessages(IConnection, Pop3ListFields) {#listmessages_2}

列出消息。

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| fields | Pop3ListFields | 我们要获取 |

### 返回值

Pop3MessageInfoCollection

### 评论

请注意，标记为已删除的消息未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IConnection, Pop3ListFields, bool, MailQuery) {#listmessages_3}

列出消息。

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| fields | Pop3ListFields | 我们要获取 |
| closeTransaction | Boolean | 指示当前事务是否必须在检索列表之前关闭。 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)对象。 |

### 返回值

Pop3MessageInfoCollection

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

列出消息。 获取每条消息的信息

```csharp
public Pop3MessageInfoCollection ListMessages()
```

### 返回值

Pop3MessageInfoCollection

### 评论

请注意，标记为已删除的消息未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_11}

列出消息。 获取每条消息的信息

```csharp
public Pop3MessageInfoCollection ListMessages(bool closeTransaction)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| closeTransaction | Boolean | 指示当前事务是否必须在检索列表之前关闭。 |

### 返回值

Pop3MessageInfoCollection

### 评论

请注意，标记为已删除的消息未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_10}

列出消息。

```csharp
public Pop3MessageInfoCollection ListMessages(MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)对象。 |

### 返回值

Pop3MessageInfo 对象的集合。

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields) {#listmessages_8}

列出消息。

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fields | Pop3ListFields | 我们想要获取的字段 |

### 返回值

Pop3MessageInfoCollection

### 评论

注意消息标记为已删除未列出

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields, bool, MailQuery) {#listmessages_9}

列出消息。

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields, bool closeTransaction, 
    MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fields | Pop3ListFields | 我们要获取的字段 |
| closeTransaction | Boolean | 表示如果必须关闭当前事务，则在检索列表之前。 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)对象。 |

### 返回值

Pop3MessageInfoCollection

### 也可以看看

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../pop3client)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
