---
title: ForwardAsync
second_title: Aspose.Email for .NET API 参考
description: 将指定邮件转发给收件人
type: docs
weight: 140
url: /zh/net/aspose.email.clients.smtp/smtpclient/forwardasync/
---
## ForwardAsync(IConnection, string, string, MailMessage) {#forwardasync_4}

将指定邮件转发给收件人

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sender | String | 转发消息的发件人。 |
| recipient | String | 转发消息的收件人。 |
| message | MailMessage | 转发消息。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage) {#forwardasync}

将指定邮件转发给收件人

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sender | String | 转发消息的发件人。 |
| recipients | MailAddressCollection | 转发消息的收件人。 |
| message | MailMessage | 转发消息。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage) {#forwardasync_10}

将指定邮件转发给收件人

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sender | String | 转发消息的发件人。 |
| recipient | String | 转发消息的收件人。 |
| message | MailMessage | 转发消息。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage) {#forwardasync_6}

将指定邮件转发给收件人

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sender | String | 转发消息的发件人。 |
| recipients | MailAddressCollection | 转发消息的收件人。 |
| message | MailMessage | 转发消息。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream) {#forwardasync_2}

将指定邮件转发给收件人

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sender | String | 转发消息的发件人。 |
| recipients | MailAddressCollection | 转发消息的收件人。 |
| messageStream | Stream | 以 eml 格式表示消息的流。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream) {#forwardasync_8}

将指定邮件转发给收件人

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sender | String | 转发消息的发件人。 |
| recipients | MailAddressCollection | 转发消息的收件人。 |
| messageStream | Stream | 以 eml 格式表示消息的流。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, string, MailMessage, CancellationToken) {#forwardasync_5}

将指定邮件转发给收件人

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sender | String | 转发消息的发件人。 |
| recipient | String | 转发消息的收件人。 |
| message | MailMessage | 转发消息。 |
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

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_1}

将指定邮件转发给收件人

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sender | String | 转发消息的发件人。 |
| recipients | MailAddressCollection | 转发消息的收件人。 |
| message | MailMessage | 转发消息。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage, CancellationToken) {#forwardasync_11}

将指定邮件转发给收件人

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sender | String | 转发消息的发件人。 |
| recipient | String | 转发消息的收件人。 |
| message | MailMessage | 转发消息。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_7}

将指定邮件转发给收件人

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sender | String | 转发消息的发件人。 |
| recipients | MailAddressCollection | 转发消息的收件人。 |
| message | MailMessage | 转发消息。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_3}

将指定邮件转发给收件人

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sender | String | 转发消息的发件人。 |
| recipients | MailAddressCollection | 转发消息的收件人。 |
| messageStream | Stream | 以 eml 格式表示消息的流。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_9}

将指定邮件转发给收件人

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sender | String | 转发消息的发件人。 |
| recipients | MailAddressCollection | 转发消息的收件人。 |
| messageStream | Stream | 以 eml 格式表示消息的流。 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* 命名空间 [Aspose.Email.Clients.Smtp](../../smtpclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
