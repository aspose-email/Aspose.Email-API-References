---
title: Create
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: ينشئ ملف PST الجديد باسم الملف المحدد.
type: docs
weight: 20
url: /ar/net/aspose.email.storage.pst/personalstorage/create/
---
## Create(string, FileFormatVersion, CancellationToken) {#create_5}

ينشئ ملف PST الجديد باسم الملف المحدد.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fileName | String | الاسم الكامل للملف. |
| version | FileFormatVersion | إصدار ملف PST . |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن PersonalStorage يمثل PST الجديد.

### استثناءات

| استثناء | حالة |
| --- | --- |
| NotImplementedException | رميات إذا تم إنشاء إصدار ملف ANSI |
| ArgumentNullException | رميات إذا كان اسم الملف فارغًا أو فارغًا |

### ملاحظات

ملاحظة ، يتم الآن دعم إنشاء إصدار ملف Unicode فقط.

### أنظر أيضا

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* مساحة الاسم [Aspose.Email.Storage.Pst](../../personalstorage)
* المجسم [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, CancellationToken) {#create_3}

ينشئ PST في دفق .

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق الذي يتم فيه إنشاء PST . |
| version | FileFormatVersion | إصدار ملف PST . |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن PersonalStorage يمثل PST الجديد.

### استثناءات

| استثناء | حالة |
| --- | --- |
| NotImplementedException | رميات إذا تم إنشاء إصدار ملف ANSI |
| ArgumentNullException | رميات إذا كان اسم الملف فارغًا أو فارغًا |

### ملاحظات

ملاحظة ، يتم الآن دعم إنشاء إصدار ملف Unicode فقط.

### أنظر أيضا

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* مساحة الاسم [Aspose.Email.Storage.Pst](../../personalstorage)
* المجسم [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool, CancellationToken) {#create_2}

ينشئ PST في دفق .

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    bool leaveStreamOpen, CancellationToken token)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق الذي يتم فيه إنشاء PST . |
| version | FileFormatVersion | إصدار ملف PST . |
| leaveStreamOpen | Boolean | اترك الدفق مفتوحًا عند التخلص من PersonalStorage. |
| token | CancellationToken | ينشر إشعارًا بإلغاء العمليات. |

### قيمة الإرجاع

كائن PersonalStorage يمثل PST الجديد.

### استثناءات

| استثناء | حالة |
| --- | --- |
| NotImplementedException | رميات إذا تم إنشاء إصدار ملف ANSI |
| ArgumentNullException | رميات إذا كان اسم الملف فارغًا أو فارغًا |

### ملاحظات

ملاحظة ، يتم الآن دعم إنشاء إصدار ملف Unicode فقط.

### أنظر أيضا

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* مساحة الاسم [Aspose.Email.Storage.Pst](../../personalstorage)
* المجسم [Aspose.Email](../../../)

---

## Create(string, FileFormatVersion) {#create_4}

ينشئ ملف PST الجديد باسم الملف المحدد.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fileName | String | الاسم الكامل للملف . |
| version | FileFormatVersion | إصدار ملف PST . |

### قيمة الإرجاع

كائن PersonalStorage يمثل PST الجديد.

### استثناءات

| استثناء | حالة |
| --- | --- |
| NotImplementedException | رميات إذا تم إنشاء إصدار ملف ANSI |
| ArgumentNullException | رميات إذا كان اسم الملف فارغًا أو فارغًا |

### ملاحظات

ملاحظة ، يتم الآن دعم إنشاء إصدار ملف Unicode فقط.

### أنظر أيضا

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* مساحة الاسم [Aspose.Email.Storage.Pst](../../personalstorage)
* المجسم [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion) {#create}

ينشئ PST في دفق .

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق الذي يتم فيه إنشاء PST . |
| version | FileFormatVersion | إصدار ملف PST . |

### قيمة الإرجاع

كائن PersonalStorage يمثل PST الجديد.

### استثناءات

| استثناء | حالة |
| --- | --- |
| NotImplementedException | رميات إذا تم إنشاء إصدار ملف ANSI |
| ArgumentNullException | رميات إذا كان الدفق فارغًا |

### ملاحظات

ملاحظة ، يتم الآن دعم إنشاء إصدار ملف Unicode فقط.

### أنظر أيضا

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* مساحة الاسم [Aspose.Email.Storage.Pst](../../personalstorage)
* المجسم [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool) {#create_1}

ينشئ PST في دفق .

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, bool leaveStreamOpen)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق الذي يتم فيه إنشاء PST . |
| version | FileFormatVersion | إصدار ملف PST . |
| leaveStreamOpen | Boolean | اترك الدفق مفتوحًا عند التخلص من PersonalStorage. |

### قيمة الإرجاع

كائن PersonalStorage يمثل PST الجديد.

### استثناءات

| استثناء | حالة |
| --- | --- |
| NotImplementedException | رميات إذا تم إنشاء إصدار ملف ANSI |
| ArgumentNullException | رميات إذا كان الدفق فارغًا |

### ملاحظات

ملاحظة ، يتم الآن دعم إنشاء إصدار ملف Unicode فقط.

### أنظر أيضا

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* مساحة الاسم [Aspose.Email.Storage.Pst](../../personalstorage)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
