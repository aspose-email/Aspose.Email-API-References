---
title: ListMessages
second_title: Aspose.Email for .NET API 参考
description: 列出消息
type: docs
weight: 1140
url: /zh/net/aspose.email.clients.exchange.webservice/iewsclient/listmessages/
---
## ListMessages(string) {#listmessages_2}

列出消息。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 文件夹。 |

### 返回值

一个[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_3}

列出消息。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 文件夹。 |
| options | ExchangeListMessagesOptions | 指定列表的设置 |

### 返回值

一个[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_8}

列出消息。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 文件夹。 |
| maxNumberOfMessages | Int32 | 最大消息数 |

### 返回值

一个[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_9}

列出消息。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 文件夹。 |
| maxNumberOfMessages | Int32 | 最大消息数 |
| options | ExchangeListMessagesOptions | 指定列表的设置 |

### 返回值

一个[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_13}

列出指定文件夹中的邮件

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, bool recursive)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mailbox | String | 用于初始化文件夹 id 类的邮箱。 |
| folder | String | 用于搜索邮件的文件夹 |
| recursive | Boolean | 指示是否递归列表 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的邮件

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, string, MailQuery) {#listmessages_12}

列出指定文件夹中的邮件。

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mailbox | String | 用于初始化文件夹 id 类的邮箱。 |
| folder | String | 用于搜索邮件的文件夹。 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示消息搜索条件。 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的邮件。

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_7}

列出指定文件夹中的邮件

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于搜索邮件的文件夹 |
| recursive | Boolean | 指示是否递归列表 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的邮件

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) {#listmessages_4}

列出指定文件夹中的邮件

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options, IEnumerable<PropertyDescriptor> extendedProperties)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于搜索邮件的文件夹 |
| options | ExchangeListMessagesOptions | 指定列表的设置 |
| extendedProperties | IEnumerable`1 | 检索到的消息的扩展属性 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的邮件

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery) {#listmessages_5}

列出指定文件夹中的邮件。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于在其中搜索邮件的文件夹。 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示消息搜索条件。 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的消息。

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_6}

列出指定文件夹中的邮件。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于在其中搜索邮件的文件夹。 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示消息搜索条件。 |
| recursive | Boolean | 表示是否递归列出。 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的消息。

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery, bool) {#listmessages_11}

列出指定文件夹中的邮件。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query, bool recursive)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于搜索邮件的文件夹。 |
| maxNumberOfMessages | Int32 | 最大消息数。 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示消息搜索条件。 |
| recursive | Boolean | 指示是否递归列表。 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的邮件。

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_1}

列出指定文件夹中的邮件。

```csharp
public ExchangeMessageInfoCollection ListMessages(IEnumerable<string> iDs)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| iDs | IEnumerable`1 | 消息 ID 的枚举 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含的消息。

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

列出收件箱文件夹中的邮件。

```csharp
public ExchangeMessageInfoCollection ListMessages()
```

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)从收件箱文件夹。

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery) {#listmessages_10}

列出指定文件夹中的邮件。

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folder | String | 用于搜索邮件的文件夹。 |
| maxNumberOfMessages | Int32 | 最大消息数。 |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)表示消息搜索条件。 |

### 返回值

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)包含来自指定文件夹的邮件。

### 也可以看看

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
