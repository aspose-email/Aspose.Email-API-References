---
title: "Aspose::Email::Storage::Pst::PersonalStorage::FindSubfolders method"
linktitle: "FindSubfolders"
articleTitle: "FindSubfolders"
second_title: "Aspose.Email for C++"
description: "Finds the identifiers of subfolders for for the current folder."
type: docs
weight: 180
url: /cpp/aspose.email.storage.pst/personalstorage/findsubfolders/
---

## FindSubfolders {#findsubfolders}

Finds the identifiers of subfolders for for the current folder. It might be useful in case of reading corrupted pst when the GetSubfolders and EnumerateFolders methods could throw an exception.

**Returns:** Collection of entry Ids.

```cpp
FindSubfolders(System::String parentEntryId)
```

| Parameter | Description |
| --- | --- |
| parentEntryId | Entry id of the parent folder. |

