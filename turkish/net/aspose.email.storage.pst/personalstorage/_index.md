---
title: PersonalStorage
second_title: Aspose.Email for .NET API Referansı
description: Kişisel Depolama Tablosu .pst dosyasını temsil eder.
type: docs
weight: 20290
url: /tr/net/aspose.email.storage.pst/personalstorage/
---
## PersonalStorage class

Kişisel Depolama Tablosu (.pst) dosyasını temsil eder.

```csharp
public class PersonalStorage : IDisposable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PersonalStorage](personalstorage)(TraversalExceptionsCallback) | Yeni bir örneğini başlatır[`PersonalStorage`](../personalstorage) class. PST geçişi sırasında meydana gelen istisnaları işlemek için bir geri arama yönteminin ayarlanmasına izin verir. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CanWrite](../../aspose.email.storage.pst/personalstorage/canwrite) { get; } | Geçerli pst'nin yazmayı destekleyip desteklemediğini belirten bir değer alır. |
| [Format](../../aspose.email.storage.pst/personalstorage/format) { get; } | Dosya biçimini alır. |
| [IsUnicode](../../aspose.email.storage.pst/personalstorage/isunicode) { get; } | PST dosya biçiminin Unicode olup olmadığını gösteren bir değer alır. PST dosya biçiminin iki sürümü vardır: Unicode ve ANSI. |
| [RootFolder](../../aspose.email.storage.pst/personalstorage/rootfolder) { get; } | PST'nin kök klasörünü alır. |
| [Store](../../aspose.email.storage.pst/personalstorage/store) { get; } | PST ileti deposunu alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create)(Stream, FileFormatVersion) | Bir akışta PST oluşturur. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_4)(string, FileFormatVersion) | Belirtilen dosya adıyla yeni PST dosyasını oluşturur. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_1)(Stream, FileFormatVersion, bool) | Bir akışta PST oluşturur. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_3)(Stream, FileFormatVersion, CancellationToken) | Bir akışta PST oluşturur. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_5)(string, FileFormatVersion, CancellationToken) | Belirtilen dosya adıyla yeni PST dosyasını oluşturur. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_2)(Stream, FileFormatVersion, bool, CancellationToken) | Bir akışta PST oluşturur. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile)(string) | PST'yi dosyadan yükleyin. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_3)(string, bool) | PST'yi dosyadan yükleyin. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_5)(string, CancellationToken) | PST'yi dosyadan yükleyin. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_1)(string, PersonalStorageLoadOptions) | PST'yi dosyadan yükleyin. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_4)(string, bool, CancellationToken) |  |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_2)(string, PersonalStorageLoadOptions, CancellationToken) | PST'yi dosyadan yükleyin. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream)(Stream) | Akıştan PST yükleyin. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_3)(Stream, bool) | Akıştan PST yükleyin. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_5)(Stream, CancellationToken) | PST'yi dosyadan yükleyin. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_1)(Stream, PersonalStorageLoadOptions) | Akıştan PST yükleyin. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_4)(Stream, bool, CancellationToken) |  |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_2)(Stream, PersonalStorageLoadOptions, CancellationToken) | PST'yi dosyadan yükleyin. |
| [ChangeMessage](../../aspose.email.storage.pst/personalstorage/changemessage)(string, MapiPropertyCollection) | Mesaj özelliklerini değiştirir. |
| [ConvertTo](../../aspose.email.storage.pst/personalstorage/convertto)(FileFormat) | Geçerli nesneyi belirtilen biçime dönüştürür. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder)(string, StandardIpmFolder) | Standart kişilerarası mesaj (IPM) klasörünü oluşturur. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder_1)(string, StandardIpmFolder, bool) | Standart kişilerarası mesaj (IPM) klasörünü oluşturur. |
| [Dispose](../../aspose.email.storage.pst/personalstorage/dispose)() | Serbest bırakma, serbest bırakma veya yönetilmeyen kaynakları sıfırlama ile ilgili uygulama tanımlı görevleri gerçekleştirir. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages)(string) | Klasördeki mesajların yinelenmesini destekleyen numaralandırıcıyı gösterir. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages_1)(string, int, int) | Klasördeki mesajların yinelenmesini destekleyen numaralandırıcıyı gösterir. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments)(MessageInfo) | Ekleri çıkarır. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments_1)(string) | Ekleri çıkarır. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_1)(byte[]) | PST'den mesajı alın. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage)(MessageInfo) | PST'den mesajı alın. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_2)(string) | PST'den mesajı alın. |
| [ExtractProperty](../../aspose.email.storage.pst/personalstorage/extractproperty)(byte[], long) | Öğeyi tam olarak çıkarmadan öğenin belirtilen özelliğini alır. |
| [FindMessages](../../aspose.email.storage.pst/personalstorage/findmessages)(string) | Geçerli klasör için ileti tanımlayıcılarını bulur. GetContents ve EnumerateMessages yöntemleri bir istisna oluşturabildiğinde bozuk pst okuması durumunda yararlı olabilir. |
| [FindSubfolders](../../aspose.email.storage.pst/personalstorage/findsubfolders)(string) | Geçerli klasör için alt klasörlerin tanımlayıcılarını bulur. GetSubfolders ve EnumerateFolders yöntemleri bir istisna oluşturabildiğinde bozuk pst okuması durumunda faydalı olabilir. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid)(byte[]) | Kişisel klasörü PST'den alır. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid_1)(string) | Kişisel klasörü PST'den alır. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder)(byte[]) | İletinin üst klasörünü alır. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder_1)(string) | İletinin üst klasörünü alır. |
| [GetPredefinedFolder](../../aspose.email.storage.pst/personalstorage/getpredefinedfolder)(StandardIpmFolder) | PST'den standart kişilerarası mesaj (IPM) klasörünü alır. Outlook, Giden Kutusu, Silinmiş Öğeler, Gönderilmiş Öğeler vb. gibi bir dizi varsayılan klasör oluşturabilir. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load)(Stream) | Akıştan PST yükleyin. Bu yöntem, yapıcı kullanılarak bir PersonalStorage nesnesi oluşturulduğunda kullanılır. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load_1)(string) | PST'yi dosyadan yükleyin. Bu yöntem, yapıcı kullanılarak bir PersonalStorage nesnesi oluşturulduğunda kullanılır. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith)(Stream[]) | pst deposunu bir veya daha fazla başka pst akışıyla birleştirir. Böylece, birleştirilmiş akış kaynaklardır. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith_1)(string[]) | pst deposunu bir veya daha fazla başka pst dosyasıyla birleştirir. Böylece, birleştirilen dosyalar kaynaklardır. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem)(FolderInfo, FolderInfo) | Belirtilen bir klasörü geçerli pst. içindeki yeni bir üst klasöre taşır |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem_1)(MessageInfo, FolderInfo) | Belirtilen iletiyi geçerli pst. içindeki yeni bir klasöre taşır |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas)(Stream, FileFormat) | Geçerli nesneyi bir akışta belirtilen dosya biçimine kaydeder. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas_1)(string, FileFormat) | Geçerli nesneyi farklı bir dosyada belirtilen bir dosya biçiminde kaydeder. |
| [SaveMessageToStream](../../aspose.email.storage.pst/personalstorage/savemessagetostream)(string, Stream) | İletiyi belirtilen giriş kimliğiyle bir akışa kaydeder. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto_1)(IList&lt;MailQuery&gt;, string) | pst depolama alanını ölçütlere göre böler. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto)(long, string) | pst depolama alanını daha küçük boyutlu parçalara böler. |
| [TryToGetFolderById](../../aspose.email.storage.pst/personalstorage/trytogetfolderbyid)(string, out FolderInfo) | Belirtilen giriş kimliğiyle ilişkili klasörü alır. |
| [TryToSaveMessage](../../aspose.email.storage.pst/personalstorage/trytosavemessage)(string, Stream) | İletiyi belirtilen giriş kimliğiyle bir akışa kaydeder. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
