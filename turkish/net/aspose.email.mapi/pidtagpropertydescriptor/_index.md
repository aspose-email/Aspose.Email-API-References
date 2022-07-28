---
title: PidTagPropertyDescriptor
second_title: Aspose.Email for .NET API Referansı
description: Sınıf özellik açıklama bilgilerini içerir.
type: docs
weight: 18990
url: /tr/net/aspose.email.mapi/pidtagpropertydescriptor/
---
## PidTagPropertyDescriptor class

Sınıf, özellik açıklama bilgilerini içerir.

```csharp
public class PidTagPropertyDescriptor : PropertyDescriptor
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_1)(long) | Yeni bir örneğini başlatır[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class 16 bitlik bir özellik kimliği ve 16 bitlik bir özellik türü tarafından tanımlanan bir özellik. Etiketli bir mülkün mülk kimliği 0x001 � 0x7FFF aralığındadır. 0x8000 � 0x8FFF aralığındaki Mülk Kimlikleri, adlandırılmış özelliklere atama için ayrılmıştır |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor)(int, PropertyDataType) | Yeni bir örneğini başlatır[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class 16 bitlik bir özellik kimliği ve 16 bitlik bir özellik türü tarafından tanımlanan bir özellik. Etiketli bir mülkün mülk kimliği 0x001 � 0x7FFF aralığındadır. 0x8000 � 0x8FFF aralığındaki Mülk Kimlikleri, adlandırılmış özelliklere atama için ayrılmıştır |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_2)(string, int, PropertyDataType) | Yeni bir örneğini başlatır[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class 16 bitlik bir özellik kimliği ve 16 bitlik bir özellik türü tarafından tanımlanan bir özellik. Etiketli bir mülkün mülk kimliği 0x001 � 0x7FFF aralığındadır. 0x8000 � 0x8FFF aralığındaki Mülk Kimlikleri, adlandırılmış özelliklere atama için ayrılmıştır |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_4)(string, string, long) | Yeni bir örneğini başlatır[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class 16 bitlik bir özellik kimliği ve 16 bitlik bir özellik türü tarafından tanımlanan bir özellik. Etiketli bir mülkün mülk kimliği 0x001 � 0x7FFF aralığındadır. 0x8000 � 0x8FFF aralığındaki Mülk Kimlikleri, adlandırılmış özelliklere atama için ayrılmıştır |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_3)(string, string, int, PropertyDataType) | Yeni bir örneğini başlatır[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class 16 bitlik bir özellik kimliği ve 16 bitlik bir özellik türü tarafından tanımlanan bir özellik. Etiketli bir mülkün mülk kimliği 0x001 � 0x7FFF aralığındadır. 0x8000 � 0x8FFF aralığındaki Mülk Kimlikleri, adlandırılmış özelliklere atama için ayrılmıştır |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname) { get; } | Belgelerdeki özelliğe atıfta bulunmak için kullanılan ad. Kurallı adın öneki, uygulayıcıya bir özelliğin temel özelliklerini tanımlar. Kurallı adlandırma yapısı, kurallı özellik adına aşağıdaki öneklerle gösterilen üç kategori kullanır: * PidLid öneki: Bir özellik kümesiyle birlikte imzasız 32 bitlik bir miktarla tanımlanan özellikler. * PidName öneki: Bir özellik seti ile birlikte bir dize adıyla tanımlanan özellikler. * PidTag öneki: İşaretsiz 16 bitlik bir miktarla tanımlanan özellikler. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype) { get; } | Özellik için izin verilen değerlerin türünü belirten [MS-OXCDATA]'da açıklandığı gibi özellik değeri türü. |
| [Id](../../aspose.email.mapi/pidtagpropertydescriptor/id) { get; } | Etiketli bir özelliği tanımlayan işaretsiz 16 bitlik bir miktar alır. Mülk Kimlikleri mutlaka benzersiz değildir. 0x6800 ile 0x7BFF aralığındaki özellik kimlikleri dışında, özellik kimliği ve veri türü kombinasyonu benzersizdir. 0x6800 ile 0x7BFF aralığındaki Özellik Kimlikleri, mesaj sınıfı tarafından tanımlanır. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype) { get; } | Veri türünün birden çok değer içerip içermediğini gösterir |
| [Name](../../aspose.email.mapi/propertydescriptor/name) { get; } | Bir özelliği tanımlayan dizeyi alır. |
| [Tag](../../aspose.email.mapi/pidtagpropertydescriptor/tag) { get; } | Özellik etiketi, 16 ile 31 arasındaki bitlerde benzersiz bir özellik tanımlayıcısı ve 0 ile 15 arasındaki bitlerde bir özellik türü içeren 32 bitlik bir sayıdır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals_1)(object) | Belirtilen System.Object öğesinin geçerli System.Object. ile eşit olup olmadığını belirler |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals)(PropertyDescriptor) | Geçerli nesnenin aynı türden başka bir nesneye eşit olup olmadığını gösterir. |
| override [GetHashCode](../../aspose.email.mapi/pidtagpropertydescriptor/gethashcode)() | Bir tür için karma işlevi olarak hizmet eder. |
| override [ToString](../../aspose.email.mapi/pidtagpropertydescriptor/tostring)() | Özellik açıklamasını temsil eden bir dize döndürür. |
| [operator ==](../../aspose.email.mapi/pidtagpropertydescriptor/op_equality) | Belirtilen nesnelerin birbirine eşit olup olmadığını belirler. |
| [explicit operator](../../aspose.email.mapi/pidtagpropertydescriptor/op_explicit) | Etiket değerini etiketli özelliğe dönüştürür |
| [operator !=](../../aspose.email.mapi/pidtagpropertydescriptor/op_inequality) | Belirtilen nesnelerin birbirine eşit olup olmadığını belirler. |

### Ayrıca bakınız

* class [PropertyDescriptor](../propertydescriptor)
* ad alanı [Aspose.Email.Mapi](../../aspose.email.mapi)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
