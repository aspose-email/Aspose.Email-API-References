---
title: FolderInfo.UpdateMessage
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Updates the message with the specified entry ID
type: docs
weight: 380
url: /net/aspose.email.storage.pst/folderinfo/updatemessage/
---
## FolderInfo.UpdateMessage method

Updates the message with the specified entry ID.

```csharp
public void UpdateMessage(string entryId, MapiMessageItemBase updatedMessage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryId | String | The entry ID of the message to update. |
| updatedMessage | MapiMessageItemBase | The message with the new content. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| InvalidOperationException | The PST is open for reading only. |
| ArgumentNullException | *entryId* is `null` or empty. |
| ArgumentNullException | *updatedMessage* is `null`. |
| InvalidOperationException | *entryId* is not valid. |
| NotImplementedException | The file is an OST of Outlook 2013 or later, which this method cannot edit. |

### See Also

* class [MapiMessageItemBase](../../../aspose.email.mapi/mapimessageitembase/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


