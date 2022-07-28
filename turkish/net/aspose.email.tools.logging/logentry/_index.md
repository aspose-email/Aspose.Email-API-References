---
title: LogEntry
second_title: Aspose.Email for .NET API Referansı
description: Bir günlük mesajını temsil eder. Tüm günlük mesajları için gerekli olan ortak özellikleri içerir.
type: docs
weight: 20520
url: /tr/net/aspose.email.tools.logging/logentry/
---
## LogEntry class

Bir günlük mesajını temsil eder. Tüm günlük mesajları için gerekli olan ortak özellikleri içerir.

```csharp
public class LogEntry
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [LogEntry](logentry#constructor)() | Yeni bir örneğini başlat[`LogEntry`](../logentry) sınıf. |
| [LogEntry](logentry#constructor_1)(byte[]) | Yeni bir örneğini oluşturun[`LogEntry`](../logentry) tam bir yapıcı parametreleri seti ile |
| [LogEntry](logentry#constructor_5)(string) | Yeni bir örneğini başlat[`LogEntry`](../logentry) sınıf. |
| [LogEntry](logentry#constructor_3)(byte[], Encoding) | Yeni bir örneğini oluşturun[`LogEntry`](../logentry) tam bir yapıcı parametreleri seti ile |
| [LogEntry](logentry#constructor_2)(byte[], IDictionary&lt;string, string&gt;) | Yeni bir örneğini oluşturun[`LogEntry`](../logentry) tam bir yapıcı parametreleri seti ile |
| [LogEntry](logentry#constructor_9)(string, DateTime) | Yeni bir örneğini başlat[`LogEntry`](../logentry) sınıf. |
| [LogEntry](logentry#constructor_10)(string, Exception) | Yeni bir örneğini başlat[`LogEntry`](../logentry) sınıf. |
| [LogEntry](logentry#constructor_8)(string, IDictionary&lt;string, string&gt;) | Yeni bir örneğini oluşturun[`LogEntry`](../logentry) tam bir yapıcı parametreleri seti ile |
| [LogEntry](logentry#constructor_6)(string, LogLevel) | Yeni bir örneğini başlat[`LogEntry`](../logentry) sınıf. |
| [LogEntry](logentry#constructor_4)(byte[], Encoding, IDictionary&lt;string, string&gt;) | Yeni bir örneğini oluşturun[`LogEntry`](../logentry) tam bir yapıcı parametreleri seti ile |
| [LogEntry](logentry#constructor_11)(string, Exception, LogLevel) | Yeni bir örneğini başlat[`LogEntry`](../logentry) sınıf. |
| [LogEntry](logentry#constructor_7)(string, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Yeni bir örneğini oluşturun[`LogEntry`](../logentry) tam bir yapıcı parametreleri seti ile |
| [LogEntry](logentry#constructor_12)(string, Exception, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Yeni bir örneğini oluşturun[`LogEntry`](../logentry) tam bir yapıcı parametreleri seti ile |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AppDomainName](../../aspose.email.tools.logging/logentry/appdomainname) { get; set; } | İçinde çalıştığımız AppDomain |
| [BinaryDataMessage](../../aspose.email.tools.logging/logentry/binarydatamessage) { get; set; } | Günlüğe kaydedilecek ikili ileti gövdesi. |
| [Category](../../aspose.email.tools.logging/logentry/category) { get; set; } | Günlük girişini bir veya daha fazla havuza yönlendirmek için kullanılan kategori adı. |
| [ContextualProperties](../../aspose.email.tools.logging/logentry/contextualproperties) { get; set; } | Kaydedilecek anahtar/değer çiftleri sözlüğü. |
| [ErrorMessages](../../aspose.email.tools.logging/logentry/errormessages) { get; } | İle hata mesajını alır.[`LogEntry`](../logentry) |
| [EventId](../../aspose.email.tools.logging/logentry/eventid) { get; set; } | Olay numarası veya tanımlayıcı. |
| [InnerException](../../aspose.email.tools.logging/logentry/innerexception) { get; set; } | İç istisna nesnesini alır veya ayarlar. |
| [MachineName](../../aspose.email.tools.logging/logentry/machinename) { get; set; } | Bilgisayarın adı. |
| [Message](../../aspose.email.tools.logging/logentry/message) { get; set; } | Günlüğe kaydedilecek ileti gövdesi. İleti nesnesinden ToString() yönteminden gelen değer. |
| [MessageEncoding](../../aspose.email.tools.logging/logentry/messageencoding) { get; set; } | İkili mesaj gövdesi için kodlama |
| [SequenceId](../../aspose.email.tools.logging/logentry/sequenceid) { get; } | Otomatik olarak oluşturulan ve monoton bir şekilde artan günlük olayının benzersiz tanımlayıcısı. |
| [Severity](../../aspose.email.tools.logging/logentry/severity) { get; set; } | Günlük girişi önem derecesi olarak[`Severity`](./severity) numaralandırma. (Belirtilmemiş, Bilgi, Uyarı veya Hata). |
| [ThreadName](../../aspose.email.tools.logging/logentry/threadname) { get; set; } | .NET iş parçacığının adı. |
| [TimeStamp](../../aspose.email.tools.logging/logentry/timestamp) { get; set; } | Günlük girişi mesajının tarihi ve saati. |
| [Title](../../aspose.email.tools.logging/logentry/title) { get; set; } | Günlük girişi mesajının ek açıklaması. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [AddErrorMessage](../../aspose.email.tools.logging/logentry/adderrormessage)(string) | Mesaj dizisi oluşturucunun başına bir hata veya uyarı mesajı ekleyin. Dağıtıcı tarafından sorunları kaydetmek için kullanılır. |
| [Clone](../../aspose.email.tools.logging/logentry/clone)() | Yeni bir[`LogEntry`](../logentry) bu, mevcut örneğin bir kopyasıdır. |
| override [ToString](../../aspose.email.tools.logging/logentry/tostring)() |  |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
