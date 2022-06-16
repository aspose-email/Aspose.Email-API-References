---
title: Send
second_title: Aspose.Email for .NET API 参考
description: 创建并发送指定的消息
type: docs
weight: 170
url: /zh/net/aspose.email.clients.smtp/smtpclient/send/
---
## Send(string, string, string, string) {#send_9}

创建并发送指定的消息。

```csharp
public void Send(string from, string recipients, string subject, string body)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| from | String | 包含消息发送者地址的字符串。 |
| recipients | String | 包含收件人地址的字符串。 |
| subject | String | 消息的主题。 |
| body | String | 消息体。 |

### 也可以看看

* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## Send(MailMessage) {#send_5}

发送指定消息。

```csharp
public void Send(MailMessage message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | MailMessage | 代表电子邮件消息的 MailMessage。 |

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## Send(params MailMessage[]) {#send_7}

发送指定消息。

```csharp
public void Send(params MailMessage[] messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messages | MailMessage[] | MailMessage 数组，表示要发送的电子邮件消息。 |

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## Send(MailMessageCollection) {#send_6}

发送指定的消息集合。

```csharp
public void Send(MailMessageCollection messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messages | MailMessageCollection | 消息的集合。 |

### 也可以看看

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## Send(IEnumerable&lt;MailMessage&gt;) {#send_8}

发送指定消息。

```csharp
public void Send(IEnumerable<MailMessage> messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messages | IEnumerable`1 | 支持消息迭代的 IEnumerator。 |

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## Send(IConnection, string, string, string, string) {#send_4}

创建并发送指定的消息。

```csharp
public void Send(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| from | String | 一个字符串包含消息发送者的地址。 |
| recipients | String | 包含收件人地址的字符串。 |
| subject | String | 消息的主题。 |
| body | String | 消息体。 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## Send(IConnection, MailMessage) {#send}

发送指定消息。

```csharp
public void Send(IConnection connection, MailMessage message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| message | MailMessage | MailMessage表示电子邮件消息。 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## Send(IConnection, params MailMessage[]) {#send_2}

发送指定消息。

```csharp
public void Send(IConnection connection, params MailMessage[] messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messages | MailMessage[] | 的数组MailMessage 表示要发送的电子邮件消息。 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## Send(IConnection, MailMessageCollection) {#send_1}

发送指定的消息集合。

```csharp
public void Send(IConnection connection, MailMessageCollection messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messages | MailMessageCollection | 的集合消息。 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## Send(IConnection, IEnumerable&lt;MailMessage&gt;) {#send_3}

发送指定消息。

```csharp
public void Send(IConnection connection, IEnumerable<MailMessage> messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messages | IEnumerable`1 | IEnumerator支持消息迭代。 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
