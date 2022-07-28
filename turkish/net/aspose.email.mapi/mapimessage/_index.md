---
title: MapiMessage
second_title: Aspose.Email for .NET API Referansı
description: Ayrıştırılabilen bir Outlook İletisi biçimindeki belgeyi temsil eder.
type: docs
weight: 18450
url: /tr/net/aspose.email.mapi/mapimessage/
---
## MapiMessage class

Ayrıştırılabilen bir Outlook İletisi biçimindeki belgeyi temsil eder.

```csharp
public sealed class MapiMessage : MapiMessageItemBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [MapiMessage](mapimessage#constructor)() | Yeni bir örneğini başlatır[`MapiMessage`](../mapimessage) sınıf. |
| [MapiMessage](mapimessage#constructor_1)(OutlookMessageFormat) | Yeni bir örneğini başlatır[`MapiMessage`](../mapimessage) sınıf. |
| [MapiMessage](mapimessage#constructor_2)(string, string, string, string) | Yeni bir örneğini başlatır[`MapiMessage`](../mapimessage) sınıf. |
| [MapiMessage](mapimessage#constructor_3)(string, string, string, string, OutlookMessageFormat) | Yeni bir örneğini başlatır[`MapiMessage`](../mapimessage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | İletideki ekleri alır. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Bir öğeyle ilişkili fatura bilgilerini içerir. |
| [Body](../../aspose.email.mapi/mapimessage/body) { get; set; } | Mesaj metnini alır. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | [`BodyRtf`](../mapimessageitembase/bodyrtf) varsa, HTML'ye dönüştürülen iletinin, aksi takdirde boş bir dize. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | RTF biçimli mesaj metnini alır veya ayarlar. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Gövdenin türünü alır. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | İleti nesnesi için anahtar sözcükleri veya kategorileri içerir. |
| [ClientSubmitTime](../../aspose.email.mapi/mapimessage/clientsubmittime) { get; set; } | İletiyi gönderenin bir ileti gönderdiği tarih ve saati alır veya ayarlar |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Kod sayfasını alır. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Bir öğeyle ilişkili şirketlerin adlarını içerir. |
| [ConversationTopic](../../aspose.email.mapi/mapimessage/conversationtopic) { get; } | Bir konuşma dizisindeki ilk mesajın konusunu alır. |
| [DeliveryTime](../../aspose.email.mapi/mapimessage/deliverytime) { get; set; } | Bir iletinin teslim edildiği tarih ve saati alır veya ayarlar. |
| [DisplayBcc](../../aspose.email.mapi/mapimessage/displaybcc) { get; } | Noktalı virgülle (;) ayrılmış, herhangi bir kör karbon kopya (BCC) mesajı alıcılarının görünen adlarının bir listesini alır. |
| [DisplayCc](../../aspose.email.mapi/mapimessage/displaycc) { get; } | Herhangi bir karbon kopyası (CC) mesajı alıcısının görünen adlarının noktalı virgülle (;) ayrılmış bir listesini alır. |
| [DisplayName](../../aspose.email.mapi/mapimessage/displayname) { get; } | İletinin görünen adını alır. |
| [DisplayNamePrefix](../../aspose.email.mapi/mapimessage/displaynameprefix) { get; } | Görünen adın ön ekini alır. |
| [DisplayTo](../../aspose.email.mapi/mapimessage/displayto) { get; } | Birincil (Kime) ileti alıcılarının görünen adlarının noktalı virgülle (;) ayrılmış bir listesini alır. |
| [Flags](../../aspose.email.mapi/mapimessage/flags) { get; } | İleti işaretlerini alır. |
| [Headers](../../aspose.email.mapi/mapimessage/headers) { get; set; } | Aktarım iletisi başlıklarını alır |
| [InternetMessageId](../../aspose.email.mapi/mapimessage/internetmessageid) { get; } | İletinin ileti kimliğini alır. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Öğe kimliği, bir server ile birlikte kullanılır |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | IPM gibi gönderen tarafından tanımlanan mesaj sınıfını tanımlayan büyük/küçük harfe duyarlı bir dize alır. İleti sınıfı iletinin türünü, amacını veya içeriğini belirtir. |
| [MessageFormat](../../aspose.email.mapi/mapimessage/messageformat) { get; } | Görünüm mesaj biçimini alır. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Bir öğeyle ilişkili kilometre bilgilerini içerir. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | İletinin adlandırılmış özelliklerini alır. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Adlandırılmış özellik eşlemesini alır. |
| [NormalizedSubject](../../aspose.email.mapi/mapimessage/normalizedsubject) { get; } | İletinin normalleştirilmiş konusunu alır. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Özellikler koleksiyonunu alır. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Özellik akışını alır. |
| [ReadReceiptRequested](../../aspose.email.mapi/mapimessage/readreceiptrequested) { get; set; } | Okundu bilgisinin istenip istenmediğini gösteren bir değer alır veya ayarlar. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | İletinin alıcılarını alır. |
| [ReplyTo](../../aspose.email.mapi/mapimessage/replyto) { get; set; } | Adlara verilen yanıtı alır veya ayarlar. |
| [SenderAddressType](../../aspose.email.mapi/mapimessage/senderaddresstype) { get; } | İletiyi gönderenin e-posta adresi türünü alır. |
| [SenderEmailAddress](../../aspose.email.mapi/mapimessage/senderemailaddress) { get; set; } | İletiyi gönderenin e-posta adresini alır veya ayarlar. |
| [SenderName](../../aspose.email.mapi/mapimessage/sendername) { get; set; } | İletiyi gönderenin görünen adını alır veya ayarlar. |
| [SenderSmtpAddress](../../aspose.email.mapi/mapimessage/sendersmtpaddress) { get; set; } | İletiyi gönderenin e-posta adresini alır veya ayarlar. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Hassasiyeti Alır. |
| [SentRepresentingAddressType](../../aspose.email.mapi/mapimessage/sentrepresentingaddresstype) { get; } | Gönderen tarafından temsil edilen mesajlaşma kullanıcısının adres türünü alır. |
| [SentRepresentingEmailAddress](../../aspose.email.mapi/mapimessage/sentrepresentingemailaddress) { get; set; } | Gönderen tarafından temsil edilen mesajlaşma kullanıcısı için e-posta adresini alır veya ayarlar. |
| [SentRepresentingName](../../aspose.email.mapi/mapimessage/sentrepresentingname) { get; set; } | Gönderen tarafından temsil edilen mesajlaşma kullanıcısının görünen adını alır veya ayarlar. |
| [SentRepresentingSmtpAddress](../../aspose.email.mapi/mapimessage/sentrepresentingsmtpaddress) { get; } | Gönderen tarafından temsil edilen mesajlaşma kullanıcısı için e-posta adresini alır veya ayarlar. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | İletinin konusunu alır veya ayarlar. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | İleti üzerinde genellikle iletme için "FW: " gibi bazı eylemleri belirten bir konu öneki alır. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Alt depoları alır. |
| [TransportMessageHeaders](../../aspose.email.mapi/mapimessage/transportmessageheaders) { get; } | Aktarmaya özel mesaj zarf bilgilerini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage)(MailMessage) | MailMessage'dan bir MapiMessage örneği oluşturur. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_2)(string) | MailMessage'dan bir MapiMessage örneği oluşturur. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_1)(MailMessage, MapiConversionOptions) | MailMessage'dan bir MapiMessage örneği oluşturur. |
| static [FromProperties](../../aspose.email.mapi/mapimessage/fromproperties)(MapiPropertyCollection) | Mapi özellikleri koleksiyonundan bir MapiMessage örneği oluşturur. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load)(Stream) | Akıştan mesaj yükler. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_2)(string) | Dosyadan mesaj yükler. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_1)(Stream, LoadOptions) | İletiyi akıştan ek seçeneklerle yükler. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_3)(string, LoadOptions) | Dosyadan ek seçeneklerle mesaj yükler. |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef)(Stream) | Transport Neutral Encapsulation Format (TNEF) veri yapısından mesaj yükler |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef_1)(string) | Transport Neutral Encapsulation Format (TNEF) veri yapısından mesaj yükler |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty)(MapiProperty, string) | Özel özelliği ekler. |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty_1)(MapiPropertyType, byte[], string) | Özel özelliği ekler. |
| [CheckBounced](../../aspose.email.mapi/mapimessage/checkbounced)() | Bu iletinin geri dönen ileti olarak değerlendirilip değerlendirilemeyeceğini kontrol eder. |
| [Clone](../../aspose.email.mapi/mapimessage/clone)() | Geçerli örneğin bir kopyası olan yeni bir nesne oluşturur. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilişkili uygulama tanımlı görevleri gerçekleştirir. |
| [GetCustomProperties](../../aspose.email.mapi/mapimessage/getcustomproperties)() | Özel MapiProperties koleksiyonunu alır. |
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
| [Save](../../aspose.email.mapi/mapimessage/save#save)(Stream) | Belirtilen akışa Msg. olarak kaydeder |
| [Save](../../aspose.email.mapi/mapimessage/save#save_2)(string) | Belirtilen dosyaya Msg. olarak kaydeder |
| [Save](../../aspose.email.mapi/mapimessage/save#save_1)(Stream, SaveOptions) | İletiyi ek seçeneklerle akış olarak kaydeder. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_3)(string, SaveOptions) | İletiyi ek seçeneklerle bir dosya olarak kaydeder. |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate)(Stream) | Belirtilen akışa Outlook Dosya Şablonu (OFT biçimi) olarak kaydeder. |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate_1)(string) | Belirtilen dosyaya Outlook Dosya Şablonu (OFT biçimi) olarak kaydeder. |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef)(Stream) | İletiyi TNEF biçiminde kaydedin. |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef_1)(string) | İletiyi TNEF biçiminde kaydedin. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Gövdenin içeriğini ayarlar. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Gövdenin içeriğini ayarlar. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | RTF biçimli mesaj metnini alır veya ayarlar. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | İleti bayraklarını ayarlar. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Özelliği ayarlar. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | MAPI özelliğini ayarlar. |
| [SetStringPropertyValue](../../aspose.email.mapi/mapimessage/setstringpropertyvalue)(long, string) | Dize özellik değerini ayarlar. |
| [ToMailMessage](../../aspose.email.mapi/mapimessage/tomailmessage)(MailConversionOptions) | Bu MapiMessage'dan bir MailMessage örneği oluşturur. |
| [ToMapiMessageItem](../../aspose.email.mapi/mapimessage/tomapimessageitem)() | MessageClass. 'ye bağlı olarak MapiMessage'ı IMapiMessageItem object 'ye dönüştürün |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Belirtilen etiket anahtarıyla özellik verilerini almaya çalışın. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Belirtilen özelliğin değerini DateTime türü olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Belirtilen özelliğin değerini Int32 türü olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Belirtilen özelliğin değerini Uzun tip olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Belirtilen etikete sahip dize olarak bir özellik verisi almayı deneyin. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Belirtilen etiket ve kod sayfasıyla bir özellik verisini dize olarak almaya çalışın. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Belirtilen özelliğin değerini Dize türü olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Belirtilen özelliğin değerini Dize türü olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |
| static [DestroyAttachments](../../aspose.email.mapi/mapimessage/destroyattachments)(string) | Belirtilen Outlook İleti dosyalarındaki ekleri yok eder. DestroyAttachments, ek ayrıştırmasını yok sayar. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat)(Stream) | Belirtilen akışın bir MSG biçimine sahip olup olmadığını belirler. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat_1)(string) | Belirtilen dosyanın MSG biçimine sahip olup olmadığını belirler. |
| static [RemoveAttachments](../../aspose.email.mapi/mapimessage/removeattachments)(string) | Belirtilen Outlook İleti dosyalarından tüm ekleri kaldırır. |

### Notlar

MapiMessage sınıfının örnekleri, MapiMessageReader sınıfı tarafından ayrıştırılan Microsoft Outlook Message belge dosyalarını temsil etmek için kullanılır. Bir e-posta iletisinin göndericisine, alıcısına ve içeriğine erişmek için MapiMessage sınıfının ilişkili özelliklerini kullanın.

### Örnekler

Aşağıdaki örnek, Outlook İleti dosyalarının nasıl okunacağını gösterir.

[C#]

[Visual Basic]

```csharp
//Outlook Mesaj dosyalarını aç
MapiMessage msg = MapiMessage.FromFile(@"c:\outlookmessage.msg");

/konuyu oku
onsole.WriteLine("Subject:" + msg.Subject);

/gönderenin adı
onsole.WriteLine("From:" + msg.SenderName);

/mesaj gövdesi
onsole.WriteLine("Body:" + msg.Body);

/Ekler
oreach(MapiAttachment att in msg.Attachments)

   Console.WriteLine("Attachment Name:"+att.FileName);
   att.Save(att.FileName);
    
```

```csharp
'Outlook İleti dosyalarını açın 
Dim msg As MapiMessage = MapiMessage.FromFile("c:\outlookmessage.msg") 

'konuyu oku 
Console.WriteLine("Subject:" + msg.Subject) 

'gönderenin adı 
Console.WriteLine("From:" + msg.SenderName) 

'mesaj gövdesi 
Console.WriteLine("Body:" + msg.Body) 

'ekler 
For Each att As MapiAttachment In msg.Attachments 
    Console.WriteLine("Attachment Name:" + att.FileName) 
    att.Save(att.FileName) 
Next
```

### Ayrıca bakınız

* class [MapiMessageItemBase](../mapimessageitembase)
* ad alanı [Aspose.Email.Mapi](../../aspose.email.mapi)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
