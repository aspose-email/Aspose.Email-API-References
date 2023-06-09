---
title: IEWSClient.Send
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Sends the specified message
type: docs
weight: 1400
url: /net/aspose.email.clients.exchange.webservice/iewsclient/send/
---
## Send(MailMessage) {#send}

Sends the specified message.

```csharp
public void Send(MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | The message. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## Send(string, string, string, string) {#send_2}

Sends the specified message

```csharp
public void Send(string from, string to, string subject, string body)
```

| Parameter | Type | Description |
| --- | --- | --- |
| from | String | From address |
| to | String | To address |
| subject | String | The subject of message |
| body | String | The body of message |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## Send(MailMessage, FollowUpOptions) {#send_1}

Sends the message.

```csharp
public void Send(MailMessage message, FollowUpOptions messageOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | The [`MailMessage`](../../../aspose.email/mailmessage/) to be sent. |
| messageOptions | FollowUpOptions | The [`FollowUpOptions`](../../../aspose.email.mapi/followupoptions/) that represents additional options for using follow-up flags and voting buttons. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [FollowUpOptions](../../../aspose.email.mapi/followupoptions/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


