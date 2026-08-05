---
title: "Aspose::Email::Storage::Pst::FolderInfo::AddSubFolder method"
linktitle: "AddSubFolder"
articleTitle: "AddSubFolder"
second_title: "Aspose.Email for C++"
description: "Adds the new sub-folder."
type: docs
weight: 50
url: /cpp/aspose.email.storage.pst/folderinfo/addsubfolder/
---

## AddSubFolder (1 of 4) {#addsubfolder_1}

Adds the new sub-folder.

**Returns:** The new sub-folder.

```cpp
AddSubFolder(System::String name)
```

| Parameter | Description |
| --- | --- |
| name | The name of sub-folder. |

---

## AddSubFolder (2 of 4) {#addsubfolder_2}

Adds the new sub-folder.

**Returns:** The new sub-folder.

```cpp
AddSubFolder(System::String name, bool createHierarchy)
```

| Parameter | Description |
| --- | --- |
| name | The name of sub-folder. |
| createHierarchy | if set to true , it is possible to create a folder hierarchy using string notation. Backslash ('\') is used as path separator. |

---

## AddSubFolder (3 of 4) {#addsubfolder_3}

Adds a subfolder with the specified name to the current folder using the provided creation options.

**Returns:** The FolderInfo representing the added subfolder.

```cpp
AddSubFolder(System::String name, System::SharedPtr < FolderCreationOptions > creationOptions)
```

| Parameter | Description |
| --- | --- |
| name | The name of the subfolder to add. |
| creationOptions | The options for creating the subfolder. |

---

## AddSubFolder (4 of 4) {#addsubfolder_4}

Adds the new subfolder.

**Returns:** The new subfolder.

```cpp
AddSubFolder(System::String name, System::String containerClass)
```

| Parameter | Description |
| --- | --- |
| name | The name of subfolder. |
| containerClass | Container class of the sub-Folder object. |

