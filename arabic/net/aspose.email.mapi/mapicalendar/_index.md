---
title: MapiCalendar
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل كائن تقويم mapi
type: docs
weight: 17910
url: /ar/net/aspose.email.mapi/mapicalendar/
---
## MapiCalendar class

يمثل كائن تقويم mapi

```csharp
public sealed class MapiCalendar : MapiMessageItemBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MapiCalendar](mapicalendar#constructor)() | يقوم بتهيئة مثيل جديد لملف[`MapiCalendar`](../mapicalendar) فئة |
| [MapiCalendar](mapicalendar#constructor_1)(string, string, string, DateTime, DateTime) | يقوم بتهيئة مثيل جديد لملف[`MapiCalendar`](../mapicalendar) فئة . |
| [MapiCalendar](mapicalendar#constructor_2)(string, string, string, DateTime, DateTime, MapiElectronicAddress, MapiRecipientCollection) | يقوم بتهيئة مثيل جديد لملف[`MapiCalendar`](../mapicalendar) فئة . |
| [MapiCalendar](mapicalendar#constructor_3)(string, string, string, DateTime, DateTime, string, MapiRecipientCollection) | يقوم بتهيئة مثيل جديد لملف[`MapiCalendar`](../mapicalendar) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AppointmentCounterProposal](../../aspose.email.mapi/mapicalendar/appointmentcounterproposal) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان كائن استجابة الاجتماع هو اقتراح مضاد. |
| [Attachments](../../aspose.email.mapi/mapicalendar/attachments) { get; } | الحصول على مجموعة المرفقات. |
| [Attendees](../../aspose.email.mapi/mapicalendar/attendees) { get; set; } | الحصول على أو تعيين الحاضرين |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | يحتوي على معلومات الفواتير المرتبطة بأحد العناصر . |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | يحصل على نص الرسالة. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | يحصل على ملف[`BodyRtf`](../mapimessageitembase/bodyrtf) من الرسالة محولة إلى HTML ، إن وجدت ، وإلا فسيتم تحويلها إلى سلسلة فارغة. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | الحصول على نص الرسالة المنسقة بتنسيق RTF أو تعيينه. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | يحصل على نوع الجسم. |
| [BusyStatus](../../aspose.email.mapi/mapicalendar/busystatus) { get; set; } | الحصول على أو تعيين حالة الانشغال |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | يحتوي على كلمات أساسية أو فئات لكائن الرسالة. |
| [ClientIntent](../../aspose.email.mapi/mapicalendar/clientintent) { get; set; } | الحصول على أو تعيين الإجراءات التي اتخذها المستخدم على كائن الاجتماع هذا. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | الحصول على صفحة الشفرة . |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | يحتوي على أسماء الشركات المرتبطة بأحد العناصر . |
| [EndDate](../../aspose.email.mapi/mapicalendar/enddate) { get; set; } | الحصول على أو تحديد تاريخ الانتهاء ووقت الحدث. إذا لم يتم تعيين التاريخ ، القيمة الافتراضية لـDateTime تم إرجاعه . |
| [EndDateTimeZone](../../aspose.email.mapi/mapicalendar/enddatetimezone) { get; set; } | الحصول على أو تعيين معلومات المنطقة الزمنية التي تشير إلى المنطقة الزمنية لخاصية EndDate |
| [IsAllDay](../../aspose.email.mapi/mapicalendar/isallday) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان الحدث عبارة عن حدث طوال اليوم |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | معرّف العنصر يستخدم مع server |
| [KeyWords](../../aspose.email.mapi/mapicalendar/keywords) { get; set; } | الحصول على أو تعيين فئات كائن التقويم |
| [Location](../../aspose.email.mapi/mapicalendar/location) { get; set; } | الحصول على أو تحديد موقع الحدث |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | يحصل على سلسلة حساسة لحالة الأحرف تحدد فئة الرسالة المحددة بواسطة المرسل ، مثل IPM.Note. تحدد فئة الرسالة نوع الرسالة أو الغرض منها أو محتواها. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | يحتوي على معلومات المسافة المقطوعة بالأميال المرتبطة بأحد العناصر. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | الحصول على الخصائص المسماة للرسالة . |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | الحصول على تعيين الخاصية المسماة. |
| [Organizer](../../aspose.email.mapi/mapicalendar/organizer) { get; set; } | الحصول على المنظم أو تعيينه . |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | يحصل على مجموعة الخصائص . |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | يحصل على تدفق الملكية . |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | يحصل على مستلمي الرسالة. |
| [Recurrence](../../aspose.email.mapi/mapicalendar/recurrence) { get; set; } | الحصول على أو تعيين خصائص التكرار |
| [ReminderDelta](../../aspose.email.mapi/mapicalendar/reminderdelta) { get; set; } | الحصول على أو تعيين الفاصل الزمني ، بالدقائق ، بين الوقت الذي يصبح فيه التذكير متأخرًا لأول مرة ووقت بدء كائن التقويم |
| [ReminderFileParameter](../../aspose.email.mapi/mapicalendar/reminderfileparameter) { get; set; } | يحدد المسار الكامل للصوت الذي يجب على العميل تشغيله عندما يصبح التذكير متأخرًا. |
| [ReminderSet](../../aspose.email.mapi/mapicalendar/reminderset) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان قد تم تعيين تذكير على object |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | يحصل على الحساسية . |
| [Sequence](../../aspose.email.mapi/mapicalendar/sequence) { get; set; } | الحصول على أو تحديد رقم التسلسل |
| [StartDate](../../aspose.email.mapi/mapicalendar/startdate) { get; set; } | الحصول على أو تحديد تاريخ البدء والوقت للحدث. إذا لم يتم تعيين التاريخ ، القيمة الافتراضية لـDateTime تم إرجاعه . |
| [StartDateTimeZone](../../aspose.email.mapi/mapicalendar/startdatetimezone) { get; set; } | الحصول على أو تعيين معلومات المنطقة الزمنية التي تشير إلى المنطقة الزمنية لخاصية تاريخ البدء |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | الحصول على أو تحديد موضوع الرسالة. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | الحصول على بادئة موضوع تشير عادةً إلى بعض الإجراءات على رسالة ، مثل "FW:" لإعادة التوجيه. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | يحصل على المخازن الفرعية . |
| [Uid](../../aspose.email.mapi/mapicalendar/uid) { get; set; } | الحصول على المعرف الفريد |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Dispose](../../aspose.email.mapi/mapicalendar/dispose)() | يصدر كافة الموارد . |
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
| [Save](../../aspose.email.mapi/mapicalendar/save#save)(Stream) | حفظ كائن التقويم في الملف بتنسيق iCalendar باستخدام خيارات الحفظ الافتراضية |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_3)(string) | حفظ كائن التقويم في الملف بتنسيق iCalendar باستخدام خيارات الحفظ الافتراضية |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_1)(Stream, AppointmentSaveFormat) | حفظ كائن التقويم في التدفق بالتنسيق المحدد باستخدام خيارات الحفظ الافتراضية |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_2)(Stream, MapiCalendarSaveOptions) | يحفظ التقويم في التدفق باستخدام خيارات الحفظ المحددة |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_4)(string, AppointmentSaveFormat) | حفظ كائن التقويم في الملف بالتنسيق المحدد باستخدام خيارات الحفظ الافتراضية |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_5)(string, MapiCalendarSaveOptions) | حفظ كائن التقويم في الملف بالتنسيق المحدد باستخدام خيارات الحفظ الافتراضية |
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
