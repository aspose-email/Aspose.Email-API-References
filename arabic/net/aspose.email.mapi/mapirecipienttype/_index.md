---
title: MapiRecipientType
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: تمثل خاصية PR_RECIPIENT_TYPE التي تحتوي على نوع المستلم لمستلم الرسالة.
type: docs
weight: 18660
url: /ar/net/aspose.email.mapi/mapirecipienttype/
---
## MapiRecipientType enumeration

تمثل خاصية PR_RECIPIENT_TYPE التي تحتوي على نوع المستلم لمستلم الرسالة.

```csharp
public enum MapiRecipientType
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| MAPI_BCC | `3` | المستلم هو مستلم نسخة كربونية غير مرئية (BCC). المستلمون الأساسيون والنسخة الكربونية غير مدركين لوجود مستلمي نسخة BCC. |
| MAPI_CC | `2` | المستلم هو مستلم نسخة كربونية (CC) ، مستلم يتلقى رسالة بالإضافة إلى المستلمين الأساسيين. |
| MAPI_P1 | `268435456` | لم يستلم المستلم الرسالة في المحاولة السابقة بنجاح. هذا إعادة إرسال سابق. |
| MAPI_SUBMITTED | `-2147483648` | لقد تلقى المستلم الرسالة بالفعل ولا يحتاج إلى استلامها مرة أخرى. هذا إعادة إرسال سابق. تم تعيين هذه العلامة بالاقتران مع قيم MAPI_TO و MAPI_CC و MAPI_BCC. |
| MAPI_TO | `1` | المستلم هو مستلم أساسي (إلى). يطلب من العملاء التعامل مع المستلمين الأساسيين ؛ جميع الأنواع الأخرى اختيارية. |
| Unknown | `-1` | غير معروف . |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Mapi](../../aspose.email.mapi)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->