---
title: Class MapiCalendarRecurrencePatternFactory
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarRecurrencePatternFactory class. Creates recurrence patterns from iCalendar recurrence rules
type: docs
weight: 16880
url: /net/aspose.email.mapi/mapicalendarrecurrencepatternfactory/
---
## MapiCalendarRecurrencePatternFactory class

Creates recurrence patterns from iCalendar recurrence rules.

```csharp
public static class MapiCalendarRecurrencePatternFactory
```

## Methods

| Name | Description |
| --- | --- |
| static [FromString](../../aspose.email.mapi/mapicalendarrecurrencepatternfactory/fromstring/)(string) | Creates a recurrence pattern from an iCalendar recurrence rule. |

## Examples

This example creates a weekly meeting that occurs on Mondays and Wednesdays, ten times.

[C#]

```csharp
var start = new DateTime(2026, 11, 2, 10, 0, 0, DateTimeKind.Utc);
var meeting = new MapiCalendar("Room 1", "Team sync", "Weekly sync-up", start, start.AddHours(1));

string rule = "DTSTART:" + start.ToString("yyyyMMddTHHmmssZ") + "\r\n" +
              "RRULE:FREQ=WEEKLY;BYDAY=MO,WE;COUNT=10";
meeting.Recurrence = new MapiCalendarEventRecurrence
{
    RecurrencePattern = MapiCalendarRecurrencePatternFactory.FromString(rule)
};

meeting.Save("meeting.msg", AppointmentSaveFormat.Msg);
```

[Visual Basic]

```csharp
Dim start = New DateTime(2026, 11, 2, 10, 0, 0, DateTimeKind.Utc)
Dim meeting = New MapiCalendar("Room 1", "Team sync", "Weekly sync-up", start, start.AddHours(1))

Dim rule As String = "DTSTART:" & start.ToString("yyyyMMddTHHmmssZ") & vbCrLf &
                     "RRULE:FREQ=WEEKLY;BYDAY=MO,WE;COUNT=10"
meeting.Recurrence = New MapiCalendarEventRecurrence With {
    .RecurrencePattern = MapiCalendarRecurrencePatternFactory.FromString(rule)
}

meeting.Save("meeting.msg", AppointmentSaveFormat.Msg)
```

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


