---
title: IGraphClientAsync.ListNotebooksAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously lists notebooks
type: docs
weight: 380
url: /net/aspose.email.clients.graph/igraphclientasync/listnotebooksasync/
---
## IGraphClientAsync.ListNotebooksAsync method

Asynchronously lists notebooks.

```csharp
public Task<NotebookCollection> ListNotebooksAsync(ODataQueryBuilder queryBuilder = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering notebooks. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the collection of [`Notebook`](../../notebook/).

### See Also

* class [NotebookCollection](../../notebookcollection/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


