---
title: FolderInfo.UpdateMessage
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Updates the message in folder
type: docs
weight: 360
url: /net/aspose.email.storage.pst/folderinfo/updatemessage/
---
## FolderInfo.UpdateMessage method

Updates the message in folder.

```csharp
public void UpdateMessage(string entryId, MapiMessageItemBase updatedMessage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String | The message entry identifier. |
| updatedMessage | MapiMessageItemBase | The updated message. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The ANSI file version editing is not implemented. |
| InvalidOperationException | The PST is open for reading only. or The entryId is incorrect. |
| ArgumentNullException | entryId; The entry id cannot be null or empty. or updatedMessage; The message cannot be null. |

### See Also

* class [MapiMessageItemBase](../../../aspose.email.mapi/mapimessageitembase/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


