---
title: Pop3Client
second_title: Справочник по Aspose.Email для .NET API
description: Позволяет приложениям получать доступ к сообщениям и управлять ими с помощью почтового протокола версии 3 POP3.
type: docs
weight: 16880
url: /ru/net/aspose.email.clients.pop3/pop3client/
---
## Pop3Client class

Позволяет приложениям получать доступ к сообщениям и управлять ими с помощью почтового протокола версии 3 (POP3).

```csharp
public sealed class Pop3Client : EmailClient, IAsyncPop3Client
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Pop3Client](pop3client#constructor)() | Инициализирует новый экземпляр класса[`Pop3Client`](../pop3client) |
| [Pop3Client](pop3client#constructor_1)(string) | Инициализирует новый экземпляр класса[`Pop3Client`](../pop3client) |
| [Pop3Client](pop3client#constructor_3)(string, int) | Инициализирует новый экземпляр класса[`Pop3Client`](../pop3client) |
| [Pop3Client](pop3client#constructor_2)(string, SecurityOptions) | Инициализирует новый экземпляр класса[`Pop3Client`](../pop3client) |
| [Pop3Client](pop3client#constructor_4)(string, int, SecurityOptions) | Инициализирует новый экземпляр класса[`Pop3Client`](../pop3client) |
| [Pop3Client](pop3client#constructor_11)(string, string, string) | Инициализирует новый экземпляр класса[`Pop3Client`](../pop3client) |
| [Pop3Client](pop3client#constructor_6)(string, int, string, string) | Инициализирует новый экземпляр класса[`Pop3Client`](../pop3client) |
| [Pop3Client](pop3client#constructor_12)(string, string, string, SecurityOptions) | Инициализирует новый экземпляр класса[`Pop3Client`](../pop3client) |
| [Pop3Client](pop3client#constructor_5)(string, int, string, ITokenProvider, SecurityOptions) | Инициализирует новый экземпляр класса[`Pop3Client`](../pop3client) |
| [Pop3Client](pop3client#constructor_9)(string, int, string, string, RemoteCertificateValidationCallback) | Инициализирует новый экземпляр класса[`Pop3Client`](../pop3client) |
| [Pop3Client](pop3client#constructor_7)(string, int, string, string, SecurityOptions) | Инициализирует новый экземпляр класса[`Pop3Client`](../pop3client) |
| [Pop3Client](pop3client#constructor_8)(string, int, string, string, bool, SecurityOptions) | Инициализирует новый экземпляр класса[`Pop3Client`](../pop3client) |
| [Pop3Client](pop3client#constructor_10)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | Инициализирует новый экземпляр класса[`Pop3Client`](../pop3client) |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Получает или задает токен доступа. |
| [AllowedAuthentication](../../aspose.email.clients.pop3/pop3client/allowedauthentication) { get; set; } | Получает или задает перечисление разрешенных пользователем типов аутентификации |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Содержит коллекцию клиентских сертификатов |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Получает или задает значение, определяющее режим выделения соединения в многопоточной среде Существуют следующие типы соединения: - Основное соединение создается и удаляется вместе с почтовым клиентом. Его нельзя создать или удалить вручную. - Соединение по умолчанию является соединением по умолчанию для некоторого потока. Если соединение по умолчанию существует и ConnectionAsgmtMode разрешает, все методы почтового клиента, выполняемые в этом потоке, будут неявно использовать это соединение. Для каждого потока может существовать только одно соединение по умолчанию. Он может быть создан вручную или автоматически. Это зависит от свойства EmailClient.ConnectionAsgmtMode. Эти подключения можно создать вручную с помощью метода EmailClient.CreateConnection(createAsDefaultConnection = true). Если соединение по умолчанию не используется (зависит от режима выделения соединения), вместо него неявно используется основное соединение. - Независимые соединения - это соединения, которые не связаны с потоками. Они могут быть созданы вручную и должны использоваться явно как параметр метода. Эти подключения можно создать вручную с помощью метода EmailClient.CreateConnection() или метода EmailClient.CreateConnection(createAsDefaultConnection = false). Существуют следующие типы распределения соединений: - ConnectionAsgmtType.UseMainOrDefault Этот режим используется по умолчанию в почтовых клиентах. Почтовый клиент использует основное соединение для всех операций из нескольких потоков, если соединение по умолчанию не было создано или соединение не было явно передано как параметр метода. Основное соединение - это соединение, которое создается одновременно с почтовым клиентом. Пользователь может создавать соединения по умолчанию для потоков с помощью метода CreateConnection. Если создается подключение по умолчанию для потока, оно неявно используется для всех методов почтового клиента, которые вызываются в этом потоке. Если соединение по умолчанию для потока не создано, основное соединение используется для всех методов почтового клиента, которые вызываются в этом потоке. Пользователь также может создавать соединения, не связанные с потоками (не соединения по умолчанию) с помощью метода CreateConnection. Если пользователь хочет использовать другие соединения (не основные и не по умолчанию), он должен явно передать это соединение как параметр метода, который он хочет использовать. Пользователь может дополнительно создавать любое количество подключений. Соединение по умолчанию может быть только одно на поток. Обратите внимание, что соединения по умолчанию работают правильно, если пользователь использует объекты Thread для многозадачного программирования. Если пользователь использует ConnectionPool или использует объекты Task для многозадачного программирования, этот режим может привести к неправильному поведению программы. Чтобы избежать этой проблемы, пользователь должен вручную удалить соединение по умолчанию (если он его использует) в конце кода, который выполняется в потоке. - ConnectionAsgmtType.UseMain Почтовый клиент использует основное соединение для всех операций из нескольких потоков. Основное соединение - это соединение, которое создается одновременно с почтовым клиентом. Пользователь не может создавать соединения по умолчанию. Пользователь может создавать соединения, не связанные с потоками (не соединения по умолчанию) с помощью метода CreateConnection. Если пользователь хочет использовать другие соединения (не основные и не по умолчанию), он должен явно передать это соединение как параметр метода, который он хочет использовать. Пользователь может дополнительно создавать любое количество подключений. - ConnectionAsgmtType.UseDefault Клиент электронной почты неявно использует только соединения по умолчанию для всех операций из нескольких потоков. Основное соединение в этом режиме не используется. Если для какого-то потока не было создано соединение по умолчанию (первый вызов метода почтового клиента), почтовый клиент неявно создает соединение по умолчанию для потока перед выполнением первой операции. Пользователь не может создавать подключения по умолчанию для потоков с помощью метода CreateConnection, поскольку они создаются автоматически. Когда создается соединение по умолчанию для потока, оно неявно используется для всех методов почтового клиента, которые вызываются в этом потоке. Пользователь также может создавать соединения, не связанные с потоками (не соединения по умолчанию) с помощью метода CreateConnection. Если пользователь хочет использовать другие соединения (не основные и не по умолчанию), он должен явно передать это соединение как параметр метода, который он хочет использовать. Пользователь может дополнительно создавать любое количество подключений. Соединение по умолчанию может быть только одно на поток. Обратите внимание, что соединения по умолчанию работают правильно, если пользователь использует объекты Thread для многозадачного программирования. Если пользователь использует ConnectionPool или использует объекты Task для многозадачного программирования, этот режим может привести к неправильному поведению программы. Чтобы избежать этой проблемы, пользователь должен вручную удалить соединение по умолчанию в конце кода, который выполняется в потоке. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Период проверки соединения в миллисекундах. Значение по умолчанию:5 мин. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Получает или задает количество соединений в режиме множественных соединений |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Получает текущее состояние соединения. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Получает текущее соединение в соответствии с параметром ConnectionAsgmtMode |
| override [DefaultPort](../../aspose.email.clients.pop3/pop3client/defaultport) { get; } | Получает порт по умолчанию для клиента |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Получает или устанавливает значение, которое позволяет включить/отключить регистратор |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Получает или задает время ожидания приветствия, которое используется при установлении соединения. Обратите внимание, время ожидания приветствия не может быть бесконечным. Почтовые клиенты могут выполнять достаточно длительные операции. Для ограничения времени операций пользователям необходимо использовать свойство[`Timeout`](../../aspose.email.clients/emailclient/timeout). Значения этого свойства должны иметь длинные интервалы, чтобы не препятствовать длительным операциям. Но в некоторых случаях, если EmailClient будет использовать только свойство Timeout, установление соединения может занять много времени. Например, почтовый клиент может использовать автоматический режим установления соединения. В этом режиме почтовый клиент перебирает все возможные параметры подключения, пока соединение не будет установлено. Серверы SMTP, IMAP и POP3 в случае корректного установления соединения отправляют клиенту строку приветствия. Серверы могут использовать неявную или явную (START TLS) инициацию соединения SSL/TLS. Если режим соединения не соответствует (например, сервер ожидает неявного SSL-соединения, но клиент пытается установить незащищенное или явное SSL-соединение), сервер выиграл не отправлять строку приветствия. В этом случае пользователь будет долго ждать, пока таймаут достигнет строки приветствия, и клиент перейдет к следующему варианту подключения. Чтобы избежать этой проблемы, было введено свойство GreetingTimeout. Это свойство позволяет установить таймаут для строки приветствия и уменьшить время автоматического установления соединения. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Получает или задает имя хоста. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Получает или задает имя файла журнала |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Получает или задает пароль. Ограничения пароля определяются реализацией сервера, к которому подключается клиент. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Получает или задает порт. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Получает или устанавливает прокси для клиента |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Режим безопасности для почтового клиента |
| [SupportedAuthentication](../../aspose.email.clients.pop3/pop3client/supportedauthentication) { get; } | Получает перечисление поддерживаемых сервером типов аутентификации |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Определяет используемые версии протоколов шифрования SSL/TLS. ОБРАЩАЕМ ВНИМАНИЕ, вы можете устанавливать только те версии протокола, которые поддерживаются .net framework. ЕСЛИ НЕКОТОРЫЕ ВЕРСИИ ПРОТОКОЛА НЕ ПОДДЕРЖИВАЮТСЯ ВАШЕЙ ТЕКУЩЕЙ ВЕРСИЕЙ .NET FRAMEWORK, ОНИ БУДУТ ИГНОРИРОВАТЬСЯ И ПРОПУСКАТЬСЯ. ЭТО МОЖЕТ ПРИВЕСТИ К ПОНИЖЕНИЮ УРОВНЯ БЕЗОПАСНОСТИ TLS. В ЭТОМ СЛУЧАЕ ИСКЛЮЧЕНИЕ НЕ БУДЕТ СОЗДАНО!!! Пожалуйста, смотрите[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols)документацию для более подробной информации. Пожалуйста, используйте метод[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)если вы хотите установить протоколы шифрования без каких-либо проверки совместимости. Значение по умолчанию:Tls &#x7C; Тлс11 &#x7C; Тлс12 &#x7C; Tls13 (в случае, если ваша текущая версия .net framework поддерживает эти версии TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Получает или устанавливает время ожидания для почтовых операций |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Получает или задает TokenProvider, позволяющий получить токен доступа. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Указывает, используется ли аутентификация. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Получает или задает значение, указывающее, следует ли использовать дату в имени файла журнала. |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials) { get; set; } | Получает или задает логическое значение, которое определяет, отправляются ли DefaultCredentials с запросами. Эта опция используется ТОЛЬКО с аутентификацией NTLM! |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Получает или задает значение, указывающее, должен ли клиент использовать несколько подключений для тяжелых операций. Обратите внимание, использование этого режима не обязательно должно привести к увеличению производительности. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Получает или задает объект, указывающий, включен ли режим конвейерной обработки. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Получает или задает имя пользователя. |

## Методы

| Имя | Описание |
| --- | --- |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes)() | Зафиксировать удаление |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_1)(IConnection) | Зафиксировать удаление |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_2)(int) | Зафиксировать удаление |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync)() | Зафиксировать удаление |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_5)(CancellationToken) | Зафиксировать удаление |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_1)(IConnection) | Зафиксировать удаление |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_3)(int) | Зафиксировать удаление |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_2)(IConnection, CancellationToken) | Зафиксировать удаление |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_4)(int, CancellationToken) | Зафиксировать удаление |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Создает новое независимое соединение для операций, не связанных с потоками (не соединение по умолчанию). Вызов этого метода аналогичен вызову CreateConnection(createAsDefaultConnection = false) Подробнее см. в документации по свойству EmailClient.ConnectionAsgmtMode. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Создает новое (по умолчанию или независимое) соединение для операций. Подробнее см. в документации по свойству EmailClient.ConnectionAsgmtMode. |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_2)(int) | Удаляет сообщение |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_3)(string) | Удаляет сообщение |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage)(IConnection, int) | Удаляет сообщение |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_1)(IConnection, string) | Удаляет сообщение |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_4)(int) | Удаляет сообщение |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_6)(string) | Удаляет сообщение |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync)(IConnection, int) | Удаляет сообщение |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_2)(IConnection, string) | Удаляет сообщение |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_5)(int, CancellationToken) | Удаляет сообщение |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_7)(string, CancellationToken) | Удаляет сообщение |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_1)(IConnection, int, CancellationToken) | Удаляет сообщение |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_3)(IConnection, string, CancellationToken) | Удаляет сообщение |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages)() | Удаляет все сообщения |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages_1)(IConnection) | Удаляет все сообщения |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync)() | Удаляет все сообщения |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_3)(CancellationToken) | Удаляет все сообщения |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_1)(IConnection) | Удаляет все сообщения |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_2)(IConnection, CancellationToken) | Удаляет все сообщения |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Завершает все операции с сервером. |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_2)(int) | Получает сообщение |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_3)(string) | Получает сообщение |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage)(IConnection, int) | Получает сообщение |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_1)(IConnection, string) | Получает сообщение |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_4)(int) | Получает сообщение |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_6)(string) | Получает сообщение |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync)(IConnection, int) | Получает сообщение |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_2)(IConnection, string) | Получает сообщение |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_5)(int, CancellationToken) | Получает сообщение |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_7)(string, CancellationToken) | Получает сообщение |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_1)(IConnection, int, CancellationToken) | Получает сообщение |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_3)(IConnection, string, CancellationToken) | Получает сообщение |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_2)(IEnumerable&lt;int&gt;) | Выбирает сообщения |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_3)(IEnumerable&lt;string&gt;) | Получает сообщения |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | Получает сообщения |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_1)(IConnection, IEnumerable&lt;string&gt;) | Получает сообщения |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_4)(IEnumerable&lt;int&gt;) | Выбирает сообщения асинхронно |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_6)(IEnumerable&lt;string&gt;) | Выбирает сообщения асинхронно |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | Асинхронно получает сообщения |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_2)(IConnection, IEnumerable&lt;string&gt;) | Асинхронно получает сообщения |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_5)(IEnumerable&lt;int&gt;, CancellationToken) | Выбирает сообщения асинхронно |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_7)(IEnumerable&lt;string&gt;, CancellationToken) | Выбирает сообщения асинхронно |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_1)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Асинхронно получает сообщения |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_3)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Асинхронно получает сообщения |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo)() | Получает информацию о состоянии почтового ящика |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_3)(bool) | Получает информацию о статусе почтового ящика |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_1)(IConnection) | Получает информацию о состоянии почтового ящика |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_2)(IConnection, bool) | Получает информацию о состоянии почтового ящика |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync)() | Получает информацию о состоянии почтового ящика |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_5)(bool) | Получает информацию о статусе почтового ящика |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_7)(CancellationToken) | Получает информацию о состоянии почтового ящика |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_1)(IConnection) | Получает информацию о состоянии почтового ящика |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_6)(bool, CancellationToken) | Получает информацию о статусе почтового ящика |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_2)(IConnection, bool) | Получает информацию о состоянии почтового ящика |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_4)(IConnection, CancellationToken) | Получает информацию о состоянии почтового ящика |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_3)(IConnection, bool, CancellationToken) | Получает информацию о состоянии почтового ящика |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize)() | Получает размер почтового ящика |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize_1)(IConnection) | Получает размер почтового ящика |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync)() | Получает размер почтового ящика |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_3)(CancellationToken) | Получает размер почтового ящика |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_1)(IConnection) | Получает размер почтового ящика |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_2)(IConnection, CancellationToken) | Получает размер почтового ящика |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount)() | Получает количество сообщений |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_3)(bool) | Получает количество сообщений |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_1)(IConnection) | Получает количество сообщений |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_2)(IConnection, bool) | Получает количество сообщений |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync)() | Получает количество сообщений |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_5)(bool) | Получает количество сообщений |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_7)(CancellationToken) | Получает количество сообщений |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_1)(IConnection) | Получает количество сообщений |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_6)(bool, CancellationToken) | Получает количество сообщений |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_2)(IConnection, bool) | Получает количество сообщений |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_4)(IConnection, CancellationToken) | Получает количество сообщений |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_3)(IConnection, bool, CancellationToken) | Получает количество сообщений |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_2)(int) | Получает заголовки сообщения |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_3)(string) | Получает заголовки сообщения |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders)(IConnection, int) | Получает заголовки сообщения |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_1)(IConnection, string) | Получает заголовки сообщения |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_4)(int) | Получает заголовки сообщения |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_6)(string) | Получает заголовки сообщения |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync)(IConnection, int) | Получает заголовки сообщения |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_2)(IConnection, string) | Получает заголовки сообщения |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_5)(int, CancellationToken) | Получает заголовки сообщения |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_7)(string, CancellationToken) | Получает заголовки сообщения |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_1)(IConnection, int, CancellationToken) | Получает заголовки сообщения |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_3)(IConnection, string, CancellationToken) | Получает заголовки сообщения |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_4)(int) | Получает информацию для этого сообщения |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_6)(string) | Получает информацию для этого сообщения |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo)(IConnection, int) | Получает информацию для этого сообщения |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_2)(IConnection, string) | Получает информацию для этого сообщения |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_5)(int, Pop3ListFields) | Получает информацию для этого сообщения |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_7)(string, Pop3ListFields) | Получает информацию для этого сообщения |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_1)(IConnection, int, Pop3ListFields) | Получает информацию для этого сообщения |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_3)(IConnection, string, Pop3ListFields) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_8)(int) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_12)(string) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync)(IConnection, int) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_4)(IConnection, string) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_11)(int, CancellationToken) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_9)(int, Pop3ListFields) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_15)(string, CancellationToken) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_13)(string, Pop3ListFields) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_3)(IConnection, int, CancellationToken) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_1)(IConnection, int, Pop3ListFields) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_7)(IConnection, string, CancellationToken) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_5)(IConnection, string, Pop3ListFields) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_10)(int, Pop3ListFields, CancellationToken) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_14)(string, Pop3ListFields, CancellationToken) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_2)(IConnection, int, Pop3ListFields, CancellationToken) | Получает информацию для этого сообщения |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_6)(IConnection, string, Pop3ListFields, CancellationToken) | Получает информацию для этого сообщения |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_2)(int) | Получает размер сообщения |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_3)(string) | Получает размер сообщения |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize)(IConnection, int) | Получает размер сообщения |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_1)(IConnection, string) | Получает размер сообщения |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_4)(int) | Получает размер сообщения |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_6)(string) | Получает размер сообщения |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync)(IConnection, int) | Получает размер сообщения |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_2)(IConnection, string) | Получает размер сообщения |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_5)(int, CancellationToken) | Получает размер сообщения |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_7)(string, CancellationToken) | Получает размер сообщения |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_1)(IConnection, int, CancellationToken) | Получает размер сообщения |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_3)(IConnection, string, CancellationToken) | Получает размер сообщения |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid_1)(int) | Получает уникальный идентификатор сообщения |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid)(IConnection, int) | Получает уникальный идентификатор сообщения |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_2)(int) | Получает уникальный идентификатор сообщения |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync)(IConnection, int) | Получает уникальный идентификатор сообщения |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_3)(int, CancellationToken) | Получает уникальный идентификатор сообщения |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_1)(IConnection, int, CancellationToken) | Получает уникальный идентификатор сообщения |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages)() | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_11)(bool) | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_1)(IConnection) | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_12)(IEnumerable&lt;int&gt;) | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_13)(IEnumerable&lt;string&gt;) | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_10)(MailQuery) | Список сообщений. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_8)(Pop3ListFields) | Список сообщений. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_5)(IConnection, bool) | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_6)(IConnection, IEnumerable&lt;int&gt;) | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_7)(IConnection, IEnumerable&lt;string&gt;) | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_4)(IConnection, MailQuery) | Список сообщений. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_2)(IConnection, Pop3ListFields) | Список сообщений. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_9)(Pop3ListFields, bool, MailQuery) | Список сообщений. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_3)(IConnection, Pop3ListFields, bool, MailQuery) | Список сообщений. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync)() | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_17)(bool) | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_19)(CancellationToken) | Список сообщений. Получает информацию для сообщения поиска |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_1)(IConnection) | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_15)(MailQuery) | Список сообщений. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_11)(Pop3ListFields) | Список сообщений. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_18)(bool, CancellationToken) | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_8)(IConnection, bool) | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_10)(IConnection, CancellationToken) | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_6)(IConnection, MailQuery) | Список сообщений. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_2)(IConnection, Pop3ListFields) | Список сообщений. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_16)(MailQuery, CancellationToken) | Список сообщений. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_14)(Pop3ListFields, CancellationToken) | Список сообщений. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_9)(IConnection, bool, CancellationToken) | Список сообщений. Получает информацию для поискового сообщения |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_7)(IConnection, MailQuery, CancellationToken) | Список сообщений. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_5)(IConnection, Pop3ListFields, CancellationToken) | Список сообщений. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_12)(Pop3ListFields, bool, MailQuery) | Список сообщений. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_3)(IConnection, Pop3ListFields, bool, MailQuery) | Список сообщений. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_13)(Pop3ListFields, bool, MailQuery, CancellationToken) | Список сообщений. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_4)(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) | Список сообщений. |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_3)(IEnumerable&lt;int&gt;) | Загружает список Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_2)(IEnumerable&lt;Pop3MessageInfo&gt;) | Загружает список Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_1)(IConnection, IEnumerable&lt;int&gt;) | Загружает список Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Загружает список Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_7)(IEnumerable&lt;int&gt;) | Загружает список Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_5)(IEnumerable&lt;Pop3MessageInfo&gt;) | Загружает список Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_4)(Pop3LoadMessageInfoList) | Загружает список Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_2)(IConnection, IEnumerable&lt;int&gt;) | Загружает список Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Загружает список Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_8)(IEnumerable&lt;int&gt;, CancellationToken) | Загружает список Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_6)(IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Загружает список Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_3)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Загружает список Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_1)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Загружает список Pop3MessageInfo |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop)() | Команда "Нет операции" |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop_1)(IConnection) | Команда "Нет операции" |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync)() | Команда "Нет операции" |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_3)(CancellationToken) | Команда 'Нет операции' |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_1)(IConnection) | Команда "Нет операции" |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_2)(IConnection, CancellationToken) | Команда "Нет операции" |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Сбрасывает настройки ведения журнала по умолчанию. |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_4)(int, Stream) | Выбирает и сохраняет сообщение как поток |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_5)(int, string) | Выбирает и сохраняет сообщение в файл |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_6)(string, Stream) | Выбирает и сохраняет сообщение как поток |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_7)(string, string) | Выбирает и сохраняет сообщение в файл |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage)(IConnection, int, Stream) | Выбирает и сохраняет сообщение как поток |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_1)(IConnection, int, string) | Выбирает и сохраняет сообщение в файл |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_2)(IConnection, string, Stream) | Выбирает и сохраняет сообщение как поток |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_3)(IConnection, string, string) | Выбирает и сохраняет сообщение в файл |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_8)(int, Stream) | Выбирает и сохраняет сообщение как поток |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_10)(int, string) | Выбирает и сохраняет сообщение в файл |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_12)(string, Stream) | Выбирает и сохраняет сообщение как поток |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_14)(string, string) | Выбирает и сохраняет сообщение в файл |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync)(IConnection, int, Stream) | Выбирает и сохраняет сообщение как поток |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_2)(IConnection, int, string) | Выбирает и сохраняет сообщение в файл |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_4)(IConnection, string, Stream) | Выбирает и сохраняет сообщение как поток |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_6)(IConnection, string, string) | Выбирает и сохраняет сообщение в файл |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_9)(int, Stream, CancellationToken) | Выбирает и сохраняет сообщение как поток |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_11)(int, string, CancellationToken) | Выбирает и сохраняет сообщение в файл |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_13)(string, Stream, CancellationToken) | Выбирает и сохраняет сообщение как поток |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_15)(string, string, CancellationToken) | Выбирает и сохраняет сообщение в файл |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_1)(IConnection, int, Stream, CancellationToken) | Выбирает и сохраняет сообщение как поток |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_3)(IConnection, int, string, CancellationToken) | Выбирает и сохраняет сообщение в файл |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_5)(IConnection, string, Stream, CancellationToken) | Выбирает и сохраняет сообщение как поток |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_7)(IConnection, string, string, CancellationToken) | Выбирает и сохраняет сообщение в файл |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Определяет используемые версии протоколов шифрования SSL/TLS. Этот метод не является безопасным и устанавливает протоколы шифрования без каких-либо проверок совместимости. Используйте свойство[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption)для безопасной установки только тех протоколов, которые определенно поддерживаются .net framework. Обратите внимание, если ваш текущий .net framework не поддерживает этот уровень безопасности, при попытке установить соединение с сервером будет выброшено исключение. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages)() | Восстанавливает сообщения. Если какие-либо сообщения были помечены сервером POP3 как удаленные, они не помечаются. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages_1)(IConnection) | Восстанавливает сообщения. Если какие-либо сообщения были помечены сервером POP3 как удаленные, они не помечаются. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync)() | Восстанавливает сообщения. Если какие-либо сообщения были помечены сервером POP3 как удаленные, они не помечаются. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_3)(CancellationToken) | Восстанавливает сообщения. Если какие-либо сообщения были помечены сервером POP3 как удаленные, они не помечаются. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_1)(IConnection) | Восстанавливает сообщения. Если какие-либо сообщения были помечены сервером POP3 как удаленные, они не помечаются. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_2)(IConnection, CancellationToken) | Восстанавливает сообщения. Если какие-либо сообщения были помечены сервером POP3 как удаленные, они не помечаются. |
| override [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials)() | Выполняет проверку учетных данных |
| [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials_1)(IConnection) | Выполняет проверку учетных данных |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync)() | Выполняет проверку учетных данных |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Выполняет проверку учетных данных |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Выполняет проверку учетных данных |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Выполняет проверку учетных данных |
| static [CreateAsync](../../aspose.email.clients.pop3/pop3client/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Создает новый экземпляр класса[`Pop3Client`](../pop3client) |

### Смотрите также

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncPop3Client](../iasyncpop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
