---
title: HeaderType
second_title: Aspose.Email for .NET API Referansı
description: İnternet standartlarını temsil eder ve RFCler İnternet Posta Mesajlarında oluşabilecek başlık alanlarını tanımlar .
type: docs
weight: 17510
url: /tr/net/aspose.email/headertype/
---
## HeaderType class

İnternet standartlarını temsil eder ve RFC'ler İnternet Posta Mesajlarında oluşabilecek başlık alanlarını tanımlar .

```csharp
public sealed class HeaderType
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [ApparentlyTo](../../aspose.email/headertype/apparentlyto) { get; } | Orijinal mesajda "Kime:" alıcısı olmadığında e-posta gönderilerek eklenir. Bu, zarftan türetilen alıcıların mesaj başlığında listelenmesine neden olur. Bu davranış pek uygun değildir, MTA'lar üstbilgileri değiştirmemelidir (Alınan satırları eklemek dışında) ve bazı durumlarda Bcc alıcılarının Bcc olmayan alıcılara yanlışlıkla ifşa edilmesine neden olabilir. Örnek: Görünüşe göre-Kime: birisi@somedomain.com RFC1211'de belirtilen, kullanımda önerilmeyen standart dışı başlık. |
| static [ApprovedBy](../../aspose.email/headertype/approvedby) { get; } | Bu mesajın gönderildiği posta listesinin moderatörünün adı; Liste üyelerine dağıtılmasına izin vermek için yönetilen bir posta listesine gönderilen bir gönderide gereklidir. Örnek: Onaylayan: birisi@somedomain.com E-postada kullanım için standart değildir. RFC1036'da tanımlanmıştır. |
| static [Bcc](../../aspose.email/headertype/bcc) { get; } | Birincil alıcıların bilgisi olmadan bir veya daha fazla alıcıya gönderilen e-posta mesajının bir kopyası. Birincil alıcılar Kime: ve Bilgi: satırlarında listelenir. Bu, bir mesajı birçok kişiye, her biri diğer alıcıların kim olduğunu görmeden kopyalamak istiyorsanız kullanışlıdır. Gelen postada bu başlığı görüyorsanız, başlıklarda görünmediğinden bir sorun vardır. |
| static [CC](../../aspose.email/headertype/cc) { get; } | Bu başlık, ek alıcıları belirtmek için kullanıldığı için "Kime:" alanının bir uzantısı olarak kabul edilebilir. Bu durumda, alıcıya gönderilen bir e-posta mesajının kopyasında alıcının adresi mesajda görünür. Bu, her biri diğer alıcıların kim olduğunu görerek birçok kişiye bir mesaj kopyalamak istiyorsanız kullanışlıdır; Yukarıdaki Bcc ile kontrast. Bu başlık gelen e-postada görünüyor. Örnek: Bilgi: gboyd@netcom.com |
| static [Comments](../../aspose.email/headertype/comments) { get; } | Bu, RFC2822'de tanımlanan serbest biçimli bir başlık alanıdır. Başlık, bir e-posta iletisinin başlık bölümüne açıklayıcı metin yerleştirmek için kullanılır. Alan isteğe bağlı metin içerebilir. Örnek: Yorumlar: Kimliği doğrulanmış gönderen birisi@somedonmain.com. |
| static [ContentTransferEncoding](../../aspose.email/headertype/contenttransferencoding) { get; } | MIME ile ilgili başlıkların üçüncüsü. MIME mesaj gövdesinde kullanılan kodlama yöntemini belirtir. E-postanın teslimi ile doğrudan ilgisi yoktur, ancak MIME uyumlu posta programlarının mesajın içeriğini nasıl yorumladığını etkiler. RFC2045'te tanımlanmıştır. İçerik Aktarımı-Kodlaması: 8bit İçerik Aktarımı-kodlaması: 7BIT İçerik Aktarımı-Kodlaması: 7bit İçerik Aktarımı-Kodlaması: base64 İçerik Aktarımı-Kodlaması: alıntı-yazdırılabilir |
| static [ContentType](../../aspose.email/headertype/contenttype) { get; } | "Content-Type", içeriğin biçimini (karakter kümesi vb.) tanımlar. Bu başlık için değerlerin RFC1049 ve MIME'de (RFC2045) farklı şekillerde tanımlandığını unutmayın. Content-Type'ın RFC1049'a göre mi yoksa MIME'ye (RFC2045) göre mi yorumlanacağını anlamak için MIME-version: başlığına bakın. Posta oluştururken MIME tanımı kullanılmalıdır. Tarihsel olarak, İçerik Türü alanı RFC1049'da önerilmiştir. İçinde, Content-Type, RFC2045'in yaptığı gibi türü ve alt türü ayırt etmedi. Örnek: İçerik Türü: metin/düz; charset="us-ascii" İçerik türü: metin/düz; charset=US-ASCII İçerik Türü: metin/düz; charset="iso-8859-1" İçerik Türü: metin/düz; charset=koi8-r İçerik Türü: metin/düz; karakter kümesi=bilinmeyen-8bit |
| static [Date](../../aspose.email/headertype/date) { get; } | Bu başlık, bir tarihi (ve saati), normalde mesajın oluşturulduğu ve gönderildiği tarihi belirtir. X.400 posta sistemlerinde, mesajın gönderildiği saat. Bazı İnternet posta sistemleri, mesajın gönderildiği tarihi de kullanır. Bu başlık gönderenin bilgisayarı tarafından atlanırsa, muhtemelen bir posta sunucusu veya hatta yol boyunca başka bir makine tarafından eklenebilir. "Tarih:" satırındaki bilgilerin, gönderenin bilgisayarındaki doğru ayarlanmış veya ayarlanmamış saat tarafından sağlandığını bilmiyor olabilirsiniz. Ayrıca, "Date:" başlığı normalde mesajın ne zaman gönderildiğini değil, yalnızca ne zaman oluşturulduğunu gösterir. Tarih, 3 karakterli haftanın günü (Paz - Cts), gün numarası (1-31) dd, 3 karakterli ay adı, 4 basamaklı yıl yyyy, ardından saat (24 saat) şeklindedir hh :mm:ss ve bölge zzz formatı. Saat Dilimi (zzz), 3 karakterli saat dilimi veya UTC'den (Evrensel Zaman Koordineli - eski Greenwich Ortalama Saati) saat ve dakika cinsinden yerel farktır. "-" batıyı ve "+" UTC'nin doğusunu gösterir. Standart Saat Dilimi tanımları yok gibi görünüyor. Birçok UNIX sürümü çok çeşitli kısaltmaları anlıyor, ancak bulduğum en kapsamlı liste GNU tar kılavuzu Saat Dilimi öğesi ve Perl tarih işleme modülü TIMEZONES için belgelerdi. Örnek: Tarih: 9 Ocak 2001 Salı 23:40:00 -0800 Tarih: 1 Nisan 2001 Pazar 22:52:04 EDT Tarih: Pzt, 2 Nisan 2001 16:02:19 +0200 Tarih: Cum, 30 Mart 2001 10:47:15 -0800 |
| static [DispositionNotificationTo](../../aspose.email/headertype/dispositionnotificationto) { get; } | DispositionNotificationTo alanı ayarlandığında, bir MDN (Mesaj Teslim Bildirimi) talebi yapılır. Alıcının e-posta yazılımı (Outlook, Eudora, vb.) isteği sessizce görmezden gelebilir veya kullanıcıdan MDN'yi göndermek için izin isteyebilir. "İade-makbuz" garantisi yoktur. DispositionNotificationTo alanı, iade makbuzları (yani MDN veya mesaj teslim bildirimleri) istemek için fiili standarttır. |
| static [FollowupTo](../../aspose.email/headertype/followupto) { get; } | Usenet Haberlerinde, bir makaleyle ilgili gelecekteki tartışmaların (=takip) yanıtlanan makaleden farklı bir haber gruplarına gitmesi gerektiğini belirtmek için kullanılır. En yaygın kullanım, bir makalenin birkaç haber grubuna gönderilmesi ve daha fazla tartışmanın bunlardan yalnızca birinde yer almasıdır. RFC 1036: 2.2.3'te tanımlanmıştır, e-postada kullanım için standartlaştırılmamıştır. |
| static [From](../../aspose.email/headertype/from) { get; } | Bu alan, bu mesajın gönderilmesini isteyen kişinin/kişilerin kimliğini içerir. Mesaj oluşturma işlemi, bu alanı varsayılan olarak, mesajı oluşturan ARACI'yı (kişi, sistem veya süreç) belirten, kimliği doğrulanmış tek bir makine adresi olarak belirlemelidir. Bu yapılmazsa, "Gönderen:" alanı MUTLAKA MEVCUTTUR. "Kimden:" alanı varsayılan olarak bu şekilde ayarlanmışsa, "Gönderen:" alanı isteğe bağlıdır ve "Kimden:" alanıyla birlikte gereksizdir. Örnek: Gönderen: "Mr. Some One" birisi@somedomain.com |
| static [Importance](../../aspose.email/headertype/importance) { get; } | Önemi alır. |
| static [InReplyTo](../../aspose.email/headertype/inreplyto) { get; } | Bu iletinin yanıtlandığı iletiye başvuru. |
| static [MessageID](../../aspose.email/headertype/messageid) { get; } | Bu iletinin benzersiz kimliği. RFC 822'de Tanımlandı: 4.6.1 ,RFC 1036: 2.1.5. |
| static [MIMEVersion](../../aspose.email/headertype/mimeversion) { get; } | Bu iletinin MIME standardına göre biçimlendirildiğinin göstergesi ve hangi MIME sürümünün kullanıldığının bir göstergesi. RFC 2045 'de tanımlanmıştır |
| static [Newsgroups](../../aspose.email/headertype/newsgroups) { get; } | Usenet Haberlerinde: bu makalenin gönderildiği grup(lar). Bazı sistemler bu başlık alanını e-postada da sağlar, ancak orada standartlaştırılmamıştır. Ne yazık ki, başlık alanı e-postada üç farklı ve çelişkili anlamla görünebilir: (a) Hem e-postaya hem de Usenet Haber alıcılarına gönderilen bir makalenin/mesajın haber grubu alıcısını belirtmek. (b) Haber ağ geçitlerinden bazılarına gönderilen bir mesajda, mesajın gönderileceği haber gruplarını belirtir. (c) Bir haber grubundaki bir makaleye, bu tartışmanın kaynaklandığı haber grubunu belirten, kişisel olarak gönderilen bir yanıtta. RFC 1036: 2.1.3'te tanımlanmıştır, standartlaştırılmamıştır ve e-postada kullanım için tartışmalıdır. |
| static [Received](../../aspose.email/headertype/received) { get; } | Bir iletinin geçtiği MTA'ların izi. RFC 822 içinde tanımlı |
| static [References](../../aspose.email/headertype/references) { get; } | Diğer ilgili mesajlara referans. |
| static [ReplyTo](../../aspose.email/headertype/replyto) { get; } | Bu başlık alanı, gönderenin yanıtların nereye gitmesini istediğini belirtmek içindir. Ne yazık ki, bu belirsizdir, çünkü gönderenin farklı adreslere gitmek isteyebileceği farklı yanıt türleri vardır. Özellikle, yalnızca bir kişiye yönelik kişisel yanıtlar ve yanıtlanan iletiyi okuyan tüm insan grubuna yönelik grup yanıtları vardır (farklı sözdizimi nedeniyle genellikle bir posta listesi, bir haber grubu adı burada görünemez, bkz. " Takip" .). |
| static [ReturnPath](../../aspose.email/headertype/returnpath) { get; } | İleti, "MAIL FROM"un kullanıldığı SMTP ortamından ayrıldığında, son teslimatta MAIL FROM zarf özniteliğinden gelen bilgileri iletmek için kullanılır. /// |
| static [ReturnReceiptTo](../../aspose.email/headertype/returnreceiptto) { get; } | Gönderici, bu başlık alanını ekleyerek bir iade makbuzu isteyebilir. İade makbuzu, İade-Makbuz-Alıcı başlık alanında belirtilen adrese değil, e-postanın İade Yolu adresine gönderilir. Bu başlık standart değildir ve çoğunlukla desteklenmez. Bunun yerine Disposition-Bildirim-To'yu kullanın. Desteklense bile, makbuzun gönderileceğine dair bir garanti yoktur. |
| static [Sender](../../aspose.email/headertype/sender) { get; } | Kimden: başlık alanında gösterilenden farklıysa, mesajı ağa gönderen kişi veya aracı. RFC 822'ye göre kimlik doğrulaması yapılmalıdır, ancak ne tür bir kimlik doğrulaması açık değildir. |
| static [Sensitivity](../../aspose.email/headertype/sensitivity) { get; } | Duyarlılığı alır. |
| static [Subject](../../aspose.email/headertype/subject) { get; } | Başlık, başlık, konu. Genellikle diğer mesajlara cevap veren veya yorum yapan mesajlar için konu göstergesi olarak kullanılır. |
| static [To](../../aspose.email/headertype/to) { get; } | Birincil alıcılar. Örnek: Alıcı: birisi@biralan.com |
| static [XConfirmReadingTo](../../aspose.email/headertype/xconfirmreadingto) { get; } | Bu başlık, mesaj alındığında veya okunduğunda otomatik bir onay bildirimi ister. Genellikle göz ardı edilir; muhtemelen bazı yazılımlar buna etki eder. |
| static [XMailer](../../aspose.email/headertype/xmailer) { get; } | Oluşturanın istemci yazılımı hakkında bilgi. Örnek: X-Mailer: Aspose.Email |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Equals](../../aspose.email/headertype/equals)(object) | Obj nesnesinde geçirilenin buna Eşit olup olmadığını gösteren bir boole döndürür. |
| override [GetHashCode](../../aspose.email/headertype/gethashcode)() | Belirli bir tür için karma işlevi işlevi görür. |
| override [ToString](../../aspose.email/headertype/tostring)() | Bir döndürürString akımı temsil edenObject . |
| [implicit operator](../../aspose.email/headertype/op_implicit) | Şundan örtük bir dönüştürme gerçekleştirir:[`HeaderType`](../headertype) ileString . |

### Ayrıca bakınız

* ad alanı [Aspose.Email](../../aspose.email)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
