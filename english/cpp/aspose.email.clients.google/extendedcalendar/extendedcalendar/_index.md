---
title: "Aspose::Email::Clients::Google::ExtendedCalendar::ExtendedCalendar constructor"
linktitle: "ExtendedCalendar"
articleTitle: "ExtendedCalendar"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the ExtendedCalendar class."
type: docs
weight: 10
url: /cpp/aspose.email.clients.google/extendedcalendar/extendedcalendar/
---

## ExtendedCalendar (1 of 7) {#extendedcalendar_1}

Initializes a new instance of the ExtendedCalendar class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
ExtendedCalendar()
```

---

## ExtendedCalendar (2 of 7) {#extendedcalendar_2}

Initializes a new instance of the ExtendedCalendar class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
ExtendedCalendar(System::String summary)
```

| Parameter | Description |
| --- | --- |
| summary | Title of the calendar. |

---

## ExtendedCalendar (3 of 7) {#extendedcalendar_3}

Initializes a new instance of the ExtendedCalendar class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
ExtendedCalendar(System::String id, System::String summary)
```

| Parameter | Description |
| --- | --- |
| id | Identifier of the resource. |
| summary | Title of the calendar. |

---

## ExtendedCalendar (4 of 7) {#extendedcalendar_4}

Initializes a new instance of the ExtendedCalendar class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
ExtendedCalendar(System::String summary, System::String description, System::String location, System::String timeZone)
```

| Parameter | Description |
| --- | --- |
| summary | Title of the calendar. |
| description | Description of the calendar. |
| location | Geographic location of the calendar as free-form text. |
| timeZone | The time zone of the calendar. |

---

## ExtendedCalendar (5 of 7) {#extendedcalendar_5}

Initializes a new instance of the ExtendedCalendar class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
ExtendedCalendar(System::String id, System::String summary, System::String description, System::String location, System::String timeZone)
```

| Parameter | Description |
| --- | --- |
| id | Identifier of the resource. |
| summary | Title of the calendar. |
| description | Description of the calendar. |
| location | Geographic location of the calendar as free-form text. |
| timeZone | The time zone of the calendar. |

---

## ExtendedCalendar (6 of 7) {#extendedcalendar_6}

Initializes a new instance of the ExtendedCalendar class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
ExtendedCalendar(System::String id, System::String summary, System::String description, System::String location, System::String timeZone, System::String summaryOverride, System::String colorId, System::String backgroundColor, System::String foregroundColor, bool hidden, bool selected, Aspose::Email::Clients::Google::AccessRole accessRole, System::ArrayPtr< System::Collections::Generic::KeyValuePair< ReminderMethods , int32_t >> defaultReminders, bool primary)
```

| Parameter | Description |
| --- | --- |
| id | Identifier of the resource. |
| summary | Title of the calendar. |
| description | Description of the calendar. |
| location | Geographic location of the calendar as free-form text. |
| timeZone | The time zone of the calendar. |
| summaryOverride | The summary that the authenticated user has set for this calendar. |
| colorId | The color of the calendar. This is an ID referring to an entry in the "calendar" section of the colors definition (see the "colors" endpoint). |
| backgroundColor | The main color of the calendar in the format '#0088aa'. This property supersedes the index-based colorId property. |
| foregroundColor | The foreground color of the calendar in the format '#ffffff'. This property supersedes the index-based colorId property. |
| hidden | Whether the calendar has been hidden from the list. The default is False. |
| selected | Whether the calendar content shows up in the calendar UI. The default is False. |
| accessRole | The effective access role that the authenticated user has on the calendar. Read-only. Possible values are: |
| defaultReminders | The default reminders that the authenticated user has for this calendar. |
| primary | Whether the calendar is the primary calendar of the authenticated user. Read-only. The default is False. |

---

## ExtendedCalendar (7 of 7) {#extendedcalendar_7}

Initializes a new instance of the ExtendedCalendar class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
ExtendedCalendar(System::String id, System::String eTag, System::String summary, System::String description, System::String location, System::String timeZone, System::String summaryOverride, System::String colorId, System::String backgroundColor, System::String foregroundColor, bool hidden, bool selected, Aspose::Email::Clients::Google::AccessRole accessRole, System::ArrayPtr< System::Collections::Generic::KeyValuePair< ReminderMethods , int32_t >> defaultReminders, bool primary)
```

| Parameter | Description |
| --- | --- |
| id | Identifier of the resource. |
| eTag | An entity tag |
| summary | Title of the calendar. |
| description | Description of the calendar. |
| location | Geographic location of the calendar as free-form text. |
| timeZone | The time zone of the calendar. |
| summaryOverride | The summary that the authenticated user has set for this calendar. |
| colorId | The color of the calendar. This is an ID referring to an entry in the "calendar" section of the colors definition (see the "colors" endpoint). |
| backgroundColor | The main color of the calendar in the format '#0088aa'. This property supersedes the index-based colorId property. |
| foregroundColor | The foreground color of the calendar in the format '#ffffff'. This property supersedes the index-based colorId property. |
| hidden | Whether the calendar has been hidden from the list. The default is False. |
| selected | Whether the calendar content shows up in the calendar UI. The default is False. |
| accessRole | The effective access role that the authenticated user has on the calendar. Read-only. Possible values are: |
| defaultReminders | The default reminders that the authenticated user has for this calendar. |
| primary | Whether the calendar is the primary calendar of the authenticated user. Read-only. The default is False. |

