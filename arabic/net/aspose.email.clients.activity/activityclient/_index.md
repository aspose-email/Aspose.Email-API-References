---
title: ActivityClient
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يوفر الوصول إلى MS Exchange Server Office365 باستخدام REST API.
type: docs
weight: 2360
url: /ar/net/aspose.email.clients.activity/activityclient/
---
## ActivityClient class

يوفر الوصول إلى MS Exchange Server (Office365) باستخدام REST API.

```csharp
public abstract class ActivityClient : IActivityClient
```

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [MultipleServicesTokenProvider](../../aspose.email.clients.activity/activityclient/multipleservicestokenprovider) { get; set; } | الحصول على كائن أو تعيينه يسمح باسترداد رمز وصول OAuth. |
| virtual [Proxy](../../aspose.email.clients.activity/activityclient/proxy) { get; set; } | الحصول على البيانات أو تعيينها للوصول إلى خادم Exchange. |
| virtual [ResourceId](../../aspose.email.clients.activity/activityclient/resourceid) { get; set; } | الحصول على معرف المورد أو تعيينه . على سبيل المثال ، قد يكون اسم المستخدم الأساسي (UPN) أو معرف المستخدم |
| virtual [TenantId](../../aspose.email.clients.activity/activityclient/tenantid) { get; set; } | الحصول على أو تعيين معرف المستأجر |
| virtual [Timeout](../../aspose.email.clients.activity/activityclient/timeout) { get; set; } | الحصول على أو تعيين عدد المللي ثانية للانتظار قبل انتهاء مهلة العملية . القيمة الافتراضية هي 100000 مللي ثانية (100 ثانية) . |
| virtual [TokenProvider](../../aspose.email.clients.activity/activityclient/tokenprovider) { get; set; } | الحصول على كائن أو تعيينه يسمح باسترداد رمز وصول OAuth. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients.activity/activityclient/dispose)() | تنفيذ مهام محددة بواسطة التطبيق مرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| [FetchContent](../../aspose.email.clients.activity/activityclient/fetchcontent)(string) |  |
| [ListContent](../../aspose.email.clients.activity/activityclient/listcontent#listcontent)(string) |  |
| [ListContent](../../aspose.email.clients.activity/activityclient/listcontent#listcontent_1)(string, DateTime?, DateTime?) |  |
| [ListFriendlyNames](../../aspose.email.clients.activity/activityclient/listfriendlynames)() |  |
| [ListSubscriptions](../../aspose.email.clients.activity/activityclient/listsubscriptions)() |  |
| [StartSubscription](../../aspose.email.clients.activity/activityclient/startsubscription)(string, Webhook) |  |
| [StopSubscription](../../aspose.email.clients.activity/activityclient/stopsubscription)(string) |  |
| static [GetClient](../../aspose.email.clients.activity/activityclient/getclient#getclient)(IMultipleServicesTokenProvider, string) | يقوم بتهيئة مثيل جديد لملف[`ActivityClient`](../activityclient) class مقرها |
| static [GetClient](../../aspose.email.clients.activity/activityclient/getclient#getclient_1)(ITokenProvider, string) | يقوم بتهيئة مثيل جديد لملف[`ActivityClient`](../activityclient) class مقرها |

### أنظر أيضا

* interface [IActivityClient](../iactivityclient)
* مساحة الاسم [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->