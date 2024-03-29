---
title: AddMessage
second_title: Справочник по Aspose.Email для .NET API
description: Добавляет новое сообщение в папку.
type: docs
weight: 150
url: /ru/net/aspose.email.storage.pst/folderinfo/addmessage/
---
## FolderInfo.AddMessage method

Добавляет новое сообщение в папку.

```csharp
public string AddMessage(MapiMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | MapiMessage | Сообщение необходимо добавить. |

### Возвращаемое значение

Строка, представляющая EntryId добавленного сообщения.

### Исключения

| исключение | условие |
| --- | --- |
| NotImplementedException | выдает, если версия PST-файла — ANSI. |
| ArgumentNullException | выдает, если добавляемое сообщение равно null. |
| InvalidOperationException | бросает, если PST открыт только для чтения. |

### Смотрите также

* class [MapiMessage](../../../aspose.email.mapi/mapimessage)
* class [FolderInfo](../../folderinfo)
* пространство имен [Aspose.Email.Storage.Pst](../../folderinfo)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
