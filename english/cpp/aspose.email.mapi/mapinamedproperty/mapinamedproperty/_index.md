---
title: "Aspose::Email::Mapi::MapiNamedProperty::MapiNamedProperty constructor"
linktitle: "MapiNamedProperty"
articleTitle: "MapiNamedProperty"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the MapiNamedProperty class."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapinamedproperty/mapinamedproperty/
---

## MapiNamedProperty (1 of 7) {#mapinamedproperty_1}

Initializes a new instance of the MapiNamedProperty class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiNamedProperty()
```

---

## MapiNamedProperty (2 of 7) {#mapinamedproperty_2}

Initializes a new instance of the MapiNamedProperty class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiNamedProperty(int64_t propertyTag, System::String nameIdentifier, System::Guid propertyGuid, System::ArrayPtr< uint8_t > propertyValue)
```

| Parameter | Description |
| --- | --- |
| propertyTag | The property tag represented a 32-bit value that contains a property type and a property ID. The low-order 16 bits represent the property type. The high-order 16 bits represent the property ID. |
| nameIdentifier | The name identifier that is used to refer to a named property. |
| propertyGuid | The property unique identifier. |
| propertyValue | A property value. |

---

## MapiNamedProperty (3 of 7) {#mapinamedproperty_3}

Initializes a new instance of the MapiNamedProperty class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiNamedProperty(int64_t propertyTag, int64_t nameIdentifier, System::Guid propertyGuid, System::ArrayPtr< uint8_t > propertyValue)
```

| Parameter | Description |
| --- | --- |
| propertyTag | The property tag represented a 32-bit value that contains a property type and a property ID. The low-order 16 bits represent the property type. The high-order 16 bits represent the property ID. |
| nameIdentifier | The name identifier that is used to refer to a named property. |
| propertyGuid | The property unique identifier. |
| propertyValue | A property value. |

---

## MapiNamedProperty (4 of 7) {#mapinamedproperty_4}

Initializes a new instance of the MapiNamedProperty class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiNamedProperty(System::SharedPtr < INamedPropertyTagProvider > tagProvider, System::SharedPtr < PidLidPropertyDescriptor > pd, System::SharedPtr < System::Object > data)
```

| Parameter | Description |
| --- | --- |
| tagProvider | Property storage that can provide tag for named property |
| pd | Property descriptor |
| data | A property value. |

---

## MapiNamedProperty (5 of 7) {#mapinamedproperty_5}

Initializes a new instance of the MapiNamedProperty class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiNamedProperty(System::SharedPtr < INamedPropertyTagProvider > tagProvider, System::SharedPtr < PidNamePropertyDescriptor > pd, System::SharedPtr < System::Object > data)
```

| Parameter | Description |
| --- | --- |
| tagProvider | Property storage that can provide tag for named property |
| pd | Property descriptor |
| data | A property value. |

---

## MapiNamedProperty (6 of 7) {#mapinamedproperty_6}

**Returns:** Aspose::Email::Mapi::

```cpp
MapiNamedProperty(System::String nameIdentifier, System::Guid propertyGuid, System::SharedPtr < MapiProperty > property)
```

| Parameter | Description |
| --- | --- |
| nameIdentifier |  |
| propertyGuid |  |
| property |  |

---

## MapiNamedProperty (7 of 7) {#mapinamedproperty_7}

**Returns:** Aspose::Email::Mapi::

```cpp
MapiNamedProperty(int64_t nameIdentifier, System::Guid propertyGuid, System::SharedPtr < MapiProperty > property)
```

| Parameter | Description |
| --- | --- |
| nameIdentifier |  |
| propertyGuid |  |
| property |  |

