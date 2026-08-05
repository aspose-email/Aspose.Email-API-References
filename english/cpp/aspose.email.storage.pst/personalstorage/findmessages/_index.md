---
title: "Aspose::Email::Storage::Pst::PersonalStorage::FindMessages method"
linktitle: "FindMessages"
articleTitle: "FindMessages"
second_title: "Aspose.Email for C++"
description: "Finds the identifiers of messages for for the current folder."
type: docs
weight: 170
url: /cpp/aspose.email.storage.pst/personalstorage/findmessages/
---

## FindMessages {#findmessages}

Finds the identifiers of messages for for the current folder. It might be useful in case of reading corrupted pst when the GetContents and EnumerateMessages methods could throw an exception.

**Returns:** Collection of entry Ids.

```cpp
FindMessages(System::String parentEntryId)
```

| Parameter | Description |
| --- | --- |
| parentEntryId | Entry id of the parent folder. |

