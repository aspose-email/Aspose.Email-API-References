---
title: CopyConversationItemsAsync
second_title: Справочник по Aspose.Email для .NET API
description: Копирует элементы беседы находящиеся в указанной папке в указанную целевую папку
type: docs
weight: 70
url: /ru/net/aspose.email.clients.exchange.webservice/iasyncewsclient/copyconversationitemsasync/
---
## IAsyncEwsClient.CopyConversationItemsAsync method

Копирует элементы беседы, находящиеся в указанной папке, в указанную целевую папку

```csharp
public Task CopyConversationItemsAsync(string conversationId, string destinationFolderId, 
    string contextFolderId = null, CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| conversationId | String | Идентификатор беседы для копирования |
| destinationFolderId | String | Идентификатор папки, в которую копируются элементы |
| contextFolderId | String | Идентификатор папки, в которой находятся элементы беседы. Примечание. Если установлено значение null (или empty), все элементы беседы будут скопированы |
| cancellationToken | CancellationToken | Токен отмены. |

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *conversationId*is` null` или` пусто` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderId*is` null` или` пустой` |

### Смотрите также

* interface [IAsyncEwsClient](../../iasyncewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->