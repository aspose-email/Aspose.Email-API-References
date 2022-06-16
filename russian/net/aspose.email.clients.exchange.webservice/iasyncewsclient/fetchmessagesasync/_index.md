---
title: FetchMessagesAsync
second_title: Справочник по Aspose.Email для .NET API
description: Выбирает указанные сообщения.
type: docs
weight: 270
url: /ru/net/aspose.email.clients.exchange.webservice/iasyncewsclient/fetchmessagesasync/
---
## IAsyncEwsClient.FetchMessagesAsync method

Выбирает указанные сообщения.

```csharp
public Task<MailMessageCollection> FetchMessagesAsync(IEnumerable<string> uris, 
    IEnumerable<PropertyDescriptor> extendedProperties = null, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uris | IEnumerable`1 | AIEnumerableсодержащий Uris сообщения получено |
| extendedProperties | IEnumerable`1 | Перечисление расширенных свойств |
| cancellationToken | CancellationToken | Маркер отмены. |

### Возвращаемое значение

A[`MailMessageCollection`](../../../aspose.email/mailmessagecollection)содержащий извлеченные сообщения

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *uris*is` null` |

### Смотрите также

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->