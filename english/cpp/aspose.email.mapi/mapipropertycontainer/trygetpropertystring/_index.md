---
title: "Aspose::Email::Mapi::MapiPropertyContainer::TryGetPropertyString method"
linktitle: "TryGetPropertyString"
articleTitle: "TryGetPropertyString"
second_title: "Aspose.Email for C++"
description: "Try to get a property data as string with specified tag."
type: docs
weight: 220
url: /cpp/aspose.email.mapi/mapipropertycontainer/trygetpropertystring/
---

## TryGetPropertyString (1 of 4) {#trygetpropertystring_1}

Try to get a property data as string with specified tag.

**Returns:** String that contains the contents of property data.

```cpp
TryGetPropertyString(int64_t tag)
```

| Parameter | Description |
| --- | --- |
| tag | The property tag key. |

---

## TryGetPropertyString (2 of 4) {#trygetpropertystring_2}

Try to get a property data as string with specified tag and code page.

**Returns:** String that contains the contents of property data.

```cpp
TryGetPropertyString(int64_t tag, int32_t codepage)
```

| Parameter | Description |
| --- | --- |
| tag | The property tag key. |
| codepage | The code page. |

---

## TryGetPropertyString (3 of 4) {#trygetpropertystring_3}

Gets the value of the specified property as String type. A return value indicates whether the operation succeeded.

**Returns:** true if s was converted successfully; otherwise, false.

```cpp
TryGetPropertyString(int64_t tag, System::String & value)
```

| Parameter | Description |
| --- | --- |
| tag | The MAPI property tag. |
| value | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

---

## TryGetPropertyString (4 of 4) {#trygetpropertystring_4}

Gets the value of the specified property as String type. A return value indicates whether the operation succeeded.

**Returns:** true if s was converted successfully; otherwise, false.

```cpp
TryGetPropertyString(int64_t tag, System::String & value, int32_t codepage)
```

| Parameter | Description |
| --- | --- |
| tag | The MAPI property tag. |
| value | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |
| codepage | The specified codepage used to get string value. |

