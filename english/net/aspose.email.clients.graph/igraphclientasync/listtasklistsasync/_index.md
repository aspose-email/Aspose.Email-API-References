---
title: IGraphClientAsync.ListTaskListsAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously lists task lists
type: docs
weight: 420
url: /net/aspose.email.clients.graph/igraphclientasync/listtasklistsasync/
---
## IGraphClientAsync.ListTaskListsAsync method

Asynchronously lists task lists.

```csharp
public Task<TaskListInfoCollection> ListTaskListsAsync(ODataQueryBuilder queryBuilder = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering task lists. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the collection of [`TaskListInfo`](../../tasklistinfo/).

### See Also

* class [TaskListInfoCollection](../../tasklistinfocollection/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


