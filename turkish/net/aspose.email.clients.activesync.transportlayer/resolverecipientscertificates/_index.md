---
title: ResolveRecipientsCertificates
second_title: Aspose.Email for .NET API Referansı
description: Bir alıcının sertifikaları hakkında bilgi içerir.
type: docs
weight: 1840
url: /tr/net/aspose.email.clients.activesync.transportlayer/resolverecipientscertificates/
---
## ResolveRecipientsCertificates class

Bir alıcının sertifikaları hakkında bilgi içerir.

```csharp
public class ResolveRecipientsCertificates
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ResolveRecipientsCertificates](resolverecipientscertificates)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CertificateCount](../../aspose.email.clients.activesync.transportlayer/resolverecipientscertificates/certificatecount) { get; set; } | Alıcı için bulunan geçerli sertifikaların sayısını belirtir. Sertifikalarla birlikte 8 Durum değeri döndürülürse, CertificateCount döndürülmeyen alıcı sertifikalarının sayısını belirtir. |
| [Certificates](../../aspose.email.clients.activesync.transportlayer/resolverecipientscertificates/certificates) { get; } | İkili büyük nesne (BLOB) olarak X509 sertifikalarının listesini içerir. Bu öğe, yalnızca istemci ResolveRecipients komut isteğinde CertificateRetrieval'da 2 değerini belirtirse sunucu tarafından döndürülür. |
| [MiniCertificate](../../aspose.email.clients.activesync.transportlayer/resolverecipientscertificates/minicertificate) { get; set; } | Mini sertifika BLOB'unu içerir. Bu öğe, yalnızca istemci, ResolveRecipients komut isteğinde CertificateRetrieval'da 3 değerini belirtirse ve çözümlenen alıcının geçerli bir S/MIME sertifikası varsa döndürülür. |
| [RecipientCount](../../aspose.email.clients.activesync.transportlayer/resolverecipientscertificates/recipientcount) { get; set; } | Bir dağıtım listesine ait üye sayısını belirtir. CertificateCount ve RecipientCount öğelerinin değerlerini karşılaştırarak bir dağıtım listesine ait tüm alıcıların geçerli sertifikalara sahip olup olmadığını belirlemek için kullanılabilir. |
| [Status](../../aspose.email.clients.activesync.transportlayer/resolverecipientscertificates/status) { get; set; } | ActiveSync komut isteğinin sonucunu gösterir. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->