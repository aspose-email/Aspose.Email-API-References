---
title: Formatter
second_title: Aspose.Email för .NET API-referens
description: Representerar gränssnittet för formatering av loggpostmeddelanden.
type: docs
weight: 20490
url: /sv/net/aspose.email.tools.logging/formatter/
---
## Formatter class

Representerar gränssnittet för formatering av loggpostmeddelanden.

```csharp
public abstract class Formatter : IFormatter
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [Footer](../../aspose.email.tools.logging/formatter/footer) { get; } | Hämtar eller ställer in sidfoten. |
| virtual [Header](../../aspose.email.tools.logging/formatter/header) { get; } | Hämtar eller ställer in rubriken. |
| virtual [LogHeader](../../aspose.email.tools.logging/formatter/logheader) { get; } | Hämtar eller ställer in logghuvudet |
| static [DefaultFormatter](../../aspose.email.tools.logging/formatter/defaultformatter) { get; set; } | Hämtar eller ställer in standardformateraren |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Format](../../aspose.email.tools.logging/formatter/format#format_1)(DateTime) | Formaterar en datumtid och returnerar en sträng som ska matas ut. |
| virtual [Format](../../aspose.email.tools.logging/formatter/format#format)(LogEntry) | Formaterar en loggpost och returnerar en sträng som ska matas ut. |

### Se även

* interface [IFormatter](../iformatter)
* namnutrymme [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->