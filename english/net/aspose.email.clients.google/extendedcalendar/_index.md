---
title: Class ExtendedCalendar
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Google.ExtendedCalendar class. A set of extended metadata such as a colors for a single calendar
type: docs
weight: 15730
url: /net/aspose.email.clients.google/extendedcalendar/
---
## ExtendedCalendar class

A set of extended metadata, such as a colors, for a single calendar.

```csharp
public class ExtendedCalendar : Calendar
```

## Constructors

| Name | Description |
| --- | --- |
| [ExtendedCalendar](extendedcalendar/#constructor)() | Initializes a new instance of the ExtendedCalendar class. |
| [ExtendedCalendar](extendedcalendar/#constructor_1)(string) | Initializes a new instance of the ExtendedCalendar class. |
| [ExtendedCalendar](extendedcalendar/#constructor_2)(string, string) | Initializes a new instance of the ExtendedCalendar class. |
| [ExtendedCalendar](extendedcalendar/#constructor_3)(string, string, string, string) | Initializes a new instance of the ExtendedCalendar class. |
| [ExtendedCalendar](extendedcalendar/#constructor_4)(string, string, string, string, string) | Initializes a new instance of the ExtendedCalendar class. |
| [ExtendedCalendar](extendedcalendar/#constructor_5)(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Initializes a new instance of the ExtendedCalendar class. |
| [ExtendedCalendar](extendedcalendar/#constructor_6)(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Initializes a new instance of the ExtendedCalendar class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [AccessRole](../../aspose.email.clients.google/extendedcalendar/accessrole/) { get; } | The effective access role that the authenticated user has on the calendar. Read-only. Possible values are: |
| virtual [BackgroundColor](../../aspose.email.clients.google/extendedcalendar/backgroundcolor/) { get; set; } | The main color of the calendar in the format '#0088aa'. This property supersedes the index-based colorId property. |
| virtual [ColorId](../../aspose.email.clients.google/extendedcalendar/colorid/) { get; set; } | The color of the calendar. This is an ID referring to an entry in the "calendar" section of the colors definition (see the "colors" endpoint). |
| virtual [ConferenceProperties](../../aspose.email.clients.google/calendar/conferenceproperties/) { get; } | Gets conferencing properties for this calendar. |
| virtual [DefaultReminders](../../aspose.email.clients.google/extendedcalendar/defaultreminders/) { get; set; } | The default reminders that the authenticated user has for this calendar. |
| virtual [Description](../../aspose.email.clients.google/calendar/description/) { get; set; } | Description of the calendar. |
| virtual [ETag](../../aspose.email.clients.google/basedataobject/etag/) { get; set; } | An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. This allows caches to be more efficient, and saves bandwidth, as a web server does not need to send a full response if the content has not changed. ETags can also be used for optimistic concurrency control, as a way to help prevent simultaneous updates of a resource from overwriting each other. |
| virtual [ForegroundColor](../../aspose.email.clients.google/extendedcalendar/foregroundcolor/) { get; set; } | The foreground color of the calendar in the format '#ffffff'. This property supersedes the index-based colorId property. |
| virtual [Hidden](../../aspose.email.clients.google/extendedcalendar/hidden/) { get; set; } | Whether the calendar has been hidden from the list. The default is False. |
| virtual [Id](../../aspose.email.clients.google/basedataobject/id/) { get; set; } | Identifier of the resource. |
| virtual [Kind](../../aspose.email.clients.google/basedataobject/kind/) { get; } | Type of the resource |
| virtual [Location](../../aspose.email.clients.google/calendar/location/) { get; set; } | Geographic location of the calendar as free-form text. |
| virtual [NotificationSettings](../../aspose.email.clients.google/extendedcalendar/notificationsettings/) { get; set; } | The notifications that the authenticated user is receiving for this calendar. |
| virtual [Primary](../../aspose.email.clients.google/extendedcalendar/primary/) { get; set; } | Whether the calendar is the primary calendar of the authenticated user. Read-only. The default is False. |
| virtual [Selected](../../aspose.email.clients.google/extendedcalendar/selected/) { get; set; } | Whether the calendar content shows up in the calendar UI. The default is False. |
| virtual [Summary](../../aspose.email.clients.google/calendar/summary/) { get; set; } | Title of the calendar. |
| virtual [SummaryOverride](../../aspose.email.clients.google/extendedcalendar/summaryoverride/) { get; set; } | The summary that the authenticated user has set for this calendar. |
| virtual [TimeZone](../../aspose.email.clients.google/calendar/timezone/) { get; set; } | The time zone of the calendar. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.email.clients.google/extendedcalendar/tostring/)() | Returns a string which represents the object instance. |

## Fields

| Name | Description |
| --- | --- |
| const [ExtendedCalendarKind](../../aspose.email.clients.google/extendedcalendar/extendedcalendarkind/) | Type of the resource "calendar#calendarListEntry". |
| const [ListKind](../../aspose.email.clients.google/extendedcalendar/listkind/) | Type of the resources list "calendar#calendarList". |

### See Also

* class [Calendar](../calendar/)
* namespace [Aspose.Email.Clients.Google](../../aspose.email.clients.google/)
* assembly [Aspose.Email](../../)


