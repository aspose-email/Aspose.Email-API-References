---
title: ExchangeAdminActivity
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: لتوسيع المخطط الشائع بالخصائص المحددة لجميع بيانات تدقيق مسؤول Exchange.
type: docs
weight: 2480
url: /ar/net/aspose.email.clients.activity/exchangeadminactivity/
---
## ExchangeAdminActivity class

لتوسيع المخطط الشائع بالخصائص المحددة لجميع بيانات تدقيق مسؤول Exchange.

```csharp
public class ExchangeAdminActivity : Content
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ExchangeAdminActivity](exchangeadminactivity)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | عنوان IP للجهاز الذي تم استخدامه عند تسجيل النشاط. يتم عرض عنوان IP بتنسيق عنوان IPv4 أو IPv6 . إلزامي: نعم |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | التاريخ والوقت بالتوقيت العالمي المنسق (UTC) عندما أجرى المستخدم النشاط. إلزامي: نعم |
| [ExternalAccess](../../aspose.email.clients.activity/exchangeadminactivity/externalaccess) { get; set; } | تحديد ما إذا كان قد تم تشغيل أمر cmdlet بواسطة مستخدم في مؤسستك ، أو بواسطة موظفي مركز بيانات Microsoft أو حساب خدمة مركز البيانات ، أو بواسطة مسؤول مفوض. تشير القيمة False إلى أنه تم تشغيل الأمر cmdlet بواسطة شخص ما في مؤسستك. تشير القيمة True إلى أن الأمر cmdlet تم تشغيله بواسطة أفراد مركز البيانات ، أو حساب خدمة مركز البيانات ، أو مسؤول مفوض. |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | معرّف فريد لسجل التدقيق . إلزامي: نعم |
| [ModifiedObjectResolvedName](../../aspose.email.clients.activity/exchangeadminactivity/modifiedobjectresolvedname) { get; set; } | هذا هو الاسم المألوف للمستخدم للكائن الذي تم تعديله بواسطة الأمر cmdlet. يتم تسجيل هذا فقط إذا كان الأمر cmdlet يعدل الكائن. |
| [ModifiedProperties](../../aspose.email.clients.activity/exchangeadminactivity/modifiedproperties) { get; set; } | تم تضمين الخاصية لأحداث المسؤول. تتضمن الخاصية اسم الخاصية التي تم تعديلها والقيمة الجديدة للخاصية المعدلة والقيمة السابقة للكائن المعدل. |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | بالنسبة لنشاط SharePoint و OneDrive for Business ، اسم المسار الكامل للملف أو المجلد الذي يمكن للمستخدم الوصول إليه. لتسجيل تدقيق مسؤول Exchange ، اسم الكائن الذي تم تعديله بواسطة الأمر cmdlet . إلزامي: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | اسم المستخدم أو نشاط المسؤول. للحصول على وصف للعمليات / الأنشطة الأكثر شيوعًا ، راجع البحث في سجل التدقيق في مركز حماية Office 365. بالنسبة لنشاط مسؤول Exchange ، تحدد هذه الخاصية اسم أمر cmdlet الذي تم تشغيله. بالنسبة لأحداث Dlp ، يمكن أن يكون هذا "DlpRuleMatch" أو "DlpRuleUndo" أو "DlpInfo" ، والتي تم وصفها ضمن "مخطط DLP" أدناه. إلزامي: Yes |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | المعرف الفريد العمومي (GUID) لمستأجر Office 365 الخاص بمؤسستك. ستكون هذه القيمة هي نفسها دائمًا لمؤسستك ، بغض النظر عن خدمة Office 365 التي تحدث فيها . إلزامي: نعم |
| [OrganizationName](../../aspose.email.clients.activity/exchangeadminactivity/organizationname) { get; set; } | اسم المستأجر . |
| [OriginatingServer](../../aspose.email.clients.activity/exchangeadminactivity/originatingserver) { get; set; } | اسم الخادم الذي تم من خلاله تنفيذ الأمر cmdlet . |
| [Parameters](../../aspose.email.clients.activity/exchangeadminactivity/parameters) { get; set; } | الاسم والقيمة لكافة المعلمات التي تم استخدامها مع الأمر cmdlet المحدد في خاصية العمليات. |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | نوع العملية المشار إليها بالسجل. إلزامي: نعم |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | يشير إلى ما إذا كان الإجراء (المحدد في خاصية العملية) ناجحًا أم لا. القيم المحتملة هي النجاح أو الجزئي أو الفاشل. بالنسبة لنشاط مسؤول Exchange ، تكون القيمة إما صحيحة أو خاطئة. إلزامي: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | هل تم إنشاء هذا الحدث بواسطة خدمة O365 مستضافة أو خادم محلي؟ القيم المحتملة متصلة بالإنترنت وفي وقت مبكر. لاحظ أن SharePoint هو حمل العمل الوحيد الذي يرسل حاليًا الأحداث من أماكن العمل إلى O365. إلزامي: No |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | UPN (اسم المستخدم الأساسي) للمستخدم الذي نفذ الإجراء (المحدد في خاصية العملية) الذي أدى إلى تسجيل السجل ؛ على سبيل المثال ، my_name @ my_domain_name. لاحظ أنه يتم أيضًا تضمين سجلات النشاط الذي تقوم به حسابات النظام (مثل SHAREPOINT \ system أو NT AUTHORITY \ SYSTEM). إلزامي: نعم |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | معرف بديل للمستخدم المحدد في خاصية UserId. على سبيل المثال ، يتم ملء هذه الخاصية بمعرف جواز السفر الفريد (PUID) للأحداث التي يقوم بها المستخدمون في SharePoint و OneDrive for Business و Exchange. قد تحدد هذه الخاصية أيضًا نفس القيمة مثل خاصية UserID للأحداث التي تحدث في الخدمات والأحداث الأخرى التي يتم تنفيذها بواسطة حسابات النظام. إلزامي: نعم |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | نوع المستخدم الذي أجرى العملية. إلزامي: نعم |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | خدمة Office 365 حيث حدث النشاط في سلسلة Workload. القيم المحتملة لهذه الخاصية هي: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence إلزامي: No |

### أنظر أيضا

* class [Content](../content)
* مساحة الاسم [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
