---
title: Aspose.Email.Clients.ActiveSync.TransportLayer
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: 
type: docs
weight: 80
url: /ar/net/aspose.email.clients.activesync.transportlayer/
---


## الطبقات

| فصل | وصف |
| --- | --- |
| [AccountInformation](./accountinformation) | يحتوي على معلومات حساب المستخدم . |
| [ActiveSyncTLClient](./activesynctlclient) | الفئة الأساسية لتطبيقات عميل ActiveSync |
| [AutodiscoverResult](./autodiscoverresult) | نتيجة عملية الاكتشاف التلقائي |
| [Body](./body) | تحديد حقل بيانات حر ذي طول متغير مرتبط بعنصر مخزن على الخادم. |
| [BodyPart](./bodypart) | تحديد تفاصيل حول جزء رسالة البريد الإلكتروني في الاستجابة. يجب تضمين عنصر BodyPart في استجابة الأمر عندما يتم تحديد BodyPartPreference في طلب. |
| [BodyPreference](./bodypreference) | يحتوي على معلومات التفضيل المتعلقة بنوع وحجم المعلومات التي يتم إرجاعها من البحث أو المزامنة أو الجلب. |
| [CertificateStatuses](./certificatestatuses) | يشير إلى ما إذا كان قد تم التحقق من صحة الشهادة بنجاح . |
| [DataContainer](./datacontainer) | يحتوي على بيانات لكائن معين ، مثل جهة اتصال أو رسالة بريد إلكتروني أو موعد تقويم أو عنصر مهمة. يمكن استخدام DataContainer لتغيير العناصر أو إضافة عناصر أو جلب العناصر على جهاز العميل أو الخادم. |
| [DeviceInformation](./deviceinformation) | الطلب الذي يتم استخدامه لإرسال خصائص جهاز العميل إلى الخادم. |
| [DevicePasswordRequest](./devicepasswordrequest) | يحدد طلب تعيين كلمة مرور الاسترداد لجهاز العميل بواسطة الخادم. لمسح كلمة مرور الاسترداد الحالية ، يجب على العميل إرسال كلمة مرور فارغة. |
| [EASProvisionDoc](./easprovisiondoc) | يحدد مجموعة إعدادات الأمان لتوفير الجهاز. |
| [EmptyFolderContentsRequest](./emptyfoldercontentsrequest) | يحتوي على طلب حول حذف محتويات مجلد . يدعم EmptyFolderContents عنصرًا فرعيًا واحدًا من عنصر Options ، وهو DeleteSubFolders ، والذي يحدد ما إذا كان سيتم حذف المجلدات الفرعية الموجودة في المجلد. إذا لم يتم تضمين خيار DeleteSubFolders في الطلب ، فلن يتم حذف المجلدات الفرعية الخاصة بـ CollectionId المحدد. |
| [FolderInfo](./folderinfo) | تحتوي فئة FolderInfo على معلومات المجلد |
| [FolderSyncResult](./foldersyncresult) | يحتوي على تغييرات في التسلسل الهرمي للمجلدات. |
| [ItemEstimate](./itemestimate) | يحتوي على تقييم للمجلد المطلوب |
| [ItemEstimateOptions](./itemestimateoptions) | يحتوي على عناصر تقوم بتصفية نتائج عملية GetItemEstimate. |
| [ItemEstimateRequest](./itemestimaterequest) | يحتوي على معلمات طلب ItemEstimate |
| [ItemOperationsEmptFldrCntntsResponce](./itemoperationsemptfldrcntntsresponce) | يحدد نص الاستجابة على أنه يحتوي على العملية التي تحذف محتويات المجلد. |
| [ItemOperationsFetchProperties](./itemoperationsfetchproperties) | يحتوي على الخصائص التي تم إرجاعها للعنصر (العناصر) في الاستجابة. |
| [ItemOperationsFetchRequest](./itemoperationsfetchrequest) | يحتوي على طلب حول استرداد عنصر من الخادم. |
| [ItemOperationsFetchResponce](./itemoperationsfetchresponce) | يحتوي على رد حول استرداد العناصر من الخادم. |
| [ItemOperationsMoveRequest](./itemoperationsmoverequest) | يحتوي على طلب حول نقل محادثة إلى مجلد معين. |
| [ItemOperationsMoveResponce](./itemoperationsmoveresponce) | يحدد نص الاستجابة على أنه يحتوي على العملية التي تنقل محادثة معينة. |
| [ItemOperationsRequest](./itemoperationsrequest) | يحتوي على طلب عمليات العنصر . |
| [ItemOperationsResponse](./itemoperationsresponse) | يحتوي على استجابة عمليات العنصر . |
| [ItOpEmpFldCntOptions](./itopempfldcntoptions) | يحتوي على خيارات عملية ItemOperations.EmptyFolderContents operation |
| [ItOpFetchOptions](./itopfetchoptions) | يحتوي على خيارات ItemOperations. عملية الجلب. |
| [ItOpMoveOptions](./itopmoveoptions) | يحتوي على خيارات عملية ItemOperations.Move . |
| [MeetingResponseRequest](./meetingresponserequest) | يحدد طلب الاجتماع الذي يتم الاستجابة له والاستجابة لطلب الاجتماع والمجلد الموجود على الخادم الذي يوجد فيه طلب الاجتماع. |
| [MeetingResponseResult](./meetingresponseresult) | كائن نتيجة استجابة الاجتماع |
| [MoveItemData](./moveitemdata) | يحتوي على معلومات حول نقل العناصر |
| [MoveItemResponse](./moveitemresponse) | يحتوي على معلومات تصف العناصر المنقولة. |
| [OOFMessage](./oofmessage) | تحدد رسالة OOF لجمهور معين. يتطلب Exchange 2007 و Exchange 2010 و Exchange 2013 أن تكون رسالة الرد لجماهير خارجية معروفة وخارجية غير معروفة. تدعم الخاصية الجماهير الثلاثة التالية لرسالة OOF: داخلي - مستخدم موجود في نفس المؤسسة مثل المستخدم المرسل . خارجي معروف - مستخدم خارج مؤسسة المستخدم المرسل ، ولكنه ممثل في جهات اتصال المستخدم المرسل . خارجي غير معروف - مستخدم خارج المستخدم المرسل المنظمة وغير ممثلة في جهات اتصال المستخدم المرسل. |
| [OOFReqParametrs](./oofreqparametrs) | الحصول على إعدادات معلومات OOF من الخادم. |
| [OOFRequest](./oofrequest) | يحدد فئة لاسترداد معلومات خارج المكتب (OOF) وتعيينها. |
| [OOFResponse](./oofresponse) | يحدد فئة لاسترداد معلومات خارج المكتب (OOF) وتعيينها. |
| [OOFSettings](./oofsettings) | إعدادات معلومات OOF . |
| [PictureRequest](./picturerequest) | يشير إلى أن العميل يطلب إعادة الصور في استجابة الخادم. لا يتم دعم الصورة عندما يكون إصدار البروتوكول هو 12.1 أو 14.0. يحتوي على البيانات المتعلقة بطلب الصور. |
| [PictureRespose](./picturerespose) | يحتوي على البيانات المتعلقة بصور جهة الاتصال. لا يتم دعم الصورة عندما يكون إصدار البروتوكول هو 12.1 أو 14.0 . |
| [PingParameter](./pingparameter) | يحتوي على معلمات أمر ping |
| [ProvisionPolicy](./provisionpolicy) | تحديد سياسة أمان . |
| [ProvisionPolicyData](./provisionpolicydata) | يحدد إعدادات السياسة . |
| [ProvisionRequest](./provisionrequest) | يحتوي على معلومات الطلب لأمر التوفير |
| [ProvisionResponse](./provisionresponse) | يحتوي على معلومات الاستجابة لأمر التوفير |
| [QueryType](./querytype) | يحدد الكلمات الأساسية التي سيتم استخدامها لمطابقة الإدخالات في المخزن الذي يتم البحث فيه. يتم استخدام قيمة الاستعلام كنمط مطابقة لسلسلة البادئة ، وإرجاع الإدخالات التي تطابق بداية السلسلة. على سبيل المثال ، قد يتطابق البحث عن "John" مع "John Frum" أو "Barry Johnson" ، ولكنه لن يتطابق مع "James Littlejohn" . تتم مقارنة جميع خصائص النص غير الفارغة في قائمة العناوين العمومية التي تمت فهرستها باستخدام ANR مع عنصر الاستعلام القيمة. يتم إجراء مقارنات البحث باستخدام مطابقة غير حساسة لحالة الأحرف . بالنسبة للبحث في مكتبة مستندات Windows SharePoint Services ، يدعم هذا البروتوكول استعلامات النموذج التالي: LinkId == value ، حيث تحدد القيمة عنوان URL الخاص بالعنصر أو المجلد ويشير LinkId أن القيمة المراد مقارنتها بخاصية معرف الارتباط . بالنسبة للبحث في صندوق البريد ، يكون بناء جملة الاستعلام كما يلي: - يمكن تحديد المجلدات بالطرق التالية: معرف محدد مجلد محدد ومجلدات فرعية كافة مجلدات البريد الإلكتروني ، بما في ذلك المسودة ، علبة الوارد والمجلدات الفرعية وصندوق الصادر والعناصر المرسلة - يمكن أن يتكون استعلام الكلمة الأساسية الأساسي مما يلي: عامل التشغيل الأساسي: و (القسم 2.2.3.10) عامل تصفية التاريخ والوقت المحدد باستخدام GreaterThan (القسم 2.2.3.78) و LessThan العناصر (القسم 2.2.3.87) عناصر النص الحر (القسم 2.2.3.73) التي تحتوي على كلمات رئيسية يتم تنفيذ استعلام الكلمات الأساسية الأساسي مقابل جميع الخصائص المفهرسة . |
| [Recipient](./recipient) | يمثل مستلمًا واحدًا تم حله. |
| [ResolveRecipientsAvailabilityRequest](./resolverecipientsavailabilityrequest) | يشير إلى الخادم أن بيانات التوفر / الانشغال يطلبها العميل ويحدد وقت البدء ووقت الانتهاء لبيانات التوفر / الانشغال لاستردادها. التوافر غير مدعوم عندما يكون إصدار البروتوكول هو 12.1. |
| [ResolveRecipientsAvailabilityResponse](./resolverecipientsavailabilityresponse) | يحدد الحالة وبيانات التوفر / الانشغال للمستخدمين أو قوائم التوزيع المحددة في الطلب للوقت المحدد بواسطة StartTime و EndTime . عند تضمين التوفر في طلب ResolveRecipients ، يسترد الخادم معلومات التوفر / الانشغال للمستخدمين المحددين في عناصر إلى المضمنة في الطلب ، وإرجاع معلومات التوفر / الانشغال في MergedFreeBusy في الاستجابة. عندما يوزع الخادم الطلب ، يقوم الخادم أولاً بحل المستلمين المحددين بواسطة عناصر "إلى" ، ثم يحدد معلومات التوفر / الانشغال للمستخدمين للمدى الزمني المحدد ، قبل إرجاع بيانات التوفر / الانشغال في MergedFreeBusy. |
| [ResolveRecipientsCertificates](./resolverecipientscertificates) | يحتوي على معلومات حول الشهادات الخاصة بالمستلم . |
| [ResolveRecipientsOptions](./resolverecipientsoptions) | يحتوي على خيارات حل قائمة المستلمين. |
| [ResolveRecipientsRequest](./resolverecipientsrequest) | يحتوي على معلومات لحل المستلمين . |
| [ResolveRecipientsResponse](./resolverecipientsresponse) | يحتوي على معلومات حول ما إذا كان قد تم حل المستلم أم لا. إذا تم حل المستلم ، فإنه يحتوي أيضًا على نوع المستلم وعنوان البريد الإلكتروني الذي حدده المستلم ، واختيارياً ، شهادة S / MIME للمستلم. |
| [RightsManagementInformationResponce](./rightsmanagementinformationresponce) | يحتوي على إعدادات معلومات إدارة الحقوق المستردة من الخادم. |
| [RightsManagementLicense](./rightsmanagementlicense) | يحتوي على إعدادات قالب نهج الحقوق للقالب المطبق على رسالة البريد الإلكتروني التي تتم مزامنتها. |
| [RightsManagementTemplate](./rightsmanagementtemplate) | يحتوي على معرف القالب والاسم ووصف قالب سياسة الحقوق المتاح على العميل. |
| [SearchCondition](./searchcondition) | تحديد شرط لطلبات البحث |
| [SearchOptions](./searchoptions) | يحتوي على خيارات البحث . لا يمكن إرسال اسم المستخدم وكلمة المرور إلا في الطلب بعد استلام قيمة الحالة 14. يتطلب الخادم بيانات الاعتماد هذه للوصول إلى الموارد المطلوبة. يجب على العميل إرسال هذه الرسائل فقط عبر اتصال آمن أو موثوق به ، وفقط ردًا على قيمة الحالة 14. تختلف الخيارات المدعومة وفقًا للمتجر الذي يتم البحث فيه. يسرد الجدول التالي الخيارات الصالحة لكل متجر. GAL: النطاق ، اسم المستخدم ، كلمة المرور ، Picture صندوق البريد: النطاق ، DeepTraversal ، RebuildResults ، BodyPreference ، BodyPartPreference ، RightsManagementSupport DocumentLibrary: Range ، UserName ، Password reference صالح فقط طلبات الأمر التي تحتوي على ConversationId . |
| [SearchQuery](./searchquery) | يحدد الكلمات الأساسية التي سيتم استخدامها لمطابقة الإدخالات في المخزن الذي يتم البحث فيه. يتم استخدام قيمة الاستعلام كنمط مطابقة لسلسلة بادئة ، وإرجاع الإدخالات التي تطابق بداية السلسلة. على سبيل المثال ، قد يطابق البحث عن "John" "John Frum" أو "Barry Johnson" ، ولكنه لن يتطابق مع "James Littlejohn" . تتم مقارنة جميع خصائص النص غير الفارغة في قائمة العناوين العمومية التي تمت فهرستها باستخدام ANR مع عنصر الاستعلام القيمة. يتم إجراء مقارنات البحث باستخدام مطابقة غير حساسة لحالة الأحرف . بالنسبة للبحث في مكتبة مستندات Windows SharePoint Services ، يدعم هذا البروتوكول استعلامات النموذج التالي: LinkId == value ، حيث تحدد القيمة عنوان URL الخاص بالعنصر أو المجلد ويشير LinkId أن القيمة المراد مقارنتها بخاصية معرف الارتباط . بالنسبة للبحث في صندوق البريد ، يكون بناء جملة الاستعلام كما يلي: - يمكن تحديد المجلدات بالطرق التالية: معرف محدد مجلد محدد ومجلدات فرعية كافة مجلدات البريد الإلكتروني ، بما في ذلك المسودة ، علبة الوارد والمجلدات الفرعية ، وصندوق الصادر ، والعناصر المرسلة - يمكن أن يتكون استعلام الكلمة الأساسية الأساسي مما يلي: عامل التشغيل الأساسي: و (القسم 2.2.3.10) مرشح التاريخ والوقت المحدد باستخدام GreaterThan (القسم 2.2.3.78) و LessThan العناصر (القسم 2.2.3.87) عناصر النص الحر (القسم 2.2.3.73) التي تحتوي على كلمات رئيسية يتم تنفيذ استعلام الكلمات الأساسية الأساسي مقابل جميع الخصائص المفهرسة . |
| [SearchRequest](./searchrequest) | يحتوي على معلومات طلب البحث |
| [SearchRequestStore](./searchrequeststore) | حدد الاسم والاستعلام وخيارات البحث. |
| [SearchResponse](./searchresponse) | يحتوي على معلومات استجابة البحث |
| [SearchResponseStore](./searchresponsestore) | يحتوي على عناصر الحالة والنتيجة والنطاق والإجمالي لإدخالات صندوق البريد التي تم إرجاعها. |
| [SearchResult](./searchresult) | حاوية لعنصر صندوق بريد فردي مطابق . عندما يكون المخزن الذي يتم البحث فيه هو صندوق البريد: - يوجد عنصر نتيجة واحد لكل تطابق موجود في صندوق البريد. إذا لم يتم العثور على مطابقات ، فسيكون عنصر النتيجة فارغًا موجودًا في عنصر حاوية المتجر الخاص بالاستجابة XML. - داخل عنصر النتيجة ، يحتوي عنصر الخصائص على قائمة بالخصائص المطلوبة لعنصر صندوق البريد. يتم البحث في مكتبة المستندات: - النتيجة الأولى التي يتم إرجاعها في استجابة البحث هي بيانات التعريف للمجلد الجذر أو العنصر الذي تشير إليه قيمة LinkId. يمكن للعميل اختيار تجاهل هذا الإدخال إذا لم يتطلب ذلك. - إذا كانت مكتبة المستندات: تشير قيمة عنصر LinkId في الطلب إلى مجلد ، يتم إرجاع خصائص البيانات الوصفية للمجلد كعنصر أول ومحتويات يتم إرجاع المجلد كنتائج لاحقة. ينطبق النطاق على هذه النتائج بدون اختلاف ؛ على سبيل المثال ، سيكون الفهرس 0 دائمًا للعنصر الجذر الذي يشير إليه الارتباط. - داخل عنصر النتيجة ، يحتوي عنصر الخصائص على قائمة بالخصائص المطلوبة لعنصر صندوق البريد. |
| [SearchResultProperties](./searchresultproperties) | خصائص استجابة أمر البحث عبارة عن حاوية للخصائص التي تنطبق على إدخال فردي يطابق سلسلة بحث عنصر الاستعلام. على سبيل المثال ، يحتوي عنصر الخصائص على عنصر لكل خاصية GAL غير فارغة وذات قيمة نصية مرفقة بإدخال GAL المطابق. يتم إرجاع تلك الخصائص المرفقة بإدخال GAL المحدد فقط ؛ لذلك يمكن إرجاع مجموعات مختلفة من الخصائص في استجابة XML لإدخالات GAL المطابقة المختلفة. |
| [ServerInfo](./serverinfo) | إعدادات الخادم في عملية الاكتشاف التلقائي |
| [SettingsRequest](./settingsrequest) | يدعم أمر "الإعدادات" الحصول على العمليات وتعيينها على الخصائص العامة وإعدادات "خارج المكتب" للمستخدم. يرسل أمر الإعدادات أيضًا معلومات الجهاز إلى الخادم ، ويقوم بتنفيذ استعادة كلمة مرور الجهاز / رقم التعريف الشخصي (PIN) ، ويسترجع قائمة عناوين البريد الإلكتروني للمستخدم. |
| [SettingsResponse](./settingsresponse) | يحدد استجابة بإعدادات خارج المكتب (OOF) وقائمة بحسابات المستخدم. |
| [SmartRequest](./smartrequest) | يحتوي على معلومات الطلب الذكية |
| [SmartRequestSource](./smartrequestsource) | يحتوي على معلومات حول رسالة المصدر . |
| [Status](./status) | تشير إلى نتيجة العملية. |
| [SyncAddClientOperation](./syncaddclientoperation) | إنشاء كائن جديد في مجموعة على العميل. |
| [SyncAddResponse](./syncaddresponse) | يُستخدم للإشارة إلى أنه يجب إنشاء كائن جديد في مجموعة. |
| [SyncAddServerOperation](./syncaddserveroperation) | إنشاء كائن جديد في مجموعة على الخادم. |
| [SyncChangeClientOperation](./syncchangeclientoperation) | يحتوي على خصائص كائن موجود على جهاز العميل الذي تم تعديله. يتم تحديد الكائن الذي تم تغييره بواسطة عنصر ServerId الخاص به. |
| [SyncChangeResponse](./syncchangeresponse) | يُستخدم للإشارة إلى تعديل كائن. |
| [SyncChangeServerOperation](./syncchangeserveroperation) | يحتوي على خصائص كائن موجود على الخادم الذي تم تعديله. يتم تحديد الكائن الذي تم تغييره بواسطة عنصر ServerId الخاص به. |
| [SyncCollectionRequest](./synccollectionrequest) | تحتوي الفئة على أوامر وخيارات تنطبق على مجموعة معينة. |
| [SyncCollectionResponse](./synccollectionresponse) | تحتوي الفئة على أوامر وخيارات تنطبق على استجابة المزامنة. |
| [SyncCommandsRequest](./synccommandsrequest) | يحتوي على العمليات التي تنطبق على مجموعة. العمليات المتاحة هي إضافة وحذف وتغيير وجلب و SoftDelete. |
| [SyncCommandsResponse](./synccommandsresponse) | يحتوي على العمليات التي تنطبق على مجموعة. العمليات المتاحة هي إضافة وحذف وتغيير وجلب و SoftDelete. |
| [SyncDeleteClientOperation](./syncdeleteclientoperation) | حذف كائن من جهاز العميل أو الخادم. يتم تحديد الكائن بواسطة ServerId . |
| [SyncFetchResponse](./syncfetchresponse) | يطلب بيانات التطبيق لعنصر تم قطعه في استجابة مزامنة من الخادم. |
| [SyncOperationResponse](./syncoperationresponse) | فئة الملخص الأساسية لاستجابات عملية المزامنة |
| [SyncOperationsResponse](./syncoperationsresponse) | يحتوي على استجابات لعمليات مثل الإضافة والجلب والتغيير التي تتم معالجتها بواسطة الخادم. تحتوي الاستجابة على رمز الحالة ومعلومات أخرى ، حسب العملية. |
| [SyncOptions](./syncoptions) | يحدد الخيارات التي تتحكم في جوانب معينة لكيفية إجراء المزامنة. |
| [SyncRequest](./syncrequest) | يحتوي على معلمات طلب المزامنة |
| [UserInformationResponse](./userinformationresponse) | يحتوي على حالة الطلب وقائمة بمعلومات حساب المستخدم (عناوين البريد الإلكتروني) . |
| [ValueConverter](./valueconverter) | تقوم الفئة بتحويل إصدار بروتوكول ActiveSync من تمثيل السلسلة إلى التعداد والعكس. |
## واجهات

| واجهه المستخدم | وصف |
| --- | --- |
| [IActiveSyncTLClient](./iactivesynctlclient) | واجهة عميل ActiveSync |
| [IBaseActiveSyncTLClient](./ibaseactivesynctlclient) | واجهة عميل Base ActiveSync |
## تعداد

| تعداد | وصف |
| --- | --- |
| [ActiveSyncAuthenticationType](./activesyncauthenticationtype) | يحدد Enum نوع المصادقة |
| [AirSync](./airsync) | مساحة اسم AirSync لبروتوكول ActiveSync |
| [AirSyncBase](./airsyncbase) | مساحة اسم قاعدة AirSync لبروتوكول ActiveSync |
| [AirsyncClass](./airsyncclass) | يحدد فئة العنصر. الفصول التالية مدعومة لعمليات البحث في صندوق البريد عندما يكون إصدار البروتوكول هو 12.1: - Email - Calendar - Contacts - Tasks تتوفر فئتا SMS و Notes فقط إذا كان إصدار البروتوكول هو 14.0 أو 14.1. |
| [AirsyncFilterType](./airsyncfiltertype) | يحدد نافذة زمنية اختيارية للكائنات |
| [AllowBluetooth](./allowbluetooth) | يحدد استخدام Bluetooth على الجهاز. |
| [ASProtocolVersions](./asprotocolversions) | يشير ASProtocolVersions إلى إصدارات بروتوكول ActiveSync. |
| [BehaviorReplacement](./behaviorreplacement) | يحدد كيفية حل التعارض الذي يحدث عندما يتم تغيير كائن على كل من العميل والخادم. تحدد القيمة أي كائن - كائن العميل أو كائن الخادم - يجب الاحتفاظ به إذا كان هناك تعارض. |
| [BodyType](./bodytype) | يحدد نوع تنسيق محتوى النص الأساسي للعنصر. |
| [Calendar](./calendar) | مساحة اسم التقويم لبروتوكول ActiveSync |
| [CertificateRetrieval](./certificateretrieval) | يحدد ما إذا كان يجب إرجاع شهادات S / MIME بواسطة الخادم لكل مستلم تم حله. |
| [CommandCodes](./commandcodes) | يوفر الجدول التالي الرموز الرقمية التي تتوافق مع أوامر ActiveSync. يتم استخدام الكود الرقمي في حقل كود الأمر لمُعرّف الموارد المنتظم لـ base64 لتحديد الأمر. |
| [CommandParameters](./commandparameters) | معلمات الأمر . |
| [ComposeMail](./composemail) | مساحة اسم ComposeMail لبروتوكول ActiveSync |
| [Contacts](./contacts) | مساحة اسم جهات الاتصال لبروتوكول ActiveSync |
| [Contacts2](./contacts2) | مساحة الأسماء Contacts2 لبروتوكول ActiveSync |
| [DocumentLibrary](./documentlibrary) | مساحة اسم DocumentLibrary لبروتوكول ActiveSync |
| [Email](./email) | مساحة اسم البريد الإلكتروني لبروتوكول ActiveSync |
| [Email2](./email2) | مساحة اسم Email2 لبروتوكول ActiveSync |
| [EncryptionSMIMEAlgorithm](./encryptionsmimealgorithm) | يحدد الخوارزمية المستخدمة عند تشفير رسائل S / MIME. |
| [FolderClass](./folderclass) | يحدد فئة المحتوى للمجلد المراد مراقبته. |
| [FolderHierarchy](./folderhierarchy) | مساحة اسم التسلسل الهرمي لبروتوكول ActiveSync |
| [FolderTypes](./foldertypes) | يحدد نوع المجلد الذي تم تحديثه (إعادة تسميته أو نقله) أو إضافته على الخادم. |
| [GAL](./gal) | مساحة اسم GAL لبروتوكول ActiveSync |
| [GetItemEstimate](./getitemestimate) | GetItemEstimate مساحة اسم بروتوكول ActiveSync |
| [ItemOperations](./itemoperations) | مساحة اسم عمليات العنصر لبروتوكول ActiveSync |
| [MaxAgeFilter](./maxagefilter) | يحدد الحد الأقصى لعدد أيام التقويم التي يمكن مزامنتها. |
| [MeetingResponse](./meetingresponse) | مساحة اسم MeetingResponse لبروتوكول ActiveSync |
| [MergedFreeBusy](./mergedfreebusy) | تحديد معلومات التوفر / الانشغال للمستخدمين أو قائمة التوزيع. |
| [MIMESupport](./mimesupport) | تمكين دعم MIME لعناصر البريد الإلكتروني التي يتم إرسالها من الخادم إلى العميل. |
| [MIMETruncation](./mimetruncation) | يحدد ما إذا كان يجب اقتطاع بيانات MIME لعنصر البريد الإلكتروني عند إرسالها من الخادم إلى العميل. |
| [MinDevicePasswordComplexCharacters](./mindevicepasswordcomplexcharacters) | يحدد المستوى المطلوب من التعقيد لكلمة مرور العميل. على سبيل المثال: إذا كانت قيمة MinDevicePasswordComplexCharacters هي 2 ، فستكون كلمة المرور ذات الأحرف الأبجدية الكبيرة والصغيرة كافية ، كما هو الحال مع كلمة المرور ذات الأحرف الأبجدية الصغيرة والأرقام. |
| [Move](./move) | نقل مساحة اسم بروتوكول ActiveSync |
| [Namespace](./namespace) | صفحات كود ActiveSync |
| [Notes](./notes) | مساحة اسم Notes لبروتوكول ActiveSync |
| [OofState](./oofstate) | يحدد مدى توفر خاصية Oof . |
| [Ping](./ping) | مساحة اسم Ping لبروتوكول ActiveSync |
| [Provision](./provision) | توفير مساحة اسم بروتوكول ActiveSync |
| [ProvisionPolicyStatuses](./provisionpolicystatuses) | تشير القيمة إلى نجاح أو فشل العميل في تطبيق محددات السياسة التي تم استردادها من الخادم. |
| [ProvisionRemoteWipeStatuses](./provisionremotewipestatuses) | تشير القيمة إلى نجاح أو فشل عملية المسح عن بعد على العميل. |
| [RecipientType](./recipienttype) | يشير إلى نوع المستلم . |
| [ResolveRecipients](./resolverecipients) | مساحة اسم ResolveRecipients لبروتوكول ActiveSync |
| [RightsManagement](./rightsmanagement) | مساحة اسم إدارة الحقوق لبروتوكول ActiveSync |
| [Search](./search) | بحث عن مساحة اسم بروتوكول ActiveSync |
| [ServerType](./servertype) | يحدد نوع الخادم |
| [Settings](./settings) | مساحة اسم إعدادات بروتوكول ActiveSync |
| [SignedSMIMEAlgorithm](./signedsmimealgorithm) | يحدد الخوارزمية المستخدمة عند توقيع رسائل S / MIME. |
| [SMIMEEncryptionAlgorithmNegotiation](./smimeencryptionalgorithmnegotiation) | يتحكم في تفاوض خوارزمية التشفير. |
| [StoreType](./storetype) | يحتوي على معلومات تحدد موقع العمليات. |
| [Tasks](./tasks) | مساحة اسم المهام لبروتوكول ActiveSync |
| [UserCreatedFolderTypes](./usercreatedfoldertypes) | يحدد نوع المجلد الذي سيتم إنشاؤه. |
| [UserResponse](./userresponse) | يشير إلى ما إذا كان الاجتماع قد تم قبوله أو قبوله مبدئيًا أو رفضه. |
| [ValidateCert](./validatecert) | ValidateCert مساحة الاسم لبروتوكول ActiveSync |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
