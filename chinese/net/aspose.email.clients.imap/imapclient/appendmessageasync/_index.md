---
title: AppendMessageAsync
second_title: Aspose.Email for .NET API 参考
description: 将邮件信息上传到当前文件夹 如果当前文件夹尚未指定则使用默认文件夹
type: docs
weight: 370
url: /zh/net/aspose.email.clients.imap/imapclient/appendmessageasync/
---
## AppendMessageAsync(IConnection, MailMessage) {#appendmessageasync}

将邮件信息上传到当前文件夹 如果当前文件夹尚未指定，则使用默认文件夹。

```csharp
public Task<string> AppendMessageAsync(IConnection connection, MailMessage message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| message | MailMessage | 邮件到上传 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, MailMessage) {#appendmessageasync_3}

将邮件信息上传到指定文件夹

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, 
    MailMessage message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 将接收邮件的文件夹 |
| message | MailMessage | 要上传的邮件 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string) {#appendmessageasync_2}

将邮件信息上传到当前文件夹 如果当前文件夹尚未指定，则使用默认文件夹。

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| fileName | String | 文件名 ( *.eml) 将上传的邮件消息 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, string) {#appendmessageasync_5}

将邮件信息上传到指定文件夹

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 将接收邮件消息的文件夹 |
| fileName | String | 文件名 (*. eml) 将上传的邮件消息 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(MailMessage) {#appendmessageasync_8}

将邮件信息上传到当前文件夹 如果当前文件夹尚未指定，则使用默认文件夹。

```csharp
public Task<string> AppendMessageAsync(MailMessage message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | MailMessage | 要上传的邮件 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(string, MailMessage) {#appendmessageasync_11}

将邮件信息上传到指定文件夹

```csharp
public Task<string> AppendMessageAsync(string folderName, MailMessage message)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 文件夹将收到邮件消息 |
| message | MailMessage | 要上传的邮件消息 |

### 返回值

任务对象，委托为这个操作

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(string) {#appendmessageasync_10}

将邮件信息上传到当前文件夹 如果当前文件夹尚未指定，则使用默认文件夹。

```csharp
public Task<string> AppendMessageAsync(string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 将上传的邮件的文件名 (*.eml) |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(string, string) {#appendmessageasync_13}

将邮件信息上传到指定文件夹

```csharp
public Task<string> AppendMessageAsync(string folderName, string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 文件夹将收到邮件 |
| fileName | String | 将要上传的邮件的文件名 (*.eml) |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, MailMessage, CancellationToken) {#appendmessageasync_1}

将邮件信息上传到当前文件夹 如果当前文件夹尚未指定，则使用默认文件夹。

```csharp
public Task<string> AppendMessageAsync(IConnection connection, MailMessage message, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| message | MailMessage | 邮件到上传 |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, MailMessage, CancellationToken) {#appendmessageasync_4}

将邮件信息上传到指定文件夹

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, 
    MailMessage message, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 将接收邮件的文件夹 |
| message | MailMessage | 要上传的邮件 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, CancellationToken) {#appendmessageasync_7}

将邮件信息上传到当前文件夹 如果当前文件夹尚未指定，则使用默认文件夹。

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string fileName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| fileName | String | 文件名 ( *.eml) 将上传的邮件消息 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, string, CancellationToken) {#appendmessageasync_6}

将邮件信息上传到指定文件夹

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, string fileName, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 将接收邮件消息的文件夹 |
| fileName | String | 文件名 (*. eml) 将上传的邮件消息 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(MailMessage, CancellationToken) {#appendmessageasync_9}

将邮件信息上传到当前文件夹 如果当前文件夹尚未指定，则使用默认文件夹。

```csharp
public Task<string> AppendMessageAsync(MailMessage message, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | MailMessage | 要上传的邮件 |
| token | CancellationToken | 传播通知该操作应该被取消。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(string, MailMessage, CancellationToken) {#appendmessageasync_12}

将邮件信息上传到指定文件夹

```csharp
public Task<string> AppendMessageAsync(string folderName, MailMessage message, 
    CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 文件夹将收到邮件 |
| message | MailMessage | 待上传邮件 |
| token | CancellationToken | 传播操作通知应该取消。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(string, CancellationToken) {#appendmessageasync_15}

将邮件信息上传到当前文件夹 如果当前文件夹尚未指定，则使用默认文件夹。

```csharp
public Task<string> AppendMessageAsync(string fileName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 将上传的邮件的文件名 (*.eml) |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessageAsync(string, string, CancellationToken) {#appendmessageasync_14}

将邮件信息上传到指定文件夹

```csharp
public Task<string> AppendMessageAsync(string folderName, string fileName, CancellationToken token)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 文件夹将收到邮件 |
| fileName | String | 将要上传的邮件的文件名 (*.eml) |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

任务对象，带有此操作的委托

### 也可以看看

* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
