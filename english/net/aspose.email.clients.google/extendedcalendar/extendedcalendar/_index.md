---
title: ExtendedCalendar
second_title: Aspose.Email for .NET API Reference
description: Initializes a new instance of the ExtendedCalendar class.
type: docs
weight: 10
url: /net/aspose.email.clients.google/extendedcalendar/extendedcalendar/
---
## ExtendedCalendar() {#constructor}

Initializes a new instance of the ExtendedCalendar class.

```csharp
public ExtendedCalendar()
```

### See Also

* class [ExtendedCalendar](../../extendedcalendar)
* namespace [Aspose.Email.Clients.Google](../../extendedcalendar)
* assembly [Aspose.Email](../../../)

---

## ExtendedCalendar(string) {#constructor_1}

Initializes a new instance of the ExtendedCalendar class.

```csharp
public ExtendedCalendar(string summary)
```

| Parameter | Type | Description |
| --- | --- | --- |
| summary | String | Title of the calendar. |

### See Also

* class [ExtendedCalendar](../../extendedcalendar)
* namespace [Aspose.Email.Clients.Google](../../extendedcalendar)
* assembly [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string) {#constructor_2}

Initializes a new instance of the ExtendedCalendar class.

```csharp
public ExtendedCalendar(string id, string summary)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Identifier of the resource. |
| summary | String | Title of the calendar. |

### See Also

* class [ExtendedCalendar](../../extendedcalendar)
* namespace [Aspose.Email.Clients.Google](../../extendedcalendar)
* assembly [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string) {#constructor_3}

Initializes a new instance of the ExtendedCalendar class.

```csharp
public ExtendedCalendar(string summary, string description, string location, string timeZone)
```

| Parameter | Type | Description |
| --- | --- | --- |
| summary | String | Title of the calendar. |
| description | String | Description of the calendar. |
| location | String | Geographic location of the calendar as free-form text. |
| timeZone | String | The time zone of the calendar. |

### See Also

* class [ExtendedCalendar](../../extendedcalendar)
* namespace [Aspose.Email.Clients.Google](../../extendedcalendar)
* assembly [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string) {#constructor_4}

Initializes a new instance of the ExtendedCalendar class.

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Identifier of the resource. |
| summary | String | Title of the calendar. |
| description | String | Description of the calendar. |
| location | String | Geographic location of the calendar as free-form text. |
| timeZone | String | The time zone of the calendar. |

### See Also

* class [ExtendedCalendar](../../extendedcalendar)
* namespace [Aspose.Email.Clients.Google](../../extendedcalendar)
* assembly [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_5}

Initializes a new instance of the ExtendedCalendar class.

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone, string summaryOverride, string colorId, string backgroundColor, 
    string foregroundColor, bool hidden, bool selected, AccessRole accessRole, 
    KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Identifier of the resource. |
| summary | String | Title of the calendar. |
| description | String | Description of the calendar. |
| location | String | Geographic location of the calendar as free-form text. |
| timeZone | String | The time zone of the calendar. |
| summaryOverride | String | The summary that the authenticated user has set for this calendar. |
| colorId | String | The color of the calendar. This is an ID referring to an entry in the "calendar" section of the colors definition (see the "colors" endpoint). |
| backgroundColor | String | The main color of the calendar in the format '#0088aa'. This property supersedes the index-based colorId property. |
| foregroundColor | String | The foreground color of the calendar in the format '#ffffff'. This property supersedes the index-based colorId property. |
| hidden | Boolean | Whether the calendar has been hidden from the list. The default is False. |
| selected | Boolean | Whether the calendar content shows up in the calendar UI. The default is False. |
| accessRole | AccessRole | The effective access role that the authenticated user has on the calendar. Read-only. Possible values are: |
| defaultReminders | KeyValuePair`2[] | The default reminders that the authenticated user has for this calendar. |
| primary | Boolean | Whether the calendar is the primary calendar of the authenticated user. Read-only. The default is False. |

### See Also

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* namespace [Aspose.Email.Clients.Google](../../extendedcalendar)
* assembly [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_6}

Initializes a new instance of the ExtendedCalendar class.

```csharp
public ExtendedCalendar(string id, string eTag, string summary, string description, 
    string location, string timeZone, string summaryOverride, string colorId, 
    string backgroundColor, string foregroundColor, bool hidden, bool selected, 
    AccessRole accessRole, KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Identifier of the resource. |
| eTag | String | An entity tag |
| summary | String | Title of the calendar. |
| description | String | Description of the calendar. |
| location | String | Geographic location of the calendar as free-form text. |
| timeZone | String | The time zone of the calendar. |
| summaryOverride | String | The summary that the authenticated user has set for this calendar. |
| colorId | String | The color of the calendar. This is an ID referring to an entry in the "calendar" section of the colors definition (see the "colors" endpoint). |
| backgroundColor | String | The main color of the calendar in the format '#0088aa'. This property supersedes the index-based colorId property. |
| foregroundColor | String | The foreground color of the calendar in the format '#ffffff'. This property supersedes the index-based colorId property. |
| hidden | Boolean | Whether the calendar has been hidden from the list. The default is False. |
| selected | Boolean | Whether the calendar content shows up in the calendar UI. The default is False. |
| accessRole | AccessRole | The effective access role that the authenticated user has on the calendar. Read-only. Possible values are: |
| defaultReminders | KeyValuePair`2[] | The default reminders that the authenticated user has for this calendar. |
| primary | Boolean | Whether the calendar is the primary calendar of the authenticated user. Read-only. The default is False. |

### See Also

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* namespace [Aspose.Email.Clients.Google](../../extendedcalendar)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
