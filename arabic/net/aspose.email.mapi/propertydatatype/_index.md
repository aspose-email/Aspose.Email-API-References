---
title: PropertyDataType
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: MS-OXCDATA هياكل البيانات
type: docs
weight: 19000
url: /ar/net/aspose.email.mapi/propertydatatype/
---
## PropertyDataType enumeration

[MS-OXCDATA]: هياكل البيانات

```csharp
public enum PropertyDataType
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| Unspecified | `0` | أي: قيمة نوع الخاصية هذه تطابق أي نوع ؛ يجب على الخادم إرجاع النوع الفعلي في استجابته. يجب ألا تقوم الخوادم بإرجاع هذا النوع استجابة لطلب عميل بخلاف NspiGetIDsFromNames أو طلب RopGetPropertyIdsFromNames ROP ([MS-OXCROPS] القسم 2.2.8.1) . اسم المواصفات: PtypUnspecified؛ الأسماء البديلة: PT_UNSPECIFIED ؛ |
| Null | `1` | بلا: هذه الخاصية هي عنصر نائب. اسم المواصفات: PtypNull ؛ الأسماء البديلة: PT_NULL؛ |
| Integer16 | `2` | 2 بايت ؛ عدد صحيح 16 بت اسم المواصفات: PtypInteger16 ؛ الأسماء البديلة: PT_SHORT ، PT_I2 ، i2 ، ui2 ؛ |
| Integer32 | `3` | 4 بايت ؛ عدد صحيح 32 بت اسم المواصفات: PtypInteger32 ؛ الأسماء البديلة: PT_LONG ، PT_I4 ، int ، ui4 ؛ |
| Floating32 | `4` | 4 بايت ؛ رقم الفاصلة العائمة 32 بت اسم المواصفة: PtypFloating32 ؛ الأسماء البديلة: PT_FLOAT، PT_R4، float، r4؛ |
| Floating64 | `5` | 8 بايت ؛ رقم فاصلة عائمة 64 بت اسم المواصفة: PtypFloating64؛ الأسماء البديلة: PT_DOUBLE ، PT_R8 ، r8 ؛ |
| Currency | `6` | 8 بايت ؛ 64 بت ، تمثيل عدد صحيح مقاس لقيمة العملة العشرية ، بأربعة أماكن على يمين النقطة العشرية اسم المواصفات: PtypCurrency؛ الأسماء البديلة: PT_CURRENCY ، ثابت 14.4 ؛ |
| FloatingTime | `7` | 8 بايت ؛ رقم فاصلة عائمة 64 بت يمثل فيه جزء العدد الكامل عدد الأيام منذ 30 ديسمبر 1899 ، ويمثل الجزء الكسري جزء اليوم منذ منتصف الليل اسم المواصفات: PtypFloatingTime؛ الأسماء البديلة: PT_APPTIME ؛ يتم تمثيل معلومات التاريخ بزيادات العدد الكامل ، بدءًا من 30 ديسمبر 1899 منتصف الليل كوقت صفر. يتم تمثيل معلومات الوقت بجزء من اليوم منذ منتصف الليل السابق. على سبيل المثال ، سيتم تمثيل الساعة 6:00 صباحًا في 4 كانون الثاني (يناير) 1900 بالقيمة 5.25 (5 و 1/4 من اليوم بعد 30 كانون الأول (ديسمبر) 1899). |
| ErrorCode | `10` | 4 بايت ؛ معلومات خطأ ترميز عدد صحيح 32 بت اسم المواصفات: PtypErrorCode؛ الأسماء البديلة: PT_ERROR؛ |
| Boolean | `11` | 1 بايت ؛ يقتصر على 1 أو 0 اسم المواصفات: PtypBoolean؛ الأسماء البديلة: PT_BOOLEAN. منطقي ؛ |
| Integer64 | `20` | 8 بايت ؛ عدد صحيح 64 بت اسم المواصفات: PtypInteger64 ؛ الأسماء البديلة: PT_LONGLONG ، PT_I8 ، i8 ، ui8 ؛ |
| String | `31` | حجم متغير ؛ سلسلة من أحرف Unicode بتنسيق UTF-16LE ترميز بحرف فارغ (0x0000) . اسم المواصفات: PtypString؛ الأسماء البديلة: PT_UNICODE ، سلسلة ؛ |
| String8 | `30` | حجم متغير ؛ سلسلة من الأحرف متعددة البايت في ترميز محدد خارجيًا مع حرف فارغ منتهي (مفرد 0 بايت) . اسم المواصفة: PtypString8؛ الأسماء البديلة: PT_STRING8 ؛ |
| Time | `64` | 8 بايت ؛ عدد صحيح 64 بت يمثل عدد الفواصل الزمنية 100 نانوثانية منذ 1 يناير 1601 اسم المواصفات: PtypTime؛ الأسماء البديلة: PT_SYSTIME، time، datetime، datetime.tz، datetime.rfc1123، Date، time، time.tz؛ |
| Guid | `72` | 16 بايت ؛ GUID مع حقول Data1 و Data2 و Data3 بتنسيق صغير اسم المواصفات: PtypGuid؛ الأسماء البديلة: PT_CLSID ، UUID ؛ |
| ServerId | `251` | حجم متغير ؛ حقل COUNT من 16 بت متبوعًا ببنية اسم المواصفات: PtypServerId؛ الأسماء البديلة: PT_SVREID ؛ |
| Restriction | `253` | حجم متغير ؛ صفيف بايت يمثل بنية تقييد واحدة أو أكثر اسم المواصفات: PtypRestriction؛ الأسماء البديلة: PT_SRESTRICT ؛ |
| RuleAction | `254` | حجم متغير ؛ حقل COUNT من 16 بت متبوعًا بالعديد من هياكل إجراءات القاعدة اسم المواصفة: PtypRuleAction؛ الأسماء البديلة: PT_ACTIONS ؛ |
| Binary | `258` | حجم متغير ؛ حقل COUNT متبوعًا بعدد البايتات. اسم المواصفات: PtypBinary ؛ الأسماء البديلة: PT_BINARY ؛ |
| MultipleInteger16 | `4098` | حجم متغير ؛ حقل COUNT متبوعًا بالعديد من قيم PtypInteger16. اسم المواصفات: PtypMultipleInteger16 ؛ الأسماء البديلة: PT_MV_SHORT ، PT_MV_I2 ، mv.i2 ؛ |
| MultipleInteger32 | `4099` | حجم متغير ؛ حقل COUNT متبوعًا بالعديد من قيم PtypInteger32. اسم المواصفات: PtypMultipleInteger32 ؛ الأسماء البديلة: PT_MV_LONG ، PT_MV_I4 ، mv.i4 ؛ |
| MultipleFloating32 | `4100` | حجم متغير ؛ حقل COUNT متبوعًا بالعديد من قيم PtypFloating32. اسم المواصفات: PtypMultipleFloating32 ؛ الأسماء البديلة: PT_MV_FLOAT ، PT_MV_R4 ، mv.float ؛ |
| MultipleFloating64 | `4101` | حجم متغير ؛ حقل COUNT متبوعًا بالعديد من قيم PtypFloating64. اسم المواصفات: PtypMultipleFloating64 ؛ الأسماء البديلة: PT_MV_DOUBLE ، PT_MV_R8 ؛ |
| MultipleCurrency | `4102` | حجم متغير ؛ حقل COUNT متبوعًا بالعديد من قيم PtypCurrency. اسم المواصفات: PtypMultipleCurrency ؛ الأسماء البديلة: PT_MV_CURRENCY، mv.fixed.14.4؛ |
| MultipleFloatingTime | `4103` | حجم متغير ؛ حقل COUNT متبوعًا بالعديد من قيم PtypFloatingTime. اسم المواصفات: PtypMultipleFloatingTime ؛ الأسماء البديلة: PT_MV_APPTIME ؛ |
| MultipleBoolean | `4107` | حجم متغير ؛ حقل COUNT متبوعًا بالعديد من قيم PtypBoolean. اسم المواصفات: PtypMultipleBoolean ؛ الأسماء البديلة: PT_MV_BOOLEAN ؛ |
| MultipleInteger64 | `4116` | حجم متغير ؛ حقل COUNT متبوعًا بالعديد من قيم PtypInteger64. اسم المواصفات: PtypMultipleInteger64 ؛ الأسماء البديلة: PT_MV_I8 ، PT_MV_LONGLONG ؛ |
| MultipleString | `4127` | حجم متغير ؛ حقل COUNT متبوعًا بالعديد من قيم PtypString. اسم المواصفات: PtypMultipleString ؛ الأسماء البديلة: PT_MV_UNICODE ؛ |
| MultipleString8 | `4126` | حجم متغير ؛ حقل COUNT متبوعًا بالعديد من قيم PtypString8. اسم المواصفات: PtypMultipleString8 ؛ الأسماء البديلة: PT_MV_STRING8 ، mv.string ؛ |
| MultipleTime | `4160` | حجم متغير ؛ حقل COUNT متبوعًا بالعديد من قيم PtypTime. اسم المواصفات: PtypMultipleTime ؛ الأسماء البديلة: PT_MV_SYSTIME ؛ |
| MultipleGuid | `4168` | حجم متغير ؛ حقل COUNT متبوعًا بالعديد من قيم PtypGuid. اسم المواصفات: PtypMultipleGuid ؛ الأسماء البديلة: PT_MV_CLSID ، mv.uuid ؛ |
| MultipleBinary | `4354` | حجم متغير ؛ حقل COUNT متبوعًا بالعديد من قيم PtypBinary. اسم المواصفات: PtypMultipleBinary ؛ الأسماء البديلة: PT_MV_BINARY ، mv.bin.hex ؛ |
| Object | `13` | قيمة الخاصية هي كائن طراز كائن المكون (COM). اسم المواصفات: PtypObject أو PtypEmbeddedTable ؛ الأسماء البديلة: PT_OBJECT ؛ |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Mapi](../../aspose.email.mapi)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
