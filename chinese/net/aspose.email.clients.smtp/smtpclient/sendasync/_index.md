---
title: SendAsync
second_title: Aspose.Email for .NET API 参考
description: 创建并发送指定的消息
type: docs
weight: 180
url: /zh/net/aspose.email.clients.smtp/smtpclient/sendasync/
---
## SendAsync(string, string, string, string) {#sendasync_18}

创建并发送指定的消息。

```csharp
public Task SendAsync(string from, string recipients, string subject, string body)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| from | String | 一个包含消息发送者地址的字符串。 |
| recipients | String | 包含收件人地址的字符串。 |
| subject | String | 消息的主题。 |
| body | String | 消息体。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(MailMessage) {#sendasync_11}

发送指定消息。

```csharp
public Task SendAsync(MailMessage message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | MailMessage | 表示电子邮件消息的 MailMessage。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(params MailMessage[]) {#sendasync_15}

发送指定消息。

```csharp
public Task SendAsync(params MailMessage[] messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messages | MailMessage[] | 表示要发送的电子邮件消息的 MailMessage 数组。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection) {#sendasync_13}

发送指定的消息集合。

```csharp
public Task SendAsync(MailMessageCollection messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messages | MailMessageCollection | 消息的集合。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;) {#sendasync_16}

发送指定的消息。

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messages | IEnumerable`1 | 支持消息迭代的 IEnumerator。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string) {#sendasync_7}

创建并发送指定的消息。

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| from | String | 一个包含消息发送者地址的字符串。 |
| recipients | String | 包含收件人地址的字符串。 |
| subject | String | 消息的主题。 |
| body | String | 消息体。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage) {#sendasync}

发送指定消息。

```csharp
public Task SendAsync(IConnection connection, MailMessage message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| message | MailMessage | 表示电子邮件消息的 MailMessage。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(IConnection, params MailMessage[]) {#sendasync_4}

发送指定消息。

```csharp
public Task SendAsync(IConnection connection, params MailMessage[] messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messages | MailMessage[] | 表示要发送的电子邮件消息的 MailMessage 数组。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection) {#sendasync_2}

发送指定的消息集合。

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messages | MailMessageCollection | 消息的集合。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#sendasync_5}

发送指定的消息。

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messages | IEnumerable`1 | 支持消息迭代的 IEnumerator。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(string, string, string, string, CancellationToken) {#sendasync_19}

创建并发送指定的消息。

```csharp
public Task SendAsync(string from, string recipients, string subject, string body, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| from | String | 一个包含消息发送者地址的字符串。 |
| recipients | String | 包含收件人地址的字符串。 |
| subject | String | 消息的主题。 |
| body | String | 消息体。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(MailMessage, CancellationToken) {#sendasync_12}

发送指定消息。

```csharp
public Task SendAsync(MailMessage message, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | MailMessage | 表示电子邮件消息的 MailMessage。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(CancellationToken, params MailMessage[]) {#sendasync_20}

发送指定消息。

```csharp
public Task SendAsync(CancellationToken token, params MailMessage[] messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| token | CancellationToken | 传播应取消操作的通知。 |
| messages | MailMessage[] | 表示要发送的电子邮件消息的 MailMessage 数组。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection, CancellationToken) {#sendasync_14}

发送指定的消息集合。

```csharp
public Task SendAsync(MailMessageCollection messages, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messages | MailMessageCollection | 消息的集合。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_17}

发送指定的消息。

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messages | IEnumerable`1 | 支持消息迭代的 IEnumerator。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string, CancellationToken) {#sendasync_8}

创建并发送指定的消息。

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| from | String | 一个包含消息发送者地址的字符串。 |
| recipients | String | 包含收件人地址的字符串。 |
| subject | String | 消息的主题。 |
| body | String | 消息体。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage, CancellationToken) {#sendasync_1}

发送指定消息。

```csharp
public Task SendAsync(IConnection connection, MailMessage message, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| message | MailMessage | 表示电子邮件消息的 MailMessage。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(IConnection, CancellationToken, params MailMessage[]) {#sendasync_9}

发送指定消息。

```csharp
public Task SendAsync(IConnection connection, CancellationToken token, 
    params MailMessage[] messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| token | CancellationToken | 传播应取消操作的通知。 |
| messages | MailMessage[] | 表示要发送的电子邮件消息的 MailMessage 数组。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection, CancellationToken) {#sendasync_3}

发送指定的消息集合。

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messages | MailMessageCollection | 消息的集合。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_6}

发送指定的消息。

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messages | IEnumerable`1 | 支持消息迭代的 IEnumerator。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## SendAsync(SmtpSend) {#sendasync_10}

```csharp
public Task SendAsync(SmtpSend parameters)
```

### 也可以看看

* class [SmtpSend](../../../aspose.email.clients.smtp.models/smtpsend)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
