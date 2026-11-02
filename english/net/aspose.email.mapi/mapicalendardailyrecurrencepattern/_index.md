---
title: Class MapiCalendarDailyRecurrencePattern
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarDailyRecurrencePattern class. A recurrence that repeats every N days or on selected days of the week
type: docs
weight: 16750
url: /net/aspose.email.mapi/mapicalendardailyrecurrencepattern/
---
## MapiCalendarDailyRecurrencePattern class

A recurrence that repeats every N days, or on selected days of the week.

```csharp
public sealed class MapiCalendarDailyRecurrencePattern : MapiCalendarRecurrencePattern
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendarDailyRecurrencePattern](mapicalendardailyrecurrencepattern/)() | Initializes a new instance of the `MapiCalendarDailyRecurrencePattern` class. |

## Properties

| Name | Description |
| --- | --- |
| [CalendarType](../../aspose.email.mapi/mapicalendarrecurrencepattern/calendartype/) { get; set; } | Gets or sets the calendar system of the recurrence. |
| [DayOfWeek](../../aspose.email.mapi/mapicalendardailyrecurrencepattern/dayofweek/) { get; set; } | Gets or sets the days of the week the event occurs on, for a recurrence on selected weekdays. |
| [DeletedInstanceDates](../../aspose.email.mapi/mapicalendarrecurrencepattern/deletedinstancedates/) { get; } | Gets the original dates of the occurrences that were deleted or changed. |
| [EndDate](../../aspose.email.mapi/mapicalendarrecurrencepattern/enddate/) { get; set; } | Gets or sets the date of the last occurrence, used when [`EndType`](../mapicalendarrecurrencepattern/endtype/) is `EndAfterDate`. |
| [EndType](../../aspose.email.mapi/mapicalendarrecurrencepattern/endtype/) { get; set; } | Gets or sets how the series ends. |
| [Exceptions](../../aspose.email.mapi/mapicalendarrecurrencepattern/exceptions/) { get; } | Gets the exceptions of the series: the occurrences whose details were changed. |
| virtual [Frequency](../../aspose.email.mapi/mapicalendarrecurrencepattern/frequency/) { get; } | Gets how often the series repeats. |
| [ModifiedInstanceDates](../../aspose.email.mapi/mapicalendarrecurrencepattern/modifiedinstancedates/) { get; } | Gets the dates of the occurrences that were changed. |
| [OccurrenceCount](../../aspose.email.mapi/mapicalendarrecurrencepattern/occurrencecount/) { get; set; } | Gets or sets the number of occurrences, used when [`EndType`](../mapicalendarrecurrencepattern/endtype/) is `EndAfterNOccurrences`. |
| [PatternType](../../aspose.email.mapi/mapicalendarrecurrencepattern/patterntype/) { get; set; } | Gets or sets the type of the recurrence pattern. |
| override [Period](../../aspose.email.mapi/mapicalendardailyrecurrencepattern/period/) { get; set; } | Gets or sets the interval of the recurrence, in days. |
| [SlidingFlag](../../aspose.email.mapi/mapicalendarrecurrencepattern/slidingflag/) { get; set; } | Gets or sets a value indicating whether the next occurrence is calculated from the completion of the previous one rather than from a fixed schedule. Used by recurring tasks. |
| [StartDate](../../aspose.email.mapi/mapicalendarrecurrencepattern/startdate/) { get; set; } | Gets or sets the date of the first occurrence. |
| [WeekStartDay](../../aspose.email.mapi/mapicalendarrecurrencepattern/weekstartday/) { get; set; } | Gets or sets the first day of the week. |

## Remarks

[`Period`](./period/) is the interval in days. To repeat on working days only, set [`DayOfWeek`](./dayofweek/) to the days of the week instead.

### See Also

* class [MapiCalendarRecurrencePattern](../mapicalendarrecurrencepattern/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


