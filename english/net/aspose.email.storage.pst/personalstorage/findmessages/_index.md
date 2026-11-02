---
title: PersonalStorage.FindMessages
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Finds the entry IDs of the messages of a folder. Use it to read a damaged PST when FolderInfo.GetContents and FolderInfo.EnumerateMessages throw
type: docs
weight: 260
url: /net/aspose.email.storage.pst/personalstorage/findmessages/
---
## PersonalStorage.FindMessages method

Finds the entry IDs of the messages of a folder. Use it to read a damaged PST when `FolderInfo.GetContents` and `FolderInfo.EnumerateMessages` throw.

```csharp
public IList<string> FindMessages(string parentEntryId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentEntryId | String | The entry ID of the folder. |

### Return Value

The entry IDs of the messages.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *parentEntryId* is `null` or empty. |

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


