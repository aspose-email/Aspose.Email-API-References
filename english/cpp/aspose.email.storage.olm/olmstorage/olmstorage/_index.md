---
title: "Aspose::Email::Storage::Olm::OlmStorage::OlmStorage constructor"
linktitle: "OlmStorage"
articleTitle: "OlmStorage"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the OlmStorage class."
type: docs
weight: 10
url: /cpp/aspose.email.storage.olm/olmstorage/olmstorage/
---

## OlmStorage (1 of 3) {#olmstorage_1}

Initializes a new instance of the OlmStorage class. Allows setting a callback method for handling exceptions that occur during OLM storage traversal.

**Returns:** Aspose::Email::Storage::Olm::

```cpp
OlmStorage(Exceptions::TraversalExceptionsCallback callback)
```

| Parameter | Description |
| --- | --- |
| callback | The exception callback. |

---

## OlmStorage (2 of 3) {#olmstorage_2}

Initializes a new instance of the OlmStorage class.

**Returns:** Returns an OlmStorage instance which is loaded from the specified file.

```cpp
OlmStorage(System::String fileName)
```

| Parameter | Description |
| --- | --- |
| fileName | OLM file name. |

---

## OlmStorage (3 of 3) {#olmstorage_3}

Initializes a new instance of the OlmStorage class.

**Returns:** Returns an OlmStorage instance which is loaded from the specified stream.

```cpp
OlmStorage(System::SharedPtr < System::IO::Stream > stream)
```

| Parameter | Description |
| --- | --- |
| stream | Source stream System::IO::Stream with OLM storage data. |

