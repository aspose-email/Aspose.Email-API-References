---
title: DeleteFolderAsync
second_title: Справочник по Aspose.Email для .NET API
description: Удаляет папку
type: docs
weight: 160
url: /ru/net/aspose.email.clients.exchange.webservice/iasyncewsclient/deletefolderasync/
---
## IAsyncEwsClient.DeleteFolderAsync method

Удаляет папку

```csharp
public Task DeleteFolderAsync(string folderUri, bool deletePermanently = false, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderUri | String | URI папки |
| deletePermanently | Boolean | Указывает, следует ли удалить папку навсегда или ее следует переместить в папку DeletedItems |
| cancellationToken | CancellationToken | Токен отмены. |

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *folderUri* является`нулевой` или пустой |

### Смотрите также

* interface [IAsyncEwsClient](../../iasyncewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
