---
title: MapiTask
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل كائن مهمة Outlook.
type: docs
weight: 18670
url: /ar/net/aspose.email.mapi/mapitask/
---
## MapiTask class

يمثل كائن مهمة Outlook.

```csharp
public class MapiTask : MapiMessageItemBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MapiTask](mapitask#constructor)() | يقوم بتهيئة مثيل جديد لملف[`MapiTask`](../mapitask) فئة . |
| [MapiTask](mapitask#constructor_1)(string, string, DateTime, DateTime) | يقوم بتهيئة مثيل جديد لملف[`MapiTask`](../mapitask) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AcceptanceState](../../aspose.email.mapi/mapitask/acceptancestate) { get; set; } | الحصول على حالة قبول المهمة أو تعيينها. |
| [ActualEffort](../../aspose.email.mapi/mapitask/actualeffort) { get; set; } | الحصول على أو تعيين عدد الدقائق التي التي قضاها المستخدم بالفعل في العمل على مهمة. |
| [Attachments](../../aspose.email.mapi/mapitask/attachments) { get; } | الحصول على مجموعة المرفقات. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | يحتوي على معلومات الفواتير المرتبطة بأحد العناصر . |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | يحصل على نص الرسالة. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | يحصل على ملف[`BodyRtf`](../mapimessageitembase/bodyrtf) من الرسالة محولة إلى HTML ، إن وجدت ، وإلا فسيتم تحويلها إلى سلسلة فارغة. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | الحصول على نص الرسالة المنسقة بتنسيق RTF أو تعيينه. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | يحصل على نوع الجسم. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | يحتوي على كلمات أساسية أو فئات لكائن الرسالة. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | الحصول على صفحة الشفرة . |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | يحتوي على أسماء الشركات المرتبطة بأحد العناصر . |
| [DateCompleted](../../aspose.email.mapi/mapitask/datecompleted) { get; set; } | الحصول على أو تحديد التاريخ عندما أكمل المستخدم العمل في المهمة. |
| [DueDate](../../aspose.email.mapi/mapitask/duedate) { get; set; } | الحصول على أو تحديد التاريخ الذي يتوقع المستخدم بحلوله أن يكتمل العمل في المهمة . |
| [EstimatedEffort](../../aspose.email.mapi/mapitask/estimatedeffort) { get; set; } | الحصول على أو تعيين عدد الدقائق التي يتوقعها المستخدم للعمل في مهمة . |
| [Flags](../../aspose.email.mapi/mapitask/flags) { get; } | يحصل على إشارات إشارة كائن المهمة. |
| [History](../../aspose.email.mapi/mapitask/history) { get; set; } | الحصول على أو تعيين نوع التغيير الذي تم إجراؤه مؤخرًا على كائن المهمة. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | معرّف العنصر يستخدم مع server |
| [LastUpdate](../../aspose.email.mapi/mapitask/lastupdate) { get; set; } | الحصول على أو تعيين تاريخ ووقت أحدث تغيير تم إجراؤه على كائن المهمة. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | يحصل على سلسلة حساسة لحالة الأحرف تحدد فئة الرسالة المحددة بواسطة المرسل ، مثل IPM.Note. تحدد فئة الرسالة نوع الرسالة أو الغرض منها أو محتواها. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | يحتوي على معلومات المسافة المقطوعة بالأميال المرتبطة بأحد العناصر. |
| [Mode](../../aspose.email.mapi/mapitask/mode) { get; set; } | الحصول على أو تعيين حالة تعيين كائن المهمة. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | الحصول على الخصائص المسماة للرسالة . |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | الحصول على تعيين الخاصية المسماة. |
| [PercentComplete](../../aspose.email.mapi/mapitask/percentcomplete) { get; set; } | الحصول على أو تعيين التقدم الذي أحرزه المستخدم في المهمة. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | يحصل على مجموعة الخصائص . |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | يحصل على تدفق الملكية . |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | يحصل على مستلمي الرسالة. |
| [Recurrence](../../aspose.email.mapi/mapitask/recurrence) { get; set; } | الحصول على أو تعيين خصائص التكرار. |
| [ReminderFileParameter](../../aspose.email.mapi/mapitask/reminderfileparameter) { get; set; } | يحدد المسار الكامل للصوت الذي يجب على العميل تشغيله عندما يصبح التذكير متأخرًا. |
| [ReminderSet](../../aspose.email.mapi/mapitask/reminderset) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان قد تم تعيين تذكير على object |
| [ReminderTime](../../aspose.email.mapi/mapitask/remindertime) { get; set; } | الحصول على أو ضبط وقت الإشارة الأولية للتذكير |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | يحصل على الحساسية . |
| [StartDate](../../aspose.email.mapi/mapitask/startdate) { get; set; } | الحصول على أو تحديد التاريخ الذي يتوقع فيه المستخدم بدء العمل في المهمة . |
| [State](../../aspose.email.mapi/mapitask/state) { get; set; } | الحصول على التعيين الحالي أو تعيين حالة كائن المهمة. |
| [Status](../../aspose.email.mapi/mapitask/status) { get; set; } | الحصول على أو تعيين حالة تقدم المستخدم في المهمة. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | الحصول على أو تحديد موضوع الرسالة. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | الحصول على بادئة موضوع تشير عادةً إلى بعض الإجراءات على رسالة ، مثل "FW:" لإعادة التوجيه. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | يحصل على المخازن الفرعية . |
| [Users](../../aspose.email.mapi/mapitask/users) { get; set; } | الحصول على معلومات حول مستخدمي المهام أو تعيينها. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo)(Stream) | إنشاء مثيل لـ MapiTask من الدفق المحدد. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_2)(string) | إنشاء مثيل لـ MapiTask من ملف ics المحدد. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_1)(Stream, bool) | إنشاء مثيل لـ MapiTask من الدفق المحدد. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_3)(string, bool) | إنشاء مثيل لـ MapiTask من ملف ics المحدد. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | تنفيذ مهام محددة بواسطة التطبيق مرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | يحصل على خاصية MAPI بواسطة واصف الخاصية. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | يحصل على قيمة الخاصية المحددة بواسطة العلامة كنوع منطقي. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | يحصل على قيمة سلسلة الخاصية المحددة بواسطة العلامة. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | يحصل على قيمة الخاصية المحددة بواسطة العلامة كنوع التاريخ والوقت. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | يحصل على قيمة int32 للخاصية المحددة بواسطة العلامة. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | الحصول على قيمة الخاصية المحددة بواسطة العلامة كنوع طويل (int64) . |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | الحصول على قيمة الخاصية المحددة بواسطة العلامة كنوع قصير. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | يحصل على قيمة سلسلة الخاصية المحددة بواسطة العلامة. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | يحصل على قيمة سلسلة الخاصية المحددة بواسطة العلامة. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | تحديد ما إذا كانت خصائص السلسلة مشفرة بترميز Unicode أم لا. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | يوفر إزالة الخاصية بشكل صحيح من كافة المجموعات. |
| [Save](../../aspose.email.mapi/mapitask/save#save)(Stream, TaskSaveFormat) | يحفظ هذا[`MapiTask`](../mapitask) إلى التدفق المحدد باستخدام التنسيق المحدد. |
| [Save](../../aspose.email.mapi/mapitask/save#save_1)(string, TaskSaveFormat) | يحفظ هذا[`MapiTask`](../mapitask) في ملف باستخدام التنسيق المحدد. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | يحدد محتوى الجسم. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | يحدد محتوى الجسم. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | الحصول على نص الرسالة المنسقة بتنسيق RTF أو تعيينه. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | تعيين أعلام الرسالة . |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | يعين الخاصية . |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | تعيين خاصية MAPI . |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | حاول الحصول على بيانات الخاصية باستخدام مفتاح العلامة المحدد. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | الحصول على قيمة الخاصية المحددة كنوع التاريخ والوقت. تشير القيمة المرجعة إلى نجاح العملية. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | الحصول على قيمة الخاصية المحددة كنوع Int32. تشير القيمة المرجعة إلى نجاح العملية. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | الحصول على قيمة الخاصية المحددة كنوع طويل. تشير القيمة المرجعة إلى نجاح العملية. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | حاول الحصول على بيانات خاصية كسلسلة بعلامة محددة. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | حاول الحصول على بيانات خاصية كسلسلة ذات علامة وصفحة رموز محددين . |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | يحصل على قيمة الخاصية المحددة كنوع سلسلة. تشير القيمة المرجعة إلى نجاح العملية. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | يحصل على قيمة الخاصية المحددة كنوع سلسلة. تشير القيمة المرجعة إلى نجاح العملية. |

### أنظر أيضا

* class [MapiMessageItemBase](../mapimessageitembase)
* مساحة الاسم [Aspose.Email.Mapi](../../aspose.email.mapi)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
