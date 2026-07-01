---
title: IGraphClientAsync.ListFoldersAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously lists folders from the root folder
type: docs
weight: 360
url: /net/aspose.email.clients.graph/igraphclientasync/listfoldersasync/
---
## ListFoldersAsync(ODataQueryBuilder, CancellationToken) {#listfoldersasync}

Asynchronously lists folders from the root folder.

```csharp
public Task<FolderInfoCollection> ListFoldersAsync(ODataQueryBuilder queryBuilder = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering folders. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the list of subfolders of the root folder.

### See Also

* class [FolderInfoCollection](../../folderinfocollection/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(string, ODataQueryBuilder, CancellationToken) {#listfoldersasync_1}

Asynchronously lists folders from the parent folder.

```csharp
public Task<FolderInfoCollection> ListFoldersAsync(string id, 
    ODataQueryBuilder queryBuilder = null, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Parent folder id. |
| queryBuilder | ODataQueryBuilder | Optional OData query builder for filtering folders. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the list of subfolders of the folder.

### See Also

* class [FolderInfoCollection](../../folderinfocollection/)
* class [ODataQueryBuilder](../../odataquerybuilder/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


