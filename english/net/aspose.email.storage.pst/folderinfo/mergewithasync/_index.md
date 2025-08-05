---
title: FolderInfo.MergeWithAsync
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Merges the folder with the folder from another pst
type: docs
weight: 330
url: /net/aspose.email.storage.pst/folderinfo/mergewithasync/
---
## MergeWithAsync(FolderInfo, CancellationToken) {#mergewithasync_1}

Merges the folder with the folder from another pst.

```csharp
public Task MergeWithAsync(FolderInfo sourceFolder, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolder | FolderInfo | The source folder. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Throws when the source folder is located in the same pst. |
| NotImplementedException | Thrown when attempting to edit the ANSI file version. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## MergeWithAsync(FolderInfo, bool, CancellationToken) {#mergewithasync}

Merges the folder with the folder from another pst. OnItemMoved event is called on both messages and directories.

```csharp
public Task MergeWithAsync(FolderInfo sourceFolder, bool recursiveHandler, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolder | FolderInfo | The source folder. |
| token | Boolean | Propagates notification that operations should be canceled. |
| recursiveHandler | CancellationToken | If true, OnItemMoved will be called on all messages, including messages in sub-directories, otherwise OnItemMoved will be called only for messages in the current directory. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Throws when the source folder is located in the same pst. |
| NotImplementedException | Thrown when attempting to edit the ANSI file version. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


