---
title: "Aspose::Email::Mapi::MapiCalendarRecurrencePatternFactory::ToByteArray method"
linktitle: "ToByteArray"
articleTitle: "ToByteArray"
second_title: "Aspose.Email for C++"
description: "Parses the MapiCalendarRecurrencePattern from the calendar recurrence."
type: docs
weight: 40
url: /cpp/aspose.email.mapi/mapicalendarrecurrencepatternfactory/tobytearray/
---

## ToByteArray {#tobytearray}

Parses the MapiCalendarRecurrencePattern from the calendar recurrence.

**Returns:** A parsed MapiCalendarRecurrencePattern

```cpp
ToByteArray(System::SharedPtr < MapiCalendarRecurrencePattern > recurrencePattern, System::DateTime startDate, System::DateTime endDate, System::DateTime startWhole, System::DateTime endWhole, System::DateTime clipStart, System::DateTime clipEnd, System::SharedPtr < MapiCalendarTimeZone > localTimeZone, bool isAllDay)
```

| Parameter | Description |
| --- | --- |
| recurrencePattern | The recurrence pattern. |
| startDate | The start date. |
| endDate | The end date. |
| startWhole | PidLidAppointmentStartWhole( https://docs.microsoft.com/en-us/office/client-developer/outlook/mapi/pidlidappointmentstartwhole-canonical-property ) For a recurring series, this property is the start date and time of the first instance according to the recurrence pattern. |
| endWhole | PidLidAppointmentEndWhole( https://docs.microsoft.com/en-us/office/client-developer/outlook/mapi/pidlidappointmentendwhole-canonical-property ) For a recurring series, the dispidApptEndWhole property is the end date and time of the first instance according to the recurrence pattern. |
| clipStart | PidLidClipStart( https://docs.microsoft.com/en-us/office/client-developer/outlook/mapi/pidlidclipstart-canonical-property ) Specifies midnight on the date of the first instance in UTC for a recurring series. |
| clipEnd | PidLidClipEnd( https://docs.microsoft.com/en-us/office/client-developer/outlook/mapi/pidlidclipend-canonical-property ) For a recurring series, this property specifies midnight on the date of the last instance of the recurring series in UTC, unless the recurring series has no end, in which case the value must be 31 August 4500, 11:59 p.m. |
| localTimeZone | The local TimeZone. |
| isAllDay | The AllDay property. |

