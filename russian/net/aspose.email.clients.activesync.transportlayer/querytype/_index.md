---
title: QueryType
second_title: Справочник по Aspose.Email для .NET API
description: Указывает ключевые слова используемые для сопоставления записей в искомом хранилище. Значение запроса используется в качестве шаблона сопоставления строки префикса и возвращает записи соответствующие началу строки. Например поиск Джон будет соответствовать Джон Фрум или Барри Джонсон но не будет соответствовать Джеймс Литтлджон. Все непустые текстовые свойства в глобальном списке адресов индексированные с помощью ANR сравниваются с элементом Query. ценность. Поисковые сравнения выполняются с использованием сопоставления без учета регистра. Для поиска в библиотеке документов Windows SharePoint Services этот протокол поддерживает запросы в следующей форме LinkId  значение где значение указывает URL-адрес элемента или папки а LinkId указывает что значение должно сравниваться со свойством идентификатора ссылки. Синтаксис запроса для поиска в почтовом ящике следующий - Папки могут быть указаны следующими способами Входящие и подпапки Исходящие и Отправленные  базовый запрос по ключевому слову может состоять из следующих элементов Базовый оператор И раздел 2.2.3.10 Фильтр даты и времени заданный с помощью GreaterThan раздел 2.2.3.78 и LessThan элементы раздел 2.2.3.87 Элементы FreeText раздел 2.2.3.73 содержащие ключевые слова Базовый запрос ключевых слов выполняется для всех индексированных свойств.
type: docs
weight: 1780
url: /ru/net/aspose.email.clients.activesync.transportlayer/querytype/
---
## QueryType class

Указывает ключевые слова, используемые для сопоставления записей в искомом хранилище. Значение запроса используется в качестве шаблона сопоставления строки префикса и возвращает записи, соответствующие началу строки. Например, поиск «Джон» будет соответствовать «Джон Фрум» или «Барри Джонсон», но не будет соответствовать «Джеймс Литтлджон». Все непустые текстовые свойства в глобальном списке адресов, индексированные с помощью ANR, сравниваются с элементом Query. ценность. Поисковые сравнения выполняются с использованием сопоставления без учета регистра. Для поиска в библиотеке документов Windows SharePoint Services этот протокол поддерживает запросы в следующей форме: LinkId == значение, где значение указывает URL-адрес элемента или папки, а LinkId указывает что значение должно сравниваться со свойством идентификатора ссылки. Синтаксис запроса для поиска в почтовом ящике следующий: - Папки могут быть указаны следующими способами: Входящие и подпапки, Исходящие и Отправленные — базовый запрос по ключевому слову может состоять из следующих элементов: Базовый оператор: И (раздел 2.2.3.10) Фильтр даты и времени, заданный с помощью GreaterThan (раздел 2.2.3.78) и LessThan элементы (раздел 2.2.3.87) Элементы FreeText (раздел 2.2.3.73), содержащие ключевые слова Базовый запрос ключевых слов выполняется для всех индексированных свойств.

```csharp
public class QueryType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [QueryType](querytype)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/querytype/class) { get; } | Идентифицирует класс элемента. Допустимые значения элемента airsync:Class: - Tasks - Email - Calendar - Contacts - Notes - SMS Следующие классы поддерживаются для поиска в почтовых ящиках при версии протокола 12.1: Email, Calendar, Контакты, Задачи. Классы SMS и Notes доступны только при версии протокола 14.0 или 14.1. Запрос на поиск может включать один или несколько элементов Class в запросе, чтобы ограничить тип данных, включенных в ответ на поиск. Если один или несколько элементов класса не включены в поисковый запрос, сервер вернет все поддерживаемые классы. (SearchTooComplex). |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/querytype/collectionid) { get; } | Указывает папку для поиска. Если DeepTraversal присутствует, он применяется ко всем папкам под каждым CollectionId. Если CollectionId включен в качестве дочернего элемента любого элемента, кроме And, сервер отвечает значением состояния 8 (SearchTooComplex). |
| [ConversationId](../../aspose.email.clients.activesync.transportlayer/querytype/conversationid) { get; set; } | Определяет цепочку для поиска. Значением является GUID. ConversationId не поддерживается при версии протокола 12.1. Если ConversationId включен в качестве дочернего элемента любого элемента, кроме элемента And, сервер отвечает значением состояния 8 (SearchTooComplex). |
| [FreeText](../../aspose.email.clients.activesync.transportlayer/querytype/freetext) { get; set; } | Указывает строковое значение для поиска. Если для свойства FreeText задано значение, отличное от свойства And, сервер отвечает значением состояния 8 (SearchTooComplex). |
| [GreaterThan](../../aspose.email.clients.activesync.transportlayer/querytype/greaterthan) { get; set; } | Определяет свойство и значение, которые сравниваются для условия «Больше чем» во время поиска. |
| [LessThan](../../aspose.email.clients.activesync.transportlayer/querytype/lessthan) { get; set; } | Указывает свойство и значение, которые сравниваются для условия «Меньше чем» во время поиска. |

### Смотрите также

* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
