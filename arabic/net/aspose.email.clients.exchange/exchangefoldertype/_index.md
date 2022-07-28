---
title: ExchangeFolderType
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يعدّد أنواع المجلدات المميزة. هذه القيم موجودة أيضًا في خاصية PidTagContainerClass.
type: docs
weight: 3340
url: /ar/net/aspose.email.clients.exchange/exchangefoldertype/
---
## ExchangeFolderType enumeration

يعدّد أنواع المجلدات المميزة. هذه القيم موجودة أيضًا في خاصية PidTagContainerClass.

```csharp
public enum ExchangeFolderType
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| Undefined | `0` | لم يتم تعيين نوع المجلد. يتم استخدام القيمة مع المجلدات المعروفة التالية: الجذر - مجلد المستوى الأعلى للتسلسل الهرمي لمخزن الرسائل ، والذي يحتوي على كافة كائنات المجلد الأخرى في مخزن الرسائل هذا. الباحث - يحتوي على مجلدات البحث الافتراضية . FreeBusy Data - يحتوي على بيانات التوفر / الانشغال لمالك علبة البريد. أعلى المجلدات الشخصية - المجلد العلوي من التسلسل الهرمي للرسائل الشخصية ، والذي يحتوي على مجلدات بيانات المستخدم ، بما في ذلك المجلدات الخاصة مثل مجلد علبة الوارد . طرق العرض الشائعة - يحتوي بيانات طرق العرض الافتراضية القياسية لمخزن الرسائل والتي يمكن استخدامها من قبل أي مستخدم لعميل يصل إلى مخزن الرسائل . طرق العرض الشخصية - تحتوي على البيانات الخاصة بالعروض التي حددها مستخدم معين . الإجراء المؤجل - يحتوي على أي مؤجل رسالة الإجراء (DAM) أو رسالة الخطأ المؤجلة (DEM) التي تنتج عن تنفيذ قواعد جانب العميل. |
| Note | `1` | تمثل هذه القيمة نوع مجلد رسائل البريد الإلكتروني ("IPF.Note") ._ يتم استخدام القيمة مع المجلدات المعروفة التالية: العناصر المحذوفة - الموقع الافتراضي للكائنات التي تم حذفها . علبة الصادر - البريد الإلكتروني الصادر يتم وضع كائنات الرسائل في هذا المجلد عند إرسال كائن الرسالة. العناصر المرسلة - الموقع الافتراضي الذي يتم فيه وضع نسخ من كائنات رسائل البريد الإلكتروني بعد إرسالها (إرسالها). علبة الوارد - الموقع الافتراضي للواردات ( تم استلام) كائنات رسائل البريد الإلكتروني. المسودات - الموقع الافتراضي لكائنات رسائل البريد الإلكتروني التي تم حفظها ولكن لم يتم إرسالها. بواسطة قاعدة البريد الإلكتروني غير الهام. مشكلات المزامنة - تحتوي على مجلدات تحتوي على رسائل تشير إلى مشكلات معينة تمت مواجهتها أثناء المزامنة بين العميل والخادم. هذا هو المجلد الأصل لمجلدات التعارضات والفشل المحلي وفشل الخادم . التعارضات - يحتوي على كائنات الرسائل التي تشير إلى تعارضات المزامنة بين العميل والخادم . حالات الفشل المحلية - يحتوي على رسائل تشير إلى حالات فشل مزامنة جانب العميل . فشل الخادم - يحتوي على رسائل تشير إلى فشل المزامنة من جانب الخادم . معالجة البريد المتعقب - مجلد البحث الذي يحتوي على كائنات تم وضع علامة عليها . قائمة انتظار التخزين المؤقت - يحتوي على كائنات البريد الإلكتروني التي تم إرسالها أو استلامها. |
| RSSFeeds | `2` | تمثل هذه القيمة نوع مجلد رسالة RSS ("IPF.Note.OutlookHomepage") . يتم استخدام القيمة مع المجلدات المعروفة التالية: موجز ويب لـ RSS - يحتوي على رسائل موجز تجميع بسيط جدًا (RSS) . |
| Appointment | `3` | تمثل هذه القيمة نوع مجلد "الموعد" ("IPF.Appointment") ._ يتم استخدام القيمة مع المجلدات المعروفة التالية: التقويم - يحتوي على كائنات التقويم ، مثل المواعيد. |
| Contact | `4` | تمثل هذه القيمة نوع مجلد "جهات الاتصال" ("IPF.Contact") ._ يتم استخدام القيمة مع المجلدات المعروفة التالية: جهات الاتصال - تحتوي على كائنات جهات الاتصال . جهات الاتصال المقترحة - تحتوي على كائنات جهات الاتصال التي تم إنشاؤها عندما لا يكون المستلم في دفتر العناوين . بحث جهات الاتصال - مجلد البحث الذي يعرض قائمة جهات الاتصال التي تناسب معايير البحث . |
| QuickContacts | `5` | تمثل هذه القيمة نوع المجلد لجهات الاتصال المفضلة ("IPF.Contact.MOC.QuickContacts") ._ يتم استخدام القيمة مع المجلدات المعروفة التالية: جهات اتصال سريعة - تحتوي على كائنات جهات الاتصال الخاصة بجهات الاتصال المفضلة وجهات الاتصال الخاصة بالمستخدم. |
| ImContactsList | `6` | تمثل هذه القيمة نوع المجلد لجهات اتصال المراسلة الفورية ("IPF.Contact.MOC.ImContactList") ._ يتم استخدام القيمة مع المجلدات المعروفة التالية: قائمة جهات اتصال IM - تحتوي على كائنات قائمة التوزيع الشخصية الخاصة بجهات الاتصال المفضلة وجهات اتصال المراسلة الفورية . |
| DocumentLibraries | `7` | تمثل هذه القيمة نوع مجلد "المستندات" ("IPF.ShortcutFolder") . يتم استخدام القيمة مع المجلدات المعروفة التالية: مكتبات المستندات - تحتوي على مستندات يتم تحميلها إلى موقع مشترك. |
| Journal | `8` | تمثل هذه القيمة نوع المجلد "Journal" ("IPF.Journal") ._ يتم استخدام القيمة مع المجلدات المعروفة التالية: Journal - تحتوي على كائنات دفتر اليومية. |
| StickyNote | `9` | تمثل هذه القيمة نوع مجلد "الملاحظات" ("IPF.StickyNote") ._ يتم استخدام القيمة مع المجلدات المعروفة التالية: الملاحظات - تحتوي على كائنات الملاحظات. |
| Task | `10` | تمثل هذه القيمة نوع مجلد "المهمة" ("IPF.Task") ._ يتم استخدام القيمة مع المجلدات المعروفة التالية: المهام - مجلد البحث المستخدم لتعقب كائنات المهام . المهام - يحتوي على كائنات المهام. |
| Imap | `11` | تمثل هذه القيمة نوع المجلد "imap" ("IPF.IMAP") . يُستخدم للترحيل من ملف تعريف IMAP إلى Exchange. |
| Unknown | `12` | نوع المجلد غير معروف . |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->