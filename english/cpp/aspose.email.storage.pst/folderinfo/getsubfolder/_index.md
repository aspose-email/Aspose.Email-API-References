---
title: "Aspose::Email::Storage::Pst::FolderInfo::GetSubFolder method"
linktitle: "GetSubFolder"
articleTitle: "GetSubFolder"
second_title: "Aspose.Email for C++"
description: "Get subfolder."
type: docs
weight: 310
url: /cpp/aspose.email.storage.pst/folderinfo/getsubfolder/
---

## GetSubFolder (1 of 3) {#getsubfolder_1}

Get subfolder.

**Returns:** A FolderInfo object.

```cpp
GetSubFolder(System::String name)
```

| Parameter | Description |
| --- | --- |
| name | Name of subfolder. |

---

## GetSubFolder (2 of 3) {#getsubfolder_2}

Gets the subfolder.

**Returns:** A FolderInfo object.

```cpp
GetSubFolder(System::String name, bool ignoreCase)
```

| Parameter | Description |
| --- | --- |
| name | Name of subfolder. |
| ignoreCase | Indicates that a search should ignore case sensitivity when matching the folder name. |

---

## GetSubFolder (3 of 3) {#getsubfolder_3}

Retrieves a subfolder with the specified name from the current folder.

**Returns:** The FolderInfo representing the retrieved subfolder, or null if the subfolder is not found.

```cpp
GetSubFolder(System::String name, bool ignoreCase, bool handlePathSeparator)
```

| Parameter | Description |
| --- | --- |
| name | The name of the subfolder to retrieve. |
| ignoreCase | Specifies whether to perform a case-insensitive search for folders with the given name. |
| handlePathSeparator | Specifies whether the specified folder name should be treated as a path if it contains backslashes. |

