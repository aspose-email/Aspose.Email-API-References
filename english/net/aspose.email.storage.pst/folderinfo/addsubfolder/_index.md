---
title: FolderInfo.AddSubFolder
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Adds a subfolder. With createHierarchy the name can be a path and the missing folders are created
type: docs
weight: 170
url: /net/aspose.email.storage.pst/folderinfo/addsubfolder/
---
## AddSubFolder(string, bool) {#addsubfolder_2}

Adds a subfolder. With *createHierarchy*, the name can be a path, and the missing folders are created.

```csharp
public FolderInfo AddSubFolder(string name, bool createHierarchy)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the subfolder, or a path such as `Parent\Child` when *createHierarchy* is `true`. |
| createHierarchy | Boolean | `true` to treat *name* as a path separated by backslashes and create the folders that do not exist yet. |

### Return Value

The new subfolder.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| ArgumentNullException | *name* is `null` or empty. |
| InvalidOperationException | The PST is open for reading only. |

## Remarks

The new folder gets the container class of this folder, or `IPF.Note` if this folder has none.

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## AddSubFolder(string) {#addsubfolder}

Adds a subfolder with the specified name.

```csharp
public FolderInfo AddSubFolder(string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the subfolder. |

### Return Value

The new subfolder.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| ArgumentNullException | *name* is `null` or empty. |
| InvalidOperationException | The PST is open for reading only. |
| InvalidOperationException | A subfolder with this name already exists. Names are compared case-insensitively. |

## Remarks

The new folder gets the container class of this folder, or `IPF.Note` if this folder has none.

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## AddSubFolder(string, string) {#addsubfolder_3}

Adds a subfolder with the specified name and container class.

```csharp
public FolderInfo AddSubFolder(string name, string containerClass)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the subfolder. |
| containerClass | String | The container class of the new folder, for example `IPF.Note` for mail or `IPF.Appointment` for a calendar. |

### Return Value

The new subfolder.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| ArgumentNullException | *name* is `null` or empty. |
| InvalidOperationException | The PST is open for reading only. |
| InvalidOperationException | A subfolder with this name already exists. Names are compared case-insensitively. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## AddSubFolder(string, FolderCreationOptions) {#addsubfolder_1}

Adds a subfolder with the specified name to the current folder using the provided creation options.

```csharp
public FolderInfo AddSubFolder(string name, FolderCreationOptions creationOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the subfolder to add. |
| creationOptions | FolderCreationOptions | The options for creating the subfolder. |

### Return Value

The [`FolderInfo`](../) representing the added subfolder.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws, if a PST file version is ANSI. |
| ArgumentNullException | throws, if a subfolder name is null or empty. |
| InvalidOperationException | throws, if a PST is open for reading only. |
| InvalidOperationException | throws, if a folder with same name already exists. Whether folders have the same name will depend on the [`AllowNameCaseDifference`](../../foldercreationoptions/allownamecasedifference/) parameter. |

## Remarks

*name* can be a path with backslash separators, such as `Parent1\Parent2\Subfolder`; set `FolderCreationOptions.CreateHierarchy` to create the parent folders that do not exist yet. Whether a folder with the same name already exists depends on `FolderCreationOptions.AllowNameCaseDifference`: when it is `false` (the default), names are compared case-insensitively and an existing name throws `InvalidOperationException`; when it is `true`, a name that differs only in case creates a new folder.

## Examples

This example creates a folder three levels deep, adding the parent folders that are missing.

[C#]

```csharp
using (var pst = PersonalStorage.FromFile("archive.pst"))
{
    // Treat the name as a path and create the folders that do not exist yet
    var options = new FolderCreationOptions { CreateHierarchy = true };

    var folder = pst.RootFolder.AddSubFolder(@"Projects\2026\Reports", options);
    Console.WriteLine($"Created {folder.DisplayName}");
}
```

[Visual Basic]

```csharp
Using pst As PersonalStorage = PersonalStorage.FromFile("archive.pst")
    ' Treat the name as a path and create the folders that do not exist yet
    Dim options As New FolderCreationOptions With {.CreateHierarchy = True}

    Dim folder As FolderInfo = pst.RootFolder.AddSubFolder("Projects\2026\Reports", options)
    Console.WriteLine($"Created {folder.DisplayName}")
End Using
```

### See Also

* class [FolderCreationOptions](../../foldercreationoptions/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


