---
title: EmailClient
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل العميل الذي يقوم بإنشاء اتصال بالخادم باستخدام بيانات اعتماد المضيف.
type: docs
weight: 3020
url: /ar/net/aspose.email.clients/emailclient/
---
## EmailClient class

يمثل العميل الذي يقوم بإنشاء اتصال بالخادم باستخدام بيانات اعتماد المضيف.

```csharp
public abstract class EmailClient : IDisposable
```

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | الحصول على رمز الوصول أو تعيينه. |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | يحتوي على مجموعة من شهادات العملاء |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | الحصول على أو تعيين القيمة التي تحدد وضع تخصيص الاتصال في بيئة مؤشرات الترابط المتعددة هناك أنواع اتصال متتابعة: - الاتصال الرئيسي هو الاتصال الذي تم إنشاؤه والتخلص منه مع عميل البريد. لا يمكن إنشاؤه أو التخلص منه يدويًا. - الاتصال الافتراضي هو الاتصال الافتراضي لبعض مؤشرات الترابط . إذا كان الاتصال الافتراضي موجودًا وكان ConnectionAsgmtMode يسمح بذلك ، فسيتم استخدام هذا الاتصال ضمنيًا لجميع طرق عميل البريد الإلكتروني المنفذة في هذا الموضوع. يمكن إنشاؤه يدويًا أو تلقائيًا. يعتمد ذلك على خاصية EmailClient.ConnectionAsgmtMode. يمكن إنشاء هذه الاتصالات يدويًا باستخدام طريقة EmailClient.CreateConnection (createAsDefaultConnection = true) . إذا لم يتم استخدام الاتصال الافتراضي (يعتمد على وضع تخصيص الاتصال) ، يتم استخدام الاتصال الرئيسي بشكل ضمني بدلاً منه. - الاتصالات المستقلة هي اتصالات غير مرتبطة بخيوط. يمكن إنشاؤها يدويًا ويجب استخدامها بشكل صريح كمعامل أسلوب. يمكن إنشاء هذه الاتصالات يدويًا باستخدام طريقة EmailClient.CreateConnection () أو طريقة EmailClient.CreateConnection (createAsDefaultConnection = false). هناك أنواع تخصيص اتصال متتابعة: - ConnectionAsgmtType.UseMain_ddefault. يستخدم عميل البريد الإلكتروني الاتصال الرئيسي لجميع العمليات من مؤشرات ترابط متعددة إذا لم يتم إنشاء الاتصال الافتراضي ، أو لم يتم تمرير الاتصال كمعامل أسلوب بشكل صريح. الاتصال الرئيسي هو الاتصال الذي يتم إنشاؤه في نفس الوقت مثل عميل البريد الإلكتروني. يمكن للمستخدم إنشاء اتصالات افتراضية لسلاسل الرسائل باستخدام طريقة CreateConnection. إذا تم إنشاء الاتصال الافتراضي لمؤشر الترابط ، فسيتم استخدامه ضمنيًا لجميع طرق عميل البريد الإلكتروني التي يتم استدعاؤها في هذا الموضوع. thread. يمكن للمستخدم أيضًا إنشاء اتصالات غير مرتبطة بخيوط (وليس اتصالات افتراضية) باستخدام طريقة CreateConnection. إذا أراد المستخدم استخدام اتصالات أخرى (ليست رئيسية وليست افتراضية) فعليه أن يمرر هذا الاتصال صراحة كمعامل للطريقة التي يريد استخدامها. يمكن للمستخدم أيضًا إنشاء أي عدد من الاتصالات. يمكن أن يكون الاتصال الافتراضي واحدًا فقط لكل مؤشر ترابط . يرجى ملاحظة أن الاتصالات الافتراضية تعمل بشكل صحيح إذا كان المستخدم يستخدم كائنات سلسلة الرسائل لبرمجة متعددة المهام. إذا كان المستخدم يستخدم ConnectionPool أو يستخدم كائنات المهام لبرمجة متعددة المهام ، فقد يؤدي هذا الوضع إلى سلوك خاطئ للبرنامج . لتجنب هذه المشكلة ، يتعين على المستخدم التخلص يدويًا من الاتصال الافتراضي (إذا كان يستخدمه) في نهاية الكود الذي يتم تنفيذه في الخيط. - ConnectionAsgmtType.UseMain يستخدم عميل البريد الإلكتروني الاتصال الرئيسي لجميع العمليات من سلاسل رسائل متعددة. الاتصال الرئيسي هو الاتصال الذي يتم إنشاؤه في نفس الوقت مثل عميل البريد الإلكتروني. لا يمكن للمستخدم إنشاء اتصالات افتراضية. يمكن للمستخدم إنشاء اتصالات غير مرتبطة بسلاسل (وليس اتصالات افتراضية) باستخدام طريقة CreateConnection. إذا أراد المستخدم استخدام اتصالات أخرى (ليست رئيسية وليست افتراضية) فعليه أن يمرر هذا الاتصال صراحة كمعامل للطريقة التي يريد استخدامها. يمكن للمستخدم أيضًا إنشاء أي عدد من الاتصالات. - ConnectionAsgmtType.UseDefault يستخدم عميل البريد الإلكتروني بشكل ضمني فقط الاتصالات الافتراضية لجميع العمليات من سلاسل رسائل متعددة. لا يتم استخدام الاتصال الرئيسي في هذا الوضع. إذا لم يتم إنشاء الاتصال الافتراضي لبعض سلاسل الرسائل (الاستدعاء الأول لطريقة عميل البريد الإلكتروني) ، يقوم عميل البريد الإلكتروني بإنشاء اتصال افتراضي ضمنيًا لمؤشر الترابط قبل تنفيذ العملية الأولى. لا يمكن للمستخدم إنشاء اتصالات افتراضية لسلاسل الرسائل باستخدام طريقة CreateConnection لأنه يتم إنشاؤها تلقائيًا. عند إنشاء الاتصال الافتراضي لمؤشر الترابط ، يتم استخدامه ضمنيًا لجميع طرق عميل البريد الإلكتروني التي يتم استدعاؤها في هذا الموضوع. قراءة. يمكن للمستخدم أيضًا إنشاء اتصالات غير مرتبطة بسلاسل الرسائل (وليس الاتصالات الافتراضية) باستخدام طريقة CreateConnection. إذا أراد المستخدم استخدام اتصالات أخرى (ليست رئيسية وليست افتراضية) فعليه أن يمرر هذا الاتصال صراحة كمعامل للطريقة التي يريد استخدامها. يمكن للمستخدم أيضًا إنشاء أي عدد من الاتصالات. يمكن أن يكون الاتصال الافتراضي واحدًا فقط لكل مؤشر ترابط . يرجى ملاحظة أن الاتصالات الافتراضية تعمل بشكل صحيح إذا كان المستخدم يستخدم كائنات سلسلة الرسائل لبرمجة متعددة المهام. إذا كان المستخدم يستخدم ConnectionPool أو يستخدم كائنات المهام لبرمجة متعددة المهام ، فقد يؤدي هذا الوضع إلى سلوك خاطئ للبرنامج . لتجنب هذه المشكلة ، يتعين على المستخدم التخلص يدويًا من الاتصال الافتراضي في نهاية الكود الذي يتم تنفيذه في مؤشر الترابط. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | فترة فحص الاتصال بالمللي ثانية . القيمة الافتراضية هي 5 دقائق . |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | الحصول على كمية من الاتصالات أو تعيينها في وضع الاتصال المتعدد |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | يحصل على الحالة الحالية للاتصال. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | يحصل على الاتصال الحالي وفقًا لخيار ConnectionAsgmtMode |
| virtual [DefaultPort](../../aspose.email.clients/emailclient/defaultport) { get; } | يحصل على المنفذ الافتراضي لـ client |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | الحصول على أو تعيين قيمة تسمح بتمكين / تعطيل logger |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | الحصول على أو تعيين مهلة الترحيب المستخدمة عند إنشاء اتصال. يرجى ملاحظة أن مهلة الترحيب لا يمكن أن تكون غير محدودة. قد يقوم عملاء البريد الإلكتروني بتنفيذ عمليات طويلة كافية. للحد من وقت العمليات التي يتعين على المستخدمين استخدامها[`Timeout`](./timeout)منشأه. يجب أن تحتوي قيم هذه الخاصية على فترات زمنية طويلة حتى لا تمنع العمليات التي تستغرق وقتًا طويلاً. ولكن في بعض الحالات ، إذا كان EmailClient سيستخدم فقط اتصال خاصية Timeout فقد يستغرق إنشاء اتصال وقت طويل. على سبيل المثال ، قد يستخدم عميل البريد الوضع التلقائي لإنشاء الاتصال. في هذا الوضع ، يمر عميل البريد الإلكتروني بجميع معلمات الاتصال الممكنة حتى يتم إنشاء الاتصال. خوادم SMTP و IMAP و POP3 في حالة الاتصال الصحيح لإنشاء سلسلة ترحيب إلى العميل. قد تستخدم الخوادم بدء اتصال SSL / TLS ضمنيًا أو صريحًا (START TLS). إذا كان وضع الاتصال غير متطابق (على سبيل المثال ، ينتظر الخادم اتصال SSL ضمنيًا لكن العميل يحاول إنشاء اتصال SSL غير آمن أو صريح) ، فلن يرسل الخادم سلسلة ترحيب. في هذه الحالة ، سينتظر المستخدم وقتًا طويلاً حتى تصل المهلة إلى سلسلة ترحيب ، وينتقل العميل إلى خيار الاتصال التالي. لتجنب هذه المشكلة ، تم تقديم الخاصية GreetingTimeout. تسمح لك هذه الخاصية بتعيين مهلة سلسلة الترحيب ، وتقليل وقت إنشاء الاتصال التلقائي. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | الحصول على أو تحديد اسم المضيف . |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | الحصول على أو تعيين اسم ملف السجل |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | الحصول على كلمة المرور أو تعيينها. يتم تحديد قيود كلمة المرور من خلال تنفيذ الخادم ، الذي يتصل به العميل. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | الحصول على المنفذ أو تعيينه . |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | الحصول على أو تعيين الوكيل للعميل |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | وضع الأمان لعميل البريد |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | يحدد إصدارات بروتوكولات تشفير SSL / TLS التي سيتم استخدامها. يرجى الانتباه ، يمكنك فقط تعيين تلك الإصدارات من البروتوكول ، التي يدعمها إطار. من الإطار الصافي ، سيتم تجاهلها وتخطيها . قد تؤدي إلى مستوى أمان طبقة النقل الآمنة. في هذه الحالة لن يتم إنشاء استثناء !!! من فضلك ، انظر[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) الوثائق لمزيد من التفاصيل. الرجاء استخدام[`SetSupportedEncryptionUnsafe`](./setsupportedencryptionunsafe) الطريقة إذا كنت تريد تعيين بروتوكولات التشفير دون أي فحوصات توافق. القيمة الافتراضية هي: Tls &#x7C; TLS11 &#x7C; TLS12 &#x7C; Tls13 (في حالة إذا كان الإصدار الحالي من إطار عمل .net يدعم هذه الإصدارات من TLS) |
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
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection#createconnection)() | إنشاء اتصال مستقل جديد للعمليات غير المرتبطة بسلاسل الرسائل (وليس الاتصال الافتراضي) . يشبه استدعاء هذه الطريقة استدعاء CreateConnection (createAsDefaultConnection = false) يرجى الاطلاع على المزيد في الوثائق الخاصة بخاصية EmailClient.ConnectionAsgmtMode. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection#createconnection_1)(bool) | إنشاء اتصال جديد (افتراضي أو مستقل) للعمليات . يرجى الاطلاع على المزيد في وثائق خاصية EmailClient.ConnectionAsgmtMode. |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | إنهاء جميع العمليات مع الخادم. |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| abstract [Noop](../../aspose.email.clients/emailclient/noop#noop)() | "بدون عملية" command |
| abstract [Noop](../../aspose.email.clients/emailclient/noop#noop_1)(IConnection) | "بدون عملية" command |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | يعيد تعيين إعدادات التسجيل إلى الإعدادات الافتراضية. |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | يحدد إصدارات بروتوكولات تشفير SSL / TLS التي سيتم استخدامها. هذه الطريقة ليست آمنة وتقوم بتعيين بروتوكولات التشفير دون أي فحوصات توافق.[`SupportedEncryption`](./supportedencryption) لتعيين البروتوكولات بأمان فقط التي يدعمها إطار عمل. net . يرجى ملاحظة ، إذا كان إطار عمل .net الحالي الخاص بك لا يدعم هذا المستوى من الأمان ، فسيتم طرح استثناء عند محاولة إنشاء اتصال بالخادم. |
| abstract [ValidateCredentials](../../aspose.email.clients/emailclient/validatecredentials)() | للتحقق مما إذا كانت بيانات الاعتماد صالحة |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients](../../aspose.email.clients)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
