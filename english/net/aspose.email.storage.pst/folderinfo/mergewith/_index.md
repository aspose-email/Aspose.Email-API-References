---
title: FolderInfo.MergeWith
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Merges the folder with the folder from another pst
type: docs
weight: 320
url: /net/aspose.email.storage.pst/folderinfo/mergewith/
---
## MergeWith(FolderInfo) {#mergewith}

Merges the folder with the folder from another pst.

```csharp
public void MergeWith(FolderInfo sourceFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolder | FolderInfo | The source folder. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Throws when the source folder is located in the same pst. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## MergeWith(FolderInfo, bool) {#mergewith_1}

Merges the folder with the folder from another pst. OnItemMoved event is called on both messages and directories.

```csharp
public void MergeWith(FolderInfo sourceFolder, bool recursiveHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFolder | FolderInfo | The source folder. |
| recursiveHandler | Boolean | If true, OnItemMoved will be called on all messages, including messages in sub-directories, otherwise OnItemMoved will be called only for messages in the current directory. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Throws when the source folder is located in the same pst. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


