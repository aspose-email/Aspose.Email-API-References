---
title: "Aspose::Email::Storage::Pst::PersonalStorage::GetParentFolder method"
linktitle: "GetParentFolder"
articleTitle: "GetParentFolder"
second_title: "Aspose.Email for C++"
description: "Gets the parent folder of message."
type: docs
weight: 280
url: /cpp/aspose.email.storage.pst/personalstorage/getparentfolder/
---

## GetParentFolder (1 of 2) {#getparentfolder_1}

Gets the parent folder of message.

**Returns:** The parent folder FolderInfo of message.

```cpp
GetParentFolder(System::ArrayPtr< uint8_t > entryId)
```

| Parameter | Description |
| --- | --- |
| entryId | Entry Id of message or folder. |

---

## GetParentFolder (2 of 2) {#getparentfolder_2}

Finds and enumerates all soft-deleted items.

**Returns:** An enumerable collection of RestoredItemEntry objects, each containing a soft-deleted message and the folder Id it was originally located in.

```cpp
GetParentFolder(System::String entryIdString)
```

| Parameter | Description |
| --- | --- |
| entryIdString | String representation of Entry Id of message or folder. |

