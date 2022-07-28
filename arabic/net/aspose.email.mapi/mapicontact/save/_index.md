---
title: Save
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يحفظ هذاMapiContactaspose.email.mapi/mapicontact إلى ملف vCard مع الخيارات الافتراضية . إصدار vCard المدعوم هو 2.1
type: docs
weight: 140
url: /ar/net/aspose.email.mapi/mapicontact/save/
---
## Save(string) {#save_3}

يحفظ هذا[`MapiContact`](../../mapicontact) إلى ملف vCard مع الخيارات الافتراضية . إصدار vCard المدعوم هو 2.1

```csharp
public void Save(string filePath)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | اسم ملف vCard |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | *filePath* هو`لا شيء`أو`فارغة` |

### أنظر أيضا

* class [MapiContact](../../mapicontact)
* مساحة الاسم [Aspose.Email.Mapi](../../mapicontact)
* المجسم [Aspose.Email](../../../)

---

## Save(string, ContactSaveFormat) {#save_4}

يحفظ هذا[`MapiContact`](../../mapicontact)إلى الملف المحدد بتنسيق باستخدام الخيارات الافتراضية . تنسيق الحفظ المدعوم هو vCard.

```csharp
public void Save(string filePath, ContactSaveFormat saveFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | اسم ملف vCard |
| saveFormat | ContactSaveFormat | تنسيق حفظ |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | *filePath* هو`لا شيء`أو`فارغة` |
| NotSupportedException | التنسيق المحدد غير مدعوم |

### أنظر أيضا

* enum [ContactSaveFormat](../../contactsaveformat)
* class [MapiContact](../../mapicontact)
* مساحة الاسم [Aspose.Email.Mapi](../../mapicontact)
* المجسم [Aspose.Email](../../../)

---

## Save(string, ContactSaveOptions) {#save_5}

يحفظ هذا[`MapiContact`](../../mapicontact) في ملف باستخدام خيارات الحفظ المحددة. خيارات الحفظ المدعومة هي[`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions)

```csharp
public void Save(string filePath, ContactSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | اسم ملف vCard |
| saveOptions | ContactSaveOptions | خيارات الحفظ |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | *filePath* هو`لا شيء`أو`فارغة` |
| ArgumentNullException | *saveOptions* هو`لا شيء` |
| NotSupportedException | بعض خيار الحفظ غير مدعوم |

### أنظر أيضا

* class [ContactSaveOptions](../../contactsaveoptions)
* class [MapiContact](../../mapicontact)
* مساحة الاسم [Aspose.Email.Mapi](../../mapicontact)
* المجسم [Aspose.Email](../../../)

---

## Save(Stream) {#save}

يحفظ هذا[`MapiContact`](../../mapicontact) في التدفق المحدد بتنسيق vCard . إصدار vCard المدعوم هو 2.1

```csharp
public void Save(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | تيار للحفظ فيه |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *stream* هو`لا شيء` |
| NotSupportedException | *stream* لا يدعم الكتابة |

### أنظر أيضا

* class [MapiContact](../../mapicontact)
* مساحة الاسم [Aspose.Email.Mapi](../../mapicontact)
* المجسم [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveFormat) {#save_1}

يحفظ هذا[`MapiContact`](../../mapicontact) إلى التدفق المحدد بتنسيق باستخدام الخيارات الافتراضية . تنسيق الحفظ المدعوم هو vCard

```csharp
public void Save(Stream stream, ContactSaveFormat saveFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | تيار للحفظ فيه |
| saveFormat | ContactSaveFormat | تنسيق حفظ |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *stream* هو`لا شيء` |
| NotSupportedException | *stream* لا يدعم الكتابة |
| NotSupportedException | التنسيق المحدد غير مدعوم |

### أنظر أيضا

* enum [ContactSaveFormat](../../contactsaveformat)
* class [MapiContact](../../mapicontact)
* مساحة الاسم [Aspose.Email.Mapi](../../mapicontact)
* المجسم [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveOptions) {#save_2}

يحفظ هذا[`MapiContact`](../../mapicontact) إلى التدفق المحدد باستخدام خيارات الحفظ المحددة. خيارات الحفظ المدعومة هي[`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions)

```csharp
public void Save(Stream stream, ContactSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | تيار للحفظ فيه |
| saveOptions | ContactSaveOptions | خيارات الحفظ |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *stream*أو*saveOptions* هو`لا شيء` |
| NotSupportedException | *stream* لا يدعم الكتابة |
| ArgumentException | غير صحيح*saveOptions* |
| NotSupportedException | بعض خيار الحفظ غير مدعوم |

### أنظر أيضا

* class [ContactSaveOptions](../../contactsaveoptions)
* class [MapiContact](../../mapicontact)
* مساحة الاسم [Aspose.Email.Mapi](../../mapicontact)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->