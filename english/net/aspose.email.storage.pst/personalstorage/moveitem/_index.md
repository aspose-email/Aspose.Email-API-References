---
title: PersonalStorage.MoveItem
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Moves a message to another folder of the same PST
type: docs
weight: 350
url: /net/aspose.email.storage.pst/personalstorage/moveitem/
---
## MoveItem(MessageInfo, FolderInfo) {#moveitem_1}

Moves a message to another folder of the same PST.

```csharp
public void MoveItem(MessageInfo message, FolderInfo newFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MessageInfo | The message to move. |
| newFolder | FolderInfo | The folder to move the message to. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *message* is `null`. |
| ArgumentNullException | *newFolder* is `null`. |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |

### See Also

* class [MessageInfo](../../messageinfo/)
* class [FolderInfo](../../folderinfo/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## MoveItem(FolderInfo, FolderInfo) {#moveitem}

Moves a folder to another parent folder of the same PST.

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
| ArgumentNullException | *folder* is `null`. |
| ArgumentNullException | *newFolder* is `null`. |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| InvalidOperationException | *folder* is the root folder, which cannot be moved. |
| InvalidOperationException | *newFolder* is *folder* itself. |
| InvalidOperationException | *newFolder* is a subfolder of *folder*. |

### See Also

* class [FolderInfo](../../folderinfo/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


