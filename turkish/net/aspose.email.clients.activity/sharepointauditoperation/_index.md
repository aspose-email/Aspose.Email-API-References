---
title: SharePointAuditOperation
second_title: Aspose.Email for .NET API Referansı
description: SharePoint denetim işlemleri
type: docs
weight: 2760
url: /tr/net/aspose.email.clients.activity/sharepointauditoperation/
---
## SharePointAuditOperation enumeration

SharePoint denetim işlemleri

```csharp
public enum SharePointAuditOperation
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| AccessInvitationAccepted | `0` | Bu işlem Önizleme'dedir. Paylaşılan bir dosyayı (veya klasörü) görüntüleme veya düzenleme davetinin alıcısı, davetteki bağlantıya tıklayarak paylaşılan dosyaya erişmiştir. |
| AccessInvitationCreated | `1` | Bu işlem Önizleme'dedir. Kullanıcı, SharePoint veya OneDrive İş sitesinde paylaşılan bir dosya veya klasörü görüntülemek veya düzenlemek için başka bir kişiye (kuruluşunun içinden veya dışından) bir davet gönderir. Etkinlik girişinin ayrıntıları, paylaşılan dosyanın adını, davetin gönderildiği kullanıcıyı, ve daveti gönderen kişi tarafından seçilen paylaşım izninin türünü tanımlar. |
| AccessInvitationExpired | `2` | Bu işlem Önizleme'dedir. Harici bir kullanıcıya gönderilen davetiyenin süresi dolar. Varsayılan olarak, kuruluşunuz dışından bir kullanıcıya gönderilen davetiyenin süresi, davetin kabul edilmemesi durumunda 7 gün sonra sona erer. |
| AccessInvitationRevoked | `3` | Bu işlem Önizleme'dedir. SharePoint veya OneDrive İş'teki bir sitenin veya belgenin site yöneticisi veya sahibi, kuruluşunuzun dışındaki bir kullanıcıya gönderilen davetiyeyi geri çeker. Bir davet, yalnızca kabul edilmeden önce geri çekilebilir. |
| AccessInvitationUpdated | `4` | Bu işlem Önizleme'dedir. SharePoint veya OneDrive İş sitesinde paylaşılan bir dosyayı (veya klasörü) görüntülemek veya düzenlemek için başka bir kişiye davetiye oluşturup gönderen kullanıcı daveti yeniden gönderir. |
| AccessRequestApproved | `5` | SharePoint veya OneDrive İş'teki bir sitenin veya belgenin site yöneticisi veya sahibi, siteye veya belgeye erişim için bir kullanıcı isteğini onaylar. |
| AccessRequestCreated | `6` | Kullanıcı, SharePoint veya OneDrive İş'te erişim izninin olmadığı bir siteye veya belgeye erişim ister. |
| AccessRequestRejected | `7` | Bu işlem Önizleme'dedir. SharePoint'teki bir sitenin veya belgenin site yöneticisi veya sahibi, kullanıcının siteye veya belgeye erişme isteğini reddediyor. |
| ActivationEnabled | `8` | Bu işlem Önizleme'dedir. Kullanıcılar, form kodu içermeyen, tam güven gerektiren, mobil cihazda oluşturmayı etkinleştiren veya bir sunucu yöneticisi tarafından yönetilen bir veri bağlantısını kullanan form şablonlarını tarayıcıda etkinleştirebilir. |
| AdministratorAddedToTermStore | `9` | Bu işlem Önizleme'dedir. Dönem deposu yöneticisi eklendi. |
| AdministratorDeletedFromTermStore | `10` | Bu işlem Önizleme'dedir. Dönem deposu yöneticisi silindi. |
| AllowGroupCreationSet | `11` | Bu işlem Önizleme'dedir. Site yöneticisi veya sahibi, bir SharePoint veya OneDrive İş sitesine, bu izne atanan bir kullanıcının o site için bir grup oluşturmasına izin veren bir izin düzeyi ekler. |
| AppCatalogCreated | `12` | Bu işlem Önizleme'dedir. Özel iş uygulamalarını SharePoint Ortamınız için kullanılabilir hale getirmek için oluşturulan uygulama kataloğu. |
| AuditPolicyRemoved | `13` | Bu işlem Önizleme'dedir. Bir site koleksiyonu için Belge Yaşam Döngüsü İlkesi kaldırıldı. |
| AuditPolicyUpdate | `14` | Bu işlem Önizleme'dedir. Belge Yaşam Döngüsü İlkesi bir site koleksiyonu için güncellendi. |
| AzureStreamingEnabledSet | `15` | Bu işlem Önizleme'dedir. Bir video portalı sahibi, Azure'dan video akışına izin verdi. |
| CollaborationTypeModified | `16` | Bu işlem Önizleme'dedir. Sitelerde izin verilen işbirliği türü (örneğin intranet, extranet veya genel) değiştirildi. |
| ConnectedSiteSettingModified | `17` | Kullanıcı bir proje ile proje sitesi arasındaki bağlantıyı oluşturmuş, değiştirmiş veya silmiş ya da kullanıcı Project Web App'te bağlantıdaki senkronizasyon ayarını değiştirmiştir. |
| CreateSSOApplication | `18` | Bu işlem Önizleme'dedir. Güvenli mağaza hizmetinde oluşturulan hedef uygulama. |
| CustomFieldOrLookupTableCreated | `19` | Kullanıcı, Project Web App'te özel bir arkadaş veya arama tablosu/öğesi oluşturdu. |
| CustomFieldOrLookupTableDeleted | `20` | Kullanıcı, Project Web App'te özel bir alanı veya arama tablosunu/öğesini sildi. |
| CustomFieldOrLookupTableModified | `21` | Kullanıcı, Project Web App'te özel bir alanı veya arama tablosunu/öğesini değiştirdi. |
| CustomizeExemptUsers | `22` | Bu işlem Önizleme'dedir. Genel yönetici, SharePoint yönetim merkezinde muaf kullanıcı aracılarının listesini özelleştirdi. Dizine alınacak bir Web sayfasının tamamını almaktan hangi kullanıcı aracılarının muaf tutulacağını belirtebilirsiniz. Bu, muaf olarak belirttiğiniz bir kullanıcı aracısı bir InfoPath formuyla karşılaştığında, formun tüm Web sayfası yerine bir XML dosyası olarak döndürüleceği anlamına gelir. Bu, InfoPath formlarının daha hızlı dizine eklenmesini sağlar. |
| DefaultLanguageChangedInTermStore | `23` | Bu işlem Önizleme'dedir. Terminoloji deposunda dil ayarı değişti. |
| DelegateModified | `24` | Kullanıcı, Project Web App'te bir güvenlik temsilcisi oluşturdu veya değiştirdi. |
| DelegateRemoved | `25` | Kullanıcı, Project Web App'te bir güvenlik temsilcisini sildi. |
| DeleteSSOApplication | `26` | Bu işlem Önizleme'dedir. Bir TOA uygulaması silindi. |
| eDiscoveryHoldApplied | `27` | Bu işlem Önizleme'dedir. Bir içerik kaynağına Yerinde Bekletme uygulandı. Yerinde Muhafazalar, SharePoint'te bir eDiscovery site koleksiyonu (eDiscovery Center gibi) kullanılarak yönetilir. |
| eDiscoveryHoldRemoved | `28` | Bu işlem Önizleme'dedir. Bir içerik kaynağından Yerinde Bekletme kaldırıldı. Yerinde Muhafazalar, SharePoint'te bir eDiscovery site koleksiyonu (eDiscovery Center gibi) kullanılarak yönetilir. |
| eDiscoverySearchPerformed | `29` | Bu işlem Önizleme'dedir. SharePoint'te bir eKeşif site koleksiyonu kullanılarak bir eKeşif araması yapıldı. |
| EngagementAccepted | `30` | Kullanıcı, Project Web App'te bir kaynak katılımını kabul eder. |
| EngagementModified | `31` | Kullanıcı, Project Web App'te bir kaynak etkileşimini değiştirir. |
| EngagementRejected | `32` | Kullanıcı, Project Web App'te bir kaynak katılımını reddediyor. |
| EnterpriseCalendarModified | `33` | Kullanıcı, Project Web App'te bir kurumsal takvimi kopyalar, değiştirir veya siler. |
| EntityDeleted | `34` | Kullanıcı, Project Web App'te bir zaman çizelgesini siler. |
| EntityForceCheckedIn | `35` | Kullanıcı, Project Web App'te bir takvimde, özel alanda veya arama tablosunda bir iade işlemi yapmaya zorlar. |
| ExemptUserAgentSet | `36` | Bu işlem Önizleme'dedir. Genel yönetici, SharePoint yönetim merkezindeki muaf kullanıcı aracıları listesine bir kullanıcı aracısı ekler. |
| FileAccessed | `37` | Kullanıcı veya sistem hesabı, bir SharePoint veya OneDrive İş sitesindeki bir dosyaya erişir. Sistem hesapları ayrıca FileAccessed olayları da oluşturabilir. |
| FileCheckOutDiscarded | `38` | Bu işlem Önizleme'dedir. Kullanıcı, teslim alınmış bir dosyayı atar (veya geri alır). Bu, teslim alındığında dosyada yapılan tüm değişikliklerin atıldığı ve belge kitaplığındaki belge sürümüne kaydedilmediği anlamına gelir. |
| FileCheckedIn | `39` | Bu işlem Önizleme'dedir. Kullanıcı, bir SharePoint veya OneDrive İş belge kitaplığından teslim aldığı bir belgeyi teslim eder. |
| FileCheckedOut | `40` | Bu işlem Önizleme'dedir. Kullanıcı, SharePoint veya OneDrive İş belge kitaplığında bulunan bir belgeyi teslim alır. Kullanıcılar, kendileriyle paylaşılan belgeleri teslim alabilir ve bu belgelerde değişiklik yapabilir. |
| FileCopied | `41` | Kullanıcı, bir SharePoint veya OneDrive İş sitesinden bir belge kopyalar. Kopyalanan dosya sitedeki başka bir klasöre kaydedilebilir. |
| FileDeleted | `42` | Kullanıcı, bir SharePoint veya OneDrive İş sitesinden bir belge siler. |
| FileDeletedFirstStageRecycleBin | `43` | Kullanıcı, SharePoint veya OneDrive İş sitesindeki geri dönüşüm kutusundan bir dosya siler. |
| FileDeletedSecondStageRecycleBin | `44` | Kullanıcı, bir SharePoint veya OneDrive İş sitesinde ikinci aşama geri dönüşüm kutusundan bir dosya siler. |
| FileDownloaded | `45` | Kullanıcı, bir SharePoint veya OneDrive İş sitesinden bir belge indirir. |
| FileFetched | `46` | Bu olay FileAccessed olayı ile değiştirildi ve kullanımdan kaldırıldı. |
| FileModified | `47` | Kullanıcı veya sistem hesabı, SharePoint veya OneDrive İş sitesinde bulunan bir belgenin içeriğini veya özelliklerini değiştirir. |
| FileMoved | `48` | Kullanıcı, bir belgeyi SharePoint veya OneDrive İş sitesindeki geçerli konumundan yeni bir konuma taşır. |
| FilePreviewed | `49` | Kullanıcı, bir SharePoint veya OneDrive İş sitesindeki bir belgeyi önizler. |
| FileRenamed | `50` | Kullanıcı, SharePoint veya OneDrive İş sitesindeki bir belgeyi yeniden adlandırır. |
| FileRestored | `51` | Kullanıcı, bir SharePoint veya OneDrive İş sitesinin geri dönüşüm kutusundan bir belgeyi geri yükler. |
| FileSyncDownloadedFull | `52` | Kullanıcı bir eşitleme ilişkisi kurar ve dosyaları bir SharePoint veya OneDrive İş belge kitaplığından ilk kez bilgisayarına başarıyla indirir. |
| FileSyncDownloadedPartial | `53` | Kullanıcı, dosyalarda yapılan değişiklikleri SharePoint veya OneDrive İş belge kitaplığından başarıyla indirir. Bu olay, belge kitaplığındaki dosyalarda yapılan tüm değişikliklerin kullanıcının bilgisayarına indirildiğini gösterir. Belge kitaplığı daha önce kullanıcı tarafından indirildiğinden (FileSyncDownloadedFull olayında belirtildiği gibi) yalnızca değişiklikler indirildi. |
| FileSyncUploadedFull | `54` | Bu işlem Önizleme'dedir. Kullanıcı bir eşitleme ilişkisi kurar ve dosyaları ilk kez bilgisayarından bir SharePoint veya OneDrive İş belge kitaplığına başarıyla yükler. |
| FileSyncUploadedPartial | `55` | Bu işlem Önizleme'dedir. Kullanıcı, değişiklikleri bir SharePoint veya OneDrive İş belge kitaplığındaki dosyalara başarıyla yükler. Bu olay, bir belge kitaplığından bir dosyanın yerel sürümünde yapılan tüm değişikliklerin belge kitaplığına başarıyla yüklendiğini gösterir. Bu dosyalar daha önce kullanıcı tarafından yüklendiğinden (FileSyncUploadedFull olayında belirtildiği gibi) yalnızca değişiklikler kaldırılır. |
| FileUploaded | `56` | Kullanıcı, SharePoint veya OneDrive İş sitesindeki bir klasöre belge yükler. |
| FileViewed | `57` | Bu olay FileAccessed olayı ile değiştirildi ve kullanımdan kaldırıldı. |
| FolderCopied | `58` | Kullanıcı, bir SharePoint veya OneDrive İş sitesindeki bir klasörü SharePoint veya OneDrive İş'teki başka bir konuma kopyalar. |
| FolderCreated | `59` | Kullanıcı, SharePoint veya OneDrive İş sitesinde bir klasör oluşturur. |
| FolderDeleted | `60` | Kullanıcı, bir SharePoint veya OneDrive İş sitesinden bir klasörü siler. |
| FolderDeletedFirstStageRecycleBin | `61` | Kullanıcı, SharePoint veya OneDrive İş sitesindeki geri dönüşüm kutusundan bir klasörü siler . |
| FolderDeletedSecondStageRecycleBin | `62` | Kullanıcı, bir SharePoint veya OneDrive İş sitesinde ikinci aşama geri dönüşüm kutusundan bir klasörü siler. |
| FolderModified | `63` | Kullanıcı, SharePoint veya OneDrive İş sitesindeki bir klasörü değiştirir. Bu etkinlik, etiketler ve özellikler gibi klasör meta veri değişikliklerini içerir. |
| FolderMoved | `64` | Kullanıcı, bir SharePoint veya OneDrive İş sitesinden bir klasör taşır. |
| FolderRenamed | `65` | Kullanıcı, SharePoint veya OneDrive İş sitesindeki bir klasörü yeniden adlandırır. |
| FolderRestored | `66` | Kullanıcı, SharePoint veya OneDrive İş sitesinde Geri Dönüşüm Kutusu'ndaki bir klasörü geri yükler. |
| GroupAdded | `67` | Bu işlem Önizleme'dedir. Site yöneticisi veya sahibi, bir SharePoint veya OneDrive İş sitesi için bir grup oluşturur veya bir grubun oluşturulmasıyla sonuçlanan bir görev gerçekleştirir. Örneğin, bir kullanıcı bir dosyayı paylaşmak için ilk kez bir bağlantı oluşturduğunda, kullanıcının OneDrive İş sitesine bir sistem grubu eklenir. Bu olay, bir kullanıcının paylaşılan bir dosyaya düzenleme izinlerine sahip bir bağlantı oluşturmasının bir sonucu da olabilir. |
| GroupRemoved | `68` | Bu işlem Önizleme'dedir. Kullanıcı, bir SharePoint veya OneDrive İş sitesinden bir grubu siler. |
| GroupUpdated | `69` | Bu işlem Önizleme'dedir. Site yöneticisi veya sahibi, bir SharePoint veya OneDrive İş sitesi için bir grubun ayarlarını değiştirir. Bu, grup adının değiştirilmesini, grup üyeliğini kimlerin görüntüleyebileceğini veya düzenleyebileceğini ve üyelik isteklerinin nasıl işlendiğini içerebilir. |
| LanguageAddedToTermStore | `70` | Bu işlem Önizleme'dedir. Terminoloji deposuna dil eklendi. |
| LanguageRemovedFromTermStore | `71` | Bu işlem Önizleme'dedir. Terminoloji deposundan dil kaldırıldı. |
| LegacyWorkflowEnabledSet | `72` | Bu işlem Önizleme'dedir. Site yöneticisi veya sahibi, siteye SharePoint İş Akışı Görevi içerik türünü ekler. Genel yöneticiler ayrıcaSharePoint yönetim merkezinde tüm kuruluş için iş akışlarını etkinleştirebilir. |
| LookAndFeelModified | `73` | Kullanıcı hızlı başlatmayı, gantt şeması biçimlerini veya grup biçimlerini değiştirir. Veya kullanıcı, Project Web App'te bir görünüm oluşturur, değiştirir veya siler. |
| ManagedSyncClientAllowed | `74` | Kullanıcı, bir SharePoint veya OneDrive İş sitesiyle başarılı bir şekilde eşitleme ilişkisi kurar. Kullanıcının bilgisayarı, kuruluşunuzdaki belge kitaplıklarına erişebilen etki alanları listesine (güvenli alıcılar listesi adı verilir) eklenmiş bir etki alanının üyesi olduğu için eşitleme ilişkisi başarılıdır. Bu özellik hakkında daha fazla bilgi için bkz. Güvenli alıcılar listesindeki etki alanları için OneDrive eşitlemesini etkinleştirmek üzere Windows PowerShell cmdlet'lerini kullanma. |
| MaxQuotaModified | `75` | Bu işlem Önizleme'dedir. Bir site için maksimum kota değiştirildi. |
| MaxResourceUsageModified | `76` | Bu işlem Önizleme'dedir. Bir site için izin verilen maksimum kaynak kullanımı değiştirildi. |
| MySitePublicEnabledSet | `77` | Bu işlem Önizleme'dedir. Kullanıcıların herkese açık MySites'a sahip olmasını sağlayan bayrak, SharePoint yöneticisi tarafından ayarlandı. |
| NewsFeedEnabledSet | `78` | Bu işlem Önizleme'dedir. Site yöneticisi veya sahibi, bir SharePoint veya OneDrive İş sitesi için RSS beslemelerini etkinleştirir. Genel yöneticiler, SharePoint yönetim merkezinde tüm kuruluş için RSS beslemelerini etkinleştirebilir. |
| ODBNextUXSettings | `79` | Bu işlem Önizleme'dedir. OneDrive İş için yeni kullanıcı arayüzü etkinleştirildi. |
| OfficeOnDemandSet | `80` | Bu işlem Önizleme'dedir. Site yöneticisi, kullanıcıların Office masaüstü uygulamalarının en son sürümüne erişmesine olanak tanıyan Office on Demand'ı etkinleştirir. İsteğe Bağlı Office, SharePoint yönetim merkezinde etkinleştirilir ve tam, yüklü Office uygulamalarını içeren bir Office 365 aboneliği gerektirir. |
| PageViewed | `81` | Kullanıcı, bir SharePoint sitesinde veya OneDrive İş sitesinde bir sayfa görüntüler. Bu, bir SharePoint sitesinden veya One Drive for Business sitesinden belge kitaplığı dosyalarının tarayıcıda görüntülenmesini içermez. |
| PeopleResultsScopeSet | `82` | Bu işlem Önizleme'dedir. Site yöneticisi, bir SharePoint sitesi için Kişi Aramaları için sonuç kaynağını oluşturur veya değiştirir. |
| PermissionSyncSettingModified | `83` | Kullanıcı, Project Web App'te proje izin eşitleme ayarlarını değiştirir. |
| PermissionTemplateModified | `84` | Kullanıcı, Project Web App'te bir izin şablonu oluşturur, değiştirir veya siler. |
| PortfolioDataAccessed | `85` | Kullanıcı, Project Web App'te portföy içeriğine (sürücü kitaplığı, sürücü önceliklendirme, portföy analizleri) erişir. |
| PortfolioDataModified | `86` | Kullanıcı, Project Web App'te portföy verilerini (sürücü kitaplığı, sürücü önceliklendirme, portföy analizleri) oluşturur, değiştirir veya siler. |
| PreviewModeEnabledSet | `87` | Bu işlem Önizleme'dedir. Site yöneticisi, bir SharePoint sitesi için belge önizlemesini etkinleştirir. |
| ProjectAccessed | `88` | Kullanıcı, Project Web App'te proje içeriğine erişir. |
| ProjectCheckedIn | `89` | Kullanıcı, bir Proje Web Uygulamasından teslim aldığı bir projeyi kontrol eder. |
| ProjectCheckedOut | `90` | Kullanıcı, Project Web Uygulamasında bulunan bir projeyi kontrol eder. Kullanıcılar, açma iznine sahip oldukları projeleri kontrol edebilir ve bu projelerde değişiklik yapabilir. |
| ProjectCreated | `91` | Kullanıcı, Project Web App'te bir proje oluşturur. |
| ProjectDeleted | `92` | Kullanıcı, Project Web App'te bir projeyi siler. |
| ProjectForceCheckedIn | `93` | Kullanıcı, Project Web App'te bir projeye giriş yapmaya zorlar. |
| ProjectModified | `94` | Kullanıcı, Project Web App'te bir projeyi değiştirir. |
| ProjectPublished | `95` | Kullanıcı, Project Web App'te bir proje yayınlar. |
| ProjectWorkflowRestarted | `96` | Kullanıcı, Project Web App'te bir iş akışını yeniden başlatır. |
| PWASettingsAccessed | `97` | Kullanıcı, CSOM aracılığıyla Project Web App ayarlarına erişir. |
| PWASettingsModified | `98` | Kullanıcı, Project Web App yapılandırmasını değiştirir. |
| QueueJobStateModified | `99` | Kullanıcı, Project Web App'te bir kuyruk işini iptal eder veya yeniden başlatır. |
| QuotaWarningEnabledModified | `100` | Bu işlem Önizleme'dedir. Depolama kotası uyarısı değiştirildi. |
| RenderingEnabled | `101` | Bu işlem Önizleme'dedir. Tarayıcı etkin form şablonları, InfoPath form hizmetleri tarafından oluşturulacaktır. |
| ReportingAccessed | `102` | Kullanıcı, Project Web App'te raporlama uç noktasına erişti. |
| ReportingSettingModified | `103` | Kullanıcı, Project Web App'te raporlama yapılandırmasını değiştirir. |
| ResourceAccessed | `104` | Kullanıcı, Project Web App'te bir kurumsal kaynak içeriğine erişir. |
| ResourceCheckedIn | `105` | Kullanıcı, Project Web App'ten teslim aldığı bir kurumsal kaynağı kontrol eder. |
| ResourceCheckedOut | `106` | Kullanıcı, Project Web App'te bulunan bir kurumsal kaynağı kontrol eder. |
| ResourceCreated | `107` | Kullanıcı, Project Web App'te bir kurumsal kaynak oluşturur. |
| ResourceDeleted | `108` | Kullanıcı, Project Web App'te bir kurumsal kaynağı siler. |
| ResourceForceCheckedIn | `109` | Kullanıcı, Project Web App'te bir kurumsal kaynağın iadesini zorlar. |
| ResourceModified | `110` | Kullanıcı, Project Web App'te bir kurumsal kaynağı değiştirir. |
| ResourcePlanCheckedInOrOut | `111` | Kullanıcı, Project Web App'te bir kaynak planına giriş veya çıkış yapar. |
| ResourcePlanModified | `112` | Kullanıcı, Project Web App'te bir kaynak planını değiştirir. |
| ResourcePlanPublished | `113` | Kullanıcı, Project Web App'te bir kaynak planı yayınlar. |
| ResourceRedacted | `114` | Kullanıcı, Project Web App'teki tüm kişisel bilgileri kaldırarak bir kurumsal kaynağı yeniden düzenler. |
| ResourceWarningEnabledModified | `115` | Bu işlem Önizleme'dedir. Kaynak kotası uyarısı değiştirildi. |
| SSOGroupCredentialsSet | `116` | Bu işlem Önizleme'dedir. Güvenli mağaza hizmetinde ayarlanan grup kimlik bilgileri. |
| SSOUserCredentialsSet | `117` | Bu işlem Önizleme'dedir. Güvenli mağaza hizmetinde ayarlanan kullanıcı kimlik bilgileri. |
| SearchCenterUrlSet | `118` | Bu işlem Önizleme'dedir. Arama merkezi URL seti. |
| SecondaryMySiteOwnerSet | `119` | Bu işlem Önizleme'dedir. Bir kullanıcı MySite'ına ikinci bir sahip ekledi. |
| SecurityCategoryModified | `120` | Kullanıcı, Project Web App'te bir güvenlik kategorisi oluşturur, değiştirir veya siler. |
| SecurityGroupModified | `121` | Kullanıcı, Project Web App'te bir güvenlik grubu oluşturur, değiştirir veya siler. |
| SendToConnectionAdded | `122` | Bu işlem Önizleme'dedir. Genel yönetici, SharePoint yönetim merkezindeki Kayıt yönetimi sayfasında yeni bir Gönder bağlantısı oluşturur. Şuraya Gönder bağlantısı, bir belge havuzu veya kayıt merkezi için ayarları belirtir. Bir Gönderme bağlantısı oluşturduğunuzda, bir İçerik Düzenleyici belirtilen konuma belgeler gönderebilir. |
| SendToConnectionRemoved | `123` | Bu işlem Önizleme'dedir. Genel yönetici, SharePoint yönetim merkezindeki Kayıt yönetimi sayfasındaki Gönder bağlantısını siler. |
| SharedLinkCreated | `124` | Kullanıcı, SharePoint veya OneDrive İş'te paylaşılan bir dosyaya bağlantı oluşturur. Bu bağlantı, dosyaya erişmelerini sağlamak için diğer kişilere gönderilebilir. Bir kullanıcı iki tür bağlantı oluşturabilir: kullanıcının paylaşılan dosyayı görüntülemesine ve düzenlemesine izin veren bir bağlantı veya kullanıcının yalnızca dosyayı görüntülemesine izin veren bir bağlantı. |
| SharedLinkDisabled | `125` | Bu işlem Önizleme'dedir. Kullanıcı, bir dosyayı paylaşmak için oluşturulmuş bir bağlantıyı (kalıcı olarak) devre dışı bırakır. |
| SharingInvitationAccepted | `126` | Bu işlem Önizleme'dedir. Kullanıcı, bir dosya veya klasörü paylaşma davetini kabul eder. Bu olay, bir kullanıcı bir dosyayı diğer kullanıcılarla paylaştığında günlüğe kaydedilir. |
| SharingRevoked | `127` | Bu işlem Önizleme'dedir. Kullanıcı, daha önce diğer kullanıcılarla paylaşılan bir dosya veya klasörün paylaşımını kaldırır. Bu olay, bir kullanıcı diğer kullanıcılarla dosya paylaşmayı bıraktığında günlüğe kaydedilir. |
| SharingSet | `128` | Kullanıcı, SharePoint veya OneDrive İş'te bulunan bir dosya veya klasörü kendi kuruluşu içindeki başka bir kullanıcıyla paylaşır. |
| SiteAdminChangeRequest | `129` | Bu işlem Önizleme'dedir. Kullanıcı, bir SharePoint site koleksiyonu için site koleksiyonu yöneticisi olarak eklenme istekleri. Site koleksiyonu yöneticileri, site koleksiyonu ve tüm alt siteler için tam denetim izinlerine sahiptir. |
| SiteCollectionAdminAdded | `130` | Bu işlem Önizleme'dedir. Site koleksiyonu yöneticisi veya sahibi, bir kişiyi SharePoint veya OneDrive İş sitesi için site koleksiyonu yöneticisi olarak ekler. Site koleksiyonu yöneticileri, site koleksiyonu ve tüm alt siteler için tam denetim izinlerine sahiptir. |
| SiteCollectionCreated | `131` | Bu işlem Önizleme'dedir. Genel yönetici, SharePoint kuruluşunuzda yeni bir site koleksiyonu oluşturur. |
| SiteRenamed | `132` | Bu işlem Önizleme'dedir. Site yöneticisi veya sahibi, bir SharePoint veya OneDrive İş sitesini yeniden adlandırır |
| StatusReportModified | `133` | Kullanıcı, Project Web App'te bir durum raporu oluşturur, değiştirir veya siler. |
| SyncGetChanges | `134` | Bu işlem Önizleme'dedir. Kullanıcı, belge kitaplığındaki dosyada yapılan değişiklikleri kendi bilgisayarlarıyla eşitlemek için SharePoint veya OneDrive İş'teki eylem tepsisinde Eşitle'yi tıklatır. |
| TaskStatusAccessed | `135` | Kullanıcı, Project Web App'te bir veya daha fazla görevin durumuna erişir. |
| TaskStatusApproved | `136` | Kullanıcı, Project Web App'te bir veya daha fazla görevin durum güncellemesini onaylar. |
| TaskStatusRejected | `137` | Kullanıcı, Project Web App'te bir veya daha fazla görevin durum güncellemesini reddediyor. |
| TaskStatusSaved | `138` | Kullanıcı, Project Web App'te bir veya daha fazla görevin durum güncellemesini kaydeder. |
| TaskStatusSubmitted | `139` | Kullanıcı, Project Web App'te bir veya daha fazla görevin durum güncellemesini gönderir. |
| TimesheetAccessed | `140` | Kullanıcı, Project Web App'te bir zaman çizelgesine erişir. |
| TimesheetApproved | `141` | Kullanıcı, Project Web App'te zaman çizelgesini onaylar. |
| TimesheetRejected | `142` | Kullanıcı, Project Web App'te bir zaman çizelgesini reddediyor. |
| TimesheetSaved | `143` | Kullanıcı, Project Web App'te bir zaman çizelgesi kaydeder. |
| TimesheetSubmitted | `144` | Kullanıcı, Project Web App'te bir durum zaman çizelgesi gönderir. |
| UnmanagedSyncClientBlocked | `145` | Kullanıcı, kuruluşunuzun etki alanının üyesi olmayan veya etki alanları listesine eklenmemiş bir etki alanının üyesi olan bir bilgisayardan bir SharePoint veya OneDrive İş sitesi ile eşitleme ilişkisi kurmaya çalışır ( kuruluşunuzdaki belge kitaplıklarına erişebilen güvenli alıcılar listesi olarak adlandırılır). Eşitleme ilişkisine izin verilmiyor ve kullanıcının bilgisayarının bir belge kitaplığındaki dosyaları eşitlemesi, indirmesi veya karşıya yüklemesi engelleniyor. Bu özellik hakkında bilgi için bkz. Güvenli alıcılar listesindeki etki alanları için OneDrive eşitlemesini etkinleştirmek üzere Windows PowerShell cmdlet'lerini kullanma. |
| UpdateSSOApplication | `146` | Bu işlem Önizleme'dedir. Güvenli mağaza hizmetinde güncellenen hedef uygulama. |
| UserAddedToGroup | `147` | Bu işlem Önizleme'dedir. Site yöneticisi veya sahibi, SharePoint veya OneDrive İş sitesindeki bir gruba bir kişi ekler. Gruba bir kişi eklemek, kullanıcıya gruba atanan izinleri verir. |
| UserRemovedFromGroup | `148` | Bu işlem Önizleme'dedir. Site yöneticisi veya sahibi, bir kişiyi SharePoint veya OneDrive İş sitesindeki bir gruptan kaldırır. Kişi kaldırıldıktan sonra, gruba atanan izinlere artık verilmez. |
| WorkflowModified | `149` | Kullanıcı, Project Web App'te bir Kurumsal Proje Türü veya İş Akışı aşamaları veya aşamaları oluşturur, değiştirir veya siler. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
