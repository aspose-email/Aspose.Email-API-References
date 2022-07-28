---
title: Pop3Client
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يسمح للتطبيقات بالوصول إلى رسائل ومعالجتها باستخدام الإصدار 3 من بروتوكول Post Office Protocol POP3 .
type: docs
weight: 16880
url: /ar/net/aspose.email.clients.pop3/pop3client/
---
## Pop3Client class

يسمح للتطبيقات بالوصول إلى رسائل ومعالجتها باستخدام الإصدار 3 من بروتوكول Post Office Protocol (POP3) .

```csharp
public sealed class Pop3Client : EmailClient, IAsyncPop3Client
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Pop3Client](pop3client#constructor)() | يقوم بتهيئة مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |
| [Pop3Client](pop3client#constructor_1)(string) | يقوم بتهيئة مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |
| [Pop3Client](pop3client#constructor_3)(string, int) | يقوم بتهيئة مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |
| [Pop3Client](pop3client#constructor_2)(string, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |
| [Pop3Client](pop3client#constructor_4)(string, int, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |
| [Pop3Client](pop3client#constructor_11)(string, string, string) | يقوم بتهيئة مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |
| [Pop3Client](pop3client#constructor_6)(string, int, string, string) | يقوم بتهيئة مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |
| [Pop3Client](pop3client#constructor_12)(string, string, string, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |
| [Pop3Client](pop3client#constructor_5)(string, int, string, ITokenProvider, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |
| [Pop3Client](pop3client#constructor_9)(string, int, string, string, RemoteCertificateValidationCallback) | يقوم بتهيئة مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |
| [Pop3Client](pop3client#constructor_7)(string, int, string, string, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |
| [Pop3Client](pop3client#constructor_8)(string, int, string, string, bool, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |
| [Pop3Client](pop3client#constructor_10)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | يقوم بتهيئة مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | الحصول على رمز الوصول أو تعيينه. |
| [AllowedAuthentication](../../aspose.email.clients.pop3/pop3client/allowedauthentication) { get; set; } | الحصول على أو تعيين التعداد المسموح به بواسطة أنواع مصادقة المستخدم |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | يحتوي على مجموعة من شهادات العملاء |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | الحصول على أو تعيين القيمة التي تحدد وضع تخصيص الاتصال في بيئة مؤشرات الترابط المتعددة هناك أنواع اتصال متتابعة: - الاتصال الرئيسي هو الاتصال الذي تم إنشاؤه والتخلص منه مع عميل البريد. لا يمكن إنشاؤه أو التخلص منه يدويًا. - الاتصال الافتراضي هو الاتصال الافتراضي لبعض مؤشرات الترابط . إذا كان الاتصال الافتراضي موجودًا وكان ConnectionAsgmtMode يسمح بذلك ، فسيتم استخدام هذا الاتصال ضمنيًا لجميع طرق عميل البريد الإلكتروني المنفذة في هذا الموضوع. يمكن إنشاؤه يدويًا أو تلقائيًا. يعتمد ذلك على خاصية EmailClient.ConnectionAsgmtMode. يمكن إنشاء هذه الاتصالات يدويًا باستخدام طريقة EmailClient.CreateConnection (createAsDefaultConnection = true) . إذا لم يتم استخدام الاتصال الافتراضي (يعتمد على وضع تخصيص الاتصال) ، يتم استخدام الاتصال الرئيسي بشكل ضمني بدلاً منه. - الاتصالات المستقلة هي اتصالات غير مرتبطة بخيوط. يمكن إنشاؤها يدويًا ويجب استخدامها بشكل صريح كمعامل أسلوب. يمكن إنشاء هذه الاتصالات يدويًا باستخدام طريقة EmailClient.CreateConnection () أو طريقة EmailClient.CreateConnection (createAsDefaultConnection = false). هناك أنواع تخصيص اتصال متتابعة: - ConnectionAsgmtType.UseMain_ddefault. يستخدم عميل البريد الإلكتروني الاتصال الرئيسي لجميع العمليات من مؤشرات ترابط متعددة إذا لم يتم إنشاء الاتصال الافتراضي ، أو لم يتم تمرير الاتصال كمعامل أسلوب بشكل صريح. الاتصال الرئيسي هو الاتصال الذي يتم إنشاؤه في نفس الوقت مثل عميل البريد الإلكتروني. يمكن للمستخدم إنشاء اتصالات افتراضية لسلاسل الرسائل باستخدام طريقة CreateConnection. إذا تم إنشاء الاتصال الافتراضي لمؤشر الترابط ، فسيتم استخدامه ضمنيًا لجميع طرق عميل البريد الإلكتروني التي يتم استدعاؤها في هذا الموضوع. thread. يمكن للمستخدم أيضًا إنشاء اتصالات غير مرتبطة بخيوط (وليس اتصالات افتراضية) باستخدام طريقة CreateConnection. إذا أراد المستخدم استخدام اتصالات أخرى (ليست رئيسية وليست افتراضية) فعليه أن يمرر هذا الاتصال صراحة كمعامل للطريقة التي يريد استخدامها. يمكن للمستخدم أيضًا إنشاء أي عدد من الاتصالات. يمكن أن يكون الاتصال الافتراضي واحدًا فقط لكل مؤشر ترابط . يرجى ملاحظة أن الاتصالات الافتراضية تعمل بشكل صحيح إذا كان المستخدم يستخدم كائنات سلسلة الرسائل لبرمجة متعددة المهام. إذا كان المستخدم يستخدم ConnectionPool أو يستخدم كائنات المهام لبرمجة متعددة المهام ، فقد يؤدي هذا الوضع إلى سلوك خاطئ للبرنامج . لتجنب هذه المشكلة ، يتعين على المستخدم التخلص يدويًا من الاتصال الافتراضي (إذا كان يستخدمه) في نهاية الكود الذي يتم تنفيذه في الخيط. - ConnectionAsgmtType.UseMain يستخدم عميل البريد الإلكتروني الاتصال الرئيسي لجميع العمليات من سلاسل رسائل متعددة. الاتصال الرئيسي هو الاتصال الذي يتم إنشاؤه في نفس الوقت مثل عميل البريد الإلكتروني. لا يمكن للمستخدم إنشاء اتصالات افتراضية. يمكن للمستخدم إنشاء اتصالات غير مرتبطة بسلاسل (وليس اتصالات افتراضية) باستخدام طريقة CreateConnection. إذا أراد المستخدم استخدام اتصالات أخرى (ليست رئيسية وليست افتراضية) فعليه أن يمرر هذا الاتصال صراحة كمعامل للطريقة التي يريد استخدامها. يمكن للمستخدم أيضًا إنشاء أي عدد من الاتصالات. - ConnectionAsgmtType.UseDefault يستخدم عميل البريد الإلكتروني بشكل ضمني فقط الاتصالات الافتراضية لجميع العمليات من سلاسل رسائل متعددة. لا يتم استخدام الاتصال الرئيسي في هذا الوضع. إذا لم يتم إنشاء الاتصال الافتراضي لبعض سلاسل الرسائل (الاستدعاء الأول لطريقة عميل البريد الإلكتروني) ، يقوم عميل البريد الإلكتروني بإنشاء اتصال افتراضي ضمنيًا لمؤشر الترابط قبل تنفيذ العملية الأولى. لا يمكن للمستخدم إنشاء اتصالات افتراضية لسلاسل الرسائل باستخدام طريقة CreateConnection لأنه يتم إنشاؤها تلقائيًا. عند إنشاء الاتصال الافتراضي لمؤشر الترابط ، يتم استخدامه ضمنيًا لجميع طرق عميل البريد الإلكتروني التي يتم استدعاؤها في هذا الموضوع. قراءة. يمكن للمستخدم أيضًا إنشاء اتصالات غير مرتبطة بسلاسل الرسائل (وليس الاتصالات الافتراضية) باستخدام طريقة CreateConnection. إذا أراد المستخدم استخدام اتصالات أخرى (ليست رئيسية وليست افتراضية) فعليه أن يمرر هذا الاتصال صراحة كمعامل للطريقة التي يريد استخدامها. يمكن للمستخدم أيضًا إنشاء أي عدد من الاتصالات. يمكن أن يكون الاتصال الافتراضي واحدًا فقط لكل مؤشر ترابط . يرجى ملاحظة أن الاتصالات الافتراضية تعمل بشكل صحيح إذا كان المستخدم يستخدم كائنات سلسلة الرسائل لبرمجة متعددة المهام. إذا كان المستخدم يستخدم ConnectionPool أو يستخدم كائنات المهام لبرمجة متعددة المهام ، فقد يؤدي هذا الوضع إلى سلوك خاطئ للبرنامج . لتجنب هذه المشكلة ، يتعين على المستخدم التخلص يدويًا من الاتصال الافتراضي في نهاية الكود الذي يتم تنفيذه في مؤشر الترابط. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | فترة فحص الاتصال بالمللي ثانية . القيمة الافتراضية هي 5 دقائق . |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | الحصول على كمية من الاتصالات أو تعيينها في وضع الاتصال المتعدد |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | يحصل على الحالة الحالية للاتصال. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | يحصل على الاتصال الحالي وفقًا لخيار ConnectionAsgmtMode |
| override [DefaultPort](../../aspose.email.clients.pop3/pop3client/defaultport) { get; } | يحصل على المنفذ الافتراضي لـ client |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | الحصول على أو تعيين قيمة تسمح بتمكين / تعطيل logger |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | الحصول على أو تعيين مهلة الترحيب المستخدمة عند إنشاء اتصال. يرجى ملاحظة أن مهلة الترحيب لا يمكن أن تكون غير محدودة. قد يقوم عملاء البريد الإلكتروني بتنفيذ عمليات طويلة كافية. للحد من وقت العمليات التي يتعين على المستخدمين استخدامها[`Timeout`](../../aspose.email.clients/emailclient/timeout)منشأه. يجب أن تحتوي قيم هذه الخاصية على فترات زمنية طويلة حتى لا تمنع العمليات التي تستغرق وقتًا طويلاً. ولكن في بعض الحالات ، إذا كان EmailClient سيستخدم فقط اتصال خاصية Timeout فقد يستغرق إنشاء اتصال وقت طويل. على سبيل المثال ، قد يستخدم عميل البريد الوضع التلقائي لإنشاء الاتصال. في هذا الوضع ، يمر عميل البريد الإلكتروني بجميع معلمات الاتصال الممكنة حتى يتم إنشاء الاتصال. خوادم SMTP و IMAP و POP3 في حالة الاتصال الصحيح لإنشاء سلسلة ترحيب إلى العميل. قد تستخدم الخوادم بدء اتصال SSL / TLS ضمنيًا أو صريحًا (START TLS). إذا كان وضع الاتصال غير متطابق (على سبيل المثال ، ينتظر الخادم اتصال SSL ضمنيًا لكن العميل يحاول إنشاء اتصال SSL غير آمن أو صريح) ، فلن يرسل الخادم سلسلة ترحيب. في هذه الحالة ، سينتظر المستخدم وقتًا طويلاً حتى تصل المهلة إلى سلسلة ترحيب ، وينتقل العميل إلى خيار الاتصال التالي. لتجنب هذه المشكلة ، تم تقديم الخاصية GreetingTimeout. تسمح لك هذه الخاصية بتعيين مهلة سلسلة الترحيب ، وتقليل وقت إنشاء الاتصال التلقائي. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | الحصول على أو تحديد اسم المضيف . |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | الحصول على أو تعيين اسم ملف السجل |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | الحصول على كلمة المرور أو تعيينها. يتم تحديد قيود كلمة المرور من خلال تنفيذ الخادم ، الذي يتصل به العميل. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | الحصول على المنفذ أو تعيينه . |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | الحصول على أو تعيين الوكيل للعميل |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | وضع الأمان لعميل البريد |
| [SupportedAuthentication](../../aspose.email.clients.pop3/pop3client/supportedauthentication) { get; } | يحصل على تعداد يدعمه أنواع مصادقة الخادم |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | يحدد إصدارات بروتوكولات تشفير SSL / TLS التي سيتم استخدامها. يرجى الانتباه ، يمكنك فقط تعيين تلك الإصدارات من البروتوكول ، التي يدعمها إطار. من الإطار الصافي ، سيتم تجاهلها وتخطيها . قد تؤدي إلى مستوى أمان طبقة النقل الآمنة. في هذه الحالة لن يتم إنشاء استثناء !!! من فضلك ، انظر[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) الوثائق لمزيد من التفاصيل. الرجاء استخدام[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) الطريقة إذا كنت تريد تعيين بروتوكولات التشفير دون أي فحوصات توافق. القيمة الافتراضية هي: Tls &#x7C; TLS11 &#x7C; TLS12 &#x7C; Tls13 (في حالة إذا كان الإصدار الحالي من إطار عمل .net يدعم هذه الإصدارات من TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | الحصول على أو تعيين مهلة عمليات البريد |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | الحصول على أو تعيين TokenProvider الذي يسمح باسترداد رمز الوصول. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | يشير إلى ما إذا كانت المصادقة مستخدمة. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | الحصول على القيمة أو تعيينها والتي تشير إلى ما إذا كان يجب استخدام التاريخ في اسم ملف السجل. |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials) { get; set; } | الحصول على أو تعيين قيمة منطقية تتحكم في إرسال بيانات الاعتماد الافتراضية مع الطلبات. يتم استخدام هذا الخيار مع مصادقة NTLM فقط! |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | الحصول على القيمة أو تعيينها والتي تشير إلى ما إذا كان يتعين على العميل استخدام اتصالات متعددة لعمليات تحميل ثقيلة. يرجى ملاحظة أن استخدام هذا الوضع ليس ضروريًا يجب أن يؤدي إلى زيادة الأداء. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | الحصول على أو تعيين الكائن الذي يشير إلى ما إذا كان وضع خطوط الأنابيب ممكّنًا. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | الحصول على اسم المستخدم أو تعيينه. |

## طُرق

| اسم | وصف |
| --- | --- |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes)() | تنفيذ عمليات الحذف |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_1)(IConnection) | تنفيذ عمليات الحذف |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_2)(int) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync)() | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_5)(CancellationToken) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_1)(IConnection) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_3)(int) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_2)(IConnection, CancellationToken) | تنفيذ عمليات الحذف |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_4)(int, CancellationToken) | تنفيذ عمليات الحذف |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | إنشاء اتصال مستقل جديد للعمليات غير المرتبطة بسلاسل الرسائل (وليس الاتصال الافتراضي) . يشبه استدعاء هذه الطريقة استدعاء CreateConnection (createAsDefaultConnection = false) يرجى الاطلاع على المزيد في الوثائق الخاصة بخاصية EmailClient.ConnectionAsgmtMode. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | إنشاء اتصال جديد (افتراضي أو مستقل) للعمليات . يرجى الاطلاع على المزيد في وثائق خاصية EmailClient.ConnectionAsgmtMode. |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_2)(int) | حذف الرسالة |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_3)(string) | حذف الرسالة |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage)(IConnection, int) | حذف الرسالة |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_1)(IConnection, string) | حذف الرسالة |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_4)(int) | حذف الرسالة |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_6)(string) | حذف الرسالة |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync)(IConnection, int) | حذف الرسالة |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_2)(IConnection, string) | حذف الرسالة |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_5)(int, CancellationToken) | حذف الرسالة |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_7)(string, CancellationToken) | حذف الرسالة |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_1)(IConnection, int, CancellationToken) | حذف الرسالة |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_3)(IConnection, string, CancellationToken) | حذف الرسالة |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages)() | حذف كافة الرسائل |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages_1)(IConnection) | حذف كافة الرسائل |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync)() | حذف كافة الرسائل |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_3)(CancellationToken) | حذف كافة الرسائل |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_1)(IConnection) | حذف كافة الرسائل |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_2)(IConnection, CancellationToken) | حذف كافة الرسائل |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | إنهاء جميع العمليات مع الخادم. |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_2)(int) | يجلب الرسالة |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_3)(string) | يجلب الرسالة |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage)(IConnection, int) | يجلب الرسالة |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_1)(IConnection, string) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_4)(int) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_6)(string) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync)(IConnection, int) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_2)(IConnection, string) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_5)(int, CancellationToken) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_7)(string, CancellationToken) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_1)(IConnection, int, CancellationToken) | يجلب الرسالة |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_3)(IConnection, string, CancellationToken) | يجلب الرسالة |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_2)(IEnumerable&lt;int&gt;) | جلب الرسائل |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_3)(IEnumerable&lt;string&gt;) | جلب الرسائل |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | جلب الرسائل |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_1)(IConnection, IEnumerable&lt;string&gt;) | جلب الرسائل |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_4)(IEnumerable&lt;int&gt;) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_6)(IEnumerable&lt;string&gt;) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_2)(IConnection, IEnumerable&lt;string&gt;) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_5)(IEnumerable&lt;int&gt;, CancellationToken) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_7)(IEnumerable&lt;string&gt;, CancellationToken) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_1)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | جلب الرسائل بشكل غير متزامن |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_3)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | جلب الرسائل بشكل غير متزامن |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo)() | يحصل على معلومات حالة صندوق البريد |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_3)(bool) | يحصل على معلومات حالة صندوق البريد |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_1)(IConnection) | يحصل على معلومات حالة صندوق البريد |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_2)(IConnection, bool) | يحصل على معلومات حالة صندوق البريد |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync)() | يحصل على معلومات حالة صندوق البريد |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_5)(bool) | يحصل على معلومات حالة صندوق البريد |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_7)(CancellationToken) | يحصل على معلومات حالة صندوق البريد |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_1)(IConnection) | يحصل على معلومات حالة صندوق البريد |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_6)(bool, CancellationToken) | يحصل على معلومات حالة صندوق البريد |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_2)(IConnection, bool) | يحصل على معلومات حالة صندوق البريد |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_4)(IConnection, CancellationToken) | يحصل على معلومات حالة صندوق البريد |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_3)(IConnection, bool, CancellationToken) | يحصل على معلومات حالة صندوق البريد |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize)() | يحصل على حجم صندوق البريد |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize_1)(IConnection) | يحصل على حجم صندوق البريد |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync)() | يحصل على حجم صندوق البريد |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_3)(CancellationToken) | يحصل على حجم صندوق البريد |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_1)(IConnection) | يحصل على حجم صندوق البريد |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_2)(IConnection, CancellationToken) | يحصل على حجم صندوق البريد |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount)() | يحصل على عدد الرسائل |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_3)(bool) | يحصل على عدد الرسائل |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_1)(IConnection) | يحصل على عدد الرسائل |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_2)(IConnection, bool) | يحصل على عدد الرسائل |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync)() | يحصل على عدد الرسائل |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_5)(bool) | يحصل على عدد الرسائل |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_7)(CancellationToken) | يحصل على عدد الرسائل |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_1)(IConnection) | يحصل على عدد الرسائل |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_6)(bool, CancellationToken) | يحصل على عدد الرسائل |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_2)(IConnection, bool) | يحصل على عدد الرسائل |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_4)(IConnection, CancellationToken) | يحصل على عدد الرسائل |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_3)(IConnection, bool, CancellationToken) | يحصل على عدد الرسائل |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_2)(int) | يحصل على رؤوس الرسائل |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_3)(string) | يحصل على رؤوس الرسائل |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders)(IConnection, int) | يحصل على رؤوس الرسائل |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_1)(IConnection, string) | يحصل على رؤوس الرسائل |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_4)(int) | يحصل على رؤوس الرسائل |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_6)(string) | يحصل على رؤوس الرسائل |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync)(IConnection, int) | يحصل على رؤوس الرسائل |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_2)(IConnection, string) | يحصل على رؤوس الرسائل |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_5)(int, CancellationToken) | يحصل على رؤوس الرسائل |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_7)(string, CancellationToken) | يحصل على رؤوس الرسائل |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_1)(IConnection, int, CancellationToken) | يحصل على رؤوس الرسائل |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_3)(IConnection, string, CancellationToken) | يحصل على رؤوس الرسائل |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_4)(int) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_6)(string) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo)(IConnection, int) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_2)(IConnection, string) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_5)(int, Pop3ListFields) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_7)(string, Pop3ListFields) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_1)(IConnection, int, Pop3ListFields) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_3)(IConnection, string, Pop3ListFields) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_8)(int) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_12)(string) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync)(IConnection, int) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_4)(IConnection, string) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_11)(int, CancellationToken) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_9)(int, Pop3ListFields) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_15)(string, CancellationToken) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_13)(string, Pop3ListFields) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_3)(IConnection, int, CancellationToken) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_1)(IConnection, int, Pop3ListFields) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_7)(IConnection, string, CancellationToken) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_5)(IConnection, string, Pop3ListFields) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_10)(int, Pop3ListFields, CancellationToken) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_14)(string, Pop3ListFields, CancellationToken) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_2)(IConnection, int, Pop3ListFields, CancellationToken) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_6)(IConnection, string, Pop3ListFields, CancellationToken) | الحصول على المعلومات الخاصة بهذه الرسالة |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_2)(int) | يحصل على حجم الرسالة |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_3)(string) | يحصل على حجم الرسالة |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize)(IConnection, int) | يحصل على حجم الرسالة |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_1)(IConnection, string) | يحصل على حجم الرسالة |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_4)(int) | يحصل على حجم الرسالة |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_6)(string) | يحصل على حجم الرسالة |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync)(IConnection, int) | يحصل على حجم الرسالة |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_2)(IConnection, string) | يحصل على حجم الرسالة |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_5)(int, CancellationToken) | يحصل على حجم الرسالة |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_7)(string, CancellationToken) | يحصل على حجم الرسالة |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_1)(IConnection, int, CancellationToken) | يحصل على حجم الرسالة |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_3)(IConnection, string, CancellationToken) | يحصل على حجم الرسالة |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid_1)(int) | يحصل على الرسالة الفريدة id |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid)(IConnection, int) | يحصل على الرسالة الفريدة id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_2)(int) | يحصل على الرسالة الفريدة id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync)(IConnection, int) | يحصل على الرسالة الفريدة id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_3)(int, CancellationToken) | يحصل على الرسالة الفريدة id |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_1)(IConnection, int, CancellationToken) | يحصل على الرسالة الفريدة id |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages)() | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_11)(bool) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_1)(IConnection) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_12)(IEnumerable&lt;int&gt;) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_13)(IEnumerable&lt;string&gt;) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_10)(MailQuery) | يسرد الرسائل . |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_8)(Pop3ListFields) | يسرد الرسائل . |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_5)(IConnection, bool) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_6)(IConnection, IEnumerable&lt;int&gt;) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_7)(IConnection, IEnumerable&lt;string&gt;) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_4)(IConnection, MailQuery) | يسرد الرسائل . |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_2)(IConnection, Pop3ListFields) | يسرد الرسائل . |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_9)(Pop3ListFields, bool, MailQuery) | يسرد الرسائل . |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_3)(IConnection, Pop3ListFields, bool, MailQuery) | يسرد الرسائل . |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync)() | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_17)(bool) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_19)(CancellationToken) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_1)(IConnection) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_15)(MailQuery) | يسرد الرسائل . |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_11)(Pop3ListFields) | يسرد الرسائل . |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_18)(bool, CancellationToken) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_8)(IConnection, bool) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_10)(IConnection, CancellationToken) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_6)(IConnection, MailQuery) | يسرد الرسائل . |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_2)(IConnection, Pop3ListFields) | يسرد الرسائل . |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_16)(MailQuery, CancellationToken) | يسرد الرسائل . |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_14)(Pop3ListFields, CancellationToken) | يسرد الرسائل . |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_9)(IConnection, bool, CancellationToken) | يسرد الرسائل. يحصل على معلومات لرسالة البحث |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_7)(IConnection, MailQuery, CancellationToken) | يسرد الرسائل . |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_5)(IConnection, Pop3ListFields, CancellationToken) | يسرد الرسائل . |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_12)(Pop3ListFields, bool, MailQuery) | يسرد الرسائل . |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_3)(IConnection, Pop3ListFields, bool, MailQuery) | يسرد الرسائل . |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_13)(Pop3ListFields, bool, MailQuery, CancellationToken) | يسرد الرسائل . |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_4)(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) | يسرد الرسائل . |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_3)(IEnumerable&lt;int&gt;) | قائمة تحميلات Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_2)(IEnumerable&lt;Pop3MessageInfo&gt;) | قائمة تحميلات Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_1)(IConnection, IEnumerable&lt;int&gt;) | قائمة تحميلات Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | قائمة تحميلات Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_7)(IEnumerable&lt;int&gt;) | قائمة تحميلات Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_5)(IEnumerable&lt;Pop3MessageInfo&gt;) | قائمة تحميلات Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_4)(Pop3LoadMessageInfoList) | قائمة تحميلات Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_2)(IConnection, IEnumerable&lt;int&gt;) | قائمة تحميلات Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | قائمة تحميلات Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_8)(IEnumerable&lt;int&gt;, CancellationToken) | قائمة تحميلات Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_6)(IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | قائمة تحميلات Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_3)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | قائمة تحميلات Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_1)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | قائمة تحميلات Pop3MessageInfo |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop)() | "بدون عملية" command |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop_1)(IConnection) | "بدون عملية" command |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync)() | "بدون عملية" command |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_3)(CancellationToken) | "بدون عملية" command |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_1)(IConnection) | "بدون عملية" command |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_2)(IConnection, CancellationToken) | "بدون عملية" command |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | يعيد تعيين إعدادات التسجيل إلى الإعدادات الافتراضية. |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_4)(int, Stream) | يجلب الرسالة وحفظها على هيئة تدفق |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_5)(int, string) | يجلب الرسالة وحفظها في ملف |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_6)(string, Stream) | يجلب الرسالة وحفظها على هيئة تدفق |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_7)(string, string) | يجلب الرسالة وحفظها في ملف |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage)(IConnection, int, Stream) | يجلب الرسالة وحفظها على هيئة تدفق |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_1)(IConnection, int, string) | يجلب الرسالة وحفظها في ملف |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_2)(IConnection, string, Stream) | يجلب الرسالة وحفظها على هيئة تدفق |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_3)(IConnection, string, string) | يجلب الرسالة وحفظها في ملف |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_8)(int, Stream) | يجلب الرسالة وحفظها على هيئة تدفق |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_10)(int, string) | يجلب الرسالة وحفظها في ملف |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_12)(string, Stream) | يجلب الرسالة وحفظها على هيئة تدفق |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_14)(string, string) | يجلب الرسالة وحفظها في ملف |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync)(IConnection, int, Stream) | يجلب الرسالة وحفظها على هيئة تدفق |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_2)(IConnection, int, string) | يجلب الرسالة وحفظها في ملف |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_4)(IConnection, string, Stream) | يجلب الرسالة وحفظها على هيئة تدفق |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_6)(IConnection, string, string) | يجلب الرسالة وحفظها في ملف |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_9)(int, Stream, CancellationToken) | يجلب الرسالة وحفظها على هيئة تدفق |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_11)(int, string, CancellationToken) | يجلب الرسالة وحفظها في ملف |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_13)(string, Stream, CancellationToken) | يجلب الرسالة وحفظها على هيئة تدفق |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_15)(string, string, CancellationToken) | يجلب الرسالة وحفظها في ملف |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_1)(IConnection, int, Stream, CancellationToken) | يجلب الرسالة وحفظها على هيئة تدفق |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_3)(IConnection, int, string, CancellationToken) | يجلب الرسالة وحفظها في ملف |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_5)(IConnection, string, Stream, CancellationToken) | يجلب الرسالة وحفظها على هيئة تدفق |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_7)(IConnection, string, string, CancellationToken) | يجلب الرسالة وحفظها في ملف |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | يحدد إصدارات بروتوكولات تشفير SSL / TLS التي سيتم استخدامها. هذه الطريقة ليست آمنة وتقوم بتعيين بروتوكولات التشفير دون أي فحوصات توافق.[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) لتعيين البروتوكولات بأمان فقط التي يدعمها إطار عمل. net . يرجى ملاحظة ، إذا كان إطار عمل .net الحالي الخاص بك لا يدعم هذا المستوى من الأمان ، فسيتم طرح استثناء عند محاولة إنشاء اتصال بالخادم. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages)() | إلغاء حذف الرسائل. إذا تم وضع علامة على أية رسائل على أنها محذوفة بواسطة خادم POP3 ، فلن يتم تمييزها. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages_1)(IConnection) | إلغاء حذف الرسائل. إذا تم وضع علامة على أية رسائل على أنها محذوفة بواسطة خادم POP3 ، فلن يتم تمييزها. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync)() | إلغاء حذف الرسائل. إذا تم وضع علامة على أية رسائل على أنها محذوفة بواسطة خادم POP3 ، فلن يتم تمييزها. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_3)(CancellationToken) | إلغاء حذف الرسائل. إذا تم وضع علامة على أية رسائل على أنها محذوفة بواسطة خادم POP3 ، فلن يتم تمييزها. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_1)(IConnection) | إلغاء حذف الرسائل. إذا تم وضع علامة على أية رسائل على أنها محذوفة بواسطة خادم POP3 ، فلن يتم تمييزها. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_2)(IConnection, CancellationToken) | إلغاء حذف الرسائل. إذا تم وضع علامة على أية رسائل على أنها محذوفة بواسطة خادم POP3 ، فلن يتم تمييزها. |
| override [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials)() | تنفيذ التحقق من صحة بيانات الاعتماد |
| [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials_1)(IConnection) | تنفيذ التحقق من صحة بيانات الاعتماد |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync)() | تنفيذ التحقق من صحة بيانات الاعتماد |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | تنفيذ التحقق من صحة بيانات الاعتماد |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | تنفيذ التحقق من صحة بيانات الاعتماد |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | تنفيذ التحقق من صحة بيانات الاعتماد |
| static [CreateAsync](../../aspose.email.clients.pop3/pop3client/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | لإنشاء مثيل جديد لملف[`Pop3Client`](../pop3client) فئة |

### أنظر أيضا

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncPop3Client](../iasyncpop3client)
* مساحة الاسم [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
