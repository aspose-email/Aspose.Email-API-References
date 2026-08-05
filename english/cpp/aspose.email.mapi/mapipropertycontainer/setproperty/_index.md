---
title: "Aspose::Email::Mapi::MapiPropertyContainer::SetProperty method"
linktitle: "SetProperty"
articleTitle: "SetProperty"
second_title: "Aspose.Email for C++"
description: "Set the property."
type: docs
weight: 150
url: /cpp/aspose.email.mapi/mapipropertycontainer/setproperty/
---

## SetProperty (1 of 8) {#setproperty_1}

Set the property.

**Returns:** void Aspose::Email::Mapi::

```cpp
SetProperty(int64_t tag, System::ArrayPtr< uint8_t > data)
```

| Parameter | Description |
| --- | --- |
| tag | The tag. |
| data | The property data. |

---

## SetProperty (2 of 8) {#setproperty_2}

Set the datetime property.

**Returns:** void Aspose::Email::Mapi::

```cpp
SetProperty(int64_t tag, System::DateTime dateTime)
```

| Parameter | Description |
| --- | --- |
| tag | The tag. |
| dateTime | The dateTime. |

---

## SetProperty (3 of 8) {#setproperty_3}

Set the string property with CurrentEncoding

**Returns:** void Aspose::Email::Mapi::

```cpp
SetProperty(int64_t tag, System::String value)
```

| Parameter | Description |
| --- | --- |
| tag | The tag. |
| value | The property value. |

---

## SetProperty (4 of 8) {#setproperty_4}

Set the string property.

**Returns:** void Aspose::Email::Mapi::

```cpp
SetProperty(int64_t tag, System::String value, bool isUnicode)
```

| Parameter | Description |
| --- | --- |
| tag | The tag. |
| value | The property value. |
| isUnicode | If true, the Unicode encoding is used, otherwise the CurrentEncoding. |

---

## SetProperty (5 of 8) {#setproperty_5}

Set the string property.

**Returns:** void Aspose::Email::Mapi::

```cpp
SetProperty(int64_t tag, System::String value, OutlookMessageFormat format)
```

| Parameter | Description |
| --- | --- |
| tag | The tag. |
| value | The property value. |
| format | The type of encoding. If format == Unicode, the Unicode encoding is used, otherwise the CurrentEncoding. |

---

## SetProperty (6 of 8) {#setproperty_6}

Set the string property.

**Returns:** void Aspose::Email::Mapi::

```cpp
SetProperty(int64_t tag, System::String value, System::SharedPtr < System::Text::Encoding > nonUnicodeEncoding)
```

| Parameter | Description |
| --- | --- |
| tag | The tag. |
| value | The property value. |
| nonUnicodeEncoding | If message is Unicode, the Unicode encoding is used, otherwise the nonUnicodeEncoding. |

---

## SetProperty (7 of 8) {#setproperty_7}

Sets the property.

**Returns:** virtual void Aspose::Email::Mapi::

```cpp
SetProperty(System::SharedPtr < MapiProperty > value)
```

| Parameter | Description |
| --- | --- |
| value | The property. |

---

## SetProperty (8 of 8) {#setproperty_8}

Sets MAPI property.

**Returns:** virtual void Aspose::Email::Mapi::

```cpp
SetProperty(System::SharedPtr < PropertyDescriptor > pd, System::SharedPtr < System::Object > value)
```

| Parameter | Description |
| --- | --- |
| pd | The property descriptor. |
| value | The property data. |

