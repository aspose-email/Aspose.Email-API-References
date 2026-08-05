---
title: "Aspose::Email::Mapi::MapiAttachmentCollection::Add method"
linktitle: "Add"
articleTitle: "Add"
second_title: "Aspose.Email for C++"
description: "Adds an object to the end of the T:System::Collections::ObjectModel::Collection`1 ."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapiattachmentcollection/add/
---

## Add (1 of 5) {#add_1}

Adds an object to the end of the T:System::Collections::ObjectModel::Collection`1 .

**Returns:** void Aspose::Email::Mapi::

```cpp
Add(const System::SharedPtr < MapiAttachment > & item)
```

| Parameter | Description |
| --- | --- |
| item | The object to be added to the end of the T:System::Collections::ObjectModel::Collection`1 . The value can be null for reference types. |

---

## Add (2 of 5) {#add_2}

Adds the new attachment.

**Returns:** void Aspose::Email::Mapi::

```cpp
Add(System::String name, System::ArrayPtr< uint8_t > data)
```

| Parameter | Description |
| --- | --- |
| name | The name of attachment. |
| data | The attachment data. |

---

## Add (3 of 5) {#add_3}

Adds the new attachment as embedded message.

**Returns:** void Aspose::Email::Mapi::

```cpp
Add(System::String name, System::SharedPtr < MapiMessage > msg)
```

| Parameter | Description |
| --- | --- |
| name | The name of attachment. |
| msg | The MapiMessage that represents the attached message. |

---

## Add (4 of 5) {#add_4}

Adds a reference attachment to the collection using the specified name and configuration options.

**Returns:** void Aspose::Email::Mapi::

```cpp
Add(System::String name, System::SharedPtr < ReferenceAttachmentOptions > options)
```

| Parameter | Description |
| --- | --- |
| name | The name of the attachment to display in the message. |
| options | An instance of ReferenceAttachmentOptions containing the configuration details for the reference attachment, such as the shared link, URL, and provider name. |

---

## Add (5 of 5) {#add_5}

Adds the reference attachment.

**Returns:** void Aspose::Email::Mapi::

```cpp
Add(System::String name, System::String sharedLink, System::String url, System::String providerName)
```

| Parameter | Description |
| --- | --- |
| name | The name of attachment. |
| sharedLink | A fully qualified shared link to the attachment provided by web service manipulating the attachment. |
| url | A file location. |
| providerName | A name of reference attachment provider. |

