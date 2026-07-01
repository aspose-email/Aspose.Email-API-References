---
title: Class CalendarReader
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.CalendarReader class. Provides functionality to read and extract events from an ICS iCalendar file
type: docs
weight: 570
url: /net/aspose.email.calendar/calendarreader/
---
## CalendarReader class

Provides functionality to read and extract events from an ICS (iCalendar) file.

```csharp
public class CalendarReader
```

## Constructors

| Name | Description |
| --- | --- |
| [CalendarReader](calendarreader/#constructor)(Stream) | Initializes a new instance of CalendarReader with source stream and default Appointment LoadOptions. |
| [CalendarReader](calendarreader/#constructor_2)(string) | Initializes a new instance of CalendarReader with source file and default Appointment LoadOptions. |
| [CalendarReader](calendarreader/#constructor_1)(Stream, AppointmentLoadOptions) | Initializes a new instance of CalendarReader with source stream and Appointment LoadOptions. |
| [CalendarReader](calendarreader/#constructor_3)(string, AppointmentLoadOptions) | Initializes a new instance of CalendarReader with source file and Appointment LoadOptions. |

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.email.calendar/calendarreader/count/) { get; } | Gets the number of Vevent components. |
| [Current](../../aspose.email.calendar/calendarreader/current/) { get; } | Current read event. |
| [IsMultiEvents](../../aspose.email.calendar/calendarreader/ismultievents/) { get; } | Gets whether calendar contains multi events. |
| [Method](../../aspose.email.calendar/calendarreader/method/) { get; } | Gets the iCalendar object method type associated with the calendar object. |
| [Version](../../aspose.email.calendar/calendarreader/version/) { get; } | Gets the Version of calendar. |

## Methods

| Name | Description |
| --- | --- |
| [LoadAsMultiple](../../aspose.email.calendar/calendarreader/loadasmultiple/)() | Loads a list of events from a calendar with multiple events. |
| [NextEvent](../../aspose.email.calendar/calendarreader/nextevent/)() | Reads next Event from source and save it to the Current. |

## Remarks

The `CalendarReader` class allows sequential reading of events from an iCalendar (.ics) file. It is designed to parse and access event details such as appointments, meetings, and other calendar items.

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


