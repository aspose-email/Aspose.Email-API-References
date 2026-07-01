---
title: Class MapiCalendarEventRecurrence
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarEventRecurrence class. Represents the recurrence properties of a calendar object including the recurrence pattern time zone information and the date range of recurrence. This class encapsulates all the data needed to define how recurring calendar events repeat over time
type: docs
weight: 16770
url: /net/aspose.email.mapi/mapicalendareventrecurrence/
---
## MapiCalendarEventRecurrence class

Represents the recurrence properties of a calendar object, including the recurrence pattern, time zone information, and the date range of recurrence. This class encapsulates all the data needed to define how recurring calendar events repeat over time.

```csharp
public sealed class MapiCalendarEventRecurrence
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendarEventRecurrence](mapicalendareventrecurrence/)() | Initializes a new instance of the `MapiCalendarEventRecurrence` class |

## Properties

| Name | Description |
| --- | --- |
| [AppointmentTimeZoneDefinitionRecur](../../aspose.email.mapi/mapicalendareventrecurrence/appointmenttimezonedefinitionrecur/) { get; set; } | Gets or sets time zone information that describes how to convert the meeting date and time on a recurring series to and from UTC. |
| [ClipEnd](../../aspose.email.mapi/mapicalendareventrecurrence/clipend/) { get; set; } | Gets or sets the date of the last instance |
| [ClipStart](../../aspose.email.mapi/mapicalendareventrecurrence/clipstart/) { get; set; } | Gets or sets the date of the first instance |
| [IsException](../../aspose.email.mapi/mapicalendareventrecurrence/isexception/) { get; set; } | Gets or sets a value indicating whether the object represents an exception |
| [RecurrencePattern](../../aspose.email.mapi/mapicalendareventrecurrence/recurrencepattern/) { get; set; } | Gets or sets the recurrence pattern |
| [TimeZoneStruct](../../aspose.email.mapi/mapicalendareventrecurrence/timezonestruct/) { get; set; } | Gets or sets the time zone information for a recurring meeting. |

## Remarks

This class is used with [`MapiCalendar`](../mapicalendar/) to manage recurring meeting patterns. The [`RecurrencePattern`](./recurrencepattern/) property defines the type and frequency of recurrence (daily, weekly, monthly, or yearly). The [`ClipStart`](./clipstart/) and [`ClipEnd`](./clipend/) properties specify the date range for the recurrence, and the time zone properties ensure proper time conversion across different time zones. Exception meetings have a different recurrence structure than the main series.

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


