---
title: SearchResult
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: حاوية لعنصر صندوق بريد فردي مطابق . عندما يكون المخزن الذي يتم البحث فيه هو صندوق البريد - يوجد عنصر نتيجة واحد لكل تطابق موجود في صندوق البريد. إذا لم يتم العثور على مطابقات  فسيكون عنصر النتيجة فارغًا موجودًا في عنصر حاوية المتجر الخاص بالاستجابة XML. - داخل عنصر النتيجة  يحتوي عنصر الخصائص على قائمة بالخصائص المطلوبة لعنصر صندوق البريد. يتم البحث في مكتبة المستندات - النتيجة الأولى التي يتم إرجاعها في استجابة البحث هي بيانات التعريف للمجلد الجذر أو العنصر الذي تشير إليه قيمة LinkId. يمكن للعميل اختيار تجاهل هذا الإدخال إذا لم يتطلب ذلك. - إذا كانت مكتبة المستندات تشير قيمة عنصر LinkId في الطلب إلى مجلد  يتم إرجاع خصائص البيانات الوصفية للمجلد كعنصر أول ومحتويات يتم إرجاع المجلد كنتائج لاحقة. ينطبق النطاق على هذه النتائج بدون اختلاف  على سبيل المثال  سيكون الفهرس 0 دائمًا للعنصر الجذر الذي يشير إليه الارتباط. - داخل عنصر النتيجة  يحتوي عنصر الخصائص على قائمة بالخصائص المطلوبة لعنصر صندوق البريد.
type: docs
weight: 2010
url: /ar/net/aspose.email.clients.activesync.transportlayer/searchresult/
---
## SearchResult class

حاوية لعنصر صندوق بريد فردي مطابق . عندما يكون المخزن الذي يتم البحث فيه هو صندوق البريد: - يوجد عنصر نتيجة واحد لكل تطابق موجود في صندوق البريد. إذا لم يتم العثور على مطابقات ، فسيكون عنصر النتيجة فارغًا موجودًا في عنصر حاوية المتجر الخاص بالاستجابة XML. - داخل عنصر النتيجة ، يحتوي عنصر الخصائص على قائمة بالخصائص المطلوبة لعنصر صندوق البريد. يتم البحث في مكتبة المستندات: - النتيجة الأولى التي يتم إرجاعها في استجابة البحث هي بيانات التعريف للمجلد الجذر أو العنصر الذي تشير إليه قيمة LinkId. يمكن للعميل اختيار تجاهل هذا الإدخال إذا لم يتطلب ذلك. - إذا كانت مكتبة المستندات: تشير قيمة عنصر LinkId في الطلب إلى مجلد ، يتم إرجاع خصائص البيانات الوصفية للمجلد كعنصر أول ومحتويات يتم إرجاع المجلد كنتائج لاحقة. ينطبق النطاق على هذه النتائج بدون اختلاف ؛ على سبيل المثال ، سيكون الفهرس 0 دائمًا للعنصر الجذر الذي يشير إليه الارتباط. - داخل عنصر النتيجة ، يحتوي عنصر الخصائص على قائمة بالخصائص المطلوبة لعنصر صندوق البريد.

```csharp
public class SearchResult
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [SearchResult](searchresult)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/searchresult/class) { get; set; } | يحدد فئة العنصر. |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/searchresult/collectionid) { get; } | يحدد المجلدات التي تم العثور على العنصر فيها. |
| [LongId](../../aspose.email.clients.activesync.transportlayer/searchresult/longid) { get; set; } | يحدد معرفًا فريدًا يتم تعيينه بواسطة الخادم لكل مجموعة نتائج يتم إرجاعها. يمكن استخدام قيمة LongId كمعرف طويل محدد في طلب الأمر ItemOperations أو طلب أمر SmartReply أو طلب أمر SmartForward أو طلب الأمر MeetingResponse للإشارة إلى مجموعة النتائج. يجب على العميل تخزين قيمة LongId كسلسلة معتمة تصل إلى 256 حرفًا. |
| [Properties](../../aspose.email.clients.activesync.transportlayer/searchresult/properties) { get; set; } | خصائص استجابة أمر البحث عبارة عن حاوية للخصائص التي تنطبق على إدخال فردي يطابق سلسلة بحث عنصر الاستعلام. على سبيل المثال ، يحتوي عنصر الخصائص على عنصر لكل خاصية GAL غير فارغة وذات قيمة نصية مرفقة بإدخال GAL المطابق. يتم إرجاع تلك الخصائص المرفقة بإدخال GAL المحدد فقط ؛ لذلك يمكن إرجاع مجموعات مختلفة من الخصائص في استجابة XML لإدخالات GAL المطابقة المختلفة. |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->