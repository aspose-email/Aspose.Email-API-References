---
title: Class CalendarRecurrence
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.Recurrences.CalendarRecurrence class. The main class represents an iCalendar recurrence
type: docs
weight: 670
url: /net/aspose.email.calendar.recurrences/calendarrecurrence/
---
## CalendarRecurrence class

The main class, represents an iCalendar recurrence.

```csharp
public class CalendarRecurrence : IEquatable<CalendarRecurrence>
```

## Constructors

| Name | Description |
| --- | --- |
| [CalendarRecurrence](calendarrecurrence/#constructor)() | Initializes a new instance of the `CalendarRecurrence` class. |
| [CalendarRecurrence](calendarrecurrence/#constructor_1)(string) | Initializes a new instance of the `CalendarRecurrence` class. |

## Properties

| Name | Description |
| --- | --- |
| [EndDate](../../aspose.email.calendar.recurrences/calendarrecurrence/enddate/) { get; set; } | Gets or sets the end date. |
| [ExDates](../../aspose.email.calendar.recurrences/calendarrecurrence/exdates/) { get; } | Gets the ex dates. |
| [ExRules](../../aspose.email.calendar.recurrences/calendarrecurrence/exrules/) { get; } | Gets the ex rules. |
| [RDates](../../aspose.email.calendar.recurrences/calendarrecurrence/rdates/) { get; } | Gets the R dates. |
| [RRules](../../aspose.email.calendar.recurrences/calendarrecurrence/rrules/) { get; } | Gets the R rules. |
| [StartDate](../../aspose.email.calendar.recurrences/calendarrecurrence/startdate/) { get; set; } | Gets or sets the start date. |

## Methods

| Name | Description |
| --- | --- |
| static [FromiCalendar](../../aspose.email.calendar.recurrences/calendarrecurrence/fromicalendar/)(string) | Gets a recurrence pattern from iCalendar string. |
| static [FromRecurrence](../../aspose.email.calendar.recurrences/calendarrecurrence/fromrecurrence/#fromrecurrence)(string) | Gets a recurrence pattern from XML pattern string. |
| static [FromRecurrence](../../aspose.email.calendar.recurrences/calendarrecurrence/fromrecurrence/#fromrecurrence_1)(XmlElement) | Gets a recurrence pattern from XmlElement. |
| virtual [Equals](../../aspose.email.calendar.recurrences/calendarrecurrence/equals/#equals)(CalendarRecurrence) | Determines whether the specified `CalendarRecurrence` is equal to this instance. |
| override [Equals](../../aspose.email.calendar.recurrences/calendarrecurrence/equals/#equals_1)(object) | Determines whether the specified Object is equal to the current Object. |
| [GenerateOccurrences](../../aspose.email.calendar.recurrences/calendarrecurrence/generateoccurrences/#generateoccurrences)() | Generates the occurrences. |
| [GenerateOccurrences](../../aspose.email.calendar.recurrences/calendarrecurrence/generateoccurrences/#generateoccurrences_1)(int) | Generates n next occurrences. |
| [GenerateOccurrences](../../aspose.email.calendar.recurrences/calendarrecurrence/generateoccurrences/#generateoccurrences_2)(DateTime, DateTime) | Generates the occurrences. |
| [GenerateOccurrences](../../aspose.email.calendar.recurrences/calendarrecurrence/generateoccurrences/#generateoccurrences_3)(DateTime, DateTime, int) | Generates n next occurrences. |
| override [GetHashCode](../../aspose.email.calendar.recurrences/calendarrecurrence/gethashcode/)() | Returns a hash code for this instance. |
| [ToiCalendar](../../aspose.email.calendar.recurrences/calendarrecurrence/toicalendar/)() | To iCalendar string. |
| [operator ==](../../aspose.email.calendar.recurrences/calendarrecurrence/op_equality/) | Implements the operator ==. |
| [operator !=](../../aspose.email.calendar.recurrences/calendarrecurrence/op_inequality/) | Implements the operator !=. |

### See Also

* namespace [Aspose.Email.Calendar.Recurrences](../../aspose.email.calendar.recurrences/)
* assembly [Aspose.Email](../../)


