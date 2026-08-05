---
title: "Aspose::Email::Mapi::MapiCalendar::MapiCalendar constructor"
linktitle: "MapiCalendar"
articleTitle: "MapiCalendar"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the MapiCalendar class"
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapicalendar/mapicalendar/
---

## MapiCalendar (1 of 8) {#mapicalendar_1}

Initializes a new instance of the MapiCalendar class

**Returns:** Aspose::Email::Mapi::

```cpp
MapiCalendar()
```

---

## MapiCalendar (2 of 8) {#mapicalendar_2}

Initializes a new instance of the MapiCalendar class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiCalendar(System::String location, System::String summary, System::String description, System::DateTime startDate, System::DateTime endDate)
```

| Parameter | Description |
| --- | --- |
| location | The appointment location. |
| summary | The appointment summary. |
| description | The appointment description. |
| startDate | The start date. |
| endDate | The end date. |

---

## MapiCalendar (3 of 8) {#mapicalendar_3}

Initializes a new instance of the MapiCalendar class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiCalendar(System::String location, System::DateTime startDate, System::DateTime endDate, System::String organizer, System::SharedPtr < MapiRecipientCollection > attendees)
```

| Parameter | Description |
| --- | --- |
| location | The meeting location. |
| startDate | The start date. |
| endDate | The end date. |
| organizer | The meeting organizer address. |
| attendees | The meeting attendees. |

---

## MapiCalendar (4 of 8) {#mapicalendar_4}

Initializes a new instance of the MapiCalendar class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiCalendar(System::String location, System::String summary, System::String description, System::DateTime startDate, System::DateTime endDate, System::String organizer, System::SharedPtr < MapiRecipientCollection > attendees)
```

| Parameter | Description |
| --- | --- |
| location | The meeting location. |
| summary | The meeting summary. |
| description | The meeting description. |
| startDate | The start date. |
| endDate | The end date. |
| organizer | The meeting organizer address. |
| attendees | The meeting attendees. |

---

## MapiCalendar (5 of 8) {#mapicalendar_5}

Initializes a new instance of the MapiCalendar class.

**Returns:** Aspose::Email::Mapi::

```cpp
MapiCalendar(System::String location, System::String summary, System::String description, System::DateTime startDate, System::DateTime endDate, System::SharedPtr < MapiElectronicAddress > organizer, System::SharedPtr < MapiRecipientCollection > attendees)
```

| Parameter | Description |
| --- | --- |
| location | The meeting location. |
| summary | The meeting summary. |
| description | The meeting description. |
| startDate | The start date. |
| endDate | The end date. |
| organizer | The meeting organizer. |
| attendees | The meeting attendees. |

---

## MapiCalendar (6 of 8) {#mapicalendar_6}

Initializes a new instance of the MapiCalendar class

**Returns:** Aspose::Email::Mapi::

```cpp
MapiCalendar(System::SharedPtr < MapiMessage > msg)
```

| Parameter | Description |
| --- | --- |
| msg | A MapiMessage whose class name is IPM.Appointment or starts with IPM.Appointment. or IPM.Schedule.meeting. |

---

## MapiCalendar (7 of 8) {#mapicalendar_7}

**Returns:** Aspose::Email::Mapi::

```cpp
MapiCalendar(System::SharedPtr < MapiMessageItemBase > msg, bool checkMessageClass)
```

| Parameter | Description |
| --- | --- |
| msg |  |
| checkMessageClass |  |

---

## MapiCalendar (8 of 8) {#mapicalendar_8}

**Returns:** Aspose::Email::Mapi::

```cpp
MapiCalendar(int64_t storeSupportMask)
```

| Parameter | Description |
| --- | --- |
| storeSupportMask |  |

