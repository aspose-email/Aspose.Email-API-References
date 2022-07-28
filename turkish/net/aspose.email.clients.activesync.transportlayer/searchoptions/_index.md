---
title: SearchOptions
second_title: Aspose.Email for .NET API Referansı
description: Arama seçeneklerini içerir. KullanıcıAdı ve Parola yalnızca 14 Durum değeri alındıktan sonra istekte gönderilebilir. Sunucu istenen kaynaklara erişmek için bu kimlik bilgilerini gerektirir. İstemci bunları yalnızca güvenli veya güvenilir bir bağlantı üzerinden ve yalnızca 14 Durum değerine yanıt olarak göndermesi ZORUNLUDUR. Desteklenen seçenekler aranmakta olan mağazaya göre değişir. Aşağıdaki tablo her mağaza için geçerli seçenekleri listeler. GAL Aralık KullanıcıAdı Parola Picture Posta Kutusu Aralık DeepTraversal RebuildResults BodyPreference BodyPartPreference RightsManagementSupport DocumentLibrary Aralık KullanıcıAdı Parola SearchPreferenceda yalnızca BodyPart geçerlidir ConversationId. içeren komut istekleri
type: docs
weight: 1950
url: /tr/net/aspose.email.clients.activesync.transportlayer/searchoptions/
---
## SearchOptions class

Arama seçeneklerini içerir. KullanıcıAdı ve Parola, yalnızca 14 Durum değeri alındıktan sonra istekte gönderilebilir. Sunucu, istenen kaynaklara erişmek için bu kimlik bilgilerini gerektirir. İstemci bunları yalnızca güvenli veya güvenilir bir bağlantı üzerinden ve yalnızca 14 Durum değerine yanıt olarak göndermesi ZORUNLUDUR. Desteklenen seçenekler aranmakta olan mağazaya göre değişir. Aşağıdaki tablo, her mağaza için geçerli seçenekleri listeler. GAL: Aralık, KullanıcıAdı, Parola, Picture Posta Kutusu: Aralık, DeepTraversal, RebuildResults, BodyPreference, BodyPartPreference, RightsManagementSupport DocumentLibrary: Aralık, KullanıcıAdı, Parola SearchPreference'da yalnızca BodyPart geçerlidir ConversationId. içeren komut istekleri

```csharp
public class SearchOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [SearchOptions](searchoptions)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BodyPartPreference](../../aspose.email.clients.activesync.transportlayer/searchoptions/bodypartpreference) { get; } | Bir mesaj bölümünün aranmasından, eşitlenmesinden veya getirilmesinden döndürülen bilgilerin türü ve boyutuyla ilgili tercih bilgilerini içerir. |
| [BodyPreference](../../aspose.email.clients.activesync.transportlayer/searchoptions/bodypreference) { get; } | Arama, eşitleme veya getirme işlemlerinden döndürülen bilgilerin türü ve boyutuyla ilgili tercih bilgilerini içerir. |
| [DeepTraversal](../../aspose.email.clients.activesync.transportlayer/searchoptions/deeptraversal) { get; set; } | İstemcinin, sunucunun sorguda belirtilen klasörler için tüm alt klasörleri aramasını istediğini belirtir. |
| [MIMESupport](../../aspose.email.clients.activesync.transportlayer/searchoptions/mimesupport) { get; set; } | Sunucudan istemciye gönderilen e-posta öğeleri için MIME desteğini etkinleştirir. airsync:MIMESupport öğesi Arama isteğinde 'SendForSecureMIMEonly' (1) veya 'SendForAll' (2) olarak ayarlanırsa: - Şunun özelliği airsyncbase:BodyPreference, Tür, Arama isteğine dahil edilmelidir, , sunucuya cihazın MIME BLOB'unu okuyabildiğini bildirmek için bir 'MIME' (4) değeri içerir. - Sunucudan gelen yanıt, airsyncbase:Özelliklerin alt öğesi olan Gövde. airsyncbase:Body, bir S/MIME Arama yanıtında aşağıdaki özellikleri içermelidir ZORUNLU: - airsyncbase:Verinin bir MIME BLOB olduğunu cihaza bildirmek için 'MIME' (4) değerine sahip yazın. - airsyncbase :EstimatedDataSize verinin kaba toplam boyutunu belirtmek için. - airsyncbase:MIME BLOB'unun kesilip kesilmediğini belirtmek için kısaltıldı. - airsyncbase:Tam MIME BLOB'unu içeren veriler. |
| [Password](../../aspose.email.clients.activesync.transportlayer/searchoptions/password) { get; set; } | Verilen KullanıcıAdı için parolayı belirtir. Parola değerinin maksimum uzunluğu 100 karakterdir. |
| [Picture](../../aspose.email.clients.activesync.transportlayer/searchoptions/picture) { get; set; } | Fotoğraf isteğiyle ilgili verileri içerir. Protokol sürümü 12.1 veya 14.0. olduğunda Resim desteklenmez. |
| [Range](../../aspose.email.clients.activesync.transportlayer/searchoptions/range) { get; set; } | Döndürülecek maksimum eşleşen giriş sayısını belirtir. Aralık öğesi değerinin biçimi, sıfır, kısa çizgi ve başka bir sayısal değerden oluşan sıfır tabanlı bir dizin belirteci biçimindedir: "mn." m, öğeleri tutacak sıfır tabanlı bir dizinin en düşük dizinini gösterir. n, öğeleri tutacak sıfır tabanlı bir dizinin en yüksek dizinini belirtir. Örneğin, 0–9 aralığındaki bir Aralık öğesi değeri 10 öğeyi, 0–10 ise 11 öğeyi belirtir. 0–0 Aralık öğesi değeri 1 öğeyi belirtir. Aralık boşsa, her Mağaza türü için varsayılan Aralık değeri kullanılır. Aşağıdaki tablo, her Mağaza türü için döndürülen varsayılan Aralık değerlerini ve maksimum sonuçları tanımlar: Posta Kutusu - Varsayılan aralık değeri: 0-99 - Döndürülen maksimum sonuç: 100 DocumentLibrary - Döndürülen varsayılan aralık değeri: 0-999 - : 1000 GAL - Varsayılan aralık değeri: 0-99 - Döndürülen maksimum sonuç: 100 İstekte belirtilen Aralık değeri varsayılan aralık değerini aşarsa, maksimum aralığın aşıldığını belirtmek için 12 Durum değeri döndürülür. Arama komutu yanıtında, Toplam özelliği, Sorgu değeriyle eşleşen toplam giriş sayısının bir tahminini gösterir. Arama sonuçları, sunucudaki bir arama klasöründe depolanır. Bu şekilde, bir istemci aynı sorguyla ancak yeni bir satır aralığıyla geri geldiğinde, o anda arama klasöründe depolanan sonuç kümesinden satırlar çekilir. Sonuç kümesinin tamamının yeniden oluşturulması gerekmez. |
| [RebuildResults](../../aspose.email.clients.activesync.transportlayer/searchoptions/rebuildresults) { get; set; } | Sunucuyu, belirli bir sorguya karşılık gelen arama klasörünü (2) yeniden oluşturmaya zorlar. Arama sonuçları (yani sonuç kümesi), sunucudaki bir arama klasöründe depolanır. Bu şekilde, bir istemci aynı sorguyla ancak yeni bir satır aralığıyla geri geldiğinde, o anda arama klasöründe depolanan sonuç kümesinden satırlar çekilir. Tüm sonuç kümesinin yeniden oluşturulması gerekmez. İstemci, sonuç kümesini güncellemek için aşağıdakilerden birini yapana kadar arama klasörü değişmeden kalır: - Yeni bir sorgu belirterek bir Arama isteği gönderir. Bu durumda, arama klasörü otomatik olarak yeniden oluşturulur. RebuildResults düğümünün dahil edilmesi gerekmez. - RebuildResults düğümünü içeren bir Arama isteği gönderir. Bu durumda, sunucu arama klasörünü yeniden oluşturmaya zorlanır. Yeni bir öğe eklenirse, sonuç kümesi güncellenene kadar öğe sonuç kümesinde görünmez. Bir öğe silinirse, sunucu silinen öğeyi sonuç kümesinin dışında filtreleyecektir. İstemci, o sorgu için doğru sonuçları sağlamak için birkaç günde bir verilen sorguyla yeni bir Arama isteği göndermeli ve RebuildResults seçeneğini dahil etmelidir. |
| [RightsManagementSupport](../../aspose.email.clients.activesync.transportlayer/searchoptions/rightsmanagementsupport) { get; set; } | Sunucunun haklarıyla yönetilen e-posta iletilerini istemciye nasıl döndürdüğünü belirtir. Değer DOĞRU ise, sunucu, hakları yönetilen e-posta iletilerini istemciye göndermeden önce sıkıştırır ve şifresini çözer. Değer YANLIŞ ise, sunucu, hakları yönetilen e-posta iletilerini istemciye göndermeden önce sıkıştırmayı açmaz veya şifresini çözmez. RightsManagementSupport öğesi bir istek iletisine dahil edilmemişse, varsayılan bir FALSE değeri varsayılır. |
| [UserName](../../aspose.email.clients.activesync.transportlayer/searchoptions/username) { get; set; } | Belge kitaplığından belge aramak için kullanılan kullanıcı hesabını belirtir. KullanıcıAdı değeri en fazla 100 karakter uzunluğunda olabilir. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
