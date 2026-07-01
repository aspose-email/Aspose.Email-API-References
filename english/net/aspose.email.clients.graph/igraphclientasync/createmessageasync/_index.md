---
title: IGraphClientAsync.CreateMessageAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously creates a message in the specified folder
type: docs
weight: 90
url: /net/aspose.email.clients.graph/igraphclientasync/createmessageasync/
---
## CreateMessageAsync(string, MapiMessage, CancellationToken) {#createmessageasync_1}

Asynchronously creates a message in the specified folder.

```csharp
public Task<MapiMessage> CreateMessageAsync(string folderId, MapiMessage message, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderId | String | The ID of the folder where the message will be created. |
| message | MapiMessage | The [`MapiMessage`](../../../aspose.email.mapi/mapimessage/) to create. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created [`MapiMessage`](../../../aspose.email.mapi/mapimessage/).

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)

---

## CreateMessageAsync(string, MailMessage, CancellationToken) {#createmessageasync}

Asynchronously creates a mail message in the specified folder.

```csharp
public Task<MailMessage> CreateMessageAsync(string folderId, MailMessage message, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderId | String | The ID of the folder where the mail message will be created. |
| message | MailMessage | The [`MailMessage`](../../../aspose.email/mailmessage/) to create. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created [`MailMessage`](../../../aspose.email/mailmessage/).

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


