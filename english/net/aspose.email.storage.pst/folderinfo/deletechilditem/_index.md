---
title: FolderInfo.DeleteChildItem
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Deletes a message or subfolder of this folder by its entry ID
type: docs
weight: 210
url: /net/aspose.email.storage.pst/folderinfo/deletechilditem/
---
## FolderInfo.DeleteChildItem method

Deletes a message or subfolder of this folder by its entry ID.

```csharp
public void DeleteChildItem(byte[] entryId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | Byte[] | The entry ID of the item to delete. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *entryId* is `null`. |
| InvalidOperationException | The item does not belong to this folder or cannot be deleted, or *entryId* is not valid. |
| InvalidOperationException | The PST is open for reading only. |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |

## Remarks

The item must be a direct child of this folder.

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


