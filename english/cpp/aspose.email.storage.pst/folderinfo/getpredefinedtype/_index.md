---
title: "Aspose::Email::Storage::Pst::FolderInfo::GetPredefinedType method"
linktitle: "GetPredefinedType"
articleTitle: "GetPredefinedType"
second_title: "Aspose.Email for C++"
description: "Gets the type of predefined folder."
type: docs
weight: 300
url: /cpp/aspose.email.storage.pst/folderinfo/getpredefinedtype/
---

## GetPredefinedType {#getpredefinedtype}

Gets the type of predefined folder.

**Returns:** The StandardIpmFolder enum value. If the folder is not predefined, it returns StandardIpmFolder::Unspecified

```cpp
GetPredefinedType(bool getForTopLevelParent)
```

| Parameter | Description |
| --- | --- |
| getForTopLevelParent | If true, returns the predefined type for the top-level parent folder. This determines whether the current folder is a subfolder of a predefined folder. If false, it returns the predefined type for the current folder. |

