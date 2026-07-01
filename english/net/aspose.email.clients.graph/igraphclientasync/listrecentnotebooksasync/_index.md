---
title: IGraphClientAsync.ListRecentNotebooksAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously lists recent notebooks
type: docs
weight: 400
url: /net/aspose.email.clients.graph/igraphclientasync/listrecentnotebooksasync/
---
## IGraphClientAsync.ListRecentNotebooksAsync method

Asynchronously lists recent notebooks.

```csharp
public Task<NotebookCollection> ListRecentNotebooksAsync(bool includePersonalNotebooks, 
    ODataQueryBuilder queryBuilder = null, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| includePersonalNotebooks | Boolean | Whether to include personal notebooks in the result. |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering notebooks. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the collection of recent [`Notebook`](../../notebook/).

### See Also

* class [NotebookCollection](../../notebookcollection/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


