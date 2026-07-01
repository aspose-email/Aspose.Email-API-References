---
title: Class MapiCalendarAttendees
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarAttendees class. Represents the attendees and related properties for a MAPI calendar item meeting request appointment. This class manages recipient information for calendar events including required and optional attendees unsendable recipients and meetingspecific options like proposal restrictions
type: docs
weight: 16710
url: /net/aspose.email.mapi/mapicalendarattendees/
---
## MapiCalendarAttendees class

Represents the attendees and related properties for a MAPI calendar item (meeting request, appointment). This class manages recipient information for calendar events, including required and optional attendees, unsendable recipients, and meeting-specific options like proposal restrictions.

```csharp
public sealed class MapiCalendarAttendees
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendarAttendees](mapicalendarattendees/)() | Initializes a new instance of the `MapiCalendarAttendees` class |

## Properties

| Name | Description |
| --- | --- |
| [AppointmentRecipients](../../aspose.email.mapi/mapicalendarattendees/appointmentrecipients/) { get; set; } | Gets or sets a list of attendees. |
| [AppointmentUnsendableRecipients](../../aspose.email.mapi/mapicalendarattendees/appointmentunsendablerecipients/) { get; set; } | Gets or sets a list of unsendable attendees. |
| [NotAllowPropose](../../aspose.email.mapi/mapicalendarattendees/notallowpropose/) { get; set; } | Gets or sets a value indicating whether attendees are not allowed to propose a new date and/or time for the meeting. |
| [ResponseRequested](../../aspose.email.mapi/mapicalendarattendees/responserequested/) { get; set; } | Gets or sets a value indicating whether a response is requested to a Message object. |

## Remarks

This class is used with [`MapiCalendar`](../mapicalendar/) to manage meeting attendees and their properties. The [`AppointmentRecipients`](./appointmentrecipients/) collection contains the main attendees, while [`AppointmentUnsendableRecipients`](./appointmentunsendablerecipients/) contains recipients that cannot be sent to directly. The !:AppointmentNotAllowPropose property controls whether attendees can propose new meeting times, and [`ResponseRequested`](./responserequested/) indicates if a response is expected.

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


