---
title: FolderInfo.DeleteChildItems
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Deletes the specified messages of the folder
type: docs
weight: 220
url: /net/aspose.email.storage.pst/folderinfo/deletechilditems/
---
## FolderInfo.DeleteChildItems method

Deletes the specified messages of the folder.

```csharp
public void DeleteChildItems(IEnumerable<string> entryIdCollection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryIdCollection | IEnumerable`1 | The entry IDs of the messages to delete. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | The PST is open for reading only. |
| InvalidOperationException | An item does not belong to this folder or cannot be deleted, such as a search folder or the Deleted Items folder, or an entry ID is not valid. |
| ArgumentNullException | *entryIdCollection* is `null`. |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


