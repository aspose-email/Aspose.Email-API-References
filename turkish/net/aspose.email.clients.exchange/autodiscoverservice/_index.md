---
title: AutodiscoverService
second_title: Aspose.Email for .NET API Referansı
description: Exchange Otomatik Bulma Hizmetine bir bağlamayı temsil eder.
type: docs
weight: 3090
url: /tr/net/aspose.email.clients.exchange/autodiscoverservice/
---
## AutodiscoverService class

Exchange Otomatik Bulma Hizmetine bir bağlamayı temsil eder.

```csharp
public sealed class AutodiscoverService : AutodiscoverServiceBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [AutodiscoverService](autodiscoverservice#constructor)() | Yeni bir örneğini başlatır[`AutodiscoverService`](../autodiscoverservice) sınıf. |
| [AutodiscoverService](autodiscoverservice#constructor_1)(ExchangeVersion) | Yeni bir örneğini başlatır[`AutodiscoverService`](../autodiscoverservice) sınıf. |
| [AutodiscoverService](autodiscoverservice#constructor_2)(string) | Yeni bir örneğini başlatır[`AutodiscoverService`](../autodiscoverservice) sınıf. |
| [AutodiscoverService](autodiscoverservice#constructor_4)(Uri) | Yeni bir örneğini başlatır[`AutodiscoverService`](../autodiscoverservice) sınıf. |
| [AutodiscoverService](autodiscoverservice#constructor_3)(string, ExchangeVersion) | Yeni bir örneğini başlatır[`AutodiscoverService`](../autodiscoverservice) sınıf. |
| [AutodiscoverService](autodiscoverservice#constructor_5)(Uri, ExchangeVersion) | Yeni bir örneğini başlatır[`AutodiscoverService`](../autodiscoverservice) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AcceptGzipEncoding](../../aspose.email.clients.exchange/autodiscoverservicebase/acceptgzipencoding) { get; set; } | GZip sıkıştırma kodlamasının kabul edilip edilmeyeceğini belirten bir değer alır veya ayarlar. |
| [ClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/clientrequestid) { get; set; } | İstek için istek kimliğini alır veya ayarlar. |
| [ConnectionGroupName](../../aspose.email.clients.exchange/autodiscoverservicebase/connectiongroupname) { get; set; } | İstek için bağlantı grubunun adını alır veya ayarlar. |
| [CookieContainer](../../aspose.email.clients.exchange/autodiscoverservicebase/cookiecontainer) { get; set; } | Çerez kapsayıcısını alır veya ayarlar. |
| [Credentials](../../aspose.email.clients.exchange/autodiscoverservicebase/credentials) { get; set; } | Exchange Web Hizmetleri ile kimlik doğrulaması yapmak için kullanılan kimlik bilgilerini alır veya ayarlar. Kimlik Bilgileri özelliği ayarlandığında UseDefaultCredentials otomatik olarak false. değerine ayarlanır. |
| [Domain](../../aspose.email.clients.exchange/autodiscoverservice/domain) { get; set; } | Bu hizmetin bağlı olduğu etki alanını alır veya ayarlar. Bu özellik ayarlandığında, Otomatik Keşfet hizmeti URL'sini otomatik olarak belirlemek için domain adı kullanılır. |
| [EnableScpLookup](../../aspose.email.clients.exchange/autodiscoverservice/enablescplookup) { get; set; } | Otomatik Bulma hizmeti URL'sini belirlerken AutodiscoverService'in SCP (ServiceConnectionPoint) kayıt araması yapması gerekip gerekmediğini belirten bir değer alır veya ayarlar. |
| [HttpHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpheaders) { get; } | Her istekle birlikte EWS'ye gönderilecek bir HTTP üstbilgisi koleksiyonu alır. |
| [HttpResponseHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpresponseheaders) { get; } | Son yanıttan bir HTTP üstbilgileri koleksiyonu alır. |
| [IsExternal](../../aspose.email.clients.exchange/autodiscoverservice/isexternal) { get; } | URL'nin işaret ettiği Otomatik Bulma hizmetinin dahili (şirket ağının içinde) veya harici (şirket ağının dışında) olduğunu gösteren bir değer alır. |
| [KeepAlive](../../aspose.email.clients.exchange/autodiscoverservicebase/keepalive) { get; set; } | İnternet kaynağına yapılan isteğin Keep-alive değerine sahip bir Bağlantı HTTP başlığı içermesi gerekip gerekmediğini alır veya ayarlar |
| [LogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/logfilename) { get; set; } | Günlük dosyası adını alır veya ayarlar |
| [PreAuthenticate](../../aspose.email.clients.exchange/autodiscoverservicebase/preauthenticate) { get; set; } | HTTP ön kimlik doğrulamasının gerçekleştirilip gerçekleştirilmeyeceğini belirten bir değer alır veya ayarlar. |
| [RedirectionUrlValidationCallback](../../aspose.email.clients.exchange/autodiscoverservice/redirectionurlvalidationcallback) { get; set; } | Yeniden yönlendirme URL doğrulama geri aramasını alır veya ayarlar. |
| [RequestedServerVersion](../../aspose.email.clients.exchange/autodiscoverservicebase/requestedserverversion) { get; } | İstenen sunucu sürümünü alır. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/returnclientrequestid) { get; set; } | İstemcinin sunucu tarafının istek kimliğini döndürmesini gerektirip gerektirmediğini belirtmek için bir bayrak alır veya ayarlar. |
| [SendClientLatencies](../../aspose.email.clients.exchange/autodiscoverservicebase/sendclientlatencies) { get; set; } | İstemci gecikme bilgisinin sunucuya gönderilip gönderilmediğini gösteren bir değer alır veya ayarlar. |
| [ServerInfo](../../aspose.email.clients.exchange/autodiscoverservicebase/serverinfo) { get; } | Son isteği işleyen sunucuyla ilişkili bilgileri alır. Hiçbir istek işlenmediyse boş olur. |
| [Timeout](../../aspose.email.clients.exchange/autodiscoverservicebase/timeout) { get; set; } | HTTP istekleri gönderilirken ve HTTP yanıtları alınırken kullanılan zaman aşımını milisaniye cinsinden alır veya ayarlar. Varsayılan olarak 100000. |
| [Url](../../aspose.email.clients.exchange/autodiscoverservice/url) { get; set; } | Bu hizmetin bağlı olduğu URL'yi alır veya ayarlar. |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/usedateinlogfilename) { get; set; } | Günlük dosyası adında tarihin kullanılması gerekip gerekmediğini gösteren değeri alır veya ayarlar. |
| [UseDefaultCredentials](../../aspose.email.clients.exchange/autodiscoverservicebase/usedefaultcredentials) { get; set; } | Şu anda Windows'ta oturum açmış olan kullanıcının kimlik bilgilerinin Exchange Web Hizmetleri ile kimlik doğrulaması için kullanılması gerekip gerekmediğini belirten bir değer alır veya ayarlar. UseDefaultCredentials öğesinin true olarak ayarlanması, Credentials özelliğini otomatik olarak null. değerine ayarlar. |
| [UserAgent](../../aspose.email.clients.exchange/autodiscoverservicebase/useragent) { get; set; } | Kullanıcı aracısını alır veya ayarlar. |
| [WebProxy](../../aspose.email.clients.exchange/autodiscoverservicebase/webproxy) { get; set; } | EWS'ye istek gönderirken kullanılması gereken web proxy'sini alır veya ayarlar. Varsayılan web proxy'sini kullanmak için bu özelliği null olarak ayarlayın. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [GetUserSettings](../../aspose.email.clients.exchange/autodiscoverservice/getusersettings)(string, params UserSettingName[]) | Tek SMTP adresi için belirtilen ayarları alır. |
| [GetUsersSettings](../../aspose.email.clients.exchange/autodiscoverservice/getuserssettings)(IEnumerable&lt;string&gt;, params UserSettingName[]) | Bir dizi kullanıcı için belirtilen ayarları alır. |

### Ayrıca bakınız

* class [AutodiscoverServiceBase](../autodiscoverservicebase)
* ad alanı [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
