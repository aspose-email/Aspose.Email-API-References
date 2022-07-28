---
title: ExchangeClient
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: تسمح فئة ExchangeClient للتطبيقات بإدارة صندوق البريد الإلكتروني في Microsoft Exchange Server باستخدام WebDav Exchange Store Protocol.
type: docs
weight: 3150
url: /ar/net/aspose.email.clients.exchange.dav/exchangeclient/
---
## ExchangeClient class

تسمح فئة ExchangeClient للتطبيقات بإدارة صندوق البريد الإلكتروني في Microsoft Exchange Server باستخدام WebDav Exchange Store Protocol.

```csharp
public sealed class ExchangeClient : ExchangeClientBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ExchangeClient](exchangeclient#constructor)(string, ICredentials) | تهيئة مثيل جديد للفئة[`ExchageClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_1)(string, string, string) | تهيئة مثيل جديد للفئة[`ExchageClient`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_2)(string, string, string, string) | تهيئة مثيل جديد للفئة[`ExchageClient`](../exchangeclient) |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ClientCertificate](../../aspose.email.clients.exchange.dav/exchangeclient/clientcertificate) { get; set; } | الحصول على أو تعيين شهادة العميل . |
| [CookieContainer](../../aspose.email.clients.exchange.dav/exchangeclient/cookiecontainer) { get; set; } | الحصول على أو تعيين حاوية ملفات تعريف الارتباط. |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | الحصول على أو تعيين بيانات الاعتماد |
| [Encoding](../../aspose.email.clients.exchange.dav/exchangeclient/encoding) { get; set; } | الحصول على الترميز أو تعيينه . |
| [KeepAlive](../../aspose.email.clients.exchange.dav/exchangeclient/keepalive) { get; set; } | يشير إلى ما إذا كان يجب البقاء على قيد الحياة . |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | الحصول على أو تعيين اسم ملف السجل |
| [MailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/mailboxinfo) { get; } | يحصل على معلومات صندوق البريد. |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | الحصول على علبة البريد أو تعيينها uri |
| [PreAuthenticate](../../aspose.email.clients.exchange.dav/exchangeclient/preauthenticate) { get; set; } | يشير إلى ما إذا كان سيتم إجراء مصادقة مسبقة . |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | الحصول على الوكيل أو تعيينه. |
| [SendChunked](../../aspose.email.clients.exchange.dav/exchangeclient/sendchunked) { get; set; } | الحصول على أو تعيين قيمة تشير إلى [إرسال مقسم] . |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | الحصول على أو تعيين عدد المللي ثانية للانتظار قبل انتهاء مهلة العملية . القيمة الافتراضية هي 100000 مللي ثانية (100 ثانية) . |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | الحصول على القيمة أو تعيينها والتي تشير إلى ما إذا كان يجب استخدام التاريخ في اسم ملف السجل. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage)(string, MailMessage) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage_1)(string, MailMessage, bool) | تحميل رسالة البريد إلى المجلد المحدد |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [CreateContact](../../aspose.email.clients.exchange.dav/exchangeclient/createcontact)(Contact) | إنشاء عنصر جهة اتصال في مخزن Exchange . |
| [CreateFolder](../../aspose.email.clients.exchange.dav/exchangeclient/createfolder)(string, string) | لإنشاء المجلد الجديد بالاسم المحدد في المجلد الأصل المحدد. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_1)(Contact) | حذف جهة الاتصال . |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact)(MapiContact) | حذف جهة الاتصال . |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_2)(string) | حذف جهة الاتصال . |
| [DeleteFolder](../../aspose.email.clients.exchange.dav/exchangeclient/deletefolder)(string) | حذف المجلد |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage)(string) | حذف رسالة البريد . |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage_1)(string, bool) | حذف رسالة البريد . |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | تنفيذ مهام محددة بواسطة التطبيق مرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| [FetchAttachment](../../aspose.email.clients.exchange.dav/exchangeclient/fetchattachment)(string) | يجلب المرفق |
| [FetchMapiMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmapimessage)(string) | يجلب رسالة mapi مع uri المحدد. |
| [FetchMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmessage)(string) | يجلب رسالة البريد باستخدام uri المحدد . |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists)(string, string) | للتحقق مما إذا كان المجلد المحدد موجودًا. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | للتحقق مما إذا كان المجلد المحدد موجودًا. |
| [GetContacts](../../aspose.email.clients.exchange.dav/exchangeclient/getcontacts)(string) | يسرد جهات الاتصال الموجودة في المجلد المحدد على server |
| [GetFolderInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getfolderinfo)(string) | يحصل على معلومات المجلد. |
| [GetMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxes)() | يسرد صناديق البريد في قائمة العناوين العمومية. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo)() | الحصول على معلومات صندوق البريد |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo_1)(string) | يحصل على معلومات صندوق البريد |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize)() | احصل على حجم maibox |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize_1)(string) | احصل على حجم maibox |
| [GetVersionInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getversioninfo)() | إرجاع معلومات إصدار خادم التبادل info |
| [ListContacts](../../aspose.email.clients.exchange.dav/exchangeclient/listcontacts)(string) | يسرد جهات الاتصال الموجودة في المجلد المحدد على server |
| [ListMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/listmailboxes)() | يسرد صناديق البريد في قائمة العناوين العمومية. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages)(string) | يسرد الرسائل . |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_3)(string, bool) | سرد الرسائل في المجلد المحدد |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_1)(string, ExchangeListMessagesOptions) | يسرد رسالة البريد في المجلد المحدد. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_4)(string, int) | يسرد الرسائل . |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_6)(string, string) | يسرد الرسائل . |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_5)(string, int, ExchangeListMessagesOptions) | سرد الرسائل في المجلد المحدد |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_2)(string, MailQuery, bool) | يسرد الرسائل . |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_7)(string, string, bool) | يسرد الرسائل . |
| [ListMessagesById](../../aspose.email.clients.exchange.dav/exchangeclient/listmessagesbyid)(string, string) | يسرد الرسائل حسب المعرف . |
| [ListPublicFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listpublicfolders)() | الحصول على مجموعة من المجلدات العامة من المجلد العام الجذر |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | الحصول على مجموعة من المجلدات العامة التابعة من parent |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders_1)(string) | الحصول على مجموعة من المجلدات الفرعية من parent |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems_1)(string, params string[]) | نقل العناصر . |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems)(string, bool, params string[]) | نقل العناصر . |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage)(ExchangeMessageInfo, string) | لنقل الرسالة . |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_3)(string, string) | لنقل الرسالة . |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_1)(ExchangeMessageInfo, string, bool) | لنقل الرسالة . |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_2)(string, bool, string) | لنقل الرسالة . |
| [ResolveContacts](../../aspose.email.clients.exchange.dav/exchangeclient/resolvecontacts)(string) | يحل أسماء عرض صندوق البريد الغامضة . ملاحظة: الحد الأقصى لعدد جهات الاتصال التي تم إرجاعها هو 100. هذا تقييد لأمر التبادل المستخدم. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_1)(PersonalStorage, RestoreOptions) | يستعيد مجلدات التبادل من وحدة التخزين الشخصية المحددة. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_3)(Stream, RestoreOptions) | يستعيد مجلدات التبادل من وحدة التخزين الشخصية المحددة. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_5)(string, RestoreOptions) | يستعيد مجلدات التبادل من ملف التخزين الشخصي المحدد. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore)(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) | يستعيد مجلدات التبادل المحددة من التخزين الشخصي المحدد. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_2)(Stream, ExchangeFolderInfoCollection, RestoreOptions) | يستعيد مجلدات التبادل المحددة من التخزين الشخصي المحدد. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_4)(string, ExchangeFolderInfoCollection, RestoreOptions) | يستعيد مجلدات التبادل المحددة من ملف التخزين الشخصي المحدد. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage)(string, Stream) | يحفظ الرسالة. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage_1)(string, string) | يحفظ رسالة البريد المحددة بواسطة uri إلى نظام الملفات المحلي. ملف رسالة البريد هو تنسيق متوافق مع RFC 822 (EML) .  إذا كنت تريد تحليل ملفات رسائل البريد ، فاستخدم[`MailMessage`](../../aspose.email/mailmessage). |
| [Send](../../aspose.email.clients.exchange.dav/exchangeclient/send)(MailMessage) | يرسل رسالة البريد . |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag)(string) | وضع علامة على الرسالة المحددة كمقروءة. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag_1)(string, bool) | وضع علامة على الرسالة المحددة كمقروءة. |

### أنظر أيضا

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* مساحة الاسم [Aspose.Email.Clients.Exchange.Dav](../../aspose.email.clients.exchange.dav)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
