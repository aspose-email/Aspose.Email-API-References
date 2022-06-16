---
title: ActiveSyncTLClient
second_title: Справочник по Aspose.Email для .NET API
description: Базовый класс для клиентских реализаций ActiveSync
type: docs
weight: 950
url: /ru/net/aspose.email.clients.activesync.transportlayer/activesynctlclient/
---
## ActiveSyncTLClient class

Базовый класс для клиентских реализаций ActiveSync

```csharp
public class ActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [AuthenticationType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/authenticationtype) { get; set; } | Получает или задает тип аутентификации, используемый клиентом ActiveSync. |
| virtual [AutodiscoverUri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscoveruri) { get; set; } | Получает или задает uri службы автообнаружения |
| virtual [Credentials](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/credentials) { get; } | Учетные данные пользователя для сервера Exchange |
| virtual [DeviceID](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/deviceid) { get; set; } | GUID, идентифицирующий устройство. Идентификатор устройства задается частью правила ABNF спецификации идентификатора устройства значения простого текстового запроса. Значение, представленное правилом ABNF идентификатора устройства, представляет собой строку, указывающую устройство. Каждое устройство ДОЛЖНО иметь уникальную строку идентификатора устройства. Каждый запрос от устройства ДОЛЖЕН включать одну и ту же строку идентификатора устройства. |
| virtual [DeviceType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/devicetype) { get; set; } | Тип устройства определяется частью правила ABNF спецификации типа устройства в значении простого текстового запроса. Значение, представленное правилом ABNF типа устройства, представляет собой любую строку, указывающую тип устройства. "SP" указывает SmartPhone, а "PPC" указывает PocketPC. Другие клиентские устройства отправляют уникальные строки для своего конкретного типа устройства. Каждый запрос от клиентского устройства ДОЛЖЕН включать одну и ту же строку типа устройства. |
| virtual [PolicyState](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/policystate) { get; set; } | Целое число без знака, указывающее состояние параметров политики на клиентском устройстве, как указано в разделе 2.2.2.41 [MS-ASPROV]. |
| virtual [Proxy](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/proxy) { get; set; } | Получает или задает прокси. |
| virtual [SupportedServerCommands](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedservercommands) { get; } | Получает поддерживаемые версии команд ActiveSync |
| virtual [SupportedServerProtocols](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedserverprotocols) { get; } | Получает поддерживаемые версии протоколов ActiveSync |
| virtual [Timeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/timeout) { get; set; } | Получает или задает количество миллисекунд ожидания до истечения времени ожидания операции. Значение по умолчанию — 100 000 миллисекунд (100 секунд). |
| virtual [Uri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/uri) { get; } | Получает URL службы ActiveSync |
| virtual [UserAgent](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/useragent) { get; set; } | Поле заголовка запроса User-Agent содержит информацию о пользовательском агенте, инициирующем запрос. Это для статистических целей, отслеживания нарушений протокола и автоматического распознавания пользовательских агентов с целью адаптации ответов, чтобы избежать конкретных ограничений пользовательских агентов. Пользовательские агенты ДОЛЖНЫ включать это поле в запросы. Поле может содержать несколько токенов продукта (раздел 3.8) и комментарии идентифицирующие агент и любые подпродукты, которые составляют значительную часть пользовательского агента. По соглашению токены продукта перечислены в порядке их значимости для идентификации приложения. Пример: User-Agent:CERN-LineMode/2.15 libwww/2.17b3 |
| virtual [Version](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/version) { get; } | Получает версию протокола, который используется в клиенте ActiveSync. |
| static [DefaultTimeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/defaulttimeout) { get; set; } | Получает или задает значение времени ожидания по умолчанию для экземпляров клиента ActiveSync Значение по умолчанию — 100 000 миллисекунд (100 секунд). |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string) | Команда Autodiscover облегчает обнаружение информации о конфигурации основной учетной записи, используя SMTP-адрес пользователя в качестве основного ввода. |
| [Dispose](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/dispose)() | Выполняет задачи, связанные с освобождением, освобождением или сбросом неуправляемых ресурсов. |
| static [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string, NetworkCredential, string) | Команда Autodiscover облегчает обнаружение информации о конфигурации основной учетной записи, используя SMTP-адрес пользователя в качестве основного ввода. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance)(string, NetworkCredential) | Получает экземпляр клиента ActiveSync Версия протокола ActiveSync выбирается автоматически в соответствии с ответом сервера. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance_1)(string, NetworkCredential, ASProtocolVersions) | Получает экземпляр клиента ActiveSync |
| static [GetOptions](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getoptions)(string, NetworkCredential, out string[], out string[]) | Статический метод GetOptions используется для определения того, какие версии протокола поддерживаются и какие команды протокола поддерживаются на сервере. Клиент использует статический метод GetOptions, чтобы определить, поддерживает ли сервер те же версии протокола, что и клиент. |

### Смотрите также

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
