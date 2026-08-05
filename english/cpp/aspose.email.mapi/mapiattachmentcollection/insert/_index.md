---
title: "Aspose::Email::Mapi::MapiAttachmentCollection::Insert method"
linktitle: "Insert"
articleTitle: "Insert"
second_title: "Aspose.Email for C++"
description: "Inserts an element into the T:System::Collections::ObjectModel::Collection`1 at the specified index."
type: docs
weight: 60
url: /cpp/aspose.email.mapi/mapiattachmentcollection/insert/
---

## Insert (1 of 2) {#insert_1}

Inserts an element into the T:System::Collections::ObjectModel::Collection`1 at the specified index.

**Returns:** void Aspose::Email::Mapi::

```cpp
Insert(int32_t index, const System::SharedPtr < MapiAttachment > & item)
```

| Parameter | Description |
| --- | --- |
| index | The zero-based index at which item should be inserted. |
| item | The object to insert. The value can be null for reference types. |

---

## Insert (2 of 2) {#insert_2}

Inserts a message as attachment into the MapiAttachmentCollection at the specified index.

**Returns:** void Aspose::Email::Mapi::

```cpp
Insert(int32_t index, System::String name, System::SharedPtr < MapiMessage > msg)
```

| Parameter | Description |
| --- | --- |
| index | The zero-based index at which should be inserted. |
| name | The name of attachment. |
| msg | The MapiMessage that represents the attached message. |

