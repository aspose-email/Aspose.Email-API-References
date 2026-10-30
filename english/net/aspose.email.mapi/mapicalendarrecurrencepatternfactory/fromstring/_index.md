---
title: MapiCalendarRecurrencePatternFactory.FromString
second_title: Aspose.Email for .NET API Reference
description: MapiCalendarRecurrencePatternFactory method. Creates a recurrence pattern from an iCalendar recurrence rule
type: docs
weight: 10
url: /net/aspose.email.mapi/mapicalendarrecurrencepatternfactory/fromstring/
---
## MapiCalendarRecurrencePatternFactory.FromString method

Creates a recurrence pattern from an iCalendar recurrence rule.

```csharp
public static MapiCalendarRecurrencePattern FromString(string pattern)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pattern | String | The rule in iCalendar format: a `DTSTART` line followed by an `RRULE` line, and optionally `EXDATE` lines, for example `DTSTART:20261102T100000Z` and `RRULE:FREQ=WEEKLY;BYDAY=MO;COUNT=10`. |

### Return Value

The pattern for the first `RRULE`, with the `EXDATE` dates added to its deleted occurrences; `null` if *pattern* is `null` or has no `RRULE`.

### See Also

* class [MapiCalendarRecurrencePattern](../../mapicalendarrecurrencepattern/)
* class [MapiCalendarRecurrencePatternFactory](../)
* namespace [Aspose.Email.Mapi](../../mapicalendarrecurrencepatternfactory/)
* assembly [Aspose.Email](../../../)


