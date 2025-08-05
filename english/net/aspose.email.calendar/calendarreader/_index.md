---
title: Class CalendarReader
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.CalendarReader class. Allows read the calendar with multi events to the Appointment object from a file or stream
type: docs
weight: 570
url: /net/aspose.email.calendar/calendarreader/
---
## CalendarReader class

Allows read the calendar with multi events to the Appointment object from a file or stream.

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

### See Also

* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


