---
title: FolderInfo.GetSubFolder
second_title: Aspose.Email for .NET API Reference
description: FolderInfo method. Get subfolder
type: docs
weight: 300
url: /net/aspose.email.storage.pst/folderinfo/getsubfolder/
---
## GetSubFolder(string) {#getsubfolder}

Get subfolder.

```csharp
public FolderInfo GetSubFolder(string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Name of subfolder. |

### Return Value

A FolderInfo object.

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## GetSubFolder(string, bool) {#getsubfolder_1}

Gets the subfolder.

```csharp
public FolderInfo GetSubFolder(string name, bool ignoreCase)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Name of subfolder. |
| ignoreCase | Boolean | Indicates that a search should ignore case sensitivity when matching the folder name. |

### Return Value

A FolderInfo object.

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)

---

## GetSubFolder(string, bool, bool) {#getsubfolder_2}

Retrieves a subfolder with the specified name from the current folder.

```csharp
public FolderInfo GetSubFolder(string name, bool ignoreCase, bool handlePathSeparator)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the subfolder to retrieve. |
| ignoreCase | Boolean | Specifies whether to perform a case-insensitive search for folders with the given name. |
| handlePathSeparator | Boolean | Specifies whether the specified folder name should be treated as a path if it contains backslashes. |

### Return Value

The [`FolderInfo`](../) representing the retrieved subfolder, or `null` if the subfolder is not found.

## Remarks

The *name* parameter specifies the name of the subfolder to retrieve. The *ignoreCase* parameter determines whether the search for the subfolder name should be case-sensitive or case-insensitive. If set to `true`, the search will be case-insensitive, otherwise, it will be case-sensitive. The *handlePathSeparator* parameter specifies whether the specified folder name should be treated as a path if it contains backslashes. If set to `true`, the method will interpret the folder name as a path, attempting to navigate to the subfolder using the path. If set to `false`, the method will treat the folder name as a simple name, searching for a subfolder with an exact name match. If the subfolder is found, the method returns the [`FolderInfo`](../) object representing the retrieved subfolder. If the subfolder is not found, the method returns `null`.

### See Also

* class [FolderInfo](../)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo/)
* assembly [Aspose.Email](../../../)


