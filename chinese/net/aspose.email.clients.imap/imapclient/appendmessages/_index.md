---
title: AppendMessages
second_title: Aspose.Email for .NET API 参考
description: 将邮件信息上传到当前文件夹 如果当前文件夹尚未指定则使用默认文件夹
type: docs
weight: 380
url: /zh/net/aspose.email.clients.imap/imapclient/appendmessages/
---
## AppendMessages(IConnection, IEnumerable&lt;MailMessage&gt;) {#appendmessages}

将邮件信息上传到当前文件夹 如果当前文件夹尚未指定，则使用默认文件夹。

```csharp
public AppendMessagesResult AppendMessages(IConnection connection, 
    IEnumerable<MailMessage> messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| messages | IEnumerable`1 | 电子邮件枚举要上传的消息 |

### 返回值

附加消息的唯一 ID

### 也可以看看

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessages(IConnection, string, IEnumerable&lt;MailMessage&gt;) {#appendmessages_1}

将邮件信息上传到指定文件夹

```csharp
public AppendMessagesResult AppendMessages(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | IConnection | 连接到服务器 |
| folderName | String | 将接收邮件的文件夹 |
| messages | IEnumerable`1 | 电子邮件消息的枚举上传 |

### 返回值

附加消息的唯一 ID

### 也可以看看

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessages(IEnumerable&lt;MailMessage&gt;) {#appendmessages_2}

将邮件信息上传到当前文件夹 如果当前文件夹尚未指定，则使用默认文件夹。

```csharp
public AppendMessagesResult AppendMessages(IEnumerable<MailMessage> messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messages | IEnumerable`1 | 要上传的电子邮件消息的枚举 |

### 返回值

唯一附加消息的 ID

### 也可以看看

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

---

## AppendMessages(string, IEnumerable&lt;MailMessage&gt;) {#appendmessages_3}

将邮件信息上传到指定文件夹

```csharp
public AppendMessagesResult AppendMessages(string folderName, IEnumerable<MailMessage> messages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderName | String | 文件夹将收到邮件 |
| messages | IEnumerable`1 | 要上传的电子邮件消息的枚举 |

### 返回值

的唯一 ID附加消息

### 也可以看看

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../imapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->