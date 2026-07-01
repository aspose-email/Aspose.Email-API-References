---
title: IGraphClientAsync.ListAttachmentsAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously lists attachments for the specified item
type: docs
weight: 300
url: /net/aspose.email.clients.graph/igraphclientasync/listattachmentsasync/
---
## IGraphClientAsync.ListAttachmentsAsync method

Asynchronously lists attachments for the specified item.

```csharp
public Task<MapiAttachmentCollection> ListAttachmentsAsync(string id, 
    ODataQueryBuilder queryBuilder = null, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | The ID of the parent item (message, event, etc.). |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering attachments. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the collection of [`MapiAttachment`](../../../aspose.email.mapi/mapiattachment/).

### See Also

* class [MapiAttachmentCollection](../../../aspose.email.mapi/mapiattachmentcollection/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


