---
title: Enum MapiCalendarRecurrencePatternType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarRecurrencePatternType enum. Defines the type of a recurrence pattern
type: docs
weight: 16890
url: /net/aspose.email.mapi/mapicalendarrecurrencepatterntype/
---
## MapiCalendarRecurrencePatternType enumeration

Defines the type of a recurrence pattern.

```csharp
public enum MapiCalendarRecurrencePatternType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Day | `0` | The event has a daily recurrence. |
| Week | `1` | The event has a weekly recurrence. |
| Month | `2` | The event has a monthly recurrence. |
| MonthEnd | `4` | The event occurs on the last day of the month. |
| MonthNth | `3` | The event occurs on the Nth weekday of the month. |
| HjMonth | `10` | The event has a monthly recurrence in the Hijri calendar. |
| HjMonthNth | `11` | The event occurs on the Nth weekday of the month in the Hijri calendar. |
| HjMonthEnd | `12` | The event occurs on the last day of the month in the Hijri calendar. |

## Remarks

This enumeration defines the various recurrence pattern types supported by MAPI calendar items, including daily, weekly, monthly, and yearly patterns. Some patterns support both Gregorian and Hijri calendar systems (e.g., HjMonth for Hijri monthly recurrence). The pattern type determines which properties are meaningful in the corresponding [`MapiCalendarRecurrencePattern`](../mapicalendarrecurrencepattern/) implementation.

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


