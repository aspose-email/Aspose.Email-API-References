---
title: MapiProperty
second_title: Aspose.Email for .NET API Referansı
description: mapi özelliğini temsil eder.
type: docs
weight: 18560
url: /tr/net/aspose.email.mapi/mapiproperty/
---
## MapiProperty class

mapi özelliğini temsil eder.

```csharp
public class MapiProperty
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [MapiProperty](mapiproperty#constructor_2)(long) | MapiProperty sınıfının yeni bir örneğini başlatır. |
| [MapiProperty](mapiproperty#constructor_3)(long, byte[]) | MapiProperty sınıfının yeni bir örneğini başlatır. |
| [MapiProperty](mapiproperty#constructor_5)(long, IList&lt;object&gt;) | Yeni bir örneğini başlatır[`MapiProperty`](../mapiproperty) class. Bu aşırı yükleme, birden çok değerli özellik oluşturmak için kullanılır, PT_MV_*. |
| [MapiProperty](mapiproperty#constructor)(PidLidPropertyDescriptor, object) | MapiProperty sınıfının yeni bir örneğini başlatır. |
| [MapiProperty](mapiproperty#constructor_1)(PidTagPropertyDescriptor, object) | MapiProperty sınıfının yeni bir örneğini başlatır. |
| [MapiProperty](mapiproperty#constructor_4)(long, long, byte[]) | Yeni bir örneğini başlatır[`MapiProperty`](../mapiproperty) sınıf. |
| [MapiProperty](mapiproperty#constructor_6)(string, long, long, byte[]) | MapiProperty sınıfının yeni bir örneğini başlatır. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data) { get; } | İkili verileri alır. |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype) { get; } | Veri türünü alır. |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor) { get; } | MAPI özelliğinin tanımlayıcısını alır |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier) { get; } | Göstergeyi alır. |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed) { get; } | Özelliğin adlandırılmış bir özellik olup olmadığını gösterir. |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned) { get; set; } | İkili verilerin imzalanıp imzalanmadığını gösterir. |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries) { get; } | MV girişleri listesini alır. |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name) { get; } | Adı alır. |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname) { get; } | PropertyName'i alır. |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag) { get; } | etiketini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [CreateMapiPropertyFromBytes](../../aspose.email.mapi/mapiproperty/createmapipropertyfrombytes)(long, byte[]) | bytes. öğesinden mapi özelliğini oluşturur |
| static [CreateMapiPropertyFromDateTime](../../aspose.email.mapi/mapiproperty/createmapipropertyfromdatetime)(long, DateTime) | Tarih saatinden itibaren mapi özelliğini oluşturur. |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong)(long, long) | long. öğesinden mapi özelliğini oluşturur |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong_1)(long, long, long) | long. öğesinden mapi özelliğini oluşturur |
| virtual [GetBoolean](../../aspose.email.mapi/mapiproperty/getboolean)() | İkili verilerin ilk baytlarını boolean olarak alır. |
| virtual [GetCurrency](../../aspose.email.mapi/mapiproperty/getcurrency)() | Belirtilen kod sayfasını kullanarak Para Birimi'ni dize olarak alır. |
| virtual [GetDateTime](../../aspose.email.mapi/mapiproperty/getdatetime)() | İkili verilerin ilk baytlarını datetime olarak alır. |
| virtual [GetDouble](../../aspose.email.mapi/mapiproperty/getdouble)() | İkili verilerin baytlarını double olarak alır. |
| virtual [GetFloat](../../aspose.email.mapi/mapiproperty/getfloat)() | İkili verilerin baytlarını kayan nokta olarak alır. |
| virtual [GetFloatingDate](../../aspose.email.mapi/mapiproperty/getfloatingdate)() | İkili verilerin baytlarını DateTime. olarak alır |
| virtual [GetGuid](../../aspose.email.mapi/mapiproperty/getguid)() | İkili verilerin baytlarını Guid. olarak alır |
| virtual [GetInt32](../../aspose.email.mapi/mapiproperty/getint32)() | İkili verilerin ilk 4 baytını int32. olarak alır |
| virtual [GetLong](../../aspose.email.mapi/mapiproperty/getlong)() | İkili verilerin ilk 8 baytını şu uzunlukta alır. |
| virtual [GetShort](../../aspose.email.mapi/mapiproperty/getshort)() | İkili verilerin ilk 2 baytını kısa olarak alır. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring)() | İkili verileri string olarak alır. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring_1)(int) | Belirtilen kod sayfasını kullanarak ikili verileri dize olarak alır. |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue)() | object olarak değer alır |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring)() | Bir döndürürString akımı temsil edenObject . |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Mapi](../../aspose.email.mapi)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
