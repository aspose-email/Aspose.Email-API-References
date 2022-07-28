---
title: MapiContact
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل outlook contact information
type: docs
weight: 18190
url: /ar/net/aspose.email.mapi/mapicontact/
---
## MapiContact class

يمثل outlook contact information

```csharp
public sealed class MapiContact : MapiMessageItemBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MapiContact](mapicontact#constructor)() | يقوم بتهيئة مثيل جديد لملف[`MapiContact`](../mapicontact) فئة |
| [MapiContact](mapicontact#constructor_1)(string, string) | يقوم بتهيئة مثيل جديد لملف[`MapiContact`](../mapicontact) فئة . |
| [MapiContact](mapicontact#constructor_2)(string, string, string) | يقوم بتهيئة مثيل جديد لملف[`MapiContact`](../mapicontact) فئة . |
| [MapiContact](mapicontact#constructor_3)(string, string, string, string) | يقوم بتهيئة مثيل جديد لملف[`MapiContact`](../mapicontact) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapicontact/attachments) { get; } | يحصل على المرفقات في جهة الاتصال. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | يحتوي على معلومات الفواتير المرتبطة بأحد العناصر . |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | يحصل على نص الرسالة. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | يحصل على ملف[`BodyRtf`](../mapimessageitembase/bodyrtf) من الرسالة محولة إلى HTML ، إن وجدت ، وإلا فسيتم تحويلها إلى سلسلة فارغة. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | الحصول على نص الرسالة المنسقة بتنسيق RTF أو تعيينه. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | يحصل على نوع الجسم. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | يحتوي على كلمات أساسية أو فئات لكائن الرسالة. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | الحصول على صفحة الشفرة . |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | يحتوي على أسماء الشركات المرتبطة بأحد العناصر . |
| [ElectronicAddresses](../../aspose.email.mapi/mapicontact/electronicaddresses) { get; set; } | حدد خصائص ما يصل إلى ثلاثة عناوين بريد إلكتروني مختلفة وثلاثة عناوين فاكس مختلفة |
| [Events](../../aspose.email.mapi/mapicontact/events) { get; set; } | تحديد الأحداث المرتبطة بجهة اتصال |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | معرّف العنصر يستخدم مع server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | يحصل على سلسلة حساسة لحالة الأحرف تحدد فئة الرسالة المحددة بواسطة المرسل ، مثل IPM.Note. تحدد فئة الرسالة نوع الرسالة أو الغرض منها أو محتواها. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | يحتوي على معلومات المسافة المقطوعة بالأميال المرتبطة بأحد العناصر. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | الحصول على الخصائص المسماة للرسالة . |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | الحصول على تعيين الخاصية المسماة. |
| [NameInfo](../../aspose.email.mapi/mapicontact/nameinfo) { get; set; } | يتم استخدام الخصائص لتحديد اسم للشخص الذي يمثله جهة الاتصال |
| [OtherFields](../../aspose.email.mapi/mapicontact/otherfields) { get; set; } | حدد مجالات الاتصال الأخرى. |
| [PersonalInfo](../../aspose.email.mapi/mapicontact/personalinfo) { get; set; } | حدد معلومات اتصال إضافية أخرى |
| [Photo](../../aspose.email.mapi/mapicontact/photo) { get; set; } | يحتوي على صورة جهة الاتصال[`MapiContactPhoto`](../mapicontactphoto) . |
| [PhysicalAddresses](../../aspose.email.mapi/mapicontact/physicaladdresses) { get; set; } | حدد ثلاثة عناوين فعلية: عنوان المنزل وعنوان العمل وعنوان آخر . يمكن وضع علامة على أحد العناوين على أنه العنوان البريدي |
| [ProfessionalInfo](../../aspose.email.mapi/mapicontact/professionalinfo) { get; set; } | يتم استخدام الخصائص لتخزين تفاصيل احترافية للشخص الذي يمثله جهة الاتصال |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | يحصل على مجموعة الخصائص . |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | يحصل على تدفق الملكية . |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | يحصل على مستلمي الرسالة. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | يحصل على الحساسية . |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | الحصول على أو تحديد موضوع الرسالة. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | الحصول على بادئة موضوع تشير عادةً إلى بعض الإجراءات على رسالة ، مثل "FW:" لإعادة التوجيه. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | يحصل على المخازن الفرعية . |
| [Telephones](../../aspose.email.mapi/mapicontact/telephones) { get; set; } | حدد أرقام الهاتف لجهة الاتصال |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard)(Stream) | يقرأ[`MapiContact`](../mapicontact) من الدفق المحدد الذي يحتوي على vCard. إصدارات vCard المدعومة هي 2.1 و 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_2)(string) | يقرأ[`MapiContact`](../mapicontact) من ملف vCard المحدد file إصدارات vCard المدعومة هي 2.1 و 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_1)(Stream, Encoding) | يقرأ[`MapiContact`](../mapicontact) من الدفق المحدد الذي يحتوي على vCard. إصدارات vCard المدعومة هي 2.1 و 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_3)(string, Encoding) | يقرأ[`MapiContact`](../mapicontact) من ملف vCard المحدد file إصدارات vCard المدعومة هي 2.1 و 3.0 |
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
| [GetUnderlyingMessage](../../aspose.email.mapi/mapicontact/getunderlyingmessage)() | احصل على MapiMessage التي تمثل جهة الاتصال. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | تحديد ما إذا كانت خصائص السلسلة مشفرة بترميز Unicode أم لا. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | يوفر إزالة الخاصية بشكل صحيح من كافة المجموعات. |
| [Save](../../aspose.email.mapi/mapicontact/save#save)(Stream) | يحفظ هذا[`MapiContact`](../mapicontact) في التدفق المحدد بتنسيق vCard . إصدار vCard المدعوم هو 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_3)(string) | يحفظ هذا[`MapiContact`](../mapicontact) إلى ملف vCard مع الخيارات الافتراضية . إصدار vCard المدعوم هو 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_1)(Stream, ContactSaveFormat) | يحفظ هذا[`MapiContact`](../mapicontact) إلى التدفق المحدد بتنسيق باستخدام الخيارات الافتراضية . تنسيق الحفظ المدعوم هو vCard |
| [Save](../../aspose.email.mapi/mapicontact/save#save_2)(Stream, ContactSaveOptions) | يحفظ هذا[`MapiContact`](../mapicontact) إلى التدفق المحدد باستخدام خيارات الحفظ المحددة. خيارات الحفظ المدعومة هي[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| [Save](../../aspose.email.mapi/mapicontact/save#save_4)(string, ContactSaveFormat) | يحفظ هذا[`MapiContact`](../mapicontact)إلى الملف المحدد بتنسيق باستخدام الخيارات الافتراضية . تنسيق الحفظ المدعوم هو vCard. |
| [Save](../../aspose.email.mapi/mapicontact/save#save_5)(string, ContactSaveOptions) | يحفظ هذا[`MapiContact`](../mapicontact) في ملف باستخدام خيارات الحفظ المحددة. خيارات الحفظ المدعومة هي[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| override [SetBodyContent](../../aspose.email.mapi/mapicontact/setbodycontent#setbodycontent)(string, BodyContentType) | يحدد محتوى الجسم. |
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
