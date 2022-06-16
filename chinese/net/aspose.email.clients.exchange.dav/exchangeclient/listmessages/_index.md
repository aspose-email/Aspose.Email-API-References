---
title: ListMessages
second_title: Aspose.Email for .NET API 参考
description: 列出消息
type: docs
weight: 280
url: /zh/net/aspose.email.clients.exchange.dav/exchangeclient/listmessages/
---
## ListMessages(string) {#listmessages}

列出消息。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 文件夹。 |

### 返回值

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_4}

列出消息。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 文件夹。 |
| maxNumberOfMessages | Int32 | 最大消息数 |

### 返回值

AExchangeMessageInfoCollection

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_7}

列出消息。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string messageClass, 
    bool recursive)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 文件夹。 |
| messageClass | String | 消息类。 |
| recursive | Boolean | 如果设置为` true` [递归]。 |

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_3}

列出指定文件夹中的消息

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 文件夹 Uri |
| recursive | Boolean | 表示是否递归列出。 |

### 返回值

消息信息集合

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, string) {#listmessages_6}

列出消息。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 文件夹。 |
| query | String | 查询。 |

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_2}

列出消息。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 包含消息的文件夹的 Uri。 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示搜索条件。 |
| recursive | Boolean | 表示是否递归列出。 |

### 返回值

消息信息集合。

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_1}

列出指定文件夹中的邮件消息。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 文件夹 URL |
| options | ExchangeListMessagesOptions | 指定列表 |

### 返回值

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)集合。

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_5}

列出指定文件夹中的消息

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 文件夹 Uri |
| maxNumberOfMessages | Int32 | 最大消息数 |
| options | ExchangeListMessagesOptions | 指定列表设置 |

### 返回值

消息信息集合

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
