---
title: MapiNote
second_title: Aspose.Email for .NET API Referansı
description: Outlook Note nesnesini yapışkan not temsil eder
type: docs
weight: 18530
url: /tr/net/aspose.email.mapi/mapinote/
---
## MapiNote class

Outlook Note nesnesini ("yapışkan not") temsil eder

```csharp
public sealed class MapiNote : MapiMessageItemBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [MapiNote](mapinote#constructor)() | Yeni bir örneğini başlatır[`MapiNote`](../mapinote) sınıf. |
| [MapiNote](mapinote#constructor_1)(string, string) | Yeni bir örneğini başlatır[`MapiNote`](../mapinote) sınıf. |

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
| [Color](../../aspose.email.mapi/mapinote/color) { get; set; } | Not nesnesinin önerilen arka plan rengini alır veya ayarlar |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Bir öğeyle ilişkili şirketlerin adlarını içerir. |
| [CreationDate](../../aspose.email.mapi/mapinote/creationdate) { get; set; } | note oluşturma tarihini alır veya ayarlar |
| [Height](../../aspose.email.mapi/mapinote/height) { get; set; } | Görünür mesaj penceresinin yüksekliğini piksel cinsinden alır veya ayarlar |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Öğe kimliği, bir server ile birlikte kullanılır |
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
| [Width](../../aspose.email.mapi/mapinote/width) { get; set; } | Görünür mesaj penceresinin genişliğini piksel cinsinden alır veya ayarlar |
| [XPosition](../../aspose.email.mapi/mapinote/xposition) { get; set; } | Bir kullanıcı arabiriminin bir Not nesnesi görüntülemesi için ekranın sol kenarından piksel cinsinden uzaklığı alır veya ayarlar |
| [YPosition](../../aspose.email.mapi/mapinote/yposition) { get; set; } | Bir kullanıcı arabiriminin bir Not nesnesi görüntülemesi için ekranın üst kenarından piksel cinsinden uzaklığı alır veya ayarlar |

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
| [Save](../../aspose.email.mapi/mapinote/save#save)(Stream, NoteSaveFormat) | Bunu kaydeder[`MapiNote`](../mapinote) belirtilen formatı kullanarak verilen akışa. |
| [Save](../../aspose.email.mapi/mapinote/save#save_1)(string, NoteSaveFormat) | Bunu kaydeder[`MapiNote`](../mapinote) belirtilen formatı kullanarak dosyaya. |
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
