---
title: Class MapiCalendarAttendees
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarAttendees class. The attendees of a meeting and the settings of their responses
type: docs
weight: 16710
url: /net/aspose.email.mapi/mapicalendarattendees/
---
## MapiCalendarAttendees class

The attendees of a meeting and the settings of their responses.

```csharp
public sealed class MapiCalendarAttendees
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendarAttendees](mapicalendarattendees/)() | Initializes a new instance of the `MapiCalendarAttendees` class. |

## Properties

| Name | Description |
| --- | --- |
| [AppointmentRecipients](../../aspose.email.mapi/mapicalendarattendees/appointmentrecipients/) { get; set; } | Gets or sets the attendees the meeting is sent to. |
| [AppointmentUnsendableRecipients](../../aspose.email.mapi/mapicalendarattendees/appointmentunsendablerecipients/) { get; set; } | Gets or sets the attendees the meeting cannot be sent to, such as attendees that were removed from it. |
| [NotAllowPropose](../../aspose.email.mapi/mapicalendarattendees/notallowpropose/) { get; set; } | Gets or sets a value indicating whether attendees are prevented from proposing a new time for the meeting. |
| [ResponseRequested](../../aspose.email.mapi/mapicalendarattendees/responserequested/) { get; set; } | Gets or sets a value indicating whether the organizer asks attendees to respond. |

## Remarks

Returned by [`Attendees`](../mapicalendar/attendees/). [`AppointmentRecipients`](./appointmentrecipients/) holds the attendees the meeting is sent to; [`AppointmentUnsendableRecipients`](./appointmentunsendablerecipients/) holds the attendees it cannot be sent to, such as removed attendees. [`NotAllowPropose`](./notallowpropose/) and [`ResponseRequested`](./responserequested/) control how attendees may respond.

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


