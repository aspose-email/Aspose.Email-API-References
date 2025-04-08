---
title: IGmailClient.AppendMessage
second_title: Aspose.Email for .NET API Reference
description: IGmailClient method. Directly appends a message into INBOX similar to IMAP APPEND bypassing most scanning and classification. Does not send a message
type: docs
weight: 10
url: /net/aspose.email.clients.google/igmailclient/appendmessage/
---
## AppendMessage(MailMessage) {#appendmessage}

Directly appends a message into INBOX similar to IMAP APPEND, bypassing most scanning and classification. Does not send a message.

```csharp
public string AppendMessage(MailMessage msg)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MailMessage | MailMerssage that will be appended. |

### Return Value

The Id of appended message.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IGmailClient](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessage(MailMessage, string) {#appendmessage_1}

Directly appends a message into only this user's mailbox similar to IMAP APPEND, bypassing most scanning and classification. Does not send a message.

```csharp
public string AppendMessage(MailMessage msg, string labelName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MailMessage | MailMerssage that will be appended. |
| labelName | String | The name of Label that will be appplied to appended message.If name null or empty then label INBOX will be applied. |

### Return Value

The Id of appended message.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IGmailClient](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclient/)
* assembly [Aspose.Email](../../../)


