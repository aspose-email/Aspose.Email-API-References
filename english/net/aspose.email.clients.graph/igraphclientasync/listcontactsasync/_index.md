---
title: IGraphClientAsync.ListContactsAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously lists MapiContact from the parent folder
type: docs
weight: 350
url: /net/aspose.email.clients.graph/igraphclientasync/listcontactsasync/
---
## IGraphClientAsync.ListContactsAsync method

Asynchronously lists MapiContact from the parent folder.

```csharp
public Task<MapiContactCollection> ListContactsAsync(string id, 
    ODataQueryBuilder queryBuilder = null, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Parent folder id. |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering contacts. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the list of MapiContact of the folder.

### See Also

* class [MapiContactCollection](../../../aspose.email.mapi/mapicontactcollection/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


