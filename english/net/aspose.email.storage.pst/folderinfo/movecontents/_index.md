---
title: FolderInfo.MoveContents
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Moves all messages of this folder to another folder
type: docs
weight: 340
url: /net/aspose.email.storage.pst/folderinfo/movecontents/
---
## FolderInfo.MoveContents method

Moves all messages of this folder to another folder.

```csharp
public void MoveContents(FolderInfo newFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newFolder | FolderInfo | The folder to move the messages to. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| ArgumentNullException | *newFolder* is `null`. |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *newFolder* was not obtained from a [`PersonalStorage`](../../personalstorage/). |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


