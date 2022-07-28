---
title: MapiRecipient
second_title: Aspose.Email for .NET API Referansı
description: Microsoft Outlook İletisindeki alıcı bilgilerini temsil eder.
type: docs
weight: 18620
url: /tr/net/aspose.email.mapi/mapirecipient/
---
## MapiRecipient class

Microsoft Outlook İletisindeki alıcı bilgilerini temsil eder.

```csharp
public class MapiRecipient : MapiPropertyContainer
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AddressType](../../aspose.email.mapi/mapirecipient/addresstype) { get; } | İleti alıcısının veya gönderenin adresinin türünü alır. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Kod sayfasını alır. |
| [Content](../../aspose.email.mapi/mapirecipient/content) { get; } | İçeriği alır. |
| [DisplayName](../../aspose.email.mapi/mapirecipient/displayname) { get; set; } | İleti alıcısının veya gönderenin görünen adını alır veya ayarlar. |
| [EmailAddress](../../aspose.email.mapi/mapirecipient/emailaddress) { get; set; } | mesaj alıcısının veya gönderenin e-posta adresini alır veya ayarlar. |
| [NamedProperties](../../aspose.email.mapi/mapirecipient/namedproperties) { get; } | İletinin adlandırılmış özelliklerini alır. |
| [OrganizationEmailAddress](../../aspose.email.mapi/mapirecipient/organizationemailaddress) { get; } | Kuruluşun e-posta adresini alır. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Özellikler koleksiyonunu alır. |
| [PropertyStream](../../aspose.email.mapi/mapirecipient/propertystream) { get; } | Özellik akışını alır. |
| [RecipientClass](../../aspose.email.mapi/mapirecipient/recipientclass) { get; } | tarif türünü alır. |
| [RecipientTrackStatus](../../aspose.email.mapi/mapirecipient/recipienttrackstatus) { get; set; } | Alıcının bir toplantı isteğine verdiği yanıtın durumu. |
| [RecipientType](../../aspose.email.mapi/mapirecipient/recipienttype) { get; } | Alıcının veya gönderenin türünü alır. |
| [SubStorages](../../aspose.email.mapi/mapirecipient/substorages) { get; } | Alt depoları alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [GetProperty](../../aspose.email.mapi/mapipropertycontainer/getproperty)(PropertyDescriptor) | Özellik tanımlayıcısına göre MAPI özelliğini alır. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Boole türü olarak etiket tarafından belirtilen özelliğin değerini alır. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | etiketi tarafından belirtilen özelliğin dize değerini alır. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | DateTime türü olarak etiket tarafından belirtilen özelliğin değerini alır. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | etiketi tarafından belirtilen özelliğin int32 değerini alır. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Uzun (int64) türü olarak etiket tarafından belirtilen özelliğin değerini alır. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Etiket tarafından Kısa tür olarak belirtilen özelliğin değerini alır. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | etiketi tarafından belirtilen özelliğin dize değerini alır. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | etiketi tarafından belirtilen özelliğin dize değerini alır. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Dize özelliklerinin Unicode kodlu olup olmadığını belirler. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Özelliği ayarlar. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(PropertyDescriptor, object) | MAPI özelliğini ayarlar. |
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
