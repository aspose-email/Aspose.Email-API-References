---
title: Class MapiCalendarMonthlyRecurrencePattern
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarMonthlyRecurrencePattern class. A recurrence on a given day of every N months such as the 15th of every month
type: docs
weight: 16810
url: /net/aspose.email.mapi/mapicalendarmonthlyrecurrencepattern/
---
## MapiCalendarMonthlyRecurrencePattern class

A recurrence on a given day of every N months, such as "the 15th of every month".

```csharp
public class MapiCalendarMonthlyRecurrencePattern : MapiCalendarYearlyAndMonthlyRecurrencePattern
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendarMonthlyRecurrencePattern](mapicalendarmonthlyrecurrencepattern/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CalendarType](../../aspose.email.mapi/mapicalendarrecurrencepattern/calendartype/) { get; set; } | Gets or sets the calendar system of the recurrence. |
| [Day](../../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/day/) { get; set; } | Gets or sets the day of the month the event occurs on. |
| [DayOfWeek](../../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/dayofweek/) { get; set; } | Gets or sets the days of the week the event occurs on, for a recurrence on the Nth weekday of the month. |
| [DeletedInstanceDates](../../aspose.email.mapi/mapicalendarrecurrencepattern/deletedinstancedates/) { get; } | Gets the original dates of the occurrences that were deleted or changed. |
| [EndDate](../../aspose.email.mapi/mapicalendarrecurrencepattern/enddate/) { get; set; } | Gets or sets the date of the last occurrence, used when [`EndType`](../mapicalendarrecurrencepattern/endtype/) is `EndAfterDate`. |
| [EndType](../../aspose.email.mapi/mapicalendarrecurrencepattern/endtype/) { get; set; } | Gets or sets how the series ends. |
| [Exceptions](../../aspose.email.mapi/mapicalendarrecurrencepattern/exceptions/) { get; } | Gets the exceptions of the series: the occurrences whose details were changed. |
| override [Frequency](../../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/frequency/) { get; } | Gets how often the series repeats: `Yearly` when [`Period`](../mapicalendaryearlyandmonthlyrecurrencepattern/period/) is a multiple of 12, otherwise `Monthly`. |
| [ModifiedInstanceDates](../../aspose.email.mapi/mapicalendarrecurrencepattern/modifiedinstancedates/) { get; } | Gets the dates of the occurrences that were changed. |
| [OccurrenceCount](../../aspose.email.mapi/mapicalendarrecurrencepattern/occurrencecount/) { get; set; } | Gets or sets the number of occurrences, used when [`EndType`](../mapicalendarrecurrencepattern/endtype/) is `EndAfterNOccurrences`. |
| [PatternType](../../aspose.email.mapi/mapicalendarrecurrencepattern/patterntype/) { get; set; } | Gets or sets the type of the recurrence pattern. |
| override [Period](../../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/period/) { get; set; } | Gets or sets the interval of the recurrence, in months: 12 for a yearly recurrence. |
| [Position](../../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/position/) { get; set; } | Gets or sets which occurrence of [`DayOfWeek`](../mapicalendaryearlyandmonthlyrecurrencepattern/dayofweek/) in the month the event falls on, such as the second or the last. |
| [SlidingFlag](../../aspose.email.mapi/mapicalendarrecurrencepattern/slidingflag/) { get; set; } | Gets or sets a value indicating whether the next occurrence is calculated from the completion of the previous one rather than from a fixed schedule. Used by recurring tasks. |
| [StartDate](../../aspose.email.mapi/mapicalendarrecurrencepattern/startdate/) { get; set; } | Gets or sets the date of the first occurrence. |
| [WeekStartDay](../../aspose.email.mapi/mapicalendarrecurrencepattern/weekstartday/) { get; set; } | Gets or sets the first day of the week. |

## Remarks

Set the day with [`Day`](../mapicalendaryearlyandmonthlyrecurrencepattern/day/) and the interval in months with [`Period`](../mapicalendaryearlyandmonthlyrecurrencepattern/period/).

### See Also

* class [MapiCalendarYearlyAndMonthlyRecurrencePattern](../mapicalendaryearlyandmonthlyrecurrencepattern/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


