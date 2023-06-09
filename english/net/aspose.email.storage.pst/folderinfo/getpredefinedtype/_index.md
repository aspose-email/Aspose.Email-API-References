---
title: FolderInfo.GetPredefinedType
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Gets the type of predefined folder
type: docs
weight: 290
url: /net/aspose.email.storage.pst/folderinfo/getpredefinedtype/
---
## FolderInfo.GetPredefinedType method

Gets the type of predefined folder.

```csharp
public StandardIpmFolder GetPredefinedType(bool getForTopLevelParent)
```

| Parameter | Type | Description |
| --- | --- | --- |
| getForTopLevelParent | Boolean | If true, returns the predefined type for the top-level parent folder. This determines whether the current folder is a subfolder of a predefined folder. If false, it returns the predefined type for the current folder. |

### Return Value

The [`StandardIpmFolder`](../../standardipmfolder/) enum value. If the folder is not predefined, it returns Unspecified

## Remarks

Checks if the folder is predefined by returning the corresponding type.

### See Also

* enum [StandardIpmFolder](../../standardipmfolder/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


