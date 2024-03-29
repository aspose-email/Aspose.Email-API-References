---
title: ListContactsAsync
second_title: Справочник по Aspose.Email для .NET API
description: Список контактов находящихся в указанной папке на сервере.
type: docs
weight: 420
url: /ru/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listcontactsasync/
---
## IAsyncEwsClient.ListContactsAsync method

Список контактов, находящихся в указанной папке на сервере.

```csharp
public Task<IEnumerable<MapiContact>> ListContactsAsync(string folderUri, 
    IEnumerable<PropertyDescriptor> mapiProperties = null, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderUri | String | Папка для поиска контактов. |
| mapiProperties | IEnumerable`1 | Необходимые дополнительные свойства карты. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Массив чтения[`MapiContact`](../../../aspose.email.mapi/mapicontact) который представляет контактную информацию.

### Смотрите также

* class [MapiContact](../../../aspose.email.mapi/mapicontact)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
