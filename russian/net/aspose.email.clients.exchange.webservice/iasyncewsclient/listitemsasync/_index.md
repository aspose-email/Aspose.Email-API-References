---
title: ListItemsAsync
second_title: Справочник по Aspose.Email для .NET API
description: Получить список URI элементов в указанной папке
type: docs
weight: 430
url: /ru/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listitemsasync/
---
## IAsyncEwsClient.ListItemsAsync method

Получить список URI элементов в указанной папке

```csharp
public Task<string[]> ListItemsAsync(string folder, string mailbox = null, MailQuery query = null, 
    bool recursive = false, CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | папка для поиска предметов |
| mailbox | String | Почтовый ящик, который используется для инициализации класса идентификатора папки. |
| query | MailQuery | Дополнительные условия для выбора товаров |
| recursive | Boolean | Указывает, должен ли запрос быть рекурсивным. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Возвращает список URI элементов

### Смотрите также

* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
