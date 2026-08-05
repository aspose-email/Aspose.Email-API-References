---
title: "Aspose::Email::Mapi::MapiCalendar class"
linktitle: "MapiCalendar"
articleTitle: "MapiCalendar"
second_title: "Aspose.Email for C++"
description: "Represents a MAPI calendar item."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapicalendar/
---

## MapiCalendar class

**Inherits:** Aspose::Email::Mapi::MapiMessageItemBase

Represents a MAPI calendar item.

This class serves as a wrapper for MapiMessage to simplify the process of handling calendar information from MAPI properties. It provides a more intuitive interface for accessing and manipulating calendar data within the MAPI message.

The following example demonstrates how to get a MapiCalendar object from a MapiMessage .

```csharp
var msg = MapiMessage.Load("calendar.msg");
 
// Check if the loaded message is a supported calendar type
if (msg.SupportedType == MapiItemType.Calendar)
{
 // Convert the MAPI message to a MapiCalendar object
    var mapiCalendar = (MapiCalendar)msg.ToMapiMessageItem();
 
 // Display some calendar info
    Console.WriteLine(mapiCalendar.Subject);
    Console.WriteLine(mapiCalendar.StartDate);
}
```

```vb
Dim msg = MapiMessage.Load("calendar.msg")
 
' Check if the loaded message is a supported calendar type
If msg.SupportedType = MapiItemType.Calendar Then
    ' Convert the MAPI message to a MapiCalendar object
    Dim mapiCalendar = DirectCast(msg.ToMapiMessageItem(), MapiCalendar)
 
 ' Display some calendar info
    Console.WriteLine(mapiCalendar.Subject)
    Console.WriteLine(mapiCalendar.StartDate)
End If
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendar (8 overloads)](./mapicalendar/) | Initializes a new instance of the MapiCalendar class |

## Methods

| Name | Description |
| --- | --- |
| [ConvertToMapiMessage](./converttomapimessage/) | Converts the task object to mapi message |
| [Dispose](./dispose/) | Releases all resources. |
| [get_AppointmentCounterProposal](./get_appointmentcounterproposal/) | Gets a value indicating whether a Meeting Response object is a counter proposal. |
| [get_Attachments](./get_attachments/) | Gets the attachment collection. |
| [get_Attendees](./get_attendees/) | Gets the attendees |
| [get_AuxiliaryFlags](./get_auxiliaryflags/) | Gets the auxiliary state |
| [get_BusyStatus](./get_busystatus/) | Gets the busy status |
| [get_ClientIntent](./get_clientintent/) | Gets the actions the user has taken on this Meeting object. |
| [get_EndDate](./get_enddate/) | Gets the end date and time of the event. If the date is not set, default value for DateTime is returned. |
| [get_EndDateTimeZone](./get_enddatetimezone/) | Gets time zone information that indicates the time zone of the EndDate property |
| [get_IsAllDay](./get_isallday/) | Gets a value indicating whether the event is an all-day event |
| [get_KeyWords](./get_keywords/) | Gets the categories of the calendar object |
| [get_Location](./get_location/) | Gets the location of the event |
| [get_Organizer](./get_organizer/) | Gets the organizer. |
| [get_Recurrence](./get_recurrence/) | Gets the recurrence properties |
| [get_ReminderDelta](./get_reminderdelta/) | Gets the interval, in minutes, between the time at which the reminder first becomes overdue and the start time of the Calendar object |
| [get_ReminderFileParameter](./get_reminderfileparameter/) | Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue. |
| [get_ReminderSet](./get_reminderset/) | Gets a value indicating whether a reminder is set on the object |
| [get_Sequence](./get_sequence/) | Gets the sequence number |
| [get_StartDate](./get_startdate/) | Gets the start date and time of the event. If the date is not set, default value for DateTime is returned. |
| [get_StartDateTimeZone](./get_startdatetimezone/) | Gets time zone information that indicates the time zone of the StartDate property |
| [get_State](./get_state/) | Gets the state of the calendar object |
| [get_Uid](./get_uid/) | Gets the unique identifier |
| [GetUnderlyingMessage](./getunderlyingmessage/) | Retrieves the underlying MapiMessage object. |
| [Save (6 overloads)](./save/) | Saves calendar object to the file with iCalendar format using te default save options |
| [set_AppointmentCounterProposal](./set_appointmentcounterproposal/) | Sets a value indicating whether a Meeting Response object is a counter proposal. |
| [set_Attendees](./set_attendees/) | Sets the attendees |
| [set_AuxiliaryFlags](./set_auxiliaryflags/) | Sets the auxiliary state |
| [set_BusyStatus](./set_busystatus/) | Sets the busy status |
| [set_ClientIntent](./set_clientintent/) | Sets the actions the user has taken on this Meeting object. |
| [set_EndDate](./set_enddate/) | Sets the end date and time of the event. If the date is not set, default value for DateTime is returned. |
| [set_EndDateTimeZone](./set_enddatetimezone/) | Sets time zone information that indicates the time zone of the EndDate property |
| [set_IsAllDay](./set_isallday/) | Sets a value indicating whether the event is an all-day event |
| [set_KeyWords](./set_keywords/) | Sets the categories of the calendar object |
| [set_Location](./set_location/) | Sets the location of the event |
| [set_Organizer](./set_organizer/) | Sets the organizer. |
| [set_Recurrence](./set_recurrence/) | Sets the recurrence properties |
| [set_ReminderDelta](./set_reminderdelta/) | Sets the interval, in minutes, between the time at which the reminder first becomes overdue and the start time of the Calendar object |
| [set_ReminderFileParameter](./set_reminderfileparameter/) | Specifies the full path of the sound that a client SHOULD play when the reminder becomes overdue. |
| [set_ReminderSet](./set_reminderset/) | Sets a value indicating whether a reminder is set on the object |
| [set_Sequence](./set_sequence/) | Sets the sequence number |
| [set_StartDate](./set_startdate/) | Sets the start date and time of the event. If the date is not set, default value for DateTime is returned. |
| [set_StartDateTimeZone](./set_startdatetimezone/) | Sets time zone information that indicates the time zone of the StartDate property |
| [set_State](./set_state/) | Sets the state of the calendar object |
| [set_Uid](./set_uid/) | Gets the unique identifier |
| [SetStateForced](./setstateforced/) | Sets the state of the calendar object, overriding any default behavior. |
| [ToIcalendar](./toicalendar/) | Converts this MapiCalendar into CalendarObject |

