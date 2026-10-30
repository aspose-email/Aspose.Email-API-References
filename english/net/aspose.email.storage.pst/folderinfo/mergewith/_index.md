---
title: FolderInfo.MergeWith
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Merges a folder from another PST into this folder
type: docs
weight: 320
url: /net/aspose.email.storage.pst/folderinfo/mergewith/
---
## MergeWith(FolderInfo) {#mergewith}

Merges a folder from another PST into this folder.

```csharp
public void MergeWith(FolderInfo sourceFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolder | FolderInfo | The folder to merge. It must belong to another PST. |

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

## MergeWith(FolderInfo, bool) {#mergewith_1}

Merges a folder from another PST into this folder and raises `ItemMoved` for the merged messages and folders.

```csharp
public void MergeWith(FolderInfo sourceFolder, bool recursiveHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolder | FolderInfo | The folder to merge. It must belong to another PST. |
| recursiveHandler | Boolean | `true` to raise `ItemMoved` for the messages in the subfolders of *sourceFolder* too; `false` to raise it only for the messages directly in *sourceFolder*. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | *sourceFolder* belongs to the same PST. |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


