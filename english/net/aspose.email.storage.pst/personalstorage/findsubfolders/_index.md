---
title: PersonalStorage.FindSubfolders
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Finds the entry IDs of the subfolders of a folder. Use it to read a damaged PST when FolderInfo.GetSubFolders and FolderInfo.EnumerateFolders throw
type: docs
weight: 270
url: /net/aspose.email.storage.pst/personalstorage/findsubfolders/
---
## PersonalStorage.FindSubfolders method

Finds the entry IDs of the subfolders of a folder. Use it to read a damaged PST when `FolderInfo.GetSubFolders` and `FolderInfo.EnumerateFolders` throw.

```csharp
public IList<string> FindSubfolders(string parentEntryId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentEntryId | String | The entry ID of the folder. |

### Return Value

The entry IDs of the subfolders.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *parentEntryId* is `null` or empty. |

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


