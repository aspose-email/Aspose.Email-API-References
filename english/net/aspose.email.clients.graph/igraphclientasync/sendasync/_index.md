---
title: IGraphClientAsync.SendAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously sends a draft message by its ID
type: docs
weight: 470
url: /net/aspose.email.clients.graph/igraphclientasync/sendasync/
---
## SendAsync(string, CancellationToken) {#sendasync_3}

Asynchronously sends a draft message by its ID.

```csharp
public Task SendAsync(string itemId, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| itemId | String | The ID of the draft message to send. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous send operation.

### See Also

* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)

---

## SendAsync(MapiMessage, CancellationToken) {#sendasync_2}

Asynchronously sends a [`MapiMessage`](../../../aspose.email.mapi/mapimessage/).

```csharp
public Task SendAsync(MapiMessage message, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessage | The [`MapiMessage`](../../../aspose.email.mapi/mapimessage/) to send. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous send operation.

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)

---

## SendAsync(MapiMessage, bool, CancellationToken) {#sendasync_1}

Asynchronously sends a [`MapiMessage`](../../../aspose.email.mapi/mapimessage/) with an option to save to Sent Items.

```csharp
public Task SendAsync(MapiMessage message, bool saveToSentItems, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessage | The [`MapiMessage`](../../../aspose.email.mapi/mapimessage/) to send. |
| saveToSentItems | Boolean | Whether to save the message to Sent Items. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous send operation.

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)

---

## SendAsync(MailMessage, CancellationToken) {#sendasync}

Asynchronously sends a [`MailMessage`](../../../aspose.email/mailmessage/).

```csharp
public Task SendAsync(MailMessage message, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | The [`MailMessage`](../../../aspose.email/mailmessage/) to send. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous send operation.

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


