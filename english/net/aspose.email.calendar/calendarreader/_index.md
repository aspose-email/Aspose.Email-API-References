---
title: Class CalendarReader
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.CalendarReader class. Reads the events of an iCalendar ICS file or stream one by one
type: docs
weight: 570
url: /net/aspose.email.calendar/calendarreader/
---
## CalendarReader class

Reads the events of an iCalendar (ICS) file or stream one by one.

```csharp
public class CalendarReader
```

## Constructors

| Name | Description |
| --- | --- |
| [CalendarReader](calendarreader/#constructor)(Stream) | Initializes a new instance of the `CalendarReader` class that reads the specified stream with the default options. |
| [CalendarReader](calendarreader/#constructor_2)(string) | Initializes a new instance of the `CalendarReader` class that reads the specified file with the default options. |
| [CalendarReader](calendarreader/#constructor_1)(Stream, AppointmentLoadOptions) | Initializes a new instance of the `CalendarReader` class that reads the specified stream with the specified options. |
| [CalendarReader](calendarreader/#constructor_3)(string, AppointmentLoadOptions) | Initializes a new instance of the `CalendarReader` class that reads the specified file with the specified options. |

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.email.calendar/calendarreader/count/) { get; } | Gets the number of events (VEVENT components) in the calendar. |
| [Current](../../aspose.email.calendar/calendarreader/current/) { get; } | Gets the event read by the last call to `NextEvent`, or `null` before the first call. |
| [IsMultiEvents](../../aspose.email.calendar/calendarreader/ismultievents/) { get; } | Gets a value indicating whether the calendar contains more than one event. |
| [Method](../../aspose.email.calendar/calendarreader/method/) { get; } | Gets the iCalendar METHOD of the calendar. |
| [Version](../../aspose.email.calendar/calendarreader/version/) { get; } | Gets the version of the calendar: 2.0 for iCalendar, 1.0 for vCalendar. |

## Methods

| Name | Description |
| --- | --- |
| [LoadAsMultiple](../../aspose.email.calendar/calendarreader/loadasmultiple/)() | Reads all events of the calendar. |
| [NextEvent](../../aspose.email.calendar/calendarreader/nextevent/)() | Reads the next event and makes it available in `Current`. |

## Remarks

The calendar is parsed when the reader is created. Call `NextEvent` until it returns `false` and take each event from `Current`, or call `LoadAsMultiple` to get all events at once. Only events (VEVENT components) are read.

## Examples

This example demonstrates how to read multiple events from an ICS file and store them in a list of [`Appointment`](../appointment/) objects.

[C#]

```csharp
// Create a list to hold the appointments
var appointments = new List<Appointment>();

// Initialize CalendarReader with the ICS file path
var reader = new CalendarReader("US-Holidays.ics");

// Iterate through the events in the ICS file
while (reader.NextEvent())
{
    // Add the current event to the appointments list
    appointments.Add(reader.Current);
}

// Working with the appointments...
```

[Visual Basic]

```csharp
' Create a list to hold the appointments
Dim appointments As New List(Of Appointment)

' Initialize CalendarReader with the ICS file path
Dim reader As New CalendarReader("US-Holidays.ics")

' Iterate through the events in the ICS file
While reader.NextEvent()
    ' Add the current event to the appointments list
    appointments.Add(reader.Current)
End While

' Working with the appointments...
```

### See Also

* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


