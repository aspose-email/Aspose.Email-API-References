---
title: "Aspose::Email::Mime::HeaderCollection::Add method"
linktitle: "Add"
articleTitle: "Add"
second_title: "Aspose.Email for C++"
description: "Adds a header to collection."
type: docs
weight: 10
url: /cpp/aspose.email.mime/headercollection/add/
---

## Add (1 of 4) {#add_1}

Adds a header to collection.

**Returns:** void Aspose::Email::Mime::

```cpp
Add(const System::SharedPtr < HeaderCollection > & c)
```

| Parameter | Description |
| --- | --- |
| c | HeaderCollection for adding. |

---

## Add (2 of 4) {#add_2}

Adds the header without value

**Returns:** void Aspose::Email::Mime::

```cpp
Add(const System::String & item)
```

| Parameter | Description |
| --- | --- |
| item |  |

---

## Add (3 of 4) {#add_3}

Adds a header to collection

**Returns:** void Aspose::Email::Mime::

```cpp
Add(System::SharedPtr < RawMimeHeader > header, System::SharedPtr < System::Text::Encoding > preferredEncoding)
```

| Parameter | Description |
| --- | --- |
| header | A RawMimeHeader containing a header key and a raw header value |
| preferredEncoding | A preferred text encoding |

---

## Add (4 of 4) {#add_4}

Adds the header.

**Returns:** void Aspose::Email::Mime::

```cpp
Add(System::String name, System::String value)
```

| Parameter | Description |
| --- | --- |
| name | The header name. |
| value | The header value. |

