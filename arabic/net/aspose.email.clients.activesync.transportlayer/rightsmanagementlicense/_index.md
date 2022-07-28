---
title: RightsManagementLicense
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يحتوي على إعدادات قالب نهج الحقوق للقالب المطبق على رسالة البريد الإلكتروني التي تتم مزامنتها.
type: docs
weight: 1900
url: /ar/net/aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/
---
## RightsManagementLicense class

يحتوي على إعدادات قالب نهج الحقوق للقالب المطبق على رسالة البريد الإلكتروني التي تتم مزامنتها.

```csharp
public class RightsManagementLicense
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [RightsManagementLicense](rightsmanagementlicense)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ContentExpiryDate](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentexpirydate) { get; set; } | يحدد تاريخ انتهاء صلاحية الترخيص. يتم تعيين عنصر ContentExpiryDate على "9999-12-30T23: 59: 59.999Z" إذا لم يتم تعيين تاريخ انتهاء صلاحية ترخيص إدارة الحقوق. |
| [ContentOwner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentowner) { get; set; } | يحدد ما إذا كان يمكن للمستخدم تعديل محتوى البريد الإلكتروني الأصلي عندما يقوم المستخدم بإعادة التوجيه أو الرد أو الرد على جميع رسائل البريد الإلكتروني. القيمة هي TRUE إذا كان يمكن للمستخدم تعديل البريد الإلكتروني ؛ خلافًا لذلك ، FALSE. تتطلب قيمة FALSE أن يستبعد العميل رسالة البريد الإلكتروني الأصلية المُدارة بواسطة الحقوق من طلب SmartForward أو SmartReply. وبالتالي ، لا يُسمح بالردود المضمنة إذا تم تعيين عنصر EditAllowed على FALSE. عند تعيين EditAllowed على FALSE وعدم وجود ReplaceMime في طلب SmartForward أو SmartReply ، سيضيف الخادم رسالة البريد الإلكتروني الأصلية المُدارة بواسطة الحقوق كمرفق بالرسالة الجديدة. على العكس من ذلك ، إذا كان ReplaceMime موجودًا ، فلن يقوم الخادم بإرفاق رسالة البريد الإلكتروني الأصلية المُدارة بواسطة الحقوق كمرفق. |
| [EditAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/editallowed) { get; set; } | يحدد ما إذا كان يمكن للمستخدم تعديل محتوى البريد الإلكتروني الأصلي عندما يقوم المستخدم بإعادة التوجيه أو الرد أو الرد على جميع رسائل البريد الإلكتروني. القيمة هي TRUE إذا كان يمكن للمستخدم تعديل البريد الإلكتروني ؛ خلافًا لذلك ، FALSE. تتطلب قيمة FALSE أن يستبعد العميل رسالة البريد الإلكتروني الأصلية المُدارة بواسطة الحقوق من طلب SmartForward أو SmartReply. وبالتالي ، لا يُسمح بالردود المضمنة إذا تم تعيين عنصر EditAllowed على FALSE. عند تعيين EditAllowed على FALSE وعدم وجود ReplaceMime في طلب SmartForward أو SmartReply ، سيضيف الخادم رسالة البريد الإلكتروني الأصلية المُدارة بواسطة الحقوق كمرفق بالرسالة الجديدة. على العكس ، إذا كان البريد المركب: ReplaceMime موجودًا ، فلن يقوم الخادم بإرفاق رسالة البريد الإلكتروني الأصلية المُدارة بواسطة الحقوق كمرفق. |
| [ExportAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/exportallowed) { get; set; } | يحدد ما إذا كان يمكن للمستخدم إزالة حماية IRM على رسالة البريد الإلكتروني. القيمة هي TRUE إذا كان بإمكان المستخدم إزالة حماية IRM عندما يقوم المستخدم بإعادة التوجيه أو الرد أو الرد على جميع رسائل البريد الإلكتروني ؛ وإلا ، FALSE. إذا تمت إعادة توجيه رسالة بريد إلكتروني مُدارة بواسطة الحقوق أو الرد عليها باستخدام الأمر SmartForward أو SmartReply ، يتم تقييم الشروط التالية: - يحتوي قالب نهج الحقوق الأصلي على عنصر ExportAllowed المعين على TRUE - معرف القالب على الجديد تم تعيين الرسالة إلى القالب "بلا قيود" (قيمة TemplateID "00000000-0000-0000-0000-000000000000") إذا تحققت الحالتان ، فستتم إزالة حماية IRM من الرسالة الصادرة. تحتفظ الرسالة الأصلية بحماية IRM الخاصة بها. |
| [ExtractAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/extractallowed) { get; set; } | تحديد ما إذا كان يمكن للمستخدم نسخ المحتوى من رسالة البريد الإلكتروني. القيمة هي TRUE إذا كان من الممكن قص محتوى رسالة البريد الإلكتروني أو نسخه أو التقاط محتوى للشاشة ؛ وإلا ، FALSE. |
| [ForwardAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/forwardallowed) { get; set; } | تحديد ما إذا كان يمكن للمستخدم إعادة توجيه رسالة البريد الإلكتروني. القيمة هي TRUE إذا كان بإمكان المستخدم إعادة توجيه رسالة البريد الإلكتروني ؛ وإلا ، FALSE. |
| [ModifyRecipientsAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/modifyrecipientsallowed) { get; set; } | يحدد ما إذا كان يمكن للمستخدم تعديل قائمة المستلمين عند إعادة توجيه المستخدم أو الرد على رسالة البريد الإلكتروني. القيمة هي TRUE إذا كان بإمكان المستخدم تعديل قائمة المستلمين (1) ؛ وإلا ، FALSE. |
| [Owner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/owner) { get; set; } | تحديد ما إذا كان المستخدم هو مالك رسالة البريد الإلكتروني. القيمة هي TRUE إذا كان المستخدم هو مالك رسالة البريد الإلكتروني ؛ خلاف ذلك ، خطأ. تشير القيمة TRUE إلى أن المستخدم الذي تمت مصادقته لديه حقوق مالك لهذه الرسالة. يُستخدم هذا العنصر لأغراض عرض المعلومات فقط. يتم استخدام العناصر المسموح بها (EditAllowed ، ReplyAllowed ، إلخ.) لتقييم ما إذا كان إجراء معين مسموحًا به أم مقيدًا. |
| [PrintAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/printallowed) { get; set; } | تحديد ما إذا كان يمكن للمستخدم طباعة البريد الإلكتروني. لا يشير هذا العنصر إلى دعم العميل لطباعة رسالة بريد إلكتروني ؛ يحدد فقط ما إذا كان يمكن طباعة رسالة البريد الإلكتروني إذا كان العميل يدعم الطباعة. القيمة هي TRUE إذا كان يمكن للمستخدم طباعة البريد الإلكتروني ؛ وإلا ، FALSE. |
| [ProgrammaticAccessAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/programmaticaccessallowed) { get; set; } | تحديد ما إذا كان يمكن الوصول إلى محتويات رسالة البريد الإلكتروني برمجيًا بواسطة تطبيقات الطرف الثالث. القيمة هي TRUE إذا كان بإمكان تطبيقات الطرف الثالث الوصول إلى محتوى رسالة البريد الإلكتروني برمجيًا ؛ خلاف ذلك ، خطأ. تشير قيمة TRUE إلى ما إذا كان المحتوى المحمي يمكن الوصول إليه بواسطة تطبيقات أخرى. يتكون المحتوى المحمي من نص الرسالة والمرفقات. |
| [ReplyAllAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallallowed) { get; set; } | تحديد ما إذا كان يمكن للمستخدم الرد على كافة مستلمي رسالة البريد الإلكتروني الأصلية (1). القيمة هي TRUE إذا كان بإمكان المستخدم الرد على كافة مستلمي رسالة البريد الإلكتروني ؛ وإلا ، FALSE. |
| [ReplyAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallowed) { get; set; } | تحديد ما إذا كان يُسمح للمستخدم بالرد على رسالة البريد الإلكتروني. القيمة هي TRUE إذا كان بإمكان المستخدم الرد على رسالة البريد الإلكتروني ؛ وإلا ، FALSE. |
| [TemplateDescription](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatedescription) { get; set; } | يحتوي على وصف لقالب نهج الحقوق الذي يمثله عنصر RightsManagementLicense الأصل. يتم استخدام هذا العنصر لأغراض العرض التقديمي المعلوماتي فقط. الحد الأقصى لطول عنصر TemplateDescription هو 10240 حرفًا . |
| [TemplateID](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templateid) { get; set; } | يحتوي على سلسلة تحدد قالب نهج الحقوق الذي يمثله عنصر RightsManagementLicense الأصل. |
| [TemplateName](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatename) { get; set; } | يحدد اسم قالب نهج الحقوق الذي يمثله عنصر RightsManagementLicense الأصل. يتم استخدام هذا العنصر لأغراض العرض التقديمي المعلوماتي فقط. الحد الأقصى لطول عنصر TemplateName هو 256 حرفًا. |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
