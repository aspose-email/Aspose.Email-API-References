---
title: ActiveSyncTLClient
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: الفئة الأساسية لتطبيقات عميل ActiveSync
type: docs
weight: 950
url: /ar/net/aspose.email.clients.activesync.transportlayer/activesynctlclient/
---
## ActiveSyncTLClient class

الفئة الأساسية لتطبيقات عميل ActiveSync

```csharp
public class ActiveSyncTLClient : IBaseActiveSyncTLClient
```

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [AuthenticationType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/authenticationtype) { get; set; } | الحصول على نوع المصادقة المستخدم بواسطة عميل ActiveSync أو تعيينه. |
| virtual [AutodiscoverUri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscoveruri) { get; set; } | الحصول على خدمة الاكتشاف التلقائي أو تعيينها uri |
| virtual [Credentials](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/credentials) { get; } | بيانات اعتماد المستخدم لخادم Exchange |
| virtual [DeviceID](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/deviceid) { get; set; } | GUID الذي يقوم بتعريف الجهاز. يتم تحديد معرف الجهاز بواسطة جزء قاعدة ABNF الخاص بمواصفات معرف الجهاز لقيمة استعلام النص العادي. القيمة ، ممثلة بقاعدة ABNF معرّف الجهاز ، هي سلسلة تحدد الجهاز. يجب أن يكون لكل جهاز سلسلة معرف جهاز فريد. يجب أن يتضمن كل طلب من الجهاز نفس سلسلة معرف الجهاز. |
| virtual [DeviceType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/devicetype) { get; set; } | يتم تحديد نوع الجهاز بواسطة جزء قاعدة ABNF من نوع مواصفات الجهاز لقيمة استعلام النص العادي. القيمة ، ممثلة بقاعدة ABNF من نوع الجهاز ، هي أي سلسلة تحدد نوع الجهاز. "SP" تحدد الهاتف الذكي و "PPC" تحدد PocketPC. ترسل الأجهزة العميلة الأخرى سلاسل فريدة لنوع الجهاز المحدد الخاص بها. يجب أن يتضمن كل طلب من جهاز عميل نفس سلسلة نوع الجهاز. |
| virtual [PolicyState](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/policystate) { get; set; } | عدد صحيح بدون إشارة يشير إلى حالة إعدادات النهج على جهاز العميل ، كما هو محدد في القسم [MS-ASPROV] 2.2.2.41. |
| virtual [Proxy](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/proxy) { get; set; } | الحصول على الوكيل أو تعيينه. |
| virtual [SupportedServerCommands](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedservercommands) { get; } | يحصل على إصدارات أوامر ActiveSync المدعومة |
| virtual [SupportedServerProtocols](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedserverprotocols) { get; } | يحصل على إصدارات بروتوكولات ActiveSync المدعومة |
| virtual [Timeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/timeout) { get; set; } | الحصول على أو تعيين عدد المللي ثانية للانتظار قبل انتهاء مهلة العملية . القيمة الافتراضية هي 100000 مللي ثانية (100 ثانية) . |
| virtual [Uri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/uri) { get; } | الحصول على عنوان URL لخدمة ActiveSync |
| virtual [UserAgent](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/useragent) { get; set; } | يحتوي حقل عنوان طلب وكيل المستخدم على معلومات حول وكيل المستخدم الذي أنشأ الطلب. هذا للأغراض الإحصائية ، وتعقب انتهاكات البروتوكول ، والتعرف الآلي على وكلاء المستخدم من أجل تخصيص الاستجابات لتجنب قيود وكيل المستخدم. يجب على وكلاء المستخدم تضمين هذا الحقل مع الطلبات. يمكن أن يحتوي الحقل على العديد من الرموز المميزة للمنتج (القسم 3.8) والتعليقات التي تحدد الوكيل وأي منتجات فرعية تشكل جزءًا مهمًا من وكيل المستخدم. حسب الاصطلاح ، يتم سرد الرموز المميزة للمنتج حسب أهميتها في تحديد التطبيق. مثال: وكيل المستخدم: CERN-LineMode / 2.15 libwww / 2.17b3 |
| virtual [Version](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/version) { get; } | الحصول على إصدار البروتوكول المستخدم في عميل ActiveSync. |
| static [DefaultTimeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/defaulttimeout) { get; set; } | الحصول على أو تعيين قيمة المهلة الافتراضية لمثيلات عميل ActiveSync القيمة الافتراضية هي 100000 مللي ثانية (100 ثانية) . |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string) | يسهل أمر الاكتشاف التلقائي اكتشاف معلومات تكوين الحساب الأساسي باستخدام عنوان بروتوكول نقل البريد البسيط (SMTP) الخاص بالمستخدم كمدخل أساسي. |
| [Dispose](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/dispose)() | يؤدي المهام المرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| static [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string, NetworkCredential, string) | يسهل أمر الاكتشاف التلقائي اكتشاف معلومات تكوين الحساب الأساسي باستخدام عنوان بروتوكول نقل البريد البسيط (SMTP) الخاص بالمستخدم كمدخل أساسي. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance)(string, NetworkCredential) | الحصول على مثيل لـ ActiveSync client يتم تحديد إصدار بروتوكول ActiveSync تلقائيًا وفقًا لاستجابة الخادم. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance_1)(string, NetworkCredential, ASProtocolVersions) | الحصول على مثيل لـ ActiveSync client |
| static [GetOptions](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getoptions)(string, NetworkCredential, out string[], out string[]) | يتم استخدام الأسلوب الثابت GetOptions لاكتشاف إصدارات البروتوكول المدعومة وأوامر البروتوكول المدعومة على الخادم. يستخدم العميل أسلوب GetOptions الثابت لتحديد ما إذا كان الخادم يدعم نفس إصدارات البروتوكول التي يدعمها العميل. |

### أنظر أيضا

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
