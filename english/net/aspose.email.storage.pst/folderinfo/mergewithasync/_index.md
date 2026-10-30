---
title: FolderInfo.MergeWithAsync
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Asynchronously merges a folder from another PST into this folder
type: docs
weight: 330
url: /net/aspose.email.storage.pst/folderinfo/mergewithasync/
---
## MergeWithAsync(FolderInfo, CancellationToken) {#mergewithasync_1}

Asynchronously merges a folder from another PST into this folder.

```csharp
public Task MergeWithAsync(FolderInfo sourceFolder, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolder | FolderInfo | The folder to merge. It must belong to another PST. |
| token | CancellationToken | A token to cancel the operation. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | *sourceFolder* belongs to the same PST. |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## MergeWithAsync(FolderInfo, bool, CancellationToken) {#mergewithasync}

Asynchronously merges a folder from another PST into this folder and raises `ItemMoved` for the merged messages and folders.

```csharp
public Task MergeWithAsync(FolderInfo sourceFolder, bool recursiveHandler, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolder | FolderInfo | The folder to merge. It must belong to another PST. |
| token | Boolean | A token to cancel the operation. |
| recursiveHandler | CancellationToken | `true` to raise `ItemMoved` for the messages in the subfolders of *sourceFolder* too; `false` to raise it only for the messages directly in *sourceFolder*. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | *sourceFolder* belongs to the same PST. |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


