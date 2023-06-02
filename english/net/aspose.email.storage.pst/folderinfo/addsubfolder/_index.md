---
title: FolderInfo.AddSubFolder
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Adds the new subfolder
type: docs
weight: 170
url: /net/aspose.email.storage.pst/folderinfo/addsubfolder/
---
## AddSubFolder(string, bool) {#addsubfolder_2}

Adds the new sub-folder.

```csharp
public FolderInfo AddSubFolder(string name, bool createHierarchy)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of sub-folder. |
| createHierarchy | Boolean | if set to `true`, it is possible to create a folder hierarchy using string notation. Backslash ('\') is used as path separator. |

### Return Value

The new sub-folder.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws, if a PST file version is ANSI. |
| ArgumentNullException | throws, if a sub-folder name is null or empty. |
| InvalidOperationException | throws, if a PST is open for reading only. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## AddSubFolder(string) {#addsubfolder}

Adds the new sub-folder.

```csharp
public FolderInfo AddSubFolder(string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of sub-folder. |

### Return Value

The new sub-folder.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws, if a PST file version is ANSI. |
| ArgumentNullException | throws, if a sub-folder name is null or empty. |
| InvalidOperationException | throws, if a PST is open for reading only. |
| InvalidOperationException | throws, if a folder with same name already exists. The comparison will be case-insensitive, and the folder creation operation will consider folders with the same name but different casing as duplicates. |

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## AddSubFolder(string, string) {#addsubfolder_3}

Adds the new subfolder.

```csharp
public FolderInfo AddSubFolder(string name, string containerClass)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of subfolder. |
| containerClass | String | Container class of the sub-Folder object. |

### Return Value

The new subfolder.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws, if a PST file version is ANSI. |
| ArgumentNullException | throws, if a subfolder name is null or empty. |
| InvalidOperationException | throws, if a PST is open for reading only. |
| InvalidOperationException | throws, if a folder with same name already exists. The comparison will be case-insensitive, and the folder creation operation will consider folders with the same name but different casing as duplicates. |

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

The *name* parameter specifies the name of the subfolder to add. The *creationOptions* parameter allows customization of the subfolder creation behavior, such as specifying whether to create the hierarchy of parent folders and the container class of the new subfolder. If the subfolder with the specified name already exists, the behavior depends on the value of [`AllowNameCaseDifference`](../../foldercreationoptions/allownamecasedifference/). If [`AllowNameCaseDifference`](../../foldercreationoptions/allownamecasedifference/) is set to `true`, a difference in name casing will be allowed, and the subfolder will be added even if an existing folder with the same name but in a different case exists. If [`AllowNameCaseDifference`](../../foldercreationoptions/allownamecasedifference/) is set to `false`, the comparison will be case-insensitive, and an InvalidOperationException will be thrown to indicate that a folder with the specified name already exists. The name may contain backslash (\) as the path separators (for example, "parent1\parent2\subfolder"). In this case if [`CreateHierarchy`](../../foldercreationoptions/createhierarchy/) is set to `true`, the hierarchy of parent folders should be created.

### See Also

* class [FolderCreationOptions](../../foldercreationoptions/)
* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


