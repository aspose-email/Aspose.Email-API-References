---
title: ImapMessageInfo
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل كائن رسالة Imap .
type: docs
weight: 16370
url: /ar/net/aspose.email.clients.imap/imapmessageinfo/
---
## ImapMessageInfo class

يمثل كائن رسالة Imap .

```csharp
public sealed class ImapMessageInfo : MessageInfoBase
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Answered](../../aspose.email.clients.imap/imapmessageinfo/answered) { get; } | يحصل على قيمة تشير إلى ما إذا كانت خاصية الإشارات تحتوي على علامة "تم الرد عليها". |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc) { get; } | الحصول على نسخة كربونية مخفية من رسالة البريد الإلكتروني. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc) { get; } | يحصل على نسخة من رسالة البريد الإلكتروني. |
| [ConversationId](../../aspose.email.clients.imap/imapmessageinfo/conversationid) { get; } | يحصل على قيمة تشير إلى معرف المحادثة. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date) { get; } | يحدد تاريخ الإنشاء التاريخ والوقت الذي أشار فيه منشئ الرسالة إلى أن الرسالة كانت كاملة وجاهزة للدخول إلى نظام تسليم البريد. على سبيل المثال ، قد يكون هذا هو الوقت الذي يضغط فيه المستخدم على الزر "إرسال" أو "إرسال" في أحد برامج التطبيق. بدلاً من ذلك الوقت الذي وضع فيه الإنسان أو منشئ الرسالة الآخر الرسالة في شكلها النهائي ، جاهزة للنقل . (على سبيل المثال ، قد يصطف مستخدم الكمبيوتر المحمول غير المتصل بشبكة رسالة لتسليمها. يهدف تاريخ الإنشاء إلى احتواء التاريخ والوقت اللذين وضع المستخدم فيهما الرسالة في قائمة انتظار ، وليس الوقت الذي اتصل فيه المستخدم بالشبكة لإرسال الرسالة.) |
| [Deleted](../../aspose.email.clients.imap/imapmessageinfo/deleted) { get; } | يحصل على قيمة تشير إلى ما إذا كانت خاصية الإشارات تحتوي على العلامة المحذوفة. |
| [Draft](../../aspose.email.clients.imap/imapmessageinfo/draft) { get; } | يحصل على قيمة تشير إلى ما إذا كانت خاصية الإشارات تحتوي على علامة المسودة. |
| [ExtraParameters](../../aspose.email.clients.imap/imapmessageinfo/extraparameters) { get; } | الحصول على معلمات إضافية للرسالة . |
| [Flagged](../../aspose.email.clients.imap/imapmessageinfo/flagged) { get; } | يحصل على قيمة تشير إلى ما إذا كانت خاصية الإشارات تحتوي على العلامة المميزة. |
| [Flags](../../aspose.email.clients.imap/imapmessageinfo/flags) { get; } | يحصل على إشارات الرسالة. |
| [From](../../aspose.email.clients/messageinfobase/from) { get; } | الحصول على قائمة مؤلفي هذه الرسالة. |
| [Headers](../../aspose.email.clients/messageinfobase/headers) { get; } | الحصول على رؤوس رسالة البريد الإلكتروني. |
| [InternalDate](../../aspose.email.clients.imap/imapmessageinfo/internaldate) { get; } | التاريخ الداخلي للرسالة ووقتها على الخادم. هذا ليس التاريخ والوقت في رأس [RFC-2822] ، بل هو تاريخ ووقت يعكسان وقت استلام الرسالة. - في حالة تسليم الرسائل عبر [SMTP] ، يجب أن يكون هذا هو تاريخ ووقت التسليم النهائي للرسالة على النحو المحدد بواسطة [SMTP]. - في حالة الرسائل التي تم تسليمها بواسطة أمر IMAP4rev1 COPY ، يجب أن يكون هذا هو التاريخ والوقت الداخلي لرسالة المصدر . - في حالة الرسائل التي تم تسليمها بواسطة أمر IMAP4rev1 APPEND ، يجب أن يكون هذا التاريخ والوقت كما هو محدد في وصف الأمر APPEND . - يتم تحديد جميع الحالات الأخرى. |
| [IsRead](../../aspose.email.clients.imap/imapmessageinfo/isread) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الخاصية Flags تحتوي على علامة القراءة. |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe) { get; } | يصف حقل القائمة-إلغاء الاشتراك الأمر (يفضل استخدام البريد) لإلغاء اشتراك المستخدم مباشرةً (إزالته من القائمة) . لمزيد من التفاصيل ، يرجى الاطلاع على https://tools.ietf.org/html/rfc2369 |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid) { get; } | يحصل على معرف الرسالة. |
| [ModificationSequence](../../aspose.email.clients.imap/imapmessageinfo/modificationsequence) { get; } | يحصل على تسلسل التعديل لهذه الرسالة. انظر المزيد: https://tools.ietf.org/html/rfc7162 |
| [ParentFolder](../../aspose.email.clients.imap/imapmessageinfo/parentfolder) { get; } | يحصل على المجلد الأصل للرسالة |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties) { get; } | يحصل على خصائص mapi . |
| [Recent](../../aspose.email.clients.imap/imapmessageinfo/recent) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الخاصية Flags تحتوي على العلامة الأخيرة. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto) { get; } | الحصول على قائمة العناوين التي يجب أن تتلقى ردودًا على هذه الرسالة. |
| [Sender](../../aspose.email.clients/messageinfobase/sender) { get; } | يحصل على مرسل هذه الرسالة. |
| [SequenceNumber](../../aspose.email.clients.imap/imapmessageinfo/sequencenumber) { get; } | يحصل على رقم تسلسل الرسالة. |
| [Size](../../aspose.email.clients/messageinfobase/size) { get; } | الحصول على حجم رسالة البريد الإلكتروني. |
| [Subject](../../aspose.email.clients/messageinfobase/subject) { get; } | يحصل على موضوع رسالة البريد الإلكتروني. |
| virtual [To](../../aspose.email.clients/messageinfobase/to) { get; } | الحصول على مستلمي رسالة البريد الإلكتروني. |
| [UniqueId](../../aspose.email.clients.imap/imapmessageinfo/uniqueid) { get; } | يحصل على المعرف الفريد للرسالة. |

## طُرق

| اسم | وصف |
| --- | --- |
| [ContainsKeyword](../../aspose.email.clients.imap/imapmessageinfo/containskeyword)(string) | يحصل على قيمة تشير إلى ما إذا كانت خاصية الإشارات تحتوي على علامة الكلمة الأساسية. |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose)() | يؤدي المهام المرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| override [ToString](../../aspose.email.clients.imap/imapmessageinfo/tostring)() | إرجاع سلسلة تمثل الكائن الحالي. |

### أنظر أيضا

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
