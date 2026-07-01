---
title: IGraphClientAsync.CreateTaskAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously creates a task in the specified task list
type: docs
weight: 130
url: /net/aspose.email.clients.graph/igraphclientasync/createtaskasync/
---
## IGraphClientAsync.CreateTaskAsync method

Asynchronously creates a task in the specified task list.

```csharp
public Task<MapiTask> CreateTaskAsync(MapiTask task, string taskListUri, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| task | MapiTask | The [`MapiTask`](../../../aspose.email.mapi/mapitask/) to create. |
| taskListUri | String | The URI of the task list. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created [`MapiTask`](../../../aspose.email.mapi/mapitask/).

### See Also

* class [MapiTask](../../../aspose.email.mapi/mapitask/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


