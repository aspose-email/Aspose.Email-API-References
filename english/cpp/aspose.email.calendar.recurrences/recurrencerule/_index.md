---
title: "Aspose::Email::Calendar::Recurrences::RecurrenceRule class"
linktitle: "RecurrenceRule"
articleTitle: "RecurrenceRule"
second_title: "Aspose.Email for C++"
description: "Represents one recurrence or exception rule in a recurrence pattern."
type: docs
weight: 10
url: /cpp/aspose.email.calendar.recurrences/recurrencerule/
---

## RecurrenceRule class

Represents one recurrence or exception rule in a recurrence pattern.

Corresponds to RRULE or EXRULE part in iCalendar.

To construct a recurrence rule, you typically need to:

1. Specify the type of the rule in Frequency .

2. Specify how the recurrence pattern ends using EndType , Count or Until .

3. Specify values in one or more ByXXX collections.

Note, that if ByXXX rule part values are found which are beyond the available scope (ie, BYMONTHDAY=30 in February), they are simply ignored.

Information, not contained in the rule, necessary to determine the various recurrence instance start time and dates are derived from CalendarRecurrence::StartDate . For example, "FREQ=YEARLY;BYMONTH=1" doesn't specify a specific day within the month or a time. This information would be the same as what is specified for DTSTART.

ByXXX rule parts modify the recurrence in some manner. ByXXX rule parts for a period of time which is the same or greater than the frequency generally reduce or limit the number of occurrences of the recurrence generated. For example, "FREQ=DAILY;BYMONTH=1" reduces the number of recurrence instances from all days (if BYMONTH tag is not present) to all days in January. ByXXX rule parts for a period of time less than the frequency generally increase or expand the number of occurrences of the recurrence. For example, "FREQ=YEARLY;BYMONTH=1,2" increases the number of days within the yearly recurrence set from 1 (if BYMONTH tag is not present) to 2.

If multiple ByXXX rule parts are specified, then after evaluating the specified Frequency and Interval rule parts, the ByXXX rule parts are applied to the current set of evaluated occurrences in the following order: ByMonth , ByWeekNo , ByYearDay , ByMonthDay , ByDay , ByHour , ByMinute , BySecond and BySetPos ; then Count and Until are evaluated.

## Constructors

| Name | Description |
| --- | --- |
| [RecurrenceRule](./recurrencerule/) | Initializes a new instance of the RecurrenceRule class. |

## Methods

| Name | Description |
| --- | --- |
| [Equals (2 overloads)](./equals/) | Determines whether the specified RecurrenceRule is equal to this instance. |
| [FromiCalendar](./fromicalendar/) |  |
| [GenerateOccurrences](./generateoccurrences/) |  |
| [get_ByDay](./get_byday/) | Gets the by day. |
| [get_ByHour](./get_byhour/) | Gets the by hour. |
| [get_ByMinute](./get_byminute/) | Gets the by minute. |
| [get_ByMonth](./get_bymonth/) | Gets the by month. |
| [get_ByMonthDay](./get_bymonthday/) | Gets the by month day. |
| [get_BySecond](./get_bysecond/) | Gets the by second. |
| [get_BySetPos](./get_bysetpos/) | Gets the by set pos. |
| [get_ByWeekNo](./get_byweekno/) | Gets the by week no. |
| [get_ByYearDay](./get_byyearday/) | Gets the by year day. |
| [get_Count](./get_count/) | Gets the count. |
| [get_EndType](./get_endtype/) | Gets the end type. |
| [get_Frequency](./get_frequency/) | Gets the type of the recurrence rule. |
| [get_FriendlyText](./get_friendlytext/) | Gets user friendly text of rule. |
| [get_Interval](./get_interval/) | Gets the interval. |
| [get_Until](./get_until/) | Gets the until. |
| [get_WeekStart](./get_weekstart/) | Gets the starting day of the week. |
| [GetDayOfWeekString](./getdayofweekstring/) |  |
| [GetHashCode](./gethashcode/) | GetHashCode returns a hash function for this object. |
| [IsValidByxxx](./isvalidbyxxx/) | Checks date on correspondence to conditions BYxxx |
| [set_Count](./set_count/) | Sets the count. |
| [set_EndType](./set_endtype/) | Sets the end type. |
| [set_Frequency](./set_frequency/) | Sets the type of the recurrence rule. |
| [set_Interval](./set_interval/) | Sets the interval. |
| [set_Until](./set_until/) | Sets the until. |
| [set_WeekStart](./set_weekstart/) | Sets the starting day of the week. |
| [ToiCalendar](./toicalendar/) |  |

