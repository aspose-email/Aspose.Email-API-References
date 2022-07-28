---
title: ListContent
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: تسرد هذه العملية المحتوى المتاح حاليًا للاسترجاع لنوع المحتوى المحدد. المحتوى عبارة عن تجميع للإجراءات والأحداث التي يتم حصادها من خوادم متعددة عبر مراكز بيانات متعددة. سيتم سرد المحتوى بالترتيب الذي تصبح به التجميعات متاحة  ولكن الأحداث والإجراءات داخل التجميعات غير مضمونة لتكون متسلسلة. افتراضيًا  عند حذف startTime و endTime  يتم إرجاع المحتوى المتاح في آخر 24 ساعة.
type: docs
weight: 80
url: /ar/net/aspose.email.clients.activity/iactivityclient/listcontent/
---
## ListContent(string) {#listcontent}

تسرد هذه العملية المحتوى المتاح حاليًا للاسترجاع لنوع المحتوى المحدد. المحتوى عبارة عن تجميع للإجراءات والأحداث التي يتم حصادها من خوادم متعددة عبر مراكز بيانات متعددة. سيتم سرد المحتوى بالترتيب الذي تصبح به التجميعات متاحة ، ولكن الأحداث والإجراءات داخل التجميعات غير مضمونة لتكون متسلسلة. افتراضيًا ، عند حذف startTime و endTime ، يتم إرجاع المحتوى المتاح في آخر 24 ساعة.

```csharp
public ContentInfo[] ListContent(string contentType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| contentType | String | يشير إلى نوع المحتوى. |

### قيمة الإرجاع

قائمة المعلومات المتوفرة حول النشاط

### أنظر أيضا

* class [ContentInfo](../../contentinfo)
* interface [IActivityClient](../../iactivityclient)
* مساحة الاسم [Aspose.Email.Clients.Activity](../../iactivityclient)
* المجسم [Aspose.Email](../../../)

---

## ListContent(string, DateTime?, DateTime?) {#listcontent_1}

تسرد هذه العملية المحتوى المتاح حاليًا للاسترجاع لنوع المحتوى المحدد. المحتوى عبارة عن تجميع للإجراءات والأحداث التي يتم حصادها من خوادم متعددة عبر مراكز بيانات متعددة. سيتم سرد المحتوى بالترتيب الذي تصبح به التجميعات متاحة ، ولكن الأحداث والإجراءات داخل التجميعات غير مضمونة لتكون متسلسلة.

```csharp
public ContentInfo[] ListContent(string contentType, DateTime? startTime, DateTime? endTime)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| contentType | String | يشير إلى نوع المحتوى. |
| startTime | Nullable`1 | أوقات زمنية اختيارية (UTC) تشير إلى النطاق الزمني للمحتوى الذي سيتم إرجاعه ، بناءً على وقت توفر المحتوى. النطاق الزمني شامل فيما يتعلق بوقت البدء (وقت البدء أقل أو يساوي المحتوى الذي تم إنشاؤه) ، بحيث يمكن استخدام الفواصل الزمنية المتزايدة وغير المتداخلة للصفحة من خلال المحتوى المتاح. يجب تحديد كلاهما (وقت البدء ووقت الانتهاء) (أو حذفهما ) . يجب ألا يفصل بين النطاق الزمني أكثر من 24 ساعة ، على ألا يكون وقت البدء في الماضي أكثر من 7 أيام. |
| endTime | Nullable`1 | أوقات زمنية اختيارية (UTC) تشير إلى النطاق الزمني للمحتوى الذي سيتم إرجاعه ، بناءً على وقت توفر المحتوى. النطاق الزمني حصري فيما يتعلق بـ endTime (contentCreated less endTime) ، بحيث يمكن استخدام الفواصل الزمنية المتزايدة وغير المتداخلة للصفحات من خلال المحتوى المتاح. يجب تحديد كلا (startTime و endTime) (أو حذفهما) يجب ألا يكون النطاق الزمني أكثر من 24 ساعة ، على ألا يكون وقت البدء في الماضي أكثر من 7 أيام. |

### قيمة الإرجاع

قائمة المعلومات المتوفرة حول النشاط

### أنظر أيضا

* class [ContentInfo](../../contentinfo)
* interface [IActivityClient](../../iactivityclient)
* مساحة الاسم [Aspose.Email.Clients.Activity](../../iactivityclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->