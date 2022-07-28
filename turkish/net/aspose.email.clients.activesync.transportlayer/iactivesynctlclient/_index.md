---
title: IActiveSyncTLClient
second_title: Aspose.Email for .NET API Referansı
description: ActiveSync istemci arabirimi
type: docs
weight: 1310
url: /tr/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/
---
## IActiveSyncTLClient interface

ActiveSync istemci arabirimi

```csharp
public interface IActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AirSyncKeys](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/airsynckeys) { get; } | Her eşitlenmiş koleksiyonun eşitleme durumunu işaretlemek için sunucu tarafından kullanılan değerleri içerir. Burada sözlük anahtarı sunucu kimliği ve sözlük değeri SyncKey'dir. GetItemEtimate ve Sync komutları için. |
| [FoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderssynckey) { get; } | İstemcinin mevcut durumunu izlemek için sunucu tarafından kullanılır. Yalnızca klasörlerle yapılan işlemler için |
| [HeartbeatInterval](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/heartbeatinterval) { get; set; } | HeartbeatInterval öğesi, Ping komutu istekleri ve yanıtlarındaki Ping öğesinin bir alt öğesidir. Ping komut isteklerinde, bölüm 3.1.5.6'da belirtildiği gibi, belirtilen klasör kümesine yeni öğe eklenmezse, sunucunun yanıt göndermeden önce beklemesi gereken süreyi saniye cinsinden belirtir. HeartbeatInterval öğesi ayrıca sunucu tarafından 5 durum koduyla döndürülür ve istemci kabul edilebilir aralığın dışında bir sinyal aralığı istediğinde izin verilen minimum veya maksimum aralığını belirtir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [FolderCreate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldercreate)(string, string, UserCreatedFolderTypes) | FolderCreate, belirtilen üst klasörün alt klasörü olarak yeni bir klasör oluşturur. |
| [FolderDelete](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderdelete)(string) | Eşleşen tanımlayıcıya sahip koleksiyonu siler. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync)() | FolderSync, koleksiyon hiyerarşisini senkronize eder ancak koleksiyonlardaki öğeleri senkronize etmez. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync_1)(bool) | FolderSync, koleksiyon hiyerarşisini senkronize eder ancak koleksiyonlardaki öğeleri senkronize etmez. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate)(FolderInfo) | FolderUpdate komutu, bir klasörü sunucuda bir konumdan diğerine taşır. Komut, bir klasörü yeniden adlandırmak için de kullanılır. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate_1)(string, string, string) | FolderUpdate komutu, bir klasörü sunucuda bir konumdan diğerine taşır. Komut, bir klasörü yeniden adlandırmak için de kullanılır. |
| [GetAttachment](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getattachment)(string) | GetAttachment, sunucudan bir e-posta eki alır. GetAttachment, protokol sürümü 14.0 veya 14.1 olduğunda desteklenmez. Bunun yerine ItemOperations komutunun Getir öğesini kullanın. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_2)(IEnumerable&lt;ItemEstimateRequest&gt;) | GetItemEstimate komutu, eşitlenmesi gereken sunucudaki bir koleksiyon veya klasördeki öğelerin bir tahminini alır. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate)(ItemEstimateRequest) | GetItemEstimate komutu, eşitlenmesi gereken sunucudaki bir koleksiyon veya klasördeki öğelerin bir tahminini alır. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_1)(params ItemEstimateRequest[]) | GetItemEstimate komutu, eşitlenmesi gereken sunucudaki bir koleksiyon veya klasördeki öğelerin bir tahminini alır. |
| [ItemOperations](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/itemoperations)(ItemOperationsRequest) | ItemOperations, Fetch, EmptyFolderContents ve Move işlemlerinin toplu çevrimiçi işlenmesini sağlar. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_3)(IEnumerable&lt;MeetingResponseRequest&gt;) | Kullanıcının Gelen Kutusu klasöründeki veya Takvim klasöründeki bir toplantı isteğini kabul eder, geçici olarak kabul eder veya reddeder. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_2)(params MeetingResponseRequest[]) | Kullanıcının Gelen Kutusu klasöründeki veya Takvim klasöründeki bir toplantı isteğini kabul eder, geçici olarak kabul eder veya reddeder. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse)(UserResponse, string, string) | Kullanıcının Gelen Kutusu klasöründeki veya Takvim klasöründeki bir toplantı isteğini kabul eder, geçici olarak kabul eder veya reddeder. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_1)(UserResponse, string, string, string, string) | Kullanıcının Gelen Kutusu klasöründeki veya Takvim klasöründeki bir toplantı isteğini kabul eder, geçici olarak kabul eder veya reddeder. |
| [MoveItem](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitem)(string, string, string) | MoveItems komutu, bir öğeyi veya öğeleri sunucudaki bir klasörden diğerine taşır. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems_1)(IEnumerable&lt;MoveItemData&gt;) | MoveItems komutu, bir öğeyi veya öğeleri sunucudaki bir klasörden diğerine taşır. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems)(params MoveItemData[]) | MoveItems komutu, bir öğeyi veya öğeleri sunucudaki bir klasörden diğerine taşır. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_4)(IEnumerable&lt;PingParameter&gt;) | Ping komutu, istemcinin yeniden eşitlenmesini gerektirecek değişiklikler için sunucunun belirtilen klasörleri izlemesini istemek için kullanılır. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping)(params PingParameter[]) | Ping komutu, istemcinin yeniden eşitlenmesini gerektirecek değişiklikler için sunucunun belirtilen klasörleri izlemesini istemek için kullanılır. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_2)(int, IEnumerable&lt;PingParameter&gt;) | Ping komutu, istemcinin yeniden eşitlenmesini gerektirecek değişiklikler için sunucunun belirtilen klasörleri izlemesini istemek için kullanılır. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_1)(int, params PingParameter[]) | Ping komutu, istemcinin yeniden eşitlenmesini gerektirecek değişiklikler için sunucunun belirtilen klasörleri izlemesini istemek için kullanılır. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_5)(string, FolderClass) | Ping komutu, istemcinin yeniden eşitlenmesini gerektirecek değişiklikler için sunucunun belirtilen klasörleri izlemesini istemek için kullanılır. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_3)(int, string, FolderClass) | Ping komutu, istemcinin yeniden eşitlenmesini gerektirecek değişiklikler için sunucunun belirtilen klasörleri izlemesini istemek için kullanılır. |
| [Provision](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/provision)(ProvisionRequest) | Tedarik komutu, istemci cihazların, yöneticinin belirlediği güvenlik ilkesi ayarlarını sunucudan istemesini sağlar, minimum kişisel kimlik numarası (PIN) parola uzunluğu gereksinimi gibi. |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey)() | Tüm koleksiyonlar için GetItemEstimate ve Sync işlemleri için SyncKeys'i sıfırlayın. |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey_1)(string) | GetItemEstimate için SyncKey'i sıfırlayın ve tanımlı koleksiyon için Sync işlemleri. |
| [ResetFoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetfolderssynckey)() | Klasörlerle yapılan işlemler için SyncKey'i sıfırlayın |
| [ResolveRecipients](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resolverecipients)(ResolveRecipientsRequest) | ResolveRecipients, sağlanan alıcıların listesini çözümlemek, serbest/meşgul bilgilerini almak ve isteğe bağlı olarak, istemcilerin şifreli S/MIME e-posta iletileri gönderebilmesi için S/MIME sertifikalarını almak için kullanılır. Serbest/meşgul bilgilerinin alınması ResolveRecipients komutundaki Availability öğesinin kullanılması, protokol sürümü 12.1. olduğunda desteklenmez. |
| [Search](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/search)(SearchRequest) | Arama, bir adres defterindeki, posta kutusundaki veya belge kitaplığındaki (UNC veya Windows SharePoint Services) girişleri bulmak için kullanılır. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail)(string) | SendMail, istemciler tarafından sunucuya MIME biçimli e-posta iletileri göndermek için kullanılır. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_1)(string, bool) | SendMail, istemciler tarafından sunucuya MIME biçimli e-posta iletileri göndermek için kullanılır. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_2)(string, bool, string) | SendMail, istemciler tarafından sunucuya MIME biçimli e-posta iletileri göndermek için kullanılır. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_3)(string, bool, string, string) | SendMail, istemciler tarafından sunucuya MIME biçimli e-posta iletileri göndermek için kullanılır. |
| [Settings](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/settings)(SettingsRequest) | Ayarlar, kullanıcı için genel özellikler ve İşyeri Dışı (OOF) ayarlarında alma ve ayarlama işlemlerini destekler. Ayarlar ayrıca sunucuya cihaz bilgilerini gönderir, cihaz parolası/kişisel kimlik numarası (PIN) kurtarma işlemini uygular ve kullanıcının e-posta adreslerinin bir listesini alır. |
| [SmartForward](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartforward)(SmartRequest) | SmartForward komutu, istemciler tarafından, sunucudan tam, orijinal mesajı almadan mesajları iletmek için kullanılır. |
| [SmartReply](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartreply)(SmartRequest) | SmartReply komutu, istemciler tarafından, sunucudan orijinal mesajın tamamını almadan mesajları yanıtlamak için kullanılır. |
| [Sync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sync)(SyncRequest) | Senkronizasyon, bir koleksiyondaki değişiklikleri istemci ve sunucu arasında senkronize eder. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert)(IEnumerable&lt;X509Certificate&gt;) | ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_4)(X509Certificate) | ValidateCert komutu, istemci tarafından bir S/MIME postası aracılığıyla alınan bir sertifikayı doğrulamak için kullanılır. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_1)(IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_2)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) | ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_5)(X509Certificate, bool) | ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_6)(X509Certificate, IEnumerable&lt;X509Certificate&gt;) | ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_3)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_7)(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert, istemci tarafından bir S/MIME postası yoluyla alınan bir sertifikayı doğrulamak için kullanılır. |

### Ayrıca bakınız

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
