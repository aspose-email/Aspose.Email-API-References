---
title: AmpMessage
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: رسالة تسمح للمرسلين بتضمين مكونات AMP داخل رسائل البريد الإلكتروني.
type: docs
weight: 140
url: /ar/net/aspose.email.amp/ampmessage/
---
## AmpMessage class

رسالة تسمح للمرسلين بتضمين مكونات AMP داخل رسائل البريد الإلكتروني.

```csharp
public class AmpMessage : MailMessage
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [AmpMessage](ampmessage)() | يقوم بتهيئة مثيل جديد لملف[`MailMessage`](../../aspose.email/mailmessage) فئة |

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [AlternateViews](../../aspose.email/mailmessage/alternateviews) { get; } | الحصول على مجموعة من طرق العرض البديلة للرسالة |
| virtual [AmpHtmlBody](../../aspose.email.amp/ampmessage/amphtmlbody) { get; set; } | الحصول على تمثيل AmpHtml لنص الرسالة. |
| virtual [Attachments](../../aspose.email/mailmessage/attachments) { get; } | الحصول على مجموعة مرفقات message |
| virtual [Bcc](../../aspose.email/mailmessage/bcc) { get; set; } | الحصول على أو تعيين مجموعة العناوين التي تحتوي على مستلمي BCC للرسالة |
| virtual [Body](../../aspose.email/mailmessage/body) { get; set; } | الحصول على تمثيل النص العادي لجسم الرسالة أو تعيينه. إذا كان النص / الجزء العادي موجودًا في الرسالة ، تُرجع الخاصية بياناتها النصية. |
| virtual [BodyEncoding](../../aspose.email/mailmessage/bodyencoding) { get; set; } | الحصول على أو تعيين ترميز body |
| [BodyType](../../aspose.email/mailmessage/bodytype) { get; } | يحصل على نوع الجسم. |
| virtual [CC](../../aspose.email/mailmessage/cc) { get; set; } | الحصول على أو تعيين مجموعة العناوين التي تحتوي على مستلمي CC |
| virtual [Date](../../aspose.email/mailmessage/date) { get; set; } | الحصول على أو تحديد تاريخ الرسالة |
| virtual [DeliveryNotificationOptions](../../aspose.email/mailmessage/deliverynotificationoptions) { get; set; } | الحصول على أو تعيين إعلامات التسليم |
| [Epilogue](../../aspose.email/mailmessage/epilogue) { get; set; } | الحصول على نص خاتمة أو تعيينه. يقع بعد الحد الأخير . |
| virtual [From](../../aspose.email/mailmessage/from) { get; set; } | الحصول على أو تعيين من address |
| virtual [Headers](../../aspose.email/mailmessage/headers) { get; } | الحصول على مجموعة رؤوس الرسائل |
| virtual [HtmlBody](../../aspose.email/mailmessage/htmlbody) { get; set; } | الحصول على أو تعيين html body |
| virtual [IsBodyHtml](../../aspose.email/mailmessage/isbodyhtml) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان نص الرسالة بتنسيق Html |
| virtual [IsDraft](../../aspose.email/mailmessage/isdraft) { get; set; } | الحصول على أو تعيين قيمة تشير إلى إرسال رسالة أم لا. |
| virtual [IsEncrypted](../../aspose.email/mailmessage/isencrypted) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الرسالة مشفرة. |
| virtual [IsReadOnly](../../aspose.email/mailmessage/isreadonly) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الرسالة مقروءة فقط |
| virtual [IsSigned](../../aspose.email/mailmessage/issigned) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الرسالة موقعة أم لا. |
| virtual [LinkedResources](../../aspose.email/mailmessage/linkedresources) { get; } | الحصول على مجموعة الموارد المرتبطة من message |
| virtual [MessageId](../../aspose.email/mailmessage/messageid) { get; set; } | الحصول على الرسالة أو تحديدها id |
| virtual [OriginalIsTnef](../../aspose.email/mailmessage/originalistnef) { get; } | يحصل على قيمة تشير إلى ما إذا كانت رسالة EML الأصلية بتنسيق TNEF . |
| [Preamble](../../aspose.email/mailmessage/preamble) { get; set; } | الحصول على نص تمهيد أو تعيينه. وهو موجود قبل الحد الأول ويتضمن عمومًا ملاحظة توضيحية للقراء غير المتوافقين مع MIME. |
| [PreferredTextEncoding](../../aspose.email/mailmessage/preferredtextencoding) { get; set; } | الحصول على أو تعيين الترميز المفضل لجميع خصائص النص |
| virtual [Priority](../../aspose.email/mailmessage/priority) { get; set; } | الحصول على أو تعيين أولوية message |
| [ReadReceiptTo](../../aspose.email/mailmessage/readreceiptto) { get; set; } | الحصول على عنوان إيصال القراءة أو تعيينه. |
| virtual [ReplyToList](../../aspose.email/mailmessage/replytolist) { get; set; } | الحصول على أو تعيين قائمة العناوين للرد عليها لرسالة البريد |
| virtual [ReversePath](../../aspose.email/mailmessage/reversepath) { get; set; } | الحصول على أو تعيين عنوان ReversePath |
| virtual [Sender](../../aspose.email/mailmessage/sender) { get; set; } | الحصول على أو تعيين عنوان المرسل |
| virtual [Sensitivity](../../aspose.email/mailmessage/sensitivity) { get; set; } | الحصول على أو تحديد حساسية message |
| virtual [Subject](../../aspose.email/mailmessage/subject) { get; set; } | الحصول على أو تعيين سطر الموضوع |
| virtual [SubjectEncoding](../../aspose.email/mailmessage/subjectencoding) { get; set; } | الحصول على أو تعيين ترميز subject |
| [TimeZoneOffset](../../aspose.email/mailmessage/timezoneoffset) { get; set; } | الحصول على إزاحة للتوقيت العالمي المنسق (UTC) أو تعيينها لتواريخ الرسائل . تحدد هذه الخاصية فرق المنطقة الزمنية ، بين التوقيت المحلي والتوقيت العالمي المنسق. |
| virtual [To](../../aspose.email/mailmessage/to) { get; set; } | الحصول على أو تعيين مجموعة العناوين التي تحتوي على مستلمي message |
| virtual [XMailer](../../aspose.email/mailmessage/xmailer) { get; set; } | الحصول على أو تعيين X-Mailer البرنامج الذي أنشأ رسالة البريد الإلكتروني |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [AddAlternateView](../../aspose.email/mailmessage/addalternateview)(AlternateView) | إضافة طريقة عرض بديلة إلى message |
| [AddAmpComponent](../../aspose.email.amp/ampmessage/addampcomponent)(AmpComponent) | أضف مكون Amp إلى هذه الرسالة. |
| virtual [AddAttachment](../../aspose.email/mailmessage/addattachment)(Attachment) | إضافة مرفق إلى message |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(CmsSigner) | إنشاء رسالة موقعة. إنشاء نسخة للقراءة فقط من MailMessage المحدد وإضافة توقيع رقمي إليها . |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(X509Certificate2) | إنشاء رسالة موقعة. إنشاء نسخة للقراءة فقط من MailMessage المحدد وإضافة توقيع رقمي إليها . |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(CmsSigner, bool) | إنشاء رسالة موقعة. إنشاء نسخة للقراءة فقط من MailMessage المحدد وإضافة توقيع رقمي إليها . |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(X509Certificate2, bool) | إنشاء رسالة موقعة. إنشاء نسخة للقراءة فقط من MailMessage المحدد وإضافة توقيع رقمي إليها . |
| virtual [CheckBounced](../../aspose.email/mailmessage/checkbounced)() | للتحقق مما إذا كان يمكن التعامل مع هذه الرسالة كرسالة مرتدة. |
| virtual [CheckSignature](../../aspose.email/mailmessage/checksignature)() | التحقق من التوقيع الموجود في MailMessage . |
| virtual [Clone](../../aspose.email/mailmessage/clone)() | استنساخ هذا المثال |
| [CreateReadReceipt](../../aspose.email/mailmessage/createreadreceipt)(string, string) | إنشاء إيصال بالقراءة . |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt)() | يفك تشفير هذه الرسالة |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt)(X509Certificate2) | يفك تشفير هذه الرسالة |
| [Dispose](../../aspose.email/mailmessage/dispose)() | يقوم بإصدار كافة الموارد المستخدمة بواسطة MailMessage |
| virtual [DKIMSign](../../aspose.email/mailmessage/dkimsign)(RSACryptoServiceProvider, DKIMSignatureInfo) | توقيع هذه الرسالة باستخدام توقيع DKIM (البريد المعرف بمفاتيح المجال). |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt)(X509Certificate2) | تشفير هذه الرسالة |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt)(X509Certificate2[]) | تشفير هذه الرسالة |
| override [Equals](../../aspose.email/mailmessage/equals)(object) | تحديد ما إذا كان الكائن المحدد يساوي الكائن الحالي. |
| [GetEnumerator](../../aspose.email/mailmessage/getenumerator)() | إرجاع عداد يتكرر خلال مجموعة. |
| override [GetHashCode](../../aspose.email/mailmessage/gethashcode)() | إرجاع رمز تجزئة للكائن |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext)(bool) | يحصل على نص html للرسالة كنص عادي. تقوم هذه الطريقة بتوزيع خاصية HtmlBody وإرجاع محتوى نص عادي متجاهلًا علامة html. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext)(HyperlinkRenderingCallback) | يحصل على الرسالة htmlbody كنص عادي. |
| virtual [GetObjectData](../../aspose.email/mailmessage/getobjectdata)(SerializationInfo, StreamingContext) | يسكن أSerializationInfo بالبيانات اللازمة لتسلسل الكائن الهدف. |
| virtual [Import](../../aspose.email/mailmessage/import)(Stream) | يستورد الرسالة من stream |
| [RecomposeTnefContent](../../aspose.email/mailmessage/recomposetnefcontent)() | يؤلف محتوى TNEF. ملاحظة ، يتكون مرفق tnef هذا إذا كانت الرسالة تحتوي مبدئيًا على TNEF وتم تحميلها بدون علامة FileCompatibilityMode.PreserveTnefAttachments ، هذه الطريقة لا تنشئ رسالة tnef من الرسالة العادية. |
| virtual [RemoveSignature](../../aspose.email/mailmessage/removesignature)() | إزالة التوقيع |
| virtual [Save](../../aspose.email/mailmessage/save)(Stream) | حفظ الرسالة كتدفق |
| virtual [Save](../../aspose.email/mailmessage/save)(string) | حفظ الرسالة كملف |
| override [Save](../../aspose.email.amp/ampmessage/save#save_1)(Stream, SaveOptions) | حفظ الرسالة كتدفق |
| virtual [Save](../../aspose.email/mailmessage/save)(string, SaveOptions) | حفظ الرسالة كملف مع خيارات إضافية . |
| virtual [SetHtmlBody](../../aspose.email/mailmessage/sethtmlbody)(string, bool) | يعين نص html . |
| override [ToString](../../aspose.email/mailmessage/tostring)() | إرجاع سلسلة تمثل الكائن الحالي. |

### أنظر أيضا

* class [MailMessage](../../aspose.email/mailmessage)
* مساحة الاسم [Aspose.Email.Amp](../../aspose.email.amp)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
