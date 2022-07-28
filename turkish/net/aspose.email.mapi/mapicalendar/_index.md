---
title: MapiCalendar
second_title: Aspose.Email for .NET API Referansı
description: mapi takvim nesnesini temsil eder
type: docs
weight: 17910
url: /tr/net/aspose.email.mapi/mapicalendar/
---
## MapiCalendar class

mapi takvim nesnesini temsil eder

```csharp
public sealed class MapiCalendar : MapiMessageItemBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [MapiCalendar](mapicalendar#constructor)() | Yeni bir örneğini başlatır[`MapiCalendar`](../mapicalendar) class |
| [MapiCalendar](mapicalendar#constructor_1)(string, string, string, DateTime, DateTime) | Yeni bir örneğini başlatır[`MapiCalendar`](../mapicalendar) sınıf. |
| [MapiCalendar](mapicalendar#constructor_2)(string, string, string, DateTime, DateTime, MapiElectronicAddress, MapiRecipientCollection) | Yeni bir örneğini başlatır[`MapiCalendar`](../mapicalendar) sınıf. |
| [MapiCalendar](mapicalendar#constructor_3)(string, string, string, DateTime, DateTime, string, MapiRecipientCollection) | Yeni bir örneğini başlatır[`MapiCalendar`](../mapicalendar) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AppointmentCounterProposal](../../aspose.email.mapi/mapicalendar/appointmentcounterproposal) { get; set; } | Bir Toplantı Yanıtı nesnesinin bir karşı teklif olup olmadığını belirten bir değer alır veya ayarlar. |
| [Attachments](../../aspose.email.mapi/mapicalendar/attachments) { get; } | Ek koleksiyonunu alır. |
| [Attendees](../../aspose.email.mapi/mapicalendar/attendees) { get; set; } | Katılımcıları alır veya ayarlar |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Bir öğeyle ilişkili fatura bilgilerini içerir. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Mesaj metnini alır. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | [`BodyRtf`](../mapimessageitembase/bodyrtf) varsa, HTML'ye dönüştürülen iletinin, aksi takdirde boş bir dize. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | RTF biçimli mesaj metnini alır veya ayarlar. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Gövdenin türünü alır. |
| [BusyStatus](../../aspose.email.mapi/mapicalendar/busystatus) { get; set; } | Meşgul durumunu alır veya ayarlar |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | İleti nesnesi için anahtar sözcükleri veya kategorileri içerir. |
| [ClientIntent](../../aspose.email.mapi/mapicalendar/clientintent) { get; set; } | Kullanıcının bu Toplantı nesnesi üzerinde gerçekleştirdiği eylemleri alır veya ayarlar. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Kod sayfasını alır. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Bir öğeyle ilişkili şirketlerin adlarını içerir. |
| [EndDate](../../aspose.email.mapi/mapicalendar/enddate) { get; set; } | Olayın bitiş tarihini ve saatini alır veya ayarlar. Tarih ayarlanmamışsa için varsayılan değerDateTime döndürülür. |
| [EndDateTimeZone](../../aspose.email.mapi/mapicalendar/enddatetimezone) { get; set; } | EndDate özelliğinin saat dilimini gösteren saat dilimi bilgilerini alır veya ayarlar |
| [IsAllDay](../../aspose.email.mapi/mapicalendar/isallday) { get; set; } | Etkinliğin tüm gün süren bir etkinlik olup olmadığını belirten bir değer alır veya ayarlar |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Öğe kimliği, bir server ile birlikte kullanılır |
| [KeyWords](../../aspose.email.mapi/mapicalendar/keywords) { get; set; } | Takvim nesnesinin kategorilerini alır veya ayarlar |
| [Location](../../aspose.email.mapi/mapicalendar/location) { get; set; } | event konumunu alır veya ayarlar |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | IPM gibi gönderen tarafından tanımlanan mesaj sınıfını tanımlayan büyük/küçük harfe duyarlı bir dize alır. İleti sınıfı iletinin türünü, amacını veya içeriğini belirtir. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Bir öğeyle ilişkili kilometre bilgilerini içerir. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | İletinin adlandırılmış özelliklerini alır. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Adlandırılmış özellik eşlemesini alır. |
| [Organizer](../../aspose.email.mapi/mapicalendar/organizer) { get; set; } | Düzenleyiciyi alır veya ayarlar. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Özellikler koleksiyonunu alır. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Özellik akışını alır. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | İletinin alıcılarını alır. |
| [Recurrence](../../aspose.email.mapi/mapicalendar/recurrence) { get; set; } | Yineleme özelliklerini alır veya ayarlar |
| [ReminderDelta](../../aspose.email.mapi/mapicalendar/reminderdelta) { get; set; } | Hatırlatıcının ilk zaman aşımına uğradığı saat ile Takvim nesnesinin başlangıç zamanı arasındaki dakika cinsinden aralığı alır veya ayarlar |
| [ReminderFileParameter](../../aspose.email.mapi/mapicalendar/reminderfileparameter) { get; set; } | Hatırlatıcının süresi geçtiğinde istemcinin çalması GEREKEN sesin tam yolunu belirtir. |
| [ReminderSet](../../aspose.email.mapi/mapicalendar/reminderset) { get; set; } | object üzerinde bir hatırlatıcı ayarlanıp ayarlanmadığını gösteren bir değer alır veya ayarlar |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Hassasiyeti Alır. |
| [Sequence](../../aspose.email.mapi/mapicalendar/sequence) { get; set; } | Sıra numarasını alır veya ayarlar |
| [StartDate](../../aspose.email.mapi/mapicalendar/startdate) { get; set; } | Olayın başlangıç tarihini ve saatini alır veya ayarlar. Tarih ayarlanmadıysa, için varsayılan değerDateTime döndürülür. |
| [StartDateTimeZone](../../aspose.email.mapi/mapicalendar/startdatetimezone) { get; set; } | StartDate özelliğinin saat dilimini gösteren saat dilimi bilgilerini alır veya ayarlar |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | İletinin konusunu alır veya ayarlar. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | İleti üzerinde genellikle iletme için "FW: " gibi bazı eylemleri belirten bir konu öneki alır. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Alt depoları alır. |
| [Uid](../../aspose.email.mapi/mapicalendar/uid) { get; set; } | Benzersiz tanımlayıcıyı alır |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Dispose](../../aspose.email.mapi/mapicalendar/dispose)() | Tüm kaynakları serbest bırakır. |
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
| [Save](../../aspose.email.mapi/mapicalendar/save#save)(Stream) | Varsayılan kaydetme seçeneklerini kullanarak takvim nesnesini iCalendar biçiminde dosyaya kaydeder |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_3)(string) | Varsayılan kaydetme seçeneklerini kullanarak takvim nesnesini iCalendar biçiminde dosyaya kaydeder |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_1)(Stream, AppointmentSaveFormat) | Varsayılan kaydetme seçeneklerini kullanarak takvim nesnesini belirtilen biçimde akışa kaydeder |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_2)(Stream, MapiCalendarSaveOptions) | Takvimi belirtilen kaydetme seçenekleriyle akışa kaydeder |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_4)(string, AppointmentSaveFormat) | Varsayılan kaydetme seçeneklerini kullanarak takvim nesnesini belirtilen biçimde dosyaya kaydeder |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_5)(string, MapiCalendarSaveOptions) | Varsayılan kaydetme seçeneklerini kullanarak takvim nesnesini belirtilen biçimde dosyaya kaydeder |
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
