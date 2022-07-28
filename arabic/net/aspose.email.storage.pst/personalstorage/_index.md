---
title: PersonalStorage
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل ملف جدول التخزين الشخصي .pst.
type: docs
weight: 20290
url: /ar/net/aspose.email.storage.pst/personalstorage/
---
## PersonalStorage class

يمثل ملف جدول التخزين الشخصي (.pst).

```csharp
public class PersonalStorage : IDisposable
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PersonalStorage](personalstorage)(TraversalExceptionsCallback) | يقوم بتهيئة مثيل جديد لملف[`PersonalStorage`](../personalstorage) class. يسمح بتعيين طريقة رد اتصال لمعالجة الاستثناءات التي تحدث أثناء اجتياز PST. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CanWrite](../../aspose.email.storage.pst/personalstorage/canwrite) { get; } | يحصل على قيمة تشير إلى ما إذا كان pst الحالي يدعم الكتابة. |
| [Format](../../aspose.email.storage.pst/personalstorage/format) { get; } | يحصل على تنسيق الملف. |
| [IsUnicode](../../aspose.email.storage.pst/personalstorage/isunicode) { get; } | يحصل على قيمة تشير إلى ما إذا كان تنسيق ملف PST هو Unicode . يوجد إصداران من تنسيق ملف PST: Unicode و ANSI. |
| [RootFolder](../../aspose.email.storage.pst/personalstorage/rootfolder) { get; } | يحصل على المجلد الجذر لـ PST . |
| [Store](../../aspose.email.storage.pst/personalstorage/store) { get; } | يحصل على مخزن رسائل PST. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create)(Stream, FileFormatVersion) | ينشئ PST في دفق . |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_4)(string, FileFormatVersion) | ينشئ ملف PST الجديد باسم الملف المحدد. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_1)(Stream, FileFormatVersion, bool) | ينشئ PST في دفق . |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_3)(Stream, FileFormatVersion, CancellationToken) | ينشئ PST في دفق . |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_5)(string, FileFormatVersion, CancellationToken) | ينشئ ملف PST الجديد باسم الملف المحدد. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_2)(Stream, FileFormatVersion, bool, CancellationToken) | ينشئ PST في دفق . |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile)(string) | تحميل PST من ملف . |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_3)(string, bool) | تحميل PST من ملف . |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_5)(string, CancellationToken) | تحميل PST من ملف . |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_1)(string, PersonalStorageLoadOptions) | تحميل PST من ملف . |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_4)(string, bool, CancellationToken) |  |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_2)(string, PersonalStorageLoadOptions, CancellationToken) | تحميل PST من ملف . |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream)(Stream) | تحميل PST من الدفق. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_3)(Stream, bool) | تحميل PST من الدفق. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_5)(Stream, CancellationToken) | تحميل PST من ملف . |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_1)(Stream, PersonalStorageLoadOptions) | تحميل PST من الدفق. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_4)(Stream, bool, CancellationToken) |  |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_2)(Stream, PersonalStorageLoadOptions, CancellationToken) | تحميل PST من ملف . |
| [ChangeMessage](../../aspose.email.storage.pst/personalstorage/changemessage)(string, MapiPropertyCollection) | يغير خصائص الرسالة . |
| [ConvertTo](../../aspose.email.storage.pst/personalstorage/convertto)(FileFormat) | تحويل الكائن الحالي إلى التنسيق المحدد. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder)(string, StandardIpmFolder) | لإنشاء مجلد الرسائل الشخصية القياسية (IPM) . |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder_1)(string, StandardIpmFolder, bool) | لإنشاء مجلد الرسائل الشخصية القياسية (IPM) . |
| [Dispose](../../aspose.email.storage.pst/personalstorage/dispose)() | تنفيذ مهام محددة بواسطة التطبيق مرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages)(string) | يعرض العداد الذي يدعم تكرار الرسائل في المجلد. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages_1)(string, int, int) | يعرض العداد الذي يدعم تكرار الرسائل في المجلد. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments)(MessageInfo) | استخراج المرفقات. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments_1)(string) | استخراج المرفقات. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_1)(byte[]) | احصل على الرسالة من PST . |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage)(MessageInfo) | احصل على الرسالة من PST . |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_2)(string) | احصل على الرسالة من PST . |
| [ExtractProperty](../../aspose.email.storage.pst/personalstorage/extractproperty)(byte[], long) | الحصول على الخاصية المحددة للعنصر ، بدون استخراج العنصر بالكامل. |
| [FindMessages](../../aspose.email.storage.pst/personalstorage/findmessages)(string) | البحث عن معرفات الرسائل للمجلد الحالي. قد يكون مفيدًا في حالة قراءة pst التالفة عندما يمكن أن تؤدي أساليب GetContents و EnumerateMessages إلى استثناء. |
| [FindSubfolders](../../aspose.email.storage.pst/personalstorage/findsubfolders)(string) | البحث عن معرفات المجلدات الفرعية للمجلد الحالي. قد يكون مفيدًا في حالة قراءة pst التالف عندما يمكن أن تطرح أساليب GetSubfolders و EnumerateFolders استثناءً. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid)(byte[]) | يحصل على المجلد الشخصي من PST . |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid_1)(string) | يحصل على المجلد الشخصي من PST . |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder)(byte[]) | يحصل على المجلد الأصل للرسالة . |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder_1)(string) | يحصل على المجلد الأصل للرسالة . |
| [GetPredefinedFolder](../../aspose.email.storage.pst/personalstorage/getpredefinedfolder)(StandardIpmFolder) | الحصول على مجلد الرسائل الشخصية القياسية (IPM) من PST. يمكن لبرنامج Outlook إنشاء عدد من المجلدات الافتراضية ، مثل صندوق الصادر والعناصر المحذوفة والعناصر المرسلة وما إلى ذلك. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load)(Stream) | تحميل PST من الدفق. يتم استخدام هذه الطريقة عند إنشاء كائن PersonalStorage باستخدام المُنشئ. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load_1)(string) | تحميل PST من ملف. يتم استخدام هذه الطريقة عند إنشاء كائن PersonalStorage باستخدام المُنشئ. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith)(Stream[]) | يدمج تخزين pst مع واحد أو أكثر من تدفقات pst الأخرى . وبالتالي ، فإن الدفق المدمج عبارة عن مصادر. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith_1)(string[]) | يدمج تخزين pst مع واحد أو أكثر من ملفات pst . وبالتالي ، فإن الملفات المدمجة هي مصادر . |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem)(FolderInfo, FolderInfo) | نقل مجلد محدد إلى مجلد أصل جديد ضمن pst الحالي. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem_1)(MessageInfo, FolderInfo) | لنقل رسالة محددة إلى مجلد جديد ضمن pst الحالي. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas)(Stream, FileFormat) | يحفظ الكائن الحالي بتنسيق ملف محدد في تدفق . |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas_1)(string, FileFormat) | يحفظ الكائن الحالي بتنسيق ملف محدد في ملف مختلف. |
| [SaveMessageToStream](../../aspose.email.storage.pst/personalstorage/savemessagetostream)(string, Stream) | يحفظ الرسالة ، مع معرف الإدخال المحدد ، في تيار . |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto_1)(IList&lt;MailQuery&gt;, string) | يقسم تخزين pst بناءً على المعايير . |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto)(long, string) | يقسم تخزين pst إلى أجزاء أقل حجمًا. |
| [TryToGetFolderById](../../aspose.email.storage.pst/personalstorage/trytogetfolderbyid)(string, out FolderInfo) | يحصل على المجلد المرتبط بمعرف الإدخال المحدد. |
| [TryToSaveMessage](../../aspose.email.storage.pst/personalstorage/trytosavemessage)(string, Stream) | يحفظ الرسالة ، مع معرف الإدخال المحدد ، في تيار . |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
