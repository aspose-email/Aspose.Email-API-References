---
title: FolderInfo.AddSubFolder
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Adds the new subfolder
type: docs
weight: 170
url: /net/aspose.email.storage.pst/folderinfo/addsubfolder/
---
## AddSubFolder(string, bool) {#addsubfolder_1}

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

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## AddSubFolder(string, string) {#addsubfolder_2}

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

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


