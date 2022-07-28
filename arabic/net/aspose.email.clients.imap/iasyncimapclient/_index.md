---
title: IAsyncImapClient
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: للسماح للتطبيقات بالوصول إلى الرسائل ومعالجتها باستخدام بروتوكول الوصول إلى الرسائل عبر الإنترنت IMAP .
type: docs
weight: 16240
url: /ar/net/aspose.email.clients.imap/iasyncimapclient/
---
## IAsyncImapClient interface

للسماح للتطبيقات بالوصول إلى الرسائل ومعالجتها باستخدام بروتوكول الوصول إلى الرسائل عبر الإنترنت (IMAP) .

```csharp
public interface IAsyncImapClient
```

## طُرق

| اسم | وصف |
| --- | --- |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/addmessageflagsasync)(ImapChangeMessageFlags) | يضيف الإشارات إلى الرسالة |
| [AppendMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessageasync)(MailMessage, string, IConnection, CancellationToken) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/appendmessagesasync)(IEnumerable&lt;MailMessage&gt;, string, IConnection, CancellationToken) | تحميل رسائل البريد إلى المجلد الحالي |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync)(ImapFolderInfoCollection, Stream, BackupSettings, IConnection, CancellationToken) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [BackupAsync](../../aspose.email.clients.imap/iasyncimapclient/backupasync#backupasync_1)(ImapFolderInfoCollection, string, BackupSettings, IConnection, CancellationToken) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/changemessageflagsasync)(ImapChangeMessageFlags) | يغير أعلام الرسالة |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/iasyncimapclient/clientcapabilitiesasync)(IEnumerable&lt;string&gt;, IConnection, CancellationToken) | لإعلام الخادم بالملحقات التي يدعمها العميل . يرجى ملاحظة أن هذه العملية تعمل فقط في حالة إذا كان الخادم يدعم RFC5161 انظر المزيد https://tools.ietf.org/html/rfc5161 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/iasyncimapclient/commitdeletesasync)(ImapUniqueIdParameterSet) | تنفيذ عمليات الحذف |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync)(int, string, IConnection, CancellationToken) | نسخ الرسالة |
| [CopyMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessageasync#copymessageasync_1)(string, string, IConnection, CancellationToken) | نسخ الرسالة . |
| [CopyMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/copymessagesasync)(ImapCopyMessages) | انسخ الرسائل . |
| [CreateFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/createfolderasync)(string, IConnection, CancellationToken) | إنشاء مجلد بالاسم المحدد . |
| [DeleteFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/deletefolderasync)(string, IConnection, CancellationToken) | حذف مجلد محدد. تمثل هذه الطريقة أمر IMAP DELETE. |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/deletemessagesasync)(ImapDeleteMessages) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [ExistFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/existfolderasync)(string, IConnection, CancellationToken) | تحقق مما إذا كان هذا المجلد موجودًا |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchattachmentasync)(int, string, IConnection, CancellationToken) | يجلب المرفق المحدد . |
| [FetchMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/fetchmessagesasync)(ImapFetchMessages) | جلب الرسائل بشكل غير متزامن |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/iasyncimapclient/getfolderinfoasync)(string, IConnection, CancellationToken) | إرجاع معلومات حول المجلد المحدد بدون تحديده |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/getmessagethreadsasync)(BaseSearchConditions, IConnection, CancellationToken) | الحصول على سلاسل الرسائل . |
| [GetNamespacesAsync](../../aspose.email.clients.imap/iasyncimapclient/getnamespacesasync)(IConnection, CancellationToken) | يحصل على مساحات الأسماء المتاحة على الخادم. |
| [GetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotaasync)(string, IConnection, CancellationToken) | يحصل على معلومات الحصة |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/iasyncimapclient/getquotarootasync)(string, IConnection, CancellationToken) | الحصول على معلومات جذر الحصة النسبية لـ mailbox |
| [IntroduceClientAsync](../../aspose.email.clients.imap/iasyncimapclient/introduceclientasync)(ImapIdentificationInfo, IConnection, CancellationToken) | يقدم معلومات العميل إلى الخادم. |
| [ListFoldersAsync](../../aspose.email.clients.imap/iasyncimapclient/listfoldersasync)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, IConnection, CancellationToken) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync)(int, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessageasync#listmessageasync_1)(string, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | الحصول على معلومات حول الرسالة . |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync)(MailQuery, string, int, IConnection, CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesasync#listmessagesasync_1)(string, long, bool, IEnumerable&lt;string&gt;, IConnection, CancellationToken) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync_1)(int, int, PageSettings, CancellationToken) | يحصل على قائمة الرسائل |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync#listmessagesbypageasync)(MailQuery, PageInfo, PageSettings, CancellationToken) | يحصل على قائمة الرسائل |
| [MoveFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/movefolderasync)(string, string, IConnection, CancellationToken) | نقل المجلد المحدد ومجلداته الفرعية إلى موقع جديد. |
| [MoveMessagesAsync](../../aspose.email.clients.imap/iasyncimapclient/movemessagesasync)(ImapMoveMessages) | لنقل الرسائل . |
| [NoopAsync](../../aspose.email.clients.imap/iasyncimapclient/noopasync)(IConnection, CancellationToken) | "بدون عملية" command |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/iasyncimapclient/removemessageflagsasync)(ImapChangeMessageFlags) | يزيل إشارات الرسالة |
| [RenameFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/renamefolderasync)(string, string, IConnection, CancellationToken) | إعادة تسمية مجلد محدد باسم جديد |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/iasyncimapclient/requestcheckpointasync)(IConnection, CancellationToken) | يطلب نقطة فحص لصندوق البريد المحدد حاليًا. |
| [RestoreAsync](../../aspose.email.clients.imap/iasyncimapclient/restoreasync)(PersonalStorage, RestoreSettings, CancellationToken) | يبدأ في استعادة مجلدات imap من وحدة التخزين الشخصية المحددة. |
| [ResumeMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState, CancellationToken) | يستأنف مراقبة تغييرات الرسائل للمجلد المحدد. على عكس طريقة StartMonitoring ، فإنه سيجد جميع التغييرات المفقودة في صندوق البريد ويستدعى رد الاتصال الخاص بهم . |
| [SelectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/selectfolderasync)(string, bool?, IConnection, CancellationToken) | تحديد المجلد المحدد |
| [SetQuotaAsync](../../aspose.email.clients.imap/iasyncimapclient/setquotaasync)(string, string, int, IConnection, CancellationToken) | تعيين معلومات الحصة |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/iasyncimapclient/sortmessagethreadsasync)(SortConditions, IConnection, CancellationToken) | فرز رسائل الرسائل . |
| [StartMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/startmonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | يبدأ في مراقبة تغييرات الرسائل للمجلد المحدد. |
| [StopMonitoringAsync](../../aspose.email.clients.imap/iasyncimapclient/stopmonitoringasync)(string, CancellationToken) | يوقف مراقبة تغييرات الرسائل للمجلد المحدد. يوقف مراقبة جميع المجلدات إذا كان اسم المجلد فارغًا. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/subscribefolderasync)(string, IConnection, CancellationToken) | أرسل أمر الاشتراك الذي يضيف اسم صندوق البريد المحدد إلى مجموعة صناديق البريد "النشطة" الخاصة بالخادم. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync)(int, long, IConnection, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/iasyncimapclient/undeletemessageasync#undeletemessageasync_1)(string, long, IConnection, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unselectfolderasync)(bool, IConnection, CancellationToken) | إلغاء تحديد المجلد المحدد حاليًا. إذا كانت خاصية doNotExpunge صحيحة ، فسيتم وضع علامة على جميع الرسائل على أنها محذوفة ، وإلا تم إلغاء الحذف. ietf.org/html/rfc3691 |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/iasyncimapclient/unsubscribefolderasync)(string, IConnection, CancellationToken) | أرسل الأمر UNSUBSCRIBE الذي يزيل اسم صندوق البريد المحدد من مجموعة علب البريد "النشطة" على الخادم |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/iasyncimapclient/validatecredentialsasync)(IConnection, CancellationToken) | تنفيذ التحقق من صحة بيانات الاعتماد |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
