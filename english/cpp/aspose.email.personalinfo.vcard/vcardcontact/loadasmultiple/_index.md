---
title: "Aspose::Email::PersonalInfo::VCard::VCardContact::LoadAsMultiple method"
linktitle: "LoadAsMultiple"
articleTitle: "LoadAsMultiple"
second_title: "Aspose.Email for C++"
description: "Loads list of contacts from multi contact stream."
type: docs
weight: 150
url: /cpp/aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple/
---

## LoadAsMultiple (1 of 6) {#loadasmultiple_1}

Loads list of contacts from multi contact stream.

**Returns:** List of contacs

```cpp
LoadAsMultiple(System::SharedPtr < System::IO::Stream > stream)
```

| Parameter | Description |
| --- | --- |
| stream | Source stream |

---

## LoadAsMultiple (2 of 6) {#loadasmultiple_2}

Loads list of contacts from multi contact stream.

**Returns:** List of contacts

```cpp
LoadAsMultiple(System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < System::Text::Encoding > encoding)
```

| Parameter | Description |
| --- | --- |
| stream | Source stream |
| encoding | Stream data encoding,if null then UTF8 will be used. |

---

## LoadAsMultiple (3 of 6) {#loadasmultiple_3}

Loads list of contacts from multi contact stream.

**Returns:** List of contacts

```cpp
LoadAsMultiple(System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < VCardLoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| stream | Source stream |
| options | Additional options when loading a VCardContact |

---

## LoadAsMultiple (4 of 6) {#loadasmultiple_4}

Loads list of contacts from multi contact file.

**Returns:** List of contacts

```cpp
LoadAsMultiple(System::String filePath)
```

| Parameter | Description |
| --- | --- |
| filePath | Source file |

---

## LoadAsMultiple (5 of 6) {#loadasmultiple_5}

Loads list of contacts from multi contact file.

**Returns:** List of contacts

```cpp
LoadAsMultiple(System::String filePath, System::SharedPtr < System::Text::Encoding > encoding)
```

| Parameter | Description |
| --- | --- |
| filePath | Source file |
| encoding | File data encoding,if null then UTF8 will be used. |

---

## LoadAsMultiple (6 of 6) {#loadasmultiple_6}

**Returns:** List of contacts

```cpp
LoadAsMultiple(System::String filePath, System::SharedPtr < VCardLoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| filePath | Source file |
| options | Additional options when loading a VCardContact |

