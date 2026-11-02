---
title: Class MapiCalendarRecurrencePattern
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarRecurrencePattern class. The base class of the recurrence patterns how often a series repeats from when and until when
type: docs
weight: 16870
url: /net/aspose.email.mapi/mapicalendarrecurrencepattern/
---
## MapiCalendarRecurrencePattern class

The base class of the recurrence patterns: how often a series repeats, from when, and until when.

```csharp
public abstract class MapiCalendarRecurrencePattern
```

## Properties

| Name | Description |
| --- | --- |
| [CalendarType](../../aspose.email.mapi/mapicalendarrecurrencepattern/calendartype/) { get; set; } | Gets or sets the calendar system of the recurrence. |
| [DeletedInstanceDates](../../aspose.email.mapi/mapicalendarrecurrencepattern/deletedinstancedates/) { get; } | Gets the original dates of the occurrences that were deleted or changed. |
| [EndDate](../../aspose.email.mapi/mapicalendarrecurrencepattern/enddate/) { get; set; } | Gets or sets the date of the last occurrence, used when [`EndType`](./endtype/) is `EndAfterDate`. |
| [EndType](../../aspose.email.mapi/mapicalendarrecurrencepattern/endtype/) { get; set; } | Gets or sets how the series ends. |
| [Exceptions](../../aspose.email.mapi/mapicalendarrecurrencepattern/exceptions/) { get; } | Gets the exceptions of the series: the occurrences whose details were changed. |
| virtual [Frequency](../../aspose.email.mapi/mapicalendarrecurrencepattern/frequency/) { get; } | Gets how often the series repeats. |
| [ModifiedInstanceDates](../../aspose.email.mapi/mapicalendarrecurrencepattern/modifiedinstancedates/) { get; } | Gets the dates of the occurrences that were changed. |
| [OccurrenceCount](../../aspose.email.mapi/mapicalendarrecurrencepattern/occurrencecount/) { get; set; } | Gets or sets the number of occurrences, used when [`EndType`](./endtype/) is `EndAfterNOccurrences`. |
| [PatternType](../../aspose.email.mapi/mapicalendarrecurrencepattern/patterntype/) { get; set; } | Gets or sets the type of the recurrence pattern. |
| abstract [Period](../../aspose.email.mapi/mapicalendarrecurrencepattern/period/) { get; set; } | Gets or sets the interval of the recurrence, in the units of the pattern (days, weeks or months). |
| [SlidingFlag](../../aspose.email.mapi/mapicalendarrecurrencepattern/slidingflag/) { get; set; } | Gets or sets a value indicating whether the next occurrence is calculated from the completion of the previous one rather than from a fixed schedule. Used by recurring tasks. |
| [StartDate](../../aspose.email.mapi/mapicalendarrecurrencepattern/startdate/) { get; set; } | Gets or sets the date of the first occurrence. |
| [WeekStartDay](../../aspose.email.mapi/mapicalendarrecurrencepattern/weekstartday/) { get; set; } | Gets or sets the first day of the week. |

## Remarks

Use one of the derived classes: [`MapiCalendarDailyRecurrencePattern`](../mapicalendardailyrecurrencepattern/), [`MapiCalendarWeeklyRecurrencePattern`](../mapicalendarweeklyrecurrencepattern/), [`MapiCalendarMonthlyRecurrencePattern`](../mapicalendarmonthlyrecurrencepattern/), [`MapiCalendarMonthlyNthRecurrencePattern`](../mapicalendarmonthlynthrecurrencepattern/) or [`MapiCalendarYearlyAndMonthlyRecurrencePattern`](../mapicalendaryearlyandmonthlyrecurrencepattern/), or create a pattern from an iCalendar rule with [`MapiCalendarRecurrencePatternFactory`](../mapicalendarrecurrencepatternfactory/).

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


