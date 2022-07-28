---
title: MapiDistributionList
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل كائن قائمة التوزيع الشخصية.
type: docs
weight: 18360
url: /ar/net/aspose.email.mapi/mapidistributionlist/
---
## MapiDistributionList class

يمثل كائن قائمة التوزيع الشخصية.

```csharp
public sealed class MapiDistributionList : MapiMessageItemBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MapiDistributionList](mapidistributionlist#constructor)() | يقوم بتهيئة مثيل جديد لملف[`MapiDistributionList`](../mapidistributionlist) فئة . |
| [MapiDistributionList](mapidistributionlist#constructor_1)(string, MapiDistributionListMemberCollection) | يقوم بتهيئة مثيل جديد لملف[`MapiDistributionList`](../mapidistributionlist) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | يحصل على المرفقات في الرسالة . |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | يحتوي على معلومات الفواتير المرتبطة بأحد العناصر . |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | يحصل على نص الرسالة. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | يحصل على ملف[`BodyRtf`](../mapimessageitembase/bodyrtf) من الرسالة محولة إلى HTML ، إن وجدت ، وإلا فسيتم تحويلها إلى سلسلة فارغة. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | الحصول على نص الرسالة المنسقة بتنسيق RTF أو تعيينه. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | يحصل على نوع الجسم. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | يحتوي على كلمات أساسية أو فئات لكائن الرسالة. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | الحصول على صفحة الشفرة . |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | يحتوي على أسماء الشركات المرتبطة بأحد العناصر . |
| [DisplayName](../../aspose.email.mapi/mapidistributionlist/displayname) { get; set; } | الحصول على أو تعيين الاسم المرئي للمستخدم لقائمة التوزيع الشخصية. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | معرّف العنصر يستخدم مع server |
| [Members](../../aspose.email.mapi/mapidistributionlist/members) { get; } | الحصول على قائمة أعضاء قائمة التوزيع الشخصية. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | يحصل على سلسلة حساسة لحالة الأحرف تحدد فئة الرسالة المحددة بواسطة المرسل ، مثل IPM.Note. تحدد فئة الرسالة نوع الرسالة أو الغرض منها أو محتواها. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | يحتوي على معلومات المسافة المقطوعة بالأميال المرتبطة بأحد العناصر. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | الحصول على الخصائص المسماة للرسالة . |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | الحصول على تعيين الخاصية المسماة. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | يحصل على مجموعة الخصائص . |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | يحصل على تدفق الملكية . |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | يحصل على مستلمي الرسالة. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | يحصل على الحساسية . |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | الحصول على أو تحديد موضوع الرسالة. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | الحصول على بادئة موضوع تشير عادةً إلى بعض الإجراءات على رسالة ، مثل "FW:" لإعادة التوجيه. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | يحصل على المخازن الفرعية . |

## طُرق

| اسم | وصف |
| --- | --- |
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
| [Save](../../aspose.email.mapi/mapidistributionlist/save#save)(Stream) | يحفظ الدفق المحدد. |
| [Save](../../aspose.email.mapi/mapidistributionlist/save#save_1)(string) | يحفظ اسم الملف المحدد. |
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
