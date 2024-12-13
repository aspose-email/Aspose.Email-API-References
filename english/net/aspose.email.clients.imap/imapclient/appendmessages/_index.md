---
title: ImapClient.AppendMessages
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Uploads the mail message to the specified folder
type: docs
weight: 390
url: /net/aspose.email.clients.imap/imapclient/appendmessages/
---
## AppendMessages(string, IEnumerable&lt;MailMessage&gt;) {#appendmessages_3}

Uploads the mail message to the specified folder

```csharp
public AppendMessagesResult AppendMessages(string folderName, IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder that will receive the mail message |
| messages | IEnumerable`1 | Enumeration of email messages to be upload |

### Return Value

An unique id of appended message

### See Also

* class [AppendMessagesResult](../../appendmessagesresult/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessages(IConnection, IEnumerable&lt;MailMessage&gt;) {#appendmessages}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public AppendMessagesResult AppendMessages(IConnection connection, 
    IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| messages | IEnumerable`1 | Enumeration of email messages to be upload |

### Return Value

An unique id of appended message

### See Also

* class [AppendMessagesResult](../../appendmessagesresult/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessages(IConnection, string, IEnumerable&lt;MailMessage&gt;) {#appendmessages_1}

Uploads the mail message to the specified folder

```csharp
public AppendMessagesResult AppendMessages(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Folder that will receive the mail message |
| messages | IEnumerable`1 | Enumeration of email messages to be upload |

### Return Value

An unique id of appended message

### See Also

* class [AppendMessagesResult](../../appendmessagesresult/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessages(IEnumerable&lt;MailMessage&gt;) {#appendmessages_2}

Uploads the mail message to the current folder If current folder hasn't been specified default folder is used.

```csharp
public AppendMessagesResult AppendMessages(IEnumerable<MailMessage> messages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | IEnumerable`1 | Enumeration of email messages to be upload |

### Return Value

An unique id of appended message

### See Also

* class [AppendMessagesResult](../../appendmessagesresult/)
* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


