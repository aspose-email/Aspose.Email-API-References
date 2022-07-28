---
title: MapiAttachment
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل المرفق في رسالة البريد الإلكتروني.
type: docs
weight: 17880
url: /ar/net/aspose.email.mapi/mapiattachment/
---
## MapiAttachment class

يمثل المرفق في رسالة البريد الإلكتروني.

```csharp
public class MapiAttachment : MapiPropertyContainer
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [BinaryData](../../aspose.email.mapi/mapiattachment/binarydata) { get; set; } | الحصول على أو تعيين بيانات المرفقات الثنائية. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | الحصول على صفحة الشفرة . |
| [Content](../../aspose.email.mapi/mapiattachment/content) { get; } | الحصول على المحتوى. |
| [DisplayName](../../aspose.email.mapi/mapiattachment/displayname) { get; } | الحصول على اسم عرض كائن أول في مرفق. |
| [Extension](../../aspose.email.mapi/mapiattachment/extension) { get; } | يحصل على ملحق اسم الملف الذي يشير إلى نوع المستند المرفق. |
| [FileName](../../aspose.email.mapi/mapiattachment/filename) { get; } | الحصول على اسم الملف الأساسي وامتداده ، باستثناء المسار. |
| virtual [ItemId](../../aspose.email.mapi/mapiattachment/itemid) { get; } | معرّف العنصر يستخدم مع server |
| [LongFileName](../../aspose.email.mapi/mapiattachment/longfilename) { get; } | الحصول على اسم الملف الطويل وامتداده ، باستثناء المسار. |
| [MimeTag](../../aspose.email.mapi/mapiattachment/mimetag) { get; } | الحصول على معلومات التنسيق حول مرفق ملحقات بريد الإنترنت متعدد الأغراض (MIME) . |
| [NamedProperties](../../aspose.email.mapi/mapiattachment/namedproperties) { get; } | الحصول على الخصائص المسماة للرسالة . |
| [ObjectData](../../aspose.email.mapi/mapiattachment/objectdata) { get; } | الحصول على كائن مرفق يتم الوصول إليه عادةً من خلال واجهة OLE IStorage. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | يحصل على مجموعة الخصائص . |
| [PropertyStream](../../aspose.email.mapi/mapiattachment/propertystream) { get; } | يحصل على تدفق الملكية . |
| [SubStorages](../../aspose.email.mapi/mapiattachment/substorages) { get; } | يحصل على المخازن الفرعية . |

## طُرق

| اسم | وصف |
| --- | --- |
| override [GetProperty](../../aspose.email.mapi/mapiattachment/getproperty)(PropertyDescriptor) | يحصل على خاصية MAPI بواسطة واصف الخاصية. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | يحصل على قيمة الخاصية المحددة بواسطة العلامة كنوع منطقي. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | يحصل على قيمة سلسلة الخاصية المحددة بواسطة العلامة. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | يحصل على قيمة الخاصية المحددة بواسطة العلامة كنوع التاريخ والوقت. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | يحصل على قيمة int32 للخاصية المحددة بواسطة العلامة. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | الحصول على قيمة الخاصية المحددة بواسطة العلامة كنوع طويل (int64) . |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | الحصول على قيمة الخاصية المحددة بواسطة العلامة كنوع قصير. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | يحصل على قيمة سلسلة الخاصية المحددة بواسطة العلامة. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | يحصل على قيمة سلسلة الخاصية المحددة بواسطة العلامة. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | تحديد ما إذا كانت خصائص السلسلة مشفرة بترميز Unicode أم لا. |
| [RemoveProperty](../../aspose.email.mapi/mapiattachment/removeproperty)(long) | يوفر إزالة الخاصية بشكل صحيح من كافة المجموعات. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save)(Stream) | حفظ محتوى المرفقات. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save_1)(string) | حفظ محتوى المرفقات. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty)(MapiProperty) | يعين الخاصية . |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty_1)(PropertyDescriptor, object) | تعيين خاصية MAPI . |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | حاول الحصول على بيانات الخاصية باستخدام مفتاح العلامة المحدد. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | الحصول على قيمة الخاصية المحددة كنوع التاريخ والوقت. تشير القيمة المرجعة إلى نجاح العملية. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | الحصول على قيمة الخاصية المحددة كنوع Int32. تشير القيمة المرجعة إلى نجاح العملية. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | الحصول على قيمة الخاصية المحددة كنوع طويل. تشير القيمة المرجعة إلى نجاح العملية. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | حاول الحصول على بيانات خاصية كسلسلة بعلامة محددة. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | حاول الحصول على بيانات خاصية كسلسلة ذات علامة وصفحة رموز محددين . |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | يحصل على قيمة الخاصية المحددة كنوع سلسلة. تشير القيمة المرجعة إلى نجاح العملية. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | يحصل على قيمة الخاصية المحددة كنوع سلسلة. تشير القيمة المرجعة إلى نجاح العملية. |

### أنظر أيضا

* class [MapiPropertyContainer](../mapipropertycontainer)
* مساحة الاسم [Aspose.Email.Mapi](../../aspose.email.mapi)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
