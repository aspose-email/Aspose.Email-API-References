---
title: ExtendedCalendar
second_title: Справочник по Aspose.Email для .NET API
description: Инициализирует новый экземпляр класса ExtendedCalendar.
type: docs
weight: 10
url: /ru/net/aspose.email.clients.google/extendedcalendar/extendedcalendar/
---
## ExtendedCalendar() {#constructor}

Инициализирует новый экземпляр класса ExtendedCalendar.

```csharp
public ExtendedCalendar()
```

### Смотрите также

* class [ExtendedCalendar](../../extendedcalendar)
* пространство имен [Aspose.Email.Clients.Google](../../extendedcalendar)
* сборка [Aspose.Email](../../../)

---

## ExtendedCalendar(string) {#constructor_1}

Инициализирует новый экземпляр класса ExtendedCalendar.

```csharp
public ExtendedCalendar(string summary)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| summary | String | Название календаря. |

### Смотрите также

* class [ExtendedCalendar](../../extendedcalendar)
* пространство имен [Aspose.Email.Clients.Google](../../extendedcalendar)
* сборка [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string) {#constructor_2}

Инициализирует новый экземпляр класса ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string summary)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | String | Идентификатор ресурса. |
| summary | String | Название календаря. |

### Смотрите также

* class [ExtendedCalendar](../../extendedcalendar)
* пространство имен [Aspose.Email.Clients.Google](../../extendedcalendar)
* сборка [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string) {#constructor_3}

Инициализирует новый экземпляр класса ExtendedCalendar.

```csharp
public ExtendedCalendar(string summary, string description, string location, string timeZone)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| summary | String | Название календаря. |
| description | String | Описание календаря. |
| location | String | Географическое положение календаря в виде текста произвольной формы. |
| timeZone | String | Часовой пояс календаря. |

### Смотрите также

* class [ExtendedCalendar](../../extendedcalendar)
* пространство имен [Aspose.Email.Clients.Google](../../extendedcalendar)
* сборка [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string) {#constructor_4}

Инициализирует новый экземпляр класса ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | String | Идентификатор ресурса. |
| summary | String | Название календаря. |
| description | String | Описание календаря. |
| location | String | Географическое положение календаря в виде текста произвольной формы. |
| timeZone | String | Часовой пояс календаря. |

### Смотрите также

* class [ExtendedCalendar](../../extendedcalendar)
* пространство имен [Aspose.Email.Clients.Google](../../extendedcalendar)
* сборка [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_5}

Инициализирует новый экземпляр класса ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone, string summaryOverride, string colorId, string backgroundColor, 
    string foregroundColor, bool hidden, bool selected, AccessRole accessRole, 
    KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | String | Идентификатор ресурса. |
| summary | String | Название календаря. |
| description | String | Описание календаря. |
| location | String | Географическое положение календаря в виде текста произвольной формы. |
| timeZone | String | Часовой пояс календаря. |
| summaryOverride | String | Сводка, которую аутентифицированный пользователь установил для этого календаря. |
| colorId | String | Цвет календаря. Это идентификатор, относящийся к записи в разделе «календарь» определения цветов (см. конечную точку «цвета»). |
| backgroundColor | String | Основной цвет календаря в формате '#0088aa'. Это свойство заменяет свойство colorId на основе индекса. |
| foregroundColor | String | Основной цвет календаря в формате '#ffffff'. Это свойство заменяет свойство colorId на основе индекса. |
| hidden | Boolean | Был ли календарь скрыт из списка. Значение по умолчанию — Ложь. |
| selected | Boolean | Отображается ли содержимое календаря в пользовательском интерфейсе календаря. Значение по умолчанию — Ложь. |
| accessRole | AccessRole | Действующая роль доступа, которую пользователь, прошедший проверку подлинности, имеет в календаре. Только для чтения. Возможные значения: |
| defaultReminders | KeyValuePair`2[] | Напоминания по умолчанию, которые есть у аутентифицированного пользователя для этого календаря. |
| primary | Boolean | Является ли календарь основным календарем аутентифицированного пользователя. Только для чтения. Значение по умолчанию — Ложь. |

### Смотрите также

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* пространство имен [Aspose.Email.Clients.Google](../../extendedcalendar)
* сборка [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_6}

Инициализирует новый экземпляр класса ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string eTag, string summary, string description, 
    string location, string timeZone, string summaryOverride, string colorId, 
    string backgroundColor, string foregroundColor, bool hidden, bool selected, 
    AccessRole accessRole, KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | String | Идентификатор ресурса. |
| eTag | String | Тег объекта |
| summary | String | Название календаря. |
| description | String | Описание календаря. |
| location | String | Географическое положение календаря в виде текста произвольной формы. |
| timeZone | String | Часовой пояс календаря. |
| summaryOverride | String | Сводка, которую аутентифицированный пользователь установил для этого календаря. |
| colorId | String | Цвет календаря. Это идентификатор, относящийся к записи в разделе «календарь» определения цветов (см. конечную точку «цвета»). |
| backgroundColor | String | Основной цвет календаря в формате '#0088aa'. Это свойство заменяет свойство colorId на основе индекса. |
| foregroundColor | String | Основной цвет календаря в формате '#ffffff'. Это свойство заменяет свойство colorId на основе индекса. |
| hidden | Boolean | Был ли календарь скрыт из списка. Значение по умолчанию — Ложь. |
| selected | Boolean | Отображается ли содержимое календаря в пользовательском интерфейсе календаря. Значение по умолчанию — Ложь. |
| accessRole | AccessRole | Действующая роль доступа, которую пользователь, прошедший проверку подлинности, имеет в календаре. Только для чтения. Возможные значения: |
| defaultReminders | KeyValuePair`2[] | Напоминания по умолчанию, которые есть у аутентифицированного пользователя для этого календаря. |
| primary | Boolean | Является ли календарь основным календарем аутентифицированного пользователя. Только для чтения. Значение по умолчанию — Ложь. |

### Смотрите также

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* пространство имен [Aspose.Email.Clients.Google](../../extendedcalendar)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
