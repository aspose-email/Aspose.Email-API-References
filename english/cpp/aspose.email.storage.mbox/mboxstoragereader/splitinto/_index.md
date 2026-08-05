---
title: "Aspose::Email::Storage::Mbox::MboxStorageReader::SplitInto method"
linktitle: "SplitInto"
articleTitle: "SplitInto"
second_title: "Aspose.Email for C++"
description: "Splits the mbox storage into less sized parts."
type: docs
weight: 180
url: /cpp/aspose.email.storage.mbox/mboxstoragereader/splitinto/
---

## SplitInto (1 of 2) {#splitinto_1}

Splits the mbox storage into less sized parts.

**Returns:** void Aspose::Email::Storage::Mbox::

```cpp
SplitInto(int64_t chunkSize, System::String outputPath)
```

| Parameter | Description |
| --- | --- |
| chunkSize | The approximate size of a chunk in bytes. |
| outputPath | The folder path where chunks will be created. |

---

## SplitInto (2 of 2) {#splitinto_2}

Splits the mbox storage into less sized parts.

**Returns:** void Aspose::Email::Storage::Mbox::

```cpp
SplitInto(int64_t chunkSize, System::String outputPath, System::String partFileNamePrefix)
```

| Parameter | Description |
| --- | --- |
| chunkSize | The approximate size of a chunk in bytes. |
| outputPath | The folder path where chunks will be created. |
| partFileNamePrefix | The prefix to be added to the filename of each part of pst. Exceptions ArgumentException Throws when the path parameter is null or empty. |
| ArgumentException | Throws when the path parameter is null or empty. |

