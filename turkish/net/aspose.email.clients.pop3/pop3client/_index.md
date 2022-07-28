---
title: Pop3Client
second_title: Aspose.Email for .NET API Referansı
description: Uygulamaların Postane Protokolü Sürüm 3ü POP3 kullanarak iletilerine erişmesine ve bunları değiştirmesine izin verir.
type: docs
weight: 16880
url: /tr/net/aspose.email.clients.pop3/pop3client/
---
## Pop3Client class

Uygulamaların Postane Protokolü Sürüm 3'ü (POP3) kullanarak iletilerine erişmesine ve bunları değiştirmesine izin verir.

```csharp
public sealed class Pop3Client : EmailClient, IAsyncPop3Client
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Pop3Client](pop3client#constructor)() | Yeni bir örneğini başlatır[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_1)(string) | Yeni bir örneğini başlatır[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_3)(string, int) | Yeni bir örneğini başlatır[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_2)(string, SecurityOptions) | Yeni bir örneğini başlatır[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_4)(string, int, SecurityOptions) | Yeni bir örneğini başlatır[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_11)(string, string, string) | Yeni bir örneğini başlatır[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_6)(string, int, string, string) | Yeni bir örneğini başlatır[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_12)(string, string, string, SecurityOptions) | Yeni bir örneğini başlatır[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_5)(string, int, string, ITokenProvider, SecurityOptions) | Yeni bir örneğini başlatır[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_9)(string, int, string, string, RemoteCertificateValidationCallback) | Yeni bir örneğini başlatır[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_7)(string, int, string, string, SecurityOptions) | Yeni bir örneğini başlatır[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_8)(string, int, string, string, bool, SecurityOptions) | Yeni bir örneğini başlatır[`Pop3Client`](../pop3client) class |
| [Pop3Client](pop3client#constructor_10)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | Yeni bir örneğini başlatır[`Pop3Client`](../pop3client) class |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Erişim belirtecini alır veya ayarlar. |
| [AllowedAuthentication](../../aspose.email.clients.pop3/pop3client/allowedauthentication) { get; set; } | Kullanıcı kimlik doğrulama türleri tarafından izin verilenlerin numaralandırmasını alır veya ayarlar |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | İstemci sertifikaları koleksiyonunu içerir |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Birden çok iş parçacığı ortamında bağlantı ayırma modunu tanımlayan değeri alır veya ayarlar Aşağıdaki bağlantı türleri vardır: - Ana bağlantı, posta istemcisi ile birlikte oluşturulan ve atılan bağlantıdır.Manuel olarak oluşturulamaz veya atılamaz. - Varsayılan bağlantı, bazı iş parçacıkları için varsayılan bağlantıdır. Varsayılan bağlantı varsa ve ConnectionAsgmtMode izin veriyorsa, bu iş parçacığında yürütülen tüm e-posta istemcisi yöntemleri örtük olarak bu bağlantıyı kullanır. İş parçacığı başına yalnızca bir varsayılan bağlantı olabilir. Manuel veya otomatik olarak oluşturulabilir. EmailClient.ConnectionAsgmtMode özelliğine bağlıdır. Bu bağlantılar EmailClient.CreateConnection(createAsDefaultConnection = true) yöntemiyle manuel olarak oluşturulabilir. Varsayılan bağlantı kullanılmazsa (bağlantı ayırma moduna bağlıdır), bunun yerine dolaylı olarak ana bağlantı kullanılır. - Bağımsız bağlantılar, iş parçacıklarına bağlı değiller. Elle oluşturulabilirler ve açıkça yöntem parametresi olarak kullanılmaları gerekir. Bu bağlantılar, EmailClient.CreateConnection() yöntemiyle veya EmailClient.CreateConnection(createAsDefaultConnection = false) yöntemiyle manuel olarak oluşturulabilir. Aşağıdaki bağlantı ayırma türleri vardır: - ConnectionAsgmtType. Bu e-posta kipinde ConnectionAsgmtType.UseMainOrDefault varsayılan olarak kullanılır. E-posta istemcisi, varsayılan bağlantı oluşturulmamışsa veya bağlantı açıkça yöntem parametresi olarak geçirilmemişse, birden çok iş parçacığından gelen tüm işlemler için ana bağlantıyı kullanır. Ana bağlantı, e-posta istemcisi ile aynı anda oluşturulan bağlantıdır. Kullanıcı, CreateConnection yöntemi ile threadler için varsayılan bağlantılar oluşturabilir. Dizi için varsayılan bağlantı oluşturulursa, bu ileti dizisinde çağrılan tüm e-posta istemcisi yöntemleri için örtük olarak kullanılır. Dizi için varsayılan bağlantı oluşturulmazsa, bu ileti dizisinde çağrılan tüm e-posta istemcisi yöntemleri için ana bağlantı kullanılır. thread. Kullanıcı ayrıca CreateConnection yöntemiyle threadlerle bağlantılı olmayan (varsayılan bağlantılar değil) bağlantılar oluşturabilir. Kullanıcı başka bağlantılar kullanmak istiyorsa (ana değil ve varsayılan değil) bu bağlantıyı kullanmak istediği yöntemin parametresi olarak açıkça iletmelidir. Kullanıcı ayrıca herhangi bir sayıda bağlantı oluşturabilir. Varsayılan bağlantı, iş parçacığı başına yalnızca bir olabilir. Kullanıcı, çoklu görev programlaması için Thread nesnelerini kullanıyorsa, varsayılan bağlantıların doğru çalıştığını lütfen unutmayın. Kullanıcı ConnectionPool kullanıyorsa veya çok görevli programlama için Task nesneleri kullanıyorsa, bu mod bir programın yanlış davranışına yol açabilir. Bu sorunu önlemek için kullanıcının varsayılan bağlantıyı (kullanıyorsa) çalıştıran kodun sonuna manuel olarak atması gerekir. thread. - ConnectionAsgmtType.UseMain E-posta istemcisi, birden çok iş parçacığından gelen tüm işlemler için ana bağlantıyı kullanır. Ana bağlantı, e-posta istemcisi ile aynı anda oluşturulan bağlantıdır. Kullanıcı varsayılan bağlantılar oluşturamaz. Kullanıcı, CreateConnection yöntemiyle iş parçacıklarına bağlı olmayan (varsayılan bağlantılar değil) bağlantılar oluşturabilir. Kullanıcı başka bağlantılar kullanmak istiyorsa (ana değil ve varsayılan değil) bu bağlantıyı kullanmak istediği yöntemin parametresi olarak açıkça iletmelidir. Kullanıcı ayrıca herhangi bir sayıda bağlantı oluşturabilir. - ConnectionAsgmtType.UseDefault E-posta istemcisi, birden çok iş parçacığından gelen tüm işlemler için örtük olarak yalnızca varsayılan bağlantıları kullanır. Bu modda ana bağlantı kullanılmaz. Bir dizi için varsayılan bağlantı oluşturulmamışsa (e-posta istemcisi yönteminin ilk çağrılması), e-posta istemcisi, ilk işlem yürütülmeden önce örtük olarak dizi için varsayılan bağlantı oluşturur. Kullanıcı yapamaz otomatik olarak oluşturuldukları için CreateConnection yöntemiyle iş parçacıkları için varsayılan bağlantılar oluşturun. İş parçacığı için varsayılan bağlantı oluşturulduğunda, bu thread.read. içinde çağrılan tüm e-posta istemcisi yöntemleri için örtük olarak kullanılır. Kullanıcı ayrıca CreateConnection yöntemiyle iş parçacıklarıyla bağlantılı olmayan (varsayılan bağlantılar değil) bağlantılar oluşturabilir. Kullanıcı başka bağlantılar kullanmak istiyorsa (ana değil ve varsayılan değil) bu bağlantıyı kullanmak istediği yöntemin parametresi olarak açıkça iletmelidir. Kullanıcı ayrıca herhangi bir sayıda bağlantı oluşturabilir. Varsayılan bağlantı, iş parçacığı başına yalnızca bir olabilir. Kullanıcı, çoklu görev programlaması için Thread nesnelerini kullanıyorsa, varsayılan bağlantıların doğru çalıştığını lütfen unutmayın. Kullanıcı ConnectionPool kullanıyorsa veya çok görevli programlama için Task nesneleri kullanıyorsa, bu mod bir programın yanlış davranışına yol açabilir. Bu sorunu önlemek için kullanıcının iş parçacığında yürütülen kodun sonundaki varsayılan bağlantıyı manuel olarak atması gerekir. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Milisaniye cinsinden bağlantı denetimi süresi. Varsayılan değer 5 dak. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Çoklu bağlantı modunda bağlantı miktarını alır veya ayarlar |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Bağlantının mevcut durumunu alır. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | ConnectionAsgmtMode seçeneğine göre mevcut bağlantıyı alır |
| override [DefaultPort](../../aspose.email.clients.pop3/pop3client/defaultport) { get; } | client için varsayılan bağlantı noktasını alır |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Kaydediciyi etkinleştirmeye/devre dışı bırakmaya izin veren değeri alır veya ayarlar |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Bir bağlantı kurarken kullanılan karşılama zaman aşımını alır veya ayarlar. Lütfen, karşılama zaman aşımının sonsuz olamayacağını unutmayın. E-posta istemcileri yeterince uzun işlemler yürütebilir. Kullanıcıların kullanması gereken işlemlerin süresini sınırlamak için[`Timeout`](../../aspose.email.clients/emailclient/timeout)Emlak. Uzun süreli işlemleri engellememek için bu özelliğin değerlerinin uzun aralıklarla olması gerekir. Ancak bazı durumlarda, EmailClient yalnızca Timeout özelliğini kullanacaksa bağlantı kurulması uzun sürebilir. Örneğin, posta istemcisi bağlantı kurmak için otomatik modu kullanabilir. Bu modda, e-posta istemcisi bağlantı kurulana kadar tüm olası bağlantı parametrelerinden geçer. SMTP, IMAP ve POP3 sunucuları, doğru bağlantı kurulması durumunda istemciye tebrik dizesi gönderir. Sunucular, örtük veya açık (START TLS) SSL/TLS bağlantı başlatma kullanabilir. Bağlantı modu eşleşmezse (örneğin, sunucu örtük bir SSL bağlantısı bekler ancak istemci güvenli olmayan veya açık bir SSL bağlantısı kurmaya çalışırsa), sunucu bir karşılama dizesi göndermez. Bu durumda, kullanıcı zaman aşımı bir karşılama dizesine ulaşana kadar uzun bir süre bekler ve istemci bir sonraki bağlantı seçeneğine gider. Bu sorunu önlemek için TebrikTimeout özelliği tanıtıldı. Bu özellik, karşılama dizesi için zaman aşımını ayarlamanıza ve otomatik bağlantı kurma süresini kısaltmanıza olanak tanır. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Ana bilgisayar adını alır veya ayarlar. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Günlük dosyası adını alır veya ayarlar |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Parolayı alır veya ayarlar. Parola sınırlamaları, istemcinin bağlandığı sunucu uygulaması tarafından tanımlanır. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Bağlantı noktasını alır veya ayarlar. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | client için proxy alır veya ayarlar |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Posta istemcisi için güvenlik modu |
| [SupportedAuthentication](../../aspose.email.clients.pop3/pop3client/supportedauthentication) { get; } | Sunucu kimlik doğrulama türleri tarafından desteklenen numaralandırmayı alır |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Kullanılacak SSL/TLS şifreleme protokollerinin sürümlerini tanımlar. LÜTFEN DİKKAT EDİN, yalnızca .net çerçevesi tarafından desteklenen protokol sürümlerini ayarlayabilirsiniz. PROTOKOLÜN BAZI VERSİYONLARI GÜNCEL SÜRÜMÜNÜZ TARAFINDAN DESTEKLENMİYORSA .NET ÇERÇEVESİYLE GÖRÜNMEZLER YOK EDİLECEKLER VE ATLANACAKLAR. TLS GÜVENLİK SEVİYESİNİN AZALTILMASINA YOL AÇABİLİR. BU DURUMDA İSTİSNA OLUŞTURULMAZ!!! Lütfen, bkz.[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) daha fazla ayrıntı için belgeler. Lütfen kullanın[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) şifreleme protokollerini herhangi bir uyumluluk kontrolü yapmadan ayarlamak istiyorsanız bu yöntemi kullanın. Varsayılan değer: Tls &#x7C; 11 TL &#x7C; 12 TL &#x7C; Tls13 (mevcut .net çerçeve sürümünüz bu TLS sürümlerini destekliyorsa) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Posta işlemleri için zaman aşımını alır veya ayarlar |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Erişim belirtecinin alınmasına izin veren TokenProvider'ı alır veya ayarlar. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Kimlik doğrulamanın kullanılıp kullanılmadığını gösterir. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Günlük dosyası adında tarihin kullanılması gerekip gerekmediğini gösteren değeri alır veya ayarlar. |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials) { get; set; } | Varsayılan Kimlik Bilgilerinin isteklerle gönderilip gönderilmediğini denetleyen bir Boole değeri alır veya ayarlar. Bu seçenek YALNIZCA NTLM kimlik doğrulamasıyla kullanılır! |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | İstemcinin yoğun yüklü işlemler için birden çok bağlantı kullanması gerekip gerekmediğini gösteren değeri alır veya ayarlar. Bu modun kullanılmasının gerekli olmadığını lütfen unutmayın, performans artışına yol açmalıdır. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Ardışık düzen modunun etkin olup olmadığını gösteren nesneyi alır veya ayarlar. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Kullanıcı adını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes)() | Silme işlemlerini gerçekleştir |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_1)(IConnection) | Silme işlemlerini gerçekleştir |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_2)(int) | Silme işlemlerini gerçekleştir |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync)() | Silme işlemlerini gerçekleştir |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_5)(CancellationToken) | Silme işlemlerini gerçekleştir |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_1)(IConnection) | Silme işlemlerini gerçekleştir |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_3)(int) | Silme işlemlerini gerçekleştir |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_2)(IConnection, CancellationToken) | Silme işlemlerini gerçekleştir |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_4)(int, CancellationToken) | Silme işlemlerini gerçekleştir |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | İş parçacıklarına bağlı olmayan işlemler için yeni bağımsız bağlantı oluşturur (varsayılan bağlantı değil). Bu yöntemin çağrılması, CreateConnection(createAsDefaultConnection = false) çağrısına benzer Lütfen EmailClient.ConnectionAsgmtMode özelliğine ilişkin belgelerde daha fazla bilgi edinin. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | İşlemler için yeni (varsayılan veya bağımsız) bağlantı oluşturur. Lütfen EmailClient.ConnectionAsgmtMode özelliğine ilişkin belgelerde daha fazla bilgi edinin. |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_2)(int) | İletiyi siler |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_3)(string) | İletiyi siler |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage)(IConnection, int) | İletiyi siler |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_1)(IConnection, string) | İletiyi siler |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_4)(int) | İletiyi siler |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_6)(string) | İletiyi siler |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync)(IConnection, int) | İletiyi siler |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_2)(IConnection, string) | İletiyi siler |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_5)(int, CancellationToken) | İletiyi siler |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_7)(string, CancellationToken) | İletiyi siler |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_1)(IConnection, int, CancellationToken) | İletiyi siler |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_3)(IConnection, string, CancellationToken) | İletiyi siler |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages)() | Tüm mesajları siler |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages_1)(IConnection) | Tüm mesajları siler |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync)() | Tüm mesajları siler |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_3)(CancellationToken) | Tüm mesajları siler |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_1)(IConnection) | Tüm mesajları siler |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_2)(IConnection, CancellationToken) | Tüm mesajları siler |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Bir sunucu ile tüm işlemleri sonlandırır. |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_2)(int) | İletiyi getirir |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_3)(string) | İletiyi getirir |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage)(IConnection, int) | İletiyi getirir |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_1)(IConnection, string) | İletiyi getirir |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_4)(int) | İletiyi getirir |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_6)(string) | İletiyi getirir |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync)(IConnection, int) | İletiyi getirir |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_2)(IConnection, string) | İletiyi getirir |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_5)(int, CancellationToken) | İletiyi getirir |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_7)(string, CancellationToken) | İletiyi getirir |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_1)(IConnection, int, CancellationToken) | İletiyi getirir |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_3)(IConnection, string, CancellationToken) | İletiyi getirir |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_2)(IEnumerable&lt;int&gt;) | Mesajları getirir |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_3)(IEnumerable&lt;string&gt;) | Mesajları getirir |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | Mesajları getirir |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_1)(IConnection, IEnumerable&lt;string&gt;) | Mesajları getirir |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_4)(IEnumerable&lt;int&gt;) | İletileri eşzamansız olarak getirir |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_6)(IEnumerable&lt;string&gt;) | İletileri eşzamansız olarak getirir |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | İletileri eşzamansız olarak getirir |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_2)(IConnection, IEnumerable&lt;string&gt;) | İletileri eşzamansız olarak getirir |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_5)(IEnumerable&lt;int&gt;, CancellationToken) | İletileri eşzamansız olarak getirir |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_7)(IEnumerable&lt;string&gt;, CancellationToken) | İletileri eşzamansız olarak getirir |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_1)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | İletileri eşzamansız olarak getirir |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_3)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | İletileri eşzamansız olarak getirir |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo)() | Posta kutusu durumunu alır info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_3)(bool) | Posta kutusu durumunu alır info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_1)(IConnection) | Posta kutusu durumunu alır info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_2)(IConnection, bool) | Posta kutusu durumunu alır info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync)() | Posta kutusu durumunu alır info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_5)(bool) | Posta kutusu durumunu alır info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_7)(CancellationToken) | Posta kutusu durumunu alır info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_1)(IConnection) | Posta kutusu durumunu alır info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_6)(bool, CancellationToken) | Posta kutusu durumunu alır info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_2)(IConnection, bool) | Posta kutusu durumunu alır info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_4)(IConnection, CancellationToken) | Posta kutusu durumunu alır info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_3)(IConnection, bool, CancellationToken) | Posta kutusu durumunu alır info |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize)() | Posta kutusunun boyutunu alır |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize_1)(IConnection) | Posta kutusunun boyutunu alır |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync)() | Posta kutusunun boyutunu alır |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_3)(CancellationToken) | Posta kutusunun boyutunu alır |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_1)(IConnection) | Posta kutusunun boyutunu alır |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_2)(IConnection, CancellationToken) | Posta kutusunun boyutunu alır |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount)() | count mesajını alır |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_3)(bool) | count mesajını alır |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_1)(IConnection) | count mesajını alır |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_2)(IConnection, bool) | count mesajını alır |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync)() | count mesajını alır |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_5)(bool) | count mesajını alır |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_7)(CancellationToken) | count mesajını alır |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_1)(IConnection) | count mesajını alır |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_6)(bool, CancellationToken) | count mesajını alır |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_2)(IConnection, bool) | count mesajını alır |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_4)(IConnection, CancellationToken) | count mesajını alır |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_3)(IConnection, bool, CancellationToken) | count mesajını alır |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_2)(int) | İleti başlıklarını alır |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_3)(string) | İleti başlıklarını alır |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders)(IConnection, int) | İleti başlıklarını alır |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_1)(IConnection, string) | İleti başlıklarını alır |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_4)(int) | İleti başlıklarını alır |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_6)(string) | İleti başlıklarını alır |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync)(IConnection, int) | İleti başlıklarını alır |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_2)(IConnection, string) | İleti başlıklarını alır |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_5)(int, CancellationToken) | İleti başlıklarını alır |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_7)(string, CancellationToken) | İleti başlıklarını alır |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_1)(IConnection, int, CancellationToken) | İleti başlıklarını alır |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_3)(IConnection, string, CancellationToken) | İleti başlıklarını alır |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_4)(int) | Bu iletinin bilgilerini alır |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_6)(string) | Bu iletinin bilgilerini alır |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo)(IConnection, int) | Bu iletinin bilgilerini alır |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_2)(IConnection, string) | Bu iletinin bilgilerini alır |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_5)(int, Pop3ListFields) | Bu iletinin bilgilerini alır |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_7)(string, Pop3ListFields) | Bu iletinin bilgilerini alır |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_1)(IConnection, int, Pop3ListFields) | Bu iletinin bilgilerini alır |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_3)(IConnection, string, Pop3ListFields) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_8)(int) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_12)(string) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync)(IConnection, int) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_4)(IConnection, string) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_11)(int, CancellationToken) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_9)(int, Pop3ListFields) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_15)(string, CancellationToken) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_13)(string, Pop3ListFields) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_3)(IConnection, int, CancellationToken) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_1)(IConnection, int, Pop3ListFields) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_7)(IConnection, string, CancellationToken) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_5)(IConnection, string, Pop3ListFields) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_10)(int, Pop3ListFields, CancellationToken) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_14)(string, Pop3ListFields, CancellationToken) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_2)(IConnection, int, Pop3ListFields, CancellationToken) | Bu iletinin bilgilerini alır |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_6)(IConnection, string, Pop3ListFields, CancellationToken) | Bu iletinin bilgilerini alır |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_2)(int) | İletinin boyutunu alır |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_3)(string) | İletinin boyutunu alır |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize)(IConnection, int) | İletinin boyutunu alır |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_1)(IConnection, string) | İletinin boyutunu alır |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_4)(int) | İletinin boyutunu alır |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_6)(string) | İletinin boyutunu alır |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync)(IConnection, int) | İletinin boyutunu alır |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_2)(IConnection, string) | İletinin boyutunu alır |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_5)(int, CancellationToken) | İletinin boyutunu alır |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_7)(string, CancellationToken) | İletinin boyutunu alır |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_1)(IConnection, int, CancellationToken) | İletinin boyutunu alır |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_3)(IConnection, string, CancellationToken) | İletinin boyutunu alır |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid_1)(int) | Benzersiz id iletisini alır |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid)(IConnection, int) | Benzersiz id iletisini alır |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_2)(int) | Benzersiz id iletisini alır |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync)(IConnection, int) | Benzersiz id iletisini alır |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_3)(int, CancellationToken) | Benzersiz id iletisini alır |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_1)(IConnection, int, CancellationToken) | Benzersiz id iletisini alır |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages)() | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_11)(bool) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_1)(IConnection) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_12)(IEnumerable&lt;int&gt;) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_13)(IEnumerable&lt;string&gt;) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_10)(MailQuery) | Mesajları listeler. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_8)(Pop3ListFields) | Mesajları listeler. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_5)(IConnection, bool) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_6)(IConnection, IEnumerable&lt;int&gt;) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_7)(IConnection, IEnumerable&lt;string&gt;) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_4)(IConnection, MailQuery) | Mesajları listeler. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_2)(IConnection, Pop3ListFields) | Mesajları listeler. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_9)(Pop3ListFields, bool, MailQuery) | Mesajları listeler. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_3)(IConnection, Pop3ListFields, bool, MailQuery) | Mesajları listeler. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync)() | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_17)(bool) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_19)(CancellationToken) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_1)(IConnection) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_15)(MailQuery) | Mesajları listeler. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_11)(Pop3ListFields) | Mesajları listeler. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_18)(bool, CancellationToken) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_8)(IConnection, bool) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_10)(IConnection, CancellationToken) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_6)(IConnection, MailQuery) | Mesajları listeler. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_2)(IConnection, Pop3ListFields) | Mesajları listeler. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_16)(MailQuery, CancellationToken) | Mesajları listeler. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_14)(Pop3ListFields, CancellationToken) | Mesajları listeler. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_9)(IConnection, bool, CancellationToken) | Mesajları listeler. Arama mesajı için bir bilgi alır |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_7)(IConnection, MailQuery, CancellationToken) | Mesajları listeler. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_5)(IConnection, Pop3ListFields, CancellationToken) | Mesajları listeler. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_12)(Pop3ListFields, bool, MailQuery) | Mesajları listeler. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_3)(IConnection, Pop3ListFields, bool, MailQuery) | Mesajları listeler. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_13)(Pop3ListFields, bool, MailQuery, CancellationToken) | Mesajları listeler. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_4)(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) | Mesajları listeler. |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_3)(IEnumerable&lt;int&gt;) | Pop3MessageInfo listesini yükler |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_2)(IEnumerable&lt;Pop3MessageInfo&gt;) | Pop3MessageInfo listesini yükler |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_1)(IConnection, IEnumerable&lt;int&gt;) | Pop3MessageInfo listesini yükler |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Pop3MessageInfo listesini yükler |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_7)(IEnumerable&lt;int&gt;) | Pop3MessageInfo listesini yükler |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_5)(IEnumerable&lt;Pop3MessageInfo&gt;) | Pop3MessageInfo listesini yükler |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_4)(Pop3LoadMessageInfoList) | Pop3MessageInfo listesini yükler |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_2)(IConnection, IEnumerable&lt;int&gt;) | Pop3MessageInfo listesini yükler |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Pop3MessageInfo listesini yükler |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_8)(IEnumerable&lt;int&gt;, CancellationToken) | Pop3MessageInfo listesini yükler |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_6)(IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Pop3MessageInfo listesini yükler |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_3)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Pop3MessageInfo listesini yükler |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_1)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Pop3MessageInfo listesini yükler |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop)() | 'İşlem yok' komutu |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop_1)(IConnection) | 'İşlem yok' komutu |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync)() | 'İşlem yok' komutu |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_3)(CancellationToken) | 'İşlem yok' komutu |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_1)(IConnection) | 'İşlem yok' komutu |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_2)(IConnection, CancellationToken) | 'İşlem yok' komutu |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Günlük ayarlarını varsayılana sıfırlar. |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_4)(int, Stream) | İletiyi bir akış olarak alır ve kaydeder |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_5)(int, string) | İletiyi alır ve bir dosyaya kaydeder |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_6)(string, Stream) | İletiyi bir akış olarak alır ve kaydeder |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_7)(string, string) | İletiyi alır ve bir dosyaya kaydeder |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage)(IConnection, int, Stream) | İletiyi bir akış olarak alır ve kaydeder |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_1)(IConnection, int, string) | İletiyi alır ve bir dosyaya kaydeder |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_2)(IConnection, string, Stream) | İletiyi bir akış olarak alır ve kaydeder |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_3)(IConnection, string, string) | İletiyi alır ve bir dosyaya kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_8)(int, Stream) | İletiyi bir akış olarak alır ve kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_10)(int, string) | İletiyi alır ve bir dosyaya kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_12)(string, Stream) | İletiyi bir akış olarak alır ve kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_14)(string, string) | İletiyi alır ve bir dosyaya kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync)(IConnection, int, Stream) | İletiyi bir akış olarak alır ve kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_2)(IConnection, int, string) | İletiyi alır ve bir dosyaya kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_4)(IConnection, string, Stream) | İletiyi bir akış olarak alır ve kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_6)(IConnection, string, string) | İletiyi alır ve bir dosyaya kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_9)(int, Stream, CancellationToken) | İletiyi bir akış olarak alır ve kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_11)(int, string, CancellationToken) | İletiyi alır ve bir dosyaya kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_13)(string, Stream, CancellationToken) | İletiyi bir akış olarak alır ve kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_15)(string, string, CancellationToken) | İletiyi alır ve bir dosyaya kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_1)(IConnection, int, Stream, CancellationToken) | İletiyi bir akış olarak alır ve kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_3)(IConnection, int, string, CancellationToken) | İletiyi alır ve bir dosyaya kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_5)(IConnection, string, Stream, CancellationToken) | İletiyi bir akış olarak alır ve kaydeder |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_7)(IConnection, string, string, CancellationToken) | İletiyi alır ve bir dosyaya kaydeder |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Kullanılacak SSL/TLS şifreleme protokollerinin sürümlerini tanımlar. Bu yöntem güvenli değildir ve şifreleme protokollerini herhangi bir uyumluluk denetimi yapmadan ayarlar. Kullan[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) yalnızca .net çerçevesi tarafından kesinlikle desteklenen protokolleri güvenli bir şekilde ayarlama özelliği. Geçerli .net çerçeveniz bu güvenlik düzeyini desteklemiyorsa, sunucuyla bağlantı kurmaya çalışırken bir istisna atılacağını lütfen unutmayın. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages)() | İletilerin silinmesini geri alır. POP3 sunucusu tarafından silinmiş olarak işaretlenen iletiler varsa, bu iletiler kaldırılır. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages_1)(IConnection) | İletilerin silinmesini geri alır. POP3 sunucusu tarafından silinmiş olarak işaretlenen iletiler varsa, bu iletiler kaldırılır. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync)() | İletilerin silinmesini geri alır. POP3 sunucusu tarafından silinmiş olarak işaretlenen iletiler varsa, bu iletiler kaldırılır. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_3)(CancellationToken) | İletilerin silinmesini geri alır. POP3 sunucusu tarafından silinmiş olarak işaretlenen iletiler varsa, bu iletiler kaldırılır. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_1)(IConnection) | İletilerin silinmesini geri alır. POP3 sunucusu tarafından silinmiş olarak işaretlenen iletiler varsa, bu iletiler kaldırılır. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_2)(IConnection, CancellationToken) | İletilerin silinmesini geri alır. POP3 sunucusu tarafından silinmiş olarak işaretlenen iletiler varsa, bu iletiler kaldırılır. |
| override [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials)() | Kimlik doğrulamasını yürütür |
| [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials_1)(IConnection) | Kimlik doğrulamasını yürütür |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync)() | Kimlik doğrulamasını yürütür |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Kimlik doğrulamasını yürütür |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Kimlik doğrulamasını yürütür |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Kimlik doğrulamasını yürütür |
| static [CreateAsync](../../aspose.email.clients.pop3/pop3client/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Yeni bir örneğini oluşturur[`Pop3Client`](../pop3client) class |

### Ayrıca bakınız

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncPop3Client](../iasyncpop3client)
* ad alanı [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
