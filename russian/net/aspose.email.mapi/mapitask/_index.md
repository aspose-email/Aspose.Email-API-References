---
title: MapiTask
second_title: Справочник по Aspose.Email для .NET API
description: Представляет объект задачи Outlook.
type: docs
weight: 18670
url: /ru/net/aspose.email.mapi/mapitask/
---
## MapiTask class

Представляет объект задачи Outlook.

```csharp
public class MapiTask : MapiMessageItemBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MapiTask](mapitask#constructor)() | Инициализирует новый экземпляр[`MapiTask`](../mapitask) класс. |
| [MapiTask](mapitask#constructor_1)(string, string, DateTime, DateTime) | Инициализирует новый экземпляр[`MapiTask`](../mapitask) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AcceptanceState](../../aspose.email.mapi/mapitask/acceptancestate) { get; set; } | Получает или задает состояние принятия задачи. |
| [ActualEffort](../../aspose.email.mapi/mapitask/actualeffort) { get; set; } | Получает или задает количество минут, которые пользователь действительно потратил на работу над задачей. |
| [Attachments](../../aspose.email.mapi/mapitask/attachments) { get; } | Получает коллекцию вложений. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Содержит платежную информацию, связанную с элементом. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Получает текст сообщения. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Получает[`BodyRtf`](../mapimessageitembase/bodyrtf) сообщения, преобразованного в HTML, если он присутствует, иначе пустая строка. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Получает или задает текст сообщения в формате RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Получает тип тела. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Содержит ключевые слова или категории для объекта сообщения. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Получает кодовую страницу. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Содержит названия компаний, связанных с элементом. |
| [DateCompleted](../../aspose.email.mapi/mapitask/datecompleted) { get; set; } | Получает или задает дату, когда пользователь завершил работу над задачей. |
| [DueDate](../../aspose.email.mapi/mapitask/duedate) { get; set; } | Получает или задает дату, к которой пользователь ожидает завершения работы над задачей. |
| [EstimatedEffort](../../aspose.email.mapi/mapitask/estimatedeffort) { get; set; } | Получает или задает количество минут , которое пользователь ожидает отработать над задачей. |
| [Flags](../../aspose.email.mapi/mapitask/flags) { get; } | Получает флаги индикации объекта Task. |
| [History](../../aspose.email.mapi/mapitask/history) { get; set; } | Получает или задает тип изменения , которое в последний раз было внесено в объект Task. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Идентификатор элемента, используется с server |
| [LastUpdate](../../aspose.email.mapi/mapitask/lastupdate) { get; set; } | Получает или задает дату и время самого последнего изменения , внесенного в объект Task. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Получает строку с учетом регистра, которая идентифицирует определенный отправителем класс сообщения, например IPM.Note. Класс сообщения определяет тип, цель или содержимое сообщения. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Содержит информацию о пробеге, связанном с элементом. |
| [Mode](../../aspose.email.mapi/mapitask/mode) { get; set; } | Получает или задает статус назначения объекта Task. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Получает именованные свойства сообщения. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Получает сопоставление именованного свойства. |
| [PercentComplete](../../aspose.email.mapi/mapitask/percentcomplete) { get; set; } | Получает или задает ход выполнения пользователем задачи. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Получает набор свойств. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Получает поток свойств. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Получает получателей сообщения. |
| [Recurrence](../../aspose.email.mapi/mapitask/recurrence) { get; set; } | Получает или задает свойства повторения. |
| [ReminderFileParameter](../../aspose.email.mapi/mapitask/reminderfileparameter) { get; set; } | Указывает полный путь к звуку, который клиент ДОЛЖЕН воспроизводить, когда напоминание просрочено. |
| [ReminderSet](../../aspose.email.mapi/mapitask/reminderset) { get; set; } | Получает или задает значение, указывающее, установлено ли напоминание для object |
| [ReminderTime](../../aspose.email.mapi/mapitask/remindertime) { get; set; } | Получает или задает начальное время сигнала для напоминания |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Получает чувствительность. |
| [StartDate](../../aspose.email.mapi/mapitask/startdate) { get; set; } | Получает или задает дату, когда пользователь ожидает начала работы над задачей. |
| [State](../../aspose.email.mapi/mapitask/state) { get; set; } | Получает или задает текущее состояние назначения объекта Task. |
| [Status](../../aspose.email.mapi/mapitask/status) { get; set; } | Получает или задает состояние выполнения пользователем задачи. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Получает или задает тему сообщения. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Получает префикс темы, который обычно указывает на какое-либо действие над сообщением, например "FW: " для пересылки. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Получает вспомогательные хранилища. |
| [Users](../../aspose.email.mapi/mapitask/users) { get; set; } | Получает или задает информацию о пользователях задачи. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo)(Stream) | Создает экземпляр MapiTask из указанного потока. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_2)(string) | Создает экземпляр MapiTask из указанного файла .ics. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_1)(Stream, bool) | Создает экземпляр MapiTask из указанного потока. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_3)(string, bool) | Создает экземпляр MapiTask из указанного файла .ics. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Выполняет определяемые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Получает свойство MAPI по дескриптору свойства. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Получает значение свойства, указанного тегом, в виде логического типа. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Получает строковое значение свойства, указанного тегом. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Получает значение свойства, указанного тегом как тип DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Получает значение int32 свойства, указанного тегом. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Получает значение свойства, указанного тегом, типа Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Получает значение свойства, указанного тегом, как тип Short. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Получает строковое значение свойства, указанного тегом. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Получает строковое значение свойства, указанного тегом. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Определяет, закодированы ли строковые свойства в Unicode или нет. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Обеспечивает корректное удаление свойства из всех коллекций. |
| [Save](../../aspose.email.mapi/mapitask/save#save)(Stream, TaskSaveFormat) | Сохраняет это[`MapiTask`](../mapitask) в данный поток, используя указанный формат. |
| [Save](../../aspose.email.mapi/mapitask/save#save_1)(string, TaskSaveFormat) | Сохраняет это[`MapiTask`](../mapitask) в файл, используя указанный формат. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Задает содержимое тела. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Задает содержимое тела. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Получает или задает текст сообщения в формате RTF. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Устанавливает флаги сообщения. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Задает свойство. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Задает свойство MAPI. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Попытаться получить данные свойства с указанным ключом тега. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Получает значение указанного свойства как тип DateTime. Возвращаемое значение указывает, успешно ли выполнена операция. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Получает значение указанного свойства как тип Int32. Возвращаемое значение указывает, успешно ли выполнена операция. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Получает значение указанного свойства как тип Long. Возвращаемое значение указывает, успешно ли выполнена операция. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Попытаться получить данные свойства в виде строки с указанным тегом. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Попытаться получить данные свойства в виде строки с указанным тегом и кодовой страницей. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Получает значение указанного свойства как тип String. Возвращаемое значение указывает, успешно ли выполнена операция. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Получает значение указанного свойства как тип String. Возвращаемое значение указывает, успешно ли выполнена операция. |

### Смотрите также

* class [MapiMessageItemBase](../mapimessageitembase)
* пространство имен [Aspose.Email.Mapi](../../aspose.email.mapi)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
