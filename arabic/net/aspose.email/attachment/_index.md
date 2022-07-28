---
title: Attachment
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل مرفق بريد إلكتروني.
type: docs
weight: 350
url: /ar/net/aspose.email/attachment/
---
## Attachment class

يمثل مرفق بريد إلكتروني.

```csharp
public class Attachment : AttachmentBase, IAttachment, IPreferredTextEncodingProvider
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Attachment](attachment#constructor_3)(string) | يقوم بتهيئة مثيل جديد لملف[`Attachment`](../attachment) فئة . |
| [Attachment](attachment#constructor)(Stream, ContentType) | يقوم بتهيئة مثيل جديد لملف[`Attachment`](../attachment) فئة . |
| [Attachment](attachment#constructor_1)(Stream, string) | يقوم بتهيئة مثيل جديد لملف[`Attachment`](../attachment) فئة . |
| [Attachment](attachment#constructor_4)(string, ContentType) | يقوم بتهيئة مثيل جديد لملف[`Attachment`](../attachment) فئة . |
| [Attachment](attachment#constructor_5)(string, string) | يقوم بتهيئة مثيل جديد لملف[`Attachment`](../attachment) فئة . |
| [Attachment](attachment#constructor_2)(Stream, string, string) | يقوم بتهيئة مثيل جديد لملف[`Attachment`](../attachment) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ContentDisposition](../../aspose.email/attachment/contentdisposition) { get; } | الحصول على رأس ترتيب المحتوى |
| [ContentId](../../aspose.email/attachmentbase/contentid) { get; set; } | الحصول على معرف المحتوى أو تعيينه. |
| [ContentStream](../../aspose.email/attachmentbase/contentstream) { get; set; } | الحصول على دفق المحتوى أو تعيينه. |
| [ContentType](../../aspose.email/attachmentbase/contenttype) { get; set; } | الحصول على أو تحديد نوع المحتوى. |
| virtual [Headers](../../aspose.email/attachmentbase/headers) { get; } | الحصول على مجموعة رؤوس المرفقات. |
| [IsEmbeddedMessage](../../aspose.email/attachment/isembeddedmessage) { get; } | يحصل على قيمة تشير إلى ما إذا كان المرفق رسالة مضمنة. |
| [IsUri](../../aspose.email/attachment/isuri) { get; } | يحصل على قيمة تشير إلى ما إذا كان المرفق هو مرفق URI. |
| [Name](../../aspose.email/attachment/name) { get; set; } | الحصول على أو تعيين اسم المرفق |
| [NameEncoding](../../aspose.email/attachment/nameencoding) { get; set; } | الحصول على أو تعيين ترميز لاسم المرفق |
| [PreferredTextEncoding](../../aspose.email/attachment/preferredtextencoding) { get; set; } | الحصول على أو تعيين ترميز النص المفضل |
| [TransferEncoding](../../aspose.email/attachmentbase/transferencoding) { get; set; } | الحصول على ترميز النقل أو تعيينه. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring#createattachmentfromstring)(string, ContentType) | إنشاء المرفق من السلسلة . |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring#createattachmentfromstring_1)(string, string) | إنشاء المرفق من السلسلة . |
| static [CreateAttachmentFromString](../../aspose.email/attachment/createattachmentfromstring#createattachmentfromstring_2)(string, string, Encoding, string) | إنشاء المرفق من السلسلة . |
| [Dispose](../../aspose.email/attachmentbase/dispose)() | تنفيذ مهام محددة بواسطة التطبيق مرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| virtual [Save](../../aspose.email/attachmentbase/save)(Stream) | يحفظ الدفق المحدد. |
| virtual [Save](../../aspose.email/attachmentbase/save)(string) | يحفظ اسم الملف المحدد. |

### أنظر أيضا

* class [AttachmentBase](../attachmentbase)
* interface [IAttachment](../iattachment)
* interface [IPreferredTextEncodingProvider](../ipreferredtextencodingprovider)
* مساحة الاسم [Aspose.Email](../../aspose.email)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->