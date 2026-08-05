---
title: "Aspose::Email::Mapi::MapiProperty::MapiProperty constructor"
linktitle: "MapiProperty"
articleTitle: "MapiProperty"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the MapiProperty class."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapiproperty/mapiproperty/
---

## MapiProperty (1 of 9) {#mapiproperty_1}

Initializes a new instance of the MapiProperty class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiProperty(int64_t tag, System::ArrayPtr< uint8_t > data)
```

| Parameter | Description |
| --- | --- |
| tag | The tag key of the property. |
| data | The binary data of the property. |

---

## MapiProperty (2 of 9) {#mapiproperty_2}

Initializes a new instance of the MapiProperty class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiProperty(int64_t tag)
```

| Parameter | Description |
| --- | --- |
| tag | The tag key of the property. |

---

## MapiProperty (3 of 9) {#mapiproperty_3}

Initializes a new instance of the MapiProperty class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiProperty(System::SharedPtr < PidTagPropertyDescriptor > pd, System::SharedPtr < System::Object > data)
```

| Parameter | Description |
| --- | --- |
| pd | Property descriptor |
| data | The data of the property. |

---

## MapiProperty (4 of 9) {#mapiproperty_4}

Initializes a new instance of the MapiProperty class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiProperty(System::SharedPtr < PidLidPropertyDescriptor > pd, System::SharedPtr < System::Object > data)
```

| Parameter | Description |
| --- | --- |
| pd | Property descriptor |
| data | The data of the property. |

---

## MapiProperty (5 of 9) {#mapiproperty_5}

**Returns:** Aspose::Email::Mapi::

```cpp
MapiProperty(System::SharedPtr < PidTagPropertyDescriptor > pd, System::SharedPtr < System::Collections::Generic::IList< System::SharedPtr < System::Object >>> values)
```

| Parameter | Description |
| --- | --- |
| pd |  |
| values |  |

---

## MapiProperty (6 of 9) {#mapiproperty_6}

Initializes a new instance of the MapiProperty class. This overload is used to create a multiple valued property, PT_MV_*.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiProperty(int64_t tag, System::SharedPtr < System::Collections::Generic::IList< System::SharedPtr < System::Object >>> values)
```

| Parameter | Description |
| --- | --- |
| tag | The property tag. |
| values | The values. |

---

## MapiProperty (7 of 9) {#mapiproperty_7}

Initializes a new instance of the MapiProperty class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiProperty(int64_t tag, int64_t signedParam, System::ArrayPtr< uint8_t > data)
```

| Parameter | Description |
| --- | --- |
| tag | The property tag. |
| signedParam | The signed. |
| data | The property data. |

---

## MapiProperty (8 of 9) {#mapiproperty_8}

Initializes a new instance of the MapiProperty class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiProperty(System::String name, int64_t tag, int64_t signedParam, System::ArrayPtr< uint8_t > data)
```

| Parameter | Description |
| --- | --- |
| name | The name. |
| tag | The tag key of the property. |
| signedParam | Indicates the data is signed or not. |
| data | The binary data of the property. |

---

## MapiProperty (9 of 9) {#mapiproperty_9}

Initializes a new instance of the MapiProperty class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiProperty()
```

