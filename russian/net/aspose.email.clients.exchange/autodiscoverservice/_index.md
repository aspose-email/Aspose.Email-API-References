---
title: AutodiscoverService
second_title: Справочник по Aspose.Email для .NET API
description: Представляет привязку к службе автообнаружения Exchange.
type: docs
weight: 3090
url: /ru/net/aspose.email.clients.exchange/autodiscoverservice/
---
## AutodiscoverService class

Представляет привязку к службе автообнаружения Exchange.

```csharp
public sealed class AutodiscoverService : AutodiscoverServiceBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AutodiscoverService](autodiscoverservice#constructor)() | Инициализирует новый экземпляр[`AutodiscoverService`](../autodiscoverservice) класс. |
| [AutodiscoverService](autodiscoverservice#constructor_1)(ExchangeVersion) | Инициализирует новый экземпляр[`AutodiscoverService`](../autodiscoverservice) класс. |
| [AutodiscoverService](autodiscoverservice#constructor_2)(string) | Инициализирует новый экземпляр[`AutodiscoverService`](../autodiscoverservice) класс. |
| [AutodiscoverService](autodiscoverservice#constructor_4)(Uri) | Инициализирует новый экземпляр[`AutodiscoverService`](../autodiscoverservice) класс. |
| [AutodiscoverService](autodiscoverservice#constructor_3)(string, ExchangeVersion) | Инициализирует новый экземпляр[`AutodiscoverService`](../autodiscoverservice) класс. |
| [AutodiscoverService](autodiscoverservice#constructor_5)(Uri, ExchangeVersion) | Инициализирует новый экземпляр[`AutodiscoverService`](../autodiscoverservice) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AcceptGzipEncoding](../../aspose.email.clients.exchange/autodiscoverservicebase/acceptgzipencoding) { get; set; } | Получает или задает значение, указывающее, следует ли принимать кодирование со сжатием GZip. |
| [ClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/clientrequestid) { get; set; } | Получает или задает идентификатор запроса для запроса. |
| [ConnectionGroupName](../../aspose.email.clients.exchange/autodiscoverservicebase/connectiongroupname) { get; set; } | Получает или задает имя группы подключения для запроса. |
| [CookieContainer](../../aspose.email.clients.exchange/autodiscoverservicebase/cookiecontainer) { get; set; } | Получает или задает контейнер cookie. |
| [Credentials](../../aspose.email.clients.exchange/autodiscoverservicebase/credentials) { get; set; } | Получает или задает учетные данные, используемые для аутентификации в веб-службах Exchange. Установка Credentials property автоматически устанавливает для UseDefaultCredentials значение false. |
| [Domain](../../aspose.email.clients.exchange/autodiscoverservice/domain) { get; set; } | Получает или задает домен, к которому привязана эта служба. Если установлено это свойство, имя domain используется для автоматического определения URL-адреса службы автообнаружения. |
| [EnableScpLookup](../../aspose.email.clients.exchange/autodiscoverservice/enablescplookup) { get; set; } | Получает или задает значение, указывающее, должна ли служба AutodiscoverService выполнять поиск записи SCP (ServiceConnectionPoint) при определении URL-адреса службы автообнаружения. |
| [HttpHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpheaders) { get; } | Получает коллекцию заголовков HTTP, которые будут отправляться с каждым запросом к EWS. |
| [HttpResponseHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpresponseheaders) { get; } | Получает коллекцию заголовков HTTP из последнего ответа. |
| [IsExternal](../../aspose.email.clients.exchange/autodiscoverservice/isexternal) { get; } | Получает значение, указывающее, является ли служба автообнаружения, на которую указывает URL-адрес, внутренней (внутри корпоративной сети) или внешней (вне корпоративной сети). |
| [KeepAlive](../../aspose.email.clients.exchange/autodiscoverservicebase/keepalive) { get; set; } | Возвращает или задает, должен ли запрос к интернет-ресурсу содержать HTTP-заголовок Connection со значением Keep-alive |
| [LogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/logfilename) { get; set; } | Получает или задает имя файла журнала |
| [PreAuthenticate](../../aspose.email.clients.exchange/autodiscoverservicebase/preauthenticate) { get; set; } | Получает или задает значение, указывающее, следует ли выполнять предварительную аутентификацию HTTP. |
| [RedirectionUrlValidationCallback](../../aspose.email.clients.exchange/autodiscoverservice/redirectionurlvalidationcallback) { get; set; } | Получает или задает обратный вызов проверки URL-адреса перенаправления. |
| [RequestedServerVersion](../../aspose.email.clients.exchange/autodiscoverservicebase/requestedserverversion) { get; } | Получает запрошенную версию сервера. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/returnclientrequestid) { get; set; } | Получает или устанавливает флаг, указывающий, требует ли клиент, чтобы сторона сервера возвращала идентификатор запроса. |
| [SendClientLatencies](../../aspose.email.clients.exchange/autodiscoverservicebase/sendclientlatencies) { get; set; } | Получает или задает значение, указывающее, передается ли информация о задержке клиента на сервер. |
| [ServerInfo](../../aspose.email.clients.exchange/autodiscoverservicebase/serverinfo) { get; } | Получает информацию, связанную с сервером, обработавшим последний запрос. Будет нулевым, если запросы не были обработаны. |
| [Timeout](../../aspose.email.clients.exchange/autodiscoverservicebase/timeout) { get; set; } | Получает или задает время ожидания, используемое при отправке HTTP-запросов и при получении HTTP-ответов, в миллисекундах. По умолчанию 100000. |
| [Url](../../aspose.email.clients.exchange/autodiscoverservice/url) { get; set; } | Получает или задает URL-адрес, к которому привязана эта служба. |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/usedateinlogfilename) { get; set; } | Получает или задает значение, указывающее, следует ли использовать дату в имени файла журнала. |
| [UseDefaultCredentials](../../aspose.email.clients.exchange/autodiscoverservicebase/usedefaultcredentials) { get; set; } | Получает или задает значение, указывающее, следует ли использовать учетные данные пользователя, выполнившего вход в Windows, для аутентификации в веб-службах Exchange. Установка для UseDefaultCredentials значения true автоматически устанавливает для свойства Credentials значение null. |
| [UserAgent](../../aspose.email.clients.exchange/autodiscoverservicebase/useragent) { get; set; } | Получает или задает пользовательский агент. |
| [WebProxy](../../aspose.email.clients.exchange/autodiscoverservicebase/webproxy) { get; set; } | Получает или задает веб-прокси, который следует использовать при отправке запросов на EWS. Установите для этого свойства значение null, чтобы использовать веб-прокси по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetUserSettings](../../aspose.email.clients.exchange/autodiscoverservice/getusersettings)(string, params UserSettingName[]) | Извлекает указанные параметры для одного SMTP-адреса. |
| [GetUsersSettings](../../aspose.email.clients.exchange/autodiscoverservice/getuserssettings)(IEnumerable&lt;string&gt;, params UserSettingName[]) | Извлекает указанные параметры для набора пользователей. |

### Смотрите также

* class [AutodiscoverServiceBase](../autodiscoverservicebase)
* пространство имен [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
