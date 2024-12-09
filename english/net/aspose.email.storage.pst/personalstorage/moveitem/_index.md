---
title: PersonalStorage.MoveItem
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Moves a specified message to a new folder within the current pst
type: docs
weight: 320
url: /net/aspose.email.storage.pst/personalstorage/moveitem/
---
## MoveItem(MessageInfo, FolderInfo) {#moveitem_1}

Moves a specified message to a new folder within the current pst.

```csharp
public void MoveItem(MessageInfo message, FolderInfo newFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MessageInfo | The message to move. |
| newFolder | FolderInfo | The new folder for the message. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when message is null. |
| ArgumentNullException | Thrown when new folder is null. |
| NotImplementedException | Thrown when attempting to edit the ANSI file version. |

### See Also

* class [MessageInfo](../../messageinfo/)
* class [FolderInfo](../../folderinfo/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## MoveItem(FolderInfo, FolderInfo) {#moveitem}

Moves a specified folder to a new parent folder within the current pst.

```csharp
public void MoveItem(FolderInfo folder, FolderInfo newFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | FolderInfo | The folder to move. |
| newFolder | FolderInfo | The new parent folder. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when message is null. |
| ArgumentNullException | Thrown when new folder is null. |
| NotImplementedException | Thrown when attempting to edit the ANSI file version. |
| InvalidOperationException | Thrown when there is an attempt to move the root folder, which is not a valid operation because a root folder should maintain its position in the hierarchy. |
| InvalidOperationException | Thrown when there is an attempt to move a folder into itself. |
| InvalidOperationException | Thrown when there is an attempt to move a folder into one of its own subfolders. |

### See Also

* class [FolderInfo](../../folderinfo/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


