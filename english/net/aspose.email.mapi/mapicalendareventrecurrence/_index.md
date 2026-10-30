---
title: Class MapiCalendarEventRecurrence
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarEventRecurrence class. The recurrence of a calendar event the pattern the time zone and the range of the series
type: docs
weight: 16770
url: /net/aspose.email.mapi/mapicalendareventrecurrence/
---
## MapiCalendarEventRecurrence class

The recurrence of a calendar event: the pattern, the time zone and the range of the series.

```csharp
public sealed class MapiCalendarEventRecurrence
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendarEventRecurrence](mapicalendareventrecurrence/)() | Initializes a new instance of the `MapiCalendarEventRecurrence` class. |

## Properties

| Name | Description |
| --- | --- |
| [AppointmentTimeZoneDefinitionRecur](../../aspose.email.mapi/mapicalendareventrecurrence/appointmenttimezonedefinitionrecur/) { get; set; } | Gets or sets the time zone used to convert the times of the recurring series to and from UTC. |
| [ClipEnd](../../aspose.email.mapi/mapicalendareventrecurrence/clipend/) { get; set; } | Gets or sets the date of the last occurrence. |
| [ClipStart](../../aspose.email.mapi/mapicalendareventrecurrence/clipstart/) { get; set; } | Gets or sets the date of the first occurrence. |
| [IsException](../../aspose.email.mapi/mapicalendareventrecurrence/isexception/) { get; set; } | Gets or sets a value indicating whether the object is an exception: a changed occurrence of a series. |
| [RecurrencePattern](../../aspose.email.mapi/mapicalendareventrecurrence/recurrencepattern/) { get; set; } | Gets or sets the recurrence pattern. |
| [TimeZoneStruct](../../aspose.email.mapi/mapicalendareventrecurrence/timezonestruct/) { get; set; } | Gets or sets the time zone of the recurring meeting. |

## Remarks

Assign an instance to [`Recurrence`](../mapicalendar/recurrence/). [`RecurrencePattern`](./recurrencepattern/) defines how the event repeats; create it with one of the pattern classes or with [`MapiCalendarRecurrencePatternFactory`](../mapicalendarrecurrencepatternfactory/).

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


