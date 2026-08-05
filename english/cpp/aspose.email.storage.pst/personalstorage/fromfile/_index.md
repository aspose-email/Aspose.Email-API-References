---
title: "Aspose::Email::Storage::Pst::PersonalStorage::FromFile method"
linktitle: "FromFile"
articleTitle: "FromFile"
second_title: "Aspose.Email for C++"
description: "Load PST from file."
type: docs
weight: 190
url: /cpp/aspose.email.storage.pst/personalstorage/fromfile/
---

## FromFile (1 of 3) {#fromfile_1}

Load PST from file.

**Returns:** A PersonalStorage object that represents the current PST.

```cpp
FromFile(System::String fileName)
```

| Parameter | Description |
| --- | --- |
| fileName | Name of .pst file. |

---

## FromFile (2 of 3) {#fromfile_2}

Load PST from file.

**Returns:** A PersonalStorage object that represents the current PST.

```cpp
FromFile(System::String fileName, bool writable)
```

| Parameter | Description |
| --- | --- |
| fileName | Name of .pst file. |
| writable | if set to true then the the pst file will support writing, otherwise it will be opened in read-only mode. |

---

## FromFile (3 of 3) {#fromfile_3}

Load PST from file.

**Returns:** A PersonalStorage object that represents the current PST.

```cpp
FromFile(System::String fileName, System::SharedPtr < PersonalStorageLoadOptions > loadOptions)
```

| Parameter | Description |
| --- | --- |
| fileName | Name of .pst file. |
| loadOptions | The load options. |

