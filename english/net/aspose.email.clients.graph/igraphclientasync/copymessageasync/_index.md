---
title: IGraphClientAsync.CopyMessageAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously copies a message to a new parent folder
type: docs
weight: 20
url: /net/aspose.email.clients.graph/igraphclientasync/copymessageasync/
---
## IGraphClientAsync.CopyMessageAsync method

Asynchronously copies a message to a new parent folder.

```csharp
public Task<MapiMessage> CopyMessageAsync(string newParentId, string itemId, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newParentId | String | The ID of the new parent folder. |
| itemId | String | The ID of the message to copy. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the copied [`MapiMessage`](../../../aspose.email.mapi/mapimessage/).

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


