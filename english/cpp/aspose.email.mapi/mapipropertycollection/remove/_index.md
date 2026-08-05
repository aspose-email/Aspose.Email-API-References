---
title: "Aspose::Email::Mapi::MapiPropertyCollection::Remove method"
linktitle: "Remove"
articleTitle: "Remove"
second_title: "Aspose.Email for C++"
description: "Removes the property with the specified tag from the collection."
type: docs
weight: 190
url: /cpp/aspose.email.mapi/mapipropertycollection/remove/
---

## Remove (1 of 3) {#remove_1}

Removes the property with the specified tag from the collection.

**Returns:** true if the property is successfully removed; otherwise, false.

```cpp
Remove(const int64_t & key)
```

| Parameter | Description |
| --- | --- |
| key | The tag of the property to remove. |

---

## Remove (2 of 3) {#remove_2}

**Returns:** bool Aspose::Email::Mapi::

```cpp
Remove(const System::Collections::Generic::KeyValuePair< int64_t, System::SharedPtr < MapiProperty >> & item)
```

| Parameter | Description |
| --- | --- |
| item |  |

---

## Remove (3 of 3) {#remove_3}

Removes the property with the specified property descriptor from the collection.

**Returns:** true if the property is successfully removed; otherwise, false.

```cpp
Remove(const System::SharedPtr < PropertyDescriptor > & pd)
```

| Parameter | Description |
| --- | --- |
| pd | Property descriptor of the property to remove. |

