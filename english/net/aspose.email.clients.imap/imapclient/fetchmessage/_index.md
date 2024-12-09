---
title: ImapClient.FetchMessage
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Fetches the message
type: docs
weight: 660
url: /net/aspose.email.clients.imap/imapclient/fetchmessage/
---
## FetchMessage(IConnection, int) {#fetchmessage}

Fetches the message

```csharp
public MailMessage FetchMessage(IConnection connection, int sequenceNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of message |

### Return Value

[`MailMessage`](../../../aspose.email/mailmessage/) that represents e-mail message

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## FetchMessage(IConnection, int, bool) {#fetchmessage_1}

Fetches the message

```csharp
public MailMessage FetchMessage(IConnection connection, int sequenceNumber, bool ignoreAttachment)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of message |
| ignoreAttachment | Boolean | A value that defines whether the attachments should not be loaded. If it is set to `true`, then only message headers, message body and attachment information are fetched. Attachment content is not loaded |

### Return Value

[`MailMessage`](../../../aspose.email/mailmessage/) that represents e-mail message

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## FetchMessage(int) {#fetchmessage_3}

Fetches the message

```csharp
public MailMessage FetchMessage(int sequenceNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of message |

### Return Value

[`MailMessage`](../../../aspose.email/mailmessage/) that represents e-mail message

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## FetchMessage(int, bool) {#fetchmessage_4}

Fetches the message

```csharp
public MailMessage FetchMessage(int sequenceNumber, bool ignoreAttachment)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of message |
| ignoreAttachment | Boolean | A value that defines whether the attachments should not be loaded. If it is set to `true`, then only message headers, message body and attachment information are fetched. Attachment content is not loaded |

### Return Value

[`MailMessage`](../../../aspose.email/mailmessage/) that represents e-mail message

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## FetchMessage(IConnection, string) {#fetchmessage_2}

Fetches the message

```csharp
public MailMessage FetchMessage(IConnection connection, string uniqueId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique id of message |

### Return Value

[`MailMessage`](../../../aspose.email/mailmessage/) that represents e-mail message

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## FetchMessage(string) {#fetchmessage_5}

Fetches the message

```csharp
public MailMessage FetchMessage(string uniqueId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique id of message |

### Return Value

[`MailMessage`](../../../aspose.email/mailmessage/) that represents e-mail message

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


