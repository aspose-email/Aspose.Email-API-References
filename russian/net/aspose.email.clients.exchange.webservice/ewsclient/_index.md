---
title: EWSClient
second_title: Справочник по Aspose.Email для .NET API
description: Предоставляет доступ к серверу MS Exchange с помощью веб-служб Exchange EWS.
type: docs
weight: 3680
url: /ru/net/aspose.email.clients.exchange.webservice/ewsclient/
---
## EWSClient class

Предоставляет доступ к серверу MS Exchange с помощью веб-служб Exchange (EWS).

```csharp
public abstract class EWSClient : ExchangeClientBase
```

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | Получает или устанавливает учетные данные |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | Получает или задает имя файла журнала |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | Получает или задает почтовый ящик uri |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | Получает или задает прокси. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | Получает или задает количество миллисекунд ожидания до истечения времени ожидания операции. Значение по умолчанию — 100 000 миллисекунд (100 секунд). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | Получает или задает значение, указывающее, следует ли использовать дату в имени файла журнала. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | Выполняет определяемые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_2)(string, ICredentials) | Инициализирует новый экземпляр[`EWSClient`](../ewsclient) на основе class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_3)(string, ICredentials, WebProxy) | Инициализирует новый экземпляр[`EWSClient`](../ewsclient) на основе class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_4)(string, string, string) | Инициализирует новый экземпляр[`EWSClient`](../ewsclient) на основе class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_1)(ExchangeVersion, string, ICredentials, WebProxy) | Инициализирует новый экземпляр[`EWSClient`](../ewsclient) на основе class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_6)(string, string, string, string) | Инициализирует новый экземпляр[`EWSClient`](../ewsclient) на основе class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_5)(string, string, string, WebProxy) | Инициализирует новый экземпляр[`EWSClient`](../ewsclient) на основе class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_7)(string, string, string, string, WebProxy) | Инициализирует новый экземпляр[`EWSClient`](../ewsclient) на основе class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient)(ExchangeVersion, bool, string, string, ICredentials, WebProxy) | Инициализирует новый экземпляр[`EWSClient`](../ewsclient) на основе class |
| static [GetEwsClientAsync](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclientasync)(string, ICredentials, WebProxy, CancellationToken) | Инициализирует новый экземпляр[`EWSClient`](../ewsclient) на основе class |

### Смотрите также

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
