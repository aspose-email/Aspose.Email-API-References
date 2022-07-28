---
title: PersonalStorageQueryBuilder
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل منشئ تعبير البحث الذي يستخدمه pst .
type: docs
weight: 20310
url: /ar/net/aspose.email.storage.pst/personalstoragequerybuilder/
---
## PersonalStorageQueryBuilder class

يمثل منشئ تعبير البحث الذي يستخدمه pst .

```csharp
public sealed class PersonalStorageQueryBuilder : MailQueryBuilder
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PersonalStorageQueryBuilder](personalstoragequerybuilder)() | يقوم بتهيئة مثيل جديد لملف[`PersonalStorageQueryBuilder`](../personalstoragequerybuilder) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | يحصل على الحقل الذي يسمح بالعثور على الرسائل التي تحتوي على السلسلة المحددة في حقل نسخة مخفية الوجهة لبنية المغلف. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | يحصل على الحقل الذي يسمح بالعثور على الرسائل التي تحتوي على السلسلة المحددة في نص الرسالة. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | يحصل على الحقل الذي يسمح بالعثور على الرسائل التي تحتوي على السلسلة المحددة في حقل CC الخاص بهيكل المغلف. |
| [ContainerClass](../../aspose.email.storage.pst/personalstoragequerybuilder/containerclass) { get; } | يحصل على مجلدات بفئة رسالة محددة. |
| [ContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/contentscount) { get; } | بحث عن مجلدات ذات محتويات محددة. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | الحصول على التشفير الافتراضي (مجموعة أحرف) لمنشئ الاستعلام |
| [FolderName](../../aspose.email.storage.pst/personalstoragequerybuilder/foldername) { get; } | بحث عن مجلدات باسم عرض محدد . |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | يحصل على الحقل الذي يسمح بالعثور على الرسائل التي تحتوي على السلسلة المحددة في حقل FROM الخاص ببنية المغلف. |
| [Importance](../../aspose.email.storage.pst/personalstoragequerybuilder/importance) { get; } | البحث في الرسائل ذات الأهمية المحددة . |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | يحصل على الحقل الذي يسمح بالعثور على الرسائل حسب التاريخ الداخلي. |
| [MessageClass](../../aspose.email.storage.pst/personalstoragequerybuilder/messageclass) { get; } | الحصول على رسائل بفئة رسالة محددة. |
| [MessageId](../../aspose.email.storage.pst/personalstoragequerybuilder/messageid) { get; } | يحصل على الحقل الذي يسمح بالعثور على الرسائل التي تحتوي على السلسلة المحددة في حقل MessageId الخاص بهيكل المغلف. |
| [MessageSize](../../aspose.email.storage.pst/personalstoragequerybuilder/messagesize) { get; } | البحث في الرسائل ذات الحجم المحدد . |
| [OnlyFoldersCreatedByUser](../../aspose.email.storage.pst/personalstoragequerybuilder/onlyfolderscreatedbyuser) { get; } | يحصل على المجلدات التي أنشأها المستخدم ، أي يستبعد جميع مجلدات IPM القياسية. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | يحصل على الحقل الذي يسمح بالعثور على الرسائل حسب تاريخ الإرسال. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | يحصل على الحقل الذي يسمح بالعثور على الرسائل التي تحتوي على السلسلة المحددة في حقل SUBJECT الخاص ببنية المغلف. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | يحصل على الحقل الذي يسمح بالعثور على الرسائل التي تحتوي على السلسلة المحددة في الرؤوس (الموضوع ، من ، إلى ، نسخة إلى) ونص الرسالة. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | يحصل على الحقل الذي يسمح بالعثور على الرسائل التي تحتوي على السلسلة المحددة في حقل TO لبنية المغلف. |
| [UnreadContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/unreadcontentscount) { get; } | بحث عن مجلدات ذات محتوى محدد غير مقروء. |

## طُرق

| اسم | وصف |
| --- | --- |
| [FindConversationThread](../../aspose.email.storage.pst/personalstoragequerybuilder/findconversationthread)(MessageInfo) | البحث عن موضوع المحادثة . |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | يحصل على الاستعلام. |
| [HasFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasflags)(MapiMessageFlags) | البحث في الرسائل ذات العلامات المحددة . |
| [HasNoFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnoflags)(MapiMessageFlags) | البحث في الرسائل ذات العلامات غير المحددة . |
| [HasNoSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnosubfolders)() | بحث في المجلدات التي لا تحتوي على مجلدات فرعية. |
| [HasSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hassubfolders)() | بحث في المجلدات التي تحتوي على مجلدات فرعية. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | البحث عن الرسائل التي تطابق أيًا من مفتاحي البحث. يوفر الفصل بين تعبيرين (OR) . |

### أنظر أيضا

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* مساحة الاسم [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
