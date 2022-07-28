---
title: BodyRtf
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: الحصول على نص الرسالة المنسقة بتنسيق RTF أو تعيينه.
type: docs
weight: 50
url: /ar/net/aspose.email.mapi/mapimessageitembase/bodyrtf/
---
## MapiMessageItemBase.BodyRtf property

الحصول على نص الرسالة المنسقة بتنسيق RTF أو تعيينه.

```csharp
public string BodyRtf { get; set; }
```

### Property_Value

السلسلة التي تمثل نص الرسالة rtf.

### ملاحظات

عند تعيين قيمة ، يتم تحديث قيم PR_RTF_COMPRESSED و PR_RTF_DECOMPRESSES و PR_BODY. يجب أن يكون لقيمة السلسلة التي يتم تعيينها تنسيق RTF. وبالتالي ، إذا كان من الضروري تعيين قيمة بتنسيق HTML ، يجب أن تكون القيمة أولاً مشفرة ضمن RTF ، وفقًا لمواصفات ملحقات RTF. لتعيين محتوى الرسالة الأساسية في تنسيق HTML أو نص عادي بسرعة ، من فضلك ، استخدم طريقة SetBodyContent. عند تعيين قيمة فارغة أو سلسلة فارغة ، يتم تعيين قيم خصائص BodyRtf و Body على قيمة خالية.

### أنظر أيضا

* class [MapiMessageItemBase](../../mapimessageitembase)
* مساحة الاسم [Aspose.Email.Mapi](../../mapimessageitembase)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->