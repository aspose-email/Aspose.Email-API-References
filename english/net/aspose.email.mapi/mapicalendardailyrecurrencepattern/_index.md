---
title: Class MapiCalendarDailyRecurrencePattern
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarDailyRecurrencePattern class. Represents a daily recurrence pattern for MAPI calendar items allowing you to define how recurring meetings or events repeat on a daily basis. This class provides properties to configure the recurrence interval and specific days of the week for weeklybased daily patterns
type: docs
weight: 16750
url: /net/aspose.email.mapi/mapicalendardailyrecurrencepattern/
---
## MapiCalendarDailyRecurrencePattern class

Represents a daily recurrence pattern for MAPI calendar items, allowing you to define how recurring meetings or events repeat on a daily basis. This class provides properties to configure the recurrence interval and specific days of the week for weekly-based daily patterns.

```csharp
public sealed class MapiCalendarDailyRecurrencePattern : MapiCalendarRecurrencePattern
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendarDailyRecurrencePattern](mapicalendardailyrecurrencepattern/)() | Initializes a new instance of the `MapiCalendarDailyRecurrencePattern` class |

## Properties

| Name | Description |
| --- | --- |
| [CalendarType](../../aspose.email.mapi/mapicalendarrecurrencepattern/calendartype/) { get; set; } | Gets or sets the type of calendar that is used |
| [DayOfWeek](../../aspose.email.mapi/mapicalendardailyrecurrencepattern/dayofweek/) { get; set; } | Gets or sets the days of week at which the event occurs |
| [DeletedInstanceDates](../../aspose.email.mapi/mapicalendarrecurrencepattern/deletedinstancedates/) { get; } | An array of dates, each of which is the original instance date of either a deleted instance or a modified instance for this recurrence. |
| [EndDate](../../aspose.email.mapi/mapicalendarrecurrencepattern/enddate/) { get; set; } | Gets or sets Defines the end date of an item recurrence pattern. |
| [EndType](../../aspose.email.mapi/mapicalendarrecurrencepattern/endtype/) { get; set; } | Gets or sets the ending type for the recurrence. |
| [Exceptions](../../aspose.email.mapi/mapicalendarrecurrencepattern/exceptions/) { get; } | An exception specifies changes to an instance of a recurring series. |
| virtual [Frequency](../../aspose.email.mapi/mapicalendarrecurrencepattern/frequency/) { get; } | Gets or sets the frequency of the recurring series. |
| [ModifiedInstanceDates](../../aspose.email.mapi/mapicalendarrecurrencepattern/modifiedinstancedates/) { get; } | An array of dates, each of which is the date of a modified instance. |
| [OccurrenceCount](../../aspose.email.mapi/mapicalendarrecurrencepattern/occurrencecount/) { get; set; } | Gets or sets the number of occurrences in a recurrence. |
| [PatternType](../../aspose.email.mapi/mapicalendarrecurrencepattern/patterntype/) { get; set; } | Gets or sets the type of recurrence pattern |
| override [Period](../../aspose.email.mapi/mapicalendardailyrecurrencepattern/period/) { get; set; } | Gets or sets interval (in days) at which the meeting pattern repeats |
| [SlidingFlag](../../aspose.email.mapi/mapicalendarrecurrencepattern/slidingflag/) { get; set; } | Defines whether pattern is sliding or not. |
| [StartDate](../../aspose.email.mapi/mapicalendarrecurrencepattern/startdate/) { get; set; } | Gets or sets the start date of an item recurrence pattern. |
| [WeekStartDay](../../aspose.email.mapi/mapicalendarrecurrencepattern/weekstartday/) { get; set; } | Gets or sets the first day of the calendar week. |

## Remarks

Use this class to define recurring calendar events that occur every N days or on specific days of the week. The [`Period`](./period/) property controls the interval (in days), while [`DayOfWeek`](./dayofweek/) specifies which days of the week the event occurs when using weekly recurrence patterns. This pattern is used in [`MapiCalendar`](../mapicalendar/) to configure recurring meeting schedules.

### See Also

* class [MapiCalendarRecurrencePattern](../mapicalendarrecurrencepattern/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


