---
title: ImapClient.FetchMessages
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Fetches the messages
type: docs
weight: 680
url: /net/aspose.email.clients.imap/imapclient/fetchmessages/
---
## FetchMessages(IEnumerable&lt;int&gt;) {#fetchmessages_2}

Fetches the messages

```csharp
public IList<MailMessage> FetchMessages(IEnumerable<int> sequenceNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumbers | IEnumerable`1 | The sequence numbers of the messages |

### Return Value

List of [`MailMessage`](../../../aspose.email/mailmessage/) objects

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## FetchMessages(IEnumerable&lt;string&gt;) {#fetchmessages_3}

Fetches the messages

```csharp
public IList<MailMessage> FetchMessages(IEnumerable<string> uids)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uids | IEnumerable`1 | The sequence numbers of the messages |

### Return Value

List of [`MailMessage`](../../../aspose.email/mailmessage/) objects

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## FetchMessages(IConnection, IEnumerable&lt;int&gt;) {#fetchmessages}

Fetches the messages

```csharp
public IList<MailMessage> FetchMessages(IConnection connection, IEnumerable<int> sequenceNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumbers | IEnumerable`1 | The sequence numbers of the messages |

### Return Value

List of [`MailMessage`](../../../aspose.email/mailmessage/) objects

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## FetchMessages(IConnection, IEnumerable&lt;string&gt;) {#fetchmessages_1}

Fetches the messages

```csharp
public IList<MailMessage> FetchMessages(IConnection connection, IEnumerable<string> uids)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uids | IEnumerable`1 | The sequence numbers of the messages |

### Return Value

List of [`MailMessage`](../../../aspose.email/mailmessage/) objects

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


