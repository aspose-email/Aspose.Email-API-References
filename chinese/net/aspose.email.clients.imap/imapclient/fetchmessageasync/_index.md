---
title: FetchMessageAsync
second_title: Aspose.Email for .NET API 参考
description: 获取消息
type: docs
weight: 660
url: /zh/net/aspose.email.clients.imap/imapclient/fetchmessageasync/
---
## FetchMessageAsync(IConnection, int) {#fetchmessageasync}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, bool) {#fetchmessageasync_1}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    bool ignoreAttachment)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| ignoreAttachment | Boolean | 定义是否不应加载附件的值。 如果设置为`真的`，则只获取邮件标题、邮件正文和附件信息。 未加载附件内容 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## FetchMessageAsync(int) {#fetchmessageasync_6}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## FetchMessageAsync(int, bool) {#fetchmessageasync_7}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, bool ignoreAttachment)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| ignoreAttachment | Boolean | 定义是否不应加载附件的值。 如果设置为`真的`，则只获取邮件标题、邮件正文和附件信息。 未加载附件内容 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, string) {#fetchmessageasync_4}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, string uniqueId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一id |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## FetchMessageAsync(string) {#fetchmessageasync_10}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一id |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, CancellationToken) {#fetchmessageasync_3}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, bool, CancellationToken) {#fetchmessageasync_2}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    bool ignoreAttachment, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| sequenceNumber | Int32 | 消息的序号 |
| ignoreAttachment | Boolean | 定义是否不应加载附件的值。 如果设置为`真的`，则只获取邮件标题、邮件正文和附件信息。 未加载附件内容 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## FetchMessageAsync(int, CancellationToken) {#fetchmessageasync_9}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## FetchMessageAsync(int, bool, CancellationToken) {#fetchmessageasync_8}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, bool ignoreAttachment, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sequenceNumber | Int32 | 消息的序号 |
| ignoreAttachment | Boolean | 定义是否不应加载附件的值。 如果设置为`真的`，则只获取邮件标题、邮件正文和附件信息。 未加载附件内容 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, string, CancellationToken) {#fetchmessageasync_5}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, string uniqueId, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| uniqueId | String | 消息的唯一id |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## FetchMessageAsync(string, CancellationToken) {#fetchmessageasync_11}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uniqueId | String | 消息的唯一id |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，具有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
