---
title: O365EmailMessageActivity
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: لتوسيع المخطط العام بالخصائص الخاصة ببيانات الحماية المتقدمة من التهديدات والحماية من التهديدات لـ Office 365. تتوفر أحداث الحماية المتقدمة من التهديدات ATP و Office 365 لعملاء Office 365 الذين لديهم اشتراك ATP أو ذكاء التهديدات أو E5 . يتوافق كل حدث في موجز ATP واستخبارات التهديدات مع يتم إرسال رسالة بريد إلكتروني أو استلامها بواسطة مستخدم في المؤسسة مع اكتشافات على الرسائل في وقت التسليم ومن المسح التلقائي لساعة الصفر .
type: docs
weight: 2660
url: /ar/net/aspose.email.clients.activity/o365emailmessageactivity/
---
## O365EmailMessageActivity class

لتوسيع المخطط العام بالخصائص الخاصة ببيانات الحماية المتقدمة من التهديدات والحماية من التهديدات لـ Office 365. تتوفر أحداث الحماية المتقدمة من التهديدات (ATP) و Office 365 لعملاء Office 365 الذين لديهم اشتراك ATP أو ذكاء التهديدات أو E5 . يتوافق كل حدث في موجز ATP واستخبارات التهديدات مع يتم إرسال رسالة بريد إلكتروني أو استلامها بواسطة مستخدم في المؤسسة مع اكتشافات على الرسائل في وقت التسليم ومن المسح التلقائي لساعة الصفر .

```csharp
public class O365EmailMessageActivity : Content
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [O365EmailMessageActivity](o365emailmessageactivity)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AttachmentData](../../aspose.email.clients.activity/o365emailmessageactivity/attachmentdata) { get; set; } | بيانات حول المرفقات في رسالة البريد الإلكتروني التي أدت إلى تشغيل الحدث. إلزامي: No |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | عنوان IP للجهاز الذي تم استخدامه عند تسجيل النشاط. يتم عرض عنوان IP بتنسيق عنوان IPv4 أو IPv6 . إلزامي: نعم |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | التاريخ والوقت بالتوقيت العالمي المنسق (UTC) عندما أجرى المستخدم النشاط. إلزامي: نعم |
| [DetectionMethod](../../aspose.email.clients.activity/o365emailmessageactivity/detectionmethod) { get; set; } | الطريقة أو التقنية المستخدمة بواسطة Office 365 ATP للكشف . إلزامي: نعم |
| [DetectionType](../../aspose.email.clients.activity/o365emailmessageactivity/detectiontype) { get; set; } | نوع الاكتشاف . إلزامي: نعم |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | معرّف فريد لسجل التدقيق . إلزامي: نعم |
| [InternetMessageId](../../aspose.email.clients.activity/o365emailmessageactivity/internetmessageid) { get; set; } | معرف رسالة الإنترنت . إلزامي: نعم |
| [NetworkMessageId](../../aspose.email.clients.activity/o365emailmessageactivity/networkmessageid) { get; set; } | معرف رسالة شبكة Exchange عبر الإنترنت . إلزامي: نعم |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | بالنسبة لنشاط SharePoint و OneDrive for Business ، اسم المسار الكامل للملف أو المجلد الذي يمكن للمستخدم الوصول إليه. لتسجيل تدقيق مسؤول Exchange ، اسم الكائن الذي تم تعديله بواسطة الأمر cmdlet . إلزامي: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | اسم المستخدم أو نشاط المسؤول. للحصول على وصف للعمليات / الأنشطة الأكثر شيوعًا ، راجع البحث في سجل التدقيق في مركز حماية Office 365. بالنسبة لنشاط مسؤول Exchange ، تحدد هذه الخاصية اسم أمر cmdlet الذي تم تشغيله. بالنسبة لأحداث Dlp ، يمكن أن يكون هذا "DlpRuleMatch" أو "DlpRuleUndo" أو "DlpInfo" ، والتي تم وصفها ضمن "مخطط DLP" أدناه. إلزامي: Yes |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | المعرف الفريد العمومي (GUID) لمستأجر Office 365 الخاص بمؤسستك. ستكون هذه القيمة هي نفسها دائمًا لمؤسستك ، بغض النظر عن خدمة Office 365 التي تحدث فيها . إلزامي: نعم |
| [P1Sender](../../aspose.email.clients.activity/o365emailmessageactivity/p1sender) { get; set; } | مسار الإرجاع لمرسل رسالة البريد الإلكتروني . إلزامي: نعم |
| [P2Sender](../../aspose.email.clients.activity/o365emailmessageactivity/p2sender) { get; set; } | من مرسل رسالة البريد الإلكتروني . إلزامي: نعم |
| [Recipients](../../aspose.email.clients.activity/o365emailmessageactivity/recipients) { get; set; } | مصفوفة من مستلمي رسالة البريد الإلكتروني . إلزامي: نعم |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | نوع العملية المشار إليها بالسجل. إلزامي: نعم |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | يشير إلى ما إذا كان الإجراء (المحدد في خاصية العملية) ناجحًا أم لا. القيم المحتملة هي النجاح أو الجزئي أو الفاشل. بالنسبة لنشاط مسؤول Exchange ، تكون القيمة إما صحيحة أو خاطئة. إلزامي: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | هل تم إنشاء هذا الحدث بواسطة خدمة O365 مستضافة أو خادم محلي؟ القيم المحتملة متصلة بالإنترنت وفي وقت مبكر. لاحظ أن SharePoint هو حمل العمل الوحيد الذي يرسل حاليًا الأحداث من أماكن العمل إلى O365. إلزامي: No |
| [SenderIp](../../aspose.email.clients.activity/o365emailmessageactivity/senderip) { get; set; } | عنوان IP الذي أرسل البريد الإلكتروني الخاص بـ Office 365. يتم عرض عنوان IP بتنسيق عنوان IPv4 أو IPv6 . إلزامي: Yes |
| [Subject](../../aspose.email.clients.activity/o365emailmessageactivity/subject) { get; set; } | سطر موضوع الرسالة . إلزامي: نعم |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | UPN (اسم المستخدم الأساسي) للمستخدم الذي نفذ الإجراء (المحدد في خاصية العملية) الذي أدى إلى تسجيل السجل ؛ على سبيل المثال ، my_name @ my_domain_name. لاحظ أنه يتم أيضًا تضمين سجلات النشاط الذي تقوم به حسابات النظام (مثل SHAREPOINT \ system أو NT AUTHORITY \ SYSTEM). إلزامي: نعم |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | معرف بديل للمستخدم المحدد في خاصية UserId. على سبيل المثال ، يتم ملء هذه الخاصية بمعرف جواز السفر الفريد (PUID) للأحداث التي يقوم بها المستخدمون في SharePoint و OneDrive for Business و Exchange. قد تحدد هذه الخاصية أيضًا نفس القيمة مثل خاصية UserID للأحداث التي تحدث في الخدمات والأحداث الأخرى التي يتم تنفيذها بواسطة حسابات النظام. إلزامي: نعم |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | نوع المستخدم الذي أجرى العملية. إلزامي: نعم |
| [Verdict](../../aspose.email.clients.activity/o365emailmessageactivity/verdict) { get; set; } | الحكم على الرسالة. إلزامي: نعم |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | خدمة Office 365 حيث حدث النشاط في سلسلة Workload. القيم المحتملة لهذه الخاصية هي: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence إلزامي: No |

### أنظر أيضا

* class [Content](../content)
* مساحة الاسم [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
