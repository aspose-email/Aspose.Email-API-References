---
title: "Aspose::Email::Storage::Pst::PersonalStorage::SplitInto method"
linktitle: "SplitInto"
articleTitle: "SplitInto"
second_title: "Aspose.Email for C++"
description: "Splits the pst storage into less sized parts."
type: docs
weight: 370
url: /cpp/aspose.email.storage.pst/personalstorage/splitinto/
---

## SplitInto (1 of 4) {#splitinto_1}

Splits the pst storage into less sized parts.

**Returns:** void Aspose::Email::Storage::Pst::

```cpp
SplitInto(int64_t chunkSize, System::String partFileNamePrefix, System::String path)
```

| Parameter | Description |
| --- | --- |
| chunkSize | The approximate size of a chunk in bytes. |
| path | The folder path where chunks will be created. |
| partFileNamePrefix | The prefix to be added to the filename of each part of pst. If provided, the prefix will be added to the beginning of each file name. If not provided (null or empty), the pst parts will be created without a prefix. |

---

## SplitInto (2 of 4) {#splitinto_2}

Splits the pst storage into less sized parts.

**Returns:** void Aspose::Email::Storage::Pst::

```cpp
SplitInto(int64_t chunkSize, System::String path)
```

| Parameter | Description |
| --- | --- |
| chunkSize | The approximate size of a chunk in bytes. |
| path | The folder path where chunks will be created. |

---

## SplitInto (3 of 4) {#splitinto_3}

Splits the pst storage based on criteria.

**Returns:** void Aspose::Email::Storage::Pst::

```cpp
SplitInto(System::SharedPtr < System::Collections::Generic::IList< System::SharedPtr < Tools::Search::MailQuery >>> criteria, System::String partFileNamePrefix, System::String path)
```

| Parameter | Description |
| --- | --- |
| criteria | The collection of MailQuery that represents criteria of pst splitting. |
| path | The folder path where chunks will be created. |

---

## SplitInto (4 of 4) {#splitinto_4}

Splits the pst storage based on criteria.

**Returns:** void Aspose::Email::Storage::Pst::

```cpp
SplitInto(System::SharedPtr < System::Collections::Generic::IList< System::SharedPtr < Tools::Search::MailQuery >>> criteria, System::String path)
```

| Parameter | Description |
| --- | --- |
| criteria | The collection of MailQuery that represents criteria of pst splitting. |
| path | The folder path where chunks will be created. |

