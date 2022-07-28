---
title: Aspose.Email.Clients.Imap
second_title: Aspose.Email for .NET API Referansı
description: Aspose.Email.Clients.Imap ad alanı ye erişmek ve Internet İleti Erişim Protokolünü IMAP kullanarak iletileri değiştirmek için sınıflar sağlar.
type: docs
weight: 220
url: /tr/net/aspose.email.clients.imap/
---
**Aspose.Email.Clients.Imap** ad alanı, 'ye erişmek ve Internet İleti Erişim Protokolü'nü (IMAP) kullanarak iletileri değiştirmek için sınıflar sağlar.

## sınıflar

| Sınıf | Tanım |
| --- | --- |
| [AppendMessagesResult](./appendmessagesresult) | Mesajlarla işlemin sonucunu içerir |
| [BackupSettings](./backupsettings) | Sınıf, yedekleme işlemi için seçenekler içerir |
| [BaseSearchConditions](./basesearchconditions) | Arama koşulları için temel sınıf sağlar. |
| [ESearchOptions](./esearchoptions) | ESEARCH Sonuç Seçenekler Bu yöntem yalnızca sunucu ESEARCH uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| [FetchTimeoutException](./fetchtimeoutexception) | Bir ileti belirtilen süre içinde okunamadığında oluşturulan özel durumu temsil eder. |
| [ImapAttachmentInfo](./imapattachmentinfo) | Bir ek bilgisini temsil eder. |
| [ImapAttachmentInfoCollection](./imapattachmentinfocollection) | Şunların koleksiyonunu temsil eder:[`ImapAttachmentInfo`](../aspose.email.clients.imap/imapattachmentinfo) |
| [ImapClient](./imapclient) | Uygulamaların İnternet İleti Erişim Protokolü'nü (IMAP) kullanarak iletilerine erişmesine ve bunları değiştirmesine izin verir. |
| [ImapFolderInfo](./imapfolderinfo) | Bir IMAP klasörünü temsil eder. |
| [ImapFolderInfoCollection](./imapfolderinfocollection) | ImapFolderInfo nesneleri koleksiyonu için bir kap sağlar. |
| [ImapIdentificationInfo](./imapidentificationinfo) | Posta istemcisi ve sunucu arasında değiş tokuş yapmak için kimlik bilgileri içeren sınıf kapsayıcısını temsil eder. Lütfen daha fazla bilgi edinin rfc2971 https://tools.ietf.org/html/rfc2971 |
| [ImapMailboxInfo](./imapmailboxinfo) | Özel kullanımlı posta kutuları kümesi içerir |
| [ImapMessageFlags](./imapmessageflags) | İletiyle ilişkili bayrakları temsil eder. |
| [ImapMessageInfo](./imapmessageinfo) | Bir Imap ileti nesnesini temsil eder. |
| [ImapMessageInfoCollection](./imapmessageinfocollection) | Bir koleksiyon için bir kap sağlar[`ImapMessageInfo`](../aspose.email.clients.imap/imapmessageinfo) nesneler |
| [ImapMonitoringErrorEventArgs](./imapmonitoringerroreventargs) | Sınıf, izleme hatası olay verilerini içerir. |
| [ImapMonitoringErrorEventHandler](./imapmonitoringerroreventhandler) | Bir imap izleme hatasını işleyecek olan yöntemi temsil eder event |
| [ImapMonitoringEventArgs](./imapmonitoringeventargs) | Sınıf, izleme olayı verilerini içerir. |
| [ImapMonitoringEventHandler](./imapmonitoringeventhandler) | Bir imap izleme olayını işleyecek yöntemi temsil eder event |
| [ImapNamespace](./imapnamespace) | IMAP ad alanını temsil eder Daha fazla ayrıntı: https://tools.ietf.org/html/rfc2342 |
| [ImapPageInfo](./imappageinfo) | Sayfalama yöntemleri kullanıldığında alınan sayfa hakkında bilgi içerir. |
| [ImapQueryBuilder](./imapquerybuilder) | IMAP protokolü tarafından kullanılan arama ifadesi oluşturucusunu temsil eder. |
| [ImapQuota](./imapquota) | Posta kutusu kaynağı kotası hakkında bilgi içerir. |
| [ImapQuotaRoot](./imapquotaroot) | Posta kutusu kaynağı için kota kökü hakkında bilgi içerir. |
| [MessageThreadResult](./messagethreadresult) | SORT veya THREAD yöntemleri için sonucu içerir Daha fazlasını görün: https://tools.ietf.org/html/rfc5256 |
| [ModificationSequenceField](./modificationsequencefield) | Aranacak seçili alan için bir dizi değer tanımlar. |
| [PageSettings](./pagesettings) | ImapClient.ListMessagesByPage yönteminin ayarları |
| [PageSettingsAsync](./pagesettingsasync) | ImapClient.BeginListMessagesByPage zaman uyumsuz yöntemi için ayarlar. |
| [RangeSeqSet](./rangeseqset) | Aranacak değer aralığını içeren kapsayıcı. |
| [ReadLinesTimeoutException](./readlinestimeoutexception) | Sunucudan gelen yanıt belirtilen süre içinde okunamadığında oluşturulan özel durumu temsil eder. |
| [RestoreSettings](./restoresettings) | ImapClient.Restore yönteminin ayarları |
| [RestoreSettingsAsync](./restoresettingsasync) | ImapClient.Restore zaman uyumsuz yönteminin ayarları. |
| [SequenceSetBaseValue](./sequencesetbasevalue) | Aranacak değerler için farklı kapsayıcılar için temel sınıf. |
| [SequenceSetField](./sequencesetfield) | Aranacak seçili alan için bir dizi değer tanımlar. |
| [SimpleSeqSet](./simpleseqset) | Aranacak değer için basit kapsayıcı. |
| [SortConditions](./sortconditions) | SORT uzantısı için arama koşullarını sağlar. https://tools.ietf.org/html/rfc5256 adresinde açıklanan SORT IMAP uzantısıyla uyumludur. |
| [ThreadSearchConditions](./threadsearchconditions) | E-posta dizisini almak için arama koşullarını sağlar. https://tools.ietf.org/html/rfc5256 adresinde açıklanan THREAD IMAP uzantısıyla uyumludur |
| [XGMThreadSearchConditions](./xgmthreadsearchconditions) | E-posta ileti dizisini almak için arama koşullarını sağlar. https://developers.google.com/gmail/imap/imap-extensions#checking_for_the_presence_of_extensions. adresinde açıklanan X-GM-EXT-1 IMAP uzantısıyla uyumludur. |
## Arayüzler

| Arayüz | Tanım |
| --- | --- |
| [IAsyncImapClient](./iasyncimapclient) | Uygulamaların İnternet İleti Erişim Protokolü'nü (IMAP) kullanarak iletilerine erişmesine ve bunları değiştirmesine izin verir. |
| [IImapMonitoringState](./iimapmonitoringstate) | Klasör izleme durumunu tutar. Bu, klasör izlemeye, hata oluştuğunda durduğu place konumundan devam etmek için kullanılabilir. Kullanmak[`ResumeMonitoring`](../aspose.email.clients.imap/imapclient/resumemonitoring) yöntem. |
## numaralandırma

| numaralandırma | Tanım |
| --- | --- |
| [ImapCommandResult](./imapcommandresult) | imap komutu sonuçlarını numaralandırır. |
| [ImapKnownAuthenticationType](./imapknownauthenticationtype) |  |
| [ImapListFields](./imaplistfields) | Sunucudan alınabilecek alanlar |
| [ImapNamespaceType](./imapnamespacetype) | IMAP ad alanı type 'yi temsil eder Daha fazla ayrıntı: https://tools.ietf.org/html/rfc2342 |
| [ImapSpecialFolderTypes](./imapspecialfoldertypes) | Özel kullanımlı posta kutularının numaralandırılmasını temsil eder Daha fazla ayrıntı için bkz. RFC6154 http://tools.ietf.org/html/rfc6154 |
| [ImapStatusCode](./imapstatuscode) | Durum yanıtlarını temsil eder. |
| [ListFoldersOptions](./listfoldersoptions) | Klasör listesi seçim seçenekleri Sunucunun RFC 5258 "IMAP LIST Komut Uzantılarını" desteklemesi durumunda bu seçeneklerin desteklendiğini lütfen unutmayın https://tools.ietf.org/html/rfc5258 adresinde daha fazla ayrıntıya bakın |
| [ListFoldersReturnOptions](./listfoldersreturnoptions) | ListFolders işlemi için dönüş seçenekleri Sunucunun RFC 5258 "IMAP LIST Komut Uzantılarını" desteklemesi durumunda bu seçeneklerin desteklendiğini lütfen unutmayın https://tools.ietf.org/html/rfc5258 adresinde daha fazla ayrıntıya bakın |
| [SortingKey](./sortingkey) | "SIRALA" komutu için sıralama kriterleri Daha fazlasını görün: https://tools.ietf.org/html/rfc5256 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
