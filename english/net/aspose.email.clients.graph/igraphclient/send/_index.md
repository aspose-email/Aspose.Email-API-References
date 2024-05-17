---
title: IGraphClient.Send
second_title: Aspose.Email for .NET API Reference
description: IGraphClient method. Send a message in the draft folder. The draft message can be a new message draft reply draft replyall draft or a forward draft. The message is then saved in the Sent Items folder
type: docs
weight: 430
url: /net/aspose.email.clients.graph/igraphclient/send/
---
## Send(string) {#send_3}

Send a message in the draft folder. The draft message can be a new message draft, reply draft, reply-all draft, or a forward draft. The message is then saved in the Sent Items folder.

```csharp
public void Send(string itemId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| itemId | String | Item id of the draft message |

### See Also

* interface [IGraphClient](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclient/)
* assembly [Aspose.Email](../../../)

---

## Send(MapiMessage) {#send_1}

Sends email message

```csharp
public void Send(MapiMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessage | Mapi message to send |

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* interface [IGraphClient](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclient/)
* assembly [Aspose.Email](../../../)

---

## Send(MapiMessage, bool) {#send_2}

Sends email message

```csharp
public void Send(MapiMessage message, bool saveToSentItems)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessage | Mapi message to send |
| saveToSentItems | Boolean | Indicates whether to save the message in Sent Items. |

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* interface [IGraphClient](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclient/)
* assembly [Aspose.Email](../../../)

---

## Send(MailMessage) {#send}

Sends email message

```csharp
public void Send(MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | MailMessage[`MailMessage`](../../../aspose.email/mailmessage/) to send |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IGraphClient](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclient/)
* assembly [Aspose.Email](../../../)


