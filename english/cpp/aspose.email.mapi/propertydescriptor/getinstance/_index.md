---
title: "Aspose::Email::Mapi::PropertyDescriptor::GetInstance method"
linktitle: "GetInstance"
articleTitle: "GetInstance"
second_title: "Aspose.Email for C++"
description: "Retrieves PidTagPropertyDescriptor object"
type: docs
weight: 70
url: /cpp/aspose.email.mapi/propertydescriptor/getinstance/
---

## GetInstance (1 of 5) {#getinstance_1}

Retrieves PidTagPropertyDescriptor object

**Returns:** PidTagPropertyDescriptor object

```cpp
GetInstance(int32_t id, PropertyDataType dataType)
```

| Parameter | Description |
| --- | --- |
| id | Id of a property |
| dataType | Data type of a property |

---

## GetInstance (2 of 5) {#getinstance_2}

Retrieves PidLidPropertyDescriptor object

**Returns:** PidLidPropertyDescriptor object

```cpp
GetInstance(int64_t lid, PropertyDataType dataType, System::Guid propertySet)
```

| Parameter | Description |
| --- | --- |
| lid | Long id of a property |
| dataType | Data type of a property |
| propertySet | PropertySet of a property |

---

## GetInstance (3 of 5) {#getinstance_3}

Retrieves PidTagPropertyDescriptor object

**Returns:** PidTagPropertyDescriptor object

```cpp
GetInstance(int64_t tag)
```

| Parameter | Description |
| --- | --- |
| tag | Tag of a property |

---

## GetInstance (4 of 5) {#getinstance_4}

Retrieves PropertyDescriptor object from MAPI property

**Returns:** static System::SharedPtr < PropertyDescriptor > Aspose::Email::Mapi::

```cpp
GetInstance(System::SharedPtr < MapiProperty > property)
```

| Parameter | Description |
| --- | --- |
| property | MapiProperty object |

---

## GetInstance (5 of 5) {#getinstance_5}

Retrieves PidNamePropertyDescriptor object

**Returns:** PidNamePropertyDescriptor object

```cpp
GetInstance(System::String name, PropertyDataType dataType, System::Guid propertySet)
```

| Parameter | Description |
| --- | --- |
| name | Name of a property |
| dataType | Data type of a property |
| propertySet | PropertySet of a property |

