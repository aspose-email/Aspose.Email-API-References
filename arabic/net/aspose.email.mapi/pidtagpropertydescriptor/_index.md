---
title: PidTagPropertyDescriptor
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: تحتوي الفئة على معلومات وصف الخاصية.
type: docs
weight: 18990
url: /ar/net/aspose.email.mapi/pidtagpropertydescriptor/
---
## PidTagPropertyDescriptor class

تحتوي الفئة على معلومات وصف الخاصية.

```csharp
public class PidTagPropertyDescriptor : PropertyDescriptor
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_1)(long) | يقوم بتهيئة مثيل جديد لملف[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class خاصية تم تعريفها بواسطة معرف خاصية 16 بت ونوع خاصية 16 بت. يقع معرف الخاصية لخاصية مميزة في النطاق 0x001 × 0x7FFF. معرّفات الخاصية في النطاق 0x8000 × 0x8FFF محجوزة للتعيين إلى الخصائص المسماة |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor)(int, PropertyDataType) | يقوم بتهيئة مثيل جديد لملف[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class خاصية تم تعريفها بواسطة معرف خاصية 16 بت ونوع خاصية 16 بت. يقع معرف الخاصية لخاصية مميزة في النطاق 0x001 × 0x7FFF. معرّفات الخاصية في النطاق 0x8000 × 0x8FFF محجوزة للتعيين إلى الخصائص المسماة |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_2)(string, int, PropertyDataType) | يقوم بتهيئة مثيل جديد لملف[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class خاصية تم تعريفها بواسطة معرف خاصية 16 بت ونوع خاصية 16 بت. يقع معرف الخاصية لخاصية مميزة في النطاق 0x001 × 0x7FFF. معرّفات الخاصية في النطاق 0x8000 × 0x8FFF محجوزة للتعيين إلى الخصائص المسماة |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_4)(string, string, long) | يقوم بتهيئة مثيل جديد لملف[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class خاصية تم تعريفها بواسطة معرف خاصية 16 بت ونوع خاصية 16 بت. يقع معرف الخاصية لخاصية مميزة في النطاق 0x001 × 0x7FFF. معرّفات الخاصية في النطاق 0x8000 × 0x8FFF محجوزة للتعيين إلى الخصائص المسماة |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_3)(string, string, int, PropertyDataType) | يقوم بتهيئة مثيل جديد لملف[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class خاصية تم تعريفها بواسطة معرف خاصية 16 بت ونوع خاصية 16 بت. يقع معرف الخاصية لخاصية مميزة في النطاق 0x001 × 0x7FFF. معرّفات الخاصية في النطاق 0x8000 × 0x8FFF محجوزة للتعيين إلى الخصائص المسماة |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname) { get; } | الاسم المستخدم للإشارة إلى الخاصية في الوثائق. تحدد بادئة الاسم المتعارف عليه الخصائص الأساسية للخاصية للمنفذ. تستخدم بنية التسمية المتعارف عليها ثلاث فئات يتم الإشارة إليها بالبادئات التالية لاسم الخاصية المتعارف عليها: * بادئة PidLid: الخصائص المحددة بواسطة كمية 32 بت غير موقعة مع مجموعة خصائص. * بادئة PidName: الخصائص التي تم تحديدها بواسطة اسم سلسلة مع مجموعة خاصية . * بادئة PidTag: الخصائص المحددة بكمية 16 بت غير موقعة. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype) { get; } | نوع قيمة الخاصية ، كما هو موضح في [MS-OXCDATA] ، الذي يحدد نوع القيم المسموح بها للخاصية. |
| [Id](../../aspose.email.mapi/pidtagpropertydescriptor/id) { get; } | يحصل على كمية 16 بت غير موقعة تحدد خاصية مميزة. معرّفات المواقع ليست بالضرورة فريدة. باستثناء معرفات الخاصية في النطاق من 0x6800 إلى 0x7BFF ، فإن تركيبة معرف الخاصية ونوع البيانات فريدة من نوعها. يتم تعريف معرفات الخاصية في النطاق من 0x6800 إلى 0x7BFF بواسطة فئة الرسالة. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype) { get; } | يشير إلى ما إذا كان نوع البيانات يحتوي على قيم متعددة |
| [Name](../../aspose.email.mapi/propertydescriptor/name) { get; } | يحصل على سلسلة تحدد الخاصية. |
| [Tag](../../aspose.email.mapi/pidtagpropertydescriptor/tag) { get; } | علامة الخاصية هي رقم 32 بت يحتوي على معرف خاصية فريد في البتات 16 إلى 31 ونوع الخاصية في البتات من 0 إلى 15. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals_1)(object) | تحديد ما إذا كان System.Object المحدد يساوي كائن System.Object الحالي. |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals)(PropertyDescriptor) | يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع. |
| override [GetHashCode](../../aspose.email.mapi/pidtagpropertydescriptor/gethashcode)() | يعمل كدالة تجزئة لنوع . |
| override [ToString](../../aspose.email.mapi/pidtagpropertydescriptor/tostring)() | إرجاع سلسلة تمثل وصف الخاصية. |
| [operator ==](../../aspose.email.mapi/pidtagpropertydescriptor/op_equality) | لتحديد ما إذا كانت الكائنات المحددة متساوية مع بعضها البعض. |
| [explicit operator](../../aspose.email.mapi/pidtagpropertydescriptor/op_explicit) | تحويل قيمة العلامة إلى property المميزة بعلامات |
| [operator !=](../../aspose.email.mapi/pidtagpropertydescriptor/op_inequality) | لتحديد ما إذا كانت الكائنات المحددة لا تساوي بعضها البعض. |

### أنظر أيضا

* class [PropertyDescriptor](../propertydescriptor)
* مساحة الاسم [Aspose.Email.Mapi](../../aspose.email.mapi)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
