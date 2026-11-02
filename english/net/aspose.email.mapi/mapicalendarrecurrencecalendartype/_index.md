---
title: Enum MapiCalendarRecurrenceCalendarType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarRecurrenceCalendarType enum. Defines the calendar system a recurrence is calculated in
type: docs
weight: 16840
url: /net/aspose.email.mapi/mapicalendarrecurrencecalendartype/
---
## MapiCalendarRecurrenceCalendarType enumeration

Defines the calendar system a recurrence is calculated in.

```csharp
public enum MapiCalendarRecurrenceCalendarType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | `0` | The Gregorian calendar; the Hijri calendar if the pattern type is `HjMonth`, `HjMonthNth` or `HjMonthEnd`. |
| CAL_GREGORIAN | `1` | The localized Gregorian calendar. |
| CAL_GREGORIAN_US | `2` | The U.S. Gregorian calendar. |
| CAL_JAPAN | `3` | The Japanese Emperor Era calendar. |
| CAL_TAIWAN | `4` | The Taiwan calendar. |
| CAL_KOREA | `5` | The Korean Tangun Era calendar. |
| CAL_HIJRI | `6` | The Hijri (Arabic lunar) calendar. |
| CAL_THAI | `7` | The Thai calendar. |
| CAL_HEBREW | `8` | The Hebrew lunar calendar. |
| CAL_GREGORIAN_ME_FRENCH | `9` | The Gregorian Middle East French calendar. |
| CAL_GREGORIAN_ARABIC | `10` | The Gregorian Arabic calendar. |
| CAL_GREGORIAN_XLIT_ENGLISH | `11` | The Gregorian transliterated English calendar. |
| CAL_GREGORIAN_XLIT_FRENCH | `12` | The Gregorian transliterated French calendar. |
| CAL_LUNAR_JAPANESE | `14` | The Japanese lunar calendar. |
| CAL_CHINESE_LUNAR | `15` | The Chinese lunar calendar. |
| CAL_SAKA | `16` | The Saka Era calendar. |
| CAL_LUNAR_ETO_CHN | `17` | The Chinese lunar ETO calendar. |
| CAL_LUNAR_ETO_KOR | `18` | The Korean lunar ETO calendar. |
| CAL_LUNAR_ROKUYOU | `19` | The Rokuyou lunar calendar. |
| CAL_LUNAR_KOREAN | `20` | The Korean lunar calendar. |
| CAL_UMALQURA | `23` | The Um Al Qura calendar. |

## Remarks

`Default` means the Gregorian calendar, except for the Hijri pattern types of [`MapiCalendarRecurrencePatternType`](../mapicalendarrecurrencepatterntype/), which use the Hijri calendar.

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


