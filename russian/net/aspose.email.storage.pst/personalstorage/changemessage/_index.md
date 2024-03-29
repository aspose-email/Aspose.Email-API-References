---
title: ChangeMessage
second_title: Справочник по Aspose.Email для .NET API
description: Изменяет свойства сообщения.
type: docs
weight: 120
url: /ru/net/aspose.email.storage.pst/personalstorage/changemessage/
---
## PersonalStorage.ChangeMessage method

Изменяет свойства сообщения.

```csharp
public void ChangeMessage(string entryId, MapiPropertyCollection updatedProperties)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| entryId | String | Идентификатор записи сообщения. |
| updatedProperties | MapiPropertyCollection | Обновленные свойства. |

### Исключения

| исключение | условие |
| --- | --- |
| NotImplementedException | Редактирование версии файла ANSI не реализовано. |
| InvalidOperationException | PST открыт только для чтения. или Неверный идентификатор записи. |
| ArgumentNullException | entryIdCollection;Набор идентификаторов записей не может быть нулевым. or updatedProperties;Набор свойств не может быть нулевым. |

### Смотрите также

* class [MapiPropertyCollection](../../../aspose.email.mapi/mapipropertycollection)
* class [PersonalStorage](../../personalstorage)
* пространство имен [Aspose.Email.Storage.Pst](../../personalstorage)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
