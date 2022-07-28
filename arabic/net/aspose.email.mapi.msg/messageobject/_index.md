---
title: MessageObject
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل كائن رسالة Outlook. حدود التقييم يتم قراءة مرفق واحد فقط ومستلم واحد عند تحميل الرسالة  وستتم إضافة العلامة المائية عند حفظ الرسالة.
type: docs
weight: 18820
url: /ar/net/aspose.email.mapi.msg/messageobject/
---
## MessageObject class

يمثل كائن رسالة Outlook. حدود التقييم: يتم قراءة مرفق واحد فقط ومستلم واحد عند تحميل الرسالة ، وستتم إضافة العلامة المائية عند حفظ الرسالة.

```csharp
public sealed class MessageObject : IMessageObjectPropertyContainer
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MessageObject](messageobject#constructor)(Stream, MessageObjectLoadFormat) | يقوم بتهيئة مثيل جديد لملف[`MessageObject`](../messageobject) فئة . |
| [MessageObject](messageobject#constructor_1)(string, MessageObjectLoadFormat) | يقوم بتهيئة مثيل جديد لملف[`MessageObject`](../messageobject) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Attachments](../../aspose.email.mapi.msg/messageobject/attachments) { get; } | يحصل على مرفقات ملف[`MessageObject`](../messageobject) . |
| [Codepage](../../aspose.email.mapi.msg/messageobject/codepage) { get; } | الحصول على مخطط الشفرة المستخدم لترميز / فك تشفير خصائص السلسلة في الحالةPT_STRING8 اكتب لهم يستخدم. |
| [Properties](../../aspose.email.mapi.msg/messageobject/properties) { get; } | يحصل على خصائص ملف[`MessageObject`](../messageobject) . |
| [Recipients](../../aspose.email.mapi.msg/messageobject/recipients) { get; } | يحصل على مستلمي ملف[`MessageObject`](../messageobject) . |

## طُرق

| اسم | وصف |
| --- | --- |
| [GetIdForNamedProperty](../../aspose.email.mapi.msg/messageobject/getidfornamedproperty)() | الحصول على المعرف الذي سيتم استخدامه للخاصية المسماة ، الخصائص المسماة هي خصائص خاصة ويجب أن تكون معرّفاتها في النطاق [0x8000،0xfffe] بدءًا من 0x8000 بالتسلسل . استخدم هذه الطريقة للعثور على المعرف المتاح لأنه قد يكون من الصعب احسبها بنفسك. |
| [Save](../../aspose.email.mapi.msg/messageobject/save#save)(Stream, MessageObjectSaveFormat) | يحفظ كائن الرسالة الحالية إلى التدفق المحدد. |
| [Save](../../aspose.email.mapi.msg/messageobject/save#save_1)(string, MessageObjectSaveFormat) | يحفظ كائن الرسالة الحالية في الملف المحدد. |

### أنظر أيضا

* interface [IMessageObjectPropertyContainer](../imessageobjectpropertycontainer)
* مساحة الاسم [Aspose.Email.Mapi.Msg](../../aspose.email.mapi.msg)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->