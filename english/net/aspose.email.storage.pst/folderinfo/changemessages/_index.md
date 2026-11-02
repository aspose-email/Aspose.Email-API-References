---
title: FolderInfo.ChangeMessages
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Sets the specified properties on the given messages of the folder
type: docs
weight: 200
url: /net/aspose.email.storage.pst/folderinfo/changemessages/
---
## ChangeMessages(IEnumerable&lt;string&gt;, MapiPropertyCollection) {#changemessages_1}

Sets the specified properties on the given messages of the folder.

```csharp
public void ChangeMessages(IEnumerable<string> entryIdCollection, 
    MapiPropertyCollection updatedProperties)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryIdCollection | IEnumerable`1 | The entry IDs of the messages to change. |
| updatedProperties | MapiPropertyCollection | The properties to set. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| InvalidOperationException | The PST is open for reading only. |
| ArgumentNullException | *entryIdCollection* is `null`. |
| ArgumentNullException | *updatedProperties* is `null`. |
| InvalidOperationException | An entry ID in *entryIdCollection* is not valid. |

### See Also

* class [MapiPropertyCollection](../../../aspose.email.mapi/mapipropertycollection/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## ChangeMessages(MapiPropertyCollection) {#changemessages}

Sets the specified properties on all messages of the folder.

```csharp
public void ChangeMessages(MapiPropertyCollection updatedProperties)
```

| Parameter | Type | Description |
| --- | --- | --- |
| updatedProperties | MapiPropertyCollection | The properties to set. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| InvalidOperationException | The PST is open for reading only. |
| ArgumentNullException | *updatedProperties* is `null`. |

### See Also

* class [MapiPropertyCollection](../../../aspose.email.mapi/mapipropertycollection/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


