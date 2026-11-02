---
title: Class MapiCalendarYearlyAndMonthlyRecurrencePattern
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarYearlyAndMonthlyRecurrencePattern class. A recurrence every N months on a given day of the month or on the Nth weekday of the month. A period that is a multiple of 12 makes it a yearly recurrence
type: docs
weight: 16980
url: /net/aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/
---
## MapiCalendarYearlyAndMonthlyRecurrencePattern class

A recurrence every N months: on a given day of the month or on the Nth weekday of the month. A period that is a multiple of 12 makes it a yearly recurrence.

```csharp
public class MapiCalendarYearlyAndMonthlyRecurrencePattern : MapiCalendarRecurrencePattern
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendarYearlyAndMonthlyRecurrencePattern](mapicalendaryearlyandmonthlyrecurrencepattern/)() | Initializes a new instance of the `MapiCalendarYearlyAndMonthlyRecurrencePattern` class. |

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
| override [Frequency](../../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/frequency/) { get; } | Gets how often the series repeats: `Yearly` when [`Period`](./period/) is a multiple of 12, otherwise `Monthly`. |
| [ModifiedInstanceDates](../../aspose.email.mapi/mapicalendarrecurrencepattern/modifiedinstancedates/) { get; } | Gets the dates of the occurrences that were changed. |
| [OccurrenceCount](../../aspose.email.mapi/mapicalendarrecurrencepattern/occurrencecount/) { get; set; } | Gets or sets the number of occurrences, used when [`EndType`](../mapicalendarrecurrencepattern/endtype/) is `EndAfterNOccurrences`. |
| [PatternType](../../aspose.email.mapi/mapicalendarrecurrencepattern/patterntype/) { get; set; } | Gets or sets the type of the recurrence pattern. |
| override [Period](../../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/period/) { get; set; } | Gets or sets the interval of the recurrence, in months: 12 for a yearly recurrence. |
| [Position](../../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/position/) { get; set; } | Gets or sets which occurrence of [`DayOfWeek`](./dayofweek/) in the month the event falls on, such as the second or the last. |
| [SlidingFlag](../../aspose.email.mapi/mapicalendarrecurrencepattern/slidingflag/) { get; set; } | Gets or sets a value indicating whether the next occurrence is calculated from the completion of the previous one rather than from a fixed schedule. Used by recurring tasks. |
| [StartDate](../../aspose.email.mapi/mapicalendarrecurrencepattern/startdate/) { get; set; } | Gets or sets the date of the first occurrence. |
| [WeekStartDay](../../aspose.email.mapi/mapicalendarrecurrencepattern/weekstartday/) { get; set; } | Gets or sets the first day of the week. |

## Remarks

Set the interval in months with [`Period`](./period/): 1 for every month, 12 for every year. For a fixed day of the month set [`Day`](./day/); for, say, the last Friday set [`DayOfWeek`](./dayofweek/) and [`Position`](./position/). [`MapiCalendarMonthlyRecurrencePattern`](../mapicalendarmonthlyrecurrencepattern/) and [`MapiCalendarMonthlyNthRecurrencePattern`](../mapicalendarmonthlynthrecurrencepattern/) are specialized forms of this class.

## Examples

The following example shows how to create a yearly recurrence pattern for a MAPI calendar item.

[C#]

```csharp
// Create a MapiCalendar
var calendar = new MapiCalendar(
    "Team Meeting",
    DateTime.Now,
    DateTime.Now.AddHours(2),
    " organizer@company.com",
    "attendee@company.com");

// Create a yearly recurrence pattern (repeats every year on January 15th)
var yearlyPattern = new MapiCalendarYearlyAndMonthlyRecurrencePattern()
{
    Period = 12,  // 12 months = 1 year
    Day = 15,     // 15th day of the month
    StartDate = DateTime.Now,
    EndDate = DateTime.Now.AddYears(5),
    Frequency = MapiCalendarRecurrenceFrequency.Yearly,
    PatternType = MapiCalendarRecurrencePatternType.Month,
    CalendarType = MapiCalendarRecurrenceCalendarType.CAL_GREGORIAN_US
};

// Set the recurrence pattern
calendar.Recurrence = new MapiCalendarEventRecurrence()
{
    RecurrencePattern = yearlyPattern
};

// Save the calendar item
calendar.Save("yearly_meeting.msg", SaveOptions.DefaultMsgUnicode);
```

[Visual Basic]

```csharp
' Create a MapiCalendar
Dim calendar As New MapiCalendar(
    "Team Meeting",
    DateTime.Now,
    DateTime.Now.AddHours(2),
    "organizer@company.com",
    "attendee@company.com")

' Create a yearly recurrence pattern (repeats every year on January 15th)
Dim yearlyPattern As New MapiCalendarYearlyAndMonthlyRecurrencePattern() With {
    .Period = 12,  ' 12 months = 1 year
    .Day = 15,     ' 15th day of the month
    .StartDate = DateTime.Now,
    .EndDate = DateTime.Now.AddYears(5),
    .Frequency = MapiCalendarRecurrenceFrequency.Yearly,
    .PatternType = MapiCalendarRecurrencePatternType.Month,
    .CalendarType = MapiCalendarRecurrenceCalendarType.CAL_GREGORIAN_US
}

' Set the recurrence pattern
calendar.Recurrence = New MapiCalendarEventRecurrence() With {
    .RecurrencePattern = yearlyPattern
}

' Save the calendar item
calendar.Save("yearly_meeting.msg", SaveOptions.DefaultMsgUnicode)
```

### See Also

* class [MapiCalendarRecurrencePattern](../mapicalendarrecurrencepattern/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


