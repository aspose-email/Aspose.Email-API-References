---
title: ExtendedCalendar
second_title: Справочник по Aspose.Email для .NET API
description: Набор расширенных метаданных таких как цвета для одного календаря.
type: docs
weight: 15700
url: /ru/net/aspose.email.clients.google/extendedcalendar/
---
## ExtendedCalendar class

Набор расширенных метаданных, таких как цвета, для одного календаря.

```csharp
public class ExtendedCalendar : Calendar
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ExtendedCalendar](extendedcalendar#constructor)() | Инициализирует новый экземпляр класса ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_1)(string) | Инициализирует новый экземпляр класса ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_2)(string, string) | Инициализирует новый экземпляр класса ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_3)(string, string, string, string) | Инициализирует новый экземпляр класса ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_4)(string, string, string, string, string) | Инициализирует новый экземпляр класса ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_5)(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Инициализирует новый экземпляр класса ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_6)(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Инициализирует новый экземпляр класса ExtendedCalendar. |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [AccessRole](../../aspose.email.clients.google/extendedcalendar/accessrole) { get; } | Эффективная роль доступа, которую имеет аутентифицированный пользователь в календаре. Только для чтения. Возможные значения: |
| virtual [BackgroundColor](../../aspose.email.clients.google/extendedcalendar/backgroundcolor) { get; set; } | Основной цвет календаря в формате '#0088aa'. Это свойство заменяет свойство colorId на основе индекса. |
| virtual [ColorId](../../aspose.email.clients.google/extendedcalendar/colorid) { get; set; } | Цвет календаря. Это идентификатор, относящийся к записи в разделе «календарь» определения цветов (см. конечную точку «цвета»). |
| virtual [ConferenceProperties](../../aspose.email.clients.google/calendar/conferenceproperties) { get; } | Получает свойства конференции для этого календаря. |
| virtual [DefaultReminders](../../aspose.email.clients.google/extendedcalendar/defaultreminders) { get; set; } | Напоминания по умолчанию, которые есть у аутентифицированного пользователя для этого календаря. |
| virtual [Description](../../aspose.email.clients.google/calendar/description) { get; set; } | Описание календаря. |
| virtual [ETag](../../aspose.email.clients.google/basedataobject/etag) { get; set; } | ETag или тег объекта — это один из нескольких механизмов, которые HTTP предоставляет для проверки веб-кеша и который позволяет клиенту делать условные запросы. Это позволяет повысить эффективность кэшей и экономит пропускную способность, поскольку веб-серверу не нужно отправлять полный ответ, если содержимое не изменилось. ETag также можно использовать для управления оптимистичным параллелизмом, чтобы предотвратить одновременные обновления ресурса от перезаписи друг друга. |
| virtual [ForegroundColor](../../aspose.email.clients.google/extendedcalendar/foregroundcolor) { get; set; } | Цвет переднего плана календаря в формате '#ffffff'. Это свойство заменяет свойство colorId на основе индекса. |
| virtual [Hidden](../../aspose.email.clients.google/extendedcalendar/hidden) { get; set; } | Был ли календарь скрыт из списка. Значение по умолчанию — False. |
| virtual [Id](../../aspose.email.clients.google/basedataobject/id) { get; set; } | Идентификатор ресурса. |
| virtual [Kind](../../aspose.email.clients.google/basedataobject/kind) { get; } | Тип ресурса |
| virtual [Location](../../aspose.email.clients.google/calendar/location) { get; set; } | Географическое положение календаря в виде текста произвольной формы. |
| virtual [NotificationSettings](../../aspose.email.clients.google/extendedcalendar/notificationsettings) { get; set; } | Уведомления, которые пользователь, прошедший проверку подлинности, получает для этого календаря. |
| virtual [Primary](../../aspose.email.clients.google/extendedcalendar/primary) { get; set; } | Является ли календарь основным календарем аутентифицированного пользователя. Только для чтения. Значение по умолчанию — False. |
| virtual [Selected](../../aspose.email.clients.google/extendedcalendar/selected) { get; set; } | Отображается ли содержимое календаря в пользовательском интерфейсе календаря. Значение по умолчанию — False. |
| virtual [Summary](../../aspose.email.clients.google/calendar/summary) { get; set; } | Название календаря. |
| virtual [SummaryOverride](../../aspose.email.clients.google/extendedcalendar/summaryoverride) { get; set; } | Сводка, которую пользователь, прошедший проверку подлинности, установил для этого календаря. |
| virtual [TimeZone](../../aspose.email.clients.google/calendar/timezone) { get; set; } | Часовой пояс календаря. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ToString](../../aspose.email.clients.google/extendedcalendar/tostring)() | Возвращает строку, представляющую экземпляр объекта. |

## Поля

| Имя | Описание |
| --- | --- |
| const [ExtendedCalendarKind](../../aspose.email.clients.google/extendedcalendar/extendedcalendarkind) | Тип ресурса "calendar#calendarListEntry". |
| const [ListKind](../../aspose.email.clients.google/extendedcalendar/listkind) | Тип списка ресурсов "calendar#calendarList". |

### Смотрите также

* class [Calendar](../calendar)
* пространство имен [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
