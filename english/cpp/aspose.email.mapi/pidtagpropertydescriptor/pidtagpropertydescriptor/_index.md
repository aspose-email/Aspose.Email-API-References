---
title: "Aspose::Email::Mapi::PidTagPropertyDescriptor::PidTagPropertyDescriptor constructor"
linktitle: "PidTagPropertyDescriptor"
articleTitle: "PidTagPropertyDescriptor"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the PidTagPropertyDescriptor class A property that is defined by a 16-bit property ID and a 16-bit property type."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/pidtagpropertydescriptor/pidtagpropertydescriptor/
---

## PidTagPropertyDescriptor (1 of 5) {#pidtagpropertydescriptor_1}

Initializes a new instance of the PidTagPropertyDescriptor class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 � 0x7FFF. Property IDs in the range 0x8000 � 0x8FFF are reserved for assignment to named properties

**Returns:** Aspose::Email::Mapi::

```cpp
PidTagPropertyDescriptor(int32_t id, PropertyDataType type)
```

| Parameter | Description |
| --- | --- |
| id | Unsigned 16-bit quantity that identifies a tagged property. |
| type | Specifies the type of values allowed for the property. |

---

## PidTagPropertyDescriptor (2 of 5) {#pidtagpropertydescriptor_2}

Initializes a new instance of the PidTagPropertyDescriptor class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 � 0x7FFF. Property IDs in the range 0x8000 � 0x8FFF are reserved for assignment to named properties

**Returns:** Aspose::Email::Mapi::

```cpp
PidTagPropertyDescriptor(System::String canonicalName, int32_t id, PropertyDataType type)
```

| Parameter | Description |
| --- | --- |
| canonicalName | The name used to refer to the property in the documentation. |
| id | Unsigned 16-bit quantity that identifies a tagged property. |
| type | Specifies the type of values allowed for the property. |

---

## PidTagPropertyDescriptor (3 of 5) {#pidtagpropertydescriptor_3}

Initializes a new instance of the PidTagPropertyDescriptor class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 � 0x7FFF. Property IDs in the range 0x8000 � 0x8FFF are reserved for assignment to named properties

**Returns:** Aspose::Email::Mapi::

```cpp
PidTagPropertyDescriptor(System::String canonicalName, System::String name, int32_t id, PropertyDataType type)
```

| Parameter | Description |
| --- | --- |
| canonicalName | The name used to refer to the property in the documentation. |
| name | The MAPI name used to refer to the property in the documentation. |
| id | Unsigned 16-bit quantity that identifies a tagged property. |
| type | Specifies the type of values allowed for the property. |

---

## PidTagPropertyDescriptor (4 of 5) {#pidtagpropertydescriptor_4}

Initializes a new instance of the PidTagPropertyDescriptor class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 � 0x7FFF. Property IDs in the range 0x8000 � 0x8FFF are reserved for assignment to named properties

**Returns:** Aspose::Email::Mapi::

```cpp
PidTagPropertyDescriptor(int64_t tag)
```

| Parameter | Description |
| --- | --- |
| tag | A tag is a 32-bit number that contains a unique property identifier in bits 16 through 31 and a property type in bits 0 through 15 |

---

## PidTagPropertyDescriptor (5 of 5) {#pidtagpropertydescriptor_5}

Initializes a new instance of the PidTagPropertyDescriptor class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 � 0x7FFF. Property IDs in the range 0x8000 � 0x8FFF are reserved for assignment to named properties

**Returns:** Aspose::Email::Mapi::

```cpp
PidTagPropertyDescriptor(System::String canonicalName, System::String name, int64_t tag)
```

| Parameter | Description |
| --- | --- |
| canonicalName | The name used to refer to the property in the documentation. |
| name | The MAPI name used to refer to the property in the documentation. |
| tag | A tag is a 32-bit number that contains a unique property identifier in bits 16 through 31 and a property type in bits 0 through 15 |

