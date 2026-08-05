---
title: "Aspose::Email::Storage::Pst::FolderInfo::MergeWith method"
linktitle: "MergeWith"
articleTitle: "MergeWith"
second_title: "Aspose.Email for C++"
description: "Merges the folder with the folder from another pst."
type: docs
weight: 340
url: /cpp/aspose.email.storage.pst/folderinfo/mergewith/
---

## MergeWith (1 of 2) {#mergewith_1}

Merges the folder with the folder from another pst.

**Returns:** void Aspose::Email::Storage::Pst::

```cpp
MergeWith(System::SharedPtr < FolderInfo > sourceFolder)
```

| Parameter | Description |
| --- | --- |
| sourceFolder | The source folder. |

---

## MergeWith (2 of 2) {#mergewith_2}

Merges the folder with the folder from another pst. OnItemMoved event is called on both messages and directories.

**Returns:** void Aspose::Email::Storage::Pst::

```cpp
MergeWith(System::SharedPtr < FolderInfo > sourceFolder, bool recursiveHandler)
```

| Parameter | Description |
| --- | --- |
| sourceFolder | The source folder. |
| recursiveHandler | If true, OnItemMoved will be called on all messages, including messages in sub-directories, otherwise OnItemMoved will be called only for messages in the current directory. |

