---
title: FolderInfo.MoveSubfolders
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Moves all subfolders of this folder to another parent folder
type: docs
weight: 350
url: /net/aspose.email.storage.pst/folderinfo/movesubfolders/
---
## FolderInfo.MoveSubfolders method

Moves all subfolders of this folder to another parent folder.

```csharp
public void MoveSubfolders(FolderInfo newFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newFolder | FolderInfo | The new parent folder. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| ArgumentNullException | *newFolder* is `null`. |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *newFolder* was not obtained from a [`PersonalStorage`](../../personalstorage/). |
| InvalidOperationException | *newFolder* is a subfolder of this folder. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


