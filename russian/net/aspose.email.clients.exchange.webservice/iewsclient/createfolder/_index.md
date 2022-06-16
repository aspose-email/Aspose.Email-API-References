---
title: CreateFolder
second_title: Справочник по Aspose.Email для .NET API
description: Создает новую папку с указанным именем в указанной родительской папке.
type: docs
weight: 500
url: /ru/net/aspose.email.clients.exchange.webservice/iewsclient/createfolder/
---
## CreateFolder(string, string) {#createfolder_2}

Создает новую папку с указанным именем в указанной родительской папке.

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| parentFolderUri | String | URI родительской папки. |
| name | String | Имя создаваемой папки. |

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri*или*name*is` null` или` пустой` . |

### Смотрите также

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection) {#createfolder_3}

Создает новую папку

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| parentFolderUri | String | URI родительской папки |
| name | String | Имя новой папки |
| permissions | ExchangeFolderPermissionCollection | Разрешение на новую папку |

### Возвращаемое значение

Возвращает информацию о папке

### Смотрите также

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection, string) {#createfolder_4}

Создает новую папку

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions, string folderClass)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| parentFolderUri | String | URI родительской папки |
| name | String | Имя новой папки |
| permissions | ExchangeFolderPermissionCollection | Разрешение на новую папку |
| folderClass | String | Класс новой папки |

### Возвращаемое значение

Возвращает информацию о папке

### Смотрите также

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## CreateFolder(string, ExchangeFolderType) {#createfolder_1}

Создает новую папку в корневой папке.

```csharp
public ExchangeFolderInfo CreateFolder(string name, ExchangeFolderType folderType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя новой папки |
| folderType | ExchangeFolderType | Тип folder |

### Возвращаемое значение

Возвращает информацию о папке

### Смотрите также

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderType) {#createfolder_5}

Создает новую папку

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderType folderType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| parentFolderUri | String | URI родительской папки |
| name | String | Имя новой папки |
| folderType | ExchangeFolderType | Тип папки |

### Возвращаемое значение

Возвращает информацию о папке

### Смотрите также

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## CreateFolder(string) {#createfolder}

Создает новую папку в корневой папке.

```csharp
public ExchangeFolderInfo CreateFolder(string name)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя новой папки |

### Возвращаемое значение

Возвращает информацию о папке

### Смотрите также

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
