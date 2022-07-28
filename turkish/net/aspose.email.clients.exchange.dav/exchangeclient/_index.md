---
title: ExchangeClient
second_title: Aspose.Email for .NET API Referansı
description: ExchangeClient sınıfı uygulamaların WebDav Exchange Mağaza Protokolünü kullanarak Microsoft Exchange Serverdaki E-Posta kutusunu yönetmesine izin verir.
type: docs
weight: 3150
url: /tr/net/aspose.email.clients.exchange.dav/exchangeclient/
---
## ExchangeClient class

ExchangeClient sınıfı, uygulamaların WebDav Exchange Mağaza Protokolünü kullanarak Microsoft Exchange Server'daki E-Posta kutusunu yönetmesine izin verir.

```csharp
public sealed class ExchangeClient : ExchangeClientBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ExchangeClient](exchangeclient#constructor)(string, ICredentials) | Sınıfın yeni bir örneğini başlat[`ExchangeMüşteri`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_1)(string, string, string) | Sınıfın yeni bir örneğini başlat[`ExchangeMüşteri`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_2)(string, string, string, string) | Sınıfın yeni bir örneğini başlat[`ExchangeMüşteri`](../exchangeclient) |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ClientCertificate](../../aspose.email.clients.exchange.dav/exchangeclient/clientcertificate) { get; set; } | İstemci sertifikasını alır veya ayarlar. |
| [CookieContainer](../../aspose.email.clients.exchange.dav/exchangeclient/cookiecontainer) { get; set; } | Çerez kapsayıcısını alır veya ayarlar. |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | Kimlik bilgilerini alır veya ayarlar |
| [Encoding](../../aspose.email.clients.exchange.dav/exchangeclient/encoding) { get; set; } | Kodlamayı alır veya ayarlar. |
| [KeepAlive](../../aspose.email.clients.exchange.dav/exchangeclient/keepalive) { get; set; } | Canlı tutulup tutulmayacağını belirtir. |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | Günlük dosyası adını alır veya ayarlar |
| [MailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/mailboxinfo) { get; } | Posta kutusu bilgilerini alır. |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | uri posta kutusunu alır veya ayarlar |
| [PreAuthenticate](../../aspose.email.clients.exchange.dav/exchangeclient/preauthenticate) { get; set; } | Ön kimlik doğrulamanın yapılıp yapılmayacağını belirtir. |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | Proxy'yi alır veya ayarlar. |
| [SendChunked](../../aspose.email.clients.exchange.dav/exchangeclient/sendchunked) { get; set; } | [yığın halinde gönder] olup olmadığını belirten bir değer alır veya ayarlar. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | İşlem zaman aşımına uğramadan önce beklenecek milisaniye sayısını alır veya ayarlar. Varsayılan değer 100.000 milisaniyedir (100 saniye). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | Günlük dosyası adında tarihin kullanılması gerekip gerekmediğini gösteren değeri alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage)(string, MailMessage) | Posta mesajını belirtilen klasöre yükler |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage_1)(string, MailMessage, bool) | Posta mesajını belirtilen klasöre yükler |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Belirtilen klasörlerin içeriğini yedekler |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | Belirtilen klasörlerin içeriğini yedekler |
| [CreateContact](../../aspose.email.clients.exchange.dav/exchangeclient/createcontact)(Contact) | Exchange deposunda bir kişi öğesi oluşturur. |
| [CreateFolder](../../aspose.email.clients.exchange.dav/exchangeclient/createfolder)(string, string) | Belirtilen üst klasörde belirtilen ada sahip yeni klasörü oluşturur. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_1)(Contact) | Kişiyi siler. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact)(MapiContact) | Kişiyi siler. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_2)(string) | Kişiyi siler. |
| [DeleteFolder](../../aspose.email.clients.exchange.dav/exchangeclient/deletefolder)(string) | klasörünü siler |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage)(string) | Posta mesajını siler. |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage_1)(string, bool) | Posta mesajını siler. |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilişkili uygulama tanımlı görevleri gerçekleştirir. |
| [FetchAttachment](../../aspose.email.clients.exchange.dav/exchangeclient/fetchattachment)(string) | Ekini getirir |
| [FetchMapiMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmapimessage)(string) | Belirtilen uri. ile mapi mesajını getirir |
| [FetchMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmessage)(string) | Belirtilen uri. ile posta mesajını getirir |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists)(string, string) | Belirtilen klasörün var olup olmadığını kontrol eder. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | Belirtilen klasörün var olup olmadığını kontrol eder. |
| [GetContacts](../../aspose.email.clients.exchange.dav/exchangeclient/getcontacts)(string) | server üzerinde belirtilen klasörde bulunan kişileri listeler |
| [GetFolderInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getfolderinfo)(string) | Klasör bilgilerini alır. |
| [GetMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxes)() | Genel adres listesindeki posta kutularını listeler. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo)() | Posta kutusunun bilgilerini alın |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo_1)(string) | Posta kutusu bilgilerini alır |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize)() | Maibox boyutunu alın |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize_1)(string) | Maibox boyutunu alın |
| [GetVersionInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getversioninfo)() | Exchange sunucusu sürümünü döndürür info |
| [ListContacts](../../aspose.email.clients.exchange.dav/exchangeclient/listcontacts)(string) | server üzerinde belirtilen klasörde bulunan kişileri listeler |
| [ListMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/listmailboxes)() | Genel adres listesindeki posta kutularını listeler. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages)(string) | Mesajları listeler. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_3)(string, bool) | Belirtilen klasördeki iletileri listeleyin |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_1)(string, ExchangeListMessagesOptions) | Belirtilen klasördeki posta mesajını listeler. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_4)(string, int) | Mesajları listeler. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_6)(string, string) | Mesajları listeler. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_5)(string, int, ExchangeListMessagesOptions) | Belirtilen klasördeki iletileri listeleyin |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_2)(string, MailQuery, bool) | Mesajları listeler. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_7)(string, string, bool) | Mesajları listeler. |
| [ListMessagesById](../../aspose.email.clients.exchange.dav/exchangeclient/listmessagesbyid)(string, string) | İletileri kimliğe göre listeler. |
| [ListPublicFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listpublicfolders)() | Kök ortak klasöründen ortak klasörlerin koleksiyonunu alır |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | parent öğesinden alt ortak klasörlerin koleksiyonunu alır |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders_1)(string) | parent öğesinden alt klasörlerin koleksiyonunu alır |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems_1)(string, params string[]) | Öğeleri taşır. |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems)(string, bool, params string[]) | Öğeleri taşır. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage)(ExchangeMessageInfo, string) | İletiyi taşır. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_3)(string, string) | İletiyi taşır. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_1)(ExchangeMessageInfo, string, bool) | İletiyi taşır. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_2)(string, bool, string) | İletiyi taşır. |
| [ResolveContacts](../../aspose.email.clients.exchange.dav/exchangeclient/resolvecontacts)(string) | Belirsiz posta kutusu görünen adlarını çözer. Not: maksimum döndürülen kişi sayısı 100'dür. Bu, kullanılan değişim komutunun bir kısıtlamasıdır. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_1)(PersonalStorage, RestoreOptions) | Verilen kişisel depolama alanından değişim klasörlerini geri yükler. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_3)(Stream, RestoreOptions) | Verilen kişisel depolama alanından değişim klasörlerini geri yükler. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_5)(string, RestoreOptions) | Belirtilen kişisel depolama dosyasından değişim klasörlerini geri yükler. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore)(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) | Belirtilen değişim klasörlerini verilen kişisel depolama alanından geri yükler. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_2)(Stream, ExchangeFolderInfoCollection, RestoreOptions) | Belirtilen değişim klasörlerini verilen kişisel depolama alanından geri yükler. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_4)(string, ExchangeFolderInfoCollection, RestoreOptions) | Belirtilen kişisel depolama dosyasından belirtilen değişim klasörlerini geri yükler. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage)(string, Stream) | Mesajı kaydeder. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage_1)(string, string) | uri tarafından belirtilen posta mesajını yerel dosya sistemine kaydeder. Posta iletisi dosyası, RFC 822 uyumlu biçimdir (EML).  posta mesajı dosyalarını ayrıştırmak istiyorsanız,[`MailMessage`](../../aspose.email/mailmessage). |
| [Send](../../aspose.email.clients.exchange.dav/exchangeclient/send)(MailMessage) | Posta mesajını gönderir. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag)(string) | Belirtilen iletiyi okundu olarak işaretler. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag_1)(string, bool) | Belirtilen iletiyi okundu olarak işaretler. |

### Ayrıca bakınız

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../aspose.email.clients.exchange.dav)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
