---
title: EASProvisionDoc
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يحدد مجموعة إعدادات الأمان لتوفير الجهاز.
type: docs
weight: 1190
url: /ar/net/aspose.email.clients.activesync.transportlayer/easprovisiondoc/
---
## EASProvisionDoc class

يحدد مجموعة إعدادات الأمان لتوفير الجهاز.

```csharp
public class EASProvisionDoc
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EASProvisionDoc](easprovisiondoc)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AllowBluetooth](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowbluetooth) { get; set; } | يحدد استخدام Bluetooth على الجهاز. يجب تجاهل هذه الخاصية إذا كان العميل لا يدعم تقنية Bluetooth . |
| [AllowBrowser](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowbrowser) { get; set; } | يحدد ما إذا كان الجهاز يسمح باستخدام مستعرض ويب. |
| [AllowCamera](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowcamera) { get; set; } | يحدد ما إذا كان الجهاز يسمح باستخدام الكاميرا المدمجة. يجب تجاهل هذه الخاصية إذا لم يكن لدى العميل كاميرا ولا يمكن توصيل أي كاميرا بالجهاز. |
| [AllowConsumerEmail](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowconsumeremail) { get; set; } | يحدد ما إذا كان الجهاز يسمح للمستخدم بتكوين حساب بريد إلكتروني شخصي. |
| [AllowDesktopSync](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowdesktopsync) { get; set; } | يحدد ما إذا كان الجهاز يسمح بالمزامنة مع Desktop ActiveSync . يجب تجاهل هذه الخاصية إذا كان العميل لا يدعم الاتصال بجهاز كمبيوتر شخصي. |
| [AllowHTMLEmail](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowhtmlemail) { get; set; } | يحدد ما إذا كان العميل يستخدم بريدًا إلكترونيًا بتنسيق HTML. |
| [AllowInternetSharing](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowinternetsharing) { get; set; } | يحدد ما إذا كان الجهاز يسمح باستخدام "مشاركة الإنترنت". يجب تجاهل هذه الخاصية إذا كان العميل لا يدعم مشاركة اتصال الإنترنت الخاص به مع الأجهزة الأخرى. |
| [AllowIrDA](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowirda) { get; set; } | يحدد ما إذا كان الجهاز يسمح باستخدام اتصالات الأشعة تحت الحمراء (الأشعة تحت الحمراء). يجب تجاهل هذه الخاصية إذا لم يكن لدى العميل القدرة على إرسال أو استقبال إشارات الأشعة تحت الحمراء. |
| [AllowPOPIMAPEmail](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowpopimapemail) { get; set; } | يحدد ما إذا كان الجهاز يسمح بالوصول إلى بريد POP أو IMAP الإلكتروني. |
| [AllowRemoteDesktop](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowremotedesktop) { get; set; } | يحدد ما إذا كان الجهاز يسمح باستخدام سطح المكتب البعيد. يجب تجاهل هذه الخاصية إذا كان العميل لا يدعم الاتصال عن بعد بجهاز كمبيوتر شخصي. |
| [AllowSimpleDevicePassword](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowsimpledevicepassword) { get; set; } | يحدد ما إذا كان العميل يسمح بكلمات مرور بسيطة. كلمة المرور البسيطة هي كلمة تتكون فقط من أحرف متكررة ("2222") أو متسلسلة ("abcd") . إذا كانت AllowSimpleDevicePassword فارغة ، فيجب على العميل معاملة هذه القيمة على أنها TRUE. إذا تم تعيين قيمة DevicePasswordEnabled على FALSE ، يجب على العميل تجاهل هذه الخاصية. |
| [AllowSMIMEEncryptionAlgorithmNegotiation](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowsmimeencryptionalgorithmnegotiation) { get; set; } | يتحكم في تفاوض خوارزمية التشفير. |
| [AllowSMIMESoftCerts](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowsmimesoftcerts) { get; set; } | يحدد ما إذا كان يمكن للعميل استخدام شهادات النظام لتوقيع الرسائل الصادرة. |
| [AllowStorageCard](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowstoragecard) { get; set; } | يحدد ما إذا كان الجهاز يسمح باستخدام بطاقة التخزين. يجب تجاهل هذه الخاصية إذا كان العميل لا يدعم تخزين البيانات على وحدة تخزين قابلة للإزالة. |
| [AllowTextMessaging](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowtextmessaging) { get; set; } | يحدد ما إذا كان الجهاز يسمح باستخدام SMS أو الرسائل النصية. يجب تجاهل هذه الخاصية إذا كان العميل لا يدعم الرسائل النصية القصيرة أو الرسائل النصية . |
| [AllowUnsignedApplications](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowunsignedapplications) { get; set; } | يحدد ما إذا كان الجهاز يسمح بتنفيذ التطبيقات غير الموقعة. |
| [AllowUnsignedInstallationPackages](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowunsignedinstallationpackages) { get; set; } | يحدد ما إذا كان الجهاز يسمح بتثبيت ملفات الخزانة (.cab) غير الموقعة. |
| [AllowWiFi](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowwifi) { get; set; } | يحدد ما إذا كان الجهاز يسمح باستخدام اتصالات Wi-Fi . يجب تجاهل هذه الخاصية إذا لم يكن لدى العميل إمكانية Wi-Fi . |
| [AlphanumericDevicePasswordRequired](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/alphanumericdevicepasswordrequired) { get; set; } | يحدد ما إذا كان العميل يتطلب كلمة مرور أبجدية رقمية. إذا كان AlphanumericDevicePasswordRequired فارغًا ، فيجب على العميل معاملة هذه القيمة على أنها FALSE. إذا كانت قيمة DevicePasswordEnabled FALSE ، فيجب على العميل تجاهل هذه الخاصية. |
| [ApprovedApplicationList](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/approvedapplicationlist) { get; } | تحديد قائمة بالتطبيقات الموجودة في الذاكرة التي تمت الموافقة عليها للتنفيذ. تتأثر التطبيقات الموجودة في الذاكرة فقط بهذه الخاصية. لا تنطبق هذه الخاصية على تطبيقات ذاكرة القراءة فقط. إذا لم يكن فارغًا ، يجب على العميل السماح فقط بتنفيذ التطبيقات الموجودة في الذاكرة المحددة بواسطة هذه الخاصية. |
| [AttachmentsEnabled](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/attachmentsenabled) { get; set; } | يحدد ما إذا كانت مرفقات البريد الإلكتروني ممكنة. |
| [DevicePasswordEnabled](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordenabled) { get; set; } | يحدد ما إذا كان العميل يتطلب كلمة مرور . |
| [DevicePasswordExpiration](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordexpiration) { get; set; } | يحدد الحد الأقصى لعدد الأيام حتى انتهاء صلاحية كلمة المرور . يمكن أن يكون DevicePasswordExpiration فارغًا ، مما يشير إلى عدم تعيين سياسة انتهاء صلاحية كلمة المرور. يتم سرد القيم الصالحة أدناه: = 0 - كلمات المرور لا تنتهي صلاحيتها . &gt; 0 - تنتهي صلاحية كلمات المرور. في الحد الأقصى لعدد الأيام المحدد . إذا كان DevicePasswordExpiration فارغًا ، فيجب على العميل التعامل مع هذه القيمة على أنها 0. إذا تم تعيين قيمة DevicePasswordEnabled على FALSE ، فيجب أن يتجاهل العميل هذه الخاصية. |
| [DevicePasswordHistory](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordhistory) { get; set; } | يحدد الحد الأدنى لعدد كلمات المرور المستخدمة سابقًا والمخزنة لمنع إعادة الاستخدام من قبل العميل. تم سرد القيم الصالحة أدناه: = 0 - تخزين كلمات المرور المستخدمة سابقًا غير مطلوب . &gt; 0 - الحد الأدنى لعدد كلمات المرور المستخدمة مسبقًا المراد استخدامها store. إذا كانت DevicePasswordHistory خالية ، فيجب على العميل معاملة هذه القيمة على أنها 0. إذا تم تعيين قيمة DevicePasswordEnabled على TRUE ، فإن العميل لا يسمح للمستخدم باستخدام كلمة مرور سابقة مخزنة بعد انتهاء صلاحية كلمة المرور. تم تعيين DevicePasswordEnabled على FALSE ، يجب على العميل تجاهل هذه الخاصية. |
| [MaxAttachmentSize](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxattachmentsize) { get; set; } | تحديد الحد الأقصى لحجم المرفقات بالبايت كما هو محدد بواسطة نهج الأمان. إذا كانت الخاصية خالية ، يفسر العميل ذلك على أنه يعني أنه لم يتم تعيين الحد الأقصى لحجم المرفقات بواسطة نهج الأمان. |
| [MaxCalendarAgeFilter](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxcalendaragefilter) { get; set; } | يحدد الحد الأقصى لعدد أيام التقويم التي يمكن مزامنتها. يتم سرد القيم الصالحة أدناه: كل الأيام أسبوعان شهر واحد 3 شهور 6 شهور |
| [MaxDevicePasswordFailedAttempts](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxdevicepasswordfailedattempts) { get; set; } | تحديد الحد الأقصى لعدد محاولات تسجيل الدخول الفاشلة بكلمة المرور المسموح بها. يجب على العميل إجراء مسح محلي أو إدخال وضع تأمين مؤقت إذا تم الوصول إلى الحد الأقصى لعدد محاولات تسجيل الدخول الفاشلة. فارغ ، يفسر العميل هذا على أنه يعني أنه لم يتم تعيين الحد الأقصى لعدد محاولات تسجيل الدخول الفاشلة بواسطة نهج الأمان. إذا تم تعيين قيمة DevicePasswordEnabled على FALSE ، يتجاهل العميل هذه الخاصية. |
| [MaxEmailAgeFilter](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxemailagefilter) { get; set; } | يحدد الحد الأقصى لعمر البريد الإلكتروني للمزامنة. يتم سرد القيم الصالحة أدناه: مزامنة all يوم واحد 3 أيام أسبوع واحد أسبوعان شهر واحد |
| [MaxEmailBodyTruncationSize](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxemailbodytruncationsize) { get; set; } | يحدد حجم الاقتطاع للنص العادي - البريد الإلكتروني المنسق. يتم سرد القيم الصالحة أدناه: -1 لا اقتطاع . = 0 اقتطاع الرأس فقط. &gt; 0 اقتطاع نص البريد الإلكتروني إلى الحجم المحدد. |
| [MaxEmailHTMLBodyTruncationSize](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxemailhtmlbodytruncationsize) { get; set; } | يحدد حجم الاقتطاع للبريد الإلكتروني بتنسيق HTML. يتم سرد القيم الصالحة أدناه: -1 لا اقتطاع . = 0 اقتطاع الرأس فقط. |
| [MaxInactivityTimeDeviceLock](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxinactivitytimedevicelock) { get; set; } | يحدد الحد الأقصى لعدد ثواني عدم النشاط قبل أن يقوم الجهاز بإقفال نفسه. إذا كانت هذه القيمة أكبر من أو تساوي 9999 ، يفسرها العميل على أنها غير محدودة. إذا كان MaxInactivityTimeDeviceLock فارغًا ، فسيفسر العميل ذلك على أنه يعني أنه لم يتم تعيين قفل الجهاز للوقت بواسطة سياسة الأمان. |
| [MinDevicePasswordComplexCharacters](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/mindevicepasswordcomplexcharacters) { get; set; } | يحدد المستوى المطلوب من التعقيد لكلمة مرور العميل. تحدد القيمة عدد مجموعات الأحرف المطلوبة لتكون موجودة في كلمة المرور. يتم تعريف مجموعات الأحرف على النحو التالي: الأحرف الأبجدية الصغيرة = 1 الأحرف الأبجدية الصغيرة والكبيرة = 2 الأحرف الأبجدية الصغيرة والحروف الأبجدية الكبيرة والأرقام = 3 الأحرف الصغيرة والكبيرة الأبجدية والأرقام والأحرف غير الأبجدية الرقمية = 4 على سبيل المثال: إذا كانت قيمة MinDevicePasswordComplexCharacters هي 2 ، فستكون كلمة المرور ذات الأحرف الأبجدية الكبيرة والصغيرة كافية ، كما هو الحال مع كلمة المرور ذات الأحرف الأبجدية الصغيرة والأرقام . |
| [MinDevicePasswordLength](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/mindevicepasswordlength) { get; set; } | تحديد الحد الأدنى لطول كلمة مرور العميل . يمكن أن يكون MinDevicePasswordLength فارغًا أو أن يكون له قيمة لا تقل عن 1 ولا تزيد عن 16. إذا كانت الخاصية خالية أو كانت قيمة هذه الخاصية 1 ، فلا يوجد حد أدنى لطول كلمه مرور الجهاز. إذا كانت قيمة DevicePasswordEnabled FALSE ، فيجب على العميل تجاهل هذه الخاصية . |
| [PasswordRecoveryEnabled](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/passwordrecoveryenabled) { get; set; } | يحدد ما إذا كان الخادم يدعم تخزين كلمة مرور الاسترداد ليتم إرسالها من قبل العميل باستخدام الأمر Settings . كلمة مرور الاسترداد هي كلمة مرور خاصة تم إنشاؤها بواسطة العميل والتي تمنح المسؤول أو المستخدم القدرة على تسجيل الدخول إلى الجهاز مرة واحدة ، وبعد ذلك يُطلب من المستخدم إنشاء كلمة مرور جديدة. يقوم العميل بعد ذلك بإنشاء كلمة مرور استرداد جديدة. إذا تم تعيين PasswordRecoveryEnabled على TRUE ، فإن الخادم يدعم تخزين كلمة مرور الاسترداد التي يرسلها الجهاز. إذا تم تعيين الخاصية على FALSE ، فلا ينبغي للجهاز إرسال كلمة مرور الاسترداد ، لأن الخادم لا يدعم تخزين كلمة المرور. إذا كانت PasswordRecoveryEnabled خالية ، فيجب على العميل التعامل مع هذه القيمة على أنها FALSE. إذا كانت قيمة DevicePasswordEnabled FALSE ، فيجب على العميل تجاهل هذه الخاصية. يجب تجاهل هذه الخاصية إذا كان العميل لا يدعم كلمات مرور الاسترداد. |
| [RequireDeviceEncryption](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiredeviceencryption) { get; set; } | يحدد ما إذا كان العميل يستخدم التشفير. |
| [RequireEncryptedSMIMEMessages](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requireencryptedsmimemessages) { get; set; } | يحدد ما إذا كان العميل سيرسل رسائل بريد إلكتروني مشفرة. |
| [RequireEncryptionSMIMEAlgorithm](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requireencryptionsmimealgorithm) { get; set; } | يحدد الخوارزمية المستخدمة عند تشفير رسائل S / MIME. |
| [RequireManualSyncWhenRoaming](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiremanualsyncwhenroaming) { get; set; } | يحدد ما إذا كان الجهاز يتطلب المزامنة اليدوية أثناء تجوال الجهاز. |
| [RequireSignedSMIMEAlgorithm](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiresignedsmimealgorithm) { get; set; } | يحدد الخوارزمية المستخدمة عند توقيع رسائل S / MIME. |
| [RequireSignedSMIMEMessages](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiresignedsmimemessages) { get; set; } | يحدد ما إذا كان العميل سيرسل رسائل S / MIME موقعة. |
| [RequireStorageCardEncryption](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requirestoragecardencryption) { get; set; } | يحدد ما إذا كان الجهاز يشفر المحتوى المخزن على الجهاز. يجب تجاهل هذه الخاصية إذا كان العميل لا يدعم تخزين البيانات على وحدة تخزين قابلة للإزالة. |
| [UnapprovedInROMApplicationList](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/unapprovedinromapplicationlist) { get; } | تحديد قائمة بالتطبيقات داخل ذاكرة القراءة فقط التي لم يتم اعتمادها للتنفيذ. تتأثر فقط التطبيقات المثبتة مسبقًا في ROM بالإدخالات الموجودة في هذه الخاصية. لا تنطبق هذه الخاصية على التطبيقات المثبتة في الذاكرة. |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
