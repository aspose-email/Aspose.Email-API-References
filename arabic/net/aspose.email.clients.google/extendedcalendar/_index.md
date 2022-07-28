---
title: ExtendedCalendar
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: مجموعة من البيانات الوصفية الممتدة  مثل الألوان  لتقويم واحد.
type: docs
weight: 15700
url: /ar/net/aspose.email.clients.google/extendedcalendar/
---
## ExtendedCalendar class

مجموعة من البيانات الوصفية الممتدة ، مثل الألوان ، لتقويم واحد.

```csharp
public class ExtendedCalendar : Calendar
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ExtendedCalendar](extendedcalendar#constructor)() | تهيئة مثيل جديد لفئة ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_1)(string) | تهيئة مثيل جديد لفئة ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_2)(string, string) | تهيئة مثيل جديد لفئة ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_3)(string, string, string, string) | تهيئة مثيل جديد لفئة ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_4)(string, string, string, string, string) | تهيئة مثيل جديد لفئة ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_5)(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | تهيئة مثيل جديد لفئة ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_6)(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | تهيئة مثيل جديد لفئة ExtendedCalendar. |

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [AccessRole](../../aspose.email.clients.google/extendedcalendar/accessrole) { get; } | دور الوصول الفعال الذي يتمتع به المستخدم المصادق عليه في التقويم. يقرأ فقط. القيم الممكنة هي: |
| virtual [BackgroundColor](../../aspose.email.clients.google/extendedcalendar/backgroundcolor) { get; set; } | اللون الرئيسي للتقويم بتنسيق "# 0088aa". هذه الخاصية تحل محل خاصية colorId المستندة إلى الفهرس. |
| virtual [ColorId](../../aspose.email.clients.google/extendedcalendar/colorid) { get; set; } | لون التقويم. هذا معرف يشير إلى إدخال في قسم "التقويم" لتعريف الألوان (انظر نقطة نهاية "الألوان") . |
| virtual [ConferenceProperties](../../aspose.email.clients.google/calendar/conferenceproperties) { get; } | الحصول على خصائص المؤتمر لهذا التقويم . |
| virtual [DefaultReminders](../../aspose.email.clients.google/extendedcalendar/defaultreminders) { get; set; } | التذكيرات الافتراضية التي يمتلكها المستخدم المصادق عليه لهذا التقويم. |
| virtual [Description](../../aspose.email.clients.google/calendar/description) { get; set; } | وصف التقويم. |
| virtual [ETag](../../aspose.email.clients.google/basedataobject/etag) { get; set; } | علامة ETag أو علامة الكيان هي إحدى الآليات العديدة التي يوفرها HTTP للتحقق من ذاكرة التخزين المؤقت على الويب ، والتي تسمح للعميل بإجراء طلبات مشروطة. هذا يسمح بأن تكون ذاكرات التخزين المؤقت أكثر كفاءة ، ويحفظ النطاق الترددي ، لأن خادم الويب لا يحتاج إلى إرسال استجابة كاملة إذا لم يتغير المحتوى. يمكن أيضًا استخدام ETags للتحكم المتفائل في التزامن ، كطريقة للمساعدة في منع التحديثات المتزامنة للمورد من الكتابة فوق بعضها البعض. |
| virtual [ForegroundColor](../../aspose.email.clients.google/extendedcalendar/foregroundcolor) { get; set; } | لون المقدمة للتقويم بتنسيق "#ffffff". هذه الخاصية تحل محل خاصية colorId المستندة إلى الفهرس. |
| virtual [Hidden](../../aspose.email.clients.google/extendedcalendar/hidden) { get; set; } | ما إذا كان التقويم مخفيًا من القائمة. الافتراضي هو False . |
| virtual [Id](../../aspose.email.clients.google/basedataobject/id) { get; set; } | معرف المورد . |
| virtual [Kind](../../aspose.email.clients.google/basedataobject/kind) { get; } | نوع المورد |
| virtual [Location](../../aspose.email.clients.google/calendar/location) { get; set; } | الموقع الجغرافي للتقويم كنص حر. |
| virtual [NotificationSettings](../../aspose.email.clients.google/extendedcalendar/notificationsettings) { get; set; } | الإشعارات التي يتلقاها المستخدم المصادق عليه لهذا التقويم. |
| virtual [Primary](../../aspose.email.clients.google/extendedcalendar/primary) { get; set; } | ما إذا كان التقويم هو التقويم الأساسي للمستخدم المصادق عليه. يقرأ فقط. الافتراضي هو False . |
| virtual [Selected](../../aspose.email.clients.google/extendedcalendar/selected) { get; set; } | ما إذا كان محتوى التقويم يظهر في واجهة مستخدم التقويم. الافتراضي هو False . |
| virtual [Summary](../../aspose.email.clients.google/calendar/summary) { get; set; } | عنوان التقويم . |
| virtual [SummaryOverride](../../aspose.email.clients.google/extendedcalendar/summaryoverride) { get; set; } | الملخص الذي قام المستخدم المصادق بتعيينه لهذا التقويم. |
| virtual [TimeZone](../../aspose.email.clients.google/calendar/timezone) { get; set; } | المنطقة الزمنية للتقويم. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [ToString](../../aspose.email.clients.google/extendedcalendar/tostring)() | إرجاع سلسلة تمثل مثيل الكائن. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [ExtendedCalendarKind](../../aspose.email.clients.google/extendedcalendar/extendedcalendarkind) | نوع المورد "تقويم # calendarListEntry" . |
| const [ListKind](../../aspose.email.clients.google/extendedcalendar/listkind) | نوع قائمة الموارد "التقويم # قائمة التقويم" . |

### أنظر أيضا

* class [Calendar](../calendar)
* مساحة الاسم [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
