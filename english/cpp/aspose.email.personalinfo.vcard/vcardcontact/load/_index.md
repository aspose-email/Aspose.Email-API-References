---
title: "Aspose::Email::PersonalInfo::VCard::VCardContact::Load method"
linktitle: "Load"
articleTitle: "Load"
second_title: "Aspose.Email for C++"
description: "Reads VCardContact from the specified stream containing vCard."
type: docs
weight: 140
url: /cpp/aspose.email.personalinfo.vcard/vcardcontact/load/
---

## Load (1 of 6) {#load_1}

Reads VCardContact from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

**Returns:** A read VCardContact

```cpp
Load(System::SharedPtr < System::IO::Stream > stream)
```

| Parameter | Description |
| --- | --- |
| stream | A stream to read from |

---

## Load (2 of 6) {#load_2}

Reads VCardContact from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

**Returns:** A read VCardContact

```cpp
Load(System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < System::Text::Encoding > encoding)
```

| Parameter | Description |
| --- | --- |
| stream | A stream to read from |
| encoding | Stream data encoding |

---

## Load (3 of 6) {#load_3}

Reads VCardContact from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

**Returns:** A read VCardContact

```cpp
Load(System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < VCardLoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| stream | A stream to read from |
| options | Additional options when loading a VCardContact |

---

## Load (4 of 6) {#load_4}

Reads VCardContact from the specified vCard file The supported vCard versions are 2.1 and 3.0

**Returns:** A read VCardContact

```cpp
Load(System::String filePath)
```

| Parameter | Description |
| --- | --- |
| filePath | A file name to read from |

---

## Load (5 of 6) {#load_5}

Reads VCardContact from the specified vCard file The supported vCard versions are 2.1 and 3.0

**Returns:** A read VCardContact

```cpp
Load(System::String filePath, System::SharedPtr < System::Text::Encoding > encoding)
```

| Parameter | Description |
| --- | --- |
| filePath | A file name to read from |
| encoding | File encoding |

---

## Load (6 of 6) {#load_6}

Reads VCardContact from the specified vCard file The supported vCard versions are 2.1 and 3.0

**Returns:** List of contacts

```cpp
Load(System::String filePath, System::SharedPtr < VCardLoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| filePath | Source file |
| options | Additional options when loading a VCardContact |

