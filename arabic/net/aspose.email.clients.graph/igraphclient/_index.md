---
title: IGraphClient
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل واجهة عميل Exchange REST.
type: docs
weight: 15950
url: /ar/net/aspose.email.clients.graph/igraphclient/
---
## IGraphClient interface

يمثل واجهة عميل Exchange REST.

```csharp
public interface IGraphClient : IDisposable
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [MultipleServicesTokenProvider](../../aspose.email.clients.graph/igraphclient/multipleservicestokenprovider) { get; set; } | الحصول على كائن أو تعيينه يسمح باسترداد رمز وصول OAuth. |
| [Proxy](../../aspose.email.clients.graph/igraphclient/proxy) { get; set; } | الحصول على البيانات أو تعيينها للوصول إلى خادم Exchange. |
| [Resource](../../aspose.email.clients.graph/igraphclient/resource) { get; set; } | الحصول على نوع المورد أو تعيينه. |
| [ResourceId](../../aspose.email.clients.graph/igraphclient/resourceid) { get; set; } | الحصول على معرف المورد أو تعيينه . على سبيل المثال ، قد يكون اسم المستخدم الأساسي (UPN) أو معرف المستخدم |
| [TenantId](../../aspose.email.clients.graph/igraphclient/tenantid) { get; set; } | الحصول على أو تعيين معرف المستأجر |
| [Timeout](../../aspose.email.clients.graph/igraphclient/timeout) { get; set; } | الحصول على أو تعيين عدد المللي ثانية للانتظار قبل انتهاء مهلة العملية . القيمة الافتراضية هي 100000 مللي ثانية (100 ثانية) . |
| [TokenProvider](../../aspose.email.clients.graph/igraphclient/tokenprovider) { get; set; } | الحصول على كائن أو تعيينه يسمح باسترداد رمز وصول OAuth. |

## طُرق

| اسم | وصف |
| --- | --- |
| [CopyFolder](../../aspose.email.clients.graph/igraphclient/copyfolder)(string, string) | انسخ مجلد البريد ومحتوياته إلى مجلد بريد آخر. |
| [CopyMessage](../../aspose.email.clients.graph/igraphclient/copymessage)(string, string) | نسخ رسالة إلى مجلد بريد آخر. |
| [CopyNotebook](../../aspose.email.clients.graph/igraphclient/copynotebook)(string, string, string) | نسخ دفتر ملاحظات إلى مجلد دفاتر الملاحظات في مكتبة المستندات الوجهة. يتم إنشاء المجلد إذا لم يكن موجودًا. بالنسبة لعمليات النسخ ، يمكنك اتباع نمط استدعاء غير متزامن: قم أولاً باستدعاء إجراء النسخ ، ثم استقصاء نقطة نهاية العملية للنتيجة. واجهة برمجة التطبيقات هذه . تفويض (حساب العمل أو المدرسة) Notes.Create، Notes.ReadWrite، Notes.ReadWrite.All المفوض (حساب Microsoft الشخصي) |
| [CreateAttachment](../../aspose.email.clients.graph/igraphclient/createattachment)(string, MapiAttachment) | إنشاء مرفق جديد لعنصر محدد |
| [CreateCategory](../../aspose.email.clients.graph/igraphclient/createcategory)(string, CategoryPreset) | ينشئ ملف[`OutlookCategory`](../outlookcategory) الكائن في القائمة الرئيسية للفئات للمستخدم. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder)(string) | إنشاء مجلد جديد. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder_1)(string, string) | إنشاء مجلد جديد. |
| [CreateMessage](../../aspose.email.clients.graph/igraphclient/createmessage)(string, MapiMessage) | إنشاء رسالة في المجلد المحدد |
| [CreateNotebook](../../aspose.email.clients.graph/igraphclient/createnotebook)(Notebook) | إنشاء دفتر ملاحظات OneNote جديد. أذونات مطلوب أحد الأذونات التالية لاستدعاء API هذا. تفويض (حساب العمل أو المدرسة) Notes.Create ، Notes.ReadWrite ، Notes.ReadWrite.All المفوض (حساب Microsoft الشخصي) الملاحظات. إنشاء ، ملاحظات. ReadWrite Application Notes.ReadWrite.All |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride)(ClassificationOverride) | قم بإنشاء تجاوز لمرسل معرف بواسطة عنوان SMTP. سيتم تصنيف الرسائل المستقبلية من عنوان SMTP هذا باستمرار على النحو المحدد في التجاوز . ملاحظة: - إذا كان هناك تجاوز بالفعل بعنوان SMTP نفسه ، فسيتم تحديث حقلي التصنيف والاسم لهذا التجاوز بالقيم المتوفرة. - الحد الأقصى لعدد عمليات التخطي المدعومة لصندوق بريد هو 1000 ، استنادًا إلى عناوين SMTP الفريدة للمرسل. |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride_1)(MailAddress, ClassificationType) | قم بإنشاء تجاوز لمرسل معرف بواسطة عنوان SMTP. سيتم تصنيف الرسائل المستقبلية من عنوان SMTP هذا باستمرار على النحو المحدد في التجاوز . ملاحظة: - إذا كان هناك تجاوز بالفعل بعنوان SMTP نفسه ، فسيتم تحديث حقلي التصنيف والاسم لهذا التجاوز بالقيم المتوفرة. - الحد الأقصى لعدد عمليات التخطي المدعومة لصندوق بريد هو 1000 ، استنادًا إلى عناوين SMTP الفريدة للمرسل. |
| [CreateRule](../../aspose.email.clients.graph/igraphclient/createrule)(InboxRule) | إنشاء قاعدة رسالة من خلال تحديد مجموعة من الشروط والإجراءات. يقوم Outlook بتنفيذ هذه الإجراءات إذا كانت الرسالة الواردة في علبة الوارد للمستخدم تفي بالشروط المحددة. الأذونات: أحد الأذونات التالية مطلوب لاستدعاء واجهة برمجة التطبيقات هذه. تعرف على المزيد ، بما في ذلك كيفية اختيار الأذونات ، راجع الأذونات. |
| [Delete](../../aspose.email.clients.graph/igraphclient/delete)(string) | حذف الكائن . |
| [DeleteAttachment](../../aspose.email.clients.graph/igraphclient/deleteattachment)(string) | يزيل المرفقات |
| [FetchAttachment](../../aspose.email.clients.graph/igraphclient/fetchattachment)(string) | يحصل على المرفق للمعرف المحدد |
| [FetchCategory](../../aspose.email.clients.graph/igraphclient/fetchcategory)(string) | احصل على خصائص وعلاقات كائن outlookCategory المحدد. |
| [FetchMessage](../../aspose.email.clients.graph/igraphclient/fetchmessage)(string) | يحصل على الرسالة بالمعرف المحدد |
| [FetchNotebook](../../aspose.email.clients.graph/igraphclient/fetchnotebook)(string) | استرداد خصائص وعلاقات كائن دفتر ملاحظات . أذونات مطلوب أحد الأذونات التالية لاستدعاء واجهة برمجة التطبيقات هذه. ، Notes.ReadWrite.All تفويض (حساب Microsoft الشخصي) Notes.Create ، Notes.Read ، Notes.ReadWrite Application Notes.Read.All ، Notes.ReadWrite.All |
| [FetchRule](../../aspose.email.clients.graph/igraphclient/fetchrule)(string) | الحصول على خصائص وعلاقات كائن قاعدة الرسالة. أذونات مطلوب أحد الأذونات التالية لاستدعاء واجهة برمجة التطبيقات هذه. لمعرفة المزيد ، بما في ذلك كيفية اختيار الأذونات ، راجع الأذونات. تفويض (حساب العمل أو المدرسة) MailboxSettings.Read المفوضين (حساب Microsoft الشخصي) MailboxSettings.Read إعدادات صندوق بريد التطبيق. |
| [GetFolder](../../aspose.email.clients.graph/igraphclient/getfolder)(string) | يحصل على المجلد بواسطة معرف . |
| [GetOneNoteOperationStatus](../../aspose.email.clients.graph/igraphclient/getonenoteoperationstatus)(string) | الحصول على حالة عملية OneNote طويلة الأمد. ينطبق هذا على العمليات التي تُرجع رأس موقع العملية في الاستجابة ، مثل CopyToSectionGroup و CopyToNotebook و CopyToSectionGroup و CopyToSection . يمكنك استقصاء نقطة نهاية موقع العملية حتى إرجاع خاصية الحالة مكتملة أو فاشلة. إذا اكتملت الحالة ، تحتوي الخاصية ResourceLocation على نقطة نهاية المورد URI. إذا فشلت الحالة ، فإن الخطأ وخصائص @ api.diagnostics توفر معلومات الخطأ. |
| [ListAttachments](../../aspose.email.clients.graph/igraphclient/listattachments)(string) | سرد المرفقات من الرسالة الأصلية. |
| [ListCategories](../../aspose.email.clients.graph/igraphclient/listcategories)() | احصل على جميع الفئات التي تم تحديدها للمستخدم. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders)() | سرد المجلدات من المجلد الأصل للمجلدات التي يتم عرضها في عملاء البريد العادي ، مثل صندوق الوارد. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders_1)(string) | سرد المجلدات من المجلد الأصل للمجلدات التي يتم عرضها في عملاء البريد العادي ، مثل صندوق الوارد. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages_1)(string) | سرد MessageInfo من المجلد الأصل. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages)(string, PageInfo, MailQuery) | سرد MessageInfo من المجلد الأصل. |
| [ListNotebooks](../../aspose.email.clients.graph/igraphclient/listnotebooks)() | استرداد قائمة كائنات دفتر الملاحظات. الأذونات مطلوب أحد الأذونات التالية لاستدعاء واجهة برمجة التطبيقات هذه. ReadWrite.All التفويض (حساب Microsoft الشخصي) Notes.Create، Notes.Read، Notes.ReadWrite Application Notes.Read.All، Notes.ReadWrite.All |
| [ListOverrides](../../aspose.email.clients.graph/igraphclient/listoverrides)() | احصل على الإلغاءات التي قام المستخدم بإعدادها لتصنيف الرسائل دائمًا من مرسلين معينين بطرق محددة . كل تجاوز يتوافق مع عنوان SMTP الخاص بالمرسل. في البداية ، ليس لدى المستخدم أي تجاوزات. الأذونات: أحد الأذونات التالية مطلوبة لاستدعاء واجهة برمجة التطبيقات هذه. لمعرفة المزيد ، بما في ذلك كيفية اختيار الأذونات ، راجع الأذونات . تفويض (حساب العمل أو المدرسة) البريد. |
| [ListRules](../../aspose.email.clients.graph/igraphclient/listrules)() | احصل على جميع كائنات القاعدة المحددة لصندوق الوارد الخاص بالمستخدم. الأذونات مطلوب أحد الأذونات التالية لاستدعاء واجهة برمجة التطبيقات هذه. لمعرفة المزيد ، بما في ذلك كيفية اختيار الأذونات ، راجع الأذونات. المفوضين (حساب Microsoft الشخصي) MailboxSettings.Read إعدادات صندوق بريد التطبيق. |
| [MoveFolder](../../aspose.email.clients.graph/igraphclient/movefolder)(string, string) | نقل مجلد بريد ومحتوياته إلى مجلد بريد آخر. |
| [MoveMessage](../../aspose.email.clients.graph/igraphclient/movemessage)(string, string) | نقل رسالة إلى مجلد بريد آخر. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send)(MapiMessage) | يرسل رسالة بريد إلكتروني |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_2)(string) | أرسل رسالة في مجلد المسودة. يمكن أن تكون مسودة الرسالة مسودة رسالة جديدة أو مسودة رد أو مسودة الرد على الكل أو مسودة إعادة توجيه. يتم حفظ الرسالة بعد ذلك في مجلد العناصر المرسلة. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_1)(MapiMessage, bool) | يرسل رسالة بريد إلكتروني |
| [SetRead](../../aspose.email.clients.graph/igraphclient/setread)(string) | وضع علامة على الرسالة كمقروءة |
| [UpdateCategory](../../aspose.email.clients.graph/igraphclient/updatecategory)(OutlookCategory) | تحديث ثابت اللون المحدد مسبقًا لفئة محددة |
| [UpdateFolder](../../aspose.email.clients.graph/igraphclient/updatefolder)(FolderInfo) | مجلد التحديثات . |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage)(MapiMessage) | رسالة التحديثات |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage_1)(MapiMessage, UpdateSettings) | رسالة التحديثات |
| [UpdateOverride](../../aspose.email.clients.graph/igraphclient/updateoverride)(ClassificationOverride) | تغيير حقل classifyAs للتجاوز كما هو محدد . لا يمكنك استخدام هذه الطريقة لتغيير أي حقول أخرى في مثيل ClassificationOverride . في حالة وجود تجاوز لمرسل وقام المرسل بتغيير اسم العرض الخاص به ، يمكنك استخدام CreateOrUpdateOverride إلى فرض تحديث حقل الاسم في التجاوز الحالي . إذا كان هناك تجاوز لمرسل وقام المرسل بتغيير عنوان SMTP الخاص به ، فإن حذف التجاوز الحالي وإنشاء عنوان جديد باستخدام عنوان SMTP الجديد هو الطريقة الوحيدة "تحديث" تجاوز هذا المرسل. الأذونات: أحد الأذونات التالية مطلوب لاستدعاء واجهة برمجة التطبيقات هذه. لمعرفة المزيد ، بما في ذلك كيفية اختيار الأذونات ، راجع الأذونات. تفويض (حساب العمل أو المدرسة) البريد. (حساب Microsoft الشخصي) Mail.ReadWrite Application Mail.ReadWrite |
| [UpdateRule](../../aspose.email.clients.graph/igraphclient/updaterule)(InboxRule) | تغيير الخصائص القابلة للكتابة في كائن messageRule وحفظ التغييرات. أذونات مطلوب أحد الأذونات التالية لاستدعاء API. لمعرفة المزيد ، بما في ذلك كيفية اختيار الأذونات ، راجع الأذونات . تفويض (حساب العمل أو المدرسة) MailboxSettings. ReadWrite التفويض (حساب Microsoft الشخصي) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
