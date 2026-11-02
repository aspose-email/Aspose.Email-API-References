---
title: Class FolderCreationOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Pst.FolderCreationOptions class. Options for creating a subfolder with FolderInfo.AddSubFolder whether the name is a path how names are compared and the container class of the new folder
type: docs
weight: 19110
url: /net/aspose.email.storage.pst/foldercreationoptions/
---
## FolderCreationOptions class

Options for creating a subfolder with `FolderInfo.AddSubFolder`: whether the name is a path, how names are compared, and the container class of the new folder.

```csharp
public class FolderCreationOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [FolderCreationOptions](foldercreationoptions/#constructor)() | Initializes a new instance of the `FolderCreationOptions` class with the default settings: the name is not a path, names are compared case-insensitively, and the container class is `IPF.Note`. |
| [FolderCreationOptions](foldercreationoptions/#constructor_1)(bool, bool) | Initializes a new instance of the `FolderCreationOptions` class with the specified parameters. |
| [FolderCreationOptions](foldercreationoptions/#constructor_2)(bool, bool, string) | Initializes a new instance of the `FolderCreationOptions` class with the specified parameters. |

## Properties

| Name | Description |
| --- | --- |
| [AllowNameCaseDifference](../../aspose.email.storage.pst/foldercreationoptions/allownamecasedifference/) { get; set; } | Gets or sets a value indicating whether to allow a difference in name casing when comparing folder names. |
| [ContainerClass](../../aspose.email.storage.pst/foldercreationoptions/containerclass/) { get; set; } | Gets or sets the container class of the new folder, which defines the kind of items it holds, for example `IPF.Note` for mail or `IPF.Appointment` for a calendar. |
| [CreateHierarchy](../../aspose.email.storage.pst/foldercreationoptions/createhierarchy/) { get; set; } | Gets or sets a value indicating whether to create the hierarchy of parent folders. |
| [EnforceContainerClassMatching](../../aspose.email.storage.pst/foldercreationoptions/enforcecontainerclassmatching/) { get; set; } | Gets or sets a value indicating whether the container class of the new folder must match the container class of its parent folder. |

### See Also

* namespace [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst/)
* assembly [Aspose.Email](../../)


