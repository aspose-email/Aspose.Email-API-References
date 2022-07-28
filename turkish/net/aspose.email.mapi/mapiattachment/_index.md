---
title: MapiAttachment
second_title: Aspose.Email for .NET API Referansı
description: E-posta iletisindeki eki temsil eder.
type: docs
weight: 17880
url: /tr/net/aspose.email.mapi/mapiattachment/
---
## MapiAttachment class

E-posta iletisindeki eki temsil eder.

```csharp
public class MapiAttachment : MapiPropertyContainer
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BinaryData](../../aspose.email.mapi/mapiattachment/binarydata) { get; set; } | İkili ek verilerini alır veya ayarlar. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Kod sayfasını alır. |
| [Content](../../aspose.email.mapi/mapiattachment/content) { get; } | İçeriği alır. |
| [DisplayName](../../aspose.email.mapi/mapiattachment/displayname) { get; } | Bir ekteki ole nesnesinin görünen adını alır. |
| [Extension](../../aspose.email.mapi/mapiattachment/extension) { get; } | Bir ekin belge türünü belirten bir dosya adı uzantısı alır. |
| [FileName](../../aspose.email.mapi/mapiattachment/filename) { get; } | Yol hariç, bir ekin temel dosya adını ve uzantısını alır. |
| virtual [ItemId](../../aspose.email.mapi/mapiattachment/itemid) { get; } | Öğe kimliği, bir server ile birlikte kullanılır |
| [LongFileName](../../aspose.email.mapi/mapiattachment/longfilename) { get; } | Yol dışında bir ekin uzun dosya adını ve uzantısını alır. |
| [MimeTag](../../aspose.email.mapi/mapiattachment/mimetag) { get; } | Bir Çok Amaçlı İnternet Posta Uzantıları (MIME) eki hakkında biçimlendirme bilgilerini alır. |
| [NamedProperties](../../aspose.email.mapi/mapiattachment/namedproperties) { get; } | İletinin adlandırılmış özelliklerini alır. |
| [ObjectData](../../aspose.email.mapi/mapiattachment/objectdata) { get; } | OLE IStorage arabirimi aracılığıyla genellikle erişilen bir ek nesnesini alır. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Özellikler koleksiyonunu alır. |
| [PropertyStream](../../aspose.email.mapi/mapiattachment/propertystream) { get; } | Özellik akışını alır. |
| [SubStorages](../../aspose.email.mapi/mapiattachment/substorages) { get; } | Alt depoları alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [GetProperty](../../aspose.email.mapi/mapiattachment/getproperty)(PropertyDescriptor) | Özellik tanımlayıcısına göre MAPI özelliğini alır. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Boole türü olarak etiket tarafından belirtilen özelliğin değerini alır. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | etiketi tarafından belirtilen özelliğin dize değerini alır. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | DateTime türü olarak etiket tarafından belirtilen özelliğin değerini alır. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | etiketi tarafından belirtilen özelliğin int32 değerini alır. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Uzun (int64) türü olarak etiket tarafından belirtilen özelliğin değerini alır. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Etiket tarafından Kısa tür olarak belirtilen özelliğin değerini alır. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | etiketi tarafından belirtilen özelliğin dize değerini alır. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | etiketi tarafından belirtilen özelliğin dize değerini alır. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Dize özelliklerinin Unicode kodlu olup olmadığını belirler. |
| [RemoveProperty](../../aspose.email.mapi/mapiattachment/removeproperty)(long) | Özelliğin tüm koleksiyonlardan doğru şekilde kaldırılmasını sağlar. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save)(Stream) | Ek içeriğini kaydedin. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save_1)(string) | Ek içeriğini kaydedin. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty)(MapiProperty) | Özelliği ayarlar. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty_1)(PropertyDescriptor, object) | MAPI özelliğini ayarlar. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Belirtilen etiket anahtarıyla özellik verilerini almaya çalışın. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Belirtilen özelliğin değerini DateTime türü olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Belirtilen özelliğin değerini Int32 türü olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Belirtilen özelliğin değerini Uzun tip olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Belirtilen etikete sahip dize olarak bir özellik verisi almayı deneyin. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Belirtilen etiket ve kod sayfasıyla bir özellik verisini dize olarak almaya çalışın. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Belirtilen özelliğin değerini Dize türü olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Belirtilen özelliğin değerini Dize türü olarak alır. Bir dönüş değeri, işlemin başarılı olup olmadığını gösterir. |

### Ayrıca bakınız

* class [MapiPropertyContainer](../mapipropertycontainer)
* ad alanı [Aspose.Email.Mapi](../../aspose.email.mapi)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
