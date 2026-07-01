---
title: IGmailClientAsync.AppendMessageAsync
second_title: Aspose.Email for .NET API Reference
description: IGmailClientAsync method. Asynchronously appends a message to the default INBOX label
type: docs
weight: 10
url: /net/aspose.email.clients.google/igmailclientasync/appendmessageasync/
---
## AppendMessageAsync(MailMessage, CancellationToken) {#appendmessageasync_1}

Asynchronously appends a message to the default "INBOX" label.

```csharp
public Task<string> AppendMessageAsync(MailMessage msg, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MailMessage | The message to append. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the message ID.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)

---

## AppendMessageAsync(MailMessage, string, CancellationToken) {#appendmessageasync}

Asynchronously appends a message to the specified label.

```csharp
public Task<string> AppendMessageAsync(MailMessage msg, string labelName, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| msg | MailMessage | The message to append. |
| labelName | String | The label name. |
| cancellationToken | CancellationToken | A cancellation token. |

### Return Value

A task that represents the asynchronous operation. The task result contains the message ID.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IGmailClientAsync](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclientasync/)
* assembly [Aspose.Email](../../../)


