---
title: SmtpClient
second_title: Aspose.Email for .NET API Referansı
description: Uygulamaların Basit Posta Aktarım Protokolü SMTP kullanarak mesaj göndermesine izin verir.
type: docs
weight: 17030
url: /tr/net/aspose.email.clients.smtp/smtpclient/
---
## SmtpClient class

Uygulamaların Basit Posta Aktarım Protokolü (SMTP) kullanarak mesaj göndermesine izin verir.

```csharp
public sealed class SmtpClient : EmailClient, IAsyncSmtpClient, IMailTransferAgent
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [SmtpClient](smtpclient#constructor)() | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_1)(Configuration) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) yapılandırma dosyası ayarlarını kullanarak sınıfı. |
| [SmtpClient](smtpclient#constructor_2)(string) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_4)(string, int) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_3)(string, SecurityOptions) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_5)(string, int, SecurityOptions) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_12)(string, string, ITokenProvider) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_14)(string, string, string) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_6)(string, int, string, ITokenProvider) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_8)(string, int, string, string) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_13)(string, string, ITokenProvider, SecurityOptions) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_16)(string, string, string, bool) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_15)(string, string, string, SecurityOptions) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_7)(string, int, string, ITokenProvider, SecurityOptions) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_10)(string, int, string, string, bool) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_9)(string, int, string, string, SecurityOptions) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_17)(string, string, string, bool, SecurityOptions) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |
| [SmtpClient](smtpclient#constructor_11)(string, int, string, string, bool, SecurityOptions) | Yeni bir örneğini başlatır[`SmtpClient`](../smtpclient) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Erişim belirtecini alır veya ayarlar. |
| [AllowedAuthentication](../../aspose.email.clients.smtp/smtpclient/allowedauthentication) { get; set; } | Kullanıcı kimlik doğrulama türleri tarafından izin verilenlerin numaralandırmasını alır veya ayarlar |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | İstemci sertifikaları koleksiyonunu içerir |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Birden çok iş parçacığı ortamında bağlantı ayırma modunu tanımlayan değeri alır veya ayarlar Aşağıdaki bağlantı türleri vardır: - Ana bağlantı, posta istemcisi ile birlikte oluşturulan ve atılan bağlantıdır.Manuel olarak oluşturulamaz veya atılamaz. - Varsayılan bağlantı, bazı iş parçacıkları için varsayılan bağlantıdır. Varsayılan bağlantı varsa ve ConnectionAsgmtMode izin veriyorsa, bu iş parçacığında yürütülen tüm e-posta istemcisi yöntemleri örtük olarak bu bağlantıyı kullanır. İş parçacığı başına yalnızca bir varsayılan bağlantı olabilir. Manuel veya otomatik olarak oluşturulabilir. EmailClient.ConnectionAsgmtMode özelliğine bağlıdır. Bu bağlantılar EmailClient.CreateConnection(createAsDefaultConnection = true) yöntemiyle manuel olarak oluşturulabilir. Varsayılan bağlantı kullanılmazsa (bağlantı ayırma moduna bağlıdır), bunun yerine dolaylı olarak ana bağlantı kullanılır. - Bağımsız bağlantılar, iş parçacıklarına bağlı değiller. Elle oluşturulabilirler ve açıkça yöntem parametresi olarak kullanılmaları gerekir. Bu bağlantılar, EmailClient.CreateConnection() yöntemiyle veya EmailClient.CreateConnection(createAsDefaultConnection = false) yöntemiyle manuel olarak oluşturulabilir. Aşağıdaki bağlantı ayırma türleri vardır: - ConnectionAsgmtType. Bu e-posta kipinde ConnectionAsgmtType.UseMainOrDefault varsayılan olarak kullanılır. E-posta istemcisi, varsayılan bağlantı oluşturulmamışsa veya bağlantı açıkça yöntem parametresi olarak geçirilmemişse, birden çok iş parçacığından gelen tüm işlemler için ana bağlantıyı kullanır. Ana bağlantı, e-posta istemcisi ile aynı anda oluşturulan bağlantıdır. Kullanıcı, CreateConnection yöntemi ile threadler için varsayılan bağlantılar oluşturabilir. Dizi için varsayılan bağlantı oluşturulursa, bu ileti dizisinde çağrılan tüm e-posta istemcisi yöntemleri için örtük olarak kullanılır. Dizi için varsayılan bağlantı oluşturulmazsa, bu ileti dizisinde çağrılan tüm e-posta istemcisi yöntemleri için ana bağlantı kullanılır. thread. Kullanıcı ayrıca CreateConnection yöntemiyle threadlerle bağlantılı olmayan (varsayılan bağlantılar değil) bağlantılar oluşturabilir. Kullanıcı başka bağlantılar kullanmak istiyorsa (ana değil ve varsayılan değil) bu bağlantıyı kullanmak istediği yöntemin parametresi olarak açıkça iletmelidir. Kullanıcı ayrıca herhangi bir sayıda bağlantı oluşturabilir. Varsayılan bağlantı, iş parçacığı başına yalnızca bir olabilir. Kullanıcı, çoklu görev programlaması için Thread nesnelerini kullanıyorsa, varsayılan bağlantıların doğru çalıştığını lütfen unutmayın. Kullanıcı ConnectionPool kullanıyorsa veya çok görevli programlama için Task nesneleri kullanıyorsa, bu mod bir programın yanlış davranışına yol açabilir. Bu sorunu önlemek için kullanıcının varsayılan bağlantıyı (kullanıyorsa) çalıştıran kodun sonuna manuel olarak atması gerekir. thread. - ConnectionAsgmtType.UseMain E-posta istemcisi, birden çok iş parçacığından gelen tüm işlemler için ana bağlantıyı kullanır. Ana bağlantı, e-posta istemcisi ile aynı anda oluşturulan bağlantıdır. Kullanıcı varsayılan bağlantılar oluşturamaz. Kullanıcı, CreateConnection yöntemiyle iş parçacıklarına bağlı olmayan (varsayılan bağlantılar değil) bağlantılar oluşturabilir. Kullanıcı başka bağlantılar kullanmak istiyorsa (ana değil ve varsayılan değil) bu bağlantıyı kullanmak istediği yöntemin parametresi olarak açıkça iletmelidir. Kullanıcı ayrıca herhangi bir sayıda bağlantı oluşturabilir. - ConnectionAsgmtType.UseDefault E-posta istemcisi, birden çok iş parçacığından gelen tüm işlemler için örtük olarak yalnızca varsayılan bağlantıları kullanır. Bu modda ana bağlantı kullanılmaz. Bir dizi için varsayılan bağlantı oluşturulmamışsa (e-posta istemcisi yönteminin ilk çağrılması), e-posta istemcisi, ilk işlem yürütülmeden önce örtük olarak dizi için varsayılan bağlantı oluşturur. Kullanıcı yapamaz otomatik olarak oluşturuldukları için CreateConnection yöntemiyle iş parçacıkları için varsayılan bağlantılar oluşturun. İş parçacığı için varsayılan bağlantı oluşturulduğunda, bu thread.read. içinde çağrılan tüm e-posta istemcisi yöntemleri için örtük olarak kullanılır. Kullanıcı ayrıca CreateConnection yöntemiyle iş parçacıklarıyla bağlantılı olmayan (varsayılan bağlantılar değil) bağlantılar oluşturabilir. Kullanıcı başka bağlantılar kullanmak istiyorsa (ana değil ve varsayılan değil) bu bağlantıyı kullanmak istediği yöntemin parametresi olarak açıkça iletmelidir. Kullanıcı ayrıca herhangi bir sayıda bağlantı oluşturabilir. Varsayılan bağlantı, iş parçacığı başına yalnızca bir olabilir. Kullanıcı, çoklu görev programlaması için Thread nesnelerini kullanıyorsa, varsayılan bağlantıların doğru çalıştığını lütfen unutmayın. Kullanıcı ConnectionPool kullanıyorsa veya çok görevli programlama için Task nesneleri kullanıyorsa, bu mod bir programın yanlış davranışına yol açabilir. Bu sorunu önlemek için kullanıcının iş parçacığında yürütülen kodun sonundaki varsayılan bağlantıyı manuel olarak atması gerekir. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Milisaniye cinsinden bağlantı denetimi süresi. Varsayılan değer 5 dak. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Çoklu bağlantı modunda bağlantı miktarını alır veya ayarlar |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Bağlantının mevcut durumunu alır. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | ConnectionAsgmtMode seçeneğine göre mevcut bağlantıyı alır |
| override [DefaultPort](../../aspose.email.clients.smtp/smtpclient/defaultport) { get; } | client için varsayılan bağlantı noktasını alır |
| [DeliveryMethod](../../aspose.email.clients.smtp/smtpclient/deliverymethod) { get; set; } | Teslim yöntemini alır veya ayarlar. |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Kaydediciyi etkinleştirmeye/devre dışı bırakmaya izin veren değeri alır veya ayarlar |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Bir bağlantı kurarken kullanılan karşılama zaman aşımını alır veya ayarlar. Lütfen, karşılama zaman aşımının sonsuz olamayacağını unutmayın. E-posta istemcileri yeterince uzun işlemler yürütebilir. Kullanıcıların kullanması gereken işlemlerin süresini sınırlamak için[`Timeout`](../../aspose.email.clients/emailclient/timeout)Emlak. Uzun süreli işlemleri engellememek için bu özelliğin değerlerinin uzun aralıklarla olması gerekir. Ancak bazı durumlarda, EmailClient yalnızca Timeout özelliğini kullanacaksa bağlantı kurulması uzun sürebilir. Örneğin, posta istemcisi bağlantı kurmak için otomatik modu kullanabilir. Bu modda, e-posta istemcisi bağlantı kurulana kadar tüm olası bağlantı parametrelerinden geçer. SMTP, IMAP ve POP3 sunucuları, doğru bağlantı kurulması durumunda istemciye tebrik dizesi gönderir. Sunucular, örtük veya açık (START TLS) SSL/TLS bağlantı başlatma kullanabilir. Bağlantı modu eşleşmezse (örneğin, sunucu örtük bir SSL bağlantısı bekler ancak istemci güvenli olmayan veya açık bir SSL bağlantısı kurmaya çalışırsa), sunucu bir karşılama dizesi göndermez. Bu durumda, kullanıcı zaman aşımı bir karşılama dizesine ulaşana kadar uzun bir süre bekler ve istemci bir sonraki bağlantı seçeneğine gider. Bu sorunu önlemek için TebrikTimeout özelliği tanıtıldı. Bu özellik, karşılama dizesi için zaman aşımını ayarlamanıza ve otomatik bağlantı kurma süresini kısaltmanıza olanak tanır. |
| [HelloMessage](../../aspose.email.clients.smtp/smtpclient/hellomessage) { get; set; } | Bir HELO/EHLO dizesi alır veya ayarlar. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Ana bilgisayar adını alır veya ayarlar. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Günlük dosyası adını alır veya ayarlar |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Parolayı alır veya ayarlar. Parola sınırlamaları, istemcinin bağlandığı sunucu uygulaması tarafından tanımlanır. |
| [PickupDirectoryLocation](../../aspose.email.clients.smtp/smtpclient/pickupdirectorylocation) { get; set; } | Uygulamaların yerel SMTP sunucusu tarafından işlenecek posta iletilerini kaydettiği dizini alır veya ayarlar. Lütfen unutmayın: yalnızca mutlak yola izin verilir. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Bağlantı noktasını alır veya ayarlar. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | client için proxy alır veya ayarlar |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Posta istemcisi için güvenlik modu |
| [SmtpQueueLocation](../../aspose.email.clients.smtp/smtpclient/smtpqueuelocation) { get; set; } | Uygulamaların SMTP kuyruğunda göndererek işlenecek posta mesajlarını kaydettiği dizini alır veya ayarlar. Lütfen dikkat: yalnızca mutlak yola izin verilir. |
| [SupportedAuthentication](../../aspose.email.clients.smtp/smtpclient/supportedauthentication) { get; } | Sunucu kimlik doğrulama türleri tarafından desteklenen numaralandırmayı alır |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Kullanılacak SSL/TLS şifreleme protokollerinin sürümlerini tanımlar. LÜTFEN DİKKAT EDİN, yalnızca .net çerçevesi tarafından desteklenen protokol sürümlerini ayarlayabilirsiniz. PROTOKOLÜN BAZI VERSİYONLARI GÜNCEL SÜRÜMÜNÜZ TARAFINDAN DESTEKLENMİYORSA .NET ÇERÇEVESİYLE GÖRÜNMEZLER YOK EDİLECEKLER VE ATLANACAKLAR. TLS GÜVENLİK SEVİYESİNİN AZALTILMASINA YOL AÇABİLİR. BU DURUMDA İSTİSNA OLUŞTURULMAZ!!! Lütfen, bkz.[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) daha fazla ayrıntı için belgeler. Lütfen kullanın[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) şifreleme protokollerini herhangi bir uyumluluk kontrolü yapmadan ayarlamak istiyorsanız bu yöntemi kullanın. Varsayılan değer: Tls &#x7C; 11 TL &#x7C; 12 TL &#x7C; Tls13 (mevcut .net çerçeve sürümünüz bu TLS sürümlerini destekliyorsa) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Posta işlemleri için zaman aşımını alır veya ayarlar |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Erişim belirtecinin alınmasına izin veren TokenProvider'ı alır veya ayarlar. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Kimlik doğrulamanın kullanılıp kullanılmadığını gösterir. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Günlük dosyası adında tarihin kullanılması gerekip gerekmediğini gösteren değeri alır veya ayarlar. |
| override [UseDefaultCredentials](../../aspose.email.clients.smtp/smtpclient/usedefaultcredentials) { get; set; } | Varsayılan Kimlik Bilgilerinin isteklerle gönderilip gönderilmediğini denetleyen bir Boole değeri alır veya ayarlar. |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | İstemcinin yoğun yüklü işlemler için birden çok bağlantı kullanması gerekip gerekmediğini gösteren değeri alır veya ayarlar. Bu modun kullanılmasının gerekli olmadığını lütfen unutmayın, performans artışına yol açmalıdır. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Ardışık düzen modunun etkin olup olmadığını gösteren nesneyi alır veya ayarlar. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Kullanıcı adını alır veya ayarlar. |
| [UseTnef](../../aspose.email.clients.smtp/smtpclient/usetnef) { get; set; } | İletilerin TNEF biçiminde gönderilip gönderilmediğini denetleyen bir boole değeri alır veya ayarlar. Bir ileti yüklenirken artık iletinin TNEF biçiminde gönderildiğini unutmayın. Bir ileti tnef içerir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | İş parçacıklarına bağlı olmayan işlemler için yeni bağımsız bağlantı oluşturur (varsayılan bağlantı değil). Bu yöntemin çağrılması, CreateConnection(createAsDefaultConnection = false) çağrısına benzer Lütfen EmailClient.ConnectionAsgmtMode özelliğine ilişkin belgelerde daha fazla bilgi edinin. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | İşlemler için yeni (varsayılan veya bağımsız) bağlantı oluşturur. Lütfen EmailClient.ConnectionAsgmtMode özelliğine ilişkin belgelerde daha fazla bilgi edinin. |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Bir sunucu ile tüm işlemleri sonlandırır. |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_3)(string, MailAddressCollection, MailMessage) | Belirtilen mesajı alıcıya iletir |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_4)(string, MailAddressCollection, Stream) | Belirtilen mesajı alıcıya iletir |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_5)(string, string, MailMessage) | Belirtilen mesajı alıcıya iletir |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward)(IConnection, string, MailAddressCollection, MailMessage) | Belirtilen mesajı alıcıya iletir |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_1)(IConnection, string, MailAddressCollection, Stream) | Belirtilen mesajı alıcıya iletir |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_2)(IConnection, string, string, MailMessage) | Belirtilen mesajı alıcıya iletir |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_6)(string, MailAddressCollection, MailMessage) | Belirtilen mesajı alıcıya iletir |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_8)(string, MailAddressCollection, Stream) | Belirtilen mesajı alıcıya iletir |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_10)(string, string, MailMessage) | Belirtilen mesajı alıcıya iletir |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync)(IConnection, string, MailAddressCollection, MailMessage) | Belirtilen mesajı alıcıya iletir |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_2)(IConnection, string, MailAddressCollection, Stream) | Belirtilen mesajı alıcıya iletir |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_4)(IConnection, string, string, MailMessage) | Belirtilen mesajı alıcıya iletir |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_7)(string, MailAddressCollection, MailMessage, CancellationToken) | Belirtilen mesajı alıcıya iletir |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_9)(string, MailAddressCollection, Stream, CancellationToken) | Belirtilen mesajı alıcıya iletir |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_11)(string, string, MailMessage, CancellationToken) | Belirtilen mesajı alıcıya iletir |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_1)(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) | Belirtilen mesajı alıcıya iletir |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_3)(IConnection, string, MailAddressCollection, Stream, CancellationToken) | Belirtilen mesajı alıcıya iletir |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_5)(IConnection, string, string, MailMessage, CancellationToken) | Belirtilen mesajı alıcıya iletir |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop)() | 'İşlem yok' komutu |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop_1)(IConnection) | 'İşlem yok' komutu |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync)() | 'İşlem yok' komutu |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_3)(CancellationToken) | 'İşlem yok' komutu |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_1)(IConnection) | 'İşlem yok' komutu |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_2)(IConnection, CancellationToken) | 'İşlem yok' komutu |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Günlük ayarlarını varsayılana sıfırlar. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_8)(IEnumerable&lt;MailMessage&gt;) | Belirtilen mesajları gönderin. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_5)(MailMessage) | Belirtilen iletiyi gönderin. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_6)(MailMessageCollection) | Belirtilen ileti koleksiyonunu gönderin. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_7)(params MailMessage[]) | Belirtilen iletiyi gönderin. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_3)(IConnection, IEnumerable&lt;MailMessage&gt;) | Belirtilen mesajları gönderin. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send)(IConnection, MailMessage) | Belirtilen iletiyi gönderin. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_1)(IConnection, MailMessageCollection) | Belirtilen ileti koleksiyonunu gönderin. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_2)(IConnection, params MailMessage[]) | Belirtilen iletiyi gönderin. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_9)(string, string, string, string) | Belirtilen mesajı oluşturur ve gönderir. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_4)(IConnection, string, string, string, string) | Belirtilen mesajı oluşturur ve gönderir. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_16)(IEnumerable&lt;MailMessage&gt;) | Belirtilen mesajları gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_11)(MailMessage) | Belirtilen iletiyi gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_13)(MailMessageCollection) | Belirtilen ileti koleksiyonunu gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_15)(params MailMessage[]) | Belirtilen iletiyi gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_10)(SmtpSend) |  |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_20)(CancellationToken, params MailMessage[]) | Belirtilen iletiyi gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_5)(IConnection, IEnumerable&lt;MailMessage&gt;) | Belirtilen mesajları gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync)(IConnection, MailMessage) | Belirtilen iletiyi gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_2)(IConnection, MailMessageCollection) | Belirtilen ileti koleksiyonunu gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_4)(IConnection, params MailMessage[]) | Belirtilen iletiyi gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_17)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | Belirtilen mesajları gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_12)(MailMessage, CancellationToken) | Belirtilen iletiyi gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_14)(MailMessageCollection, CancellationToken) | Belirtilen ileti koleksiyonunu gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_9)(IConnection, CancellationToken, params MailMessage[]) | Belirtilen iletiyi gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_6)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Belirtilen mesajları gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_1)(IConnection, MailMessage, CancellationToken) | Belirtilen iletiyi gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_3)(IConnection, MailMessageCollection, CancellationToken) | Belirtilen ileti koleksiyonunu gönderin. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_18)(string, string, string, string) | Belirtilen mesajı oluşturur ve gönderir. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_7)(IConnection, string, string, string, string) | Belirtilen mesajı oluşturur ve gönderir. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_19)(string, string, string, string, CancellationToken) | Belirtilen mesajı oluşturur ve gönderir. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_8)(IConnection, string, string, string, string, CancellationToken) | Belirtilen mesajı oluşturur ve gönderir. |
| [SendToQueue](../../aspose.email.clients.smtp/smtpclient/sendtoqueue)(IEnumerable&lt;MailMessage&gt;) | İletileri sıraya ekleyin |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Kullanılacak SSL/TLS şifreleme protokollerinin sürümlerini tanımlar. Bu yöntem güvenli değildir ve şifreleme protokollerini herhangi bir uyumluluk denetimi yapmadan ayarlar. Kullan[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) yalnızca .net çerçevesi tarafından kesinlikle desteklenen protokolleri güvenli bir şekilde ayarlama özelliği. Geçerli .net çerçeveniz bu güvenlik düzeyini desteklemiyorsa, sunucuyla bağlantı kurmaya çalışırken bir istisna atılacağını lütfen unutmayın. |
| override [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials)() | Kimlik doğrulamasını yürütür |
| [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials_1)(IConnection) | Kimlik doğrulamasını yürütür |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync)() | Kimlik doğrulamasını yürütür |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Kimlik doğrulamasını yürütür |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Kimlik doğrulamasını yürütür |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Kimlik doğrulamasını yürütür |
| static [CreateAsync](../../aspose.email.clients.smtp/smtpclient/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Yeni bir örneğini oluşturur[`SmtpClient`](../smtpclient) class |

### Ayrıca bakınız

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncSmtpClient](../iasyncsmtpclient)
* interface [IMailTransferAgent](../imailtransferagent)
* ad alanı [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
