---
title: O365URLTimeOfClickActivity
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: لتوسيع المخطط العام بالخصائص الخاصة ببيانات الحماية المتقدمة من التهديدات والحماية من التهديدات لـ Office 365. تتوفر أحداث الحماية المتقدمة من التهديدات ATP و Office 365 لعملاء Office 365 الذين لديهم اشتراك ATP أو ذكاء التهديدات أو E5 . يتوافق كل حدث في موجز ATP واستخبارات التهديدات مع عناوين URL التي نقر عليها مستخدم في المؤسسة والتي تم اكتشافها على أنها ضارة في وقت النقر استنادًا إلى حماية الروابط الآمنة لـ Office 365 ATP .
type: docs
weight: 2670
url: /ar/net/aspose.email.clients.activity/o365urltimeofclickactivity/
---
## O365URLTimeOfClickActivity class

لتوسيع المخطط العام بالخصائص الخاصة ببيانات الحماية المتقدمة من التهديدات والحماية من التهديدات لـ Office 365. تتوفر أحداث الحماية المتقدمة من التهديدات (ATP) و Office 365 لعملاء Office 365 الذين لديهم اشتراك ATP أو ذكاء التهديدات أو E5 . يتوافق كل حدث في موجز ATP واستخبارات التهديدات مع عناوين URL التي نقر عليها مستخدم في المؤسسة والتي تم اكتشافها على أنها ضارة في وقت النقر استنادًا إلى حماية الروابط الآمنة لـ Office 365 ATP .

```csharp
public class O365URLTimeOfClickActivity : Content
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [O365URLTimeOfClickActivity](o365urltimeofclickactivity)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AppName](../../aspose.email.clients.activity/o365urltimeofclickactivity/appname) { get; set; } | خدمة Office 365 التي تم النقر فوق عنوان URL منها (مثل البريد) . إلزامي: نعم |
| [Blocked](../../aspose.email.clients.activity/o365urltimeofclickactivity/blocked) { get; set; } | هذا صحيح إذا تم حظر نقرة URL بواسطة حماية الروابط الآمنة لـ Office 365 ATP . إلزامي: نعم |
| [ClickedThrough](../../aspose.email.clients.activity/o365urltimeofclickactivity/clickedthrough) { get; set; } | هذا صحيح إذا تم النقر فوق كتلة عنوان URL (تجاوزها) بواسطة المستخدم بناءً على سياسات المؤسسة لحماية الروابط الآمنة لـ Office 365 ATP . إلزامي: نعم |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | عنوان IP للجهاز الذي تم استخدامه عند تسجيل النشاط. يتم عرض عنوان IP بتنسيق عنوان IPv4 أو IPv6 . إلزامي: نعم |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | التاريخ والوقت بالتوقيت العالمي المنسق (UTC) عندما أجرى المستخدم النشاط. إلزامي: نعم |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | معرّف فريد لسجل التدقيق . إلزامي: نعم |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | بالنسبة لنشاط SharePoint و OneDrive for Business ، اسم المسار الكامل للملف أو المجلد الذي يمكن للمستخدم الوصول إليه. لتسجيل تدقيق مسؤول Exchange ، اسم الكائن الذي تم تعديله بواسطة الأمر cmdlet . إلزامي: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | اسم المستخدم أو نشاط المسؤول. للحصول على وصف للعمليات / الأنشطة الأكثر شيوعًا ، راجع البحث في سجل التدقيق في مركز حماية Office 365. بالنسبة لنشاط مسؤول Exchange ، تحدد هذه الخاصية اسم أمر cmdlet الذي تم تشغيله. بالنسبة لأحداث Dlp ، يمكن أن يكون هذا "DlpRuleMatch" أو "DlpRuleUndo" أو "DlpInfo" ، والتي تم وصفها ضمن "مخطط DLP" أدناه. إلزامي: Yes |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | المعرف الفريد العمومي (GUID) لمستأجر Office 365 الخاص بمؤسستك. ستكون هذه القيمة هي نفسها دائمًا لمؤسستك ، بغض النظر عن خدمة Office 365 التي تحدث فيها . إلزامي: نعم |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | نوع العملية المشار إليها بالسجل. إلزامي: نعم |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | يشير إلى ما إذا كان الإجراء (المحدد في خاصية العملية) ناجحًا أم لا. القيم المحتملة هي النجاح أو الجزئي أو الفاشل. بالنسبة لنشاط مسؤول Exchange ، تكون القيمة إما صحيحة أو خاطئة. إلزامي: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | هل تم إنشاء هذا الحدث بواسطة خدمة O365 مستضافة أو خادم محلي؟ القيم المحتملة متصلة بالإنترنت وفي وقت مبكر. لاحظ أن SharePoint هو حمل العمل الوحيد الذي يرسل حاليًا الأحداث من أماكن العمل إلى O365. إلزامي: No |
| [SourceId](../../aspose.email.clients.activity/o365urltimeofclickactivity/sourceid) { get; set; } | معرّف خدمة Office 365 التي تم النقر فوق عنوان URL منها (على سبيل المثال ، بالنسبة إلى Mail ، هذا هو معرف رسالة شبكة Exchange عبر الإنترنت) . إلزامي: Yes |
| [TimeOfClick](../../aspose.email.clients.activity/o365urltimeofclickactivity/timeofclick) { get; set; } | التاريخ والوقت بالتوقيت العالمي المنسق (UTC) عندما نقر المستخدم على عنوان URL . إلزامي: نعم |
| [URL](../../aspose.email.clients.activity/o365urltimeofclickactivity/url) { get; set; } | نقر المستخدم على عنوان URL . إلزامي: نعم |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | UPN (اسم المستخدم الأساسي) للمستخدم الذي نفذ الإجراء (المحدد في خاصية العملية) الذي أدى إلى تسجيل السجل ؛ على سبيل المثال ، my_name @ my_domain_name. لاحظ أنه يتم أيضًا تضمين سجلات النشاط الذي تقوم به حسابات النظام (مثل SHAREPOINT \ system أو NT AUTHORITY \ SYSTEM). إلزامي: نعم |
| [UserIp](../../aspose.email.clients.activity/o365urltimeofclickactivity/userip) { get; set; } | عنوان IP الخاص بالمستخدم الذي قام بالنقر فوق عنوان URL. يتم عرض عنوان IP بتنسيق عنوان IPv4 أو IPv6 . إلزامي: Yes |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | معرف بديل للمستخدم المحدد في خاصية UserId. على سبيل المثال ، يتم ملء هذه الخاصية بمعرف جواز السفر الفريد (PUID) للأحداث التي يقوم بها المستخدمون في SharePoint و OneDrive for Business و Exchange. قد تحدد هذه الخاصية أيضًا نفس القيمة مثل خاصية UserID للأحداث التي تحدث في الخدمات والأحداث الأخرى التي يتم تنفيذها بواسطة حسابات النظام. إلزامي: نعم |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | نوع المستخدم الذي أجرى العملية. إلزامي: نعم |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | خدمة Office 365 حيث حدث النشاط في سلسلة Workload. القيم المحتملة لهذه الخاصية هي: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence إلزامي: No |

### أنظر أيضا

* class [Content](../content)
* مساحة الاسم [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
