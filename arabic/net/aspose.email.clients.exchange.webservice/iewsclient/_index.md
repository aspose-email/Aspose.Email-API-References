---
title: IEWSClient
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل واجهة عميل Exchange .
type: docs
weight: 3960
url: /ar/net/aspose.email.clients.exchange.webservice/iewsclient/
---
## IEWSClient interface

يمثل واجهة عميل Exchange .

```csharp
public interface IEWSClient : IExchangeClientBase
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [CalendarFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/calendarfoldereventfilter) { get; set; } | تحديد أنواع الأحداث لمجلد التقويم |
| [ContactsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/contactsfoldereventfilter) { get; set; } | تحديد أنواع الأحداث لمجلد جهات الاتصال |
| [CurrentCalendarFolderUri](../../aspose.email.clients.exchange.webservice/iewsclient/currentcalendarfolderuri) { get; set; } | الحصول على مجلد التقويم الحالي أو تعيينه uri |
| [DeletedItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/deleteditemsfoldereventfilter) { get; set; } | تحديد أنواع الأحداث لـ DeletedItems folder |
| [DraftsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/draftsfoldereventfilter) { get; set; } | تحديد أنواع الأحداث لمجلد المسودات |
| [EnableDecompression](../../aspose.email.clients.exchange.webservice/iewsclient/enabledecompression) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان إلغاء الضغط ممكّنًا |
| [Headers](../../aspose.email.clients.exchange.webservice/iewsclient/headers) { get; } | الحصول على مصفوفة من أزواج قيم الاسم التي تمت إضافتها إلى WebHeaderCollection في طلب EWS. |
| [InboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/inboxfoldereventfilter) { get; set; } | تحديد أنواع الأحداث لمجلد علبة الوارد |
| [JournalFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/journalfoldereventfilter) { get; set; } | تحديد أنواع الأحداث لمجلد دفتر اليومية |
| [MailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/mailboxinfo) { get; } | يحصل على معلومات صندوق البريد. |
| [NotesFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/notesfoldereventfilter) { get; set; } | تحديد أنواع الأحداث لمجلد Notes |
| [NotificationsCheckInterval](../../aspose.email.clients.exchange.webservice/iewsclient/notificationscheckinterval) { get; set; } | يحدد الفاصل الزمني لفحص الإخطار |
| [NotificationTimeout](../../aspose.email.clients.exchange.webservice/iewsclient/notificationtimeout) { get; set; } | يحدد مهلة إشعارات الخادم |
| [OutboxFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/outboxfoldereventfilter) { get; set; } | تحديد أنواع الأحداث لمجلد علبة الصادر |
| [ReconnectCount](../../aspose.email.clients.exchange.webservice/iewsclient/reconnectcount) { get; set; } | الحصول على أو تعيين عدد محاولات إعادة الاتصال عند انقطاع الاتصال. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange.webservice/iewsclient/returnclientrequestid) { get; set; } | الحصول على علامة أو تعيينها للإشارة إلى ما إذا كان العميل يتطلب من جانب الخادم إعادة معرف الطلب. |
| [RootFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/rootfoldereventfilter) { get; set; } | تحديد أنواع الأحداث للمجلد الجذر |
| [SentItemsFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/sentitemsfoldereventfilter) { get; set; } | تحديد أنواع الأحداث لمجلد العناصر المرسلة |
| [ServerVersion](../../aspose.email.clients.exchange.webservice/iewsclient/serverversion) { get; } | الحصول على معلومات حول الإصدار الحالي من MS Exchange . |
| [TasksFolderEventFilter](../../aspose.email.clients.exchange.webservice/iewsclient/tasksfoldereventfilter) { get; set; } | تحديد أنواع الأحداث لمجلد المهام |
| [TimezoneId](../../aspose.email.clients.exchange.webservice/iewsclient/timezoneid) { get; set; } | الحصول على أو تحديد المنطقة الزمنية id |
| [UseSlashAsFolderSeparator](../../aspose.email.clients.exchange.webservice/iewsclient/useslashasfolderseparator) { get; set; } | الحصول على أو تعيين القيمة التي تحدد ما إذا كانت الشرطة المائلة '/' تستخدم كفاصل مجلد. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddHeader](../../aspose.email.clients.exchange.webservice/iewsclient/addheader)(string, string) | إضافة اسم وقيمة إلى WebHeaderCollection في طلب EWS . |
| [AddToDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/addtodistributionlist)(ExchangeDistributionList, MailAddressCollection) | إلحاق الأعضاء بقائمة التوزيع. |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage)(MailMessage) | تحميل رسالة البريد إلى مجلد علبة الوارد |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_1)(MapiMessage) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_2)(MapiMessage, bool) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_3)(string, MailMessage) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessage](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessage#appendmessage_5)(string, MapiMessage, bool) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_1)(IEnumerable&lt;MailMessage&gt;) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages)(params MailMessage[]) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_3)(string, IEnumerable&lt;MailMessage&gt;) | تحميل رسائل البريد إلى المجلد المحدد |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_4)(string, IEnumerable&lt;MapiMessage&gt;) | تحميل رسائل mapi إلى المجلد المحدد |
| [AppendMessages](../../aspose.email.clients.exchange.webservice/iewsclient/appendmessages#appendmessages_2)(string, params MailMessage[]) | تحميل رسالة البريد إلى المجلد المحدد |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem)(string, Appointment) | تنقل عملية ArchiveItem عنصرًا إلى صندوق بريد أرشيف مستخدم صندوق البريد. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_1)(string, ExchangeTask) | تنقل عملية ArchiveItem عنصرًا إلى صندوق بريد أرشيف مستخدم صندوق البريد. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_2)(string, MapiMessageItemBase) | تنقل عملية ArchiveItem عنصرًا إلى صندوق بريد أرشيف مستخدم صندوق البريد. |
| [ArchiveItem](../../aspose.email.clients.exchange.webservice/iewsclient/archiveitem#archiveitem_3)(string, string) | تنقل عملية ArchiveItem عنصرًا إلى صندوق بريد أرشيف مستخدم صندوق البريد. |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [Backup](../../aspose.email.clients.exchange.webservice/iewsclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment)(Appointment) | إلغاء الموعد . |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_2)(MapiCalendar) | إلغاء الموعد . |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_4)(string) | إلغاء اجتماع مغلق في تقويم منظمي |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_1)(Appointment, string) | إلغاء الموعد . |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_3)(MapiCalendar, string) | إلغاء الموعد . |
| [CancelAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/cancelappointment#cancelappointment_5)(string, string) | إلغاء اجتماع مغلق في تقويم منظمي |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability#checkuseravailability)(string, DateRange) | يتحقق من توفر المستخدم خلال النافذة الزمنية المحددة. |
| [CheckUserAvailability](../../aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability#checkuseravailability_1)(StringCollection, DateRange) | يتحقق من توفر المستخدمين خلال النافذة الزمنية المحددة. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_1)(ExchangeDelegateUser, string) | يغلق الوصول إلى صندوق البريد المحدد للمستخدم المحدد. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_2)(ExchangeDelegateUserCollection, string) | يغلق الوصول إلى صندوق البريد المحدد للمستخدم المحدد. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess)(ExchangeFolderUserInfo, string) | يغلق الوصول إلى صندوق البريد المحدد للمستخدم المحدد. |
| [CloseAccess](../../aspose.email.clients.exchange.webservice/iewsclient/closeaccess#closeaccess_3)(string, string) | يغلق الوصول إلى صندوق البريد المحدد للمستخدم المحدد. |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems#copyconversationitems)(string, string) | نسخ عناصر المحادثة في المجلد الهدف المحدد |
| [CopyConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/copyconversationitems#copyconversationitems_1)(string, string, string) | نسخ عناصر المحادثة الموجودة في المجلد المحدد إلى المجلد الهدف المحدد |
| [CopyItem](../../aspose.email.clients.exchange.webservice/iewsclient/copyitem)(string, string) | نسخ العنصر إلى المجلد المحدد |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment)(Appointment) | إنشاء موعد . |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment_1)(Appointment, string) | إنشاء موعد . |
| [CreateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/createappointment#createappointment_4)(MapiCalendar, string, bool) | إنشاء موعد . |
| [CreateCalendarSharingInvitationMessage](../../aspose.email.clients.exchange.webservice/iewsclient/createcalendarsharinginvitationmessage)(string) | إنشاء رسالة دعوة مشاركة التقويم . |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact#createcontact_1)(Contact) | إنشاء عنصر جهة اتصال في مخزن Exchange . |
| [CreateContact](../../aspose.email.clients.exchange.webservice/iewsclient/createcontact#createcontact_3)(string, Contact) | إنشاء عنصر جهة اتصال في المجلد المحدد. |
| [CreateDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/createdistributionlist)(ExchangeDistributionList, MailAddressCollection) | إنشاء قائمة التوزيع الخاصة . |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder)(string) | إنشاء مجلد جديد في المجلد الجذر. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_1)(string, ExchangeFolderType) | إنشاء مجلد جديد في المجلد الجذر. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_2)(string, string) | لإنشاء المجلد الجديد بالاسم المحدد في المجلد الأصل المحدد. |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_3)(string, string, ExchangeFolderPermissionCollection) | ينشئ المجلد الجديد |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_5)(string, string, ExchangeFolderType) | ينشئ المجلد الجديد |
| [CreateFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createfolder#createfolder_4)(string, string, ExchangeFolderPermissionCollection, string) | ينشئ المجلد الجديد |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule#createinboxrule)(InboxRule) | إنشاء قاعدة البريد الوارد المحددة |
| [CreateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/createinboxrule#createinboxrule_1)(InboxRule, string) | إنشاء قاعدة البريد الوارد المحددة |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem#createitem)(MapiMessageItemBase) | إنشاء العنصر المحدد في مجلد العنصر الافتراضي. |
| [CreateItem](../../aspose.email.clients.exchange.webservice/iewsclient/createitem#createitem_1)(string, MapiMessageItemBase) | إنشاء العنصر المحدد في المجلد المحدد . |
| [CreateItems](../../aspose.email.clients.exchange.webservice/iewsclient/createitems)(ExchangeStreamedItem[], string) | إنشاء العناصر المحددة في المجلد المحدد |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder)(string, ExchangeFolderPermissionCollection) | إنشاء المجلد العام المحدد في المجلد العام الجذر |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder_1)(string, ExchangeFolderPermissionCollection, ExchangeFolderType) | إنشاء المجلد العام المحدد في المجلد العام الجذر |
| [CreatePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/createpublicfolder#createpublicfolder_2)(string, string, ExchangeFolderPermissionCollection) | إنشاء المجلد العام المحدد في المجلد العام الجذر |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask#createtask)(ExchangeTask) | لإنشاء المهمة المحددة في مجلد المهام الافتراضي. |
| [CreateTask](../../aspose.email.clients.exchange.webservice/iewsclient/createtask#createtask_2)(string, ExchangeTask) | لإنشاء المهمة المحددة في المجلد المحدد . |
| [CreateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/createuserconfiguration)(UserConfiguration) | إنشاء تكوين المستخدم المحدد |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess)(ExchangeDelegateUser, string) | تفويض الوصول إلى صندوق البريد المحدد للمستخدم المحدد. |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess_1)(ExchangeDelegateUserCollection, string) | تفويض الوصول إلى صندوق البريد للمستخدمين المحددين. |
| [DelegateAccess](../../aspose.email.clients.exchange.webservice/iewsclient/delegateaccess#delegateaccess_2)(string, ExchangeDelegateFolderPermissionLevel, string) | تفويض الوصول إلى صندوق البريد الرئيسي للمستخدم المحدد. |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems#deleteconversationitems)(string) | حذف كافة عناصر المحادثة المحددة |
| [DeleteConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteconversationitems#deleteconversationitems_1)(string, string) | حذف عناصر المحادثة الموجودة في المجلد المحدد |
| [DeleteDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletedistributionlist)(ExchangeDistributionList, bool) | حذف قائمة التوزيع . |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder#deletefolder)(string) | حذف المجلد |
| [DeleteFolder](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolder#deletefolder_1)(string, bool) | حذف المجلد |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders)(ExchangeFolderInfoCollection) | حذف المجلدات المحددة |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_2)(StringCollection) | حذف المجلدات المحددة |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_1)(ExchangeFolderInfoCollection, bool) | حذف المجلدات المحددة |
| [DeleteFolders](../../aspose.email.clients.exchange.webservice/iewsclient/deletefolders#deletefolders_3)(StringCollection, bool) | حذف المجلد |
| [DeleteFromDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/deletefromdistributionlist)(ExchangeDistributionList, MailAddressCollection) | حذف الأعضاء من قائمة التوزيع . |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule#deleteinboxrule)(string) | حذف قاعدة علبة الوارد المحددة |
| [DeleteInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule#deleteinboxrule_1)(string, string) | حذف قاعدة علبة الوارد المحددة |
| [DeleteItem](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitem)(string, DeletionOptions) | حذف عنصر محدد |
| [DeleteItems](../../aspose.email.clients.exchange.webservice/iewsclient/deleteitems)(IEnumerable&lt;string&gt;, DeletionOptions) | حذف العناصر المحددة |
| [DeleteUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/deleteuserconfiguration)(UserConfigurationName) | حذف تكوين المستخدم المحدد |
| [DisconnectPhoneCall](../../aspose.email.clients.exchange.webservice/iewsclient/disconnectphonecall)(string) | قطع الاتصال بمكالمة هاتفية محددة بواسطة المعرف . |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder#emptyfolder)(string) | يفرغ المجلد المحدد. لن يتم حذف المجلدات الفرعية ؛ سيتم نقل العناصر المحذوفة إلى مجلد العناصر المحذوفة |
| [EmptyFolder](../../aspose.email.clients.exchange.webservice/iewsclient/emptyfolder#emptyfolder_1)(string, EmptyFolderOptions) | يفرغ المجلد المحدد |
| [ExpandDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/expanddistributionlist)(MailAddress) | لتوسيع أعضاء قائمة التوزيع العامة . |
| [ExportItems](../../aspose.email.clients.exchange.webservice/iewsclient/exportitems)(params string[]) | تصدير العناصر المحددة من mailbox |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment#fetchappointment)(string) | إحضار الموعد المحدد من الخادم . |
| [FetchAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchappointment#fetchappointment_1)(string, string) | إحضار الموعد المحدد من الخادم . |
| [FetchAttachment](../../aspose.email.clients.exchange.webservice/iewsclient/fetchattachment)(string) | يجلب المرفق |
| [FetchConversationMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchconversationmessages)(string) | يجلب رسائل المحادثة المحددة |
| [FetchDistributionList](../../aspose.email.clients.exchange.webservice/iewsclient/fetchdistributionlist)(ExchangeDistributionList) | جلب أعضاء قائمة التوزيع الخاصة. |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem#fetchitem)(string) | استرداد العنصر بتنسيق[`MapiMessage`](../../aspose.email.mapi/mapimessage) . |
| [FetchItem](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitem#fetchitem_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | استرداد العنصر بتنسيق[`MapiMessage`](../../aspose.email.mapi/mapimessage) . |
| [FetchItems](../../aspose.email.clients.exchange.webservice/iewsclient/fetchitems)(EwsFetchItems) | استرداد العناصر. |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar#fetchmapicalendar)(IEnumerable&lt;string&gt;) | إحضار مجموعة من[`MapiCalendar`](../../aspose.email.mapi/mapicalendar) الكائنات . |
| [FetchMapiCalendar](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapicalendar#fetchmapicalendar_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | إحضار مجموعة من[`MapiCalendar`](../../aspose.email.mapi/mapicalendar) الكائنات . |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages#fetchmapimessages)(IEnumerable&lt;string&gt;) | جلب الرسائل المحددة |
| [FetchMapiMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages#fetchmapimessages_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | جلب الرسائل المحددة |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes#fetchmapinotes)(IEnumerable&lt;string&gt;) | إحضار مجموعة من[`MapiNote`](../../aspose.email.mapi/mapinote) الكائنات . |
| [FetchMapiNotes](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapinotes#fetchmapinotes_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | إحضار مجموعة من[`MapiNote`](../../aspose.email.mapi/mapinote) الكائنات . |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks#fetchmapitasks)(IEnumerable&lt;string&gt;) | إحضار مجموعة من[`MapiTask`](../../aspose.email.mapi/mapitask) الكائنات . |
| [FetchMapiTasks](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmapitasks#fetchmapitasks_1)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | إحضار مجموعة من[`MapiTask`](../../aspose.email.mapi/mapitask) الكائنات . |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage#fetchmessage)(string) | يجلب الرسالة. |
| [FetchMessage](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessage#fetchmessage_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | جلب الرسالة من server |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages)(IEnumerable&lt;ExchangeMessageInfo&gt;) | جلب الرسائل المحددة |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_1)(IEnumerable&lt;string&gt;) | جلب الرسائل المحددة |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_3)(StringCollection) | جلب الرسائل المحددة |
| [FetchMessages](../../aspose.email.clients.exchange.webservice/iewsclient/fetchmessages#fetchmessages_2)(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) | جلب الرسائل المحددة |
| [FetchTask](../../aspose.email.clients.exchange.webservice/iewsclient/fetchtask)(string) | جلب المهمة المحددة. |
| [FindConversations](../../aspose.email.clients.exchange.webservice/iewsclient/findconversations)(string) | البحث عن المحادثات في المجلد المحدد |
| [FindMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/findmessagetrackingreport)(FindMessageTrackingReportOptions) | البحث عن الرسائل التي تطابق المعايير المحددة . |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople#findpeople_1)(string, int) | البحث عن جهات الاتصال الموجودة في قائمة العناوين العمومية (GAL) على الخادم. |
| [FindPeople](../../aspose.email.clients.exchange.webservice/iewsclient/findpeople#findpeople)(string, MailQuery, int) | البحث عن جهات الاتصال الموجودة في صندوق البريد الشخصي للمستخدم المحدد على الخادم. |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists#folderexists)(string, string) | للتحقق مما إذا كان المجلد المحدد موجودًا. |
| [FolderExists](../../aspose.email.clients.exchange.webservice/iewsclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | للتحقق مما إذا كان المجلد المحدد موجودًا. |
| [Forward](../../aspose.email.clients.exchange.webservice/iewsclient/forward)(MailMessage, ExchangeMessageInfo) | إعادة توجيه رسالة . |
| [GetCallInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getcallinfo)(string) | يسترجع معلومات المكالمة الهاتفية عن طريق الاتصال id |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact)(ObjectIdentifier) | استرداد معلومات الاتصال وفقًا للمعرف المحدد. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_2)(string) | استرداد معلومات الاتصال وفقًا للمعرف المحدد. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_1)(ObjectIdentifier, ExchangeListContactsOptions) | استرداد معلومات الاتصال وفقًا للمعرف المحدد. |
| [GetContact](../../aspose.email.clients.exchange.webservice/iewsclient/getcontact#getcontact_3)(string, ExchangeListContactsOptions) | استرداد معلومات الاتصال وفقًا للمعرف المحدد. |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts#getcontacts)(string) | يسرد جهات الاتصال الموجودة في المجلد المحدد على server |
| [GetContacts](../../aspose.email.clients.exchange.webservice/iewsclient/getcontacts#getcontacts_1)(string, ExchangeListContactsOptions) | يسرد جهات الاتصال الموجودة في المجلد المحدد على server |
| [GetExchangeType](../../aspose.email.clients.exchange.webservice/iewsclient/getexchangetype)() | الحصول على معلومات حول الإصدار الحالي من MS Exchange . |
| [GetFolderInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderinfo)(string) | يحصل على المجلد information |
| [GetFolderPermissions](../../aspose.email.clients.exchange.webservice/iewsclient/getfolderpermissions)(string) | يحصل على أذونات المجلد . |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules#getinboxrules)() | يحصل على قواعد البريد الوارد |
| [GetInboxRules](../../aspose.email.clients.exchange.webservice/iewsclient/getinboxrules#getinboxrules_1)(string) | يحصل على قواعد البريد الوارد |
| [GetMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxes)() | يسرد صناديق البريد التي تحتوي على عناوين smtp . ملاحظة: الحد الأقصى لعدد جهات الاتصال التي تم إرجاعها هو 100. هذا تقييد لعملية EWS المستخدمة. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo#getmailboxinfo)() | يحصل على معلومات صندوق البريد. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxinfo#getmailboxinfo_1)(string) | يحصل على معلومات صندوق البريد |
| [GetMailboxSize](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsize)() | الحصول على حجم صندوق البريد. من فضلك ، لاحظ أن هذه العملية تتم بشكل متكرر لجميع المجلدات الفرعية وتستغرق بعض الوقت |
| [GetMailboxSizeEx](../../aspose.email.clients.exchange.webservice/iewsclient/getmailboxsizeex)(string) | الحصول على حجم mailbox من فضلك ، لاحظ أن هذه العملية تتم بشكل متكرر لجميع المجلدات الفرعية وتستغرق بعض الوقت |
| [GetMailTips](../../aspose.email.clients.exchange.webservice/iewsclient/getmailtips)(GetMailTipsOptions) | الحصول على نصائح البريد |
| [GetMessageTrackingReport](../../aspose.email.clients.exchange.webservice/iewsclient/getmessagetrackingreport)(GetMessageTrackingReportOptions) | الحصول على تقرير تتبع الرسائل |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids)() | ترجع GetServerTimeZoneIds معلومات من معرّف المنطقة الزمنية المتوفرة على خادم Exchange. |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids_1)(IEnumerable&lt;string&gt;) | ترجع GetServerTimeZoneIds معلومات من معرّف المنطقة الزمنية المتوفرة على خادم Exchange. |
| [GetServerTimeZoneIds](../../aspose.email.clients.exchange.webservice/iewsclient/getservertimezoneids#getservertimezoneids_2)(params string[]) | ترجع GetServerTimeZoneIds معلومات من معرّف المنطقة الزمنية المتوفرة على خادم Exchange. |
| [GetUMConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getumconfiguration)() | استرداد تكوين الرسائل الموحدة |
| [GetUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/getuserconfiguration)(UserConfigurationName) | يحصل على تكوين المستخدم المحدد |
| [GetVersionInfo](../../aspose.email.clients.exchange.webservice/iewsclient/getversioninfo)() | إرجاع معلومات إصدار خادم التبادل info |
| [ImpersonateUser](../../aspose.email.clients.exchange.webservice/iewsclient/impersonateuser)(ItemChoice, string) | ينتحل صفة المستخدم . |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments)() | استرداد قائمة المواعيد لمجلد التقويم الافتراضي |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_3)(bool) | استرداد قائمة المواعيد لمجلد التقويم الافتراضي |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_1)(MailQuery) | استرداد قائمة المواعيد لمجلد التقويم الافتراضي |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_4)(string) | استرداد قائمة المواعيد لمجلد التقويم المحدد |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_2)(MailQuery, bool) | استرداد قائمة المواعيد لمجلد التقويم الافتراضي |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_7)(string, bool) | استرداد قائمة المواعيد لمجلد التقويم المحدد |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_5)(string, MailQuery) | استرداد قائمة المواعيد لمجلد التقويم المحدد |
| [ListAppointments](../../aspose.email.clients.exchange.webservice/iewsclient/listappointments#listappointments_6)(string, MailQuery, bool) | استرداد قائمة المواعيد لمجلد التقويم المحدد |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_2)(int) | استرداد الصفحة مع المواعيد لمجلد التقويم |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_3)(int, int) | استرداد الصفحة مع المواعيد لمجلد التقويم |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage)(MailQuery, int) | استرداد الصفحة مع المواعيد لمجلد التقويم |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_6)(string, int) | استرداد الصفحة مع المواعيد لمجلد التقويم المحدد |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_1)(MailQuery, int, int) | استرداد الصفحة مع المواعيد لمجلد التقويم |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_7)(string, int, int) | استرداد الصفحة مع المواعيد لمجلد التقويم المحدد |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_4)(string, MailQuery, int) | استرداد الصفحة مع المواعيد لمجلد التقويم المحدد |
| [ListAppointmentsByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage#listappointmentsbypage_5)(string, MailQuery, int, int) | استرداد الصفحة مع المواعيد لمجلد التقويم المحدد |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts#listcontacts)(string) | يسرد جهات الاتصال الموجودة في المجلد المحدد على server |
| [ListContacts](../../aspose.email.clients.exchange.webservice/iewsclient/listcontacts#listcontacts_1)(string, IEnumerable&lt;PropertyDescriptor&gt;) | يسرد جهات الاتصال الموجودة في المجلد المحدد على server |
| [ListDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/listdelegates)(string) | يسرد المستخدمين الذين تم منحهم حق الوصول إلى صندوق البريد المحدد. |
| [ListDistributionLists](../../aspose.email.clients.exchange.webservice/iewsclient/listdistributionlists)() | سرد قوائم التوزيع الخاصة . |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems)(string) | استرداد قائمة عناوين URL للعناصر في المجلد المحدد |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_1)(string, MailQuery) | استرداد قائمة عناوين URL للعناصر في المجلد المحدد |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_3)(string, string) | استرداد قائمة عناوين URL للعناصر في المجلد المحدد |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_2)(string, MailQuery, bool) | استرداد قائمة عناوين URL للعناصر في المجلد المحدد |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_4)(string, string, MailQuery) | استرداد قائمة عناوين URL للعناصر في المجلد المحدد |
| [ListItems](../../aspose.email.clients.exchange.webservice/iewsclient/listitems#listitems_5)(string, string, MailQuery, bool) | استرداد قائمة عناوين URL للعناصر في المجلد المحدد |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes#listmailboxes)() | قوائم صناديق البريد . |
| [ListMailboxes](../../aspose.email.clients.exchange.webservice/iewsclient/listmailboxes#listmailboxes_1)(string) | يرجى الانتباه ، فهذه الطريقة التي تم تجاوزها تعمل مع Exchange Server 2013 والإصدارات الأحدث. قوائم علب البريد. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages)() | سرد الرسائل في مجلد صندوق الوارد. |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_1)(IEnumerable&lt;string&gt;) | سرد الرسائل في المجلد المحدد . |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_2)(string) | يسرد الرسائل . |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_7)(string, bool) | سرد الرسائل في المجلد المحدد |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_3)(string, ExchangeListMessagesOptions) | يسرد الرسائل . |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_8)(string, int) | يسرد الرسائل . |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_5)(string, MailQuery) | سرد الرسائل في المجلد المحدد . |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_4)(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) | سرد الرسائل في المجلد المحدد |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_9)(string, int, ExchangeListMessagesOptions) | يسرد الرسائل . |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_10)(string, int, MailQuery) | سرد الرسائل في المجلد المحدد . |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_6)(string, MailQuery, bool) | سرد الرسائل في المجلد المحدد . |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_13)(string, string, bool) | سرد الرسائل في المجلد المحدد |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_12)(string, string, MailQuery) | سرد الرسائل في المجلد المحدد . |
| [ListMessages](../../aspose.email.clients.exchange.webservice/iewsclient/listmessages#listmessages_11)(string, int, MailQuery, bool) | سرد الرسائل في المجلد المحدد . |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_4)(string, int) | سرد الرسائل في المجلد المحدد . |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage)(string, PageInfo) | سرد الرسائل في المجلد المحدد . |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_5)(string, int, int) | سرد الرسائل في المجلد المحدد . |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_2)(string, MailQuery, int) | سرد الرسائل في المجلد المحدد . |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_1)(string, PageInfo, ExchangeListMessagesOptions) | سرد الرسائل في المجلد المحدد . |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_6)(string, int, int, ExchangeListMessagesOptions) | سرد الرسائل في المجلد المحدد . |
| [ListMessagesByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage#listmessagesbypage_3)(string, MailQuery, int, int) | سرد الرسائل في المجلد المحدد . |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder#listmessagesfrompublicfolder)(ExchangeFolderInfo) | الحصول على مجموعة من الرسائل من المجلد العام |
| [ListMessagesFromPublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/listmessagesfrompublicfolder#listmessagesfrompublicfolder_1)(string) | الحصول على مجموعة من الرسائل من المجلد العام |
| [ListPublicFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listpublicfolders)() | الحصول على مجموعة من المجلدات العامة من المجلد العام الجذر |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | الحصول على مجموعة من المجلدات العامة التابعة من parent |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders_1)(string) | الحصول على مجموعة من المجلدات الفرعية من parent |
| [ListSubFolders](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfolders#listsubfolders_2)(string, string) | الحصول على مجموعة من المجلدات الفرعية من parent |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage_1)(string, int) | يبحث في المجلد المحدد في المجلد الأصل المحدد باستخدام paging الأسلوب يدعم الترحيل. يتم استدعاءه لأول مرة في دورة الترحيل. |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage)(string, PageInfo) | يبحث في المجلد المحدد في المجلد الأصل المحدد باستخدام paging الأسلوب يدعم الترحيل . |
| [ListSubFoldersByPage](../../aspose.email.clients.exchange.webservice/iewsclient/listsubfoldersbypage#listsubfoldersbypage_2)(string, int, int) | يبحث في المجلد المحدد في المجلد الأصل المحدد باستخدام paging الأسلوب يدعم الترحيل . |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks)() | استرداد قوائم مهام التبادل للمجلد الافتراضي. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_1)(string) | استرداد قوائم مهام التبادل. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_3)(string, int) | استرداد قوائم مهام التبادل. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_2)(string, MailQuery) | استرداد قوائم مهام التبادل. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_4)(string, int, MailQuery) | استرداد قوائم مهام التبادل. |
| [ListTasks](../../aspose.email.clients.exchange.webservice/iewsclient/listtasks#listtasks_5)(string, int, MailQuery, bool) | استرداد قوائم مهام التبادل. |
| [LoadContactPhoto](../../aspose.email.clients.exchange.webservice/iewsclient/loadcontactphoto)(ContactPhoto) | تحميل بيانات صورة جهة الاتصال الثنائية |
| [MailDisablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/maildisablepublicfolder)(string) | تعطيل البريد لمجلد عام |
| [MailEnablePublicFolder](../../aspose.email.clients.exchange.webservice/iewsclient/mailenablepublicfolder)(string) | تمكين البريد لمجلد عام |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems_2)(bool, params string[]) | وضع علامة على كافة العناصر في مجلدات محددة. |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems)(bool, bool, IEnumerable&lt;string&gt;) | وضع علامة على كافة العناصر في مجلدات محددة. |
| [MarkAllItems](../../aspose.email.clients.exchange.webservice/iewsclient/markallitems#markallitems_1)(bool, bool, params string[]) | وضع علامة على كافة العناصر في مجلدات محددة. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread)() | وضع علامة على كافة العناصر الموجودة في مجلد البريد الوارد كمقروءة بدون إيصالات. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread_1)(IEnumerable&lt;string&gt;) | وضع علامة على كافة العناصر الموجودة في مجلدات محددة كمقروءة بدون إيصالات. |
| [MarkAllItemsAsRead](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasread#markallitemsasread_2)(params string[]) | وضع علامة على كافة العناصر الموجودة في مجلدات محددة كمقروءة بدون إيصالات. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread)() | وضع علامة على كافة العناصر الموجودة في مجلد البريد الوارد كغير مقروءة. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread_1)(IEnumerable&lt;string&gt;) | وضع علامة على كافة العناصر الموجودة في المجلدات المحددة كغير مقروءة. |
| [MarkAllItemsAsUnread](../../aspose.email.clients.exchange.webservice/iewsclient/markallitemsasunread#markallitemsasunread_2)(params string[]) | وضع علامة على كافة العناصر الموجودة في المجلدات المحددة كغير مقروءة. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_2)(bool, IEnumerable&lt;string&gt;) | طريقة MarkAsJunk تنقل رسائل البريد إلى حافظة البريد غير الهام وتحظر مرسل الرسالة. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_3)(bool, params string[]) | طريقة MarkAsJunk تنقل رسائل البريد إلى حافظة البريد غير الهام وتحظر مرسل الرسالة. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk)(bool, bool, IEnumerable&lt;string&gt;) | طريقة MarkAsJunk تنقل رسائل البريد إلى حافظة البريد غير الهام وتحظر مرسل الرسالة. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_1)(bool, bool, params string[]) | طريقة MarkAsJunk تنقل رسائل البريد إلى حافظة البريد غير الهام وتحظر مرسل الرسالة. |
| [MarkAsJunk](../../aspose.email.clients.exchange.webservice/iewsclient/markasjunk#markasjunk_4)(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) | طريقة MarkAsJunk تنقل رسائل البريد إلى حافظة البريد غير الهام وتحظر مرسل الرسالة. |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems#moveconversationitems)(string, string) | نقل عناصر المحادثة إلى المجلد الهدف المحدد |
| [MoveConversationItems](../../aspose.email.clients.exchange.webservice/iewsclient/moveconversationitems#moveconversationitems_1)(string, string, string) | لنقل عناصر المحادثة الموجودة في المجلد المحدد إلى المجلد الهدف المحدد |
| [MoveItem](../../aspose.email.clients.exchange.webservice/iewsclient/moveitem)(string, string) | نقل العنصر إلى المجلد المحدد |
| [PlayOnPhone](../../aspose.email.clients.exchange.webservice/iewsclient/playonphone)(string, string) | تبدأ عملية PlayOnPhone مكالمة صادرة وتقوم بتشغيل رسالة عبر الهاتف. |
| [RemoveHeader](../../aspose.email.clients.exchange.webservice/iewsclient/removeheader)(string) | إزالة WebHeader من WebHeaderCollection في طلب EWS . |
| [Reply](../../aspose.email.clients.exchange.webservice/iewsclient/reply)(MailMessage, ExchangeMessageInfo) | الرد على رسالة المرسل . |
| [ReplyAll](../../aspose.email.clients.exchange.webservice/iewsclient/replyall)(MailMessage, ExchangeMessageInfo) | الرد على المرسل وجميع مستلمي الرسالة. |
| [ResetImpersonation](../../aspose.email.clients.exchange.webservice/iewsclient/resetimpersonation)() | يجعل عملية إعادة تعيين الانتحال . |
| [ResetSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/resetsubscription)() | إعادة تعيين كافة الاشتراكات |
| [ResolveContact](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontact)(string) | يحل أسماء علب البريد المبهمة. |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts#resolvecontacts)(string) | يحل أسماء عرض صندوق البريد الغامضة . ملاحظة: الحد الأقصى لعدد جهات الاتصال التي تم إرجاعها هو 100. هذا تقييد لأمر التبادل المستخدم. |
| [ResolveContacts](../../aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts#resolvecontacts_1)(string, ExchangeListContactsOptions) | يحل عناوين البريد الإلكتروني الغامضة وأسماء العرض ملاحظة: الحد الأقصى لعدد جهات الاتصال التي تم إرجاعها هو 100. هذا تقييد لعملية EWS المستخدمة. |
| [Restore](../../aspose.email.clients.exchange.webservice/iewsclient/restore)(PersonalStorage, RestoreSettings) | يستعيد مجلدات التبادل المحددة من التخزين الشخصي المحدد. |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage#savemessage)(string, Stream) | يحفظ الرسالة. |
| [SaveMessage](../../aspose.email.clients.exchange.webservice/iewsclient/savemessage#savemessage_1)(string, string) | يحفظ الرسالة. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send)(MailMessage) | يرسل الرسالة المحددة. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send_1)(MailMessage, FollowUpOptions) | يرسل الرسالة. |
| [Send](../../aspose.email.clients.exchange.webservice/iewsclient/send#send_2)(string, string, string, string) | يرسل الرسالة المحددة |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate#setconversationreadstate)(string, bool) | تعيين حالة القراءة لعناصر المحادثة على القيمة المحددة |
| [SetConversationReadState](../../aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate#setconversationreadstate_1)(string, string, bool) | اضبط حالة القراءة لعناصر المحادثة الموجودة في المجلد المحدد على القيمة المحددة |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag#setreadflag)(string) | يضبط علامة القراءة . |
| [SetReadFlag](../../aspose.email.clients.exchange.webservice/iewsclient/setreadflag#setreadflag_1)(string, bool) | وضع علامة على الرسالة المحددة كمقروءة. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_1)(string) | استرداد التغييرات الخاصة بالعناصر والمجلدات الفرعية في مجلد محدد. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder)(SyncState) | استرداد التغييرات الخاصة بالعناصر الموجودة في مجلد محدد. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_3)(string, string) | استرداد التغييرات الخاصة بالعناصر الموجودة في مجلد محدد. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_2)(string, SyncFolderType) | استرداد التغييرات الخاصة بالعناصر والمجلدات الفرعية في مجلد محدد. |
| [SyncFolder](../../aspose.email.clients.exchange.webservice/iewsclient/syncfolder#syncfolder_4)(string, string, IEnumerable&lt;string&gt;) | استرداد التغييرات الخاصة بالعناصر الموجودة في مجلد محدد. |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment)(Appointment) | موعد التحديثات . |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_2)(MapiCalendar) | موعد التحديثات . |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_1)(Appointment, string) | موعد التحديثات . |
| [UpdateAppointment](../../aspose.email.clients.exchange.webservice/iewsclient/updateappointment#updateappointment_3)(MapiCalendar, string) | موعد التحديثات . |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact#updatecontact_1)(Contact) | يحدّث عنصر جهة اتصال في مخزن Exchange . |
| [UpdateContact](../../aspose.email.clients.exchange.webservice/iewsclient/updatecontact#updatecontact)(MapiContact) | يحدّث عنصر جهة اتصال في مخزن Exchange . |
| [UpdateDelegate](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegate)(ExchangeDelegateUser, string) | يقوم بتحديث إعدادات المستخدم المفوض الذي تم منحه حق الوصول إلى صندوق البريد المحدد. |
| [UpdateDelegates](../../aspose.email.clients.exchange.webservice/iewsclient/updatedelegates)(ExchangeDelegateUserCollection, string) | يقوم بتحديث إعدادات المستخدمين المفوضين الذين تم منحهم حق الوصول إلى صندوق البريد المحدد. |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule#updateinboxrule)(InboxRule) | يحدّث قاعدة علبة الوارد المحددة |
| [UpdateInboxRule](../../aspose.email.clients.exchange.webservice/iewsclient/updateinboxrule#updateinboxrule_1)(InboxRule, string) | يحدّث قاعدة علبة الوارد المحددة |
| [UpdateItems](../../aspose.email.clients.exchange.webservice/iewsclient/updateitems)(ExchangeStreamedItem[], string) | يقوم بتحديث العناصر المحددة في علبة البريد |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote)(MapiNote) | يقوم بتحديث الملاحظة المحددة . |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote_1)(string, MapiNote) | يقوم بتحديث الملاحظة المحددة . |
| [UpdateNote](../../aspose.email.clients.exchange.webservice/iewsclient/updatenote#updatenote_2)(string, MapiNote, IEnumerable&lt;PropertyDescriptor&gt;) | يقوم بتحديث الملاحظة المحددة . |
| [UpdateSubscription](../../aspose.email.clients.exchange.webservice/iewsclient/updatesubscription)() | تحديثات الاشتراكات |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_3)(ExchangeTask) | يقوم بتحديث المهمة المحددة. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask)(MapiTask) | يقوم بتحديث المهمة المحددة. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_4)(ExchangeTask, UpdateTaskOptions) | يقوم بتحديث المهمة المحددة. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_1)(string, MapiTask) | يقوم بتحديث المهمة المحددة. |
| [UpdateTask](../../aspose.email.clients.exchange.webservice/iewsclient/updatetask#updatetask_2)(string, MapiTask, IEnumerable&lt;PropertyDescriptor&gt;) | يقوم بتحديث المهمة المحددة. |
| [UpdateUserConfiguration](../../aspose.email.clients.exchange.webservice/iewsclient/updateuserconfiguration)(UserConfiguration) | يقوم بتحديث تكوين المستخدم المحدد |

### أنظر أيضا

* interface [IExchangeClientBase](../../aspose.email.clients.exchange/iexchangeclientbase)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
