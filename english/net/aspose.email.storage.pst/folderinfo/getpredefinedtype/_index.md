---
title: FolderInfo.GetPredefinedType
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Gets which standard Outlook folder such as Inbox or Sent Items this folder is
type: docs
weight: 290
url: /net/aspose.email.storage.pst/folderinfo/getpredefinedtype/
---
## FolderInfo.GetPredefinedType method

Gets which standard Outlook folder, such as Inbox or Sent Items, this folder is.

```csharp
public StandardIpmFolder GetPredefinedType(bool getForTopLevelParent)
```

| Parameter | Type | Description |
| --- | --- | --- |
| getForTopLevelParent | Boolean | `true` to check the top-level folder this folder belongs to, which tells whether it is inside a standard folder; `false` to check this folder itself. |

### Return Value

The [`StandardIpmFolder`](../../standardipmfolder/) value, or `StandardIpmFolder.Unspecified` if the folder is not a standard one.

## Remarks

Use it to find out whether a folder is, or lies inside, one of the standard Outlook folders.

### See Also

* enum [StandardIpmFolder](../../standardipmfolder/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


