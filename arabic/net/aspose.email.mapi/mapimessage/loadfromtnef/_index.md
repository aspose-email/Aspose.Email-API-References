---
title: LoadFromTnef
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: تحميل الرسالة من تنسيق بيانات النقل المحايد TNEF هيكل البيانات
type: docs
weight: 50
url: /ar/net/aspose.email.mapi/mapimessage/loadfromtnef/
---
## LoadFromTnef(Stream) {#loadfromtnef}

تحميل الرسالة من تنسيق بيانات النقل المحايد (TNEF) هيكل البيانات

```csharp
public static MapiMessage LoadFromTnef(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | دفق يمثل بيانات الرسالة بتنسيق TNEF |

### قيمة الإرجاع

قراءة[`MapiMessage`](../../mapimessage)

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *stream* هو`لا شيء` |
| NotSupportedException | *stream* لا يدعم القراءة |

### أنظر أيضا

* class [MapiMessage](../../mapimessage)
* مساحة الاسم [Aspose.Email.Mapi](../../mapimessage)
* المجسم [Aspose.Email](../../../)

---

## LoadFromTnef(string) {#loadfromtnef_1}

تحميل الرسالة من تنسيق بيانات النقل المحايد (TNEF) هيكل البيانات

```csharp
public static MapiMessage LoadFromTnef(string fileName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fileName | String | اسم الملف الذي يحتوي على بيانات الرسالة بتنسيق TNEF |

### قيمة الإرجاع

قراءة[`MapiMessage`](../../mapimessage)

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | *fileName* هو`لا شيء`أو`فارغة` |

### أنظر أيضا

* class [MapiMessage](../../mapimessage)
* مساحة الاسم [Aspose.Email.Mapi](../../mapimessage)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->