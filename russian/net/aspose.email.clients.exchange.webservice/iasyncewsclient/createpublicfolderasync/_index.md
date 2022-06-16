---
title: CreatePublicFolderAsync
second_title: Справочник по Aspose.Email для .NET API
description: Создает указанную общую папку в корневой общей папке
type: docs
weight: 130
url: /ru/net/aspose.email.clients.exchange.webservice/iasyncewsclient/createpublicfolderasync/
---
## CreatePublicFolderAsync(string, ExchangeFolderPermissionCollection, ExchangeFolderType, string, CancellationToken) {#createpublicfolderasync}

Создает указанную общую папку в корневой общей папке

```csharp
public Task<ExchangeFolderInfo> CreatePublicFolderAsync(string name, 
    ExchangeFolderPermissionCollection permissions, ExchangeFolderType folderType, 
    string parentFolderUri = null, CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя новой папки |
| permissions | ExchangeFolderPermissionCollection | Разрешение на новую папку |
| folderType | ExchangeFolderType | Тип папки |
| parentFolderUri | String | URI родительской папки |
| cancellationToken | CancellationToken | Маркер отмены. |

### Возвращаемое значение

Возвращает информацию о папке

### Смотрите также

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* сборка [Aspose.Email](../../../)

---

## CreatePublicFolderAsync(string, ExchangeFolderPermissionCollection, string, CancellationToken) {#createpublicfolderasync_1}

Создает указанную общую папку в корневой общей папке

```csharp
public Task<ExchangeFolderInfo> CreatePublicFolderAsync(string name, 
    ExchangeFolderPermissionCollection permissions, string parentFolderUri = null, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя новой папки |
| permissions | ExchangeFolderPermissionCollection | Разрешение на новую папку |
| parentFolderUri | String | URI родителя folder |
| cancellationToken | CancellationToken | Маркер отмены. |

### Возвращаемое значение

Возвращает информацию о папке

### Смотрите также

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->