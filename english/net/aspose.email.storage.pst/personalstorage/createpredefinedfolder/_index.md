---
title: PersonalStorage.CreatePredefinedFolder
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Creates the standard interpersonal message IPM folder
type: docs
weight: 150
url: /net/aspose.email.storage.pst/personalstorage/createpredefinedfolder/
---
## CreatePredefinedFolder(string, StandardIpmFolder, bool) {#createpredefinedfolder_1}

Creates the standard interpersonal message (IPM) folder.

```csharp
public FolderInfo CreatePredefinedFolder(string name, StandardIpmFolder defaultFolder, 
    bool createHierarchy)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of folder. |
| defaultFolder | StandardIpmFolder | The value of [`StandardIpmFolder`](../../standardipmfolder/) enumeration. |
| createHierarchy | Boolean | if set to `true`, it is possible to create a folder hierarchy using string notation. Backslash ('\') is used as path separator. |

### Return Value

A [`FolderInfo`](../../folderinfo/) object that represents a standard IPM folder.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws, if a PST file version is ANSI. |

### See Also

* class [FolderInfo](../../folderinfo/)
* enum [StandardIpmFolder](../../standardipmfolder/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## CreatePredefinedFolder(string, StandardIpmFolder) {#createpredefinedfolder}

Creates the standard interpersonal message (IPM) folder.

```csharp
public FolderInfo CreatePredefinedFolder(string name, StandardIpmFolder defaultFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of folder. |
| defaultFolder | StandardIpmFolder | The value of [`StandardIpmFolder`](../../standardipmfolder/) enumeration. |

### Return Value

A [`FolderInfo`](../../folderinfo/) object that represents a standard IPM folder.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Thrown when attempting to modify a PST file that is open for reading only. |
| NotImplementedException | Thrown when attempting to edit the ANSI file version. |
| InvalidOperationException | Thrown when standard folder already exists. |
| NotImplementedException | Thrown when attempting to edit the OST file format. |

### See Also

* class [FolderInfo](../../folderinfo/)
* enum [StandardIpmFolder](../../standardipmfolder/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


