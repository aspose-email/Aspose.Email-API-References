---
title: FolderCreationOptions.AllowNameCaseDifference
second_title: Aspose.Email for .NET API Reference
description: FolderCreationOptions property. Gets or sets a value indicating whether to allow a difference in name casing when comparing folder names
type: docs
weight: 20
url: /net/aspose.email.storage.pst/foldercreationoptions/allownamecasedifference/
---
## FolderCreationOptions.AllowNameCaseDifference property

Gets or sets a value indicating whether to allow a difference in name casing when comparing folder names.

```csharp
public bool AllowNameCaseDifference { get; set; }
```

### Property Value

`true` if a difference in name casing should be allowed when comparing folder names; otherwise, `false`. The default value is `false`.

## Remarks

If a folder with the same name already exists when adding a new folder and `AllowNameCaseDifference` is set to `true`, the folder names will be treated as different even if the casing differs. In this case, no exception will be thrown, and the folder will be added. When `AllowNameCaseDifference` is set to `false`, the comparison will be case-insensitive, and the folder creation operation will consider folders with the same name but different casing as duplicates, throwing an InvalidOperationException to indicate that a folder with the specified name already exists.

### See Also

* class [FolderCreationOptions](../)
* namespace [Aspose.Email.Storage.Pst](../../foldercreationoptions/)
* assembly [Aspose.Email](../../../)


