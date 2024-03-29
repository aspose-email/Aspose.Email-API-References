---
title: EmptyFolder
second_title: Справочник по Aspose.Email для .NET API
description: Очищает указанную папку. Подпапки не будут удалены удаленные элементы будут перемещены в папку DeletedItems
type: docs
weight: 680
url: /ru/net/aspose.email.clients.exchange.webservice/iewsclient/emptyfolder/
---
## EmptyFolder(string) {#emptyfolder}

Очищает указанную папку. Подпапки не будут удалены; удаленные элементы будут перемещены в папку DeletedItems

```csharp
public void EmptyFolder(string folderUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderUri | String | Указывает, что папка должна быть пустой |

### Исключения

| исключение | условие |
| --- | --- |
| [ExchangeException](../../../aspose.email/exchangeexception) | Не удалось выполнить операцию EmptyFolder |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *folderUri* является`нулевой`или же`пустой` |

### Смотрите также

* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## EmptyFolder(string, EmptyFolderOptions) {#emptyfolder_1}

Очищает указанную папку

```csharp
public void EmptyFolder(string folderUri, EmptyFolderOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderUri | String | Указывает, что папка должна быть пустой |
| options | EmptyFolderOptions | Указывает параметры очистки папки |

### Исключения

| исключение | условие |
| --- | --- |
| [ExchangeException](../../../aspose.email/exchangeexception) | Не удалось выполнить операцию EmptyFolder |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *folderUri* является`нулевой`или же`пустой` |

### Смотрите также

* enum [EmptyFolderOptions](../../emptyfolderoptions)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
