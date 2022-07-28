---
title: IGraphClient
second_title: Aspose.Email for .NET API Referansı
description: Exchange REST istemcisi için arabirimi temsil eder.
type: docs
weight: 15950
url: /tr/net/aspose.email.clients.graph/igraphclient/
---
## IGraphClient interface

Exchange REST istemcisi için arabirimi temsil eder.

```csharp
public interface IGraphClient : IDisposable
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [MultipleServicesTokenProvider](../../aspose.email.clients.graph/igraphclient/multipleservicestokenprovider) { get; set; } | Bir nesne alır veya ayarlar, OAuth erişim belirtecinin alınmasına izin verir. |
| [Proxy](../../aspose.email.clients.graph/igraphclient/proxy) { get; set; } | Exchange sunucusuna proxy erişimi için verileri alır veya ayarlar. |
| [Resource](../../aspose.email.clients.graph/igraphclient/resource) { get; set; } | Kaynak türünü alır veya ayarlar. |
| [ResourceId](../../aspose.email.clients.graph/igraphclient/resourceid) { get; set; } | Kaynak kimliğini alır veya ayarlar. Örneğin kullanıcılar için kullanıcı asıl adı (UPN) veya kullanıcı kimliği olabilir |
| [TenantId](../../aspose.email.clients.graph/igraphclient/tenantid) { get; set; } | Kiracı tanımlayıcısını alır veya ayarlar |
| [Timeout](../../aspose.email.clients.graph/igraphclient/timeout) { get; set; } | İşlem zaman aşımına uğramadan önce beklenecek milisaniye sayısını alır veya ayarlar. Varsayılan değer 100.000 milisaniyedir (100 saniye). |
| [TokenProvider](../../aspose.email.clients.graph/igraphclient/tokenprovider) { get; set; } | Bir nesne alır veya ayarlar, OAuth erişim belirtecinin alınmasına izin verir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [CopyFolder](../../aspose.email.clients.graph/igraphclient/copyfolder)(string, string) | Bir posta klasörünü ve içeriğini başka bir posta klasörüne kopyalayın. |
| [CopyMessage](../../aspose.email.clients.graph/igraphclient/copymessage)(string, string) | Bir İletiyi başka bir posta klasörüne kopyalayın. |
| [CopyNotebook](../../aspose.email.clients.graph/igraphclient/copynotebook)(string, string, string) | Bir not defterini hedef Belgeler kitaplığındaki Not Defterleri klasörüne kopyalar. Klasör mevcut değilse oluşturulur. Kopyalama işlemleri için eşzamansız bir çağrı düzeni izlersiniz: Önce Kopyala eylemini çağırın ve ardından sonuç için işlem uç noktasını yoklayın. Permissions Çağırmak için aşağıdaki izinlerden biri gerekir bu API. Delegated(iş veya okul hesabı) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegated(kişisel Microsoft hesabı) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateAttachment](../../aspose.email.clients.graph/igraphclient/createattachment)(string, MapiAttachment) | Belirtilen item için yeni ek oluşturur |
| [CreateCategory](../../aspose.email.clients.graph/igraphclient/createcategory)(string, CategoryPreset) | Bir[`OutlookCategory`](../outlookcategory) kullanıcının ana kategori listesindeki nesne. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder)(string) | Yeni klasör oluştur. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder_1)(string, string) | Yeni klasör oluştur. |
| [CreateMessage](../../aspose.email.clients.graph/igraphclient/createmessage)(string, MapiMessage) | Belirtilen klasörde ileti oluşturur |
| [CreateNotebook](../../aspose.email.clients.graph/igraphclient/createnotebook)(Notebook) | Yeni bir OneNote not defteri oluşturun. Permissions Bu API'yi çağırmak için aşağıdaki izinlerden biri gereklidir. Delegated (iş veya okul hesabı) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegated (kişisel Microsoft hesabı) Notes. Oluştur, Notes.ReadWrite Uygulama Notları.ReadWrite.All |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride)(ClassificationOverride) | Bir SMTP adresi tarafından tanımlanan bir gönderen için geçersiz kılma oluşturun. Bu SMTP adresinden gelecek mesajlar, geçersiz kılmada belirtildiği gibi tutarlı bir şekilde sınıflandırılacaktır. Not: - Aynı SMTP adresiyle bir geçersiz kılma zaten mevcutsa, o geçersiz kılmanın classifyAs ve ad alanları sağlanan değerlerle güncellenir. - Bir posta kutusu için desteklenen maksimum geçersiz kılma sayısı, benzersiz gönderen SMTP adreslerine bağlı olarak 1000'dir. İzinler: Temsilci (iş veya okul hesabı) Mail.ReadWrite Temsilci (kişisel Microsoft hesabı) Mail.ReadWrite Uygulama Postası.ReadWrite |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride_1)(MailAddress, ClassificationType) | Bir SMTP adresi tarafından tanımlanan bir gönderen için geçersiz kılma oluşturun. Bu SMTP adresinden gelecek mesajlar, geçersiz kılmada belirtildiği gibi tutarlı bir şekilde sınıflandırılacaktır. Not: - Aynı SMTP adresiyle bir geçersiz kılma zaten mevcutsa, o geçersiz kılmanın classifyAs ve ad alanları sağlanan değerlerle güncellenir. - Bir posta kutusu için desteklenen maksimum geçersiz kılma sayısı, benzersiz gönderen SMTP adreslerine bağlı olarak 1000'dir. İzinler: Temsilci (iş veya okul hesabı) Mail.ReadWrite Temsilci (kişisel Microsoft hesabı) Mail.ReadWrite Uygulama Postası.ReadWrite |
| [CreateRule](../../aspose.email.clients.graph/igraphclient/createrule)(InboxRule) | Bir dizi koşul ve eylem belirterek bir ileti kuralı oluşturun. Outlook, kullanıcının Gelen Kutusuna gelen bir ileti belirtilen koşulları karşılıyorsa bu eylemleri gerçekleştirir. İzinler: Bu API'yi çağırmak için aşağıdaki izinlerden biri gereklidir. izinlerin nasıl seçileceği de dahil olmak üzere daha fazla bilgi edinin, bkz. İzinler. Temsilci (iş veya okul hesabı) MailboxSettings.ReadWrite Temsilci (kişisel Microsoft hesabı) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |
| [Delete](../../aspose.email.clients.graph/igraphclient/delete)(string) | Nesneyi sil. |
| [DeleteAttachment](../../aspose.email.clients.graph/igraphclient/deleteattachment)(string) | eki kaldırır |
| [FetchAttachment](../../aspose.email.clients.graph/igraphclient/fetchattachment)(string) | Belirtilen id için ek alır |
| [FetchCategory](../../aspose.email.clients.graph/igraphclient/fetchcategory)(string) | Belirtilen outlookCategory nesnesinin özelliklerini ve ilişkilerini alın. |
| [FetchMessage](../../aspose.email.clients.graph/igraphclient/fetchmessage)(string) | Belirtilen id içindeki iletiyi alır |
| [FetchNotebook](../../aspose.email.clients.graph/igraphclient/fetchnotebook)(string) | Bir not defteri nesnesinin özelliklerini ve ilişkilerini alın. Permissions Bu API'yi çağırmak için aşağıdaki izinlerden biri gereklidir. Temsilci (iş veya okul hesabı) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All , Notes.ReadWrite.All Temsilci (kişisel Microsoft hesabı) Notes.Create, Notes.Read, Notes.ReadWrite Uygulama Notları.Read.All, Notes.ReadWrite.All |
| [FetchRule](../../aspose.email.clients.graph/igraphclient/fetchrule)(string) | Bir ileti kuralı nesnesinin özelliklerini ve ilişkilerini alın. Permissions Bu API'yi çağırmak için aşağıdaki izinlerden biri gereklidir. İzinlerin nasıl seçileceği de dahil olmak üzere daha fazla bilgi edinmek için bkz. İzinler. Temsilci (iş veya okul hesabı) MailboxSettings.Read Temsilci (kişisel Microsoft hesabı) MailboxSettings.Read Application MailboxSettings.Read |
| [GetFolder](../../aspose.email.clients.graph/igraphclient/getfolder)(string) | Klasörü bir kimliğe göre alır. |
| [GetOneNoteOperationStatus](../../aspose.email.clients.graph/igraphclient/getonenoteoperationstatus)(string) | Uzun süredir devam eden OneNote işleminin durumunu alın. Bu, CopyNotebook, CopyToNotebook, CopyToSectionGroup ve CopyToSection gibi yanıtta Operation-Location üstbilgisini döndüren işlemler için geçerlidir. status özelliği tamamlandı veya başarısız olarak döner. Durum tamamlandıysa, resourceLocation özelliği kaynak uç noktası URI'sini içerir. Durum başarısız olursa, error ve @api.diagnostics özellikleri hata bilgisi sağlar. |
| [ListAttachments](../../aspose.email.clients.graph/igraphclient/listattachments)(string) | Üst mesajdaki Ekleri Listeleyin. |
| [ListCategories](../../aspose.email.clients.graph/igraphclient/listcategories)() | Kullanıcı için tanımlanmış tüm kategorileri alın. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders)() | Gelen kutusu gibi normal posta istemcilerinde görüntülenen klasörler için üst klasördeki klasörleri listeleyin. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders_1)(string) | Gelen kutusu gibi normal posta istemcilerinde görüntülenen klasörler için üst klasördeki klasörleri listeleyin. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages_1)(string) | Üst klasördeki MessageInfo'yu listeleyin. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages)(string, PageInfo, MailQuery) | Üst klasördeki MessageInfo'yu listeleyin. |
| [ListNotebooks](../../aspose.email.clients.graph/igraphclient/listnotebooks)() | Not defteri nesnelerinin listesini alın. Permissions Bu API'yi çağırmak için aşağıdaki izinlerden biri gereklidir. Temsilci (iş veya okul hesabı) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All, Notes. ReadWrite.All Temsilci (kişisel Microsoft hesabı) Notes.Create, Notes.Read, Notes.ReadWrite Uygulama Notları.Read.All, Notes.ReadWrite.All |
| [ListOverrides](../../aspose.email.clients.graph/igraphclient/listoverrides)() | Bir kullanıcının belirli göndericilerden gelen iletileri her zaman belirli şekillerde sınıflandırmak için ayarladığı geçersiz kılmaları alın. Her geçersiz kılma, gönderenin bir SMTP adresine karşılık gelir.Başlangıçta, bir kullanıcının herhangi bir geçersiz kılma özelliği yoktur. İzinler: bu API'yi çağırmak için aşağıdaki izinler gereklidir.İzinlerin nasıl seçileceği de dahil olmak üzere daha fazla bilgi edinmek için bkz. |
| [ListRules](../../aspose.email.clients.graph/igraphclient/listrules)() | Kullanıcının Gelen Kutusu için tanımlanan tüm messageRule nesnelerini alın. Permissions Bu API'yi çağırmak için aşağıdaki izinlerden biri gereklidir. İzinlerin nasıl seçileceği de dahil olmak üzere daha fazla bilgi edinmek için İzinler bölümüne bakın. Yetkilendirilen (iş veya okul hesabı) MailboxSettings.Read Temsilci (kişisel Microsoft hesabı) MailboxSettings.Read Application MailboxSettings.Read |
| [MoveFolder](../../aspose.email.clients.graph/igraphclient/movefolder)(string, string) | Bir posta klasörünü ve içeriğini başka bir posta klasörüne taşıyın. |
| [MoveMessage](../../aspose.email.clients.graph/igraphclient/movemessage)(string, string) | İletiyi başka bir posta klasörüne taşıyın. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send)(MapiMessage) | E-posta mesajı gönderir |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_2)(string) | Taslak klasöründe bir mesaj gönderin. Taslak mesaj, yeni bir mesaj taslağı, yanıt taslağı, tümünü yanıtla taslağı veya iletme taslağı olabilir. Mesaj daha sonra Gönderilmiş Öğeler klasörüne kaydedilir. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_1)(MapiMessage, bool) | E-posta mesajı gönderir |
| [SetRead](../../aspose.email.clients.graph/igraphclient/setread)(string) | İletiyi read olarak işaretle |
| [UpdateCategory](../../aspose.email.clients.graph/igraphclient/updatecategory)(OutlookCategory) | Belirtilen kategori için önceden ayarlanmış renk sabitini günceller |
| [UpdateFolder](../../aspose.email.clients.graph/igraphclient/updatefolder)(FolderInfo) | Güncellemeler klasörü. |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage)(MapiMessage) | Güncelleme mesajı |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage_1)(MapiMessage, UpdateSettings) | Güncelleme mesajı |
| [UpdateOverride](../../aspose.email.clients.graph/igraphclient/updateoverride)(ClassificationOverride) | Bir geçersiz kılmanın classifyAs alanını belirtildiği gibi değiştirin. Bir ClassificationOverride örneğindeki diğer alanları değiştirmek için bu yöntemi kullanamazsınız. Bir gönderen için bir geçersiz kılma varsa ve gönderen kendi görünen adını değiştirirse, CreateOrUpdateOverride'ı kullanarak mevcut geçersiz kılmada ad alanına bir güncelleme yapmaya zorlayın. Gönderici için bir geçersiz kılma varsa ve gönderen SMTP adresini değiştirirse, mevcut geçersiz kılmayı silmek ve yeni SMTP adresiyle yeni bir tane oluşturmak, bunun tek yoludur. Bu gönderici için geçersiz kılmayı "güncelleyin". İzinler: Bu API'yi çağırmak için aşağıdaki izinlerden biri gereklidir.İzinlerin nasıl seçileceği de dahil olmak üzere daha fazla bilgi edinmek için bkz. (kişisel Microsoft hesabı) Mail.ReadWrite Uygulama Postası.ReadWrite |
| [UpdateRule](../../aspose.email.clients.graph/igraphclient/updaterule)(InboxRule) | Bir messageRule nesnesindeki yazılabilir özellikleri değiştirin ve değişiklikleri kaydedin. Permissions Bu API'yi çağırmak için aşağıdaki izinlerden biri gereklidir. İzinlerin nasıl seçileceği de dahil olmak üzere daha fazla bilgi edinmek için İzinler'e bakın. Yetkilendirilen (iş veya okul hesabı) Posta Kutusu Ayarları. ReadWrite Temsilci (kişisel Microsoft hesabı) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
