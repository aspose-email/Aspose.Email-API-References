---
title: ExchangeFolderType
second_title: Aspose.Email for .NET API Referansı
description: Ayırt edici klasör türlerini numaralandırır. Bu değerler PidTagContainerClass özelliğinde de bulunur.
type: docs
weight: 3340
url: /tr/net/aspose.email.clients.exchange/exchangefoldertype/
---
## ExchangeFolderType enumeration

Ayırt edici klasör türlerini numaralandırır. Bu değerler PidTagContainerClass özelliğinde de bulunur.

```csharp
public enum ExchangeFolderType
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Undefined | `0` | Klasör türü ayarlanmadı. Değer, aşağıdaki iyi bilinen klasörlerle kullanılır: Kök - Mesaj deposu hiyerarşisinin, o ileti deposundaki diğer tüm Klasör nesnelerini içeren en üst düzey klasörü. Bulucu - Varsayılan arama klasörlerini içerir. FreeBusy Verileri - Posta kutusu sahibinin serbest/meşgul verilerini içerir. Kişisel Klasörlerin Başı - Gelen Kutusu klasörü gibi çoğu özel klasör dahil olmak üzere kullanıcı verileri klasörlerini içeren kişilerarası ileti hiyerarşisinin en üst klasörü. Ortak Görünümler - İçerir mesaj deposu için standart olan ve mesaj deposuna erişen bir istemcinin herhangi bir kullanıcısı tarafından kullanılabilen varsayılan görünümler için veriler. Kişisel Görünümler - Belirli bir kullanıcı tarafından tanımlanan görünümler için verileri içerir. Ertelenmiş Eylem - Herhangi bir Ertelenmiş'i içerir İstemci tarafı kurallarının yürütülmesinden kaynaklanan Eylem Mesajı (DAM) veya Ertelenmiş Hata Mesajı (DEM). |
| Note | `1` | Bu değer, e-posta İleti klasörü türünü ("IPF.Note") temsil eder. Değer, aşağıdaki iyi bilinen klasörlerle kullanılır: Silinmiş Öğeler - Silinmiş nesneler için varsayılan konum. Giden Kutusu - Giden e-posta İleti nesneleri, İleti nesnesi gönderildiğinde bu klasöre yerleştirilir. Gönderilmiş Öğeler - E-postanın kopyalarının gönderildikten (gönderildikten) sonra yerleştirildiği varsayılan konum. Gelen Kutusu - Gelenler için varsayılan konum ( alınan) e-posta İleti nesneleri. Taslaklar - Kaydedilmiş ancak gönderilmemiş olan ileti nesneleri için varsayılan konum. Önemsiz E-posta - E-posta için varsayılan konum Önemsiz e-posta olarak belirlenen ileti nesneleri Önemsiz E-posta kuralı ile. Eşitleme Sorunları - İstemci ve sunucu arasındaki eşitleme sırasında karşılaşılan belirli sorunları gösteren iletileri içeren klasörleri içerir. Bu, Çakışmalar, Yerel Hatalar ve Sunucu Hataları klasörlerinin üst klasörüdür. Çakışmalar - İstemci ve sunucu arasındaki eşitleme çakışmalarını gösteren İleti nesnelerini içerir. Yerel Hatalar - İstemci tarafı eşitleme hatalarını gösteren iletileri içerir. Sunucu Hataları - Sunucu tarafı senkronizasyon hatalarını gösteren iletileri içerir. İzlenen Posta İşleme - İşaretli nesneleri içeren arama klasörü. Biriktirici Kuyruğu - Gönderilmiş veya alınmış E-posta nesnelerini içerir. |
| RSSFeeds | `2` | Bu değer, RSS İletisi klasör türünü ("IPF.Note.OutlookAna Sayfa") temsil eder. Değer, aşağıdaki iyi bilinen klasörlerle kullanılır: RSS Beslemeleri - Gerçekten Basit Dağıtım (RSS) besleme iletileri içerir. |
| Appointment | `3` | Bu değer, 'randevu' klasör türünü ("IPF.Appointment") temsil eder. Değer, aşağıdaki iyi bilinen klasörlerle kullanılır: Calendar - Randevular gibi Takvim nesnelerini içerir. |
| Contact | `4` | Bu değer, 'kişiler' klasör türünü ("IPF.Contact") temsil eder. Değer, aşağıdaki iyi bilinen klasörlerle kullanılır: Kişiler - Kişi nesnelerini içerir. Önerilen Kişiler - Bir alıcı olmadığında oluşturulan Kişi nesnelerini içerir. bir adres defterinde. Kişi Arama - Arama kriterlerine uyan kişilerin listesini görüntüleyen arama klasörü. |
| QuickContacts | `5` | Bu değer, sık kullanılan kişiler ("IPF.Contact.MOC.QuickContacts") için klasör türünü temsil eder. Değer, aşağıdaki iyi bilinen klasörlerle kullanılır: Hızlı Kişiler - Kullanıcının favori kişileri ve anlık ileti kişileri için Kişi nesnelerini içerir. |
| ImContactsList | `6` | Bu değer, anlık mesajlaşma kişileri ("IPF.Contact.MOC.ImContactList") için klasör türünü temsil eder. Değer, aşağıdaki iyi bilinen klasörlerle kullanılır: IM Kişi Listesi - Favori kişilerin ve anlık ileti kişilerinin Kişisel Dağıtım Listesi nesnelerini içerir . |
| DocumentLibraries | `7` | Bu değer, 'belgeler' klasör türünü ("IPF.ShortcutFolder") temsil eder. Değer, aşağıdaki iyi bilinen klasörlerle kullanılır: Belge Kitaplıkları - Paylaşılan bir konuma yüklenecek belgeleri içerir. |
| Journal | `8` | Bu değer, 'Günlük' klasör türünü ("IPF.Journal") temsil eder. Değer, aşağıdaki iyi bilinen klasörlerle kullanılır: Günlük - Günlük nesnelerini içerir. |
| StickyNote | `9` | Bu değer, 'notes' klasör türünü ("IPF.StickyNote") temsil eder. Değer, aşağıdaki iyi bilinen klasörlerle kullanılır: Notlar - Not nesnelerini içerir. |
| Task | `10` | Bu değer, 'Görev' klasör türünü ("IPF.Görev") temsil eder. Değer, aşağıdaki iyi bilinen klasörlerle kullanılır: Yapılacaklar - Görev nesnelerini izlemek için kullanılan arama klasörü. Görevler - Görev nesnelerini içerir. |
| Imap | `11` | Bu değer, 'imap' klasör türünü ("IPF.IMAP") temsil eder. IMAP profilinden Exchange'e geçiş yapmak için kullanılır. |
| Unknown | `12` | Klasör türü bilinmiyor. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
