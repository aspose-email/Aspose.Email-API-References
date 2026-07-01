---
title: IGraphClientAsync.CreateFolderAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously creates a new folder
type: docs
weight: 80
url: /net/aspose.email.clients.graph/igraphclientasync/createfolderasync/
---
## CreateFolderAsync(string, CancellationToken) {#createfolderasync_1}

Asynchronously creates a new folder.

```csharp
public Task<FolderInfo> CreateFolderAsync(string folderName, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Folder name. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created folder.

### See Also

* class [FolderInfo](../../folderinfo/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)

---

## CreateFolderAsync(string, string, CancellationToken) {#createfolderasync}

Asynchronously creates a new folder under a parent folder.

```csharp
public Task<FolderInfo> CreateFolderAsync(string parentFolderId, string folderName, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderId | String | Parent folder id. |
| folderName | String | Folder name. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created folder.

### See Also

* class [FolderInfo](../../folderinfo/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


