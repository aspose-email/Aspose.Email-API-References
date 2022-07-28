---
title: RebuildResults
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يفرض على الخادم إعادة إنشاء مجلد البحث 2 الذي يتوافق مع استعلام معين. يتم تخزين نتائج البحث أي مجموعة النتائج في مجلد بحث على الخادم. بهذه الطريقة  عندما يعود العميل بنفس الاستعلام ولكن بنطاق صف جديد  يتم سحب الصفوف من مجموعة النتائج المخزنة حاليًا في مجلد البحث. لا يلزم إعادة إنشاء مجموعة النتائج بالكامل. يظل مجلد البحث بدون تغيير حتى يقوم العميل بأحد الإجراءات التالية لتحديث مجموعة النتائج - يرسل طلب بحث  مع تحديد استعلام جديد. في هذه الحالة  يتم إعادة إنشاء مجلد البحث تلقائيًا. لا يلزم تضمين عقدة RebuildResults . - يرسل طلب بحث يتضمن عقدة RebuildResults. في هذه الحالة  يتم إجبار الخادم على إعادة إنشاء مجلد البحث . إذا تمت إضافة عنصر جديد  فلن يظهر العنصر في مجموعة النتائج حتى يتم تحديث مجموعة النتائج. إذا تم حذف عنصر ما  فسيقوم الخادم بتصفية العنصر المحذوف من مجموعة النتائج. يجب أن يرسل العميل طلب بحث جديدًا مع الاستعلام المحدد ويتضمن خيار RebuildResults كل بضعة أيام لضمان الحصول على نتائج دقيقة لهذا الاستعلام.
type: docs
weight: 90
url: /ar/net/aspose.email.clients.activesync.transportlayer/searchoptions/rebuildresults/
---
## SearchOptions.RebuildResults property

يفرض على الخادم إعادة إنشاء مجلد البحث (2) الذي يتوافق مع استعلام معين. يتم تخزين نتائج البحث (أي مجموعة النتائج) في مجلد بحث على الخادم. بهذه الطريقة ، عندما يعود العميل بنفس الاستعلام ولكن بنطاق صف جديد ، يتم سحب الصفوف من مجموعة النتائج المخزنة حاليًا في مجلد البحث. لا يلزم إعادة إنشاء مجموعة النتائج بالكامل. يظل مجلد البحث بدون تغيير حتى يقوم العميل بأحد الإجراءات التالية لتحديث مجموعة النتائج: - يرسل طلب بحث ، مع تحديد استعلام جديد. في هذه الحالة ، يتم إعادة إنشاء مجلد البحث تلقائيًا. لا يلزم تضمين عقدة RebuildResults . - يرسل طلب بحث يتضمن عقدة RebuildResults. في هذه الحالة ، يتم إجبار الخادم على إعادة إنشاء مجلد البحث . إذا تمت إضافة عنصر جديد ، فلن يظهر العنصر في مجموعة النتائج حتى يتم تحديث مجموعة النتائج. إذا تم حذف عنصر ما ، فسيقوم الخادم بتصفية العنصر المحذوف من مجموعة النتائج. يجب أن يرسل العميل طلب بحث جديدًا مع الاستعلام المحدد ويتضمن خيار RebuildResults كل بضعة أيام لضمان الحصول على نتائج دقيقة لهذا الاستعلام.

```csharp
public bool RebuildResults { get; set; }
```

### أنظر أيضا

* class [SearchOptions](../../searchoptions)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../searchoptions)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->