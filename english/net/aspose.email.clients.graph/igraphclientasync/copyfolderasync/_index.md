---
title: IGraphClientAsync.CopyFolderAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously copies a mailfolder and its contents to another mailfolder
type: docs
weight: 10
url: /net/aspose.email.clients.graph/igraphclientasync/copyfolderasync/
---
## IGraphClientAsync.CopyFolderAsync method

Asynchronously copies a mailfolder and its contents to another mailfolder.

```csharp
public Task<FolderInfo> CopyFolderAsync(string newParentId, string itemId, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newParentId | String | New parent folder id. |
| itemId | String | Item id to be copied. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the copied folder.

### See Also

* class [FolderInfo](../../folderinfo/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


