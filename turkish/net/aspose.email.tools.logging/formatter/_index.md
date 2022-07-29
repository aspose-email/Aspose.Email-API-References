---
title: Formatter
second_title: Aspose.Email for .NET API Referansı
description: Günlük girişi iletilerinin biçimlendirilmesi için arabirimi temsil eder.
type: docs
weight: 20490
url: /tr/net/aspose.email.tools.logging/formatter/
---
## Formatter class

Günlük girişi iletilerinin biçimlendirilmesi için arabirimi temsil eder.

```csharp
public abstract class Formatter : IFormatter
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [Footer](../../aspose.email.tools.logging/formatter/footer) { get; } | Altbilgiyi alır veya ayarlar. |
| virtual [Header](../../aspose.email.tools.logging/formatter/header) { get; } | Başlığı alır veya ayarlar. |
| virtual [LogHeader](../../aspose.email.tools.logging/formatter/logheader) { get; } | Günlük başlığını alır veya ayarlar |
| static [DefaultFormatter](../../aspose.email.tools.logging/formatter/defaultformatter) { get; set; } | Varsayılan biçimlendiriciyi alır veya ayarlar |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Format](../../aspose.email.tools.logging/formatter/format#format_1)(DateTime) | Bir tarih saatini biçimlendirir ve çıktısı alınacak bir dize döndürür. |
| virtual [Format](../../aspose.email.tools.logging/formatter/format#format)(LogEntry) | Günlük girişini biçimlendirir ve çıktısı alınacak bir dize döndürür. |

### Ayrıca bakınız

* interface [IFormatter](../iformatter)
* ad alanı [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->