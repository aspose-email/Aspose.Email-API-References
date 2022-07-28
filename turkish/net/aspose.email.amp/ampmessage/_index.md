---
title: AmpMessage
second_title: Aspose.Email for .NET API Referansı
description: Gönderenlerin e-postaların içine AMP bileşenlerini dahil etmesine izin veren mesaj.
type: docs
weight: 140
url: /tr/net/aspose.email.amp/ampmessage/
---
## AmpMessage class

Gönderenlerin e-postaların içine AMP bileşenlerini dahil etmesine izin veren mesaj.

```csharp
public class AmpMessage : MailMessage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [AmpMessage](ampmessage)() | Yeni bir örneğini başlatır[`MailMessage`](../../aspose.email/mailmessage) class |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [AlternateViews](../../aspose.email/mailmessage/alternateviews) { get; } | iletinin alternatif görünümlerinin koleksiyonunu alır |
| virtual [AmpHtmlBody](../../aspose.email.amp/ampmessage/amphtmlbody) { get; set; } | İletinin gövdesinin AmpHtml temsilini alır. |
| virtual [Attachments](../../aspose.email/mailmessage/attachments) { get; } | message eklerinin koleksiyonunu alır |
| virtual [Bcc](../../aspose.email/mailmessage/bcc) { get; set; } | message 'nin BCC alıcılarını içeren adres koleksiyonunu alır veya ayarlar |
| virtual [Body](../../aspose.email/mailmessage/body) { get; set; } | İleti gövdesinin düz metin gösterimini alır veya ayarlar. Bir iletide metin/düz kısım varsa, özellik metin verilerini döndürür. Aksi takdirde, özellik, html işaretlemesi olmadan HtmlBody özelliğinin metin içeriğini döndürür. |
| virtual [BodyEncoding](../../aspose.email/mailmessage/bodyencoding) { get; set; } | body kodlamasını alır veya ayarlar |
| [BodyType](../../aspose.email/mailmessage/bodytype) { get; } | Gövdenin türünü alır. |
| virtual [CC](../../aspose.email/mailmessage/cc) { get; set; } | CC alıcılarını içeren adres koleksiyonunu alır veya ayarlar |
| virtual [Date](../../aspose.email/mailmessage/date) { get; set; } | Mesajın tarihini alır veya ayarlar |
| virtual [DeliveryNotificationOptions](../../aspose.email/mailmessage/deliverynotificationoptions) { get; set; } | Teslimat bildirimlerini alır veya ayarlar |
| [Epilogue](../../aspose.email/mailmessage/epilogue) { get; set; } | Bir sonsöz metni alır veya ayarlar. Son sınırdan sonra bulunur. |
| virtual [From](../../aspose.email/mailmessage/from) { get; set; } | from address adresini alır veya ayarlar |
| virtual [Headers](../../aspose.email/mailmessage/headers) { get; } | message başlık koleksiyonunu alır |
| virtual [HtmlBody](../../aspose.email/mailmessage/htmlbody) { get; set; } | html body alır veya ayarlar |
| virtual [IsBodyHtml](../../aspose.email/mailmessage/isbodyhtml) { get; set; } | İleti gövdesinin Html içinde olup olmadığını belirten bir değer alır veya ayarlar |
| virtual [IsDraft](../../aspose.email/mailmessage/isdraft) { get; set; } | Bir iletinin gönderilip gönderilmediğini gösteren değeri alır veya ayarlar. |
| virtual [IsEncrypted](../../aspose.email/mailmessage/isencrypted) { get; } | İletinin şifrelenip şifrelenmediğini gösteren bir değer alır. |
| virtual [IsReadOnly](../../aspose.email/mailmessage/isreadonly) { get; } | İletinin salt okunur olup olmadığını belirten bir değer alır |
| virtual [IsSigned](../../aspose.email/mailmessage/issigned) { get; } | İletinin imzalanıp imzalanmadığını gösteren bir değer alır. |
| virtual [LinkedResources](../../aspose.email/mailmessage/linkedresources) { get; } | message 'nin bağlantılı kaynaklarının koleksiyonunu alır |
| virtual [MessageId](../../aspose.email/mailmessage/messageid) { get; set; } | id mesajını alır veya ayarlar |
| virtual [OriginalIsTnef](../../aspose.email/mailmessage/originalistnef) { get; } | Orijinal EML iletisinin TNEF biçiminde olup olmadığını belirten bir değer alır. |
| [Preamble](../../aspose.email/mailmessage/preamble) { get; set; } | Bir giriş metni alır veya ayarlar. İlk sınırdan önce bulunur ve genellikle MIME uyumlu olmayan okuyucular için açıklayıcı bir not içerir. |
| [PreferredTextEncoding](../../aspose.email/mailmessage/preferredtextencoding) { get; set; } | Tüm metin özellikleri için tercih edilen kodlamayı alır veya ayarlar |
| virtual [Priority](../../aspose.email/mailmessage/priority) { get; set; } | message önceliğini alır veya ayarlar |
| [ReadReceiptTo](../../aspose.email/mailmessage/readreceiptto) { get; set; } | Okundu bilgisi adresini alır veya ayarlar. |
| virtual [ReplyToList](../../aspose.email/mailmessage/replytolist) { get; set; } | Posta iletisi için yanıtlanacak adreslerinin listesini alır veya ayarlar |
| virtual [ReversePath](../../aspose.email/mailmessage/reversepath) { get; set; } | ReversePath adresini alır veya ayarlar |
| virtual [Sender](../../aspose.email/mailmessage/sender) { get; set; } | Gönderici adresini alır veya ayarlar |
| virtual [Sensitivity](../../aspose.email/mailmessage/sensitivity) { get; set; } | mesajın hassasiyetini alır veya ayarlar |
| virtual [Subject](../../aspose.email/mailmessage/subject) { get; set; } | Konu satırını alır veya ayarlar |
| virtual [SubjectEncoding](../../aspose.email/mailmessage/subjectencoding) { get; set; } | Subject kodlamasını alır veya ayarlar |
| [TimeZoneOffset](../../aspose.email/mailmessage/timezoneoffset) { get; set; } | İleti tarihleri için Eşgüdümlü Evrensel Saat (UTC) uzaklığını alır veya ayarlar. Bu özellik, yerel saat ile UTC arasındaki saat dilimi farkını tanımlar. |
| virtual [To](../../aspose.email/mailmessage/to) { get; set; } | İleti alıcılarını içeren adres koleksiyonunu alır veya ayarlar |
| virtual [XMailer](../../aspose.email/mailmessage/xmailer) { get; set; } | X-Mailer'a e-posta mesajını oluşturan yazılımını alır veya ayarlar |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [AddAlternateView](../../aspose.email/mailmessage/addalternateview)(AlternateView) | message 'ye alternatif bir görünüm ekleyin |
| [AddAmpComponent](../../aspose.email.amp/ampmessage/addampcomponent)(AmpComponent) | Bu mesaja Amp bileşeni ekleyin. |
| virtual [AddAttachment](../../aspose.email/mailmessage/addattachment)(Attachment) | iletiye bir ek ekleyin |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(CmsSigner) | İmzalı bir ileti oluşturur. Belirtilen MailMessage 'nin salt okunur bir kopyasını oluşturur ve buna bir dijital imza ekler. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(X509Certificate2) | İmzalı bir ileti oluşturur. Belirtilen MailMessage 'nin salt okunur bir kopyasını oluşturur ve buna bir dijital imza ekler. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(CmsSigner, bool) | İmzalı bir ileti oluşturur. Belirtilen MailMessage 'nin salt okunur bir kopyasını oluşturur ve buna bir dijital imza ekler. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(X509Certificate2, bool) | İmzalı bir ileti oluşturur. Belirtilen MailMessage 'nin salt okunur bir kopyasını oluşturur ve buna bir dijital imza ekler. |
| virtual [CheckBounced](../../aspose.email/mailmessage/checkbounced)() | Bu iletinin geri dönen ileti olarak değerlendirilip değerlendirilemeyeceğini kontrol eder. |
| virtual [CheckSignature](../../aspose.email/mailmessage/checksignature)() | MailMessage imzası kontrol ediliyor. |
| virtual [Clone](../../aspose.email/mailmessage/clone)() | Bu örneği klonlar |
| [CreateReadReceipt](../../aspose.email/mailmessage/createreadreceipt)(string, string) | Okundu bilgisi oluşturur. |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt)() | Bu mesajın şifresini çözer |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt)(X509Certificate2) | Bu mesajın şifresini çözer |
| [Dispose](../../aspose.email/mailmessage/dispose)() | MailMessage tarafından kullanılan tüm kaynakları serbest bırakır |
| virtual [DKIMSign](../../aspose.email/mailmessage/dkimsign)(RSACryptoServiceProvider, DKIMSignatureInfo) | Bu iletiyi DKIM (DomainKeys Identified Mail) imzasını kullanarak imzalar. |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt)(X509Certificate2) | Bu mesajı şifreler |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt)(X509Certificate2[]) | Bu mesajı şifreler |
| override [Equals](../../aspose.email/mailmessage/equals)(object) | Belirtilen Object'in mevcut Object'e eşit olup olmadığını belirler. |
| [GetEnumerator](../../aspose.email/mailmessage/getenumerator)() | Bir koleksiyon boyunca yinelenen bir Numaralandırıcı döndürür. |
| override [GetHashCode](../../aspose.email/mailmessage/gethashcode)() | object için bir karma kod döndürür |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext)(bool) | Mesaj html gövdesini düz metin olarak alır. Bu yöntem, HtmlBody özelliğini ayrıştırır ve html işaretlemesini yok sayarak düz metin içeriğini döndürür. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext)(HyperlinkRenderingCallback) | htmlbody mesajını düz metin olarak alır. |
| virtual [GetObjectData](../../aspose.email/mailmessage/getobjectdata)(SerializationInfo, StreamingContext) | BirSerializationInfo hedef nesneyi seri hale getirmek için gereken verilerle. |
| virtual [Import](../../aspose.email/mailmessage/import)(Stream) | İletiyi stream öğesinden içe aktarır |
| [RecomposeTnefContent](../../aspose.email/mailmessage/recomposetnefcontent)() | TNEF içeriğini oluşturur. Bir ileti başlangıçta TNEF içeriyorsa ve FileCompatibilityMode.PreserveTnefAttachments bayrağı olmadan yüklendiyse, tnef ekinin oluşturulduğunu unutmayın, Yani bu yöntem normal olandan tnef iletisi oluşturmaz. |
| virtual [RemoveSignature](../../aspose.email/mailmessage/removesignature)() | imzayı kaldır |
| virtual [Save](../../aspose.email/mailmessage/save)(Stream) | İletiyi akış olarak kaydet |
| virtual [Save](../../aspose.email/mailmessage/save)(string) | İletiyi dosya olarak kaydet |
| override [Save](../../aspose.email.amp/ampmessage/save#save_1)(Stream, SaveOptions) | İletiyi akış olarak kaydet |
| virtual [Save](../../aspose.email/mailmessage/save)(string, SaveOptions) | İletiyi ek seçeneklerle dosya olarak kaydedin. |
| virtual [SetHtmlBody](../../aspose.email/mailmessage/sethtmlbody)(string, bool) | HTML gövdesini ayarlar. |
| override [ToString](../../aspose.email/mailmessage/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |

### Ayrıca bakınız

* class [MailMessage](../../aspose.email/mailmessage)
* ad alanı [Aspose.Email.Amp](../../aspose.email.amp)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
