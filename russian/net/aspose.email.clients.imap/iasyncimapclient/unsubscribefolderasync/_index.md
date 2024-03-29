---
title: UnsubscribeFolderAsync
second_title: Справочник по Aspose.Email для .NET API
description: Отправлена команда UNSUBSCRIBE которая удаляет указанное имя почтового ящика из набора активных почтовых ящиков сервера
type: docs
weight: 420
url: /ru/net/aspose.email.clients.imap/iasyncimapclient/unsubscribefolderasync/
---
## IAsyncImapClient.UnsubscribeFolderAsync method

Отправлена команда UNSUBSCRIBE, которая удаляет указанное имя почтового ящика из набора «активных» почтовых ящиков сервера

```csharp
public Task UnsubscribeFolderAsync(string folderName, IConnection connection = null, 
    CancellationToken token = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | String | Подключение к серверу |
| folderName | IConnection | Имя папки |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
