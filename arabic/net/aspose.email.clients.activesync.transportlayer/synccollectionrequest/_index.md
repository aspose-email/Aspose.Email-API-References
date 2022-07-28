---
title: SyncCollectionRequest
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: تحتوي الفئة على أوامر وخيارات تنطبق على مجموعة معينة.
type: docs
weight: 2190
url: /ar/net/aspose.email.clients.activesync.transportlayer/synccollectionrequest/
---
## SyncCollectionRequest class

تحتوي الفئة على أوامر وخيارات تنطبق على مجموعة معينة.

```csharp
public class SyncCollectionRequest
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [SyncCollectionRequest](synccollectionrequest)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/collectionid) { get; set; } | يحدد معرف الخادم للمجلد المراد مزامنته. |
| [Commands](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/commands) { get; set; } | يحتوي على العمليات التي تنطبق على مجموعة. العمليات المتاحة هي إضافة وحذف وتغيير وجلب و SoftDelete. |
| [ConversationMode](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/conversationmode) { get; set; } | يحدد ما إذا كان سيتم تضمين العناصر المضمنة في طريقة المحادثة ضمن نتائج استجابة المزامنة. ومع ذلك ، على الرغم من أنه لن يتم استرداد نص رسائل البريد الإلكتروني خارج عامل التصفية المستند إلى الوقت ، سيتم استرداد معاينات النص إذا تم طلب المعاينات. يؤدي تعيين قيمة عنصر ConversationMode إلى FALSE في طلب المزامنة إلى مزامنة العناصر التي تفي بمعايير قيمة عنصر FilterType (القسم 2.2.3.64). يؤدي تعيين قيمة عنصر ConversationMode إلى TRUE إلى توسيع مجموعة النتائج لتشمل أيضًا أي عناصر لها نفس email2: قيم ConversationId ([MS-ASEMAIL] القسم 2.2.2.14) لتلك الموجودة في مجموعة نتائج FilterType. ليس لقيمة عنصر ConversationMode أي تأثير على العناصر خارج المجموعة المحددة بواسطة عنصر CollectionId (القسم 2.2.3.30.5) ؛ تقتصر مجموعة النتائج دائمًا على العناصر الموجودة في المجموعة المحددة. تقوم قيمة عنصر ConversationMode بتحديد أو توسيع النتائج المحددة بواسطة قيمة عنصر FilterType. |
| [DeletesAsMoves](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/deletesasmoves) { get; set; } | الطلبات التي تشير إلى أنه يجب نقل أي عناصر محذوفة إلى مجلد العناصر المحذوفة. إذا أراد العميل حذف العناصر نهائيًا ، فيجب أن يتضمن الطلب عنصر DeletesAsMoves بقيمة FALSE. تشير قيمة TRUE ، وهي القيمة الافتراضية ، إلى أنه تم نقل أي عناصر محذوفة إلى مجلد العناصر المحذوفة. |
| [GetChanges](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/getchanges) { get; set; } | يطلب من الخادم تضمين استجابته أية تغييرات معلقة للمجموعة التي تم تحديدها بواسطة عنصر ServerId (القسم 2.2.3.151.6). إذا كانت هناك تغييرات منذ آخر مزامنة ، فإن استجابة الخادم تتضمن عنصر أوامر (القسم 2.2.3.32) الذي يحتوي على الإضافات والحذف والتغييرات. إذا كان العميل لا يريد إرجاع تغييرات الخادم ، فيجب أن يتضمن الطلب عنصر GetChanges بقيمة FALSE. تشير القيمة TRUE إلى أن العميل يريد إرجاع تغييرات الخادم. يتم افتراض قيمة TRUE عندما يكون عنصر GetChanges فارغًا. عندما لا يكون عنصر GetChanges موجودًا في الطلب ، يعتمد السلوك على قيمة عنصر SyncKey ، كما هو محدد في القسم 2.2.3.166.4. إذا كان عنصر SyncKey له قيمة 0 ، فسيتم التعامل مع الطلب كما لو تم تعيين عنصر GetChanges على FALSE. إذا كان عنصر SyncKey له قيمة غير صفرية ، فسيتم التعامل مع الطلب كما لو تم تعيين عنصر GetChanges إلى TRUE. |
| [Options](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/options) { get; } | يحدد الخيارات التي تتحكم في جوانب معينة لكيفية إجراء المزامنة. العدد المسموح به 0 ... 2. تتيح خيارات التزامن للعميل تحديد إعدادات الاقتطاع والمحتوى. يتم تغليف هذه الإعدادات داخل airsyncbase: عنصر BodyPreference الفرعي ، كما هو محدد في القسم [MS-ASAIRS] 2.2.2.7. نظرًا لأن خيارات المزامنة محددة في مجموعة ، يمكن للعميل تحديد airsyncbase فريد: قيمة عنصر BodyPreference لكل مجموعة تتم مزامنتها . لمزيد من التفاصيل حول airsyncbase: BodyPreference element ، راجع [MS-ASAIRS] القسم 2.2. 2.7. يحافظ الخادم على كتلة الخيارات عبر الطلبات ، باستخدام مفهوم يشار إليه باسم "الخيارات الثابتة". إذا لم يتم تضمين كتلة الخيارات في أحد الطلبات ، فسيتم استخدام كتلة الخيارات السابقة. عندما يحدد العميل خيارات جديدة من خلال تضمين كتلة خيارات في الطلب ، يجب على الخادم استبدال كتلة الخيارات الأصلية بكتلة الخيارات الجديدة. حدد خيارات المزامنة لفئة SMS ، بينما يحدد عنصر الخيارات الآخر خيارات الفئة الافتراضية للمجلد المحدد. |
| [Supported](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/supported) { get; } | يمكن تضمين عناصر فئة جهات الاتصال وفئة التقويم غير المخفية كعناصر فرعية للعنصر المدعوم. للحصول على تفاصيل حول استخدام الخصائص المخفية ، راجع القسم 2.2.3.154. |
| [SyncKey](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/synckey) { get; set; } | يتم استخدام قيمة SyncKey من قبل الخادم لوضع علامة على حالة التزامن للمجموعة. يقوم مفتاح التزامن بقيمة 0 (صفر) بتهيئة حالة المزامنة على الخادم ويسبب مزامنة كاملة للمجموعة. |
| [WindowSize](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/windowsize) { get; set; } | يحدد الحد الأقصى لعدد العناصر التي تم تغييرها في مجموعة أو طلب يجب تضمينه في استجابة المزامنة . إذا لم يتم تعريف WindowSize ، يتصرف الخادم كما لو تم إرسال عنصر WindowSize بقيمة 100. يفسر الخادم القيمة 0 (صفر) والقيم التي تزيد عن 512 على أنها 512. |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
