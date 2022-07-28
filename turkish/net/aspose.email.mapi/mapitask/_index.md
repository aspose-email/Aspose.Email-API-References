---
title: MapiTask
second_title: Aspose.Email for .NET API Referansı
description: Outlook Görev nesnesini temsil eder.
type: docs
weight: 18670
url: /tr/net/aspose.email.mapi/mapitask/
---
## MapiTask class

Outlook Görev nesnesini temsil eder.

```csharp
public class MapiTask : MapiMessageItemBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [MapiTask](mapitask#constructor)() | Yeni bir örneğini başlatır[`MapiTask`](../mapitask) sınıf. |
| [MapiTask](mapitask#constructor_1)(string, string, DateTime, DateTime) | Yeni bir örneğini başlatır[`MapiTask`](../mapitask) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AcceptanceState](../../aspose.email.mapi/mapitask/acceptancestate) { get; set; } | Görevin kabul durumunu alır veya ayarlar. |
| [ActualEffort](../../aspose.email.mapi/mapitask/actualeffort) { get; set; } | Kullanıcının bir görev üzerinde çalışırken gerçekten harcadığı dakika sayısını alır veya ayarlar. |
| [Attachments](../../aspose.email.mapi/mapitask/attachments) { get; } | Ekler koleksiyonunu alır. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Bir öğeyle ilişkili fatura bilgilerini içerir. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Mesaj metnini alır. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | [`BodyRtf`](../mapimessageitembase/bodyrtf) varsa, HTML'ye dönüştürülen iletinin, aksi takdirde boş bir dize. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | RTF biçimli mesaj metnini alır veya ayarlar. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Gövdenin türünü alır. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | İleti nesnesi için anahtar sözcükleri veya kategorileri içerir. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Kod sayfasını alır. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Bir öğeyle ilişkili şirketlerin adlarını içerir. |
| [DateCompleted](../../aspose.email.mapi/mapitask/datecompleted) { get; set; } | Kullanıcının görev üzerinde çalışmayı tamamladığı tarihi alır veya ayarlar. |
| [DueDate](../../aspose.email.mapi/mapitask/duedate) { get; set; } | Kullanıcının görevde çalışmasının tamamlanmasını beklediği tarihi alır veya ayarlar. |
| [EstimatedEffort](../../aspose.email.mapi/mapitask/estimatedeffort) { get; set; } | Kullanıcının bir görev üzerinde çalışmayı beklediği dakika sayısını alır veya ayarlar. |
| [Flags](../../aspose.email.mapi/mapitask/flags) { get; } | Task nesnesinin gösterge bayraklarını alır. |
| [History](../../aspose.email.mapi/mapitask/history) { get; set; } | Task nesnesinde en son yapılan değişikliğinin türünü alır veya ayarlar. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Öğe kimliği, bir server ile birlikte kullanılır |
| [LastUpdate](../../aspose.email.mapi/mapitask/lastupdate) { get; set; } | Task nesnesinde yapılan en son değişikliğin tarih ve saatini alır veya ayarlar. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | IPM gibi gönderen tarafından tanımlanan mesaj sınıfını tanımlayan büyük/küçük harfe duyarlı bir dize alır. İleti sınıfı iletinin türünü, amacını veya içeriğini belirtir. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Bir öğeyle ilişkili kilometre bilgilerini içerir. |
| [Mode](../../aspose.email.mapi/mapitask/mode) { get; set; } | Task nesnesinin atama durumunu alır veya ayarlar. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | İletinin adlandırılmış özelliklerini alır. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Adlandırılmış özellik eşlemesini alır. |
| [PercentComplete](../../aspose.email.mapi/mapitask/percentcomplete) { get; set; } | Kullanıcının bir görevde kaydettiği ilerlemeyi alır veya ayarlar. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Özellikler koleksiyonunu alır. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Özellik akışını alır. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | İletinin alıcılarını alır. |
| [Recurrence](../../aspose.email.mapi/mapitask/recurrence) { get; set; } | Yineleme özelliklerini alır veya ayarlar. |
| [ReminderFileParameter](../../aspose.email.mapi/mapitask/reminderfileparameter) { get; set; } | Hatırlatıcının süresi geçtiğinde istemcinin çalması GEREKEN sesin tam yolunu belirtir. |
| [ReminderSet](../../aspose.email.mapi/mapitask/reminderset) { get; set; } | object üzerinde bir hatırlatıcı ayarlanıp ayarlanmadığını gösteren bir değer alır veya ayarlar |
| [ReminderTime](../../aspose.email.mapi/mapitask/remindertime) { get; set; } | Bir hatırlatıcı için başlangıç sinyal süresini alır veya ayarlar |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Hassasiyeti Alır. |
| [StartDate](../../aspose.email.mapi/mapitask/startdate) { get; set; } | Kullanıcının görev üzerinde çalışmasının başlamasını beklediği tarihi alır veya ayarlar. |
| [State](../../aspose.email.mapi/mapitask/state) { get; set; } | Task nesnesinin geçerli atama durumunu alır veya ayarlar. |
| [Status](../../aspose.email.mapi/mapitask/status) { get; set; } | Kullanıcının görevdeki ilerleme durumunu alır veya ayarlar. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | İletinin konusunu alır veya ayarlar. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | İleti üzerinde genellikle iletme için "FW: " gibi bazı eylemleri belirten bir konu öneki alır. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Alt depoları alır. |
| [Users](../../aspose.email.mapi/mapitask/users) { get; set; } | Görev kullanıcıları hakkında bilgi alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo)(Stream) | Belirtilen akıştan bir MapiTask örneği oluşturur. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_2)(string) | Belirtilen .ics dosyasından bir MapiTask örneği oluşturur. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_1)(Stream, bool) | Belirtilen akıştan bir MapiTask örneği oluşturur. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_3)(string, bool) | Belirtilen .ics dosyasından bir MapiTask örneği oluşturur. |
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
| [Save](../../aspose.email.mapi/mapitask/save#save)(Stream, TaskSaveFormat) | Bunu kaydeder[`MapiTask`](../mapitask) belirtilen formatı kullanarak verilen akışa. |
| [Save](../../aspose.email.mapi/mapitask/save#save_1)(string, TaskSaveFormat) | Bunu kaydeder[`MapiTask`](../mapitask) belirtilen formatı kullanarak dosyaya. |
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
