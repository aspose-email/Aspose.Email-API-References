---
title: ExchangeMailboxAuditGroupActivity
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: 
type: docs
weight: 2530
url: /ar/net/aspose.email.clients.activity/exchangemailboxauditgroupactivity/
---
## ExchangeMailboxAuditGroupActivity class

```csharp
public class ExchangeMailboxAuditGroupActivity : Content
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ExchangeMailboxAuditGroupActivity](exchangemailboxauditgroupactivity)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AffectedItems](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/affecteditems) { get; set; } | معلومات حول كل عنصر في المجموعة. |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | عنوان IP للجهاز الذي تم استخدامه عند تسجيل النشاط. يتم عرض عنوان IP بتنسيق عنوان IPv4 أو IPv6 . إلزامي: نعم |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | التاريخ والوقت بالتوقيت العالمي المنسق (UTC) عندما أجرى المستخدم النشاط. إلزامي: نعم |
| [CrossMailboxOperations](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/crossmailboxoperations) { get; set; } | يشير إلى ما إذا كانت العملية تتضمن أكثر من صندوق بريد واحد. |
| [DestFolder](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destfolder) { get; set; } | المجلد الوجهة لعمليات مثل Move . |
| [DestMailboxId](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxid) { get; set; } | اضبط فقط إذا كانت معلمة CrossMailboxOperations صحيحة. يحدد صندوق البريد الهدف GUID. |
| [DestMailboxOwnerMasterAccountSid](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownermasteraccountsid) { get; set; } | اضبط فقط إذا كانت معلمة CrossMailboxOperations صحيحة. تعيّن SID للحساب الرئيسي SID لمالك علبة البريد الهدف. |
| [DestMailboxOwnerSid](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownersid) { get; set; } | اضبط فقط إذا كانت معلمة CrossMailboxOperations صحيحة. يحدد معرّف الأمان (SID) الخاص بصندوق البريد الهدف. |
| [DestMailboxOwnerUPN](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownerupn) { get; set; } | اضبط فقط إذا كانت معلمة CrossMailboxOperations صحيحة. يحدد UPN لمالك صندوق البريد الهدف. |
| [Folder](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/folder) { get; set; } | المجلد الذي توجد به مجموعة من العناصر . |
| [Folders](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/folders) { get; set; } | معلومات حول مجلدات المصدر المتضمنة في عملية ما ؛ على سبيل المثال ، إذا تم تحديد المجلدات ثم حذفها. |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | معرّف فريد لسجل التدقيق . إلزامي: نعم |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | بالنسبة لنشاط SharePoint و OneDrive for Business ، اسم المسار الكامل للملف أو المجلد الذي يمكن للمستخدم الوصول إليه. لتسجيل تدقيق مسؤول Exchange ، اسم الكائن الذي تم تعديله بواسطة الأمر cmdlet . إلزامي: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | اسم المستخدم أو نشاط المسؤول. للحصول على وصف للعمليات / الأنشطة الأكثر شيوعًا ، راجع البحث في سجل التدقيق في مركز حماية Office 365. بالنسبة لنشاط مسؤول Exchange ، تحدد هذه الخاصية اسم أمر cmdlet الذي تم تشغيله. بالنسبة لأحداث Dlp ، يمكن أن يكون هذا "DlpRuleMatch" أو "DlpRuleUndo" أو "DlpInfo" ، والتي تم وصفها ضمن "مخطط DLP" أدناه. إلزامي: Yes |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | المعرف الفريد العمومي (GUID) لمستأجر Office 365 الخاص بمؤسستك. ستكون هذه القيمة هي نفسها دائمًا لمؤسستك ، بغض النظر عن خدمة Office 365 التي تحدث فيها . إلزامي: نعم |
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
