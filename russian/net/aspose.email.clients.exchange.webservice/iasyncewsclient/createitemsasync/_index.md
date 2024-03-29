---
title: CreateItemsAsync
second_title: Справочник по Aspose.Email для .NET API
description: Создает указанные элементы в указанной папке
type: docs
weight: 120
url: /ru/net/aspose.email.clients.exchange.webservice/iasyncewsclient/createitemsasync/
---
## IAsyncEwsClient.CreateItemsAsync method

Создает указанные элементы в указанной папке

```csharp
public Task<IEnumerable<ExchangeUploadItemResult>> CreateItemsAsync(
    IEnumerable<ExchangeStreamedItem> items, string parentFolderUri, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| items | IEnumerable`1 | Элементы для загрузки |
| parentFolderUri | String | Указывает папку, в которую следует поместить элементы |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Массив[`ExchangeUploadItemResult`](../../exchangeuploaditemresult)

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *items* является`нулевой` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *items* является`пустой` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri* является`нулевой`или же`пустой` |

### Смотрите также

* class [ExchangeUploadItemResult](../../exchangeuploaditemresult)
* class [ExchangeStreamedItem](../../exchangestreameditem)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
