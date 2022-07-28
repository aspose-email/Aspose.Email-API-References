---
title: MapiDistributionList
second_title: Aspose.Email for .NET API Referansı
description: Kişisel Dağıtım Listesi nesnesini temsil eder.
type: docs
weight: 18360
url: /tr/net/aspose.email.mapi/mapidistributionlist/
---
## MapiDistributionList class

Kişisel Dağıtım Listesi nesnesini temsil eder.

```csharp
public sealed class MapiDistributionList : MapiMessageItemBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [MapiDistributionList](mapidistributionlist#constructor)() | Yeni bir örneğini başlatır[`MapiDistributionList`](../mapidistributionlist) sınıf. |
| [MapiDistributionList](mapidistributionlist#constructor_1)(string, MapiDistributionListMemberCollection) | Yeni bir örneğini başlatır[`MapiDistributionList`](../mapidistributionlist) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | İletideki ekleri alır. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Bir öğeyle ilişkili fatura bilgilerini içerir. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Mesaj metnini alır. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | [`BodyRtf`](../mapimessageitembase/bodyrtf) varsa, HTML'ye dönüştürülen iletinin, aksi takdirde boş bir dize. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | RTF biçimli mesaj metnini alır veya ayarlar. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Gövdenin türünü alır. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | İleti nesnesi için anahtar sözcükleri veya kategorileri içerir. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Kod sayfasını alır. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Bir öğeyle ilişkili şirketlerin adlarını içerir. |
| [DisplayName](../../aspose.email.mapi/mapidistributionlist/displayname) { get; set; } | Kişisel dağıtım listesinin kullanıcı tarafından görülebilen adını alır veya ayarlar. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Öğe kimliği, bir server ile birlikte kullanılır |
| [Members](../../aspose.email.mapi/mapidistributionlist/members) { get; } | Kişisel dağıtım listesinin üyelerinin listesini alır. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | IPM gibi gönderen tarafından tanımlanan mesaj sınıfını tanımlayan büyük/küçük harfe duyarlı bir dize alır. İleti sınıfı iletinin türünü, amacını veya içeriğini belirtir. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Bir öğeyle ilişkili kilometre bilgilerini içerir. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | İletinin adlandırılmış özelliklerini alır. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Adlandırılmış özellik eşlemesini alır. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Özellikler koleksiyonunu alır. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Özellik akışını alır. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | İletinin alıcılarını alır. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Hassasiyeti Alır. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | İletinin konusunu alır veya ayarlar. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | İleti üzerinde genellikle iletme için "FW: " gibi bazı eylemleri belirten bir konu öneki alır. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Alt depoları alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilişkili uygulama tanımlı görevleri gerçekleştirir. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Özellik tanımlayıcısına göre MAPI özelliğini alır. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Boole türü olarak etiket tarafından belirtilen özelliğin değerini alır. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | etiketi tarafından belirtilen özelliğin dize değerini alır. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | DateTime türü olarak etiket tarafından belirtilen özelliğin değerini alır. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | etiketi tarafından belirtilen özelliğin int32 değerini alır. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Uzun (int64) türü olarak etiket tarafından belirtilen özelliğin değerini alır. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Etiket tarafından Kısa tür olarak belirtilen özelliğin değerini alır. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | etiketi tarafından belirtilen özelliğin dize değerini alır. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | etiketi tarafından belirtilen özelliğin dize değerini alır. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Dize özelliklerinin Unicode kodlu olup olmadığını belirler. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Özelliğin tüm koleksiyonlardan doğru şekilde kaldırılmasını sağlar. |
| [Save](../../aspose.email.mapi/mapidistributionlist/save#save)(Stream) | Belirtilen akışı kaydeder. |
| [Save](../../aspose.email.mapi/mapidistributionlist/save#save_1)(string) | Belirtilen dosya adını kaydeder. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Gövdenin içeriğini ayarlar. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Gövdenin içeriğini ayarlar. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | RTF biçimli mesaj metnini alır veya ayarlar. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | İleti bayraklarını ayarlar. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Özelliği ayarlar. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | MAPI özelliğini ayarlar. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Belirtilen etiket anahtarıyla özellik verilerini almaya çalışın. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Belirtilen özelliğin değerini DateTime türü olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Belirtilen özelliğin değerini Int32 türü olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Belirtilen özelliğin değerini Uzun tip olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Belirtilen etikete sahip dize olarak bir özellik verisi almayı deneyin. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Belirtilen etiket ve kod sayfasıyla bir özellik verisini dize olarak almaya çalışın. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Belirtilen özelliğin değerini Dize türü olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Belirtilen özelliğin değerini Dize türü olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |

### Ayrıca bakınız

* class [MapiMessageItemBase](../mapimessageitembase)
* ad alanı [Aspose.Email.Mapi](../../aspose.email.mapi)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
