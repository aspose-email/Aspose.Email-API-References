---
title: PersonalStorage.FindAndEnumerateSoftDeletedItems
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Finds softdeleted messages and returns them one at a time
type: docs
weight: 240
url: /net/aspose.email.storage.pst/personalstorage/findandenumeratesoftdeleteditems/
---
## PersonalStorage.FindAndEnumerateSoftDeletedItems method

Finds soft-deleted messages and returns them one at a time.

```csharp
public IEnumerable<RestoredItemEntry> FindAndEnumerateSoftDeletedItems()
```

### Return Value

The soft-deleted messages, each with the entry ID of the folder it was in. They are read from the file as the sequence is enumerated.

## Remarks

Soft-deleted messages are messages that have been deleted but whose data is still present in the PST.

### See Also

* class [RestoredItemEntry](../../restoreditementry/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


