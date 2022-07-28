---
title: SyncCollectionRequest
second_title: Aspose.Email for .NET API Referansı
description: Sınıf belirli bir koleksiyona uygulanan komutları ve seçenekleri içerir.
type: docs
weight: 2190
url: /tr/net/aspose.email.clients.activesync.transportlayer/synccollectionrequest/
---
## SyncCollectionRequest class

Sınıf, belirli bir koleksiyona uygulanan komutları ve seçenekleri içerir.

```csharp
public class SyncCollectionRequest
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [SyncCollectionRequest](synccollectionrequest)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/collectionid) { get; set; } | Senkronize edilecek klasörün sunucu kimliğini belirtir. |
| [Commands](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/commands) { get; set; } | Bir koleksiyona uygulanan işlemleri içerir. Kullanılabilir işlemler Ekle, Sil, Değiştir, Al ve SoftDelete'dir. |
| [ConversationMode](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/conversationmode) { get; set; } | Senkronizasyon yanıtının sonuçlarına konuşma modalitesine dahil edilen öğelerin dahil edilip edilmeyeceğini belirtir. ConversationMode öğesi değerinin DOĞRU olarak ayarlanması, belirtilen tarih filtresi içinde alınan konuşmalarla eşleşen tüm e-postaların alınmasını sağlar. Ancak, bu zamana dayalı filtrenin dışındaki e-postaların gövdesi alınmayacak olsa da, önizlemeler istendiyse metin önizlemeleri alınacaktır. Bir Senkronizasyon isteğinde ConversationMode öğe değerinin FALSE olarak ayarlanması, aşağıdakilerin senkronizasyonuyla sonuçlanır. FilterType öğesi (bölüm 2.2.3.64) değerinin ölçütlerini karşılayan öğeler. ConversationMode öğe değerinin DOĞRU olarak ayarlanması, sonuç kümesini, aynı email2:ConversationId ([MS-ASEMAIL] bölüm 2.2.2.14) değerlerine sahip tüm öğeleri FilterType sonuç kümesindekilerle içerecek şekilde genişletir. ConversationMode öğesi değerinin CollectionId öğesi tarafından belirtilen koleksiyonun dışındaki öğeler üzerinde hiçbir etkisi yoktur (bölüm 2.2.3.30.5); sonuç kümesi her zaman belirtilen koleksiyondaki öğelerle sınırlıdır. ConversationMode öğe değeri, yalnızca FilterType öğe değeri tarafından belirlenen sonuçları sınırlar veya genişletir. |
| [DeletesAsMoves](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/deletesasmoves) { get; set; } | Silinen tüm öğelerin Silinmiş Öğeler klasörüne taşınması gerektiğini belirten istekler. DeletesAsMoves öğesi false olarak ayarlanırsa, silme işlemi kalıcıdır. İstemci öğeleri kalıcı olarak silmek isterse, istek, FALSE değerine sahip DeletesAsMoves öğesini İÇERMELİDİR. Varsayılan değer olan DOĞRU değeri, silinen tüm öğelerin Silinmiş Öğeler klasörüne taşındığını gösterir. |
| [GetChanges](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/getchanges) { get; set; } | Sunucunun, ServerId öğesi tarafından belirtilen koleksiyonda bekleyen tüm değişiklikleri yanıtına dahil ettiği istekler (bölüm 2.2.3.151.6). Son senkronizasyondan bu yana değişiklikler olduysa, sunucu yanıtı, eklemeleri, silmeleri ve değişiklikleri içeren bir Komutlar öğesi (bölüm 2.2.3.32) içerir . İstemci, sunucu değişikliklerinin döndürülmesini istemezse, istek şunları içermelidir ZORUNLU. FALSE değerine sahip GetChanges öğesi. DOĞRU değeri, istemcinin sunucu değişikliklerinin döndürülmesini istediğini belirtir. GetChanges öğesi boş olduğunda TRUE değeri varsayılır. İstekte GetChanges öğesi bulunmadığında, davranış, bölüm 2.2.3.166.4'te belirtildiği gibi SyncKey öğesinin değerine bağlıdır. SyncKey öğesinin değeri 0 ise, istek GetChanges öğesi FALSE olarak ayarlanmış gibi işlenir. SyncKey öğesinin sıfırdan farklı bir değeri varsa, istek GetChanges öğesi ayarlanmış gibi işlenir DOĞRU'ya. |
| [Options](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/options) { get; } | Senkronizasyonun nasıl gerçekleştirildiğinin belirli yönlerini kontrol eden seçenekleri belirtir. İzin verilen sayı 0...2. Senkronizasyon seçenekleri, istemcinin kesme ve içerik ayarlarını belirlemesini sağlar. Bu ayarlar, [MS-ASAIRS] bölüm 2.2.2.7'de belirtildiği gibi bir airsyncbase:BodyPreference alt öğesi içinde kapsüllenir. Senkronizasyon seçenekleri bir koleksiyonda belirtildiğinden, istemci, senkronize edildiği her koleksiyon için benzersiz bir airsyncbase:BodyPreference öğe değeri belirleyebilir. airsyncbase:BodyPreference öğesi hakkında daha fazla ayrıntı için, bkz. [MS-ASAIRS] bölüm 2.2. 2.7. Sunucu, "yapışkan seçenekler" olarak adlandırılan bir kavram kullanarak, istekler arasında Seçenekler bloğunu korur. Seçenekler bloğu bir isteğe dahil değilse, önceki Seçenekler bloğu kullanılır. İstemci, isteğe bir Seçenekler bloğu ekleyerek yeni seçenekler belirlediğinde, sunucu orijinal Seçenekler bloğunu yeni Seçenekler bloğuyla değiştirmelidir ZORUNLU. Tek bir Senkronizasyon komut isteğine iki Seçenek öğesi dahil edilmişse, Seçenek öğelerinden biri ZORUNLUDUR SMS sınıfı için senkronizasyon seçeneklerini belirtirken, diğer Seçenekler öğesi verilen klasörün varsayılan sınıfı için seçenekleri belirtir. |
| [Supported](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/supported) { get; } | Contact sınıfının ve Ghosted olmayan Calendar sınıfının öğeleri, Supported öğesinin alt öğeleri olarak dahil edilebilir. Hayalet özelliklerin kullanımıyla ilgili ayrıntılar için bkz. bölüm 2.2.3.154. |
| [SyncKey](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/synckey) { get; set; } | SyncKey değeri, sunucu tarafından bir koleksiyonun senkronizasyon durumunu işaretlemek için kullanılır. 0 (sıfır) değerinde bir senkronizasyon anahtarı, sunucudaki senkronizasyon durumunu başlatır ve koleksiyonun tam senkronizasyonuna neden olur. |
| [WindowSize](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/windowsize) { get; set; } | Senkronizasyon yanıtına dahil edilmesi GEREKEN bir koleksiyon veya istekteki maksimum değiştirilen öğe sayısını belirtir. WindowSize tanımlı değilse, sunucu 100 değerinde bir WindowSize öğesi gönderilmiş gibi davranır. Sunucu, 0 değerini (sıfır) ve 512'nin üzerindeki değerleri 512 olarak yorumlar. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
