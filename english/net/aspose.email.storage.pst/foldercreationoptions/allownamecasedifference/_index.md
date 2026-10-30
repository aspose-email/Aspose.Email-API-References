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

When `true`, a folder whose name differs from an existing one only in case is created as a separate folder. When `false`, names are compared case-insensitively, and adding a folder whose name matches an existing one throws `InvalidOperationException`.

### See Also

* class [FolderCreationOptions](../)
* namespace [Aspose.Email.Storage.Pst](../../foldercreationoptions/)
* assembly [Aspose.Email](../../../)


