---
title: Aspose.Email.Clients.ActiveSync.TransportLayer
second_title: Aspose.Email for .NET API Referansı
description: 
type: docs
weight: 80
url: /tr/net/aspose.email.clients.activesync.transportlayer/
---


## sınıflar

| Sınıf | Tanım |
| --- | --- |
| [AccountInformation](./accountinformation) | Kullanıcının hesap bilgilerini içerir. |
| [ActiveSyncTLClient](./activesynctlclient) | ActiveSync istemci uygulamaları için temel sınıf |
| [AutodiscoverResult](./autodiscoverresult) | Otomatik Bulma işleminin sonucu |
| [Body](./body) | Sunucuda depolanan bir öğeyle ilişkili serbest biçimli, değişken uzunluklu bir veri alanını belirtir. |
| [BodyPart](./bodypart) | Bir yanıttaki bir e-postanın mesaj kısmıyla ilgili ayrıntıları belirtir. BodyPartPreference bir istekte belirtildiğinde, BodyPart öğesi bir komut yanıtına dahil edilmelidir ZORUNLU. |
| [BodyPreference](./bodypreference) | Arama, eşitleme veya getirme işlemlerinden döndürülen bilgilerin türü ve boyutuyla ilgili tercih bilgilerini içerir. |
| [CertificateStatuses](./certificatestatuses) | Sertifikanın başarıyla doğrulanıp doğrulanmadığını gösterir. |
| [DataContainer](./datacontainer) | Kişi, e-posta iletisi, takvim randevusu veya görev öğesi gibi belirli bir nesneye ilişkin verileri içerir. DataContainer, öğeleri değiştirmek, öğeleri eklemek veya istemci cihaz veya sunucudaki öğeleri almak için kullanılabilir. |
| [DeviceInformation](./deviceinformation) | İstemci aygıtının özelliklerini sunucuya göndermek için kullanılan istek. |
| [DevicePasswordRequest](./devicepasswordrequest) | Sunucu tarafından istemci cihazının kurtarma parolasını belirleme isteğini belirtir. Mevcut bir kurtarma parolasını temizlemek için istemci boş bir Parola GÖNDERMELİDİR. |
| [EASProvisionDoc](./easprovisiondoc) | Cihaz sağlama için güvenlik ayarları koleksiyonunu belirtir. |
| [EmptyFolderContentsRequest](./emptyfoldercontentsrequest) | Bir klasörün içeriğinin silinmesiyle ilgili isteği içerir. EmptyFolderContents, Seçenekler öğesinin tek bir alt öğesini, klasörde bulunan alt klasörlerin silinip silinmeyeceğini belirleyen DeleteSubFolders öğesini destekler. İstekte DeleteSubFolders seçeneği yoksa, belirtilen CollectionId'nin alt klasörleri silinmez. |
| [FolderInfo](./folderinfo) | FolderInfo sınıfı, klasör bilgilerini içerir |
| [FolderSyncResult](./foldersyncresult) | Klasör hiyerarşisindeki değişiklikleri içerir. |
| [ItemEstimate](./itemestimate) | İstenen klasörde bir değerlendirme içerir |
| [ItemEstimateOptions](./itemestimateoptions) | GetItemEstimate işleminin sonuçlarını filtreleyen öğeleri içerir. |
| [ItemEstimateRequest](./itemestimaterequest) | ItemEstimate istek parametrelerini içerir |
| [ItemOperationsEmptFldrCntntsResponce](./itemoperationsemptfldrcntntsresponce) | Bir klasörün içeriğini silen işlemi içeren yanıtın gövdesini tanımlar. |
| [ItemOperationsFetchProperties](./itemoperationsfetchproperties) | Yanıttaki öğeler için döndürülen özellikleri içerir. |
| [ItemOperationsFetchRequest](./itemoperationsfetchrequest) | Sunucudan bir öğenin alınmasıyla ilgili isteği içerir. |
| [ItemOperationsFetchResponce](./itemoperationsfetchresponce) | Sunucudan bir öğenin alınmasıyla ilgili yanıtı içerir. |
| [ItemOperationsMoveRequest](./itemoperationsmoverequest) | Bir konuşmayı belirli bir klasöre taşıma isteğini içerir. |
| [ItemOperationsMoveResponce](./itemoperationsmoveresponce) | Belirli bir konuşmayı hareket ettiren işlemi içeren yanıtın gövdesini tanımlar. |
| [ItemOperationsRequest](./itemoperationsrequest) | ItemOperations isteğini içerir. |
| [ItemOperationsResponse](./itemoperationsresponse) | ItemOperations yanıtını içerir. |
| [ItOpEmpFldCntOptions](./itopempfldcntoptions) | ItemOperations.EmptyFolderContents işlemi için seçenekleri içerir |
| [ItOpFetchOptions](./itopfetchoptions) | ItemOperations.Fetch işlemi için seçenekleri içerir. |
| [ItOpMoveOptions](./itopmoveoptions) | ItemOperations.Move işlemi için seçenekleri içerir. |
| [MeetingResponseRequest](./meetingresponserequest) | Yanıtlanmakta olan toplantı isteğini, bu toplantı isteğine verilen yanıtı ve toplantı isteğinin bulunduğu sunucudaki klasörü belirtir. |
| [MeetingResponseResult](./meetingresponseresult) | Toplantı yanıtı sonucu object |
| [MoveItemData](./moveitemdata) | Öğelerin taşınmasıyla ilgili bilgileri içerir |
| [MoveItemResponse](./moveitemresponse) | Taşınan öğeleri açıklayan bilgileri içerir. |
| [OOFMessage](./oofmessage) | Belirli bir hedef kitle için OOF mesajını belirtir. Exchange 2007, Exchange 2010 ve Exchange 2013, bilinmeyen harici ve bilinen harici kitleler için yanıt mesajının aynı olmasını gerektirir. Özellik, bir OOF mesajı için aşağıdaki üç kitleyi destekler: Dahili — Gönderen kullanıcıyla aynı kuruluşta bulunan bir kullanıcı. Bilinen harici — Gönderen kullanıcının kuruluşu dışında bulunan ancak gönderen kullanıcının kişilerinde temsil edilen bir kullanıcı. Bilinmeyen harici — Gönderen kullanıcının dışında olan bir kullanıcı kuruluştur ve gönderen kullanıcının kişilerinde temsil edilmez. |
| [OOFReqParametrs](./oofreqparametrs) | Sunucudan OOF bilgi ayarlarını alır. |
| [OOFRequest](./oofrequest) | İşyeri Dışı (OOF) bilgilerinin alınması ve ayarlanması için bir sınıf belirtir. |
| [OOFResponse](./oofresponse) | İşyeri Dışı (OOF) bilgilerinin alınması ve ayarlanması için bir sınıf belirtir. |
| [OOFSettings](./oofsettings) | OOF bilgi ayarları. |
| [PictureRequest](./picturerequest) | İstemcinin sunucu yanıtında fotoğrafların döndürülmesini istediğini belirtir. Protokol sürümü 12.1 veya 14.0 olduğunda Resim desteklenmez. Fotoğraf isteğiyle ilgili verileri içerir. |
| [PictureRespose](./picturerespose) | Kişi fotoğraflarıyla ilgili verileri içerir. Protokol sürümü 12.1 veya 14.0. olduğunda Resim desteklenmez. |
| [PingParameter](./pingparameter) | Ping komutu parametreleri 'yi içerir |
| [ProvisionPolicy](./provisionpolicy) | Bir güvenlik politikası belirtir. |
| [ProvisionPolicyData](./provisionpolicydata) | Bir ilkenin ayarlarını belirtir. |
| [ProvisionRequest](./provisionrequest) | Tedarik için istek bilgilerini içerir command |
| [ProvisionResponse](./provisionresponse) | Tedarik komutu için yanıt bilgilerini içerir |
| [QueryType](./querytype) | Aranan mağazadaki girişleri eşleştirmek için kullanılacak anahtar sözcükleri belirtir. Sorgunun değeri, önek-dize eşleştirme modeli olarak kullanılır ve dizenin başlangıcıyla eşleşen girişleri döndürür. Örneğin, "John" araması "John Frum" veya "Barry Johnson" ile eşleşir, ancak "James Littlejohn" ile eşleşmez. GAL'de ANR kullanılarak dizine eklenen boş olmayan tüm metin özellikleri Sorgu öğesiyle karşılaştırılır değer. Arama karşılaştırmaları, büyük/küçük harfe duyarlı olmayan eşleme kullanılarak gerçekleştirilir. Windows SharePoint Services belge kitaplığı araması için bu protokol aşağıdaki biçimdeki sorguları destekler: LinkId == değer, burada değer, öğenin veya klasörün URL'sini ve LinkId'nin gösterdiği değerin bağlantı kimliği özelliğiyle karşılaştırılacağını belirtir. Posta kutusu araması için sorgu sözdizimi aşağıdaki gibidir: - Klasörler aşağıdaki şekillerde belirtilebilir: Belirtilen Kimlik Belirtilen klasör ve alt klasörler Taslak dahil tüm e-posta klasörleri, Gelen kutusu ve alt klasörler, Giden Kutusu ve Gönderilmiş Öğeler - Temel anahtar kelime sorgusu aşağıdakilerden oluşabilir: Temel işleç: Ve (bölüm 2.2.3.10) BüyükTer (bölüm 2.2.3.78) ve KüçükTan kullanılarak belirtilen bir tarihsaat filtresi öğeler (bölüm 2.2.3.87) Anahtar sözcükleri içeren Serbest Metin öğeleri (bölüm 2.2.3.73) Temel anahtar sözcük sorgusu, dizine alınmış tüm özelliklere karşı yürütülür. |
| [Recipient](./recipient) | Çözümlenmiş tek bir alıcıyı temsil eder. |
| [ResolveRecipientsAvailabilityRequest](./resolverecipientsavailabilityrequest) | Sunucuya, istemci tarafından serbest/meşgul verilerinin istendiğini belirtir ve alınacak serbest/meşgul verilerinin başlangıç ve bitiş zamanını tanımlar. Protokol sürümü 12.1. olduğunda Kullanılabilirlik desteklenmez. |
| [ResolveRecipientsAvailabilityResponse](./resolverecipientsavailabilityresponse) | StartTime ve EndTime tarafından tanımlanan süre için istekte tanımlanan kullanıcıların veya dağıtım listelerinin durumunu ve serbest/meşgul verilerini tanımlar. Kullanılabilirlik bir ResolveRecipients isteğine dahil edildiğinde, sunucu tanımlanan kullanıcılar için serbest/meşgul bilgilerini alır İsteğe dahil edilen Kime öğelerinde bulunur ve yanıtta MergedFreeBusy'deki serbest/meşgul bilgilerini döndürür. Sunucu isteği ayrıştırdığında, sunucu önce Kime öğeleri tarafından tanımlanan alıcıları çözümler ve ardından MergedFreeBusy'deki serbest/meşgul verilerini döndürmeden önce, belirtilen zaman aralığı için kullanıcıların serbest/meşgul bilgilerini belirler. |
| [ResolveRecipientsCertificates](./resolverecipientscertificates) | Bir alıcının sertifikaları hakkında bilgi içerir. |
| [ResolveRecipientsOptions](./resolverecipientsoptions) | Alıcı listesini çözümleme seçeneklerini içerir. |
| [ResolveRecipientsRequest](./resolverecipientsrequest) | Alıcıları çözümlemek için bilgiler içerir. |
| [ResolveRecipientsResponse](./resolverecipientsresponse) | Alıcının çözümlenip çözümlenmediğine ilişkin bilgileri içerir. Alıcı çözümlendiyse, alıcının türünü, alıcının çözümlediği e-posta adresini ve isteğe bağlı olarak alıcının S/MIME sertifikasını da içerir. |
| [RightsManagementInformationResponce](./rightsmanagementinformationresponce) | Sunucudan alınan hak yönetimi bilgileri ayarlarını içerir. |
| [RightsManagementLicense](./rightsmanagementlicense) | Eşitlenmekte olan e-posta iletisine uygulanan şablon için hak ilkesi şablon ayarlarını içerir. |
| [RightsManagementTemplate](./rightsmanagementtemplate) | İstemcide bulunan bir hak ilkesi şablonunun şablon tanımlayıcısını, adını ve açıklamasını içerir. |
| [SearchCondition](./searchcondition) | Arama istekleri için bir koşul belirtir |
| [SearchOptions](./searchoptions) | Arama seçeneklerini içerir. KullanıcıAdı ve Parola, yalnızca 14 Durum değeri alındıktan sonra istekte gönderilebilir. Sunucu, istenen kaynaklara erişmek için bu kimlik bilgilerini gerektirir. İstemci bunları yalnızca güvenli veya güvenilir bir bağlantı üzerinden ve yalnızca 14 Durum değerine yanıt olarak göndermesi ZORUNLUDUR. Desteklenen seçenekler aranmakta olan mağazaya göre değişir. Aşağıdaki tablo, her mağaza için geçerli seçenekleri listeler. GAL: Aralık, KullanıcıAdı, Parola, Picture Posta Kutusu: Aralık, DeepTraversal, RebuildResults, BodyPreference, BodyPartPreference, RightsManagementSupport DocumentLibrary: Aralık, KullanıcıAdı, Parola SearchPreference'da yalnızca BodyPart geçerlidir ConversationId. içeren komut istekleri |
| [SearchQuery](./searchquery) | Aranan mağazadaki girişleri eşleştirmek için kullanılacak anahtar sözcükleri belirtir. Sorgunun değeri, önek-dize eşleştirme modeli olarak kullanılır ve dizenin başlangıcıyla eşleşen girişleri döndürür. Örneğin, "John" araması "John Frum" veya "Barry Johnson" ile eşleşir, ancak "James Littlejohn" ile eşleşmez. GAL'de ANR kullanılarak dizine eklenen boş olmayan tüm metin özellikleri Sorgu öğesiyle karşılaştırılır değer. Arama karşılaştırmaları, büyük/küçük harfe duyarlı olmayan eşleştirme kullanılarak gerçekleştirilir. Bir Windows SharePoint Services belge kitaplığı araması için, bu protokol aşağıdaki biçimdeki sorguları destekler: LinkId == değer, burada değer, öğenin veya klasörün URL'sini belirtir ve LinkId şunu belirtir değerin bağlantı kimliği özelliğiyle karşılaştırılacağını belirtir. Posta kutusu araması için sorgu sözdizimi aşağıdaki gibidir: - Klasörler aşağıdaki şekillerde belirtilebilir: Belirtilen Kimlik Belirtilen klasör ve alt klasörler Taslak dahil tüm e-posta klasörleri, Gelen kutusu ve alt klasörler, Giden Kutusu ve Gönderilmiş Öğeler - Temel anahtar kelime sorgusu aşağıdakilerden oluşabilir: Temel işleç: Ve (bölüm 2.2.3.10) BüyükTer (bölüm 2.2.3.78) ve KüçükTan kullanılarak belirtilen bir tarihsaat filtresi öğeler (bölüm 2.2.3.87) Anahtar sözcükleri içeren Serbest Metin öğeleri (bölüm 2.2.3.73) Temel anahtar sözcük sorgusu, dizine alınmış tüm özelliklere karşı yürütülür. |
| [SearchRequest](./searchrequest) | Arama isteği bilgilerini içerir |
| [SearchRequestStore](./searchrequeststore) | Arama için adı, sorguyu ve seçenekleri belirtin. |
| [SearchResponse](./searchresponse) | Arama yanıtı bilgilerini içerir |
| [SearchResponseStore](./searchresponsestore) | Döndürülen posta kutusu girişleri için Durum, Sonuç, Aralık ve Toplam öğelerini içerir. |
| [SearchResult](./searchresult) | Eşleşen tek bir posta kutusu öğesi için kapsayıcı. Aranan mağaza posta kutusu olduğunda: - Posta kutusunda bulunan her eşleşme için bir Sonuç öğesi vardır. Hiçbir eşleşme bulunamazsa, XML yanıtının Store kapsayıcı öğesinde boş bir Sonuç öğesi bulunur. - Sonuç öğesinin içinde, Özellikler öğesi posta kutusu öğesi için istenen özelliklerin bir listesini içerir. aranmakta olan belge kitaplığıdır: - Arama yanıtında döndürülen ilk sonuç, LinkId değerinin işaret ettiği Kök klasör veya öğenin meta verileridir. İstemci, gerektirmiyorsa bu girişi yoksaymayı seçebilir. - İstekteki Documentlibrary:LinkId öğesi değeri bir klasörü işaret ediyorsa, klasörün meta veri özellikleri ilk öğe olarak döndürülür ve içeriğin içeriği döndürülür. klasör sonraki sonuçlar olarak döndürülür. Aralık, hiçbir fark olmaksızın bu sonuçlara uygulanır; örneğin, 0 dizini her zaman bağlantının işaret ettiği kök öğe için olacaktır. - İstekteki Documentlibrary:LinkId öğesi değeri bir öğeyi işaret ediyorsa, yalnızca bir sonuç döndürülür: öğenin meta verileri. - Sonuç öğesinin içinde, Özellikler öğesi, posta kutusu öğesi için istenen özelliklerin bir listesini içerir. |
| [SearchResultProperties](./searchresultproperties) | Arama komutu yanıtı Özellikleri, Sorgu öğesi arama dizesiyle eşleşen tek bir girişe uygulanan özellikler için bir kapsayıcıdır. Örneğin, Özellikler öğesi, eşleşen GAL girişine eklenen her boş olmayan, metin değerli GAL özelliği için bir öğe içerir. Yalnızca belirli GAL girişine eklenen özellikler döndürülür; bu nedenle, farklı eşleşen GAL girişleri için yanıt XML'inde farklı özellik kümeleri döndürülebilir. Özellikler kapsayıcısındaki her öğenin kapsamı, üst düzey Arama öğesinde belirtilen uygun ad alanına göre belirlenir. |
| [ServerInfo](./serverinfo) | Otomatik Bulma işleminde sunucu ayarları |
| [SettingsRequest](./settingsrequest) | Ayarlar komutu, kullanıcı için genel özellikler ve İşyeri Dışı (OOF) ayarlarında alma ve ayarlama işlemlerini destekler. Ayarlar komutu ayrıca sunucuya cihaz bilgilerini gönderir, cihaz parolası/kişisel kimlik numarası (PIN) kurtarma işlemini uygular ve kullanıcının e-posta adreslerinin bir listesini alır. |
| [SettingsResponse](./settingsresponse) | Ofis Dışı (OOF) ayarları ve kullanıcı hesaplarının listesi ile bir yanıt belirtir. |
| [SmartRequest](./smartrequest) | Akıllı istek bilgilerini içerir |
| [SmartRequestSource](./smartrequestsource) | Kaynak mesajla ilgili bilgileri içerir. |
| [Status](./status) | Bir işlemin sonucunu gösterir. |
| [SyncAddClientOperation](./syncaddclientoperation) | İstemcideki bir koleksiyonda yeni bir nesne oluşturur. |
| [SyncAddResponse](./syncaddresponse) | Bir koleksiyonda yeni bir nesnenin oluşturulması gerektiğini belirtmek için kullanılır. |
| [SyncAddServerOperation](./syncaddserveroperation) | Sunucudaki bir koleksiyonda yeni bir nesne oluşturur. |
| [SyncChangeClientOperation](./syncchangeclientoperation) | İstemci aygıtında değiştirilmiş olan mevcut bir nesnenin özelliklerini içerir. Değiştirilen nesne, ServerId öğesiyle tanımlanır. |
| [SyncChangeResponse](./syncchangeresponse) | Bir nesnenin değiştirildiğini belirtmek için kullanılır. |
| [SyncChangeServerOperation](./syncchangeserveroperation) | Sunucuda değiştirilmiş olan mevcut bir nesnenin özelliklerini içerir. Değiştirilen nesne, ServerId öğesiyle tanımlanır. |
| [SyncCollectionRequest](./synccollectionrequest) | Sınıf, belirli bir koleksiyona uygulanan komutları ve seçenekleri içerir. |
| [SyncCollectionResponse](./synccollectionresponse) | Sınıf, bir Senkronizasyon yanıtı için geçerli olan komutları ve seçenekleri içerir. |
| [SyncCommandsRequest](./synccommandsrequest) | Bir koleksiyona uygulanan işlemleri içerir. Kullanılabilir işlemler Ekle, Sil, Değiştir, Al ve SoftDelete'dir. |
| [SyncCommandsResponse](./synccommandsresponse) | Bir koleksiyona uygulanan işlemleri içerir. Kullanılabilir işlemler Ekle, Sil, Değiştir, Al ve SoftDelete'dir. |
| [SyncDeleteClientOperation](./syncdeleteclientoperation) | İstemci cihazdaki veya sunucudaki bir nesneyi siler. Nesne, ServerId. tarafından tanımlanır |
| [SyncFetchResponse](./syncfetchresponse) | Sunucudan bir eşitleme yanıtında kesilen bir öğenin uygulama verilerini ister. |
| [SyncOperationResponse](./syncoperationresponse) | Senkronizasyon işlemi yanıtları için temel soyut sınıf |
| [SyncOperationsResponse](./syncoperationsresponse) | Sunucu tarafından işlenen Ekle, Getir, Değiştir gibi işlemlere verilen yanıtları içerir. Yanıt, işleme bağlı olarak bir durum kodu ve diğer bilgileri içerir. |
| [SyncOptions](./syncoptions) | Senkronizasyonun nasıl gerçekleştirildiğinin belirli yönlerini kontrol eden seçenekleri belirtir. |
| [SyncRequest](./syncrequest) | Senkronizasyon isteği parametrelerini içerir |
| [UserInformationResponse](./userinformationresponse) | İsteğin durumunu ve bir kullanıcının hesap bilgilerinin (e-posta adresleri) listesini içerir. |
| [ValueConverter](./valueconverter) | Sınıfı, ActiveSync protokol sürümünü dize temsilinden numaralandırmaya ve geriye dönüştürür. |
## Arayüzler

| Arayüz | Tanım |
| --- | --- |
| [IActiveSyncTLClient](./iactivesynctlclient) | ActiveSync istemci arabirimi |
| [IBaseActiveSyncTLClient](./ibaseactivesynctlclient) | Temel ActiveSync istemci arabirimi |
## numaralandırma

| numaralandırma | Tanım |
| --- | --- |
| [ActiveSyncAuthenticationType](./activesyncauthenticationtype) | Numaralandırma, kimlik doğrulama türünü belirtir |
| [AirSync](./airsync) | ActiveSync protokolünün AirSync ad alanı |
| [AirSyncBase](./airsyncbase) | ActiveSync protokolünün AirSyncBase ad alanı |
| [AirsyncClass](./airsyncclass) | Öğenin sınıfını tanımlar. Protokol sürümü 12.1 olduğunda posta kutusu aramaları için aşağıdaki sınıflar desteklenir: - Email - Calendar - Contacts - Tasks SMS ve Notes sınıfları yalnızca protokol sürümü 14.0 veya 14.1 ise kullanılabilir. |
| [AirsyncFilterType](./airsyncfiltertype) | nesneleri için isteğe bağlı bir zaman aralığı belirtir |
| [AllowBluetooth](./allowbluetooth) | Cihazda Bluetooth kullanımını belirtir. |
| [ASProtocolVersions](./asprotocolversions) | ASProtocolVersions, ActiveSync protokolünün sürümlerini gösterir. |
| [BehaviorReplacement](./behaviorreplacement) | Hem istemcide hem de sunucuda bir nesne değiştirildiğinde oluşan çakışmanın nasıl çözüleceğini belirtir. Değer, bir çakışma olması durumunda hangi nesnenin (istemci nesnesi veya sunucu nesnesi) tutulacağını belirtir. |
| [BodyType](./bodytype) | Öğenin gövde içeriğinin biçim türünü belirtir. |
| [Calendar](./calendar) | ActiveSync protokolünün takvim ad alanı |
| [CertificateRetrieval](./certificateretrieval) | Çözümlenen her alıcı için S/MIME sertifikalarının sunucu tarafından döndürülmesi GEREKLİ olup olmadığını belirtir. |
| [CommandCodes](./commandcodes) | Aşağıdaki tablo, ActiveSync komutlarına karşılık gelen sayısal kodları sağlar. Sayısal kod, komutu belirtmek için base64 kodlu URI'nin Komut kodu alanında kullanılır. |
| [CommandParameters](./commandparameters) | Komut parametreleri. |
| [ComposeMail](./composemail) | ActiveSync protokolünün ComposeMail ad alanı |
| [Contacts](./contacts) | ActiveSync protokolünün Kişiler ad alanı |
| [Contacts2](./contacts2) | ActiveSync protokolünün Contacts2 ad alanı |
| [DocumentLibrary](./documentlibrary) | ActiveSync protokolünün DocumentLibrary ad alanı |
| [Email](./email) | ActiveSync protokolünün e-posta ad alanı |
| [Email2](./email2) | ActiveSync protokolünün Email2 ad alanı |
| [EncryptionSMIMEAlgorithm](./encryptionsmimealgorithm) | S/MIME mesajlarını şifrelerken kullanılan algoritmayı belirtir. |
| [FolderClass](./folderclass) | İzlenecek klasörün içerik sınıfını belirtir. |
| [FolderHierarchy](./folderhierarchy) | ActiveSync protokolünün KlasörHiyerarşi ad alanı |
| [FolderTypes](./foldertypes) | Sunucuda güncellenen (yeniden adlandırılan veya taşınan) veya eklenen klasörün türünü belirtir. |
| [GAL](./gal) | ActiveSync protokolünün GAL ad alanı |
| [GetItemEstimate](./getitemestimate) | GetItem ActiveSync protokolünün ad alanını tahmin edin |
| [ItemOperations](./itemoperations) | ActiveSync protokolünün ItemOperations ad alanı |
| [MaxAgeFilter](./maxagefilter) | Senkronize edilebilecek maksimum takvim günü sayısını belirtir. |
| [MeetingResponse](./meetingresponse) | ActiveSync protokolünün MeetingResponse ad alanı |
| [MergedFreeBusy](./mergedfreebusy) | Kullanıcılar veya dağıtım listesi için serbest/meşgul bilgilerini belirtir. |
| [MIMESupport](./mimesupport) | Sunucudan istemciye gönderilen e-posta öğeleri için MIME desteğini etkinleştirir. |
| [MIMETruncation](./mimetruncation) | E-posta öğesinin MIME verilerinin, sunucudan istemciye gönderildiğinde kesilip kesilmemesi gerektiğini belirtir. |
| [MinDevicePasswordComplexCharacters](./mindevicepasswordcomplexcharacters) | İstemci parolasının gerekli karmaşıklık düzeyini belirtir. Örneğin: MinDevicePasswordComplexCharacters değeri 2 ise, hem büyük hem de küçük alfabetik karakterlere sahip bir parola, küçük harfli alfabetik karakterlere sahip bir parola yeterli olacaktır. ve sayılar. |
| [Move](./move) | ActiveSync protokolünün ad alanını taşıyın |
| [Namespace](./namespace) | ActiveSync Kod Sayfaları |
| [Notes](./notes) | ActiveSync protokolünün Notes ad alanı |
| [OofState](./oofstate) | Oof özelliğinin kullanılabilirliğini belirtir. |
| [Ping](./ping) | ActiveSync protokolünün ping ad alanı |
| [Provision](./provision) | ActiveSync protokolünün ad alanını sağlayın |
| [ProvisionPolicyStatuses](./provisionpolicystatuses) | Değer, istemcinin sunucudan alınan ilke ayarlarını uygulama başarısını veya başarısızlığını gösterir. |
| [ProvisionRemoteWipeStatuses](./provisionremotewipestatuses) | Değer, istemcide uzaktan silme işleminin başarısını veya başarısızlığını gösterir. |
| [RecipientType](./recipienttype) | Alıcının türünü belirtir. |
| [ResolveRecipients](./resolverecipients) | ActiveSync protokolünün ResolveRecipients ad alanı |
| [RightsManagement](./rightsmanagement) | ActiveSync protokolünün RightsManagement ad alanı |
| [Search](./search) | ActiveSync protokolünün ad alanını arayın |
| [ServerType](./servertype) | Sunucu tipini belirtir |
| [Settings](./settings) | ActiveSync protokolünün ayarlar ad alanı |
| [SignedSMIMEAlgorithm](./signedsmimealgorithm) | S/MIME iletilerini imzalarken kullanılan algoritmayı belirtir. |
| [SMIMEEncryptionAlgorithmNegotiation](./smimeencryptionalgorithmnegotiation) | Şifreleme algoritmasının anlaşmasını kontrol eder. |
| [StoreType](./storetype) | İşlemler için konumu belirten enfarmasyon içerir. |
| [Tasks](./tasks) | ActiveSync protokolünün görev ad alanı |
| [UserCreatedFolderTypes](./usercreatedfoldertypes) | Oluşturulacak klasörün türünü belirtir. |
| [UserResponse](./userresponse) | Toplantının kabul edildiğini, geçici olarak kabul edildiğini veya reddedildiğini gösterir. |
| [ValidateCert](./validatecert) | ActiveSync protokolünün ValidateCert ad alanı |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
