---
title: MapiMessage
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل مستند بتنسيق رسالة Outlook يمكن تحليله.
type: docs
weight: 18450
url: /ar/net/aspose.email.mapi/mapimessage/
---
## MapiMessage class

يمثل مستند بتنسيق رسالة Outlook يمكن تحليله.

```csharp
public sealed class MapiMessage : MapiMessageItemBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MapiMessage](mapimessage#constructor)() | يقوم بتهيئة مثيل جديد لملف[`MapiMessage`](../mapimessage) فئة . |
| [MapiMessage](mapimessage#constructor_1)(OutlookMessageFormat) | يقوم بتهيئة مثيل جديد لملف[`MapiMessage`](../mapimessage) فئة . |
| [MapiMessage](mapimessage#constructor_2)(string, string, string, string) | يقوم بتهيئة مثيل جديد لملف[`MapiMessage`](../mapimessage) فئة . |
| [MapiMessage](mapimessage#constructor_3)(string, string, string, string, OutlookMessageFormat) | يقوم بتهيئة مثيل جديد لملف[`MapiMessage`](../mapimessage) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | يحصل على المرفقات في الرسالة . |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | يحتوي على معلومات الفواتير المرتبطة بأحد العناصر . |
| [Body](../../aspose.email.mapi/mapimessage/body) { get; set; } | يحصل على نص الرسالة. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | يحصل على ملف[`BodyRtf`](../mapimessageitembase/bodyrtf) من الرسالة محولة إلى HTML ، إن وجدت ، وإلا فسيتم تحويلها إلى سلسلة فارغة. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | الحصول على نص الرسالة المنسقة بتنسيق RTF أو تعيينه. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | يحصل على نوع الجسم. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | يحتوي على كلمات أساسية أو فئات لكائن الرسالة. |
| [ClientSubmitTime](../../aspose.email.mapi/mapimessage/clientsubmittime) { get; set; } | الحصول على أو تحديد التاريخ والوقت أرسل مرسل الرسالة رسالة . |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | الحصول على صفحة الشفرة . |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | يحتوي على أسماء الشركات المرتبطة بأحد العناصر . |
| [ConversationTopic](../../aspose.email.mapi/mapimessage/conversationtopic) { get; } | الحصول على موضوع الرسالة الأولى في سلسلة محادثات. |
| [DeliveryTime](../../aspose.email.mapi/mapimessage/deliverytime) { get; set; } | الحصول على أو تحديد التاريخ والوقت تسليم الرسالة . |
| [DisplayBcc](../../aspose.email.mapi/mapimessage/displaybcc) { get; } | الحصول على قائمة بأسماء العرض لأي مستلمي رسالة نسخة كربونية غير مرئية (BCC) ، مفصولة بفواصل منقوطة (؛) . |
| [DisplayCc](../../aspose.email.mapi/mapimessage/displaycc) { get; } | الحصول على قائمة بأسماء العرض لأي مستلمي رسالة نسخة كربونية (CC) ، مفصولة بفواصل منقوطة (؛) . |
| [DisplayName](../../aspose.email.mapi/mapimessage/displayname) { get; } | يحصل على اسم العرض للرسالة. |
| [DisplayNamePrefix](../../aspose.email.mapi/mapimessage/displaynameprefix) { get; } | الحصول على بادئة لاسم العرض . |
| [DisplayTo](../../aspose.email.mapi/mapimessage/displayto) { get; } | الحصول على قائمة بأسماء العرض لمستلمي الرسالة الأساسيين (إلى) ، مفصولة بفواصل منقوطة (؛). |
| [Flags](../../aspose.email.mapi/mapimessage/flags) { get; } | يحصل على إشارات الرسالة . |
| [Headers](../../aspose.email.mapi/mapimessage/headers) { get; set; } | الحصول على رؤوس رسائل النقل |
| [InternetMessageId](../../aspose.email.mapi/mapimessage/internetmessageid) { get; } | يحصل على معرف الرسالة للرسالة. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | معرّف العنصر يستخدم مع server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | يحصل على سلسلة حساسة لحالة الأحرف تحدد فئة الرسالة المحددة بواسطة المرسل ، مثل IPM.Note. تحدد فئة الرسالة نوع الرسالة أو الغرض منها أو محتواها. |
| [MessageFormat](../../aspose.email.mapi/mapimessage/messageformat) { get; } | الحصول على تنسيق رسالة Outlook . |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | يحتوي على معلومات المسافة المقطوعة بالأميال المرتبطة بأحد العناصر. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | الحصول على الخصائص المسماة للرسالة . |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | الحصول على تعيين الخاصية المسماة. |
| [NormalizedSubject](../../aspose.email.mapi/mapimessage/normalizedsubject) { get; } | الحصول على موضوع الرسالة العادي. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | يحصل على مجموعة الخصائص . |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | يحصل على تدفق الملكية . |
| [ReadReceiptRequested](../../aspose.email.mapi/mapimessage/readreceiptrequested) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان إيصال القراءة مطلوبًا. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | يحصل على مستلمي الرسالة. |
| [ReplyTo](../../aspose.email.mapi/mapimessage/replyto) { get; set; } | الحصول على الرد على الأسماء أو تعيينه . |
| [SenderAddressType](../../aspose.email.mapi/mapimessage/senderaddresstype) { get; } | الحصول على نوع عنوان البريد الإلكتروني لمرسل الرسالة. |
| [SenderEmailAddress](../../aspose.email.mapi/mapimessage/senderemailaddress) { get; set; } | الحصول على أو تعيين عنوان البريد الإلكتروني لمرسل الرسالة. |
| [SenderName](../../aspose.email.mapi/mapimessage/sendername) { get; set; } | الحصول على أو تحديد اسم عرض مرسل الرسالة. |
| [SenderSmtpAddress](../../aspose.email.mapi/mapimessage/sendersmtpaddress) { get; set; } | الحصول على أو تعيين عنوان البريد الإلكتروني لمرسل الرسالة. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | يحصل على الحساسية . |
| [SentRepresentingAddressType](../../aspose.email.mapi/mapimessage/sentrepresentingaddresstype) { get; } | الحصول على نوع العنوان لمستخدم المراسلة الذي يمثله المرسل. |
| [SentRepresentingEmailAddress](../../aspose.email.mapi/mapimessage/sentrepresentingemailaddress) { get; set; } | الحصول على أو تعيين عنوان البريد الإلكتروني لمستخدم المراسلة الذي يمثله المرسل. |
| [SentRepresentingName](../../aspose.email.mapi/mapimessage/sentrepresentingname) { get; set; } | الحصول على أو تحديد اسم العرض لمستخدم المراسلة الذي يمثله المرسل. |
| [SentRepresentingSmtpAddress](../../aspose.email.mapi/mapimessage/sentrepresentingsmtpaddress) { get; } | الحصول على أو تعيين عنوان البريد الإلكتروني لمستخدم المراسلة الذي يمثله المرسل. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | الحصول على أو تحديد موضوع الرسالة. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | الحصول على بادئة موضوع تشير عادةً إلى بعض الإجراءات على رسالة ، مثل "FW:" لإعادة التوجيه. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | يحصل على المخازن الفرعية . |
| [TransportMessageHeaders](../../aspose.email.mapi/mapimessage/transportmessageheaders) { get; } | الحصول على معلومات مغلف الرسالة الخاصة بالنقل. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage)(MailMessage) | إنشاء مثيل لـ MapiMessage من MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_2)(string) | إنشاء مثيل لـ MapiMessage من MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_1)(MailMessage, MapiConversionOptions) | إنشاء مثيل لـ MapiMessage من MailMessage. |
| static [FromProperties](../../aspose.email.mapi/mapimessage/fromproperties)(MapiPropertyCollection) | إنشاء مثيل لـ MapiMessage من مجموعة خصائص Mapi . |
| static [Load](../../aspose.email.mapi/mapimessage/load#load)(Stream) | تحميل الرسالة من تيار . |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_2)(string) | تحميل الرسالة من ملف . |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_1)(Stream, LoadOptions) | تحميل الرسالة من الدفق بخيارات إضافية . |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_3)(string, LoadOptions) | تحميل الرسالة من ملف بخيارات إضافية . |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef)(Stream) | تحميل الرسالة من تنسيق بيانات النقل المحايد (TNEF) هيكل البيانات |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef_1)(string) | تحميل الرسالة من تنسيق بيانات النقل المحايد (TNEF) هيكل البيانات |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty)(MapiProperty, string) | يضيف الخاصية المخصصة . |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty_1)(MapiPropertyType, byte[], string) | يضيف الخاصية المخصصة . |
| [CheckBounced](../../aspose.email.mapi/mapimessage/checkbounced)() | للتحقق مما إذا كان يمكن التعامل مع هذه الرسالة كرسالة مرتدة. |
| [Clone](../../aspose.email.mapi/mapimessage/clone)() | إنشاء كائن جديد يمثل نسخة من المثيل الحالي. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | تنفيذ مهام محددة بواسطة التطبيق مرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| [GetCustomProperties](../../aspose.email.mapi/mapimessage/getcustomproperties)() | الحصول على مجموعة من MapiProperties المخصصة. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | يحصل على خاصية MAPI بواسطة واصف الخاصية. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | يحصل على قيمة الخاصية المحددة بواسطة العلامة كنوع منطقي. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | يحصل على قيمة سلسلة الخاصية المحددة بواسطة العلامة. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | يحصل على قيمة الخاصية المحددة بواسطة العلامة كنوع التاريخ والوقت. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | يحصل على قيمة int32 للخاصية المحددة بواسطة العلامة. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | الحصول على قيمة الخاصية المحددة بواسطة العلامة كنوع طويل (int64) . |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | الحصول على قيمة الخاصية المحددة بواسطة العلامة كنوع قصير. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | يحصل على قيمة سلسلة الخاصية المحددة بواسطة العلامة. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | يحصل على قيمة سلسلة الخاصية المحددة بواسطة العلامة. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | تحديد ما إذا كانت خصائص السلسلة مشفرة بترميز Unicode أم لا. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | يوفر إزالة الخاصية بشكل صحيح من كافة المجموعات. |
| [Save](../../aspose.email.mapi/mapimessage/save#save)(Stream) | يحفظ في التدفق المحدد كـ Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_2)(string) | يحفظ في الملف المحدد كـ Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_1)(Stream, SaveOptions) | يحفظ الرسالة كتدفق مع خيارات إضافية . |
| [Save](../../aspose.email.mapi/mapimessage/save#save_3)(string, SaveOptions) | لحفظ الرسالة كملف بخيارات إضافية. |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate)(Stream) | يحفظ في الدفق المحدد كقالب ملف Outlook (تنسيق OFT) . |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate_1)(string) | يحفظ في الملف المحدد كقالب ملف Outlook (تنسيق OFT) . |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef)(Stream) | حفظ الرسالة بتنسيق TNEF . |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef_1)(string) | حفظ الرسالة بتنسيق TNEF . |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | يحدد محتوى الجسم. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | يحدد محتوى الجسم. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | الحصول على نص الرسالة المنسقة بتنسيق RTF أو تعيينه. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | تعيين أعلام الرسالة . |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | يعين الخاصية . |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | تعيين خاصية MAPI . |
| [SetStringPropertyValue](../../aspose.email.mapi/mapimessage/setstringpropertyvalue)(long, string) | يحدد قيمة خاصية السلسلة . |
| [ToMailMessage](../../aspose.email.mapi/mapimessage/tomailmessage)(MailConversionOptions) | إنشاء مثيل لـ MailMessage من MapiMessage . |
| [ToMapiMessageItem](../../aspose.email.mapi/mapimessage/tomapimessageitem)() | تحويل MapiMessage إلى IMapiMessageItem object بالاعتماد على MessageClass. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | حاول الحصول على بيانات الخاصية باستخدام مفتاح العلامة المحدد. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | الحصول على قيمة الخاصية المحددة كنوع التاريخ والوقت. تشير القيمة المرجعة إلى نجاح العملية. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | الحصول على قيمة الخاصية المحددة كنوع Int32. تشير القيمة المرجعة إلى نجاح العملية. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | الحصول على قيمة الخاصية المحددة كنوع طويل. تشير القيمة المرجعة إلى نجاح العملية. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | حاول الحصول على بيانات خاصية كسلسلة بعلامة محددة. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | حاول الحصول على بيانات خاصية كسلسلة ذات علامة وصفحة رموز محددين . |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | يحصل على قيمة الخاصية المحددة كنوع سلسلة. تشير القيمة المرجعة إلى نجاح العملية. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | يحصل على قيمة الخاصية المحددة كنوع سلسلة. تشير القيمة المرجعة إلى نجاح العملية. |
| static [DestroyAttachments](../../aspose.email.mapi/mapimessage/destroyattachments)(string) | تدمير المرفقات في ملفات رسائل Outlook المحددة. سوف يتجاهل DestroyAttachments تحليل المرفقات. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat)(Stream) | تحديد ما إذا كان الدفق المحدد له تنسيق MSG. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat_1)(string) | لتحديد ما إذا كان الملف المحدد بتنسيق MSG. |
| static [RemoveAttachments](../../aspose.email.mapi/mapimessage/removeattachments)(string) | يزيل كافة المرفقات من ملفات رسائل Outlook المحددة. |

### ملاحظات

تُستخدم مثيلات فئة MapiMessage لتمثيل ملفات مستندات Microsoft Outlook Message التي يتم تحليلها بواسطة فئة MapiMessageReader. للوصول إلى المرسل والمستلم ومحتويات رسالة البريد الإلكتروني ، استخدم الخصائص المرتبطة بفئة MapiMessage.

### أمثلة

يوضح المثال التالي كيفية قراءة ملفات رسائل Outlook.

[C #]

[البصرية الأساسية]

```csharp
// فتح ملفات رسائل Outlook
MapiMessage msg = MapiMessage.FromFile(@"c:\outlookmessage.msg");

/ اقرأ الموضوع
onsole.WriteLine("Subject:" + msg.Subject);

/اسم المرسل
onsole.WriteLine("From:" + msg.SenderName);

/ نص الرسالة
onsole.WriteLine("Body:" + msg.Body);

/ المرفقات
oreach(MapiAttachment att in msg.Attachments)

   Console.WriteLine("Attachment Name:"+att.FileName);
   att.Save(att.FileName);
    
```

```csharp
'افتح ملفات رسائل Outlook 
Dim msg As MapiMessage = MapiMessage.FromFile("c:\outlookmessage.msg") 

'اقرأ الموضوع 
Console.WriteLine("Subject:" + msg.Subject) 

'اسم المرسل 
Console.WriteLine("From:" + msg.SenderName) 

'نص الرسالة 
Console.WriteLine("Body:" + msg.Body) 

'المرفقات 
For Each att As MapiAttachment In msg.Attachments 
    Console.WriteLine("Attachment Name:" + att.FileName) 
    att.Save(att.FileName) 
Next
```

### أنظر أيضا

* class [MapiMessageItemBase](../mapimessageitembase)
* مساحة الاسم [Aspose.Email.Mapi](../../aspose.email.mapi)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
