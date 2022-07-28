---
title: ExchangeMessageInfo
second_title: Aspose.Email for .NET API Referansı
description: ExchangeMessageInfo Exchange Mağazasından alınan E-Posta mesaj bilgilerini temsil eder.
type: docs
weight: 3400
url: /tr/net/aspose.email.clients.exchange/exchangemessageinfo/
---
## ExchangeMessageInfo class

ExchangeMessageInfo, Exchange Mağazasından alınan E-Posta mesaj bilgilerini temsil eder.

```csharp
public abstract class ExchangeMessageInfo : MessageInfoBase
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [Attachments](../../aspose.email.clients.exchange/exchangemessageinfo/attachments) { get; } | İleti eklerini alır |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc) { get; } | E-posta mesajının gizli karbon kopyasını alır. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc) { get; } | E-posta mesajının CC'sini alır. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date) { get; } | Oluşturma tarihi, mesajı oluşturanın mesajın tamamlandığını ve posta dağıtım sistemine girmeye hazır olduğunu belirttiği tarih ve saati belirtir. Örneğin, bir kullanıcının bir uygulama programında "gönder" veya "gönder" düğmesine bastığı zaman bu olabilir. Her durumda, özellikle iletinin gerçekten taşındığı zamanı iletmek için tasarlanmamıştır, ancak bunun yerine, mesajın insan veya diğer yaratıcısının mesajı son biçimine soktuğu, aktarıma hazır olduğu zaman. (Örneğin, bir ağa bağlı olmayan bir taşınabilir bilgisayar kullanıcısı, bir mesajı teslim edilmek üzere kuyruğa alabilir. Başlangıç tarihinin, kullanıcının iletiyi kuyruğa aldığı tarih ve saati içermesi amaçlanmıştır, kullanıcının iletiyi göndermek için ağa bağlandığı zamanı değil.) |
| [From](../../aspose.email.clients/messageinfobase/from) { get; } | Bu iletinin yazarlarının listesini alır. |
| virtual [HasAttachments](../../aspose.email.clients.exchange/exchangemessageinfo/hasattachments) { get; } | İletinin en az bir ek içerip içermediğini gösteren bir değer alır. |
| [Headers](../../aspose.email.clients/messageinfobase/headers) { get; } | E-posta iletisinin Başlıklarını alır. |
| virtual [InternalDate](../../aspose.email.clients.exchange/exchangemessageinfo/internaldate) { get; } | Sunucudaki mesajın dahili tarihi ve saati. Bu, [RFC-2822] başlığındaki tarih ve saat değil, mesajın ne zaman alındığını gösteren bir tarih ve saattir. - [SMTP] yoluyla teslim edilen mesajlar durumunda, bu, [SMTP] tarafından tanımlanan mesajın nihai teslim tarihi ve saati OLMALIDIR. - IMAP4rev1 COPY komutu tarafından teslim edilen mesajlar durumunda, bu, kaynak mesajın dahili tarih ve saati OLMALIDIR. - IMAP4rev1 EKEND komutu tarafından teslim edilen mesajlar durumunda, bu, belirtilen tarih ve saat OLMALIDIR APPEND komut açıklamasında. - Diğer tüm durumlar uygulama tanımlıdır. |
| virtual [IsRead](../../aspose.email.clients.exchange/exchangemessageinfo/isread) { get; } | İletinin okunup okunmadığını gösteren bir değer alır |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe) { get; } | Liste-Abonelikten Çıkma alanı, kullanıcının doğrudan aboneliğini iptal etme (listeden kaldırma) komutunu (tercihen posta kullanarak) açıklar. Daha fazla ayrıntı için lütfen bkz. https://tools.ietf.org/html/rfc2369 |
| virtual [MessageClass](../../aspose.email.clients.exchange/exchangemessageinfo/messageclass) { get; } | İleti için sınıfı temsil eden bir dize alır. Özellik, PidTagMessageClass MAPI özelliğine karşılık gelir. |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid) { get; } | İleti kimliğini alır. |
| virtual [MessageInfoType](../../aspose.email.clients.exchange/exchangemessageinfo/messageinfotype) { get; } | İletinin türünü alır |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties) { get; } | Bir mapi özelliği alır. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto) { get; } | Bu iletiye yanıt alması gereken adreslerin listesini alır. |
| [Sender](../../aspose.email.clients/messageinfobase/sender) { get; } | Bu mesajın göndericisini alır. |
| [Size](../../aspose.email.clients/messageinfobase/size) { get; } | E-posta iletisinin boyutunu alır. |
| [Subject](../../aspose.email.clients/messageinfobase/subject) { get; } | E-posta iletisinin Konusunu alır. |
| virtual [To](../../aspose.email.clients/messageinfobase/to) { get; } | E-posta mesajının alıcılarını alır. |
| virtual [UniqueUri](../../aspose.email.clients.exchange/exchangemessageinfo/uniqueuri) { get; } | İletinin benzersiz URI'sini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilgili görevleri gerçekleştirir. |
| override [ToString](../../aspose.email.clients/messageinfobase/tostring)() | Geçerli nesneyi temsil eden bir dize. |

### Ayrıca bakınız

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase)
* ad alanı [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
