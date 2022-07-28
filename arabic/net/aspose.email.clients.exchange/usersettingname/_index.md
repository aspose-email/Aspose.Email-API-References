---
title: UserSettingName
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: إعدادات المستخدم التي يمكن طلبها باستخدام GetUserSettings.
type: docs
weight: 3600
url: /ar/net/aspose.email.clients.exchange/usersettingname/
---
## UserSettingName enumeration

إعدادات المستخدم التي يمكن طلبها باستخدام GetUserSettings.

```csharp
public enum UserSettingName
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| UserDisplayName | `0` | اسم العرض للمستخدم . |
| UserDN | `1` | الاسم المميز القديم للمستخدم . |
| UserDeploymentId | `2` | معرف النشر الخاص بالمستخدم . |
| InternalMailboxServer | `3` | اسم المجال المؤهل بالكامل لخادم صندوق البريد. |
| InternalRpcClientServer | `4` | اسم المجال المؤهل بالكامل لخادم عميل RPC. |
| InternalMailboxServerDN | `5` | الاسم المميز القديم لخادم صندوق البريد. |
| InternalEcpUrl | `6` | عنوان URL الداخلي للوحة تحكم Exchange . |
| InternalEcpVoicemailUrl | `7` | عنوان URL الداخلي للوحة تحكم Exchange لتخصيص البريد الصوتي. |
| InternalEcpEmailSubscriptionsUrl | `8` | عنوان URL الداخلي للوحة تحكم Exchange لاشتراكات البريد الإلكتروني . |
| InternalEcpTextMessagingUrl | `9` | عنوان URL الداخلي الخاص بلوحة تحكم Exchange للرسائل النصية. |
| InternalEcpDeliveryReportUrl | `10` | عنوان URL الداخلي للوحة تحكم Exchange لتقارير التسليم. |
| InternalEcpRetentionPolicyTagsUrl | `11` | عنوان URL الداخلي للوحة تحكم Exchange لعلامات سياسة الاحتفاظ. |
| InternalEcpPublishingUrl | `12` | عنوان URL الداخلي للوحة تحكم Exchange للنشر. |
| InternalEcpPhotoUrl | `13` | عنوان URL الداخلي الخاص بلوحة تحكم Exchange للصور. |
| InternalEcpConnectUrl | `14` | عنوان URL الداخلي للوحة تحكم Exchange لاشتراكات People Connect. |
| InternalEcpTeamMailboxUrl | `15` | عنوان URL الداخلي الخاص بلوحة تحكم Exchange لصندوق بريد الفريق. |
| InternalEcpTeamMailboxCreatingUrl | `16` | عنوان URL الداخلي الخاص بلوحة تحكم Exchange لإنشاء صندوق بريد الفريق. |
| InternalEcpTeamMailboxEditingUrl | `17` | عنوان URL الداخلي الخاص بلوحة تحكم Exchange لتحرير صندوق بريد الفريق. |
| InternalEcpTeamMailboxHidingUrl | `18` | عنوان URL الداخلي للوحة تحكم Exchange لإخفاء صندوق بريد الفريق. |
| InternalEcpExtensionInstallationUrl | `19` | عنوان URL الداخلي الخاص بلوحة تحكم Exchange لتثبيت الملحق. |
| InternalEwsUrl | `20` | عنوان URL الداخلي لخدمات Exchange عبر الويب . |
| InternalEmwsUrl | `21` | عنوان URL الداخلي لخدمات ويب إدارة Exchange . |
| InternalOABUrl | `22` | عنوان URL الداخلي الخاص بدفتر العناوين غير المتصل . |
| InternalPhotosUrl | `23` | عنوان URL الداخلي لخدمة الصور . |
| InternalUMUrl | `24` | عنوان URL الداخلي لخدمات المراسلة الموحدة. |
| InternalWebClientUrls | `25` | عناوين URL الداخلية لعميل ويب Exchange . |
| MailboxDN | `26` | الاسم المميز لقاعدة بيانات علبة البريد الخاصة بصندوق بريد المستخدم. |
| PublicFolderServer | `27` | اسم خادم المجلدات العامة . |
| ActiveDirectoryServer | `28` | اسم خادم Active Directory . |
| ExternalMailboxServer | `29` | اسم RPC عبر خادم HTTP . |
| ExternalMailboxServerRequiresSSL | `30` | يشير إلى ما إذا كان RPC عبر خادم HTTP يتطلب SSL. |
| ExternalMailboxServerAuthenticationMethods | `31` | طرق المصادقة التي يدعمها RPC عبر خادم HTTP. |
| EcpVoicemailUrlFragment | `32` | جزء URL الخاص بلوحة تحكم Exchange لتخصيص البريد الصوتي. |
| EcpEmailSubscriptionsUrlFragment | `33` | جزء عنوان URL الخاص بلوحة تحكم Exchange لاشتراكات البريد الإلكتروني. |
| EcpTextMessagingUrlFragment | `34` | جزء URL الخاص بلوحة تحكم Exchange للرسائل النصية. |
| EcpDeliveryReportUrlFragment | `35` | جزء URL الخاص بلوحة تحكم Exchange لتقارير التسليم. |
| EcpRetentionPolicyTagsUrlFragment | `36` | جزء عنوان URL الخاص بلوحة تحكم Exchange لعلامات سياسة الاحتفاظ. |
| EcpPublishingUrlFragment | `37` | جزء URL الخاص بلوحة تحكم Exchange للنشر. |
| EcpPhotoUrlFragment | `38` | جزء URL الخاص بلوحة تحكم Exchange للصور. |
| EcpConnectUrlFragment | `39` | جزء URL الخاص بلوحة تحكم Exchange لـ People Connect. |
| EcpTeamMailboxUrlFragment | `40` | جزء URL الخاص بلوحة تحكم Exchange لصندوق بريد الفريق. |
| EcpTeamMailboxCreatingUrlFragment | `41` | جزء URL الخاص بلوحة تحكم Exchange لإنشاء صندوق بريد الفريق. |
| EcpTeamMailboxEditingUrlFragment | `42` | جزء URL الخاص بلوحة تحكم Exchange لتحرير صندوق بريد الفريق. |
| EcpExtensionInstallationUrlFragment | `43` | جزء URL الخاص بلوحة تحكم Exchange لتثبيت الملحق. |
| ExternalEcpUrl | `44` | عنوان URL الخارجي الخاص بلوحة تحكم Exchange. |
| ExternalEcpVoicemailUrl | `45` | عنوان URL الخارجي الخاص بلوحة تحكم Exchange لتخصيص البريد الصوتي. |
| ExternalEcpEmailSubscriptionsUrl | `46` | عنوان URL الخارجي الخاص بلوحة تحكم Exchange لاشتراكات البريد الإلكتروني . |
| ExternalEcpTextMessagingUrl | `47` | عنوان URL الخارجي الخاص بلوحة تحكم Exchange للرسائل النصية. |
| ExternalEcpDeliveryReportUrl | `48` | عنوان URL الخارجي الخاص بلوحة تحكم Exchange لتقارير التسليم. |
| ExternalEcpRetentionPolicyTagsUrl | `49` | عنوان URL الخارجي للوحة تحكم Exchange لعلامات سياسة الاحتفاظ. |
| ExternalEcpPublishingUrl | `50` | عنوان URL الخارجي الخاص بلوحة تحكم Exchange للنشر. |
| ExternalEcpPhotoUrl | `51` | عنوان URL الخارجي الخاص بلوحة تحكم Exchange للصور. |
| ExternalEcpConnectUrl | `52` | عنوان URL الخارجي الخاص بلوحة تحكم Exchange لاشتراكات People Connect. |
| ExternalEcpTeamMailboxUrl | `53` | عنوان URL الخارجي الخاص بلوحة تحكم Exchange لصندوق بريد الفريق. |
| ExternalEcpTeamMailboxCreatingUrl | `54` | عنوان URL الخارجي الخاص بلوحة تحكم Exchange لإنشاء صندوق بريد الفريق. |
| ExternalEcpTeamMailboxEditingUrl | `55` | عنوان URL الخارجي الخاص بلوحة تحكم Exchange لتحرير صندوق بريد الفريق. |
| ExternalEcpTeamMailboxHidingUrl | `56` | عنوان URL الخارجي الخاص بلوحة تحكم Exchange لإخفاء صندوق بريد الفريق. |
| ExternalEcpExtensionInstallationUrl | `57` | عنوان URL الخارجي الخاص بلوحة تحكم Exchange لتثبيت الملحق. |
| ExternalEwsUrl | `58` | عنوان URL الخارجي لخدمات Exchange على الويب . |
| ExternalEmwsUrl | `59` | عنوان URL الخارجي لخدمات ويب إدارة Exchange . |
| ExternalOABUrl | `60` | عنوان URL الخارجي لدفتر العناوين غير المتصل. |
| ExternalPhotosUrl | `61` | عنوان URL الخارجي لخدمة الصور. |
| ExternalUMUrl | `62` | عنوان URL الخارجي لخدمات المراسلة الموحدة. |
| ExternalWebClientUrls | `63` | عناوين URL الخارجية لعميل ويب Exchange . |
| CrossOrganizationSharingEnabled | `64` | يشير إلى تمكين المشاركة عبر المؤسسات . |
| AlternateMailboxes | `65` | مجموعة من علب البريد البديلة . |
| CasVersion | `66` | إصدار Client Access Server الذي يخدم الطلب (مثل 14.XX.YYY.ZZZ) |
| EwsSupportedSchemas | `67` | قائمة مفصولة بفواصل لإصدارات المخطط التي تدعمها خدمات Exchange عبر الويب. ستكون قيم إصدار المخطط هي نفسها قيم تعداد ExchangeServerVersion. |
| InternalPop3Connections | `68` | قائمة إعدادات الاتصال الداخلية لبروتوكول pop |
| ExternalPop3Connections | `69` | قائمة إعدادات الاتصال الخارجي لبروتوكول pop |
| InternalImap4Connections | `70` | قائمة إعدادات الاتصال الداخلية لبروتوكول imap4 |
| ExternalImap4Connections | `71` | قائمة إعدادات الاتصال الخارجي لبروتوكول imap4 |
| InternalSmtpConnections | `72` | قائمة إعدادات الاتصال الداخلية لبروتوكول smtp |
| ExternalSmtpConnections | `73` | قائمة إعدادات الاتصال الخارجي لبروتوكول smtp |
| InternalServerExclusiveConnect | `74` | في حالة التعيين على "إيقاف التشغيل" ، فلا يجب على العملاء الاتصال عبر هذا البروتوكول. محتويات البروتوكول هي لأغراض إعلامية فقط. |
| ExternalEwsVersion | `75` | يشير إصدار خادم Exchange Web Services ExternalEwsUrl إلى. |
| MobileMailboxPolicy | `76` | إعدادات نهج صندوق بريد الجوال. |
| DocumentSharingLocations | `77` | مواقع مشاركة المستندات وإعداداتها . |
| UserMSOnline | `78` | ما إذا كان حساب المستخدم هو حساب MSOnline . |
| InternalMailboxServerAuthenticationMethods | `79` | طرق المصادقة التي يدعمها خادم عميل RPC. |
| MailboxVersion | `80` | إصدار الخادم الذي يستضيف صندوق بريد المستخدم. |
| SPMySiteHostURL | `81` | عنوان URL لمضيف Sharepoint MySite. |
| SiteMailboxCreationURL | `82` | URL لإنشاء صندوق بريد الموقع في SharePoint. يتم استخدامه بواسطة Outlook لإنشاء صندوق بريد الموقع من SharePoint مباشرةً . |
| InternalRpcHttpServer | `83` | FQDN للخادم المستخدم لاتصال RPC / HTTP الداخلي . |
| InternalRpcHttpConnectivityRequiresSsl | `84` | يشير إلى ما إذا كان SSL مطلوبًا لاتصال RPC / HTTP الداخلي. |
| InternalRpcHttpAuthenticationMethod | `85` | طريقة المصادقة المستخدمة لاتصال RPC / HTTP الداخلي. |
| ExternalServerExclusiveConnect | `86` | في حالة التعيين على "تشغيل" ، يجب على العملاء الاتصال عبر هذا البروتوكول فقط. |
| ExchangeRpcUrl | `87` | في حالة الضبط ، يمكن للعملاء الاتصال بالخادم عبر XTC |
| ShowGalAsDefaultView | `88` | في حالة التعيين على "خطأ" ، يجب ألا يعرض العملاء قائمة العناوين العمومية افتراضيًا ، ولكن يجب أن يعرضوا قائمة جهات الاتصال . |
| AutoDiscoverSMTPAddress | `89` | اكتشاف تلقائي لعنوان SMTP الأساسي للمستخدم. |
| InteropExternalEwsUrl | `90` | عنوان URL الخارجي "interop" لخدمات ويب Exchange . يعني interop عنوان URL لخادم E14 (أو الأحدث) الذي يمكنه خدمة علب البريد التي تتم استضافتها في خادم المستوى الأدنى (E2K3 والإصدارات الأقدم) . |
| InteropExternalEwsVersion | `91` | إصدار الخادم InteropExternalEwsUrl يشير إلى. |
| PublicFolderInformation | `92` | معلومات المجلد العام (التسلسل الهرمي) |
| RedirectUrl | `93` | إصدار URL المناسب لخدمة الاكتشاف التلقائي الذي يجب أن يجيب على هذا الاستعلام. |
| EwsPartnerUrl | `94` | عنوان URL لخدمات Exchange عبر الويب لشركاء Office365 . |
| CertPrincipalName | `95` | اسم شهادة SSL |
| GroupingInformation | `96` | تلميح التجميع لعملاء معينين. |
| InternalOutlookServiceUrl | `98` | عنوان URL للخدمة الداخلية لبرنامج Outlook |
| ExternalOutlookServiceUrl | `99` | عنوان URL لخدمة Outlook الخارجية |

### ملاحظات

أضف قيمًا جديدة إلى النهاية وابقَ متزامنًا مع Microsoft.Exchange.Autodiscover.ConfigurationSettings.UserConfigurationSettingName.

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
