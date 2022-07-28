---
title: ActiveSyncTLClient
second_title: Aspose.Email for .NET API Referansı
description: ActiveSync istemci uygulamaları için temel sınıf
type: docs
weight: 950
url: /tr/net/aspose.email.clients.activesync.transportlayer/activesynctlclient/
---
## ActiveSyncTLClient class

ActiveSync istemci uygulamaları için temel sınıf

```csharp
public class ActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [AuthenticationType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/authenticationtype) { get; set; } | ActiveSync istemcisi tarafından kullanılan kimlik doğrulama türünü alır veya ayarlar. |
| virtual [AutodiscoverUri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscoveruri) { get; set; } | Otomatik bulma hizmetini alır veya ayarlar uri |
| virtual [Credentials](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/credentials) { get; } | Exchange server için kullanıcının kimlik bilgileri |
| virtual [DeviceID](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/deviceid) { get; set; } | Aygıtı tanımlayan bir GUID. Aygıt kimliği, düz metin sorgu değerinin aygıt kimliğine özgü ABNF kuralı bölümü tarafından belirlenir. Aygıt kimliği ABNF kuralı tarafından temsil edilen değer, aygıtı belirten bir dizedir. Her aygıtın benzersiz bir aygıt kimliği dizesi OLMALIDIR. Aygıttan gelen her istek aynı aygıt kimliği dizesini İÇERMEK ZORUNDADIR. |
| virtual [DeviceType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/devicetype) { get; set; } | Cihaz tipi, düz metin sorgu değerinin cihaz tipi spesifik ABNF kuralı kısmı tarafından belirlenir. Aygıt türü ABNF kuralıyla temsil edilen değer, aygıt türünü belirten herhangi bir dizedir. "SP" bir Akıllı Telefonu belirtir ve "PPC" bir PocketPC'yi belirtir. Diğer istemci cihazlar, kendi özel cihaz türleri için benzersiz dizeler gönderir. Bir istemci cihazdan gelen her istek aynı cihaz tipi dizesini içermelidir ZORUNLU. |
| virtual [PolicyState](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/policystate) { get; set; } | İstemci cihazdaki ilke ayarlarının durumunu gösteren işaretsiz bir tam sayı, [MS-ASPROV] bölüm 2.2.2.41. 'de belirtildiği gibi |
| virtual [Proxy](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/proxy) { get; set; } | Proxy'yi alır veya ayarlar. |
| virtual [SupportedServerCommands](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedservercommands) { get; } | ActiveSync komutlarının desteklenen sürümlerini alır |
| virtual [SupportedServerProtocols](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedserverprotocols) { get; } | Desteklenen ActiveSync protokollerinin sürümlerini alır |
| virtual [Timeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/timeout) { get; set; } | İşlem zaman aşımına uğramadan önce beklenecek milisaniye sayısını alır veya ayarlar. Varsayılan değer 100.000 milisaniyedir (100 saniye). |
| virtual [Uri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/uri) { get; } | ActiveSync hizmetinin URL'sini alır |
| virtual [UserAgent](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/useragent) { get; set; } | Kullanıcı Aracısı istek başlığı alanı, isteği oluşturan kullanıcı aracısı hakkında bilgi içerir. Bu, istatistiksel amaçlar, protokol ihlallerinin izlenmesi ve belirli kullanıcı aracısı sınırlamalarından kaçınmak için yanıtları uyarlama adına kullanıcı aracılarının otomatik olarak tanınması içindir. Kullanıcı aracıları bu alanı isteklere dahil etmelidir ÖNEMLİDİR. Alan, birden çok ürün belirteci (bölüm 3.8) ve aracıyı ve kullanıcı aracısının önemli bir bölümünü oluşturan alt ürünleri tanımlayan yorumları içerebilir. Geleneksel olarak, ürün belirteçleri, uygulamayı tanımlamak için önem sırasına göre listelenir. Örnek: Kullanıcı Aracısı: CERN-LineMode/2.15 libwww/2.17b3 |
| virtual [Version](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/version) { get; } | ActiveSync istemcisinde kullanılan protokolün sürümünü alır. |
| static [DefaultTimeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/defaulttimeout) { get; set; } | ActiveSync istemci örnekleri için varsayılan zaman aşımı değerini alır veya ayarlar Varsayılan değer 100.000 milisaniyedir (100 saniye). |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string) | Otomatik Bulma komutu, birincil giriş olarak kullanıcının Basit Posta Aktarım Protokolü (SMTP) adresini kullanarak temel hesap yapılandırma bilgilerinin keşfedilmesini kolaylaştırır. |
| [Dispose](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/dispose)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilgili görevleri gerçekleştirir. |
| static [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string, NetworkCredential, string) | Otomatik Bulma komutu, birincil giriş olarak kullanıcının Basit Posta Aktarım Protokolü (SMTP) adresini kullanarak temel hesap yapılandırma bilgilerinin keşfedilmesini kolaylaştırır. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance)(string, NetworkCredential) | ActiveSync istemcisinin bir örneğini alır ActiveSync protokolünün sürümü, sunucu yanıtına göre otomatik olarak seçilir. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance_1)(string, NetworkCredential, ASProtocolVersions) | ActiveSync client örneğini alır |
| static [GetOptions](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getoptions)(string, NetworkCredential, out string[], out string[]) | GetOptions statik yöntemi, hangi protokol sürümlerinin desteklendiğini ve sunucuda hangi protokol komutlarının desteklendiğini keşfetmek için kullanılır. İstemci, sunucunun, istemcinin desteklediği protokolün aynı sürümlerini destekleyip desteklemediğini belirlemek için GetOptions statik yöntemini kullanır. |

### Ayrıca bakınız

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
