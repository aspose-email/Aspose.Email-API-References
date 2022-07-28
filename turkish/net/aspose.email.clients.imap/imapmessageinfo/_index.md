---
title: ImapMessageInfo
second_title: Aspose.Email for .NET API Referansı
description: Bir Imap ileti nesnesini temsil eder.
type: docs
weight: 16370
url: /tr/net/aspose.email.clients.imap/imapmessageinfo/
---
## ImapMessageInfo class

Bir Imap ileti nesnesini temsil eder.

```csharp
public sealed class ImapMessageInfo : MessageInfoBase
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Answered](../../aspose.email.clients.imap/imapmessageinfo/answered) { get; } | Flags özelliğinin Yanıtlandı bayrağını içerip içermediğini gösteren bir değer alır. |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc) { get; } | E-posta mesajının gizli karbon kopyasını alır. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc) { get; } | E-posta mesajının CC'sini alır. |
| [ConversationId](../../aspose.email.clients.imap/imapmessageinfo/conversationid) { get; } | Görüşme kimliğini belirten bir değer alır. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date) { get; } | Oluşturma tarihi, mesajı oluşturanın mesajın tamamlandığını ve posta dağıtım sistemine girmeye hazır olduğunu belirttiği tarih ve saati belirtir. Örneğin, bir kullanıcının bir uygulama programında "gönder" veya "gönder" düğmesine bastığı zaman bu olabilir. Her durumda, özellikle iletinin gerçekten taşındığı zamanı iletmek için tasarlanmamıştır, ancak bunun yerine, mesajın insan veya diğer yaratıcısının mesajı son biçimine soktuğu, aktarıma hazır olduğu zaman. (Örneğin, bir ağa bağlı olmayan bir taşınabilir bilgisayar kullanıcısı, bir mesajı teslim edilmek üzere kuyruğa alabilir. Başlangıç tarihinin, kullanıcının iletiyi kuyruğa aldığı tarih ve saati içermesi amaçlanmıştır, kullanıcının iletiyi göndermek için ağa bağlandığı zamanı değil.) |
| [Deleted](../../aspose.email.clients.imap/imapmessageinfo/deleted) { get; } | Flags özelliğinin Silinmiş bayrağı içerip içermediğini gösteren bir değer alır. |
| [Draft](../../aspose.email.clients.imap/imapmessageinfo/draft) { get; } | Flags özelliğinin Taslak bayrağı içerip içermediğini gösteren bir değer alır. |
| [ExtraParameters](../../aspose.email.clients.imap/imapmessageinfo/extraparameters) { get; } | Bir iletinin ek parametrelerini alır. |
| [Flagged](../../aspose.email.clients.imap/imapmessageinfo/flagged) { get; } | Flags özelliğinin Bayraklı bayrağı içerip içermediğini gösteren bir değer alır. |
| [Flags](../../aspose.email.clients.imap/imapmessageinfo/flags) { get; } | İleti bayraklarını alır. |
| [From](../../aspose.email.clients/messageinfobase/from) { get; } | Bu iletinin yazarlarının listesini alır. |
| [Headers](../../aspose.email.clients/messageinfobase/headers) { get; } | E-posta iletisinin Başlıklarını alır. |
| [InternalDate](../../aspose.email.clients.imap/imapmessageinfo/internaldate) { get; } | Sunucudaki mesajın dahili tarihi ve saati. Bu, [RFC-2822] başlığındaki tarih ve saat değil, mesajın ne zaman alındığını gösteren bir tarih ve saattir. - [SMTP] yoluyla teslim edilen mesajlar durumunda, bu, [SMTP] tarafından tanımlanan mesajın nihai teslim tarihi ve saati OLMALIDIR. - IMAP4rev1 COPY komutu tarafından teslim edilen mesajlar durumunda, bu, kaynak mesajın dahili tarih ve saati OLMALIDIR. - IMAP4rev1 EKEND komutu tarafından teslim edilen mesajlar durumunda, bu, belirtilen tarih ve saat OLMALIDIR APPEND komut açıklamasında. - Diğer tüm durumlar uygulama tanımlıdır. |
| [IsRead](../../aspose.email.clients.imap/imapmessageinfo/isread) { get; } | Flags özelliğinin Okuma bayrağını içerip içermediğini gösteren bir değer alır. |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe) { get; } | Liste-Abonelikten Çıkma alanı, kullanıcının doğrudan aboneliğini iptal etme (listeden kaldırma) komutunu (tercihen posta kullanarak) açıklar. Daha fazla ayrıntı için lütfen bkz. https://tools.ietf.org/html/rfc2369 |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid) { get; } | İleti kimliğini alır. |
| [ModificationSequence](../../aspose.email.clients.imap/imapmessageinfo/modificationsequence) { get; } | Bu iletinin değişiklik sırasını alır. Daha fazlasını görün: https://tools.ietf.org/html/rfc7162 |
| [ParentFolder](../../aspose.email.clients.imap/imapmessageinfo/parentfolder) { get; } | message için üst klasörü alır |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties) { get; } | Bir mapi özelliği alır. |
| [Recent](../../aspose.email.clients.imap/imapmessageinfo/recent) { get; } | Flags özelliğinin Son bayrağı içerip içermediğini gösteren bir değer alır. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto) { get; } | Bu iletiye yanıt alması gereken adreslerin listesini alır. |
| [Sender](../../aspose.email.clients/messageinfobase/sender) { get; } | Bu mesajın göndericisini alır. |
| [SequenceNumber](../../aspose.email.clients.imap/imapmessageinfo/sequencenumber) { get; } | İleti sıra numarasını alır. |
| [Size](../../aspose.email.clients/messageinfobase/size) { get; } | E-posta iletisinin boyutunu alır. |
| [Subject](../../aspose.email.clients/messageinfobase/subject) { get; } | E-posta iletisinin Konusunu alır. |
| virtual [To](../../aspose.email.clients/messageinfobase/to) { get; } | E-posta mesajının alıcılarını alır. |
| [UniqueId](../../aspose.email.clients.imap/imapmessageinfo/uniqueid) { get; } | İletinin benzersiz kimliğini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [ContainsKeyword](../../aspose.email.clients.imap/imapmessageinfo/containskeyword)(string) | Flags özelliğinin Anahtar Kelime bayrağını içerip içermediğini gösteren bir değer alır. |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilgili görevleri gerçekleştirir. |
| override [ToString](../../aspose.email.clients.imap/imapmessageinfo/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |

### Ayrıca bakınız

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase)
* ad alanı [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
