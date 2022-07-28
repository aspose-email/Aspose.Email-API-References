---
title: ImapClient
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يسمح للتطبيقات بالوصول إلى رسائل ومعالجتها باستخدام بروتوكول الوصول إلى الرسائل عبر الإنترنت IMAP .
type: docs
weight: 16280
url: /ar/net/aspose.email.clients.imap/imapclient/
---
## ImapClient class

يسمح للتطبيقات بالوصول إلى رسائل ومعالجتها باستخدام بروتوكول الوصول إلى الرسائل عبر الإنترنت (IMAP) .

```csharp
public sealed class ImapClient : EmailClient, IAsyncImapClient
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ImapClient](imapclient#constructor)() | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_1)(string) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_3)(string, int) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_2)(string, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_4)(string, int, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_13)(string, string, ITokenProvider) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_15)(string, string, string) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_5)(string, int, string, ITokenProvider) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_7)(string, int, string, string) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_14)(string, string, ITokenProvider, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_17)(string, string, string, bool) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_16)(string, string, string, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_6)(string, int, string, ITokenProvider, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_9)(string, int, string, string, bool) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_11)(string, int, string, string, RemoteCertificateValidationCallback) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_8)(string, int, string, string, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_18)(string, string, string, bool, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_10)(string, int, string, string, bool, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |
| [ImapClient](imapclient#constructor_12)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`ImapClient`](../imapclient) فئة |

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | الحصول على رمز الوصول أو تعيينه. |
| [AllowedAuthentication](../../aspose.email.clients.imap/imapclient/allowedauthentication) { get; set; } | الحصول على أو تعيين التعداد المسموح به بواسطة أنواع مصادقة المستخدم |
| [AnnotateSupported](../../aspose.email.clients.imap/imapclient/annotatesupported) { get; set; } | يحصل على معلومات حول ما إذا كان ملحق ANNOTATE مدعومًا انظر المزيد: https://tools.ietf.org/html/rfc5257 |
| [AutoCommit](../../aspose.email.clients.imap/imapclient/autocommit) { get; set; } | يشير إلى ما إذا كان يتم تنفيذ عملية الالتزام تلقائيًا عند تغيير المجلد أو قبل إغلاق الاتصال. |
| [ChildrenSupported](../../aspose.email.clients.imap/imapclient/childrensupported) { get; set; } | الحصول على معلومات حول ما إذا كان امتداد CHILDREN مدعومًا انظر المزيد: https://tools.ietf.org/html/rfc3348 |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | يحتوي على مجموعة من شهادات العملاء |
| [ClientIdentificationInfo](../../aspose.email.clients.imap/imapclient/clientidentificationinfo) { get; set; } | الحصول على معلومات تعريف العميل أو تعيينها انظر المزيد: https://tools.ietf.org/html/rfc2971 |
| [CompressSupported](../../aspose.email.clients.imap/imapclient/compresssupported) { get; set; } | يحصل على معلومات حول ما إذا كان امتداد COMPRESS مدعومًا انظر المزيد: https://tools.ietf.org/html/rfc4978 |
| [CondstoreSupported](../../aspose.email.clients.imap/imapclient/condstoresupported) { get; set; } | يحصل على معلومات حول ما إذا كان امتداد CONDSTORE مدعومًا انظر المزيد: https://tools.ietf.org/html/rfc7162 |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | الحصول على أو تعيين القيمة التي تحدد وضع تخصيص الاتصال في بيئة مؤشرات الترابط المتعددة هناك أنواع اتصال متتابعة: - الاتصال الرئيسي هو الاتصال الذي تم إنشاؤه والتخلص منه مع عميل البريد. لا يمكن إنشاؤه أو التخلص منه يدويًا. - الاتصال الافتراضي هو الاتصال الافتراضي لبعض مؤشرات الترابط . إذا كان الاتصال الافتراضي موجودًا وكان ConnectionAsgmtMode يسمح بذلك ، فسيتم استخدام هذا الاتصال ضمنيًا لجميع طرق عميل البريد الإلكتروني المنفذة في هذا الموضوع. يمكن إنشاؤه يدويًا أو تلقائيًا. يعتمد ذلك على خاصية EmailClient.ConnectionAsgmtMode. يمكن إنشاء هذه الاتصالات يدويًا باستخدام طريقة EmailClient.CreateConnection (createAsDefaultConnection = true) . إذا لم يتم استخدام الاتصال الافتراضي (يعتمد على وضع تخصيص الاتصال) ، يتم استخدام الاتصال الرئيسي بشكل ضمني بدلاً منه. - الاتصالات المستقلة هي اتصالات غير مرتبطة بخيوط. يمكن إنشاؤها يدويًا ويجب استخدامها بشكل صريح كمعامل أسلوب. يمكن إنشاء هذه الاتصالات يدويًا باستخدام طريقة EmailClient.CreateConnection () أو طريقة EmailClient.CreateConnection (createAsDefaultConnection = false). هناك أنواع تخصيص اتصال متتابعة: - ConnectionAsgmtType.UseMain_ddefault. يستخدم عميل البريد الإلكتروني الاتصال الرئيسي لجميع العمليات من مؤشرات ترابط متعددة إذا لم يتم إنشاء الاتصال الافتراضي ، أو لم يتم تمرير الاتصال كمعامل أسلوب بشكل صريح. الاتصال الرئيسي هو الاتصال الذي يتم إنشاؤه في نفس الوقت مثل عميل البريد الإلكتروني. يمكن للمستخدم إنشاء اتصالات افتراضية لسلاسل الرسائل باستخدام طريقة CreateConnection. إذا تم إنشاء الاتصال الافتراضي لمؤشر الترابط ، فسيتم استخدامه ضمنيًا لجميع طرق عميل البريد الإلكتروني التي يتم استدعاؤها في هذا الموضوع. thread. يمكن للمستخدم أيضًا إنشاء اتصالات غير مرتبطة بخيوط (وليس اتصالات افتراضية) باستخدام طريقة CreateConnection. إذا أراد المستخدم استخدام اتصالات أخرى (ليست رئيسية وليست افتراضية) فعليه أن يمرر هذا الاتصال صراحة كمعامل للطريقة التي يريد استخدامها. يمكن للمستخدم أيضًا إنشاء أي عدد من الاتصالات. يمكن أن يكون الاتصال الافتراضي واحدًا فقط لكل مؤشر ترابط . يرجى ملاحظة أن الاتصالات الافتراضية تعمل بشكل صحيح إذا كان المستخدم يستخدم كائنات سلسلة الرسائل لبرمجة متعددة المهام. إذا كان المستخدم يستخدم ConnectionPool أو يستخدم كائنات المهام لبرمجة متعددة المهام ، فقد يؤدي هذا الوضع إلى سلوك خاطئ للبرنامج . لتجنب هذه المشكلة ، يتعين على المستخدم التخلص يدويًا من الاتصال الافتراضي (إذا كان يستخدمه) في نهاية الكود الذي يتم تنفيذه في الخيط. - ConnectionAsgmtType.UseMain يستخدم عميل البريد الإلكتروني الاتصال الرئيسي لجميع العمليات من سلاسل رسائل متعددة. الاتصال الرئيسي هو الاتصال الذي يتم إنشاؤه في نفس الوقت مثل عميل البريد الإلكتروني. لا يمكن للمستخدم إنشاء اتصالات افتراضية. يمكن للمستخدم إنشاء اتصالات غير مرتبطة بسلاسل (وليس اتصالات افتراضية) باستخدام طريقة CreateConnection. إذا أراد المستخدم استخدام اتصالات أخرى (ليست رئيسية وليست افتراضية) فعليه أن يمرر هذا الاتصال صراحة كمعامل للطريقة التي يريد استخدامها. يمكن للمستخدم أيضًا إنشاء أي عدد من الاتصالات. - ConnectionAsgmtType.UseDefault يستخدم عميل البريد الإلكتروني بشكل ضمني فقط الاتصالات الافتراضية لجميع العمليات من سلاسل رسائل متعددة. لا يتم استخدام الاتصال الرئيسي في هذا الوضع. إذا لم يتم إنشاء الاتصال الافتراضي لبعض سلاسل الرسائل (الاستدعاء الأول لطريقة عميل البريد الإلكتروني) ، يقوم عميل البريد الإلكتروني بإنشاء اتصال افتراضي ضمنيًا لمؤشر الترابط قبل تنفيذ العملية الأولى. لا يمكن للمستخدم إنشاء اتصالات افتراضية لسلاسل الرسائل باستخدام طريقة CreateConnection لأنه يتم إنشاؤها تلقائيًا. عند إنشاء الاتصال الافتراضي لمؤشر الترابط ، يتم استخدامه ضمنيًا لجميع طرق عميل البريد الإلكتروني التي يتم استدعاؤها في هذا الموضوع. قراءة. يمكن للمستخدم أيضًا إنشاء اتصالات غير مرتبطة بسلاسل الرسائل (وليس الاتصالات الافتراضية) باستخدام طريقة CreateConnection. إذا أراد المستخدم استخدام اتصالات أخرى (ليست رئيسية وليست افتراضية) فعليه أن يمرر هذا الاتصال صراحة كمعامل للطريقة التي يريد استخدامها. يمكن للمستخدم أيضًا إنشاء أي عدد من الاتصالات. يمكن أن يكون الاتصال الافتراضي واحدًا فقط لكل مؤشر ترابط . يرجى ملاحظة أن الاتصالات الافتراضية تعمل بشكل صحيح إذا كان المستخدم يستخدم كائنات سلسلة الرسائل لبرمجة متعددة المهام. إذا كان المستخدم يستخدم ConnectionPool أو يستخدم كائنات المهام لبرمجة متعددة المهام ، فقد يؤدي هذا الوضع إلى سلوك خاطئ للبرنامج . لتجنب هذه المشكلة ، يتعين على المستخدم التخلص يدويًا من الاتصال الافتراضي في نهاية الكود الذي يتم تنفيذه في مؤشر الترابط. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | فترة فحص الاتصال بالمللي ثانية . القيمة الافتراضية هي 5 دقائق . |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | الحصول على كمية من الاتصالات أو تعيينها في وضع الاتصال المتعدد |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | يحصل على الحالة الحالية للاتصال. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | يحصل على الاتصال الحالي وفقًا لخيار ConnectionAsgmtMode |
| [CurrentFolder](../../aspose.email.clients.imap/imapclient/currentfolder) { get; set; } | يحصل على المجلد الحالي |
| override [DefaultPort](../../aspose.email.clients.imap/imapclient/defaultport) { get; } | يحصل على المنفذ الافتراضي لـ client |
| [Delimiter](../../aspose.email.clients.imap/imapclient/delimiter) { get; set; } | الحصول على أو تعيين محدد المجلدات hierarhy . |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | الحصول على أو تعيين قيمة تسمح بتمكين / تعطيل logger |
| [EnableSupported](../../aspose.email.clients.imap/imapclient/enablesupported) { get; set; } | الحصول على معلومات حول ما إذا كان ملحق ENABLE مدعومًا راجع المزيد: https://tools.ietf.org/html/rfc5161 |
| [ESearchSupported](../../aspose.email.clients.imap/imapclient/esearchsupported) { get; set; } | الحصول على معلومات حول ما إذا كان امتداد ESEARCH مدعومًا شاهد المزيد: https://tools.ietf.org/html/rfc4731 |
| [ExchangeIdAutomatically](../../aspose.email.clients.imap/imapclient/exchangeidautomatically) { get; set; } | الحصول على أو تعيين القيمة التي تشير إلى ما إذا كان يجب على العميل تقديم معلومات عن نفسه إلى الخادم تلقائيًا. انظر المزيد: https://tools.ietf.org/html/rfc2971 |
| [ExtendedListSupported](../../aspose.email.clients.imap/imapclient/extendedlistsupported) { get; set; } | الحصول على معلومات حول ما إذا كان ملحق أمر LIST مدعومًا راجع المزيد https://tools.ietf.org/html/rfc5258 |
| [GmExt1Supported](../../aspose.email.clients.imap/imapclient/gmext1supported) { get; set; } | يحدد ما إذا كان ملحق Google X-GM-EXT-1 مدعومًا |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | الحصول على أو تعيين مهلة الترحيب المستخدمة عند إنشاء اتصال. يرجى ملاحظة أن مهلة الترحيب لا يمكن أن تكون غير محدودة. قد يقوم عملاء البريد الإلكتروني بتنفيذ عمليات طويلة كافية. للحد من وقت العمليات التي يتعين على المستخدمين استخدامها[`Timeout`](../../aspose.email.clients/emailclient/timeout)منشأه. يجب أن تحتوي قيم هذه الخاصية على فترات زمنية طويلة حتى لا تمنع العمليات التي تستغرق وقتًا طويلاً. ولكن في بعض الحالات ، إذا كان EmailClient سيستخدم فقط اتصال خاصية Timeout فقد يستغرق إنشاء اتصال وقت طويل. على سبيل المثال ، قد يستخدم عميل البريد الوضع التلقائي لإنشاء الاتصال. في هذا الوضع ، يمر عميل البريد الإلكتروني بجميع معلمات الاتصال الممكنة حتى يتم إنشاء الاتصال. خوادم SMTP و IMAP و POP3 في حالة الاتصال الصحيح لإنشاء سلسلة ترحيب إلى العميل. قد تستخدم الخوادم بدء اتصال SSL / TLS ضمنيًا أو صريحًا (START TLS). إذا كان وضع الاتصال غير متطابق (على سبيل المثال ، ينتظر الخادم اتصال SSL ضمنيًا لكن العميل يحاول إنشاء اتصال SSL غير آمن أو صريح) ، فلن يرسل الخادم سلسلة ترحيب. في هذه الحالة ، سينتظر المستخدم وقتًا طويلاً حتى تصل المهلة إلى سلسلة ترحيب ، وينتقل العميل إلى خيار الاتصال التالي. لتجنب هذه المشكلة ، تم تقديم الخاصية GreetingTimeout. تسمح لك هذه الخاصية بتعيين مهلة سلسلة الترحيب ، وتقليل وقت إنشاء الاتصال التلقائي. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | الحصول على أو تحديد اسم المضيف . |
| [IdSupported](../../aspose.email.clients.imap/imapclient/idsupported) { get; set; } | يحصل على معلومات حول ما إذا كان امتداد المعرف مدعومًا انظر المزيد: https://tools.ietf.org/html/rfc2971 |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | الحصول على أو تعيين اسم ملف السجل |
| [MailboxInfo](../../aspose.email.clients.imap/imapclient/mailboxinfo) { get; } | الحصول على مجموعة من علب البريد ذات الاستخدام الخاص انظر المزيد: http://tools.ietf.org/html/rfc6154 و https://tools.ietf.org/html/rfc8457 |
| [MoveSupported](../../aspose.email.clients.imap/imapclient/movesupported) { get; set; } | يحصل على معلومات حول ما إذا كان امتداد MOVE مدعومًا انظر المزيد: https://tools.ietf.org/html/rfc6851 |
| [NamespaceSupported](../../aspose.email.clients.imap/imapclient/namespacesupported) { get; set; } | يحصل على معلومات حول ما إذا كان امتداد NAMESPACE مدعومًا شاهد المزيد: https://tools.ietf.org/html/rfc2342 |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | الحصول على كلمة المرور أو تعيينها. يتم تحديد قيود كلمة المرور من خلال تنفيذ الخادم ، الذي يتصل به العميل. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | الحصول على المنفذ أو تعيينه . |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | الحصول على أو تعيين الوكيل للعميل |
| [QresyncSupported](../../aspose.email.clients.imap/imapclient/qresyncsupported) { get; set; } | يحصل على معلومات حول ما إذا كان امتداد QRESYNC مدعومًا انظر المزيد: https://tools.ietf.org/html/rfc7162 |
| [QuotaSupported](../../aspose.email.clients.imap/imapclient/quotasupported) { get; set; } | يحصل على معلومات حول ما إذا كانت الحصة مدعومة |
| [ReadOnly](../../aspose.email.clients.imap/imapclient/readonly) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يُسمح بإجراء تغييرات على الحالة الدائمة لصندوق البريد ، بما في ذلك حالة كل مستخدم. |
| [SaslIrSupported](../../aspose.email.clients.imap/imapclient/saslirsupported) { get; set; } | الحصول على معلومات حول ما إذا كان ملحق SASL Initial Client Response مدعومًا انظر المزيد: https://tools.ietf.org/html/rfc4959 |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | وضع الأمان لعميل البريد |
| [ServerIdentificationInfo](../../aspose.email.clients.imap/imapclient/serveridentificationinfo) { get; } | الحصول على معلومات تعريف الخادم انظر المزيد: https://tools.ietf.org/html/rfc2971 |
| [ServerSupportedCompression](../../aspose.email.clients.imap/imapclient/serversupportedcompression) { get; } | يحصل على معلومات حول أنواع الضغط التي يدعمها الخادم. انظر المزيد: https://tools.ietf.org/html/rfc4978 |
| [SortSupported](../../aspose.email.clients.imap/imapclient/sortsupported) { get; set; } | يحصل على معلومات حول ما إذا كان أمر الفرز مدعومًا |
| [SpecialUseSupported](../../aspose.email.clients.imap/imapclient/specialusesupported) { get; set; } | للحصول على معلومات حول ما إذا كانت علب البريد ذات الاستخدام الخاص مدعومة شاهد المزيد: https://tools.ietf.org/html/rfc6154 |
| [SupportedAuthentication](../../aspose.email.clients.imap/imapclient/supportedauthentication) { get; } | يحصل على تعداد يدعمه أنواع مصادقة الخادم |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | يحدد إصدارات بروتوكولات تشفير SSL / TLS التي سيتم استخدامها. يرجى الانتباه ، يمكنك فقط تعيين تلك الإصدارات من البروتوكول ، التي يدعمها إطار. من الإطار الصافي ، سيتم تجاهلها وتخطيها . قد تؤدي إلى مستوى أمان طبقة النقل الآمنة. في هذه الحالة لن يتم إنشاء استثناء !!! من فضلك ، انظر[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) الوثائق لمزيد من التفاصيل. الرجاء استخدام[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) الطريقة إذا كنت تريد تعيين بروتوكولات التشفير دون أي فحوصات توافق. القيمة الافتراضية هي: Tls &#x7C; TLS11 &#x7C; TLS12 &#x7C; Tls13 (في حالة إذا كان الإصدار الحالي من إطار عمل .net يدعم هذه الإصدارات من TLS) |
| [ThreadAlgorithms](../../aspose.email.clients.imap/imapclient/threadalgorithms) { get; } | الحصول على خوارزميات مؤشر الترابط المدعومة |
| [ThreadSupported](../../aspose.email.clients.imap/imapclient/threadsupported) { get; set; } | يحصل على معلومات حول ما إذا كان أمر سلسلة الرسائل مدعومًا |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | الحصول على أو تعيين مهلة عمليات البريد |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | الحصول على أو تعيين TokenProvider الذي يسمح باسترداد رمز الوصول. |
| [UidPlusSupported](../../aspose.email.clients.imap/imapclient/uidplussupported) { get; set; } | يحصل على معلومات حول ما إذا كان امتداد UIDPLUS مدعومًا انظر المزيد: https://tools.ietf.org/html/rfc4315 |
| [UnselectSupported](../../aspose.email.clients.imap/imapclient/unselectsupported) { get; set; } | للحصول على معلومات حول ما إذا كان ملحق UNSELECT مدعومًا انظر المزيد: https://tools.ietf.org/html/rfc2342 |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | يشير إلى ما إذا كانت المصادقة مستخدمة. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | الحصول على القيمة أو تعيينها والتي تشير إلى ما إذا كان يجب استخدام التاريخ في اسم ملف السجل. |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials) { get; set; } | الحصول على أو تعيين قيمة منطقية تتحكم في إرسال بيانات الاعتماد الافتراضية مع الطلبات. يتم استخدام هذا الخيار مع مصادقة NTLM فقط! |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | الحصول على القيمة أو تعيينها والتي تشير إلى ما إذا كان يتعين على العميل استخدام اتصالات متعددة لعمليات تحميل ثقيلة. يرجى ملاحظة أن استخدام هذا الوضع ليس ضروريًا يجب أن يؤدي إلى زيادة الأداء. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | الحصول على أو تعيين الكائن الذي يشير إلى ما إذا كان وضع خطوط الأنابيب ممكّنًا. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | الحصول على اسم المستخدم أو تعيينه. |
| static [DefaultFolder](../../aspose.email.clients.imap/imapclient/defaultfolder) { get; set; } | المجلد الافتراضي لـ ImapClients |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_18)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_20)(IEnumerable&lt;int&gt;, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_22)(IEnumerable&lt;string&gt;, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_14)(int, ImapMessageFlags) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_24)(string, ImapMessageFlags) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_6)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_8)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags)(IConnection, int, ImapMessageFlags) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_10)(IConnection, string, ImapMessageFlags) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_19)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_21)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_23)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_15)(int, ImapMessageFlags, long) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_16)(int, int, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_25)(string, ImapMessageFlags, long) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_26)(string, string, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_7)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_9)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_1)(IConnection, int, ImapMessageFlags, long) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_2)(IConnection, int, int, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_11)(IConnection, string, ImapMessageFlags, long) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_12)(IConnection, string, string, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_17)(int, int, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_27)(string, string, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_3)(IConnection, int, int, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlags](../../aspose.email.clients.imap/imapclient/addmessageflags#addmessageflags_13)(IConnection, string, string, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_36)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_40)(IEnumerable&lt;int&gt;, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_44)(IEnumerable&lt;string&gt;, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_28)(int, ImapMessageFlags) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_48)(string, ImapMessageFlags) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_8)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_12)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_16)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync)(IConnection, int, ImapMessageFlags) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_20)(IConnection, string, ImapMessageFlags) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_39)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_37)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_43)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_41)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_47)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_45)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_31)(int, ImapMessageFlags, CancellationToken) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_29)(int, ImapMessageFlags, long) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_32)(int, int, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_51)(string, ImapMessageFlags, CancellationToken) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_49)(string, ImapMessageFlags, long) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_52)(string, string, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_11)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_9)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_15)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_13)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_19)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_17)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_3)(IConnection, int, ImapMessageFlags, CancellationToken) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_1)(IConnection, int, ImapMessageFlags, long) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_4)(IConnection, int, int, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_23)(IConnection, string, ImapMessageFlags, CancellationToken) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_21)(IConnection, string, ImapMessageFlags, long) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_24)(IConnection, string, string, ImapMessageFlags) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_38)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_42)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_46)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_30)(int, ImapMessageFlags, long, CancellationToken) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_35)(int, int, ImapMessageFlags, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_33)(int, int, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_50)(string, ImapMessageFlags, long, CancellationToken) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_55)(string, string, ImapMessageFlags, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_53)(string, string, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_10)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_14)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_18)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_2)(IConnection, int, ImapMessageFlags, long, CancellationToken) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_7)(IConnection, int, int, ImapMessageFlags, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_5)(IConnection, int, int, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_22)(IConnection, string, ImapMessageFlags, long, CancellationToken) | يضيف الإشارات إلى الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_27)(IConnection, string, string, ImapMessageFlags, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_25)(IConnection, string, string, ImapMessageFlags, long) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_34)(int, int, ImapMessageFlags, long, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_54)(string, string, ImapMessageFlags, long, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_6)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | يضيف أعلام الرسالة |
| [AddMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/addmessageflagsasync#addmessageflagsasync_26)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | يضيف أعلام الرسالة |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_4)(MailMessage) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_5)(string) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage)(IConnection, MailMessage) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_1)(IConnection, string) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_6)(string, MailMessage) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_7)(string, string) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_2)(IConnection, string, MailMessage) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessage](../../aspose.email.clients.imap/imapclient/appendmessage#appendmessage_3)(IConnection, string, string) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_8)(MailMessage) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_10)(string) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync)(IConnection, MailMessage) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_2)(IConnection, string) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_9)(MailMessage, CancellationToken) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_15)(string, CancellationToken) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_11)(string, MailMessage) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_13)(string, string) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_1)(IConnection, MailMessage, CancellationToken) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_7)(IConnection, string, CancellationToken) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_3)(IConnection, string, MailMessage) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_5)(IConnection, string, string) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_12)(string, MailMessage, CancellationToken) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_14)(string, string, CancellationToken) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_4)(IConnection, string, MailMessage, CancellationToken) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessageAsync](../../aspose.email.clients.imap/imapclient/appendmessageasync#appendmessageasync_6)(IConnection, string, string, CancellationToken) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages#appendmessages_2)(IEnumerable&lt;MailMessage&gt;) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages#appendmessages)(IConnection, IEnumerable&lt;MailMessage&gt;) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages#appendmessages_3)(string, IEnumerable&lt;MailMessage&gt;) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessages](../../aspose.email.clients.imap/imapclient/appendmessages#appendmessages_1)(IConnection, string, IEnumerable&lt;MailMessage&gt;) | تحميل رسالة البريد إلى المجلد المحدد |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_4)(IEnumerable&lt;MailMessage&gt;) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync)(IConnection, IEnumerable&lt;MailMessage&gt;) | لتحميل رسائل البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_5)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | لتحميل رسالة البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_6)(string, IEnumerable&lt;MailMessage&gt;) | تحميل رسائل البريد إلى المجلد الحالي |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_1)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | لتحميل رسائل البريد إلى المجلد الحالي إذا لم يتم تحديد المجلد الحالي ، فسيتم استخدام المجلد الافتراضي . |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_2)(IConnection, string, IEnumerable&lt;MailMessage&gt;) | تحميل رسائل البريد إلى المجلد الحالي |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_7)(string, IEnumerable&lt;MailMessage&gt;, CancellationToken) | تحميل رسائل البريد إلى المجلد الحالي |
| [AppendMessagesAsync](../../aspose.email.clients.imap/imapclient/appendmessagesasync#appendmessagesasync_3)(IConnection, string, IEnumerable&lt;MailMessage&gt;, CancellationToken) | تحميل رسائل البريد إلى المجلد الحالي |
| [Backup](../../aspose.email.clients.imap/imapclient/backup#backup_2)(ImapFolderInfoCollection, Stream, BackupSettings) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [Backup](../../aspose.email.clients.imap/imapclient/backup#backup_3)(ImapFolderInfoCollection, string, BackupSettings) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [Backup](../../aspose.email.clients.imap/imapclient/backup#backup)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [Backup](../../aspose.email.clients.imap/imapclient/backup#backup_1)(IConnection, ImapFolderInfoCollection, string, BackupSettings) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_4)(ImapFolderInfoCollection, Stream, BackupSettings) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_6)(ImapFolderInfoCollection, string, BackupSettings) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_2)(IConnection, ImapFolderInfoCollection, string, BackupSettings) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_5)(ImapFolderInfoCollection, Stream, BackupSettings, CancellationToken) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_7)(ImapFolderInfoCollection, string, BackupSettings, CancellationToken) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_1)(IConnection, ImapFolderInfoCollection, Stream, BackupSettings, CancellationToken) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [BackupAsync](../../aspose.email.clients.imap/imapclient/backupasync#backupasync_3)(IConnection, ImapFolderInfoCollection, string, BackupSettings, CancellationToken) | النسخ الاحتياطي لمحتوى المجلدات المحددة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_18)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_20)(IEnumerable&lt;int&gt;, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_22)(IEnumerable&lt;string&gt;, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_14)(int, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_24)(string, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_6)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_8)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags)(IConnection, int, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_10)(IConnection, string, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_19)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_21)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_23)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_15)(int, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_16)(int, int, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_25)(string, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_26)(string, string, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_7)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_9)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_1)(IConnection, int, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_2)(IConnection, int, int, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_11)(IConnection, string, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_12)(IConnection, string, string, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_17)(int, int, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_27)(string, string, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_3)(IConnection, int, int, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlags](../../aspose.email.clients.imap/imapclient/changemessageflags#changemessageflags_13)(IConnection, string, string, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_36)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_40)(IEnumerable&lt;int&gt;, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_44)(IEnumerable&lt;string&gt;, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_28)(int, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_48)(string, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_8)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_12)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_16)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync)(IConnection, int, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_20)(IConnection, string, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_39)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_37)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_43)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_41)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_47)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_45)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_31)(int, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_29)(int, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_32)(int, int, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_51)(string, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_49)(string, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_52)(string, string, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_11)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_9)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_15)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_13)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_19)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_17)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_3)(IConnection, int, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_1)(IConnection, int, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_4)(IConnection, int, int, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_23)(IConnection, string, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_21)(IConnection, string, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_24)(IConnection, string, string, ImapMessageFlags) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_38)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_42)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_46)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_30)(int, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_35)(int, int, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_33)(int, int, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_50)(string, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_55)(string, string, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_53)(string, string, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_10)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_14)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_18)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_2)(IConnection, int, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_7)(IConnection, int, int, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_5)(IConnection, int, int, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_22)(IConnection, string, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_27)(IConnection, string, string, ImapMessageFlags, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_25)(IConnection, string, string, ImapMessageFlags, long) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_34)(int, int, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_54)(string, string, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_6)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ChangeMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/changemessageflagsasync#changemessageflagsasync_26)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | يغير أعلام الرسالة |
| [ClientCapabilities](../../aspose.email.clients.imap/imapclient/clientcapabilities#clientcapabilities_1)(params string[]) | لإعلام الخادم بالملحقات التي يدعمها العميل . يرجى ملاحظة أن هذه العملية تعمل فقط في حالة إذا كان الخادم يدعم RFC5161 انظر المزيد https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilities](../../aspose.email.clients.imap/imapclient/clientcapabilities#clientcapabilities)(IConnection, params string[]) | لإعلام الخادم بالملحقات التي يدعمها العميل . يرجى ملاحظة أن هذه العملية تعمل فقط في حالة إذا كان الخادم يدعم RFC5161 انظر المزيد https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync#clientcapabilitiesasync_2)(params string[]) | لإعلام الخادم بالملحقات التي يدعمها العميل . يرجى ملاحظة أن هذه العملية تعمل فقط في حالة إذا كان الخادم يدعم RFC5161 انظر المزيد https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync#clientcapabilitiesasync_3)(CancellationToken, params string[]) | لإعلام الخادم بالملحقات التي يدعمها العميل . يرجى ملاحظة أن هذه العملية تعمل فقط في حالة إذا كان الخادم يدعم RFC5161 انظر المزيد https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync#clientcapabilitiesasync)(IConnection, params string[]) | لإعلام الخادم بالملحقات التي يدعمها العميل . يرجى ملاحظة أن هذه العملية تعمل فقط في حالة إذا كان الخادم يدعم RFC5161 انظر المزيد https://tools.ietf.org/html/rfc5161 |
| [ClientCapabilitiesAsync](../../aspose.email.clients.imap/imapclient/clientcapabilitiesasync#clientcapabilitiesasync_1)(IConnection, CancellationToken, params string[]) | لإعلام الخادم بالملحقات التي يدعمها العميل . يرجى ملاحظة أن هذه العملية تعمل فقط في حالة إذا كان الخادم يدعم RFC5161 انظر المزيد https://tools.ietf.org/html/rfc5161 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes)() | تنفيذ عمليات الحذف |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_1)(IConnection) | تنفيذ عمليات الحذف |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_7)(IEnumerable&lt;string&gt;) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_6)(int) | تنفيذ عمليات الحذف |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_8)(string) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_3)(IConnection, IEnumerable&lt;string&gt;) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_2)(IConnection, int) | تنفيذ عمليات الحذف |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_4)(IConnection, string) | تنفيذ عمليات الحذف |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_9)(string, string) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletes](../../aspose.email.clients.imap/imapclient/commitdeletes#commitdeletes_5)(IConnection, string, string) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync)() | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_19)(CancellationToken) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_1)(IConnection) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_13)(IEnumerable&lt;string&gt;) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_11)(int) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_15)(string) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_10)(IConnection, CancellationToken) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_4)(IConnection, IEnumerable&lt;string&gt;) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_2)(IConnection, int) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_6)(IConnection, string) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_14)(IEnumerable&lt;string&gt;, CancellationToken) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_12)(int, CancellationToken) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_18)(string, CancellationToken) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_16)(string, string) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_5)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_3)(IConnection, int, CancellationToken) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_9)(IConnection, string, CancellationToken) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_7)(IConnection, string, string) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_17)(string, string, CancellationToken) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CommitDeletesAsync](../../aspose.email.clients.imap/imapclient/commitdeletesasync#commitdeletesasync_8)(IConnection, string, string, CancellationToken) | قم بتنفيذ الحذف تعمل هذه الطريقة فقط إذا كان الخادم يدعم ملحق UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage#copymessage_2)(int, string) | نسخ الرسالة |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage#copymessage_3)(string, string) | نسخ الرسالة |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage#copymessage)(IConnection, int, string) | نسخ الرسالة |
| [CopyMessage](../../aspose.email.clients.imap/imapclient/copymessage#copymessage_1)(IConnection, string, string) | نسخ الرسالة |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_4)(int, string) | نسخ الرسالة |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_6)(string, string) | نسخ الرسالة |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync)(IConnection, int, string) | نسخ الرسالة |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_2)(IConnection, string, string) | نسخ الرسالة |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_5)(int, string, CancellationToken) | نسخ الرسالة |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_7)(string, string, CancellationToken) | نسخ الرسالة |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_1)(IConnection, int, string, CancellationToken) | نسخ الرسالة |
| [CopyMessageAsync](../../aspose.email.clients.imap/imapclient/copymessageasync#copymessageasync_3)(IConnection, string, string, CancellationToken) | نسخ الرسالة |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_6)(IEnumerable&lt;ImapMessageInfo&gt;, string) | نسخ الرسائل |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_7)(IEnumerable&lt;int&gt;, string) | نسخ الرسائل |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_9)(IEnumerable&lt;string&gt;, string) | نسخ الرسائل |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_1)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | نسخ الرسائل |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_2)(IConnection, IEnumerable&lt;int&gt;, string) | نسخ الرسالة |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_3)(IConnection, IEnumerable&lt;string&gt;, string) | نسخ الرسائل |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_8)(IEnumerable&lt;int&gt;, string, bool) | نسخ الرسائل |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_5)(int, int, string) | نسخ الرسائل |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_10)(string, string, string) | نسخ الرسائل |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages)(IConnection, int, int, string) | نسخ الرسالة |
| [CopyMessages](../../aspose.email.clients.imap/imapclient/copymessages#copymessages_4)(IConnection, string, string, string) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_12)(IEnumerable&lt;ImapMessageInfo&gt;, string) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_14)(IEnumerable&lt;int&gt;, string) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_17)(IEnumerable&lt;string&gt;, string) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_2)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_4)(IConnection, IEnumerable&lt;int&gt;, string) | نسخ الرسالة |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_6)(IConnection, IEnumerable&lt;string&gt;, string) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_13)(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_16)(IEnumerable&lt;int&gt;, string, CancellationToken) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_18)(IEnumerable&lt;string&gt;, string, CancellationToken) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_10)(int, int, string) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_19)(string, string, string) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_3)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_5)(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) | نسخ الرسالة |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_7)(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync)(IConnection, int, int, string) | نسخ الرسالة |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_8)(IConnection, string, string, string) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_11)(int, int, string, CancellationToken) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_20)(string, string, string, CancellationToken) | نسخ الرسائل |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_1)(IConnection, int, int, string, CancellationToken) | نسخ الرسالة |
| [CopyMessagesAsync](../../aspose.email.clients.imap/imapclient/copymessagesasync#copymessagesasync_9)(IConnection, string, string, string, CancellationToken) | نسخ الرسائل |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | إنشاء اتصال مستقل جديد للعمليات غير المرتبطة بسلاسل الرسائل (وليس الاتصال الافتراضي) . يشبه استدعاء هذه الطريقة استدعاء CreateConnection (createAsDefaultConnection = false) يرجى الاطلاع على المزيد في الوثائق الخاصة بخاصية EmailClient.ConnectionAsgmtMode. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | إنشاء اتصال جديد (افتراضي أو مستقل) للعمليات . يرجى الاطلاع على المزيد في وثائق خاصية EmailClient.ConnectionAsgmtMode. |
| [CreateFolder](../../aspose.email.clients.imap/imapclient/createfolder#createfolder_1)(string) | إنشاء مجلد بالاسم المحدد |
| [CreateFolder](../../aspose.email.clients.imap/imapclient/createfolder#createfolder)(IConnection, string) | إنشاء مجلد بالاسم المحدد |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync#createfolderasync_2)(string) | إنشاء مجلد بالاسم المحدد |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync#createfolderasync)(IConnection, string) | إنشاء مجلد بالاسم المحدد |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync#createfolderasync_3)(string, CancellationToken) | إنشاء مجلد بالاسم المحدد |
| [CreateFolderAsync](../../aspose.email.clients.imap/imapclient/createfolderasync#createfolderasync_1)(IConnection, string, CancellationToken) | إنشاء مجلد بالاسم المحدد |
| [DeleteFolder](../../aspose.email.clients.imap/imapclient/deletefolder#deletefolder_1)(string) | حذف مجلد محدد. تمثل هذه الطريقة IMAP DELETE command |
| [DeleteFolder](../../aspose.email.clients.imap/imapclient/deletefolder#deletefolder)(IConnection, string) | حذف مجلد محدد. تمثل هذه الطريقة IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync#deletefolderasync_2)(string) | حذف مجلد محدد. تمثل هذه الطريقة IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync#deletefolderasync)(IConnection, string) | حذف مجلد محدد. تمثل هذه الطريقة IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync#deletefolderasync_3)(string, CancellationToken) | حذف مجلد محدد. تمثل هذه الطريقة IMAP DELETE command |
| [DeleteFolderAsync](../../aspose.email.clients.imap/imapclient/deletefolderasync#deletefolderasync_1)(IConnection, string, CancellationToken) | حذف مجلد محدد. تمثل هذه الطريقة IMAP DELETE command |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_6)(int) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_8)(string) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage)(IConnection, int) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_2)(IConnection, string) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_7)(int, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_9)(string, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_10)(string, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_1)(IConnection, int, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_3)(IConnection, string, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_4)(IConnection, string, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_11)(string, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessage](../../aspose.email.clients.imap/imapclient/deletemessage#deletemessage_5)(IConnection, string, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_12)(int) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_16)(string) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync)(IConnection, int) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_4)(IConnection, string) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_15)(int, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_13)(int, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_17)(string, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_23)(string, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_19)(string, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_3)(IConnection, int, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_1)(IConnection, int, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_5)(IConnection, string, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_11)(IConnection, string, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_7)(IConnection, string, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_14)(int, long, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_18)(string, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_20)(string, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_22)(string, long, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_2)(IConnection, int, long, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_6)(IConnection, string, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_8)(IConnection, string, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_10)(IConnection, string, long, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_21)(string, long, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessageAsync](../../aspose.email.clients.imap/imapclient/deletemessageasync#deletemessageasync_9)(IConnection, string, long, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_18)(IEnumerable&lt;ImapMessageInfo&gt;) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_22)(IEnumerable&lt;int&gt;) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_24)(IEnumerable&lt;string&gt;) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_2)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_6)(IConnection, IEnumerable&lt;int&gt;) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_8)(IConnection, IEnumerable&lt;string&gt;) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_19)(IEnumerable&lt;ImapMessageInfo&gt;, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_20)(IEnumerable&lt;ImapMessageInfo&gt;, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_23)(IEnumerable&lt;int&gt;, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_25)(IEnumerable&lt;string&gt;, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_26)(IEnumerable&lt;string&gt;, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_16)(int, int) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_28)(string, string) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_3)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_7)(IConnection, IEnumerable&lt;int&gt;, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_9)(IConnection, IEnumerable&lt;string&gt;, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_10)(IConnection, IEnumerable&lt;string&gt;, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages)(IConnection, int, int) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_12)(IConnection, string, string) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_21)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_27)(IEnumerable&lt;string&gt;, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_17)(int, int, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_29)(string, string, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_30)(string, string, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_11)(IConnection, IEnumerable&lt;string&gt;, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_1)(IConnection, int, int, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_13)(IConnection, string, string, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_14)(IConnection, string, string, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_31)(string, string, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessages](../../aspose.email.clients.imap/imapclient/deletemessages#deletemessages_15)(IConnection, string, string, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_36)(IEnumerable&lt;ImapMessageInfo&gt;) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_44)(IEnumerable&lt;int&gt;) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_48)(IEnumerable&lt;string&gt;) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_12)(IConnection, IEnumerable&lt;int&gt;) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_16)(IConnection, IEnumerable&lt;string&gt;) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_37)(IEnumerable&lt;ImapMessageInfo&gt;, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_43)(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_39)(IEnumerable&lt;ImapMessageInfo&gt;, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_47)(IEnumerable&lt;int&gt;, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_45)(IEnumerable&lt;int&gt;, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_49)(IEnumerable&lt;string&gt;, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_55)(IEnumerable&lt;string&gt;, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_51)(IEnumerable&lt;string&gt;, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_32)(int, int) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_56)(string, string) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_11)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_7)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_15)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_13)(IConnection, IEnumerable&lt;int&gt;, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_17)(IConnection, IEnumerable&lt;string&gt;, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_23)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_19)(IConnection, IEnumerable&lt;string&gt;, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync)(IConnection, int, int) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_24)(IConnection, string, string) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_38)(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_40)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_42)(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_46)(IEnumerable&lt;int&gt;, long, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_50)(IEnumerable&lt;string&gt;, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_52)(IEnumerable&lt;string&gt;, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_54)(IEnumerable&lt;string&gt;, long, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_35)(int, int, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_33)(int, int, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_57)(string, string, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_63)(string, string, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_59)(string, string, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_6)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_8)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_10)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_14)(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_18)(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_20)(IConnection, IEnumerable&lt;string&gt;, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_22)(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_3)(IConnection, int, int, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_1)(IConnection, int, int, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_25)(IConnection, string, string, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_31)(IConnection, string, string, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_27)(IConnection, string, string, long) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_41)(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_53)(IEnumerable&lt;string&gt;, long, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_34)(int, int, long, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_58)(string, string, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_60)(string, string, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_62)(string, string, long, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_9)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_21)(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_2)(IConnection, int, int, long, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_26)(IConnection, string, string, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_28)(IConnection, string, string, long, bool) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_30)(IConnection, string, string, long, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_61)(string, string, long, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| [DeleteMessagesAsync](../../aspose.email.clients.imap/imapclient/deletemessagesasync#deletemessagesasync_29)(IConnection, string, string, long, bool, CancellationToken) | وضع علامة على رسالة ذات المعرف الفريد المحدد على أنها محذوفة وتنفذ عمليات الحذف إذا حدد المستخدم هذا . تعمل هذه الطريقة فقط إذا كان الخادم يدعم امتداد UIDPLUS. من فضلك ، اقرأ المزيد https://tools.ietf.org/html/rfc4315 |
| override [Dispose](../../aspose.email.clients.imap/imapclient/dispose)() | إنهاء جميع العمليات مع الخادم. |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder#existfolder_2)(string) | تحقق مما إذا كان هذا المجلد موجودًا |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder#existfolder)(IConnection, string) | تحقق مما إذا كان هذا المجلد موجودًا |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder#existfolder_3)(string, out ImapFolderInfo) | تحقق مما إذا كان هذا المجلد موجودًا ، واستخرج معلومات المجلد إذا كان so |
| [ExistFolder](../../aspose.email.clients.imap/imapclient/existfolder#existfolder_1)(IConnection, string, out ImapFolderInfo) | تحقق مما إذا كان هذا المجلد موجودًا ، واستخرج معلومات المجلد إذا كان so |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync#existfolderasync_2)(string) | تحقق مما إذا كان هذا المجلد موجودًا |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync#existfolderasync)(IConnection, string) | تحقق مما إذا كان هذا المجلد موجودًا |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync#existfolderasync_3)(string, CancellationToken) | تحقق مما إذا كان هذا المجلد موجودًا |
| [ExistFolderAsync](../../aspose.email.clients.imap/imapclient/existfolderasync#existfolderasync_1)(IConnection, string, CancellationToken) | تحقق مما إذا كان هذا المجلد موجودًا |
| [FetchAttachment](../../aspose.email.clients.imap/imapclient/fetchattachment#fetchattachment_1)(int, string) | يجلب المرفق المحدد |
| [FetchAttachment](../../aspose.email.clients.imap/imapclient/fetchattachment#fetchattachment)(IConnection, int, string) | يجلب المرفق المحدد |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync#fetchattachmentasync_2)(int, string) | يجلب المرفق المحدد |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync#fetchattachmentasync)(IConnection, int, string) | يجلب المرفق المحدد |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync#fetchattachmentasync_3)(int, string, CancellationToken) | يجلب المرفق المحدد |
| [FetchAttachmentAsync](../../aspose.email.clients.imap/imapclient/fetchattachmentasync#fetchattachmentasync_1)(IConnection, int, string, CancellationToken) | يجلب المرفق المحدد |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage#fetchmessage_3)(int) | يجلب الرسالة |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage#fetchmessage_5)(string) | يجلب الرسالة |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage#fetchmessage)(IConnection, int) | يجلب الرسالة |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage#fetchmessage_2)(IConnection, string) | يجلب الرسالة |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage#fetchmessage_4)(int, bool) | يجلب الرسالة |
| [FetchMessage](../../aspose.email.clients.imap/imapclient/fetchmessage#fetchmessage_1)(IConnection, int, bool) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_6)(int) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_10)(string) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync)(IConnection, int) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_4)(IConnection, string) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_7)(int, bool) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_9)(int, CancellationToken) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_11)(string, CancellationToken) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_1)(IConnection, int, bool) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_3)(IConnection, int, CancellationToken) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_5)(IConnection, string, CancellationToken) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_8)(int, bool, CancellationToken) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.imap/imapclient/fetchmessageasync#fetchmessageasync_2)(IConnection, int, bool, CancellationToken) | يجلب الرسالة |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages#fetchmessages_2)(IEnumerable&lt;int&gt;) | جلب الرسائل |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages#fetchmessages_3)(IEnumerable&lt;string&gt;) | جلب الرسائل |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages#fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | جلب الرسائل |
| [FetchMessages](../../aspose.email.clients.imap/imapclient/fetchmessages#fetchmessages_1)(IConnection, IEnumerable&lt;string&gt;) | جلب الرسائل |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_4)(IEnumerable&lt;int&gt;) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_6)(IEnumerable&lt;string&gt;) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_2)(IConnection, IEnumerable&lt;string&gt;) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_5)(IEnumerable&lt;int&gt;, CancellationToken) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_7)(IEnumerable&lt;string&gt;, CancellationToken) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_1)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.imap/imapclient/fetchmessagesasync#fetchmessagesasync_3)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | جلب الرسائل بشكل غير متزامن |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| [GetFolderInfo](../../aspose.email.clients.imap/imapclient/getfolderinfo#getfolderinfo_1)(string) | إرجاع معلومات حول المجلد المحدد بدون تحديده |
| [GetFolderInfo](../../aspose.email.clients.imap/imapclient/getfolderinfo#getfolderinfo)(IConnection, string) | إرجاع معلومات حول المجلد المحدد بدون تحديده |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync#getfolderinfoasync_2)(string) | إرجاع معلومات حول المجلد المحدد بدون تحديده |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync#getfolderinfoasync)(IConnection, string) | إرجاع معلومات حول المجلد المحدد بدون تحديده |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync#getfolderinfoasync_3)(string, CancellationToken) | إرجاع معلومات حول المجلد المحدد بدون تحديده |
| [GetFolderInfoAsync](../../aspose.email.clients.imap/imapclient/getfolderinfoasync#getfolderinfoasync_1)(IConnection, string, CancellationToken) | إرجاع معلومات حول المجلد المحدد بدون تحديده |
| [GetMessageThreads](../../aspose.email.clients.imap/imapclient/getmessagethreads#getmessagethreads_1)(BaseSearchConditions) | الحصول على سلاسل الرسائل . |
| [GetMessageThreads](../../aspose.email.clients.imap/imapclient/getmessagethreads#getmessagethreads)(IConnection, BaseSearchConditions) | الحصول على سلاسل الرسائل . |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync#getmessagethreadsasync_2)(BaseSearchConditions) | الحصول على سلاسل الرسائل . |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync#getmessagethreadsasync_3)(BaseSearchConditions, CancellationToken) | الحصول على سلاسل الرسائل . |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync#getmessagethreadsasync)(IConnection, BaseSearchConditions) | الحصول على سلاسل الرسائل . |
| [GetMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/getmessagethreadsasync#getmessagethreadsasync_1)(IConnection, BaseSearchConditions, CancellationToken) | الحصول على سلاسل الرسائل . |
| [GetNamespaces](../../aspose.email.clients.imap/imapclient/getnamespaces#getnamespaces)() | يحصل على مساحات الأسماء المتاحة على الخادم. |
| [GetNamespaces](../../aspose.email.clients.imap/imapclient/getnamespaces#getnamespaces_1)(IConnection) | يحصل على مساحات الأسماء المتاحة على الخادم. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync#getnamespacesasync)() | يحصل على مساحات الأسماء المتاحة على الخادم. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync#getnamespacesasync_3)(CancellationToken) | يحصل على مساحات الأسماء المتاحة على الخادم. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync#getnamespacesasync_1)(IConnection) | يحصل على مساحات الأسماء المتاحة على الخادم. |
| [GetNamespacesAsync](../../aspose.email.clients.imap/imapclient/getnamespacesasync#getnamespacesasync_2)(IConnection, CancellationToken) | يحصل على مساحات الأسماء المتاحة على الخادم. |
| [GetQuota](../../aspose.email.clients.imap/imapclient/getquota#getquota_1)(string) | الحصول على معلومات الحصة |
| [GetQuota](../../aspose.email.clients.imap/imapclient/getquota#getquota)(IConnection, string) | يحصل على معلومات الحصة |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync#getquotaasync_2)(string) | الحصول على معلومات الحصة |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync#getquotaasync)(IConnection, string) | يحصل على معلومات الحصة |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync#getquotaasync_3)(string, CancellationToken) | الحصول على معلومات الحصة |
| [GetQuotaAsync](../../aspose.email.clients.imap/imapclient/getquotaasync#getquotaasync_1)(IConnection, string, CancellationToken) | يحصل على معلومات الحصة |
| [GetQuotaRoot](../../aspose.email.clients.imap/imapclient/getquotaroot#getquotaroot_1)(string) | الحصول على معلومات جذر الحصة النسبية لـ mailbox |
| [GetQuotaRoot](../../aspose.email.clients.imap/imapclient/getquotaroot#getquotaroot)(IConnection, string) | الحصول على معلومات جذر الحصة النسبية لـ mailbox |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync#getquotarootasync_2)(string) | الحصول على معلومات جذر الحصة النسبية لـ mailbox |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync#getquotarootasync)(IConnection, string) | الحصول على معلومات جذر الحصة النسبية لـ mailbox |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync#getquotarootasync_3)(string, CancellationToken) | الحصول على معلومات جذر الحصة النسبية لـ mailbox |
| [GetQuotaRootAsync](../../aspose.email.clients.imap/imapclient/getquotarootasync#getquotarootasync_1)(IConnection, string, CancellationToken) | الحصول على معلومات جذر الحصة النسبية لـ mailbox |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient#introduceclient)() | يقدم معلومات العميل إلى الخادم. |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient#introduceclient_1)(IConnection) | يقدم معلومات العميل إلى الخادم. |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient#introduceclient_3)(ImapIdentificationInfo) | يقدم معلومات العميل إلى الخادم. |
| [IntroduceClient](../../aspose.email.clients.imap/imapclient/introduceclient#introduceclient_2)(IConnection, ImapIdentificationInfo) | يقدم معلومات العميل إلى الخادم. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync)() | يقدم معلومات العميل إلى الخادم. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_7)(CancellationToken) | يقدم معلومات العميل إلى الخادم. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_1)(IConnection) | يقدم معلومات العميل إلى الخادم. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_5)(ImapIdentificationInfo) | يقدم معلومات العميل إلى الخادم. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_4)(IConnection, CancellationToken) | يقدم معلومات العميل إلى الخادم. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_2)(IConnection, ImapIdentificationInfo) | يقدم معلومات العميل إلى الخادم. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_6)(ImapIdentificationInfo, CancellationToken) | يقدم معلومات العميل إلى الخادم. |
| [IntroduceClientAsync](../../aspose.email.clients.imap/imapclient/introduceclientasync#introduceclientasync_3)(IConnection, ImapIdentificationInfo, CancellationToken) | يقدم معلومات العميل إلى الخادم. |
| [ListAttachments](../../aspose.email.clients.imap/imapclient/listattachments)(int) | يحصل على قائمة مرفقات الرسالة. يحصل على معلومات عن كل مرفق في الرسالة. |
| [ListAttachmentsAsync](../../aspose.email.clients.imap/imapclient/listattachmentsasync#listattachmentsasync)(int) | يحصل على قائمة مرفقات الرسالة. يحصل على معلومات عن كل مرفق في الرسالة. |
| [ListAttachmentsAsync](../../aspose.email.clients.imap/imapclient/listattachmentsasync#listattachmentsasync_1)(int, CancellationToken) | يحصل على قائمة مرفقات الرسالة. يحصل على معلومات عن كل مرفق في الرسالة. |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders)() | يحصل على قائمة المجلدات في صندوق البريد |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_6)(bool) | يحصل على قائمة المجلدات في صندوق البريد |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_1)(IConnection) | يحصل على قائمة المجلدات في صندوق البريد |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_7)(string) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_2)(IConnection, bool) | يحصل على قائمة المجلدات في صندوق البريد |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_3)(IConnection, string) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_8)(string, bool) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_4)(IConnection, string, bool) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_9)(string, bool, ListFoldersOptions, ListFoldersReturnOptions) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFolders](../../aspose.email.clients.imap/imapclient/listfolders#listfolders_5)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync)() | يحصل على قائمة المجلدات في صندوق البريد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_11)(bool) | يحصل على قائمة المجلدات في صندوق البريد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_19)(CancellationToken) | يحصل على قائمة المجلدات في صندوق البريد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_1)(IConnection) | يحصل على قائمة المجلدات في صندوق البريد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_13)(string) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_12)(bool, CancellationToken) | يحصل على قائمة المجلدات في صندوق البريد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_2)(IConnection, bool) | يحصل على قائمة المجلدات في صندوق البريد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_10)(IConnection, CancellationToken) | يحصل على قائمة المجلدات في صندوق البريد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_4)(IConnection, string) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_14)(string, bool) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_18)(string, CancellationToken) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_3)(IConnection, bool, CancellationToken) | يحصل على قائمة المجلدات في صندوق البريد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_5)(IConnection, string, bool) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_9)(IConnection, string, CancellationToken) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_17)(string, bool, CancellationToken) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_8)(IConnection, string, bool, CancellationToken) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_15)(string, bool, ListFoldersOptions, ListFoldersReturnOptions) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_6)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_16)(string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListFoldersAsync](../../aspose.email.clients.imap/imapclient/listfoldersasync#listfoldersasync_7)(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) | الحصول على قائمة المجلدات الفرعية في المجلد المحدد |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_4)(int) | الحصول على معلومات حول الرسالة . |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_6)(string) | الحصول على معلومات حول الرسالة . |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage)(IConnection, int) | الحصول على معلومات حول الرسالة . |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_2)(IConnection, string) | الحصول على معلومات حول الرسالة . |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_5)(int, IEnumerable&lt;string&gt;) | الحصول على معلومات حول الرسالة . |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_7)(string, IEnumerable&lt;string&gt;) | الحصول على معلومات حول الرسالة . |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_1)(IConnection, int, IEnumerable&lt;string&gt;) | الحصول على معلومات حول الرسالة . |
| [ListMessage](../../aspose.email.clients.imap/imapclient/listmessage#listmessage_3)(IConnection, string, IEnumerable&lt;string&gt;) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_8)(int) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_12)(string) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync)(IConnection, int) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_4)(IConnection, string) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_11)(int, CancellationToken) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_9)(int, IEnumerable&lt;string&gt;) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_15)(string, CancellationToken) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_13)(string, IEnumerable&lt;string&gt;) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_3)(IConnection, int, CancellationToken) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_1)(IConnection, int, IEnumerable&lt;string&gt;) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_7)(IConnection, string, CancellationToken) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_5)(IConnection, string, IEnumerable&lt;string&gt;) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_10)(int, IEnumerable&lt;string&gt;, CancellationToken) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_14)(string, IEnumerable&lt;string&gt;, CancellationToken) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_2)(IConnection, int, IEnumerable&lt;string&gt;, CancellationToken) | الحصول على معلومات حول الرسالة . |
| [ListMessageAsync](../../aspose.email.clients.imap/imapclient/listmessageasync#listmessageasync_6)(IConnection, string, IEnumerable&lt;string&gt;, CancellationToken) | الحصول على معلومات حول الرسالة . |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages)() | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_16)(bool) | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_1)(IConnection) | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_19)(IEnumerable&lt;string&gt;) | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_17)(int) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_18)(long) | الحصول على قائمة الرسائل الموجودة في المجلد الحالي التي تحتوي على تسلسل تعديل أكبر من القيمة المحددة . من فضلك ، راجع المزيد https://tools.ietf.org/html/rfc7162 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_14)(MailQuery) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_20)(string) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_4)(IConnection, bool) | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_5)(IConnection, int) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_6)(IConnection, long) | الحصول على قائمة الرسائل الموجودة في المجلد الحالي التي تحتوي على تسلسل تعديل أكبر من القيمة المحددة . من فضلك ، راجع المزيد https://tools.ietf.org/html/rfc7162 |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_2)(IConnection, MailQuery) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_7)(IConnection, string) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_15)(MailQuery, int) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_23)(string, bool) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_25)(string, IEnumerable&lt;int&gt;) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_26)(string, IEnumerable&lt;string&gt;) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_3)(IConnection, MailQuery, int) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_10)(IConnection, string, bool) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_12)(IConnection, string, IEnumerable&lt;int&gt;) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_13)(IConnection, string, IEnumerable&lt;string&gt;) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_24)(string, bool, IEnumerable&lt;string&gt;) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_21)(string, ImapListFields, int) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_22)(string, MailQuery, int) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_8)(IConnection, string, ImapListFields, int) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_9)(IConnection, string, MailQuery, int) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessages](../../aspose.email.clients.imap/imapclient/listmessages#listmessages_11)(IConnection, string, long, bool, IEnumerable&lt;string&gt;) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync)() | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_25)(bool) | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_41)(CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_1)(IConnection) | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_31)(IEnumerable&lt;string&gt;) | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_27)(int) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_29)(long) | الحصول على قائمة الرسائل الموجودة في المجلد الحالي التي تحتوي على تسلسل تعديل أكبر من القيمة المحددة . من فضلك ، راجع المزيد https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_21)(MailQuery) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_33)(string) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_26)(bool, CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_6)(IConnection, bool) | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_20)(IConnection, CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_8)(IConnection, int) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_10)(IConnection, long) | الحصول على قائمة الرسائل الموجودة في المجلد الحالي التي تحتوي على تسلسل تعديل أكبر من القيمة المحددة . من فضلك ، راجع المزيد https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_2)(IConnection, MailQuery) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_12)(IConnection, string) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_32)(IEnumerable&lt;string&gt;, CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_28)(int, CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_30)(long, CancellationToken) | الحصول على قائمة الرسائل الموجودة في المجلد الحالي التي تحتوي على تسلسل تعديل أكبر من القيمة المحددة . من فضلك ، راجع المزيد https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_24)(MailQuery, CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_22)(MailQuery, int) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_36)(string, bool) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_40)(string, CancellationToken) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_7)(IConnection, bool, CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_9)(IConnection, int, CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_11)(IConnection, long, CancellationToken) | الحصول على قائمة الرسائل الموجودة في المجلد الحالي التي تحتوي على تسلسل تعديل أكبر من القيمة المحددة . من فضلك ، راجع المزيد https://tools.ietf.org/html/rfc7162 |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_5)(IConnection, MailQuery, CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_3)(IConnection, MailQuery, int) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_15)(IConnection, string, bool) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_19)(IConnection, string, CancellationToken) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_23)(MailQuery, int, CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_39)(string, bool, CancellationToken) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_37)(string, bool, IEnumerable&lt;string&gt;) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_34)(string, MailQuery, int) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_4)(IConnection, MailQuery, int, CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_16)(IConnection, string, bool, CancellationToken) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_13)(IConnection, string, MailQuery, int) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_38)(string, bool, IEnumerable&lt;string&gt;, CancellationToken) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_35)(string, MailQuery, int, CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_17)(IConnection, string, long, bool, IEnumerable&lt;string&gt;) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_14)(IConnection, string, MailQuery, int, CancellationToken) | الحصول على قائمة الرسائل في المجلد الحالي. |
| [ListMessagesAsync](../../aspose.email.clients.imap/imapclient/listmessagesasync#listmessagesasync_18)(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) | الحصول على قائمة الرسائل في المجلد المحدد |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage#listmessagesbypage_2)(int, PageSettings) | يحصل على قائمة الرسائل |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage#listmessagesbypage)(PageInfo, PageSettings) | يحصل على قائمة الرسائل |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage#listmessagesbypage_3)(int, int, PageSettings) | يحصل على قائمة الرسائل |
| [ListMessagesByPage](../../aspose.email.clients.imap/imapclient/listmessagesbypage#listmessagesbypage_1)(MailQuery, PageInfo, PageSettings) | يحصل على قائمة الرسائل |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync#listmessagesbypageasync_2)(int, int, PageSettings) | يحصل على قائمة الرسائل |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync#listmessagesbypageasync)(MailQuery, PageInfo, PageSettings) | يحصل على قائمة الرسائل |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync#listmessagesbypageasync_3)(int, int, PageSettings, CancellationToken) | يحصل على قائمة الرسائل |
| [ListMessagesByPageAsync](../../aspose.email.clients.imap/imapclient/listmessagesbypageasync#listmessagesbypageasync_1)(MailQuery, PageInfo, PageSettings, CancellationToken) | يحصل على قائمة الرسائل |
| [MoveFolder](../../aspose.email.clients.imap/imapclient/movefolder#movefolder_1)(string, string) | نقل المجلد المحدد ومجلداته الفرعية إلى موقع جديد. |
| [MoveFolder](../../aspose.email.clients.imap/imapclient/movefolder#movefolder)(IConnection, string, string) | نقل المجلد المحدد ومجلداته الفرعية إلى موقع جديد. |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync#movefolderasync_2)(string, string) | نقل المجلد المحدد ومجلداته الفرعية إلى موقع جديد. |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync#movefolderasync)(IConnection, string, string) | نقل المجلد المحدد ومجلداته الفرعية إلى موقع جديد. |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync#movefolderasync_3)(string, string, CancellationToken) | نقل المجلد المحدد ومجلداته الفرعية إلى موقع جديد. |
| [MoveFolderAsync](../../aspose.email.clients.imap/imapclient/movefolderasync#movefolderasync_1)(IConnection, string, string, CancellationToken) | نقل المجلد المحدد ومجلداته الفرعية إلى موقع جديد. |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_4)(int, string) | لنقل الرسالة |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_6)(string, string) | لنقل الرسالة |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage)(IConnection, int, string) | نقل الرسالة |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_2)(IConnection, string, string) | لنقل الرسالة |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_5)(int, string, bool) | لنقل الرسالة |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_7)(string, string, bool) | لنقل الرسالة |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_1)(IConnection, int, string, bool) | نقل الرسالة |
| [MoveMessage](../../aspose.email.clients.imap/imapclient/movemessage#movemessage_3)(IConnection, string, string, bool) | لنقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_8)(int, string) | لنقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_12)(string, string) | لنقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync)(IConnection, int, string) | نقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_4)(IConnection, string, string) | لنقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_9)(int, string, bool) | لنقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_11)(int, string, CancellationToken) | لنقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_13)(string, string, bool) | لنقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_15)(string, string, CancellationToken) | لنقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_1)(IConnection, int, string, bool) | نقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_3)(IConnection, int, string, CancellationToken) | نقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_5)(IConnection, string, string, bool) | لنقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_7)(IConnection, string, string, CancellationToken) | لنقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_10)(int, string, bool, CancellationToken) | لنقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_14)(string, string, bool, CancellationToken) | لنقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_2)(IConnection, int, string, bool, CancellationToken) | نقل الرسالة |
| [MoveMessageAsync](../../aspose.email.clients.imap/imapclient/movemessageasync#movemessageasync_6)(IConnection, string, string, bool, CancellationToken) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_12)(IEnumerable&lt;ImapMessageInfo&gt;, string) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_14)(IEnumerable&lt;int&gt;, string) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_16)(IEnumerable&lt;string&gt;, string) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_2)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_4)(IConnection, IEnumerable&lt;int&gt;, string) | نقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_6)(IConnection, IEnumerable&lt;string&gt;, string) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_13)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_15)(IEnumerable&lt;int&gt;, string, bool) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_17)(IEnumerable&lt;string&gt;, string, bool) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_10)(int, int, string) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_18)(string, string, string) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_3)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_5)(IConnection, IEnumerable&lt;int&gt;, string, bool) | نقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_7)(IConnection, IEnumerable&lt;string&gt;, string, bool) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages)(IConnection, int, int, string) | نقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_8)(IConnection, string, string, string) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_11)(int, int, string, bool) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_19)(string, string, string, bool) | لنقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_1)(IConnection, int, int, string, bool) | نقل الرسالة |
| [MoveMessages](../../aspose.email.clients.imap/imapclient/movemessages#movemessages_9)(IConnection, string, string, string, bool) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_24)(IEnumerable&lt;ImapMessageInfo&gt;, string) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_28)(IEnumerable&lt;int&gt;, string) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_32)(IEnumerable&lt;string&gt;, string) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_8)(IConnection, IEnumerable&lt;int&gt;, string) | نقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_12)(IConnection, IEnumerable&lt;string&gt;, string) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_25)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_27)(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_29)(IEnumerable&lt;int&gt;, string, bool) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_31)(IEnumerable&lt;int&gt;, string, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_33)(IEnumerable&lt;string&gt;, string, bool) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_35)(IEnumerable&lt;string&gt;, string, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_20)(int, int, string) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_36)(string, string, string) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_7)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_9)(IConnection, IEnumerable&lt;int&gt;, string, bool) | نقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_11)(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) | نقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_13)(IConnection, IEnumerable&lt;string&gt;, string, bool) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_15)(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync)(IConnection, int, int, string) | نقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_16)(IConnection, string, string, string) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_26)(IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_30)(IEnumerable&lt;int&gt;, string, bool, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_34)(IEnumerable&lt;string&gt;, string, bool, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_21)(int, int, string, bool) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_23)(int, int, string, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_37)(string, string, string, bool) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_39)(string, string, string, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_6)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_10)(IConnection, IEnumerable&lt;int&gt;, string, bool, CancellationToken) | نقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_14)(IConnection, IEnumerable&lt;string&gt;, string, bool, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_1)(IConnection, int, int, string, bool) | نقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_3)(IConnection, int, int, string, CancellationToken) | نقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_17)(IConnection, string, string, string, bool) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_19)(IConnection, string, string, string, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_22)(int, int, string, bool, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_38)(string, string, string, bool, CancellationToken) | لنقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_2)(IConnection, int, int, string, bool, CancellationToken) | نقل الرسالة |
| [MoveMessagesAsync](../../aspose.email.clients.imap/imapclient/movemessagesasync#movemessagesasync_18)(IConnection, string, string, string, bool, CancellationToken) | لنقل الرسالة |
| override [Noop](../../aspose.email.clients.imap/imapclient/noop#noop)() | "بدون عملية" command |
| override [Noop](../../aspose.email.clients.imap/imapclient/noop#noop_1)(IConnection) | "بدون عملية" command |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync#noopasync)() | "بدون عملية" command |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync#noopasync_3)(CancellationToken) | "بدون عملية" command |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync#noopasync_1)(IConnection) | "بدون عملية" command |
| [NoopAsync](../../aspose.email.clients.imap/imapclient/noopasync#noopasync_2)(IConnection, CancellationToken) | "بدون عملية" command |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_18)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_20)(IEnumerable&lt;int&gt;, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_22)(IEnumerable&lt;string&gt;, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_14)(int, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_24)(string, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_4)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_6)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_8)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags)(IConnection, int, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_10)(IConnection, string, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_19)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_21)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_23)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_15)(int, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_16)(int, int, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_25)(string, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_26)(string, string, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_5)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_7)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_9)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_1)(IConnection, int, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_2)(IConnection, int, int, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_11)(IConnection, string, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_12)(IConnection, string, string, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_17)(int, int, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_27)(string, string, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_3)(IConnection, int, int, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlags](../../aspose.email.clients.imap/imapclient/removemessageflags#removemessageflags_13)(IConnection, string, string, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_36)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_40)(IEnumerable&lt;int&gt;, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_44)(IEnumerable&lt;string&gt;, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_28)(int, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_48)(string, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_8)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_12)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_16)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync)(IConnection, int, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_20)(IConnection, string, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_39)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_37)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_43)(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_41)(IEnumerable&lt;int&gt;, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_47)(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_45)(IEnumerable&lt;string&gt;, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_31)(int, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_29)(int, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_32)(int, int, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_51)(string, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_49)(string, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_52)(string, string, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_11)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_9)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_15)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_13)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_19)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_17)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_3)(IConnection, int, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_1)(IConnection, int, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_4)(IConnection, int, int, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_23)(IConnection, string, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_21)(IConnection, string, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_24)(IConnection, string, string, ImapMessageFlags) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_38)(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_42)(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_46)(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_30)(int, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_35)(int, int, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_33)(int, int, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_50)(string, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_55)(string, string, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_53)(string, string, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_10)(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_14)(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_18)(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_2)(IConnection, int, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_7)(IConnection, int, int, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_5)(IConnection, int, int, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_22)(IConnection, string, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_27)(IConnection, string, string, ImapMessageFlags, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_25)(IConnection, string, string, ImapMessageFlags, long) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_34)(int, int, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_54)(string, string, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_6)(IConnection, int, int, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RemoveMessageFlagsAsync](../../aspose.email.clients.imap/imapclient/removemessageflagsasync#removemessageflagsasync_26)(IConnection, string, string, ImapMessageFlags, long, CancellationToken) | يزيل إشارات الرسالة |
| [RenameFolder](../../aspose.email.clients.imap/imapclient/renamefolder#renamefolder_1)(string, string) | إعادة تسمية مجلد محدد باسم جديد |
| [RenameFolder](../../aspose.email.clients.imap/imapclient/renamefolder#renamefolder)(IConnection, string, string) | إعادة تسمية مجلد محدد باسم جديد |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync#renamefolderasync_2)(string, string) | إعادة تسمية مجلد محدد باسم جديد |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync#renamefolderasync)(IConnection, string, string) | إعادة تسمية مجلد محدد باسم جديد |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync#renamefolderasync_3)(string, string, CancellationToken) | إعادة تسمية مجلد محدد باسم جديد |
| [RenameFolderAsync](../../aspose.email.clients.imap/imapclient/renamefolderasync#renamefolderasync_1)(IConnection, string, string, CancellationToken) | إعادة تسمية مجلد محدد باسم جديد |
| [RequestCheckpoint](../../aspose.email.clients.imap/imapclient/requestcheckpoint#requestcheckpoint)() | يطلب نقطة فحص لصندوق البريد المحدد حاليًا. |
| [RequestCheckpoint](../../aspose.email.clients.imap/imapclient/requestcheckpoint#requestcheckpoint_1)(IConnection) | يطلب نقطة فحص لصندوق البريد المحدد حاليًا. |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync#requestcheckpointasync)() | يطلب نقطة فحص لصندوق البريد المحدد حاليًا. |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync#requestcheckpointasync_3)(CancellationToken) | يطلب نقطة فحص لصندوق البريد المحدد حاليًا. |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync#requestcheckpointasync_1)(IConnection) | يطلب نقطة فحص لصندوق البريد المحدد حاليًا. |
| [RequestCheckpointAsync](../../aspose.email.clients.imap/imapclient/requestcheckpointasync#requestcheckpointasync_2)(IConnection, CancellationToken) | يطلب نقطة فحص لصندوق البريد المحدد حاليًا. |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | يعيد تعيين إعدادات التسجيل إلى الإعدادات الافتراضية. |
| [Restore](../../aspose.email.clients.imap/imapclient/restore)(PersonalStorage, RestoreSettings) | يبدأ في استعادة مجلدات imap من وحدة التخزين الشخصية المحددة. |
| [RestoreAsync](../../aspose.email.clients.imap/imapclient/restoreasync#restoreasync)(PersonalStorage, RestoreSettings) | يبدأ في استعادة مجلدات imap من وحدة التخزين الشخصية المحددة. |
| [RestoreAsync](../../aspose.email.clients.imap/imapclient/restoreasync#restoreasync_1)(PersonalStorage, RestoreSettings, CancellationToken) | يبدأ في استعادة مجلدات imap من وحدة التخزين الشخصية المحددة. |
| [ResumeMonitoring](../../aspose.email.clients.imap/imapclient/resumemonitoring)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState) | يستأنف مراقبة تغييرات الرسائل للمجلد المحدد. على عكس طريقة StartMonitoring ، فإنه سيجد جميع تغييرات صندوق البريد المفقودة ويستدعى رد الاتصال الخاص بهم. |
| [ResumeMonitoringAsync](../../aspose.email.clients.imap/imapclient/resumemonitoringasync)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, IImapMonitoringState, CancellationToken) | يستأنف مراقبة تغييرات الرسائل للمجلد المحدد. على عكس طريقة StartMonitoring ، فإنه سيجد جميع تغييرات صندوق البريد المفقودة ويستدعى رد الاتصال الخاص بهم. |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_4)(int, Stream) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في تدفق |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_5)(int, string) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في ملف محلي |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_6)(string, Stream) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في تدفق |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_7)(string, string) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في ملف محلي |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage)(IConnection, int, Stream) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في تدفق |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_1)(IConnection, int, string) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في ملف محلي |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_2)(IConnection, string, Stream) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في تدفق |
| [SaveMessage](../../aspose.email.clients.imap/imapclient/savemessage#savemessage_3)(IConnection, string, string) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في ملف محلي |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_8)(int, Stream) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في تدفق |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_10)(int, string) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في ملف محلي |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_12)(string, Stream) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في تدفق |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_14)(string, string) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في ملف محلي |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync)(IConnection, int, Stream) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في تدفق |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_2)(IConnection, int, string) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في ملف محلي |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_4)(IConnection, string, Stream) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في تدفق |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_6)(IConnection, string, string) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في ملف محلي |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_9)(int, Stream, CancellationToken) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في تدفق |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_11)(int, string, CancellationToken) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في ملف محلي |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_13)(string, Stream, CancellationToken) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في تدفق |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_15)(string, string, CancellationToken) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في ملف محلي |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_1)(IConnection, int, Stream, CancellationToken) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في تدفق |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_3)(IConnection, int, string, CancellationToken) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في ملف محلي |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_5)(IConnection, string, Stream, CancellationToken) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في تدفق |
| [SaveMessageAsync](../../aspose.email.clients.imap/imapclient/savemessageasync#savemessageasync_7)(IConnection, string, string, CancellationToken) | يقوم بتنزيل الرسالة برقم التسلسل المحدد وكتابة بياناتها في ملف محلي |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder#selectfolder_2)(string) | تحديد المجلد المحدد |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder#selectfolder)(IConnection, string) | تحديد المجلد المحدد |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder#selectfolder_3)(string, bool?) | تحديد المجلد المحدد |
| [SelectFolder](../../aspose.email.clients.imap/imapclient/selectfolder#selectfolder_1)(IConnection, string, bool?) | تحديد المجلد المحدد |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_4)(string) | تحديد المجلد المحدد |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync)(IConnection, string) | تحديد المجلد المحدد |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_5)(string, bool?) | تحديد المجلد المحدد |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_7)(string, CancellationToken) | تحديد المجلد المحدد |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_1)(IConnection, string, bool?) | تحديد المجلد المحدد |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_3)(IConnection, string, CancellationToken) | تحديد المجلد المحدد |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_6)(string, bool?, CancellationToken) | تحديد المجلد المحدد |
| [SelectFolderAsync](../../aspose.email.clients.imap/imapclient/selectfolderasync#selectfolderasync_2)(IConnection, string, bool?, CancellationToken) | تحديد المجلد المحدد |
| [SetQuota](../../aspose.email.clients.imap/imapclient/setquota#setquota_1)(string, string, int) | تعيين معلومات الحصة |
| [SetQuota](../../aspose.email.clients.imap/imapclient/setquota#setquota)(IConnection, string, string, int) | تعيين معلومات الحصة |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync#setquotaasync_2)(string, string, int) | تعيين معلومات الحصة |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync#setquotaasync)(IConnection, string, string, int) | تعيين معلومات الحصة |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync#setquotaasync_3)(string, string, int, CancellationToken) | تعيين معلومات الحصة |
| [SetQuotaAsync](../../aspose.email.clients.imap/imapclient/setquotaasync#setquotaasync_1)(IConnection, string, string, int, CancellationToken) | تعيين معلومات الحصة |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | يحدد إصدارات بروتوكولات تشفير SSL / TLS التي سيتم استخدامها. هذه الطريقة ليست آمنة وتقوم بتعيين بروتوكولات التشفير دون أي فحوصات توافق.[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) لتعيين البروتوكولات بأمان فقط التي يدعمها إطار عمل. net . يرجى ملاحظة ، إذا كان إطار عمل .net الحالي الخاص بك لا يدعم هذا المستوى من الأمان ، فسيتم طرح استثناء عند محاولة إنشاء اتصال بالخادم. |
| [SortMessageThreads](../../aspose.email.clients.imap/imapclient/sortmessagethreads#sortmessagethreads_1)(SortConditions) | الحصول على سلاسل الرسائل . |
| [SortMessageThreads](../../aspose.email.clients.imap/imapclient/sortmessagethreads#sortmessagethreads)(IConnection, SortConditions) | الحصول على سلاسل الرسائل . |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync#sortmessagethreadsasync_2)(SortConditions) | فرز رسائل الرسائل . |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync#sortmessagethreadsasync)(IConnection, SortConditions) | فرز رسائل الرسائل . |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync#sortmessagethreadsasync_3)(SortConditions, CancellationToken) | فرز رسائل الرسائل . |
| [SortMessageThreadsAsync](../../aspose.email.clients.imap/imapclient/sortmessagethreadsasync#sortmessagethreadsasync_1)(IConnection, SortConditions, CancellationToken) | فرز رسائل الرسائل . |
| [StartMonitoring](../../aspose.email.clients.imap/imapclient/startmonitoring#startmonitoring_1)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | يبدأ في مراقبة تغييرات الرسائل للمجلد المحدد. |
| [StartMonitoringAsync](../../aspose.email.clients.imap/imapclient/startmonitoringasync#startmonitoringasync_1)(ImapMonitoringEventHandler, ImapMonitoringErrorEventHandler, string) | يبدأ في مراقبة تغييرات الرسائل للمجلد المحدد. |
| [StopMonitoring](../../aspose.email.clients.imap/imapclient/stopmonitoring#stopmonitoring)() | يوقف أي مراقبة للتغييرات . |
| [StopMonitoring](../../aspose.email.clients.imap/imapclient/stopmonitoring#stopmonitoring_1)(string) | يوقف مراقبة تغييرات الرسائل للمجلد المحدد. |
| [StopMonitoringAsync](../../aspose.email.clients.imap/imapclient/stopmonitoringasync#stopmonitoringasync)() | يوقف أي مراقبة للتغييرات . |
| [StopMonitoringAsync](../../aspose.email.clients.imap/imapclient/stopmonitoringasync#stopmonitoringasync_1)(string) | يوقف مراقبة تغييرات الرسائل للمجلد المحدد. |
| [SubscribeFolder](../../aspose.email.clients.imap/imapclient/subscribefolder#subscribefolder_1)(string) | أرسل أمر الاشتراك الذي يضيف اسم صندوق البريد المحدد إلى مجموعة صناديق البريد "النشطة" الخاصة بالخادم. |
| [SubscribeFolder](../../aspose.email.clients.imap/imapclient/subscribefolder#subscribefolder)(IConnection, string) | أرسل أمر الاشتراك الذي يضيف اسم صندوق البريد المحدد إلى مجموعة صناديق البريد "النشطة" الخاصة بالخادم. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync#subscribefolderasync_2)(string) | أرسل أمر الاشتراك الذي يضيف اسم صندوق البريد المحدد إلى مجموعة صناديق البريد "النشطة" الخاصة بالخادم. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync#subscribefolderasync)(IConnection, string) | أرسل أمر الاشتراك الذي يضيف اسم صندوق البريد المحدد إلى مجموعة صناديق البريد "النشطة" الخاصة بالخادم. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync#subscribefolderasync_3)(string, CancellationToken) | أرسل أمر الاشتراك الذي يضيف اسم صندوق البريد المحدد إلى مجموعة صناديق البريد "النشطة" الخاصة بالخادم. |
| [SubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/subscribefolderasync#subscribefolderasync_1)(IConnection, string, CancellationToken) | أرسل أمر الاشتراك الذي يضيف اسم صندوق البريد المحدد إلى مجموعة صناديق البريد "النشطة" الخاصة بالخادم. |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_4)(int) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_6)(string) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها. |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage)(IConnection, int) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_2)(IConnection, string) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها. |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_5)(int, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_7)(string, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها. |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_1)(IConnection, int, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها |
| [UndeleteMessage](../../aspose.email.clients.imap/imapclient/undeletemessage#undeletemessage_3)(IConnection, string, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_8)(int) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_12)(string) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync)(IConnection, int) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_4)(IConnection, string) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_11)(int, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_9)(int, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_15)(string, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_13)(string, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_3)(IConnection, int, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_1)(IConnection, int, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_7)(IConnection, string, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_5)(IConnection, string, long) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_10)(int, long, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_14)(string, long, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها. |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_2)(IConnection, int, long, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها |
| [UndeleteMessageAsync](../../aspose.email.clients.imap/imapclient/undeletemessageasync#undeletemessageasync_6)(IConnection, string, long, CancellationToken) | وضع علامة على رسالة برقم التسلسل المحدد على أنها لم يتم حذفها. |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder#unselectfolder)() | يزيل بشكل دائم كافة الرسائل التي تم وضع علامة عليها كمحذوفة للمجلد المحدد حاليًا ويزيل الحالة المحددة لهذا المجلد. |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder#unselectfolder_3)(bool) | إلغاء تحديد المجلد المحدد حاليًا. إذا كانت خاصية doNotExpunge صحيحة ، فسيتم وضع علامة على جميع الرسائل على أنها محذوفة ، وإلا تم إلغاء الحذف. ietf.org/html/rfc3691 |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder#unselectfolder_1)(IConnection) | يزيل بشكل دائم كافة الرسائل التي تم وضع علامة عليها كمحذوفة للمجلد المحدد حاليًا ويزيل الحالة المحددة لهذا المجلد. |
| [UnselectFolder](../../aspose.email.clients.imap/imapclient/unselectfolder#unselectfolder_2)(IConnection, bool) | إلغاء تحديد المجلد المحدد حاليًا. إذا كانت خاصية doNotExpunge صحيحة ، فسيتم وضع علامة على جميع الرسائل على أنها محذوفة ، وإلا تم إلغاء الحذف. ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync)() | يزيل بشكل دائم كافة الرسائل التي تم وضع علامة عليها كمحذوفة للمجلد المحدد حاليًا ويزيل الحالة المحددة لهذا المجلد. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_5)(bool) | إلغاء تحديد المجلد المحدد حاليًا. إذا كانت خاصية doNotExpunge صحيحة ، فسيتم وضع علامة على جميع الرسائل على أنها محذوفة ، وإلا تم إلغاء الحذف. ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_7)(CancellationToken) | يزيل بشكل دائم كافة الرسائل التي تم وضع علامة عليها كمحذوفة للمجلد المحدد حاليًا ويزيل الحالة المحددة لهذا المجلد. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_1)(IConnection) | يزيل بشكل دائم كافة الرسائل التي تم وضع علامة عليها كمحذوفة للمجلد المحدد حاليًا ويزيل الحالة المحددة لهذا المجلد. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_6)(bool, CancellationToken) | إلغاء تحديد المجلد المحدد حاليًا. إذا كانت خاصية doNotExpunge صحيحة ، فسيتم وضع علامة على جميع الرسائل على أنها محذوفة ، وإلا تم إلغاء الحذف. ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_2)(IConnection, bool) | إلغاء تحديد المجلد المحدد حاليًا. إذا كانت خاصية doNotExpunge صحيحة ، فسيتم وضع علامة على جميع الرسائل على أنها محذوفة ، وإلا تم إلغاء الحذف. ietf.org/html/rfc3691 |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_4)(IConnection, CancellationToken) | يزيل بشكل دائم كافة الرسائل التي تم وضع علامة عليها كمحذوفة للمجلد المحدد حاليًا ويزيل الحالة المحددة لهذا المجلد. |
| [UnselectFolderAsync](../../aspose.email.clients.imap/imapclient/unselectfolderasync#unselectfolderasync_3)(IConnection, bool, CancellationToken) | إلغاء تحديد المجلد المحدد حاليًا. إذا كانت خاصية doNotExpunge صحيحة ، فسيتم وضع علامة على جميع الرسائل على أنها محذوفة ، وإلا تم إلغاء الحذف. ietf.org/html/rfc3691 |
| [UnsubscribeFolder](../../aspose.email.clients.imap/imapclient/unsubscribefolder#unsubscribefolder_1)(string) | أرسل الأمر UNSUBSCRIBE الذي يزيل اسم صندوق البريد المحدد من مجموعة علب البريد "النشطة" على الخادم |
| [UnsubscribeFolder](../../aspose.email.clients.imap/imapclient/unsubscribefolder#unsubscribefolder)(IConnection, string) | أرسل الأمر UNSUBSCRIBE الذي يزيل اسم صندوق البريد المحدد من مجموعة علب البريد "النشطة" على الخادم |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync#unsubscribefolderasync_2)(string) | أرسل الأمر UNSUBSCRIBE الذي يزيل اسم صندوق البريد المحدد من مجموعة علب البريد "النشطة" على الخادم |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync#unsubscribefolderasync)(IConnection, string) | أرسل الأمر UNSUBSCRIBE الذي يزيل اسم صندوق البريد المحدد من مجموعة علب البريد "النشطة" على الخادم |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync#unsubscribefolderasync_3)(string, CancellationToken) | أرسل الأمر UNSUBSCRIBE الذي يزيل اسم صندوق البريد المحدد من مجموعة علب البريد "النشطة" على الخادم |
| [UnsubscribeFolderAsync](../../aspose.email.clients.imap/imapclient/unsubscribefolderasync#unsubscribefolderasync_1)(IConnection, string, CancellationToken) | أرسل الأمر UNSUBSCRIBE الذي يزيل اسم صندوق البريد المحدد من مجموعة علب البريد "النشطة" على الخادم |
| override [ValidateCredentials](../../aspose.email.clients.imap/imapclient/validatecredentials#validatecredentials)() | تنفيذ التحقق من صحة بيانات الاعتماد |
| [ValidateCredentials](../../aspose.email.clients.imap/imapclient/validatecredentials#validatecredentials_1)(IConnection) | تنفيذ التحقق من صحة بيانات الاعتماد |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync#validatecredentialsasync)() | تنفيذ التحقق من صحة بيانات الاعتماد |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | تنفيذ التحقق من صحة بيانات الاعتماد |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | تنفيذ التحقق من صحة بيانات الاعتماد |
| [ValidateCredentialsAsync](../../aspose.email.clients.imap/imapclient/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | تنفيذ التحقق من صحة بيانات الاعتماد |
| static [CreateAsync](../../aspose.email.clients.imap/imapclient/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | لإنشاء مثيل جديد لملف[`ImapClient`](../imapclient) فئة |

### أنظر أيضا

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncImapClient](../iasyncimapclient)
* مساحة الاسم [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
