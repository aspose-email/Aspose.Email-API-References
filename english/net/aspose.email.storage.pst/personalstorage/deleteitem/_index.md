---
title: PersonalStorage.DeleteItem
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Deletes the item folder or message by its entryId
type: docs
weight: 160
url: /net/aspose.email.storage.pst/personalstorage/deleteitem/
---
## PersonalStorage.DeleteItem method

Deletes the item (folder or message) by it's entryId

```csharp
public void DeleteItem(string entryId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String |  |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws, if a PST file version is ANSI. |
| ArgumentNullException | throws, if entryId is null. |
| InvalidOperationException | throws, when trying to delete the root folder |

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


