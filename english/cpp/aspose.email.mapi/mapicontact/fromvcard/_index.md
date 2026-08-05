---
title: "Aspose::Email::Mapi::MapiContact::FromVCard method"
linktitle: "FromVCard"
articleTitle: "FromVCard"
second_title: "Aspose.Email for C++"
description: "Reads MapiContact from the specified stream containing vCard."
type: docs
weight: 20
url: /cpp/aspose.email.mapi/mapicontact/fromvcard/
---

## FromVCard (1 of 6) {#fromvcard_1}

Reads MapiContact from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

**Returns:** A read MapiContact

```cpp
FromVCard(System::SharedPtr < System::IO::Stream > stream)
```

| Parameter | Description |
| --- | --- |
| stream | A stream to read from |

---

## FromVCard (2 of 6) {#fromvcard_2}

Reads MapiContact from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

**Returns:** A read MapiContact

```cpp
FromVCard(System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < Aspose::Email::PersonalInfo::VCard::VCardLoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| stream | A stream to read from |
| options | Additional options when loading a VCardContact |

---

## FromVCard (3 of 6) {#fromvcard_3}

Reads MapiContact from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

**Returns:** A read MapiContact

```cpp
FromVCard(System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < System::Text::Encoding > encoding)
```

| Parameter | Description |
| --- | --- |
| stream | A stream to read from |
| encoding | Stream data encoding |

---

## FromVCard (4 of 6) {#fromvcard_4}

Reads MapiContact from the specified vCard file The supported vCard versions are 2.1 and 3.0

**Returns:** A read MapiContact

```cpp
FromVCard(System::String filePath)
```

| Parameter | Description |
| --- | --- |
| filePath | A file name to read from |

---

## FromVCard (5 of 6) {#fromvcard_5}

Reads MapiContact from the specified vCard file The supported vCard versions are 2.1 and 3.0

**Returns:** A read MapiContact

```cpp
FromVCard(System::String filePath, System::SharedPtr < Aspose::Email::PersonalInfo::VCard::VCardLoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| filePath | A file name to read from |
| options | Additional options when loading a VCardContact |

---

## FromVCard (6 of 6) {#fromvcard_6}

Reads MapiContact from the specified vCard file The supported vCard versions are 2.1 and 3.0

**Returns:** A read MapiContact

```cpp
FromVCard(System::String filePath, System::SharedPtr < System::Text::Encoding > encoding)
```

| Parameter | Description |
| --- | --- |
| filePath | A file name to read from |
| encoding | File data encoding |

