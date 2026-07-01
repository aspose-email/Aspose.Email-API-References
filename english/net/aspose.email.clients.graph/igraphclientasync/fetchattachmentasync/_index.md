---
title: IGraphClientAsync.FetchAttachmentAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously fetches an attachment by its ID
type: docs
weight: 180
url: /net/aspose.email.clients.graph/igraphclientasync/fetchattachmentasync/
---
## IGraphClientAsync.FetchAttachmentAsync method

Asynchronously fetches an attachment by its ID.

```csharp
public Task<MapiAttachment> FetchAttachmentAsync(string id, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | The ID of the attachment to fetch. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the fetched [`MapiAttachment`](../../../aspose.email.mapi/mapiattachment/).

### See Also

* class [MapiAttachment](../../../aspose.email.mapi/mapiattachment/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


