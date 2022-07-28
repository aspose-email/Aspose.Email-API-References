---
title: IAsyncImapClient
second_title: Aspose.Email for .NET API Referansı
description: Uygulamaların İnternet İleti Erişim Protokolünü IMAP kullanarak iletilerine erişmesine ve bunları değiştirmesine izin verir.
type: docs
weight: 16240
url: /tr/net/aspose.email.clients.imap/iasyncimapclient/
---
## IAsyncImapClient interface

Uygulamaların İnternet İleti Erişim Protokolü'nü (IMAP) kullanarak iletilerine erişmesine ve bunları değiştirmesine izin verir.

```csharp
public interface IAsyncImapClient
```

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/addmessageflagsasync)(ImapChangeMessageFlags) | İletiye bayrak ekler |
| [AppendMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessageasync)(MailMessage, string, IConnection, CancellationToken) | Posta mesajını belirtilen klasöre yükler |
| [AppendMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessagesasync)(IEnumerable&lt;MailMessage&gt;, string, IConnection, CancellationToken) | Posta mesajlarını geçerli klasöre yükler |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync)(ImapFolderInfoCollection, Stream, BackupSettings, IConnection, CancellationToken) | Belirtilen klasörlerin içeriğini yedekler |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync_1)(ImapFolderInfoCollection, string, BackupSettings, IConnection, CancellationToken) | Belirtilen klasörlerin içeriğini yedekler |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/changemessageflagsasync)(ImapChangeMessageFlags) | İletinin bayraklarını değiştirir |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/iasyncimapclient/clientcapabilitiesasync)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | İstemci tarafından hangi uzantıların desteklendiğini sunucuya bildirir. Lütfen bu işlemin yalnızca sunucunun RFC5161'i desteklemesi durumunda çalıştığını unutmayın Daha fazlasını görün https://tools.ietf.org/html/rfc5161 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/iasyncimapclient/commitdeletesasync)(ImapUniqueIdParameterSet) | Silme işlemlerini gerçekleştir |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync)(int, string, IConnection, CancellationToken) | İletiyi kopyalar |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync_1)(string, string, IConnection, CancellationToken) | Mesajı kopyalar. |
| [CopyMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessagesasync)(ImapCopyMessages) | Mesajları kopyalayın. |
| [CreateFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/createfolderasync)(string, IConnection, CancellationToken) | Belirtilen ada sahip bir klasör oluşturur. |
| [DeleteFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/deletefolderasync)(string, IConnection, CancellationToken) | Belirtilen bir klasörü siler. Bu yöntem IMAP DELETE komutunu temsil eder. |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/deletemessagesasync)(ImapDeleteMessages) | Belirtilen benzersiz tanımlayıcıya sahip bir iletiyi silinmiş olarak işaretler ve kullanıcı bunu belirtirse silme işlemlerini gerçekleştirir. Bu yöntem yalnızca sunucu UIDPLUS uzantısını destekliyorsa çalışır. Lütfen daha fazlasını okuyun https://tools.ietf.org/html/rfc4315 |
| [ExistFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/existfolderasync)(string, IConnection, CancellationToken) | Bu klasörün var olup olmadığını kontrol edin |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchattachmentasync)(int, string, IConnection, CancellationToken) | Belirtilen eki getirir. |
| [FetchMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchmessagesasync)(ImapFetchMessages) | İletileri eşzamansız olarak getirir |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/iasyncimapclient/getfolderinfoasync)(string, IConnection, CancellationToken) | it öğesini seçmeden belirtilen klasör hakkındaki bilgileri döndürür |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/getmessagethreadsasync)(BaseSearchConditions, IConnection, CancellationToken) | İleti dizilerini alın. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/iasyncimapclient/getnamespacesasync)(IConnection, CancellationToken) | Bir sunucuda bulunan ad alanlarını alır. |
| [GetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotaasync)(string, IConnection, CancellationToken) | Kota bilgisini alır |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotarootasync)(string, IConnection, CancellationToken) | mailbox için kota kök bilgilerini alır |
| [IntroduceClientAsync](../../aspose.email.clients.imap/iasyncimapclient/introduceclientasync)(ImapIdentificationInfo, IConnection, CancellationToken) | İstemci bilgilerini bir sunucuya sunar. |
| [ListFoldersAsync](../../aspose.email.clients.imap/iasyncimapclient/listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, IConnection, CancellationToken) | Belirtilen klasördeki alt klasörlerin listesini alır |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync)(int, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Bir mesaj hakkında bilgi alır. |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync_1)(string, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Bir mesaj hakkında bilgi alır. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync)(MailQuery, string, int, IConnection, CancellationToken) | Geçerli klasördeki iletilerin listesini alır. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync_1)(string, long, bool, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | Belirtilen klasördeki iletilerin listesini alır |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync_1)(int, int, PageSettings, CancellationToken) | Mesajların listesini alır |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync)(MailQuery, PageInfo, PageSettings, CancellationToken) | Mesajların listesini alır |
| [MoveFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/movefolderasync)(string, string, IConnection, CancellationToken) | Belirtilen klasörü ve alt klasörlerini yeni konuma taşır. |
| [MoveMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/movemessagesasync)(ImapMoveMessages) | Mesajları taşır. |
| [NoopAsync](../../aspose.email.clients.imap/iasyncimapclient/noopasync)(IConnection, CancellationToken) | 'İşlem yok' komutu |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/removemessageflagsasync)(ImapChangeMessageFlags) | İletisinin bayraklarını kaldırır |
| [RenameFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/renamefolderasync)(string, string, IConnection, CancellationToken) | Belirtilen klasörü yeni bir adla yeniden adlandırır |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/iasyncimapclient/requestcheckpointasync)(IConnection, CancellationToken) | Seçili olan posta kutusunun bir kontrol noktası ister. |
| [RestoreAsync](../../aspose.email.clients.imap/iasyncimapclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | Verilen kişisel depolama alanından imap klasörlerini geri yüklemeye başlar. |
| [ResumeMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState, CancellationToken) | Belirtilen klasör için ileti değişikliklerinin izlenmesini sürdürür. StartMonitoring yönteminden farklı olarak, tüm eksik posta kutusu değişikliklerini bulur ve onlar için geri aramayı arar. |
| [SelectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/selectfolderasync)(string, bool?, IConnection, CancellationToken) | Belirtilen klasörü seçer |
| [SetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/setquotaasync)(string, string, int, IConnection, CancellationToken) | Kota bilgisini ayarlar |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/sortmessagethreadsasync)(SortConditions, IConnection, CancellationToken) | İleti dizilerini sıralayın. |
| [StartMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/startmonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | Belirtilen klasör için ileti değişikliklerinin izlenmesini başlatır. |
| [StopMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/stopmonitoringasync)(string, CancellationToken) | Belirtilen klasör için mesaj değişikliklerinin izlenmesini durdurur. KlasörAdı null ise tüm klasörlerin izlenmesini durdurur. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/subscribefolderasync)(string, IConnection, CancellationToken) | Belirtilen posta kutusu adını sunucunun "etkin" posta kutuları grubuna ekleyen ABONE OL komutunu gönderdi. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync)(int, long, IConnection, CancellationToken) | Belirtilen sıra numarasına sahip bir mesajı silinmedi olarak işaretler |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync_1)(string, long, IConnection, CancellationToken) | Belirtilen sıra numarasına sahip bir mesajı silinmedi olarak işaretler. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unselectfolderasync)(bool, IConnection, CancellationToken) | Halihazırda seçili olan klasörün seçimini kaldırır. doNotExpunge özelliği doğruysa, silindi olarak işaretlenen tüm iletiler kaldırılır, aksi takdirde silme iptal edilir. Lütfen bu işlemin yalnızca sunucunun RFC3691 'yi desteklemesi durumunda çalıştığını unutmayın. Daha fazla https://tools. ietf.org/html/rfc3691 |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unsubscribefolderasync)(string, IConnection, CancellationToken) | Belirtilen posta kutusu adını sunucunun "etkin" posta kutuları kümesinden kaldıran UNSUBSCRIBE komutunu gönderdi |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/iasyncimapclient/validatecredentialsasync)(IConnection, CancellationToken) | Kimlik doğrulamasını yürütür |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
