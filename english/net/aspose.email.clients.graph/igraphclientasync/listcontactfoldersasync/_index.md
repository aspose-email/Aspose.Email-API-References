---
title: IGraphClientAsync.ListContactFoldersAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously gets a collection of child folders under the root contact folder
type: docs
weight: 340
url: /net/aspose.email.clients.graph/igraphclientasync/listcontactfoldersasync/
---
## IGraphClientAsync.ListContactFoldersAsync method

Asynchronously gets a collection of child folders under the root contact folder.

```csharp
public Task<FolderInfoCollection> ListContactFoldersAsync(ODataQueryBuilder queryBuilder = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering contact folders. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the list of subfolders of the root contact folder.

### See Also

* class [FolderInfoCollection](../../folderinfocollection/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


