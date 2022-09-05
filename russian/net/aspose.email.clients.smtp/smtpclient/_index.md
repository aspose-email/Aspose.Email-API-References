---
title: SmtpClient
second_title: Справочник по Aspose.Email для .NET API
description: Позволяет приложениям отправлять сообщения с использованием простого протокола передачи почты SMTP.
type: docs
weight: 17030
url: /ru/net/aspose.email.clients.smtp/smtpclient/
---
## SmtpClient class

Позволяет приложениям отправлять сообщения с использованием простого протокола передачи почты (SMTP).

```csharp
public sealed class SmtpClient : EmailClient, IAsyncSmtpClient, IMailTransferAgent
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SmtpClient](smtpclient#constructor)() | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_1)(Configuration) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс с помощью настроек файла конфигурации. |
| [SmtpClient](smtpclient#constructor_2)(string) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_4)(string, int) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_3)(string, SecurityOptions) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_5)(string, int, SecurityOptions) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_12)(string, string, ITokenProvider) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_14)(string, string, string) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_6)(string, int, string, ITokenProvider) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_8)(string, int, string, string) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_13)(string, string, ITokenProvider, SecurityOptions) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_16)(string, string, string, bool) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_15)(string, string, string, SecurityOptions) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_7)(string, int, string, ITokenProvider, SecurityOptions) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_10)(string, int, string, string, bool) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_9)(string, int, string, string, SecurityOptions) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_17)(string, string, string, bool, SecurityOptions) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |
| [SmtpClient](smtpclient#constructor_11)(string, int, string, string, bool, SecurityOptions) | Инициализирует новый экземпляр[`SmtpClient`](../smtpclient) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Получает или задает токен доступа. |
| [AllowedAuthentication](../../aspose.email.clients.smtp/smtpclient/allowedauthentication) { get; set; } | Получает или задает перечисление разрешенных типов аутентификации пользователя |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Содержит коллекцию сертификатов клиентов |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Получает или задает значение, определяющее режим распределения соединений в нескольких потоках environment Существуют следующие типы соединений: - Основное соединение создается и удаляется вместе с почтовым клиентом. Его нельзя создать или удалить вручную. - Соединение по умолчанию является соединением по умолчанию для некоторого потока. Если соединение по умолчанию существует и ConnectionAsgmtMode разрешает, все методы почтового клиента, выполняемые в этом потоке, будут неявно использовать это соединение. В каждом потоке может существовать только одно соединение по умолчанию. Он может быть создан вручную или автоматически. Это зависит от свойства EmailClient.ConnectionAsgmtMode. Эти соединения можно создать вручную с помощью метода EmailClient.CreateConnection(createAsDefaultConnection = true). Если соединение по умолчанию не используется (зависит от режима распределения соединений), вместо него неявно используется основное соединение. не связаны с потоками. Они могут быть созданы вручную и должны использоваться явно как параметр метода. Эти соединения можно создать вручную с помощью метода EmailClient.CreateConnection() или метода EmailClient.CreateConnection(createAsDefaultConnection = false). Существуют следующие типы распределения соединений: - ConnectionAsgmtType.UseMainOrDefault Этот режим используется по умолчанию в почтовых клиентах. Почтовый клиент использует основное соединение для всех операций из нескольких потоков, если соединение по умолчанию не было создано или соединение не было явно передано как параметр метода. Основное соединение — это соединение, которое создается одновременно с почтовым клиентом. Пользователь может создавать соединения по умолчанию для потоков с помощью метода CreateConnection. Если создано соединение по умолчанию для потока, оно неявно используется для всех методов почтового клиента, которые вызываются в этом потоке. Если соединение по умолчанию для потока не создано, основное соединение используется для всех методов почтового клиента, которые вызываются в этом потоке. thread. Пользователь также может создавать соединения, не связанные с потоками (не соединения по умолчанию), с помощью метода CreateConnection. Если пользователь хочет использовать другие подключения (не основные и не по умолчанию), он должен явно передать это подключение как параметр метода, который он хочет использовать. Пользователь может дополнительно создать любое количество подключений. Соединение по умолчанию может быть только одно на поток. Обратите внимание, что соединения по умолчанию работают правильно, если пользователь использует объекты Thread для многозадачного программирования. Если пользователь использует ConnectionPool или объекты Task для многозадачного программирования, этот режим может привести к неправильному поведению программы. Чтобы избежать этой проблемы, пользователь должен вручную удалить соединение по умолчанию (если он его использует) в конце кода, который the thread. - ConnectionAsgmtType.UseMain Почтовый клиент использует основное соединение для всех операций из нескольких потоков. Основное соединение — это соединение, которое создается одновременно с почтовым клиентом. Пользователь не может создавать соединения по умолчанию. Пользователь может создавать соединения, не связанные с потоками (не соединения по умолчанию), с помощью метода CreateConnection. Если пользователь хочет использовать другие подключения (не основные и не по умолчанию), он должен явно передать это подключение как параметр метода, который он хочет использовать. Пользователь может дополнительно создать любое количество подключений. - ConnectionAsgmtType.UseDefault Почтовый клиент неявно использует только соединения по умолчанию для всех операций из нескольких потоков. В этом режиме основное соединение не используется. Если для какого-либо потока не было создано соединение по умолчанию (первый вызов метода почтового клиента), почтовый клиент неявно создает соединение по умолчанию для потока перед выполнением первой операции. Пользователь не может создавать подключения по умолчанию для потоков с помощью метода CreateConnection, поскольку они создаются автоматически. Когда создается соединение по умолчанию для потока, оно неявно используется для всех методов почтового клиента, которые вызываются в этом потоке. Читайте. Пользователь также может создавать соединения, не связанные с потоками (не соединения по умолчанию), с помощью метода CreateConnection. Если пользователь хочет использовать другие подключения (не основные и не по умолчанию), он должен явно передать это подключение как параметр метода, который он хочет использовать. Пользователь может дополнительно создать любое количество подключений. Соединение по умолчанию может быть только одно на поток. Обратите внимание, что соединения по умолчанию работают правильно, если пользователь использует объекты Thread для многозадачного программирования. Если пользователь использует ConnectionPool или объекты Task для многозадачного программирования, этот режим может привести к неправильному поведению программы. Чтобы избежать этой проблемы, пользователь должен вручную удалить соединение по умолчанию в конце кода, который выполняется в потоке. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Период проверки соединения в миллисекундах. Значение по умолчанию: 5 мин. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Получает или устанавливает количество подключений в режиме множественных подключений |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Получает текущее состояние соединения. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Получает текущее соединение в соответствии с ConnectionAsgmtMode option |
| override [DefaultPort](../../aspose.email.clients.smtp/smtpclient/defaultport) { get; } | Получает порт по умолчанию для client |
| [DeliveryMethod](../../aspose.email.clients.smtp/smtpclient/deliverymethod) { get; set; } | Получает или задает способ доставки. |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Получает или устанавливает значение, которое позволяет включить/выключить logger |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Получает или задает время ожидания приветствия, которое используется при установлении соединения. Обратите внимание, что время ожидания приветствия не может быть бесконечным. Почтовые клиенты могут выполнять достаточно длительные операции. Для ограничения времени операций пользователи должны использовать[`Timeout`](../../aspose.email.clients/emailclient/timeout)имущество. Значения этого свойства должны иметь длинные интервалы, чтобы не препятствовать длительным операциям. Но в некоторых случаях, если EmailClient будет использовать только свойство Timeout, установление соединения может занять много времени. Например, почтовый клиент может использовать автоматический режим установления соединения. В этом режиме почтовый клиент перебирает все возможные параметры подключения, пока соединение не будет установлено. Серверы SMTP, IMAP и POP3 в случае корректного установления соединения отправляют клиенту строку приветствия. Серверы могут использовать неявную или явную (START TLS) инициацию соединения SSL/TLS. Если режим подключения не соответствует (например, сервер ожидает неявного SSL-соединения, но клиент пытается установить незащищенное или явное SSL-соединение), сервер не будет отправлять строку приветствия. В этом случае пользователь будет долго ждать, пока таймаут достигнет строки приветствия, и клиент перейдет к следующему варианту подключения. Чтобы избежать этой проблемы, было введено свойство GreetingTimeout. Это свойство позволяет установить тайм-аут для строки приветствия и уменьшить время автоматического установления соединения. |
| [HelloMessage](../../aspose.email.clients.smtp/smtpclient/hellomessage) { get; set; } | Получает или задает строку HELO/EHLO. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Получает или задает имя хоста. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Получает или задает имя файла журнала |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Получает или устанавливает пароль. Ограничения пароля определяются реализацией сервера, к которому подключается клиент. |
| [PickupDirectoryLocation](../../aspose.email.clients.smtp/smtpclient/pickupdirectorylocation) { get; set; } | Получает или задает каталог, в котором приложения сохраняют почтовые сообщения для обработки локальным SMTP-сервером. Обратите внимание: разрешен только абсолютный путь. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Получает или задает порт. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Получает или устанавливает прокси для client |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Режим безопасности для почтового клиента |
| [SmtpQueueLocation](../../aspose.email.clients.smtp/smtpclient/smtpqueuelocation) { get; set; } | Получает или задает каталог, в котором приложения сохраняют почтовые сообщения для обработки путем отправки в очередь SMTP. Обратите внимание: разрешен только абсолютный путь. |
| [SupportedAuthentication](../../aspose.email.clients.smtp/smtpclient/supportedauthentication) { get; } | Получает перечисление поддерживаемых сервером типов аутентификации |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Определяет используемые версии протоколов шифрования SSL/TLS. ОБРАТИТЕ ВАШЕ ВНИМАНИЕ, вы можете установить только те версии протокола, которые поддерживаются .net framework. ЕСЛИ НЕКОТОРЫЕ ВЕРСИИ ПРОТОКОЛА НЕ ПОДДЕРЖИВАЮТСЯ ВАШЕЙ ТЕКУЩЕЙ ВЕРСИЕЙ .NET FRAMEWORK, ОНИ БУДУТ ИГНОРИРОВАТЬСЯ И ПРОПУСКАТЬ. ЭТО МОЖЕТ ПРИВЕСТИ К ПОНИЖЕНИЮ УРОВНЯ БЕЗОПАСНОСТИ TLS. В ЭТОМ СЛУЧАЕ ИСКЛЮЧЕНИЕ НЕ БУДЕТ СОЗДАНО!!! См.[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) документацию для более подробной информации. Пожалуйста, используйте[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) метод, если вы хотите установить протоколы шифрования без каких-либо проверок совместимости. Значение по умолчанию: Tls &#x7C; Тлс11 &#x7C; Тлс12 &#x7C; Tls13 (в случае, если ваша текущая версия .net framework поддерживает эти версии TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Получает или задает время ожидания для почтовых операций |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Получает или задает TokenProvider, позволяющий получить токен доступа. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Указывает, используется ли аутентификация. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Получает или задает значение, указывающее, следует ли использовать дату в имени файла журнала. |
| override [UseDefaultCredentials](../../aspose.email.clients.smtp/smtpclient/usedefaultcredentials) { get; set; } | Получает или задает логическое значение, которое определяет, отправляются ли DefaultCredentials с запросами. |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Получает или задает значение, указывающее, должен ли клиент использовать несколько подключений для тяжелых операций. Обратите внимание, использование этого режима не обязательно должно привести к повышению производительности. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Получает или задает объект, указывающий, включен ли конвейерный режим. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Получает или задает имя пользователя. |
| [UseTnef](../../aspose.email.clients.smtp/smtpclient/usetnef) { get; set; } | Получает или задает логическое значение, определяющее отправку сообщений в формате TNEF. Обратите внимание, что теперь сообщение отправляется в формате TNEF при загрузке сообщения, содержащего tnef. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Создает новое независимое соединение для операций, не связанных с потоками (не соединение по умолчанию). Вызов этого метода аналогичен вызову CreateConnection(createAsDefaultConnection = false) Подробнее см. в документации по свойству EmailClient.ConnectionAsgmtMode. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Создает новое (по умолчанию или независимое) соединение для операций. Дополнительные сведения см. в документации по свойству EmailClient.ConnectionAsgmtMode. |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Завершает все операции с сервером. |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_3)(string, MailAddressCollection, MailMessage) | Пересылает указанное сообщение получателю |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_4)(string, MailAddressCollection, Stream) | Пересылает указанное сообщение получателю |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_5)(string, string, MailMessage) | Пересылает указанное сообщение получателю |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward)(IConnection, string, MailAddressCollection, MailMessage) | Пересылает указанное сообщение получателю |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_1)(IConnection, string, MailAddressCollection, Stream) | Пересылает указанное сообщение получателю |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_2)(IConnection, string, string, MailMessage) | Пересылает указанное сообщение получателю |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_6)(string, MailAddressCollection, MailMessage) | Пересылает указанное сообщение получателю |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_8)(string, MailAddressCollection, Stream) | Пересылает указанное сообщение получателю |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_10)(string, string, MailMessage) | Пересылает указанное сообщение получателю |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync)(IConnection, string, MailAddressCollection, MailMessage) | Пересылает указанное сообщение получателю |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_2)(IConnection, string, MailAddressCollection, Stream) | Пересылает указанное сообщение получателю |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_4)(IConnection, string, string, MailMessage) | Пересылает указанное сообщение получателю |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_7)(string, MailAddressCollection, MailMessage, CancellationToken) | Пересылает указанное сообщение получателю |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_9)(string, MailAddressCollection, Stream, CancellationToken) | Пересылает указанное сообщение получателю |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_11)(string, string, MailMessage, CancellationToken) | Пересылает указанное сообщение получателю |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_1)(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) | Пересылает указанное сообщение получателю |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_3)(IConnection, string, MailAddressCollection, Stream, CancellationToken) | Пересылает указанное сообщение получателю |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_5)(IConnection, string, string, MailMessage, CancellationToken) | Пересылает указанное сообщение получателю |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop)() | Команда "Нет операции" |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop_1)(IConnection) | Команда "Нет операции" |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync)() | Команда "Нет операции" |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_3)(CancellationToken) | Команда "Нет операции" |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_1)(IConnection) | Команда "Нет операции" |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_2)(IConnection, CancellationToken) | Команда "Нет операции" |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Сбрасывает настройки ведения журнала по умолчанию. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_8)(IEnumerable&lt;MailMessage&gt;) | Отправить указанные сообщения. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_5)(MailMessage) | Отправить указанное сообщение. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_6)(MailMessageCollection) | Отправить указанную коллекцию сообщений. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_7)(params MailMessage[]) | Отправить указанное сообщение. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_3)(IConnection, IEnumerable&lt;MailMessage&gt;) | Отправить указанные сообщения. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send)(IConnection, MailMessage) | Отправить указанное сообщение. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_1)(IConnection, MailMessageCollection) | Отправить указанную коллекцию сообщений. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_2)(IConnection, params MailMessage[]) | Отправить указанное сообщение. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_9)(string, string, string, string) | Создает и отправляет указанное сообщение. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_4)(IConnection, string, string, string, string) | Создает и отправляет указанное сообщение. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_16)(IEnumerable&lt;MailMessage&gt;) | Отправить указанные сообщения. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_11)(MailMessage) | Отправить указанное сообщение. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_13)(MailMessageCollection) | Отправить указанную коллекцию сообщений. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_15)(params MailMessage[]) | Отправить указанное сообщение. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_10)(SmtpSend) |  |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_20)(CancellationToken, params MailMessage[]) | Отправить указанное сообщение. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_5)(IConnection, IEnumerable&lt;MailMessage&gt;) | Отправить указанные сообщения. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync)(IConnection, MailMessage) | Отправить указанное сообщение. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_2)(IConnection, MailMessageCollection) | Отправить указанную коллекцию сообщений. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_4)(IConnection, params MailMessage[]) | Отправить указанное сообщение. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_17)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | Отправить указанные сообщения. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_12)(MailMessage, CancellationToken) | Отправить указанное сообщение. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_14)(MailMessageCollection, CancellationToken) | Отправить указанную коллекцию сообщений. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_9)(IConnection, CancellationToken, params MailMessage[]) | Отправить указанное сообщение. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_6)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Отправить указанные сообщения. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_1)(IConnection, MailMessage, CancellationToken) | Отправить указанное сообщение. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_3)(IConnection, MailMessageCollection, CancellationToken) | Отправить указанную коллекцию сообщений. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_18)(string, string, string, string) | Создает и отправляет указанное сообщение. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_7)(IConnection, string, string, string, string) | Создает и отправляет указанное сообщение. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_19)(string, string, string, string, CancellationToken) | Создает и отправляет указанное сообщение. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_8)(IConnection, string, string, string, string, CancellationToken) | Создает и отправляет указанное сообщение. |
| [SendToQueue](../../aspose.email.clients.smtp/smtpclient/sendtoqueue)(IEnumerable&lt;MailMessage&gt;) | Добавлять сообщения в очередь |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Определяет используемые версии протоколов шифрования SSL/TLS. Этот метод небезопасен и устанавливает протоколы шифрования без каких-либо проверок совместимости. Использование[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) свойство для безопасной установки только тех протоколов, которые определенно поддерживаются .net framework. Обратите внимание, если ваш текущий .net framework не поддерживает этот уровень безопасности, будет выдано исключение при попытке установить соединение с сервером. |
| override [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials)() | Выполняет проверку учетных данных |
| [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials_1)(IConnection) | Выполняет проверку учетных данных |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync)() | Выполняет проверку учетных данных |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Выполняет проверку учетных данных |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Выполняет проверку учетных данных |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Выполняет проверку учетных данных |
| static [CreateAsync](../../aspose.email.clients.smtp/smtpclient/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Создает новый экземпляр[`SmtpClient`](../smtpclient) класс |

### Смотрите также

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncSmtpClient](../iasyncsmtpclient)
* interface [IMailTransferAgent](../imailtransferagent)
* пространство имен [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
