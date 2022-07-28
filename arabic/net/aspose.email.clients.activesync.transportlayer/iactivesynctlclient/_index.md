---
title: IActiveSyncTLClient
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: واجهة عميل ActiveSync
type: docs
weight: 1310
url: /ar/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/
---
## IActiveSyncTLClient interface

واجهة عميل ActiveSync

```csharp
public interface IActiveSyncTLClient : IBaseActiveSyncTLClient
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AirSyncKeys](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/airsynckeys) { get; } | يحتوي على القيم التي تستخدمها وحدة الخدمة لتحديد حالة التزامن لكل مجموعة متزامنة . حيث يكون مفتاح القاموس هو معرف وحدة الخدمة وقيمة القاموس هي SyncKey. لأوامر GetItemEstimate والمزامنة. |
| [FoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderssynckey) { get; } | يستخدم من قبل الخادم لتتبع الحالة الحالية للعميل . للعمليات مع المجلدات فقط |
| [HeartbeatInterval](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/heartbeatinterval) { get; set; } | عنصر HeartbeatInterval هو عنصر تابع لعنصر Ping في طلبات واستجابات أوامر Ping. في طلبات الأمر Ping ، تحدد المدة الزمنية بالثواني التي يجب أن ينتظرها الخادم قبل إرسال استجابة إذا لم تتم إضافة عناصر جديدة إلى مجموعة المجلدات المحددة ، كما هو محدد في القسم 3.1.5.6. يتم إرجاع عنصر HeartbeatInterval أيضًا بواسطة الخادم برمز الحالة 5 ويحدد إما الحد الأدنى أو الحد الأقصى للفاصل المسموح به عندما يطلب العميل فاصل نبضات القلب يكون خارج النطاق المقبول. |

## طُرق

| اسم | وصف |
| --- | --- |
| [FolderCreate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldercreate)(string, string, UserCreatedFolderTypes) | يقوم FolderCreate بإنشاء مجلد جديد كمجلد فرعي للمجلد الأصل المحدد. |
| [FolderDelete](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderdelete)(string) | حذف المجموعة ذات المعرف المطابق. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync)() | يقوم FolderSync بمزامنة التسلسل الهرمي للمجموعة ولكنه لا يقوم بمزامنة العناصر الموجودة في المجموعات نفسها. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync_1)(bool) | يقوم FolderSync بمزامنة التسلسل الهرمي للمجموعة ولكنه لا يقوم بمزامنة العناصر الموجودة في المجموعات نفسها. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate)(FolderInfo) | يقوم الأمر FolderUpdate بنقل مجلد من موقع إلى آخر على الخادم. يتم استخدام الأمر أيضًا لإعادة تسمية مجلد. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate_1)(string, string, string) | يقوم الأمر FolderUpdate بنقل مجلد من موقع إلى آخر على الخادم. يتم استخدام الأمر أيضًا لإعادة تسمية مجلد. |
| [GetAttachment](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getattachment)(string) | يقوم GetAttachment باسترداد مرفق بريد إلكتروني من الخادم . لا يتم دعم GetAttachment عندما يكون إصدار البروتوكول هو 14.0 أو 14.1. استخدم عنصر الجلب للأمر ItemOperations بدلاً من ذلك. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_2)(IEnumerable&lt;ItemEstimateRequest&gt;) | يحصل الأمر GetItemEstimate على تقدير لعدد العناصر في مجموعة أو مجلد على الخادم التي يجب مزامنتها. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate)(ItemEstimateRequest) | يحصل الأمر GetItemEstimate على تقدير لعدد العناصر في مجموعة أو مجلد على الخادم التي يجب مزامنتها. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_1)(params ItemEstimateRequest[]) | يحصل الأمر GetItemEstimate على تقدير لعدد العناصر في مجموعة أو مجلد على الخادم التي يجب مزامنتها. |
| [ItemOperations](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/itemoperations)(ItemOperationsRequest) | توفر عملية ItemOperations معالجة مجمعة عبر الإنترنت لعمليات الجلب ومحتويات المجلد الفارغ وعمليات النقل. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_3)(IEnumerable&lt;MeetingResponseRequest&gt;) | قبول طلب اجتماع أو قبوله مبدئيًا أو رفضه في مجلد صندوق الوارد الخاص بالمستخدم أو مجلد التقويم. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_2)(params MeetingResponseRequest[]) | قبول طلب اجتماع أو قبوله مبدئيًا أو رفضه في مجلد صندوق الوارد الخاص بالمستخدم أو مجلد التقويم. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse)(UserResponse, string, string) | قبول طلب اجتماع أو قبوله مبدئيًا أو رفضه في مجلد صندوق الوارد الخاص بالمستخدم أو مجلد التقويم. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_1)(UserResponse, string, string, string, string) | قبول طلب اجتماع أو قبوله مبدئيًا أو رفضه في مجلد صندوق الوارد الخاص بالمستخدم أو مجلد التقويم. |
| [MoveItem](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitem)(string, string, string) | يقوم الأمر MoveItems بنقل عنصر أو عناصر من مجلد على الخادم إلى مجلد آخر. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems_1)(IEnumerable&lt;MoveItemData&gt;) | يقوم الأمر MoveItems بنقل عنصر أو عناصر من مجلد على الخادم إلى مجلد آخر. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems)(params MoveItemData[]) | يقوم الأمر MoveItems بنقل عنصر أو عناصر من مجلد على الخادم إلى مجلد آخر. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_4)(IEnumerable&lt;PingParameter&gt;) | يتم استخدام الأمر Ping للمطالبة بأن يقوم الخادم بمراقبة المجلدات المحددة للتغييرات التي قد تتطلب من العميل إعادة المزامنة. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping)(params PingParameter[]) | يتم استخدام الأمر Ping للمطالبة بأن يقوم الخادم بمراقبة المجلدات المحددة للتغييرات التي قد تتطلب من العميل إعادة المزامنة. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_2)(int, IEnumerable&lt;PingParameter&gt;) | يتم استخدام الأمر Ping للمطالبة بأن يقوم الخادم بمراقبة المجلدات المحددة للتغييرات التي قد تتطلب من العميل إعادة المزامنة. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_1)(int, params PingParameter[]) | يتم استخدام الأمر Ping للمطالبة بأن يقوم الخادم بمراقبة المجلدات المحددة للتغييرات التي قد تتطلب من العميل إعادة المزامنة. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_5)(string, FolderClass) | يتم استخدام الأمر Ping للمطالبة بأن يقوم الخادم بمراقبة المجلدات المحددة للتغييرات التي قد تتطلب من العميل إعادة المزامنة. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_3)(int, string, FolderClass) | يتم استخدام الأمر Ping للمطالبة بأن يقوم الخادم بمراقبة المجلدات المحددة للتغييرات التي قد تتطلب من العميل إعادة المزامنة. |
| [Provision](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/provision)(ProvisionRequest) | يتيح الأمر Provision لأجهزة العميل أن تطلب من الخادم إعدادات نهج الأمان التي يعيّنها المسؤول ، مثل الحد الأدنى لمتطلبات طول كلمة المرور لرقم التعريف الشخصي (PIN) . |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey)() | إعادة تعيين SyncKeys لعمليات GetItemEstimate والمزامنة لجميع المجموعات. |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey_1)(string) | إعادة تعيين SyncKey لعمليات GetItemEstimate والمزامنة لمجموعة محددة. |
| [ResetFoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetfolderssynckey)() | إعادة تعيين SyncKey للعمليات مع folder |
| [ResolveRecipients](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resolverecipients)(ResolveRecipientsRequest) | يتم استخدام ResolveRecipients لحل قائمة المستلمين المزودين ، لاسترداد معلومات التوفر / الانشغال الخاصة بهم ، واختياريا ، لاسترداد شهادات S / MIME الخاصة بهم حتى يتمكن العملاء من إرسال رسائل بريد إلكتروني S / MIME مشفرة. استرداد معلومات التوفر / الانشغال استخدام عنصر الإتاحة في الأمر ResolveRecipients غير مدعوم عندما يكون إصدار البروتوكول هو 12.1. |
| [Search](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/search)(SearchRequest) | يُستخدم البحث للعثور على إدخالات في دفتر عناوين أو صندوق بريد أو مكتبة مستندات (UNC أو Windows SharePoint Services) . |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail)(string) | يتم استخدام SendMail بواسطة العملاء لإرسال رسائل بريد إلكتروني بتنسيق MIME إلى الخادم. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_1)(string, bool) | يتم استخدام SendMail بواسطة العملاء لإرسال رسائل بريد إلكتروني بتنسيق MIME إلى الخادم. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_2)(string, bool, string) | يتم استخدام SendMail بواسطة العملاء لإرسال رسائل بريد إلكتروني بتنسيق MIME إلى الخادم. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_3)(string, bool, string, string) | يتم استخدام SendMail بواسطة العملاء لإرسال رسائل بريد إلكتروني بتنسيق MIME إلى الخادم. |
| [Settings](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/settings)(SettingsRequest) | تدعم الإعدادات عمليات الحصول وتعيين على الخصائص العامة وإعدادات خارج المكتب (OOF) للمستخدم. ترسل الإعدادات أيضًا معلومات الجهاز إلى الخادم ، وتنفذ استعادة كلمة مرور الجهاز / رقم التعريف الشخصي (PIN) ، وتسترجع قائمة عناوين البريد الإلكتروني للمستخدم. |
| [SmartForward](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartforward)(SmartRequest) | يتم استخدام الأمر SmartForward بواسطة العملاء لإعادة توجيه الرسائل دون استرداد الرسالة الأصلية الكاملة من الخادم. |
| [SmartReply](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartreply)(SmartRequest) | يتم استخدام الأمر SmartReply بواسطة العملاء للرد على الرسائل دون استرداد الرسالة الأصلية الكاملة من الخادم. |
| [Sync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sync)(SyncRequest) | تقوم المزامنة بمزامنة التغييرات في مجموعة بين العميل والخادم. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert)(IEnumerable&lt;X509Certificate&gt;) | يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_4)(X509Certificate) | يتم استخدام الأمر ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_1)(IEnumerable&lt;X509Certificate&gt;, bool) | يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_2)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) | يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_5)(X509Certificate, bool) | يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_6)(X509Certificate, IEnumerable&lt;X509Certificate&gt;) | يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_3)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) | يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_7)(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) | يتم استخدام ValidateCert بواسطة العميل للتحقق من صحة الشهادة التي تم استلامها عبر بريد S / MIME. |

### أنظر أيضا

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
