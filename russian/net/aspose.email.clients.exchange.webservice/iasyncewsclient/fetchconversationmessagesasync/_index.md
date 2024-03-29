---
title: FetchConversationMessagesAsync
second_title: Справочник по Aspose.Email для .NET API
description: Извлекает указанные сообщения беседы
type: docs
weight: 240
url: /ru/net/aspose.email.clients.exchange.webservice/iasyncewsclient/fetchconversationmessagesasync/
---
## IAsyncEwsClient.FetchConversationMessagesAsync method

Извлекает указанные сообщения беседы

```csharp
public Task<MailMessageCollection> FetchConversationMessagesAsync(string conversationId, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| conversationId | String | Идентификатор разговора |
| cancellationToken | CancellationToken | Токен отмены. |

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *conversationId* является`нулевой`или же`пустой` |

### Смотрите также

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
