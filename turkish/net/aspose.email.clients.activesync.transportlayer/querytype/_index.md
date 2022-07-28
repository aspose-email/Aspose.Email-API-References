---
title: QueryType
second_title: Aspose.Email for .NET API Referansı
description: Aranan mağazadaki girişleri eşleştirmek için kullanılacak anahtar sözcükleri belirtir. Sorgunun değeri önek-dize eşleştirme modeli olarak kullanılır ve dizenin başlangıcıyla eşleşen girişleri döndürür. Örneğin John araması John Frum veya Barry Johnson ile eşleşir ancak James Littlejohn ile eşleşmez. GALde ANR kullanılarak dizine eklenen boş olmayan tüm metin özellikleri Sorgu öğesiyle karşılaştırılır değer. Arama karşılaştırmaları büyük/küçük harfe duyarlı olmayan eşleme kullanılarak gerçekleştirilir. Windows SharePoint Services belge kitaplığı araması için bu protokol aşağıdaki biçimdeki sorguları destekler LinkId  değer burada değer öğenin veya klasörün URLsini ve LinkIdnin gösterdiği değerin bağlantı kimliği özelliğiyle karşılaştırılacağını belirtir. Posta kutusu araması için sorgu sözdizimi aşağıdaki gibidir - Klasörler aşağıdaki şekillerde belirtilebilir Belirtilen Kimlik Belirtilen klasör ve alt klasörler Taslak dahil tüm e-posta klasörleri Gelen kutusu ve alt klasörler Giden Kutusu ve Gönderilmiş Öğeler - Temel anahtar kelime sorgusu aşağıdakilerden oluşabilir Temel işleç Ve bölüm 2.2.3.10 BüyükTer bölüm 2.2.3.78 ve KüçükTan kullanılarak belirtilen bir tarihsaat filtresi öğeler bölüm 2.2.3.87 Anahtar sözcükleri içeren Serbest Metin öğeleri bölüm 2.2.3.73 Temel anahtar sözcük sorgusu dizine alınmış tüm özelliklere karşı yürütülür.
type: docs
weight: 1780
url: /tr/net/aspose.email.clients.activesync.transportlayer/querytype/
---
## QueryType class

Aranan mağazadaki girişleri eşleştirmek için kullanılacak anahtar sözcükleri belirtir. Sorgunun değeri, önek-dize eşleştirme modeli olarak kullanılır ve dizenin başlangıcıyla eşleşen girişleri döndürür. Örneğin, "John" araması "John Frum" veya "Barry Johnson" ile eşleşir, ancak "James Littlejohn" ile eşleşmez. GAL'de ANR kullanılarak dizine eklenen boş olmayan tüm metin özellikleri Sorgu öğesiyle karşılaştırılır değer. Arama karşılaştırmaları, büyük/küçük harfe duyarlı olmayan eşleme kullanılarak gerçekleştirilir. Windows SharePoint Services belge kitaplığı araması için bu protokol aşağıdaki biçimdeki sorguları destekler: LinkId == değer, burada değer, öğenin veya klasörün URL'sini ve LinkId'nin gösterdiği değerin bağlantı kimliği özelliğiyle karşılaştırılacağını belirtir. Posta kutusu araması için sorgu sözdizimi aşağıdaki gibidir: - Klasörler aşağıdaki şekillerde belirtilebilir: Belirtilen Kimlik Belirtilen klasör ve alt klasörler Taslak dahil tüm e-posta klasörleri, Gelen kutusu ve alt klasörler, Giden Kutusu ve Gönderilmiş Öğeler - Temel anahtar kelime sorgusu aşağıdakilerden oluşabilir: Temel işleç: Ve (bölüm 2.2.3.10) BüyükTer (bölüm 2.2.3.78) ve KüçükTan kullanılarak belirtilen bir tarihsaat filtresi öğeler (bölüm 2.2.3.87) Anahtar sözcükleri içeren Serbest Metin öğeleri (bölüm 2.2.3.73) Temel anahtar sözcük sorgusu, dizine alınmış tüm özelliklere karşı yürütülür.

```csharp
public class QueryType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [QueryType](querytype)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/querytype/class) { get; } | Öğenin sınıfını tanımlar. Geçerli airsync:Class öğesi değerleri: - Tasks - Email - Calendar - Contacts - Notes - SMS Posta kutusu aramaları için aşağıdaki sınıflar desteklenir: E-posta, Takvim, Protokol sürümü 12.1 olduğunda Kişiler, Görevler. SMS ve Notes sınıfları yalnızca protokol sürümü 14.0 veya 14.1 ise kullanılabilir. Arama isteği, Arama yanıtına dahil edilen veri türünü sınırlamak için istekte bir veya daha fazla Sınıf öğesi içerebilir. Arama isteğine bir veya daha fazla Class öğesi eklenmezse, sunucu desteklenen tüm sınıfları döndürür. Sınıf, And öğesi dışında herhangi bir öğenin alt öğesi olarak dahil edilirse, sunucu Durum değeri 8 ile yanıt verir. (SearchTooComplex). |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/querytype/collectionid) { get; } | Arama yapılacak klasörü belirtir. DeepTraversal varsa, her CollectionId altındaki tüm klasörler için geçerlidir. CollectionId, And dışında herhangi bir öğenin alt öğesi olarak dahil edilmişse, sunucu Durum değeri 8 (SearchTooComplex). |
| [ConversationId](../../aspose.email.clients.activesync.transportlayer/querytype/conversationid) { get; set; } | Aranacak konuşmayı belirtir. Değer bir GUID'dir. Protokol sürümü 12.1. olduğunda ConversationId desteklenmez. ConversationId, And öğesi dışında herhangi bir öğenin alt öğesi olarak dahil edilirse, sunucu Durum değeri 8 (SearchTooComplex) ile yanıt verir. |
| [FreeText](../../aspose.email.clients.activesync.transportlayer/querytype/freetext) { get; set; } | Aranacak bir dize değeri belirtir. FreeText özelliği And özelliğinden farklı olarak ayarlanırsa, sunucu Durum değeri 8 (SearchTooComplex) ile yanıt verir. |
| [GreaterThan](../../aspose.email.clients.activesync.transportlayer/querytype/greaterthan) { get; set; } | Bir arama sırasında 'Büyüktür' koşulları için karşılaştırılan bir özelliği ve değeri belirtir. |
| [LessThan](../../aspose.email.clients.activesync.transportlayer/querytype/lessthan) { get; set; } | Bir arama sırasında 'Küçüktür' koşulları için karşılaştırılan bir özelliği ve değeri belirtir. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
