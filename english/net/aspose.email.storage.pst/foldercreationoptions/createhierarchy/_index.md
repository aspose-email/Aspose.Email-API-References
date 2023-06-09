---
title: FolderCreationOptions.CreateHierarchy
second_title: Aspose.Email for .NET API Reference
description: FolderCreationOptions property. Gets or sets a value indicating whether to create the hierarchy of parent folders
type: docs
weight: 40
url: /net/aspose.email.storage.pst/foldercreationoptions/createhierarchy/
---
## FolderCreationOptions.CreateHierarchy property

Gets or sets a value indicating whether to create the hierarchy of parent folders.

```csharp
public bool CreateHierarchy { get; set; }
```

### Property Value

`true` if the hierarchy of parent folders should be created. In this case, the name of the subfolder to be created is considered as path; `false` if only the subfolder with specified name should be created. The default value is `false`.

## Remarks

When specifying the subfolder path, use the backslash (\) as the separator between folder names. For example, "parent1\parent2\subfolder".

### See Also

* class [FolderCreationOptions](../)
* namespace [Aspose.Email.Storage.Pst](../../foldercreationoptions/)
* assembly [Aspose.Email](../../../)


