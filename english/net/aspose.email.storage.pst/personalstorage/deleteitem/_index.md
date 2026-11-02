---
title: PersonalStorage.DeleteItem
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Deletes a message or folder by its entry ID
type: docs
weight: 170
url: /net/aspose.email.storage.pst/personalstorage/deleteitem/
---
## PersonalStorage.DeleteItem method

Deletes a message or folder by its entry ID.

```csharp
public void DeleteItem(string entryId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String | The entry ID of the item to delete. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| ArgumentNullException | *entryId* is `null`. |
| InvalidOperationException | *entryId* identifies the root folder, which cannot be deleted. |

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


