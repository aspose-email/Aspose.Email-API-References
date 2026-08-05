---
title: "Aspose::Email::Mapi::KnownPropertyList::Find method"
linktitle: "Find"
articleTitle: "Find"
second_title: "Aspose.Email for C++"
description: "Finds properties in list according to its PropertySet"
type: docs
weight: 50
url: /cpp/aspose.email.mapi/knownpropertylist/find/
---

## Find (1 of 9) {#find_1}

Finds properties in list according to its PropertySet

**Returns:** Array of PropertyDescriptor objects with required PropertySet if found in the list; otherwise empty array.

```cpp
Find(const System::ArrayPtr< System::Guid > & propertySets)
```

| Parameter | Description |
| --- | --- |
| propertySets | PropertySet to find |

---

## Find (2 of 9) {#find_2}

Finds PidTagPropertyDescriptor properties in list

**Returns:** PidTagPropertyDescriptor Array of objects with defined tag if found in the list; otherwise empty array.

```cpp
Find(int32_t id)
```

| Parameter | Description |
| --- | --- |
| id | id to find |

---

## Find (3 of 9) {#find_3}

Finds PidTagPropertyDescriptor property in list

**Returns:** PidTagPropertyDescriptor object with defined tag if found in the list; otherwise null.

```cpp
Find(int32_t id, PropertyDataType type)
```

| Parameter | Description |
| --- | --- |
| id | id to find |
| type | Data type of a property |

---

## Find (4 of 9) {#find_4}

Finds PidLidPropertyDescriptor property in list according to required parameters

**Returns:** PidLidPropertyDescriptor object if found in the list; otherwise null.

```cpp
Find(int64_t lid, PropertyDataType type, System::Guid propertySet)
```

| Parameter | Description |
| --- | --- |
| lid | Long id of a property |
| type | Data type of a property |
| propertySet | PropertySet of a property |

---

## Find (5 of 9) {#find_5}

Finds PidLidPropertyDescriptor property in list according to required parameters This is simplified search operation without data type comparison.

**Returns:** PidLidPropertyDescriptor object if found in the list; otherwise null.

```cpp
Find(int64_t lid, System::Guid propertySet)
```

| Parameter | Description |
| --- | --- |
| lid | Long id of a property |
| propertySet | PropertySet of a property |

---

## Find (6 of 9) {#find_6}

Finds PidTagPropertyDescriptor property in list

**Returns:** PidTagPropertyDescriptor object with defined tag if found in the list; otherwise null.

```cpp
Find(int64_t tag)
```

| Parameter | Description |
| --- | --- |
| tag | Tag to find |

---

## Find (7 of 9) {#find_7}

Finds property in list with specified name

**Returns:** PropertyDescriptor object if found in the list; otherwise null.

```cpp
Find(System::String name)
```

| Parameter | Description |
| --- | --- |
| name | The name used to refer to the property. |

---

## Find (8 of 9) {#find_8}

Finds PidNamePropertyDescriptor property in list according to required parameters

**Returns:** PidNamePropertyDescriptor object if found in the list; otherwise null.

```cpp
Find(System::String name, PropertyDataType type, System::Guid propertySet)
```

| Parameter | Description |
| --- | --- |
| name | Name of a property |
| type | Data type of a property |
| propertySet | PropertySet of a property |

---

## Find (9 of 9) {#find_9}

Finds PidNamePropertyDescriptor property in list according to required parameters This is simplified search operation without data type comparison.

**Returns:** PidNamePropertyDescriptor object if found in the list; otherwise null.

```cpp
Find(System::String name, System::Guid propertySet)
```

| Parameter | Description |
| --- | --- |
| name | Name of a property |
| propertySet | PropertySet of a property |

