---
title: FolderInfo.DeleteChildItem
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Deletes the item folder or message by its entryId
type: docs
weight: 210
url: /net/aspose.email.storage.pst/folderinfo/deletechilditem/
---
## FolderInfo.DeleteChildItem method

Deletes the item (folder or message) by it's entryId.

```csharp
public void DeleteChildItem(byte[] entryId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | Byte[] | The entry id. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | throws, if entryId is null. |
| InvalidOperationException | throws, if the item doesn't belong to the folder or the item can't be deleted or entryID has the incorrect value. |
| InvalidOperationException | throws, if a PST is open for reading only. |

## Remarks

The item must be contained in a folder.

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


