---
title: IGraphClientAsync.ListTasksAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously lists tasks in the specified task list
type: docs
weight: 430
url: /net/aspose.email.clients.graph/igraphclientasync/listtasksasync/
---
## IGraphClientAsync.ListTasksAsync method

Asynchronously lists tasks in the specified task list.

```csharp
public Task<MapiTaskCollection> ListTasksAsync(string id, ODataQueryBuilder queryBuilder = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | The ID of the task list. |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering tasks. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the collection of [`MapiTask`](../../../aspose.email.mapi/mapitask/).

### See Also

* class [MapiTaskCollection](../../../aspose.email.mapi/mapitaskcollection/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


