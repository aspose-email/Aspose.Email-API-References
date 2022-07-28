---
title: MapiRecipient
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل معلومات المستلم في رسالة Microsoft Outlook.
type: docs
weight: 18620
url: /ar/net/aspose.email.mapi/mapirecipient/
---
## MapiRecipient class

يمثل معلومات المستلم في رسالة Microsoft Outlook.

```csharp
public class MapiRecipient : MapiPropertyContainer
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AddressType](../../aspose.email.mapi/mapirecipient/addresstype) { get; } | الحصول على نوع عنوان مستلم الرسالة أو مرسلها. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | الحصول على صفحة الشفرة . |
| [Content](../../aspose.email.mapi/mapirecipient/content) { get; } | الحصول على المحتوى. |
| [DisplayName](../../aspose.email.mapi/mapirecipient/displayname) { get; set; } | الحصول على أو تحديد اسم عرض الرسالة المستلم أو المرسل. |
| [EmailAddress](../../aspose.email.mapi/mapirecipient/emailaddress) { get; set; } | الحصول على أو تعيين عنوان البريد الإلكتروني لمستلم أو مرسل الرسالة . |
| [NamedProperties](../../aspose.email.mapi/mapirecipient/namedproperties) { get; } | الحصول على الخصائص المسماة للرسالة . |
| [OrganizationEmailAddress](../../aspose.email.mapi/mapirecipient/organizationemailaddress) { get; } | يحصل على عنوان البريد الإلكتروني للمؤسسة. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | يحصل على مجموعة الخصائص . |
| [PropertyStream](../../aspose.email.mapi/mapirecipient/propertystream) { get; } | يحصل على تدفق الملكية . |
| [RecipientClass](../../aspose.email.mapi/mapirecipient/recipientclass) { get; } | يحصل على نوع المستلم . |
| [RecipientTrackStatus](../../aspose.email.mapi/mapirecipient/recipienttrackstatus) { get; set; } | حالة استجابة المستلم لطلب الاجتماع. |
| [RecipientType](../../aspose.email.mapi/mapirecipient/recipienttype) { get; } | يحصل على نوع المستلم أو المرسل. |
| [SubStorages](../../aspose.email.mapi/mapirecipient/substorages) { get; } | يحصل على المخازن الفرعية . |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [GetProperty](../../aspose.email.mapi/mapipropertycontainer/getproperty)(PropertyDescriptor) | يحصل على خاصية MAPI بواسطة واصف الخاصية. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | يحصل على قيمة الخاصية المحددة بواسطة العلامة كنوع منطقي. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | يحصل على قيمة سلسلة الخاصية المحددة بواسطة العلامة. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | يحصل على قيمة الخاصية المحددة بواسطة العلامة كنوع التاريخ والوقت. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | يحصل على قيمة int32 للخاصية المحددة بواسطة العلامة. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | الحصول على قيمة الخاصية المحددة بواسطة العلامة كنوع طويل (int64) . |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | الحصول على قيمة الخاصية المحددة بواسطة العلامة كنوع قصير. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | يحصل على قيمة سلسلة الخاصية المحددة بواسطة العلامة. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | يحصل على قيمة سلسلة الخاصية المحددة بواسطة العلامة. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | تحديد ما إذا كانت خصائص السلسلة مشفرة بترميز Unicode أم لا. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | يعين الخاصية . |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(PropertyDescriptor, object) | تعيين خاصية MAPI . |
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
