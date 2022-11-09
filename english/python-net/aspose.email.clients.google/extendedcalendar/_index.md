---
title: ExtendedCalendar
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 100
url: /python-net/aspose.email.clients.google/extendedcalendar/
---

## ExtendedCalendar class

A set of extended metadata, such as a colors, for a single calendar.

The ExtendedCalendar type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|ExtendedCalendar()|Initializes a new instance of the ExtendedCalendar class.|
|ExtendedCalendar(summary)|Initializes a new instance of the ExtendedCalendar class|
|ExtendedCalendar(id, summary)|Initializes a new instance of the ExtendedCalendar class|
|ExtendedCalendar(summary, description, location, time_zone)|Initializes a new instance of the ExtendedCalendar class|
|ExtendedCalendar(id, summary, description, location, time_zone)|Initializes a new instance of the ExtendedCalendar class|
## Properties
| Name | Description |
| :- | :- |
|kind|  |
|e_tag|  |
|id|  |
|summary|Title of the calendar.|
|description|Description of the calendar.|
|location|Geographic location of the calendar as free-form text.|
|time_zone|The time zone of the calendar.|
|conference_properties|Gets conferencing properties for this calendar.|
|CALENDAR_KIND|Type of the resource "calendar#calendar".|
|summary_override|The summary that the authenticated user has set for this calendar.|
|color_id|The color of the calendar. <br/>            This is an ID referring to an entry in the "calendar" section of the colors definition (see the "colors" endpoint).|
|background_color|The main color of the calendar in the format '#0088aa'. <br/>            This property supersedes the index-based colorId property.|
|foreground_color|The foreground color of the calendar in the format '#ffffff'. <br/>            This property supersedes the index-based colorId property.|
|hidden|Whether the calendar has been hidden from the list. <br/>            The default is False.|
|selected|Whether the calendar content shows up in the calendar UI. <br/>            The default is False.|
|access_role|The effective access role that the authenticated user has on the calendar. Read-only. Possible values are:|
|primary|Whether the calendar is the primary calendar of the authenticated user. Read-only. <br/>            The default is False.|
|EXTENDED_CALENDAR_KIND|Type of the resource "calendar#calendarListEntry".|
|LIST_KIND|Type of the resources list "calendar#calendarList".|

### See Also

* namespace [aspose.email.clients.google](/python-net/aspose.email.clients.google/)
* assembly [Aspose.Email](/python-net/)

