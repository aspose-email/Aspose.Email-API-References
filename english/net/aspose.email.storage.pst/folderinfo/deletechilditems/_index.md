---
title: FolderInfo.DeleteChildItems
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Deletes the child messages
type: docs
weight: 220
url: /net/aspose.email.storage.pst/folderinfo/deletechilditems/
---
## FolderInfo.DeleteChildItems method

Deletes the child messages.

```csharp
public void DeleteChildItems(IEnumerable<string> entryIdCollection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryIdCollection | IEnumerable`1 | The entry id collection. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The ANSI file version editing is not implemented. |
| InvalidOperationException | The PST is open for reading only. or The item, to be deleted, doesn't belong to this folder. or The search folder cannot be deleted. or The \Deleted Items\ folder cannot be deleted. or The entryId is incorrect. |
| ArgumentNullException | entryId;The entryId cannot be null. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


