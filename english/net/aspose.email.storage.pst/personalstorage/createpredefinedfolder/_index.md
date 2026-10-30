---
title: PersonalStorage.CreatePredefinedFolder
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Creates a standard Outlook folder such as Inbox or Calendar with the specified name
type: docs
weight: 160
url: /net/aspose.email.storage.pst/personalstorage/createpredefinedfolder/
---
## CreatePredefinedFolder(string, StandardIpmFolder, bool) {#createpredefinedfolder_1}

Creates a standard Outlook folder, such as Inbox or Calendar, with the specified name.

```csharp
public FolderInfo CreatePredefinedFolder(string name, StandardIpmFolder defaultFolder, 
    bool createHierarchy)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the folder. |
| defaultFolder | StandardIpmFolder | Which standard folder to create. |
| createHierarchy | Boolean | `true` to treat *name* as a path separated by backslashes and create the folders that do not exist yet. |

### Return Value

The new folder.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |

### See Also

* class [FolderInfo](../../folderinfo/)
* enum [StandardIpmFolder](../../standardipmfolder/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## CreatePredefinedFolder(string, StandardIpmFolder) {#createpredefinedfolder}

Creates a standard Outlook folder, such as Inbox or Calendar, with the specified name.

```csharp
public FolderInfo CreatePredefinedFolder(string name, StandardIpmFolder defaultFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the folder. |
| defaultFolder | StandardIpmFolder | Which standard folder to create. |

### Return Value

The new folder.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | The PST is open for reading only. |
| NotImplementedException | The PST is in the ANSI format, which cannot be edited. |
| InvalidOperationException | This standard folder already exists in the PST. |
| NotImplementedException | The file is an OST. |

### See Also

* class [FolderInfo](../../folderinfo/)
* enum [StandardIpmFolder](../../standardipmfolder/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


