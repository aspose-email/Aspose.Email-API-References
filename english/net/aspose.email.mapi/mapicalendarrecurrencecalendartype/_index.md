---
title: Enum MapiCalendarRecurrenceCalendarType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarRecurrenceCalendarType enum. Specifies the calendar type used for MAPI calendar recurrence patterns. This enumeration supports multiple calendar systems including Gregorian Hijri Hebrew lunar and various regional calendars used around the world
type: docs
weight: 16840
url: /net/aspose.email.mapi/mapicalendarrecurrencecalendartype/
---
## MapiCalendarRecurrenceCalendarType enumeration

Specifies the calendar type used for MAPI calendar recurrence patterns. This enumeration supports multiple calendar systems including Gregorian, Hijri, Hebrew, lunar, and various regional calendars used around the world.

```csharp
public enum MapiCalendarRecurrenceCalendarType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | `0` | The default value for the calendar type is Gregorian. (If the PatternType is HjMonth, HjMonthNth, or HjMonthEnd, and the CalendarType is Default, this recurrence uses the Hijri calendar.) |
| CAL_GREGORIAN | `1` | Gregorian (localized) calendar |
| CAL_GREGORIAN_US | `2` | Gregorian (U.S.) calendar |
| CAL_JAPAN | `3` | Japanese Emperor Era calendar |
| CAL_TAIWAN | `4` | Taiwan calendar |
| CAL_KOREA | `5` | Korean Tangun Era calendar |
| CAL_HIJRI | `6` | Hijri (Arabic Lunar) calendar |
| CAL_THAI | `7` | Thai calendar |
| CAL_HEBREW | `8` | Hebrew lunar calendar |
| CAL_GREGORIAN_ME_FRENCH | `9` | Gregorian Middle East French calendar |
| CAL_GREGORIAN_ARABIC | `10` | Gregorian Arabic calendar |
| CAL_GREGORIAN_XLIT_ENGLISH | `11` | Gregorian transliterated English calendar |
| CAL_GREGORIAN_XLIT_FRENCH | `12` | Gregorian transliterated French calendar |
| CAL_LUNAR_JAPANESE | `14` | Japanese lunar calendar |
| CAL_CHINESE_LUNAR | `15` | Chinese lunar calendar |
| CAL_SAKA | `16` | Saka Era calendar |
| CAL_LUNAR_ETO_CHN | `17` | Lunar ETO Chinese calendar |
| CAL_LUNAR_ETO_KOR | `18` | Lunar ETO Korean calendar |
| CAL_LUNAR_ROKUYOU | `19` | Lunar Rokuyou calendar |
| CAL_LUNAR_KOREAN | `20` | Korean lunar calendar |
| CAL_UMALQURA | `23` | Um Al Qura calendar |

## Remarks

This enumeration defines the calendar system that should be used when calculating recurring calendar events. The Default value uses the Gregorian calendar, but can be overridden to use other calendar systems such as Hijri (Islamic), Hebrew, Chinese lunar, Japanese Emperor Era, or various other regional calendars. The calendar type is used in conjunction with [`MapiCalendarRecurrencePatternType`](../mapicalendarrecurrencepatterntype/) to determine the recurrence behavior for [`MapiCalendar`](../mapicalendar/) items.

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


