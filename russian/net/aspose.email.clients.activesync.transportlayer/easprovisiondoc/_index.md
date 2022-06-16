---
title: EASProvisionDoc
second_title: Справочник по Aspose.Email для .NET API
description: Задает набор параметров безопасности для подготовки устройства.
type: docs
weight: 1190
url: /ru/net/aspose.email.clients.activesync.transportlayer/easprovisiondoc/
---
## EASProvisionDoc class

Задает набор параметров безопасности для подготовки устройства.

```csharp
public class EASProvisionDoc
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EASProvisionDoc](easprovisiondoc)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AllowBluetooth](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowbluetooth) { get; set; } | Указывает использование Bluetooth на устройстве. Это свойство СЛЕДУЕТ игнорировать, если клиент не поддерживает Bluetooth. |
| [AllowBrowser](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowbrowser) { get; set; } | Указывает, позволяет ли устройство использовать веб-браузер. |
| [AllowCamera](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowcamera) { get; set; } | Указывает, позволяет ли устройство использовать встроенную камеру. Это свойство ДОЛЖНО игнорироваться, если у клиента нет камеры и никакая камера не может быть подключена к устройству. |
| [AllowConsumerEmail](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowconsumeremail) { get; set; } | Указывает, позволяет ли устройство пользователю настраивать личную учетную запись электронной почты. |
| [AllowDesktopSync](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowdesktopsync) { get; set; } | Указывает, разрешает ли устройство синхронизацию с Desktop ActiveSync. Это свойство СЛЕДУЕТ игнорировать, если клиент не поддерживает подключение к персональному компьютеру. |
| [AllowHTMLEmail](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowhtmlemail) { get; set; } | Указывает, использует ли клиент электронную почту в формате HTML. |
| [AllowInternetSharing](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowinternetsharing) { get; set; } | Указывает, разрешает ли устройство использование общего доступа к Интернету. Это свойство СЛЕДУЕТ игнорировать, если клиент не поддерживает совместное использование своего интернет-соединения с другими устройствами. |
| [AllowIrDA](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowirda) { get; set; } | Указывает, позволяет ли устройство использовать IrDA (инфракрасные) соединения. Это свойство СЛЕДУЕТ игнорировать, если клиент не имеет возможности передачи или приема инфракрасных сигналов. |
| [AllowPOPIMAPEmail](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowpopimapemail) { get; set; } | Указывает, разрешает ли устройство доступ к электронной почте POP или IMAP. |
| [AllowRemoteDesktop](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowremotedesktop) { get; set; } | Указывает, позволяет ли устройство использовать удаленный рабочий стол. Это свойство СЛЕДУЕТ игнорировать, если клиент не поддерживает удаленное подключение к персональному компьютеру. |
| [AllowSimpleDevicePassword](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowsimpledevicepassword) { get; set; } | Указывает, разрешает ли клиент простые пароли. Простой пароль состоит только из повторяющихся ("2222") или последовательных ("abcd") символов. Если AllowSimpleDevicePassword имеет значение null, клиент ДОЛЖЕН рассматривать это значение как TRUE. Если значение DevicePasswordEnabled установлено в FALSE, клиент ДОЛЖЕН игнорировать это свойство. |
| [AllowSMIMEEncryptionAlgorithmNegotiation](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowsmimeencryptionalgorithmnegotiation) { get; set; } | Управляет согласованием алгоритма шифрования. |
| [AllowSMIMESoftCerts](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowsmimesoftcerts) { get; set; } | Указывает, может ли клиент использовать программные сертификаты для подписи исходящих сообщений. |
| [AllowStorageCard](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowstoragecard) { get; set; } | Указывает, разрешает ли устройство использование карты памяти. Это свойство СЛЕДУЕТ игнорировать, если клиент не поддерживает хранение данных на съемном носителе. |
| [AllowTextMessaging](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowtextmessaging) { get; set; } | Указывает, позволяет ли устройство использовать SMS или текстовые сообщения. Это свойство СЛЕДУЕТ игнорировать, если клиент не поддерживает SMS или текстовые сообщения. |
| [AllowUnsignedApplications](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowunsignedapplications) { get; set; } | Указывает, позволяет ли устройство выполнять неподписанные приложения. |
| [AllowUnsignedInstallationPackages](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowunsignedinstallationpackages) { get; set; } | Указывает, разрешает ли устройство установку неподписанных CAB-файлов. |
| [AllowWiFi](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowwifi) { get; set; } | Указывает, разрешает ли устройство использование соединений Wi-Fi. Это свойство СЛЕДУЕТ игнорировать, если у клиента нет возможности Wi-Fi. |
| [AlphanumericDevicePasswordRequired](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/alphanumericdevicepasswordrequired) { get; set; } | Указывает, требует ли клиент буквенно-цифровой пароль. Если AlphanumericDevicePasswordRequired имеет значение null, клиент ДОЛЖЕН рассматривать это значение как FALSE. Если значение DevicePasswordEnabled равно FALSE, клиент ДОЛЖЕН игнорировать это свойство. |
| [ApprovedApplicationList](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/approvedapplicationlist) { get; } | Указывает список приложений в памяти, которые одобрены для выполнения. Это свойство затрагивает только приложения в памяти. Это свойство не применяется к приложениям в ПЗУ. Если не пусто, клиент ДОЛЖЕН разрешать выполнение только тем приложениям в памяти, которые указаны этим свойством. |
| [AttachmentsEnabled](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/attachmentsenabled) { get; set; } | Указывает, включены ли вложения электронной почты. |
| [DevicePasswordEnabled](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordenabled) { get; set; } | Указывает, требует ли клиент пароль. |
| [DevicePasswordExpiration](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordexpiration) { get; set; } | Указывает максимальное количество дней до истечения срока действия пароля. DevicePasswordExpiration может быть нулевым, указывая на то, что политика истечения срока действия пароля не установлена. Допустимые значения перечислены ниже: = 0 - Срок действия паролей не ограничен. &gt; 0 — Срок действия паролей истекает через указанное максимальное количество дней. Если DevicePasswordExpiration имеет значение null, клиент ДОЛЖЕН рассматривать это значение как 0. Если значение DevicePasswordEnabled установлено в FALSE, клиент ДОЛЖЕН игнорировать это свойство. |
| [DevicePasswordHistory](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordhistory) { get; set; } | Указывает минимальное количество ранее использованных паролей, сохраняемых для предотвращения повторного использования клиентом. Ниже перечислены допустимые значения: = 0 - Сохранение ранее использованных паролей не требуется. &gt; 0 - Минимальное количество ранее использованных паролей для хранения. Если DevicePasswordHistory имеет значение null, то клиент ДОЛЖЕН рассматривать это значение как 0. Если значение DevicePasswordEnabled установлено в TRUE, клиент запрещает пользователю использовать сохраненный предыдущий пароль после истечения срока действия пароля. Если значение DevicePasswordEnabled установлено в FALSE, клиент ДОЛЖЕН игнорировать это свойство. |
| [MaxAttachmentSize](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxattachmentsize) { get; set; } | Указывает максимальный размер вложения в байтах, определенный политикой безопасности. Если свойство имеет значение null, клиент интерпретирует это как означающее, что политика безопасности не установила максимальный размер вложения. |
| [MaxCalendarAgeFilter](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxcalendaragefilter) { get; set; } | Задает максимальное количество календарных дней, которые можно синхронизировать. Допустимые значения перечислены ниже: Все дни 2 недели 1 месяц 3 месяца 6 месяцев |
| [MaxDevicePasswordFailedAttempts](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxdevicepasswordfailedattempts) { get; set; } | Указывает максимально допустимое количество неудачных попыток входа с паролем. Клиент ДОЛЖЕН выполнить локальную очистку или войти в режим временной блокировки, если достигнуто максимальное количество неудачных попыток входа с паролем. MaxDevicePasswordFailedAttempts может быть нулевым или иметь значение в диапазоне от 4 до 16. Если свойство равно null, клиент интерпретирует это как означающее, что максимальное количество неверных паролей отсутствует. количество попыток входа было установлено политикой безопасности. Если значение DevicePasswordEnabled установлено в FALSE, клиент игнорирует это свойство. |
| [MaxEmailAgeFilter](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxemailagefilter) { get; set; } | Указывает возрастной предел электронной почты для синхронизации. Допустимые значения перечислены ниже: Синхронизировать все 1 день 3 дня 1 неделя 2 недели 1 месяц |
| [MaxEmailBodyTruncationSize](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxemailbodytruncationsize) { get; set; } | Указывает размер усечения для электронной почты в формате обычного текста. Допустимые значения перечислены ниже: -1 Без усечения. =0 Обрезать только заголовок. &gt;0 Обрезать тело электронной почты до указанного размера. |
| [MaxEmailHTMLBodyTruncationSize](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxemailhtmlbodytruncationsize) { get; set; } | Указывает размер усечения для электронной почты в формате HTML. Допустимые значения перечислены ниже: -1 Без усечения. =0 Обрезать только заголовок. &gt;0 Обрезать тело электронной почты до указанного размера. |
| [MaxInactivityTimeDeviceLock](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxinactivitytimedevicelock) { get; set; } | Указывает максимальное количество секунд бездействия, прежде чем устройство заблокируется. Если это значение больше или равно 9999, клиент интерпретирует его как неограниченное. Если MaxInactivityTimeDeviceLock имеет значение null, клиент интерпретирует это как означающее, что политика безопасности не установила блокировку устройства времени. |
| [MinDevicePasswordComplexCharacters](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/mindevicepasswordcomplexcharacters) { get; set; } | Задает требуемый уровень сложности пароля клиента. Значение указывает количество групп символов, которые должны присутствовать в пароле. Группы символов определяются следующим образом: Строчные буквы алфавита = 1 Строчные и прописные буквы алфавита = 2 Строчные и прописные буквы алфавита и цифры = 3 Строчные и прописные буквы алфавита, цифры и небуквенно-цифровые символы = 4 Например: Если значение MinDevicePasswordComplexCharacters равно 2, будет достаточно пароля, состоящего как из букв верхнего, так и из нижнего регистра, а также пароля из букв нижнего регистра и цифр. |
| [MinDevicePasswordLength](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/mindevicepasswordlength) { get; set; } | Указывает минимальную длину пароля клиента. MinDevicePasswordLength может быть пустым или иметь значение не меньше 1 и не больше 16. Если свойство равно null или значение этого свойства равно 1, минимальная длина пароля устройства. Если значение DevicePasswordEnabled равно FALSE, клиент ДОЛЖЕН игнорировать это свойство. |
| [PasswordRecoveryEnabled](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/passwordrecoveryenabled) { get; set; } | Указывает, поддерживает ли сервер хранение пароля восстановления, отправляемого клиентом с помощью команды «Настройки». Пароль восстановления - это специальный пароль, созданный клиентом, который дает администратору или пользователю возможность однократного входа в устройство, после чего пользователю требуется создать новый пароль. Затем клиент создает новый пароль восстановления. Если для PasswordRecoveryEnabled установлено значение TRUE, сервер поддерживает хранение пароля восстановления, отправленного устройством. Если свойство установлено в FALSE, устройство НЕ ДОЛЖНО отправлять пароль восстановления, потому что сервер не поддерживает хранение пароля. Если PasswordRecoveryEnabled имеет значение null, клиент ДОЛЖЕН рассматривать это значение как FALSE. Если значение DevicePasswordEnabled равно FALSE, клиент ДОЛЖЕН игнорировать это свойство. Это свойство СЛЕДУЕТ игнорировать, если клиент не поддерживает пароли восстановления. |
| [RequireDeviceEncryption](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiredeviceencryption) { get; set; } | Указывает, использует ли клиент шифрование. |
| [RequireEncryptedSMIMEMessages](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requireencryptedsmimemessages) { get; set; } | Указывает, отправляет ли клиент зашифрованные сообщения электронной почты. |
| [RequireEncryptionSMIMEAlgorithm](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requireencryptionsmimealgorithm) { get; set; } | Указывает алгоритм, используемый при шифровании сообщений S/MIME. |
| [RequireManualSyncWhenRoaming](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiremanualsyncwhenroaming) { get; set; } | Указывает, требует ли устройство ручной синхронизации, когда устройство находится в роуминге. |
| [RequireSignedSMIMEAlgorithm](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiresignedsmimealgorithm) { get; set; } | Указывает алгоритм, используемый при подписании сообщений S/MIME. |
| [RequireSignedSMIMEMessages](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiresignedsmimemessages) { get; set; } | Указывает, отправляет ли клиент подписанные сообщения S/MIME. |
| [RequireStorageCardEncryption](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requirestoragecardencryption) { get; set; } | Указывает, шифрует ли устройство содержимое, хранящееся на нем. Это свойство СЛЕДУЕТ игнорировать, если клиент не поддерживает хранение данных на съемном носителе. |
| [UnapprovedInROMApplicationList](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/unapprovedinromapplicationlist) { get; } | Указывает список встроенных в ПЗУ приложений, выполнение которых не разрешено. Записи в этом свойстве затрагивают только приложения, предварительно установленные в ПЗУ. Это свойство не применяется к приложениям, установленным в памяти. |

### Смотрите также

* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->