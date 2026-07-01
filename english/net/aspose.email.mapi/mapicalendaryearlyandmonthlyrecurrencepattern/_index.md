---
title: Class MapiCalendarYearlyAndMonthlyRecurrencePattern
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarYearlyAndMonthlyRecurrencePattern class. Represents the base class for yearly and monthly recurrence patterns in MAPI calendar items. This abstract class provides common properties and functionality for patterns that can recur either monthly on a specific day or yearly on a specific day of a specific month
type: docs
weight: 16980
url: /net/aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/
---
## MapiCalendarYearlyAndMonthlyRecurrencePattern class

Represents the base class for yearly and monthly recurrence patterns in MAPI calendar items. This abstract class provides common properties and functionality for patterns that can recur either monthly (on a specific day) or yearly (on a specific day of a specific month).

```csharp
public class MapiCalendarYearlyAndMonthlyRecurrencePattern : MapiCalendarRecurrencePattern
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendarYearlyAndMonthlyRecurrencePattern](mapicalendaryearlyandmonthlyrecurrencepattern/)() | Initializes a new instance of the `MapiCalendarYearlyAndMonthlyRecurrencePattern` class |

## Properties

| Name | Description |
| --- | --- |
| [CalendarType](../../aspose.email.mapi/mapicalendarrecurrencepattern/calendartype/) { get; set; } | Gets or sets the type of calendar that is used |
| [Day](../../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/day/) { get; set; } | Gets or sets day of the month on which the recurrence falls. |
| [DayOfWeek](../../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/dayofweek/) { get; set; } | Gets or sets the days of week at which the event occurs |
| [DeletedInstanceDates](../../aspose.email.mapi/mapicalendarrecurrencepattern/deletedinstancedates/) { get; } | An array of dates, each of which is the original instance date of either a deleted instance or a modified instance for this recurrence. |
| [EndDate](../../aspose.email.mapi/mapicalendarrecurrencepattern/enddate/) { get; set; } | Gets or sets Defines the end date of an item recurrence pattern. |
| [EndType](../../aspose.email.mapi/mapicalendarrecurrencepattern/endtype/) { get; set; } | Gets or sets the ending type for the recurrence. |
| [Exceptions](../../aspose.email.mapi/mapicalendarrecurrencepattern/exceptions/) { get; } | An exception specifies changes to an instance of a recurring series. |
| override [Frequency](../../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/frequency/) { get; } | Gets or sets the frequency of the recurring series. |
| [ModifiedInstanceDates](../../aspose.email.mapi/mapicalendarrecurrencepattern/modifiedinstancedates/) { get; } | An array of dates, each of which is the date of a modified instance. |
| [OccurrenceCount](../../aspose.email.mapi/mapicalendarrecurrencepattern/occurrencecount/) { get; set; } | Gets or sets the number of occurrences in a recurrence. |
| [PatternType](../../aspose.email.mapi/mapicalendarrecurrencepattern/patterntype/) { get; set; } | Gets or sets the type of recurrence pattern |
| override [Period](../../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/period/) { get; set; } | Gets or sets interval (in months) at which the meeting pattern repeats |
| [Position](../../aspose.email.mapi/mapicalendaryearlyandmonthlyrecurrencepattern/position/) { get; set; } | Gets or sets the occurrence of the recurrence's days in each month in which the recurrence falls. |
| [SlidingFlag](../../aspose.email.mapi/mapicalendarrecurrencepattern/slidingflag/) { get; set; } | Defines whether pattern is sliding or not. |
| [StartDate](../../aspose.email.mapi/mapicalendarrecurrencepattern/startdate/) { get; set; } | Gets or sets the start date of an item recurrence pattern. |
| [WeekStartDay](../../aspose.email.mapi/mapicalendarrecurrencepattern/weekstartday/) { get; set; } | Gets or sets the first day of the calendar week. |

## Remarks

This class is designed to be inherited by concrete pattern implementations such as [`MapiCalendarMonthlyRecurrencePattern`](../mapicalendarmonthlyrecurrencepattern/) and !:MapiCalendarYearlyRecurrencePattern. Do not instantiate this class directly. Use the concrete pattern classes to define specific recurrence behaviors. The [`Period`](./period/) property determines whether the pattern is monthly or yearly based on whether it's divisible by 12. The [`Day`](./day/) property specifies the day of the month, and [`DayOfWeek`](./dayofweek/) with [`Position`](./position/) define weekly occurrences within a month.

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


