---
title: O365URLTimeOfClickActivity
second_title: Aspose.Email for .NET API Referansı
description: Office 365 Gelişmiş Tehdit Koruması ve Tehdit İstihbaratı verilerine özgü özelliklerle Ortak şemayı genişletir. Office 365 Gelişmiş Tehdit Koruması ATP ve Tehdit İstihbaratı olayları ATP Tehdit İstihbaratı veya E5 aboneliğine sahip Office 365 müşterileri için kullanılabilir . ATP ve Tehdit İstihbaratı özet akışındaki her olay kuruluştaki bir kullanıcı tarafından tıklanan ve Office 365 ATP Güvenli Bağlantılar korumasına dayalı olarak tıklama anında kötü amaçlı olarak algılanan URLlere karşılık gelir.
type: docs
weight: 2670
url: /tr/net/aspose.email.clients.activity/o365urltimeofclickactivity/
---
## O365URLTimeOfClickActivity class

Office 365 Gelişmiş Tehdit Koruması ve Tehdit İstihbaratı verilerine özgü özelliklerle Ortak şemayı genişletir. Office 365 Gelişmiş Tehdit Koruması (ATP) ve Tehdit İstihbaratı olayları, ATP, Tehdit İstihbaratı veya E5 aboneliğine sahip Office 365 müşterileri için kullanılabilir . ATP ve Tehdit İstihbaratı özet akışındaki her olay, kuruluştaki bir kullanıcı tarafından tıklanan ve Office 365 ATP Güvenli Bağlantılar korumasına dayalı olarak tıklama anında kötü amaçlı olarak algılanan URL'lere karşılık gelir.

```csharp
public class O365URLTimeOfClickActivity : Content
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [O365URLTimeOfClickActivity](o365urltimeofclickactivity)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AppName](../../aspose.email.clients.activity/o365urltimeofclickactivity/appname) { get; set; } | URL'nin tıklandığı Office 365 hizmeti (örn. Posta). Zorunlu: Evet |
| [Blocked](../../aspose.email.clients.activity/o365urltimeofclickactivity/blocked) { get; set; } | URL tıklaması Office 365 ATP Güvenli Bağlantılar koruması tarafından engelleniyorsa bu doğrudur. Zorunlu: Evet |
| [ClickedThrough](../../aspose.email.clients.activity/o365urltimeofclickactivity/clickedthrough) { get; set; } | Bu, kuruluşun Office 365 ATP Güvenli Bağlantılar koruması için ilkelerine göre kullanıcı tarafından URL bloğu tıklandığında (geçersiz kılındığında) doğrudur. Zorunlu: Evet |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | Etkinlik günlüğe kaydedilirken kullanılan aygıtın IP adresi. IP adresi, IPv4 veya IPv6 adres biçiminde görüntülenir. Zorunlu: Yes |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | Kullanıcının etkinliği gerçekleştirdiği Eşgüdümlü Evrensel Saat (UTC) cinsinden tarih ve saat. Zorunlu: Yes |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Bir denetim kaydının benzersiz tanımlayıcısı. Zorunlu: Yes |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | SharePoint ve OneDrive İş etkinliği için, kullanıcı tarafından erişilen dosya veya klasörün tam yol adı. Exchange yönetici denetim günlüğü için, cmdlet tarafından değiştirilen nesnenin adı. Zorunlu: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Kullanıcının veya yönetici etkinliğinin adı. En yaygın işlemlerin/etkinliklerin açıklaması için Office 365 Koruma Merkezi'nde denetim günlüğünü arama bölümüne bakın. Exchange yönetici etkinliği için bu özellik, çalıştırılan cmdlet'in adını tanımlar. Dlp olayları için bu, aşağıda "DLP şeması" altında açıklanan "DlpRuleMatch", "DlpRuleUndo" veya "DlpInfo" olabilir. Zorunlu: Yes |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | Kuruluşunuzun Office 365 kiracısı için GUID. Bu değer, oluştuğu Office 365 hizmetinden bağımsız olarak kuruluşunuz için her zaman aynı olacaktır. Zorunlu: Evet |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Kayıt tarafından belirtilen işlem türü. Zorunlu: Evet |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Eylemin (Operation özelliğinde belirtilen) başarılı olup olmadığını gösterir. Olası değerler Başarılı, Kısmen Başarılı veya Başarısız'dır. Exchange yönetici etkinliği için değer, Doğru veya Yanlış'tır. Zorunlu: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Bu olay barındırılan bir O365 hizmeti veya şirket içi bir sunucu tarafından mı oluşturuldu? Olası değerler çevrimiçi ve şirket içidir. SharePoint'in şu anda şirket içinden O365. 'ye olay gönderen tek iş yükü olduğunu unutmayın. Zorunlu: No |
| [SourceId](../../aspose.email.clients.activity/o365urltimeofclickactivity/sourceid) { get; set; } | URL'nin tıklandığı Office 365 hizmetinin tanımlayıcısı (örneğin Posta için bu, Exchange Çevrimiçi Ağ İleti Kimliğidir). Zorunlu: Yes |
| [TimeOfClick](../../aspose.email.clients.activity/o365urltimeofclickactivity/timeofclick) { get; set; } | Kullanıcı URL'yi tıkladığında Eşgüdümlü Evrensel Saat (UTC) cinsinden tarih ve saat. Zorunlu: Yes |
| [URL](../../aspose.email.clients.activity/o365urltimeofclickactivity/url) { get; set; } | Kullanıcı tarafından tıklanan URL. Zorunlu: Yes |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | Kaydın günlüğe kaydedilmesine neden olan eylemi (İşlem özelliğinde belirtilen) gerçekleştiren kullanıcının UPN'si (Kullanıcı Asıl Adı); örneğin, my_name@my_domain_name. Sistem hesapları (SHAREPOINT\system veya NT AUTHORITY\SYSTEM gibi) tarafından gerçekleştirilen etkinlik kayıtlarının da dahil edildiğini unutmayın. Zorunlu: Yes |
| [UserIp](../../aspose.email.clients.activity/o365urltimeofclickactivity/userip) { get; set; } | URL'yi tıklayan kullanıcının IP adresi. IP adresi, IPv4 veya IPv6 adres biçiminde görüntülenir. Zorunlu: Yes |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | UserId özelliğinde tanımlanan kullanıcı için alternatif bir kimlik. Örneğin, bu özellik, SharePoint, OneDrive İş ve Exchange'de kullanıcılar tarafından gerçekleştirilen olaylar için pasaport benzersiz kimliği (PUID) ile doldurulur. Bu özellik, diğer hizmetlerde meydana gelen olaylar ve sistem hesapları tarafından gerçekleştirilen olaylar için UserID özelliğiyle aynı değeri belirtebilir. Zorunlu: Yes |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | İşlemi gerçekleştiren kullanıcı türü. Zorunlu: Evet |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Etkinliğin İş Yükü dizesinde gerçekleştiği Office 365 hizmeti. Bu özellik için olası değerler şunlardır: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Zorunlu: No |

### Ayrıca bakınız

* class [Content](../content)
* ad alanı [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
