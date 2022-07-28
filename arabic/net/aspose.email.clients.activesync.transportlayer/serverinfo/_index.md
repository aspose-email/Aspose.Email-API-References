---
title: ServerInfo
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: إعدادات الخادم في عملية الاكتشاف التلقائي
type: docs
weight: 2030
url: /ar/net/aspose.email.clients.activesync.transportlayer/serverinfo/
---
## ServerInfo class

إعدادات الخادم في عملية الاكتشاف التلقائي

```csharp
public class ServerInfo
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ServerInfo](serverinfo)(ServerType, string, string, string) | تهيئة مثيل جديد لفئة ServerInfo. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Name](../../aspose.email.clients.activesync.transportlayer/serverinfo/name) { get; } | يحدد عنوان URL إذا تم تعيين قيمة عنصر النوع (القسم 2.2.3.170.1) على "MobileSync" . إذا كانت قيمة عنصر النوع هي "MobileSync" ، فإن عنصر الاسم يحدد عنوان URL الذي ينقل البروتوكول. إذا كانت قيمة عنصر النوع هي "CertEnroll" ، فإن قيمة عنصر الاسم هي NULL. |
| [ServerData](../../aspose.email.clients.activesync.transportlayer/serverinfo/serverdata) { get; } | تحدد ServerData اسم القالب لشهادة العميل. اختياري. |
| [Type](../../aspose.email.clients.activesync.transportlayer/serverinfo/type) { get; } | يحدد نوع الخادم فيما يلي القيم الصالحة لعنصر النوع: MobileSync - يشير إلى أن عنوان URL الذي يتم إرجاعه بواسطة عنصر URL (القسم 2.2.3.172) يمكن الوصول إليه بواسطة العملاء. CertEnroll - يشير إلى أن عنوان URL الذي تم إرجاعه بواسطة عنصر URL (القسم 2.2.3.172) يتم إرجاعه بواسطة عنصر URL يمكن الوصول إليه من قبل العملاء للحصول على شهادة عميل لمفاوضات طبقة مآخذ التوصيل الآمنة (SSL). |
| [Url](../../aspose.email.clients.activesync.transportlayer/serverinfo/url) { get; } | يحدد سلسلة عنوان URL التي تنقل البروتوكول والمنفذ وموقع المورد ومعلومات أخرى. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [ToString](../../aspose.email.clients.activesync.transportlayer/serverinfo/tostring)() | إرجاع سلسلة تمثل الكائن الحالي. |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->