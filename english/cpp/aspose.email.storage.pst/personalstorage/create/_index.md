---
title: "Aspose::Email::Storage::Pst::PersonalStorage::Create method"
linktitle: "Create"
articleTitle: "Create"
second_title: "Aspose.Email for C++"
description: "Creates the PST in a stream."
type: docs
weight: 60
url: /cpp/aspose.email.storage.pst/personalstorage/create/
---

## Create (1 of 3) {#create_1}

Creates the PST in a stream.

**Returns:** A PersonalStorage object that represents the new PST.

```cpp
Create(System::SharedPtr < System::IO::Stream > stream, FileFormatVersion version)
```

| Parameter | Description |
| --- | --- |
| stream | The stream in which PST is created. |
| version | The PST file version. |

---

## Create (2 of 3) {#create_2}

Creates the PST in a stream.

**Returns:** A PersonalStorage object that represents the new PST.

```cpp
Create(System::SharedPtr < System::IO::Stream > stream, FileFormatVersion version, bool leaveStreamOpen)
```

| Parameter | Description |
| --- | --- |
| stream | The stream in which PST is created. |
| version | The PST file version. |
| leaveStreamOpen | Leave stream open when PersonalStorage is disposed. |

---

## Create (3 of 3) {#create_3}

Creates the new PST file with the specified file name.

**Returns:** A PersonalStorage object that represents the new PST.

```cpp
Create(System::String fileName, FileFormatVersion version)
```

| Parameter | Description |
| --- | --- |
| fileName | The full name of the file. |
| version | The PST file version. |

