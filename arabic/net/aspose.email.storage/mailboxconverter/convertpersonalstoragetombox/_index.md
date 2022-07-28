---
title: ConvertPersonalStorageToMbox
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يحول ملفPersonalStorageaspose.email.storage.pst/personalstorageإلى تنسيق mbox باستخدام مسار معين.
type: docs
weight: 10
url: /ar/net/aspose.email.storage/mailboxconverter/convertpersonalstoragetombox/
---
## ConvertPersonalStorageToMbox(PersonalStorage, string, MessageAcceptanceCallback) {#convertpersonalstoragetombox_1}

يحول ملف[`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage)إلى تنسيق mbox باستخدام مسار معين.

```csharp
public static void ConvertPersonalStorageToMbox(PersonalStorage personalStorage, 
    string storagePath, MessageAcceptanceCallback acceptanceCallback)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| personalStorage | PersonalStorage | التخزين الشخصي. |
| storagePath | String | طريق الحفظ*personalStorage* هيكل ل. |
| acceptanceCallback | MessageAcceptanceCallback | رد نداء القبول ، يمكن أن يكون فارغًا. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | إذا*personalStorage* باطل. |
| ArgumentNullException | إذا*storagePath* باطل. |

### ملاحظات

سيحتوي المجلد الناتج على نسخة طبق الأصل من ملف*personalStorage* على سبيل المثال ، سيتم إعادة إنشاء شجرة الدليل على القرص.

### أنظر أيضا

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* delegate [MessageAcceptanceCallback](../../../aspose.email/messageacceptancecallback)
* class [MailboxConverter](../../mailboxconverter)
* مساحة الاسم [Aspose.Email.Storage](../../mailboxconverter)
* المجسم [Aspose.Email](../../../)

---

## ConvertPersonalStorageToMbox(PersonalStorage, MboxStorageWriter, MessageAcceptanceCallback) {#convertpersonalstoragetombox}

يحول ملف[`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) إلى تنسيق mbox باستخدام معين[`MboxStorageWriter`](../../../aspose.email.storage.mbox/mboxstoragewriter) .

```csharp
public static void ConvertPersonalStorageToMbox(PersonalStorage personalStorage, 
    MboxStorageWriter mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| personalStorage | PersonalStorage | التخزين الشخصي. |
| mboxStorageWriter | MboxStorageWriter | كاتب تخزين mbox. |
| acceptanceCallback | MessageAcceptanceCallback | رد نداء القبول ، يمكن أن يكون فارغًا. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | إذا*personalStorage* باطل. |
| ArgumentNullException | إذا*mboxStorageWriter* باطل. |

### ملاحظات

سيحتوي تخزين mbox الناتج على مجلد واحد فقط لصندوق الوارد العادي مع جميع الرسائل ، إذا كان عليك الحفاظ على الهيكل الأصلي للتخزين ، فاستخدم طريقة XXX بدلاً من ذلك.

### أنظر أيضا

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [MboxStorageWriter](../../../aspose.email.storage.mbox/mboxstoragewriter)
* delegate [MessageAcceptanceCallback](../../../aspose.email/messageacceptancecallback)
* class [MailboxConverter](../../mailboxconverter)
* مساحة الاسم [Aspose.Email.Storage](../../mailboxconverter)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->