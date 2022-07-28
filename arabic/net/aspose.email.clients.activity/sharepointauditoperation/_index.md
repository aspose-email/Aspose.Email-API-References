---
title: SharePointAuditOperation
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: عمليات تدقيق SharePoint
type: docs
weight: 2760
url: /ar/net/aspose.email.clients.activity/sharepointauditoperation/
---
## SharePointAuditOperation enumeration

عمليات تدقيق SharePoint

```csharp
public enum SharePointAuditOperation
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| AccessInvitationAccepted | `0` | هذه العملية قيد المعاينة. قام مستلم دعوة لعرض أو تحرير ملف مشترك (أو مجلد) بالوصول إلى الملف المشترك عن طريق النقر فوق الارتباط الموجود في الدعوة. |
| AccessInvitationCreated | `1` | هذه العملية قيد المعاينة. يرسل المستخدم دعوة إلى شخص آخر (داخل مؤسسته أو خارجها) لعرض ملف أو مجلد مشترك أو تحريره على موقع SharePoint أو OneDrive for Business. تحدد تفاصيل إدخال الحدث اسم الملف الذي تمت مشاركته والمستخدم الذي تم إرسال الدعوة إليه ونوع إذن المشاركة المحدد من قبل الشخص الذي أرسل الدعوة. |
| AccessInvitationExpired | `2` | هذه العملية قيد المعاينة. تنتهي صلاحية الدعوة المرسلة إلى مستخدم خارجي. بشكل افتراضي ، تنتهي صلاحية الدعوة المرسلة إلى مستخدم خارج مؤسستك بعد 7 أيام إذا لم يتم قبول الدعوة. |
| AccessInvitationRevoked | `3` | هذه العملية قيد المعاينة. يسحب مسؤول الموقع أو مالك الموقع أو المستند في SharePoint أو OneDrive for Business دعوة تم إرسالها إلى مستخدم خارج مؤسستك. يمكن سحب الدعوة قبل قبولها فقط. |
| AccessInvitationUpdated | `4` | هذه العملية قيد المعاينة. يقوم المستخدم الذي قام بإنشاء وإرسال دعوة إلى شخص آخر لعرض ملف مشترك (أو مجلد) أو تحريره على موقع SharePoint أو OneDrive for Business بإعادة إرسال الدعوة. |
| AccessRequestApproved | `5` | يوافق مسؤول الموقع أو مالك الموقع أو المستند في SharePoint أو OneDrive for Business على طلب المستخدم للوصول إلى الموقع أو المستند. |
| AccessRequestCreated | `6` | يطلب المستخدم الوصول إلى موقع أو مستند في SharePoint أو OneDrive for Business ليس لديه إذن بالوصول إليه . |
| AccessRequestRejected | `7` | هذه العملية قيد المعاينة. يرفض مسؤول الموقع أو مالك موقع أو مستند في SharePoint طلب المستخدم للوصول إلى الموقع أو المستند . |
| ActivationEnabled | `8` | هذه العملية قيد المعاينة. يمكن للمستخدمين تمكين قوالب النماذج التي لا تحتوي على تعليمات برمجية للنموذج ، أو تتطلب ثقة كاملة ، أو تمكين العرض على جهاز محمول ، أو استخدام اتصال بيانات يديره مسؤول الخادم. |
| AdministratorAddedToTermStore | `9` | هذه العملية قيد المعاينة. تمت إضافة مدير متجر المدة. |
| AdministratorDeletedFromTermStore | `10` | هذه العملية قيد المعاينة. تم حذف مدير متجر المدة. |
| AllowGroupCreationSet | `11` | هذه العملية قيد المعاينة. يضيف مسؤول الموقع أو المالك مستوى إذنًا إلى موقع SharePoint أو OneDrive for Business يسمح للمستخدم الذي قام بتعيين هذا الإذن بإنشاء مجموعة لهذا الموقع . |
| AppCatalogCreated | `12` | هذه العملية قيد المعاينة. تم إنشاء كتالوج التطبيقات لإتاحة تطبيقات الأعمال المخصصة لبيئة SharePoint الخاصة بك. |
| AuditPolicyRemoved | `13` | هذه العملية قيد المعاينة. تمت إزالة نهج دورة حياة المستند لمجموعة مواقع مشتركة. |
| AuditPolicyUpdate | `14` | هذه العملية قيد المعاينة. تم تحديث نهج دورة حياة المستند لمجموعة مواقع مشتركة. |
| AzureStreamingEnabledSet | `15` | هذه العملية قيد المعاينة. سمح مالك مدخل الفيديو ببث الفيديو من Azure . |
| CollaborationTypeModified | `16` | هذه العملية قيد المعاينة. تم تعديل نوع التعاون المسموح به على المواقع (على سبيل المثال ، الإنترانت أو الإكسترانت أو العام). |
| ConnectedSiteSettingModified | `17` | قام المستخدم إما بإنشاء أو تعديل أو حذف الارتباط بين مشروع وموقع مشروع أو يقوم المستخدم بتعديل إعداد المزامنة على الارتباط في Project Web App . |
| CreateSSOApplication | `18` | هذه العملية قيد المعاينة. تم إنشاء التطبيق الهدف في خدمة المتجر الآمن . |
| CustomFieldOrLookupTableCreated | `19` | أنشأ المستخدم ملفًا مخصصًا أو جدول / عنصر بحث في Project Web App. |
| CustomFieldOrLookupTableDeleted | `20` | حذف المستخدم حقلاً مخصصًا أو جدول / عنصر بحث في Project Web App. |
| CustomFieldOrLookupTableModified | `21` | قام المستخدم بتعديل حقل مخصص أو جدول / عنصر بحث في Project Web App. |
| CustomizeExemptUsers | `22` | هذه العملية قيد المعاينة. قام المسؤول العام بتخصيص قائمة وكلاء المستخدم المعفيين في مركز إدارة SharePoint. يمكنك تحديد وكلاء المستخدم الذين سيتم إعفاؤهم من تلقي صفحة ويب كاملة لفهرستها. هذا يعني أنه عندما يواجه وكيل مستخدم قمت بتحديده على أنه مستثنى نموذج InfoPath ، فسيتم إرجاع النموذج كملف XML بدلاً من صفحة ويب كاملة. هذا يجعل فهرسة نماذج InfoPath أسرع. |
| DefaultLanguageChangedInTermStore | `23` | هذه العملية قيد المعاينة. تم تغيير إعداد اللغة في مخزن المصطلحات. |
| DelegateModified | `24` | قام المستخدم بإنشاء أو تعديل مفوض أمان في Project Web App. |
| DelegateRemoved | `25` | حذف المستخدم مفوض أمان في Project Web App . |
| DeleteSSOApplication | `26` | هذه العملية قيد المعاينة. تم حذف تطبيق SSO . |
| eDiscoveryHoldApplied | `27` | هذه العملية قيد المعاينة. تم وضع تعليق موضعي على مصدر محتوى. تتم إدارة عمليات التعليق الموضعية باستخدام مجموعة مواقع eDiscovery (مثل مركز eDiscovery) في SharePoint. |
| eDiscoveryHoldRemoved | `28` | هذه العملية قيد المعاينة. تمت إزالة التعليق الموضعي من مصدر المحتوى. تتم إدارة عمليات التعليق الموضعية باستخدام مجموعة مواقع eDiscovery (مثل مركز eDiscovery) في SharePoint. |
| eDiscoverySearchPerformed | `29` | هذه العملية قيد المعاينة. تم إجراء بحث eDiscovery باستخدام مجموعة مواقع eDiscovery في SharePoint. |
| EngagementAccepted | `30` | يقبل المستخدم مشاركة مورد في Project Web App . |
| EngagementModified | `31` | يعدل المستخدم مشاركة مورد في Project Web App . |
| EngagementRejected | `32` | رفض المستخدم مشاركة مورد في Project Web App . |
| EnterpriseCalendarModified | `33` | ينسخ المستخدم أو يعدل أو يحذف تقويم مؤسسة في Project Web App . |
| EntityDeleted | `34` | يحذف المستخدم الجدول الزمني في Project Web App . |
| EntityForceCheckedIn | `35` | يفرض المستخدم تسجيل وصول على تقويم أو حقل مخصص أو جدول بحث في Project Web App. |
| ExemptUserAgentSet | `36` | هذه العملية قيد المعاينة. يضيف المسؤول العام وكيل مستخدم إلى قائمة وكلاء المستخدم المستثناة في مركز إدارة SharePoint. |
| FileAccessed | `37` | يصل حساب المستخدم أو النظام إلى ملف على موقع SharePoint أو OneDrive for Business. يمكن لحسابات النظام أيضًا إنشاء أحداث FileAccessed . |
| FileCheckOutDiscarded | `38` | هذه العملية قيد المعاينة. يتجاهل المستخدم (أو يتراجع) عن ملف مسحوب. هذا يعني أنه يتم تجاهل أي تغييرات أجروها على الملف عند سحبه ، ولا يتم حفظها في إصدار المستند في مكتبة المستندات. |
| FileCheckedIn | `39` | هذه العملية قيد المعاينة. يقوم المستخدم بإيداع مستند قام بسحبه من مكتبة مستندات SharePoint أو OneDrive for Business . |
| FileCheckedOut | `40` | هذه العملية قيد المعاينة. قام المستخدم بسحب مستند موجود في مكتبة مستندات SharePoint أو OneDrive for Business. يمكن للمستخدمين سحب وإجراء تغييرات على المستندات التي تمت مشاركتها معهم. |
| FileCopied | `41` | ينسخ المستخدم مستندًا من موقع SharePoint أو OneDrive for Business. يمكن حفظ الملف المنسوخ في مجلد آخر على الموقع. |
| FileDeleted | `42` | يحذف المستخدم مستندًا من SharePoint أو موقع OneDrive for Business . |
| FileDeletedFirstStageRecycleBin | `43` | يحذف المستخدم ملفًا من سلة المحذوفات على موقع SharePoint أو OneDrive for Business. |
| FileDeletedSecondStageRecycleBin | `44` | يحذف المستخدم ملفًا من سلة محذوفات المرحلة الثانية على موقع SharePoint أو OneDrive for Business. |
| FileDownloaded | `45` | يقوم المستخدم بتنزيل مستند من موقع SharePoint أو OneDrive for Business. |
| FileFetched | `46` | تم استبدال هذا الحدث بالحدث FileAccessed ، وتم إهماله. |
| FileModified | `47` | يعدل حساب المستخدم أو النظام المحتوى أو خصائص المستند الموجود على موقع SharePoint أو OneDrive for Business . |
| FileMoved | `48` | يقوم المستخدم بنقل مستند من موقعه الحالي على موقع SharePoint أو OneDrive for Business إلى موقع جديد. |
| FilePreviewed | `49` | يقوم المستخدم بمعاينة مستند على SharePoint أو موقع OneDrive for Business . |
| FileRenamed | `50` | يقوم المستخدم بإعادة تسمية مستند على موقع SharePoint أو OneDrive for Business . |
| FileRestored | `51` | يستعيد المستخدم مستندًا من سلة المحذوفات لموقع SharePoint أو OneDrive for Business . |
| FileSyncDownloadedFull | `52` | يقوم المستخدم بتأسيس علاقة مزامنة وتنزيل الملفات بنجاح لأول مرة إلى أجهزة الكمبيوتر الخاصة به من مكتبة مستندات SharePoint أو OneDrive for Business . |
| FileSyncDownloadedPartial | `53` | قام المستخدم بتنزيل أية تغييرات على الملفات من SharePoint أو OneDrive for Business بنجاح. يشير هذا الحدث إلى أنه تم تنزيل أي تغييرات تم إجراؤها على الملفات الموجودة في مكتبة المستندات على جهاز الكمبيوتر الخاص بالمستخدم. تم تنزيل التغييرات فقط لأنه تم تنزيل مكتبة المستندات مسبقًا بواسطة المستخدم (كما هو مشار إليه بواسطة الحدث FileSyncDownloadedFull) . |
| FileSyncUploadedFull | `54` | هذه العملية قيد المعاينة. يقوم المستخدم بتأسيس علاقة مزامنة ويقوم بتحميل الملفات بنجاح لأول مرة من جهاز الكمبيوتر الخاص به إلى مكتبة مستندات SharePoint أو OneDrive for Business . |
| FileSyncUploadedPartial | `55` | هذه العملية قيد المعاينة. يقوم المستخدم بتحميل التغييرات على الملفات بنجاح على مكتبة مستندات SharePoint أو OneDrive for Business. يشير هذا الحدث إلى أنه تم بنجاح تحميل أية تغييرات تم إجراؤها على الإصدار المحلي لملف من مكتبة مستندات إلى مكتبة المستندات. يتم إلغاء تحميل التغييرات فقط لأن هذه الملفات تم تحميلها مسبقًا بواسطة المستخدم (كما هو موضح بواسطة الحدث FileSyncUploadedFull) . |
| FileUploaded | `56` | يقوم المستخدم بتحميل مستند إلى مجلد على موقع SharePoint أو OneDrive for Business . |
| FileViewed | `57` | تم استبدال هذا الحدث بالحدث FileAccessed ، وتم إهماله. |
| FolderCopied | `58` | ينسخ المستخدم مجلدًا من موقع SharePoint أو OneDrive for Business إلى موقع آخر في SharePoint أو OneDrive for Business . |
| FolderCreated | `59` | ينشئ المستخدم مجلدًا على موقع SharePoint أو OneDrive for Business . |
| FolderDeleted | `60` | يحذف المستخدم مجلدًا من موقع SharePoint أو OneDrive for Business . |
| FolderDeletedFirstStageRecycleBin | `61` | يحذف المستخدم مجلدًا من سلة المحذوفات على موقع SharePoint أو OneDrive for Business . |
| FolderDeletedSecondStageRecycleBin | `62` | يحذف المستخدم مجلدًا من سلة محذوفات المرحلة الثانية على موقع SharePoint أو OneDrive for Business . |
| FolderModified | `63` | يعدل المستخدم مجلدًا على موقع SharePoint أو OneDrive for Business. يتضمن هذا الحدث تغييرات بيانات تعريف المجلد ، مثل العلامات والخصائص. |
| FolderMoved | `64` | يقوم المستخدم بنقل مجلد من موقع SharePoint أو OneDrive for Business . |
| FolderRenamed | `65` | يعيد المستخدم تسمية مجلد على موقع SharePoint أو OneDrive for Business . |
| FolderRestored | `66` | يستعيد المستخدم مجلدًا من "سلة المحذوفات" على موقع SharePoint أو OneDrive for Business . |
| GroupAdded | `67` | هذه العملية قيد المعاينة. ينشئ مسؤول الموقع أو مالكه مجموعة لموقع SharePoint أو OneDrive for Business ، أو ينفذ مهمة تؤدي إلى إنشاء مجموعة. على سبيل المثال ، في المرة الأولى التي ينشئ فيها المستخدم ارتباطًا لمشاركة ملف ، تتم إضافة مجموعة نظام إلى موقع OneDrive for Business الخاص بالمستخدم. يمكن أن يكون هذا الحدث أيضًا نتيجة قيام المستخدم بإنشاء ارتباط بأذونات تحرير لملف مشترك. |
| GroupRemoved | `68` | هذه العملية قيد المعاينة. يحذف المستخدم مجموعة من موقع SharePoint أو OneDrive for Business . |
| GroupUpdated | `69` | هذه العملية قيد المعاينة. قام مسؤول الموقع أو المالك بتغيير إعدادات المجموعة لموقع SharePoint أو OneDrive for Business. يمكن أن يشمل ذلك تغيير اسم المجموعة ومن يمكنه عرض عضوية المجموعة أو تعديلها وكيفية التعامل مع طلبات العضوية. |
| LanguageAddedToTermStore | `70` | هذه العملية قيد المعاينة. اللغة المضافة إلى مخزن المصطلحات . |
| LanguageRemovedFromTermStore | `71` | هذه العملية قيد المعاينة. تمت إزالة اللغة من مخزن المصطلحات . |
| LegacyWorkflowEnabledSet | `72` | هذه العملية قيد المعاينة. يضيف مسؤول الموقع أو المالك نوع محتوى مهمة سير عمل SharePoint إلى الموقع. يمكن للمسؤولين العالميين أيضًا تمكين تدفقات العمل للمؤسسة بأكملها في مركز إدارةSharePoint. |
| LookAndFeelModified | `73` | يعدل المستخدم التشغيل السريع أو تنسيقات مخطط جانت أو تنسيقات المجموعة. أو يقوم المستخدم بإنشاء أو تعديل أو حذف طريقة عرض في Project Web App. |
| ManagedSyncClientAllowed | `74` | ينشئ المستخدم بنجاح علاقة مزامنة مع موقع SharePoint أو OneDrive for Business. نجحت علاقة المزامنة لأن كمبيوتر المستخدم عضو في مجال تمت إضافته إلى قائمة المجالات (تسمى قائمة المستلمين الموثوق بهم) التي يمكنها الوصول إلى مكتبات المستندات في مؤسستك. لمزيد من المعلومات حول هذه الميزة ، راجع استخدام أوامر cmdlets لـ Windows PowerShell لتمكين مزامنة OneDrive للمجالات الموجودة في قائمة المستلمين الآمنين. |
| MaxQuotaModified | `75` | هذه العملية قيد المعاينة. تم تعديل الحد الأقصى للحصة النسبية للموقع. |
| MaxResourceUsageModified | `76` | هذه العملية قيد المعاينة. تم تعديل الحد الأقصى المسموح به لاستخدام الموارد لأحد المواقع. |
| MySitePublicEnabledSet | `77` | هذه العملية قيد المعاينة. تم تعيين العلامة التي تمكّن المستخدمين من الحصول على MySites عامة من قبل مسؤول SharePoint. |
| NewsFeedEnabledSet | `78` | هذه العملية قيد المعاينة. يمكّن مسؤول الموقع أو مالكه موجزات RSS لموقع SharePoint أو OneDrive for Business. يمكن للمسؤولين العموميين تمكين موجزات RSS للمؤسسة بأكملها في مركز إدارة SharePoint. |
| ODBNextUXSettings | `79` | هذه العملية قيد المعاينة. تم تمكين واجهة مستخدم جديدة لـ OneDrive for Business . |
| OfficeOnDemandSet | `80` | هذه العملية قيد المعاينة. يقوم مسؤول الموقع بتمكين Office عند الطلب ، مما يتيح للمستخدمين الوصول إلى أحدث إصدار من تطبيقات Office لسطح المكتب. تم تمكين Office عند الطلب في مركز إدارة SharePoint ويتطلب اشتراك Office 365 الذي يتضمن تطبيقات Office كاملة ومثبتة . |
| PageViewed | `81` | يعرض المستخدم صفحة على موقع SharePoint أو موقع OneDrive for Business. لا يشمل ذلك عرض ملفات مكتبة المستندات من موقع SharePoint أو موقع One Drive for Business على مستعرض . |
| PeopleResultsScopeSet | `82` | هذه العملية قيد المعاينة. يقوم مسؤول الموقع بإنشاء أو تغيير مصدر النتائج لعمليات البحث عن أشخاص لموقع SharePoint . |
| PermissionSyncSettingModified | `83` | يعدل المستخدم إعدادات مزامنة أذونات المشروع في Project Web App. |
| PermissionTemplateModified | `84` | يقوم المستخدم بإنشاء أو تعديل أو حذف قالب أذونات في Project Web App. |
| PortfolioDataAccessed | `85` | يصل المستخدم إلى محتوى الحافظة (مكتبة برامج التشغيل ، وتخصيص برنامج التشغيل ، وتحليلات الحافظة) في Project Web App . |
| PortfolioDataModified | `86` | ينشئ المستخدم بيانات الحافظة أو يعدلها أو يحذفها (مكتبة برنامج التشغيل ، تحديد أولوية السائق ، تحليلات الحافظة) في Project Web App . |
| PreviewModeEnabledSet | `87` | هذه العملية قيد المعاينة. يقوم مسؤول الموقع بتمكين معاينة المستند لموقع SharePoint . |
| ProjectAccessed | `88` | يصل المستخدم إلى محتوى المشروع في Project Web App . |
| ProjectCheckedIn | `89` | قام المستخدم بإيداع مشروع قام بسحبه من Project Web App . |
| ProjectCheckedOut | `90` | قام المستخدم بسحب مشروع موجود في Project Web App. يمكن للمستخدمين سحب وإجراء تغييرات على المشاريع التي لديهم إذن بفتحها. |
| ProjectCreated | `91` | ينشئ المستخدم مشروعًا في Project Web App . |
| ProjectDeleted | `92` | يحذف المستخدم مشروعًا في Project Web App . |
| ProjectForceCheckedIn | `93` | يفرض المستخدم تسجيل الوصول إلى مشروع في Project Web App . |
| ProjectModified | `94` | يعدل المستخدم مشروعًا في Project Web App . |
| ProjectPublished | `95` | ينشر المستخدم مشروعًا في Project Web App . |
| ProjectWorkflowRestarted | `96` | يقوم المستخدم بإعادة تشغيل سير عمل في Project Web App . |
| PWASettingsAccessed | `97` | وصول المستخدم إلى إعدادات Project Web App عبر CSOM. |
| PWASettingsModified | `98` | يعدل المستخدم تكوين Project Web App . |
| QueueJobStateModified | `99` | يقوم المستخدم بإلغاء أو إعادة تشغيل مهمة قائمة انتظار في Project Web App. |
| QuotaWarningEnabledModified | `100` | هذه العملية قيد المعاينة. تعديل تحذير حصة التخزين. |
| RenderingEnabled | `101` | هذه العملية قيد المعاينة. سيتم تقديم قوالب النماذج الممكّنة بواسطة المستعرض بواسطة خدمات نماذج InfoPath. |
| ReportingAccessed | `102` | وصل المستخدم إلى نقطة نهاية التقرير في Project Web App . |
| ReportingSettingModified | `103` | يعدل المستخدم تكوين التقارير في Project Web App . |
| ResourceAccessed | `104` | يصل المستخدم إلى محتوى موارد المؤسسة في Project Web App . |
| ResourceCheckedIn | `105` | قام المستخدم بإيداع مورد مؤسسة قام بسحبه من Project Web App . |
| ResourceCheckedOut | `106` | قام المستخدم بسحب مورد مؤسسة موجود في Project Web App . |
| ResourceCreated | `107` | ينشئ المستخدم مورد مؤسسة في Project Web App . |
| ResourceDeleted | `108` | يحذف المستخدم مورد مؤسسة في Project Web App . |
| ResourceForceCheckedIn | `109` | يفرض المستخدم تسجيل وصول لمورد مؤسسة في Project Web App . |
| ResourceModified | `110` | يعدل المستخدم مورد مؤسسة في Project Web App . |
| ResourcePlanCheckedInOrOut | `111` | يقوم المستخدم بإيداع أو إخراج خطة موارد في Project Web App. |
| ResourcePlanModified | `112` | يعدل المستخدم خطة موارد في Project Web App . |
| ResourcePlanPublished | `113` | ينشر المستخدم خطة موارد في Project Web App . |
| ResourceRedacted | `114` | يقوم المستخدم بتنقيح مورد مؤسسة يزيل كافة المعلومات الشخصية في Project Web App . |
| ResourceWarningEnabledModified | `115` | هذه العملية قيد المعاينة. تم تعديل تحذير حصة الموارد. |
| SSOGroupCredentialsSet | `116` | هذه العملية قيد المعاينة. تعيين بيانات اعتماد المجموعة في خدمة المخزن الآمن. |
| SSOUserCredentialsSet | `117` | هذه العملية قيد المعاينة. تعيين بيانات اعتماد المستخدم في خدمة التخزين الآمن. |
| SearchCenterUrlSet | `118` | هذه العملية قيد المعاينة. تعيين عنوان URL لمركز البحث. |
| SecondaryMySiteOwnerSet | `119` | هذه العملية قيد المعاينة. أضاف مستخدم مالكًا ثانويًا إلى MySite. |
| SecurityCategoryModified | `120` | يقوم المستخدم بإنشاء فئة أمان أو تعديلها أو حذفها في Project Web App. |
| SecurityGroupModified | `121` | يقوم المستخدم بإنشاء مجموعة أمان أو تعديلها أو حذفها في Project Web App. |
| SendToConnectionAdded | `122` | هذه العملية قيد المعاينة. يقوم المسؤول العام بإنشاء اتصال "إرسال إلى" جديد في صفحة إدارة السجلات في مركز إدارة SharePoint. يحدد اتصال Send To الإعدادات لمستودع المستندات أو مركز السجلات. عند إنشاء اتصال Send To ، يمكن لمنظم المحتوى إرسال المستندات إلى الموقع المحدد. |
| SendToConnectionRemoved | `123` | هذه العملية قيد المعاينة. المسؤول العام يحذف اتصال إرسال إلى على صفحة إدارة السجلات في مركز إدارة SharePoint. |
| SharedLinkCreated | `124` | ينشئ المستخدم ارتباطًا إلى ملف مشترك في SharePoint أو OneDrive for Business. يمكن إرسال هذا الارتباط إلى أشخاص آخرين لمنحهم حق الوصول إلى الملف. يمكن للمستخدم إنشاء نوعين من الروابط: رابط يسمح للمستخدم بمشاهدة الملف المشترك وتحريره ، أو رابط يسمح للمستخدم بمشاهدة الملف فقط. |
| SharedLinkDisabled | `125` | هذه العملية قيد المعاينة. يقوم المستخدم بتعطيل ارتباط (نهائيًا) تم إنشاؤه لمشاركة ملف. |
| SharingInvitationAccepted | `126` | هذه العملية قيد المعاينة. يقبل المستخدم دعوة لمشاركة ملف أو مجلد. يتم تسجيل هذا الحدث عندما يقوم المستخدم بمشاركة ملف مع مستخدمين آخرين. |
| SharingRevoked | `127` | هذه العملية قيد المعاينة. يقوم المستخدم بإلغاء مشاركة ملف أو مجلد تمت مشاركته مسبقًا مع مستخدمين آخرين. يتم تسجيل هذا الحدث عندما يتوقف المستخدم عن مشاركة ملف مع مستخدمين آخرين. |
| SharingSet | `128` | يشارك المستخدم ملفًا أو مجلدًا موجودًا في SharePoint أو OneDrive for Business مع مستخدم آخر داخل مؤسسته. |
| SiteAdminChangeRequest | `129` | هذه العملية قيد المعاينة. يطلب المستخدم إضافته كمسؤول مجموعة مواقع لمجموعة مواقع SharePoint. يمتلك مسؤولو مجموعة الموقع أذونات تحكم كاملة لمجموعة الموقع وكافة المواقع الفرعية. |
| SiteCollectionAdminAdded | `130` | هذه العملية قيد المعاينة. يضيف مسؤول أو مالك مجموعة المواقع شخصًا كمسؤول مجموعة مواقع مشتركة لموقع SharePoint أو OneDrive for Business. يمتلك مسؤولو مجموعة الموقع أذونات تحكم كاملة لمجموعة الموقع وكافة المواقع الفرعية. |
| SiteCollectionCreated | `131` | هذه العملية قيد المعاينة. ينشئ المسؤول العام مجموعة مواقع جديدة في مؤسسة SharePoint . |
| SiteRenamed | `132` | هذه العملية قيد المعاينة. مسؤول الموقع أو مالكه يعيد تسمية SharePoint أو OneDrive for Business site |
| StatusReportModified | `133` | يقوم المستخدم بإنشاء تقرير حالة أو تعديله أو حذفه في Project Web App. |
| SyncGetChanges | `134` | هذه العملية قيد المعاينة. ينقر المستخدم فوق "المزامنة" في علبة الإجراءات الموجودة في SharePoint أو OneDrive for Business لمزامنة أية تغييرات يتم إجراؤها على ملف في مكتبة مستندات مع أجهزة الكمبيوتر الخاصة بهم. |
| TaskStatusAccessed | `135` | يصل المستخدم إلى حالة مهمة واحدة أو أكثر في Project Web App. |
| TaskStatusApproved | `136` | يوافق المستخدم على تحديث حالة مهمة واحدة أو أكثر في Project Web App. |
| TaskStatusRejected | `137` | يرفض المستخدم تحديث حالة مهمة واحدة أو أكثر في Project Web App . |
| TaskStatusSaved | `138` | يحفظ المستخدم تحديث حالة لمهمة واحدة أو أكثر في Project Web App . |
| TaskStatusSubmitted | `139` | يرسل المستخدم تحديث حالة لمهمة واحدة أو أكثر في Project Web App . |
| TimesheetAccessed | `140` | يصل المستخدم إلى جدول زمني في Project Web App . |
| TimesheetApproved | `141` | يوافق المستخدم على الجدول الزمني في Project Web App . |
| TimesheetRejected | `142` | رفض المستخدم الجدول الزمني في Project Web App . |
| TimesheetSaved | `143` | يحفظ المستخدم جدول زمني في Project Web App . |
| TimesheetSubmitted | `144` | يرسل المستخدم جدول زمني للحالة في Project Web App . |
| UnmanagedSyncClientBlocked | `145` | يحاول المستخدم إنشاء علاقة مزامنة مع موقع SharePoint أو OneDrive for Business من جهاز كمبيوتر ليس عضوًا في مجال مؤسستك أو عضو في مجال لم تتم إضافته إلى قائمة المجالات ( تسمى قائمة المستلمين الموثوق بهم) التي يمكنها الوصول إلى مكتبات المستندات في مؤسستك. علاقة المزامنة غير مسموح بها ، ويتم حظر جهاز كمبيوتر المستخدم من مزامنة الملفات أو تنزيلها أو تحميلها في مكتبة مستندات. للحصول على معلومات حول هذه الميزة ، راجع استخدام أوامر cmdlets لـ Windows PowerShell لتمكين مزامنة OneDrive للمجالات الموجودة في قائمة المستلمين الآمنين. |
| UpdateSSOApplication | `146` | هذه العملية قيد المعاينة. تحديث التطبيق الهدف في خدمة المتجر الآمن . |
| UserAddedToGroup | `147` | هذه العملية قيد المعاينة. يضيف مسؤول الموقع أو المالك شخصًا إلى مجموعة على موقع SharePoint أو OneDrive for Business. إضافة شخص إلى مجموعة يمنح المستخدم الأذونات التي تم تعيينها للمجموعة. |
| UserRemovedFromGroup | `148` | هذه العملية قيد المعاينة. يزيل مسؤول الموقع أو مالكه شخصًا من مجموعة على موقع SharePoint أو OneDrive for Business. بعد إزالة الشخص ، لن يتم منحه الأذونات التي تم تعيينها للمجموعة. |
| WorkflowModified | `149` | يقوم المستخدم بإنشاء أو تعديل أو حذف نوع مشروع مؤسسي أو مراحل أو مراحل سير العمل في Project Web App. |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
