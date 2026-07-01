---
title: IGraphClientAsync.CreateAttachmentAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously creates an attachment in the specified parent item
type: docs
weight: 40
url: /net/aspose.email.clients.graph/igraphclientasync/createattachmentasync/
---
## IGraphClientAsync.CreateAttachmentAsync method

Asynchronously creates an attachment in the specified parent item.

```csharp
public Task<MapiAttachment> CreateAttachmentAsync(string parentId, MapiAttachment attachment, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentId | String | The ID of the parent item (message, event, etc.). |
| attachment | MapiAttachment | The [`MapiAttachment`](../../../aspose.email.mapi/mapiattachment/) to create. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created [`MapiAttachment`](../../../aspose.email.mapi/mapiattachment/).

### See Also

* class [MapiAttachment](../../../aspose.email.mapi/mapiattachment/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


