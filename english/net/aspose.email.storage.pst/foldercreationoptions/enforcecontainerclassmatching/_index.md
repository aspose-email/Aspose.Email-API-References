---
title: FolderCreationOptions.EnforceContainerClassMatching
second_title: Aspose.Email for .NET API Reference
description: FolderCreationOptions property. Gets or sets a value indicating whether the container class of the new folder must match the container class of its parent folder
type: docs
weight: 50
url: /net/aspose.email.storage.pst/foldercreationoptions/enforcecontainerclassmatching/
---
## FolderCreationOptions.EnforceContainerClassMatching property

Gets or sets a value indicating whether the container class of the new folder must match the container class of its parent folder.

```csharp
public bool EnforceContainerClassMatching { get; set; }
```

### Property Value

`true` to require matching container classes; otherwise, `false`. The default is `false`.

## Remarks

When `true`, adding a folder whose container class differs from that of the parent folder throws `InvalidOperationException`.

### See Also

* class [FolderCreationOptions](../)
* namespace [Aspose.Email.Storage.Pst](../../foldercreationoptions/)
* assembly [Aspose.Email](../../../)


