---
title: Save
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يحفظ هذاMapiTaskaspose.email.mapi/mapitask إلى التدفق المحدد باستخدام التنسيق المحدد.
type: docs
weight: 220
url: /ar/net/aspose.email.mapi/mapitask/save/
---
## Save(Stream, TaskSaveFormat) {#save}

يحفظ هذا[`MapiTask`](../../mapitask) إلى التدفق المحدد باستخدام التنسيق المحدد.

```csharp
public void Save(Stream stream, TaskSaveFormat saveFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | تيار للحفظ فيه. |
| saveFormat | TaskSaveFormat | تنسيق حفظ. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *stream* هو`لا شيء` . |
| NotSupportedException | *stream* لا يدعم الكتابة. |
| NotSupportedException | التنسيق المحدد غير مدعوم. |

### أنظر أيضا

* enum [TaskSaveFormat](../../tasksaveformat)
* class [MapiTask](../../mapitask)
* مساحة الاسم [Aspose.Email.Mapi](../../mapitask)
* المجسم [Aspose.Email](../../../)

---

## Save(string, TaskSaveFormat) {#save_1}

يحفظ هذا[`MapiTask`](../../mapitask) في ملف باستخدام التنسيق المحدد.

```csharp
public void Save(string filePath, TaskSaveFormat saveFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | اسم ملف. |
| saveFormat | TaskSaveFormat | تنسيق حفظ. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | *filePath* هو`لا شيء`أو`فارغة`. |
| NotSupportedException | بعض خيار الحفظ غير مدعوم |

### أنظر أيضا

* enum [TaskSaveFormat](../../tasksaveformat)
* class [MapiTask](../../mapitask)
* مساحة الاسم [Aspose.Email.Mapi](../../mapitask)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->