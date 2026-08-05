---
title: "Aspose::Email::Mapi::PidLidPropertyDescriptor::PidLidPropertyDescriptor constructor"
linktitle: "PidLidPropertyDescriptor"
articleTitle: "PidLidPropertyDescriptor"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the PidLidPropertyDescriptor class Properties identified by an unsigned 32-bit quantity along with a property set."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/pidlidpropertydescriptor/pidlidpropertydescriptor/
---

## PidLidPropertyDescriptor (1 of 3) {#pidlidpropertydescriptor_1}

Initializes a new instance of the PidLidPropertyDescriptor class Properties identified by an unsigned 32-bit quantity along with a property set.

**Returns:** Aspose::Email::Mapi::

```cpp
PidLidPropertyDescriptor(int64_t longId, PropertyDataType type, System::Guid propertySet)
```

| Parameter | Description |
| --- | --- |
| longId | long ID (LID): An unsigned 32-bit quantity that, in combination with a GUID, defines a named property. |
| type | Specifies the type of values allowed for the property. |
| propertySet | A GUID that identifies a group of properties with a similar purpose. |

---

## PidLidPropertyDescriptor (2 of 3) {#pidlidpropertydescriptor_2}

Initializes a new instance of the PidLidPropertyDescriptor class Properties identified by an unsigned 32-bit quantity along with a property set.

**Returns:** Aspose::Email::Mapi::

```cpp
PidLidPropertyDescriptor(System::String canonicalName, int64_t longId, PropertyDataType type, System::Guid propertySet)
```

| Parameter | Description |
| --- | --- |
| canonicalName | The name used to refer to the property in the documentation. |
| longId | long ID (LID): An unsigned 32-bit quantity that, in combination with a GUID, defines a named property. |
| type | Specifies the type of values allowed for the property. |
| propertySet | A GUID that identifies a group of properties with a similar purpose. |

---

## PidLidPropertyDescriptor (3 of 3) {#pidlidpropertydescriptor_3}

Initializes a new instance of the PidLidPropertyDescriptor class Properties identified by an unsigned 32-bit quantity along with a property set.

**Returns:** Aspose::Email::Mapi::

```cpp
PidLidPropertyDescriptor(System::String canonicalName, System::String name, int64_t longId, PropertyDataType type, System::Guid propertySet)
```

| Parameter | Description |
| --- | --- |
| canonicalName | The name used to refer to the property in the documentation. |
| name | The MAPI name used to refer to the property in the documentation. |
| longId | long ID (LID): An unsigned 32-bit quantity that, in combination with a GUID, defines a named property. |
| type | Specifies the type of values allowed for the property. |
| propertySet | A GUID that identifies a group of properties with a similar purpose. |

