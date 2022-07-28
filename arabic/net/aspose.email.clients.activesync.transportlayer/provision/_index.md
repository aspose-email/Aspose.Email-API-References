---
title: Provision
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: توفير مساحة اسم بروتوكول ActiveSync
type: docs
weight: 1710
url: /ar/net/aspose.email.clients.activesync.transportlayer/provision/
---
## Provision enumeration

توفير مساحة اسم بروتوكول ActiveSync

```csharp
public enum Provision
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| Provision | `5` | إمكانيات وأذونات الجهاز . |
| Policies | `6` | مجموعة من سياسات الأمان . |
| Policy | `7` | سياسة أمان . |
| PolicyType | `8` | يحدد التنسيق الذي سيتم توفير إعدادات السياسة به. |
| PolicyKey | `9` | مستخدمة من قبل الخادم لتمييز حالة إعدادات السياسة على العميل. |
| Data | `10` | إعدادات السياسة . |
| Status | `11` | يشير إلى نجاح أو فشل أجزاء معينة من الأمر. |
| RemoteWipe | `12` | يحدد إما توجيه مسح عن بعد من الخادم أو تأكيد العميل لتوجيه المسح عن بُعد. |
| EASProvisionDoc | `13` | مجموعة إعدادات الأمان لتوفير الجهاز. |
| DevicePasswordEnabled | `14` | يشير إلى ما إذا كان جهاز العميل يتطلب كلمة مرور . |
| AlphanumericDevicePasswordRequired | `15` | يشير إلى ما إذا كان جهاز العميل يتطلب كلمة مرور أبجدية رقمية. |
| RequireStorageCardEncryption | `16` | يشير إلى ما إذا كان يجب على الجهاز تشفير المحتوى المخزن على بطاقة التخزين. |
| PasswordRecoveryEnabled | `17` | يشير إلى ما إذا كان سيتم تمكين إرسال كلمة مرور الاسترداد إلى الخادم باستخدام أمر الإعدادات. |
| AttachmentsEnabled | `19` | يشير إلى ما إذا تم تمكين مرفقات البريد الإلكتروني . |
| MinDevicePasswordLength | `20` | الحد الأدنى لطول كلمة مرور الجهاز التي يمكن للمستخدم إدخالها |
| MaxInactivityTimeDeviceLock | `21` | عدد ثوانٍ من عدم النشاط قبل أن يقفل الجهاز نفسه. |
| MaxDevicePasswordFailedAttempts | `22` | عدد مرات فشل كلمة المرور المسموح بها قبل مسح الجهاز. |
| MaxAttachmentSize | `23` | الحد الأقصى لحجم المرفقات ، كما هو محدد في سياسة الأمان. |
| AllowSimpleDevicePassword | `24` | ما إذا كان الجهاز يسمح بكلمات مرور بسيطة. |
| DevicePasswordExpiration | `25` | ما إذا كانت صلاحية كلمة المرور تنتهي بعد العدد المحدد من الأيام ، على النحو الذي تحدده السياسة. |
| DevicePasswordHistory | `26` | الحد الأدنى لعدد كلمات المرور المستخدمة مسبقًا التي يخزنها جهاز العميل لمنع إعادة الاستخدام. |
| AllowStorageCard | `27` | ما إذا كان الجهاز يسمح باستخدام بطاقة التخزين. |
| AllowCamera | `28` | ما إذا كان الجهاز يسمح باستخدام الكاميرا المدمجة. |
| RequireDeviceEncryption | `29` | ما إذا كان الجهاز يستخدم التشفير . |
| AllowUnsignedApplications | `30` | ما إذا كان الجهاز يسمح بتنفيذ التطبيقات غير الموقعة. |
| AllowUnsignedInstallationPackages | `31` | ما إذا كان الجهاز يسمح بتثبيت ملفات الخزانة (.cab) غير الموقعة. |
| MinDevicePasswordComplexCharacters | `32` | الحد الأدنى لعدد الأحرف المركبة (الأرقام والرموز) الموجودة في كلمة المرور. |
| AllowWiFi | `33` | ما إذا كان الجهاز يسمح باستخدام اتصالات Wi-Fi . |
| AllowTextMessaging | `34` | ما إذا كان الجهاز يسمح بخدمة الرسائل القصيرة (SMS) / الرسائل النصية. |
| AllowPOPIMAPEmail | `35` | ما إذا كان الجهاز يسمح بالوصول إلى بريد POP / IMAP الإلكتروني. |
| AllowBluetooth | `36` | ما إذا كان يُسمح بتوصيفات Bluetooth والتحدث اللايدوي على الجهاز. |
| AllowIrDA | `37` | ما إذا كان الجهاز يسمح باستخدام اتصالات الأشعة تحت الحمراء (الأشعة تحت الحمراء). |
| RequireManualSyncWhenRoaming | `38` | ما إذا كان الجهاز يتطلب مزامنة يدوية أثناء تجوال الجهاز. |
| AllowDesktopSync | `39` | ما إذا كان الجهاز يسمح بالمزامنة مع Desktop ActiveSync. |
| MaxCalendarAgeFilter | `40` | الحد الأقصى لعدد أيام التقويم التي يمكن مزامنتها . |
| AllowHTMLEmail | `41` | ما إذا كان الجهاز يستخدم بريدًا إلكترونيًا بتنسيق HTML. |
| MaxEmailAgeFilter | `42` | الحد الأقصى لعمر البريد الإلكتروني للمزامنة . |
| MaxEmailBodyTruncationSize | `43` | حجم الاقتطاع لرسائل البريد الإلكتروني المنسقة بالنص العادي. |
| MaxEmailHTMLBodyTruncationSize | `44` | حجم الاقتطاع لرسائل البريد الإلكتروني بتنسيق HTML . |
| RequireSignedSMIMEMessages | `45` | ما إذا كان الجهاز مطلوبًا لإرسال رسائل S / MIME موقعة. |
| RequireEncryptedSMIMEMessages | `46` | ما إذا كان الجهاز مطلوبًا لإرسال رسائل مشفرة. |
| RequireSignedSMIMEAlgorithm | `47` | الخوارزمية التي سيتم استخدامها عند توقيع رسالة. |
| RequireEncryptionSMIMEAlgorithm | `48` | الخوارزمية المستخدمة عند تشفير رسالة. |
| AllowSMIMEEncryptionAlgorithmNegotiation | `49` | ما إذا كان الجهاز يمكنه التفاوض على خوارزمية التشفير التي سيتم استخدامها للتوقيع. |
| AllowSMIMESoftCerts | `50` | ما إذا كان الجهاز يستخدم شهادات مرنة لتوقيع الرسائل الصادرة. |
| AllowBrowser | `51` | ما إذا كان الجهاز يسمح باستخدام متصفح الويب. |
| AllowConsumerEmail | `52` | ما إذا كان الجهاز يسمح باستخدام البريد الإلكتروني الشخصي. |
| AllowRemoteDesktop | `53` | ما إذا كان الجهاز يسمح باستخدام سطح المكتب البعيد. |
| AllowInternetSharing | `54` | ما إذا كان الجهاز يسمح باستخدام مشاركة الإنترنت. |
| UnapprovedInROMApplicationList | `55` | قائمة بالتطبيقات المضمنة في ذاكرة القراءة فقط التي لم تتم الموافقة عليها للتنفيذ. |
| ApplicationName | `56` | اسم تطبيق داخل ROM (ملف .exe) غير معتمد للتنفيذ. |
| ApprovedApplicationList | `57` | قائمة بتطبيقات ذاكرة الوصول العشوائي التي تمت الموافقة عليها للتنفيذ. |
| Hash | `58` | تجزئة SHA-1 لتطبيق في الذاكرة تمت الموافقة عليه للتنفيذ. |

### أنظر أيضا

* مساحة الاسم [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
