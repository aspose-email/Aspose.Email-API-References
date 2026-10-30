---
title: Class CalendarWriter
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.CalendarWriter class. Writes events to an iCalendar ICS file or stream one after another
type: docs
weight: 580
url: /net/aspose.email.calendar/calendarwriter/
---
## CalendarWriter class

Writes events to an iCalendar (ICS) file or stream, one after another.

```csharp
public class CalendarWriter : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [CalendarWriter](calendarwriter/#constructor)(Stream) | Initializes a new instance of the `CalendarWriter` class that writes to the specified stream with the default options. |
| [CalendarWriter](calendarwriter/#constructor_2)(string) | Initializes a new instance of the `CalendarWriter` class that creates the specified file with the default options. |
| [CalendarWriter](calendarwriter/#constructor_1)(Stream, AppointmentIcsSaveOptions) | Initializes a new instance of the `CalendarWriter` class that writes to the specified stream with the specified options. |
| [CalendarWriter](calendarwriter/#constructor_3)(string, AppointmentIcsSaveOptions) | Initializes a new instance of the `CalendarWriter` class that writes to the specified file with the specified options. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.email.calendar/calendarwriter/dispose/)() | Closes the underlying stream, including a stream passed to the constructor. |
| [Write](../../aspose.email.calendar/calendarwriter/write/)(Appointment) | Writes an event to the calendar. |

## Remarks

By default the writer starts a new calendar. With `AppointmentIcsSaveOptions.CreateNew` set to `false`, it adds the events to the end of an existing one. Dispose the writer when you are done; this also closes the stream.

## Examples

This example demonstrates how to generate and write multiple appointments into an ICS file.

[C#]

```csharp
using (var writer = new CalendarWriter("MultipleEvents.ics"))
{
    // Generate and write 10 appointments to the ICS file
    for (var i = 0; i < 10; i++)
    {
        var app = new Appointment(string.Empty, 
            DateTime.Now, 
            DateTime.Now, 
            "sender@domain.com", 
            "receiver@domain.com")
        {
            Description = "Appointment Example " + i,
            Summary = "Appointment: " + i
        };
        
        // Write the appointment to the ICS file
        writer.Write(app);
    }
}
```

[Visual Basic]

```csharp
Using writer As New CalendarWriter("MultipleEvents.ics")
    ' Generate and write 10 appointments to the ICS file
    For i As Integer = 0 To 9
        Dim app As New Appointment(String.Empty, DateTime.Now, DateTime.Now, "sender@domain.com", "receiver@domain.com") With {
            .Description = "Appointment Example " & i,
            .Summary = "Appointment: " & i
        }
        
        ' Write the appointment to the ICS file
        writer.Write(app)
    Next
End Using
```

### See Also

* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


