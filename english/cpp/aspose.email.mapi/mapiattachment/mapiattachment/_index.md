---
title: "Aspose::Email::Mapi::MapiAttachment::MapiAttachment constructor"
linktitle: "MapiAttachment"
articleTitle: "MapiAttachment"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the MapiAttachment class."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapiattachment/mapiattachment/
---

## MapiAttachment (1 of 8) {#mapiattachment_1}

Initializes a new instance of the MapiAttachment class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiAttachment()
```

---

## MapiAttachment (2 of 8) {#mapiattachment_2}

Initializes a new instance of the MapiAttachment class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiAttachment(System::String itemId, System::String attachName, System::ArrayPtr< uint8_t > attachData, int32_t count)
```

| Parameter | Description |
| --- | --- |
| itemId | The attachment id |
| attachName | Name of the attach. |
| attachData | The attach data. |
| count | The attachments quantity. |

---

## MapiAttachment (3 of 8) {#mapiattachment_3}

Initializes a new instance of the MapiAttachment class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiAttachment(System::String itemId, System::String attachName, System::ArrayPtr< uint8_t > attachData, System::String mediaType, int32_t count)
```

| Parameter | Description |
| --- | --- |
| itemId | The attachment id |
| attachName | Name of the attach. |
| attachData | The attach data. |
| mediaType | The media type name. |
| count | The attachments quantity. |

---

## MapiAttachment (4 of 8) {#mapiattachment_4}

Initializes a new instance of the MapiAttachment class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiAttachment(System::String attachName, System::ArrayPtr< uint8_t > attachData, int32_t count, OutlookMessageFormat format, bool preserveDates, int32_t codePage)
```

| Parameter | Description |
| --- | --- |
| attachName | Name of the attach. |
| attachData | The attach data. |
| count | The count. |
| format | The format. |
| preserveDates | If set to true [preserve dates]. |
| codePage |  |

---

## MapiAttachment (5 of 8) {#mapiattachment_5}

Initializes a new instance of the MapiAttachment class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiAttachment(System::String attachName, System::SharedPtr < MapiMessageItemBase > attachMsg, int32_t count, OutlookMessageFormat format, bool preserveDates, int32_t codePage)
```

| Parameter | Description |
| --- | --- |
| attachName | Name of the attach. |
| attachMsg |  |
| count | The count. |
| format | The format. |
| preserveDates | If set to true [preserve dates]. |
| codePage |  |

---

## MapiAttachment (6 of 8) {#mapiattachment_6}

Initializes a new instance of the MapiAttachment class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiAttachment(System::String attachName, System::String attachContentId, System::ArrayPtr< uint8_t > attachData, int32_t count, OutlookMessageFormat format, bool preserveDates)
```

| Parameter | Description |
| --- | --- |
| attachName | Name of the attach. |
| attachContentId | ContentId of the attachment. |
| attachData | The attach data. |
| count | The count. |
| format | The format. |
| preserveDates | If set to true [preserve dates]. |

---

## MapiAttachment (7 of 8) {#mapiattachment_7}

Initializes a new instance of the MapiAttachment class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiAttachment(System::String attachName, System::SharedPtr < MapiMessage > attachMsg, int32_t count, OutlookMessageFormat format, bool preserveDates)
```

| Parameter | Description |
| --- | --- |
| attachName | Name of the attach. |
| attachMsg | The mapi message that will be attached. |
| count | The count. |
| format | The format. |
| preserveDates | If set to true [preserve dates]. |

---

## MapiAttachment (8 of 8) {#mapiattachment_8}

**Returns:** Aspose::Email::Mapi::

```cpp
MapiAttachment(System::SharedPtr < ReferenceAttachment > refAttach, int32_t codePage, int32_t count, OutlookMessageFormat format, bool preserveDates)
```

| Parameter | Description |
| --- | --- |
| refAttach |  |
| codePage |  |
| count |  |
| format |  |
| preserveDates |  |

