---
title: "Aspose::Email::Clients::Exchange::AppointmentQueryBuilder::SetCalendarView method"
linktitle: "SetCalendarView"
articleTitle: "SetCalendarView"
second_title: "Aspose.Email for C++"
description: "If the CalendarView is specified, the service returns a list of single calendar items and occurrences of recurring calendar items within the range specified by "
type: docs
weight: 120
url: /cpp/aspose.email.clients.exchange/appointmentquerybuilder/setcalendarview/
---

## SetCalendarView {#setcalendarview}

If the CalendarView is specified, the service returns a list of single calendar items and occurrences of recurring calendar items within the range specified by StartDate and EndDate.

**Returns:** void Aspose::Email::Clients::Exchange::

```cpp
SetCalendarView(System::DateTime startDate, System::DateTime endDate, int32_t maxEntriesReturned)
```

| Parameter | Description |
| --- | --- |
| startDate | Identifies the start of a time span queried for calendar items. |
| endDate | Identifies the end of a time span queried for calendar items. |
| maxEntriesReturned | Describes the maximum number of results. (Value <= 0 for all results) |

