---
title: ListMessagesByPageAsync
second_title: Справочник по Aspose.Email для .NET API
description: Список сообщений в указанной папке.
type: docs
weight: 460
url: /ru/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listmessagesbypageasync/
---
## ListMessagesByPageAsync(string, int, int, MailQuery, CancellationToken) {#listmessagesbypageasync_1}

Список сообщений в указанной папке.

```csharp
public Task<ExchangeMessagePageInfo> ListMessagesByPageAsync(string folder, int itemsPerPage, 
    int offset = 0, MailQuery query = null, CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений. |
| itemsPerPage | Int32 | Количество элементов на странице |
| offset | Int32 | Смещение следующей страницы в поле зрения |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет критерии поиска. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)который содержит сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesByPageAsync(string, PageInfo, CancellationToken) {#listmessagesbypageasync}

Список сообщений в указанной папке.

```csharp
public Task<ExchangeMessagePageInfo> ListMessagesByPageAsync(string folder, PageInfo pageInfo, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений. |
| pageInfo | PageInfo | Информация о странице |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)который содержит сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
