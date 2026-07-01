---
title: FolderInfo.SetReadStatus
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Sets or clears the Read status for the specified messages in a PST file
type: docs
weight: 370
url: /net/aspose.email.storage.pst/folderinfo/setreadstatus/
---
## FolderInfo.SetReadStatus method

Sets or clears the `Read` status for the specified messages in a PST file.

```csharp
public void SetReadStatus(IList<string> messageEntryIds, bool isRead)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageEntryIds | IList`1 | A list of message entry IDs that identify the messages whose read status should be updated. |
| isRead | Boolean | `true` to mark the messages as read; `false` to mark them as unread. |

## Remarks

This method updates the read/unread state of existing messages without modifying their content or other message properties.

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


