---
title: FolderInfo.AddMapiMessageItem
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Adds a message contact appointment meeting task note or journal item to the folder
type: docs
weight: 140
url: /net/aspose.email.storage.pst/folderinfo/addmapimessageitem/
---
## FolderInfo.AddMapiMessageItem method

Adds a message, contact, appointment, meeting, task, note or journal item to the folder.

```csharp
public string AddMapiMessageItem(IMapiMessageItem item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | IMapiMessageItem | The item to add. |

### Return Value

The entry ID of the added item.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| ArgumentNullException | *item* is `null`. |
| InvalidOperationException | The PST is open for reading only. |
| NotSupportedException | The message class of *item* is not IPM.Note, IPM.StickyNote, IPM.Contact, IPM.Activity, IPM.Appointment, IPM.Schedule.Meeting or IPM.Task. |
| InvalidOperationException | The message class of *item* does not match the container class of the folder. |

### See Also

* interface [IMapiMessageItem](../../../aspose.email.mapi/imapimessageitem/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


