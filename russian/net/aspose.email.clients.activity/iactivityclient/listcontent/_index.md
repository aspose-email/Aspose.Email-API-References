---
title: ListContent
second_title: Справочник по Aspose.Email для .NET API
description: Эта операция выводит список содержимого доступного в настоящее время для извлечения для указанного типа содержимого. Контент представляет собой совокупность действий и событий собранных с нескольких серверов в нескольких центрах обработки данных. Контент будет указан в том порядке в котором агрегации становятся доступными  но не гарантируется что события и действия в агрегациях будут последовательными. По умолчанию если startTime и endTime опущены возвращается контент доступный за последние 24 часа.
type: docs
weight: 80
url: /ru/net/aspose.email.clients.activity/iactivityclient/listcontent/
---
## ListContent(string) {#listcontent}

Эта операция выводит список содержимого, доступного в настоящее время для извлечения для указанного типа содержимого. Контент представляет собой совокупность действий и событий, собранных с нескольких серверов в нескольких центрах обработки данных. Контент будет указан в том порядке, в котором агрегации становятся доступными, , но не гарантируется, что события и действия в агрегациях будут последовательными. По умолчанию, если startTime и endTime опущены, возвращается контент, доступный за последние 24 часа.

```csharp
public ContentInfo[] ListContent(string contentType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| contentType | String | Указывает тип содержимого. |

### Возвращаемое значение

Список доступной информации об активности

### Смотрите также

* class [ContentInfo](../../contentinfo)
* interface [IActivityClient](../../iactivityclient)
* пространство имен [Aspose.Email.Clients.Activity](../../iactivityclient)
* сборка [Aspose.Email](../../../)

---

## ListContent(string, DateTime?, DateTime?) {#listcontent_1}

Эта операция выводит список содержимого, доступного в настоящее время для извлечения для указанного типа содержимого. Контент представляет собой совокупность действий и событий, собранных с нескольких серверов в нескольких центрах обработки данных. Контент будет указан в том порядке, в котором агрегации становятся доступными, , но не гарантируется, что события и действия в агрегациях будут последовательными.

```csharp
public ContentInfo[] ListContent(string contentType, DateTime? startTime, DateTime? endTime)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| contentType | String | Указывает тип содержимого. |
| startTime | Nullable`1 | Необязательное значение даты и времени (UTC), указывающее временной диапазон возвращаемого содержимого в зависимости от того, когда содержимое стало доступным. Диапазон времени включает время startTime (startTime меньше или равно contentCreated), , чтобы можно было использовать неперекрывающиеся возрастающие временные интервалы для просмотра доступного контента. Оба (startTime и endTime) должны быть указаны (или оба опущены). ). Диапазон времени не должен превышать 24 часа, а время начала должно быть не более 7 дней назад. |
| endTime | Nullable`1 | Необязательное значение даты и времени (UTC), указывающее временной диапазон возвращаемого содержимого в зависимости от того, когда содержимое стало доступным. Диапазон времени является исключительным по отношению к endTime (contentCreated минус endTime), , так что неперекрывающиеся возрастающие временные интервалы могут использоваться для просмотра доступного содержимого. Оба (startTime и endTime) должны быть указаны (или оба опущены) Диапазон времени не должен превышать 24 часов, при этом время начала должно быть не более 7 дней назад. |

### Возвращаемое значение

Список доступной информации об активности

### Смотрите также

* class [ContentInfo](../../contentinfo)
* interface [IActivityClient](../../iactivityclient)
* пространство имен [Aspose.Email.Clients.Activity](../../iactivityclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
