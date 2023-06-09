---
title: FolderInfo.AddMapiMessageItem
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Adds the IMapiMessageItem object into folder
type: docs
weight: 140
url: /net/aspose.email.storage.pst/folderinfo/addmapimessageitem/
---
## FolderInfo.AddMapiMessageItem method

Adds the IMapiMessageItem object into folder.

```csharp
public string AddMapiMessageItem(IMapiMessageItem item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | IMapiMessageItem | The item necessary to add. |

### Return Value

The string that represents the EntryId of the added item.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws, if a PST file version is ANSI. |
| ArgumentNullException | throws, if an item to add is null. |
| InvalidOperationException | throws, if a PST is open for reading only. |
| NotSupportedException | Thrown when MessageClass doesn't belong to IPM.Note, IPM.StickyNote, IPM.Contact, IPM.Activity, IPM.Appointment, IPM.Schedule.meeting, IPM.Task. |
| InvalidOperationException | Thrown when MessageClass doesn't correspond to the folder's ContainerClass. |

### See Also

* interface [IMapiMessageItem](../../../aspose.email.mapi/imapimessageitem/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


