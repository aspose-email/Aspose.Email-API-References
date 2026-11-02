---
title: FolderInfo.AddMessage
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Adds a message to the folder
type: docs
weight: 150
url: /net/aspose.email.storage.pst/folderinfo/addmessage/
---
## FolderInfo.AddMessage method

Adds a message to the folder.

```csharp
public string AddMessage(MapiMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MapiMessage | The message to add. |

### Return Value

The entry ID of the added message.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| ArgumentNullException | *message* is `null`. |
| InvalidOperationException | The PST is open for reading only. |
| NotImplementedException | The file is an OST of Outlook 2013 or later, which this method cannot edit. |

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


