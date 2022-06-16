---
title: MapiCalendar
second_title: Справочник по Aspose.Email для .NET API
description: Представляет объект календаря mapi
type: docs
weight: 17910
url: /ru/net/aspose.email.mapi/mapicalendar/
---
## MapiCalendar class

Представляет объект календаря mapi

```csharp
public sealed class MapiCalendar : MapiMessageItemBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MapiCalendar](mapicalendar#constructor)() | Инициализирует новый экземпляр[`MapiCalendar`](../mapicalendar)class |
| [MapiCalendar](mapicalendar#constructor_1)(string, string, string, DateTime, DateTime) | Инициализирует новый экземпляр класса[`MapiCalendar`](../mapicalendar). |
| [MapiCalendar](mapicalendar#constructor_2)(string, string, string, DateTime, DateTime, MapiElectronicAddress, MapiRecipientCollection) | Инициализирует новый экземпляр класса[`MapiCalendar`](../mapicalendar). |
| [MapiCalendar](mapicalendar#constructor_3)(string, string, string, DateTime, DateTime, string, MapiRecipientCollection) | Инициализирует новый экземпляр класса[`MapiCalendar`](../mapicalendar). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AppointmentCounterProposal](../../aspose.email.mapi/mapicalendar/appointmentcounterproposal) { get; set; } | Получает или задает значение, указывающее, является ли объект ответа на собрание встречным предложением. |
| [Attachments](../../aspose.email.mapi/mapicalendar/attachments) { get; } | Получает коллекцию вложений. |
| [Attendees](../../aspose.email.mapi/mapicalendar/attendees) { get; set; } | Получает или задает участников |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Содержит платежную информацию, связанную с элементом. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Получает текст сообщения. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Получает[`BodyRtf`](../mapimessageitembase/bodyrtf)сообщения, преобразованного в HTML, если он присутствует, иначе пустая строка . |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Получает или задает текст сообщения в формате RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Получает тип тела. |
| [BusyStatus](../../aspose.email.mapi/mapicalendar/busystatus) { get; set; } | Получает или устанавливает статус занятости |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Содержит ключевые слова или категории для объекта сообщения. |
| [ClientIntent](../../aspose.email.mapi/mapicalendar/clientintent) { get; set; } | Получает или задает действия, предпринятые пользователем над этим объектом собрания. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Получает кодовую страницу. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Содержит названия компаний, связанных с элементом. |
| [EndDate](../../aspose.email.mapi/mapicalendar/enddate) { get; set; } | Получает или задает дату и время окончания события. Если дата не установлена, возвращается значение по умолчанию дляDateTime. |
| [EndDateTimeZone](../../aspose.email.mapi/mapicalendar/enddatetimezone) { get; set; } | Получает или задает информацию о часовом поясе, указывающую часовой пояс свойства EndDate |
| [IsAllDay](../../aspose.email.mapi/mapicalendar/isallday) { get; set; } | Получает или задает значение, указывающее, является ли событие событием на весь день |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Идентификатор элемента, используется с сервером |
| [KeyWords](../../aspose.email.mapi/mapicalendar/keywords) { get; set; } | Получает или задает категории объекта календаря |
| [Location](../../aspose.email.mapi/mapicalendar/location) { get; set; } | Получает или задает местоположение события |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Получает строку с учетом регистра, которая идентифицирует определенный отправителем класс сообщений, например IPM.Note. Класс сообщения определяет тип, цель или содержание сообщения. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Содержит информацию о пробеге, связанную с элементом. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Получает именованные свойства сообщения. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Получает сопоставление именованного свойства. |
| [Organizer](../../aspose.email.mapi/mapicalendar/organizer) { get; set; } | Получает или задает органайзер. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Получает коллекцию свойств. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Получает поток свойств. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Получает получателей сообщения. |
| [Recurrence](../../aspose.email.mapi/mapicalendar/recurrence) { get; set; } | Получает или задает свойства повторения |
| [ReminderDelta](../../aspose.email.mapi/mapicalendar/reminderdelta) { get; set; } | Получает или задает интервал в минутах между временем, когда напоминание впервые становится просроченным, и временем начала объекта Calendar |
| [ReminderFileParameter](../../aspose.email.mapi/mapicalendar/reminderfileparameter) { get; set; } | Указывает полный путь звука, который ДОЛЖЕН воспроизводить клиент, когда напоминание просрочено. |
| [ReminderSet](../../aspose.email.mapi/mapicalendar/reminderset) { get; set; } | Получает или задает значение, указывающее, установлено ли напоминание для объекта |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Получает чувствительность. |
| [Sequence](../../aspose.email.mapi/mapicalendar/sequence) { get; set; } | Получает или задает порядковый номер |
| [StartDate](../../aspose.email.mapi/mapicalendar/startdate) { get; set; } | Получает или задает дату и время начала события. Если дата не установлена, возвращается значение по умолчанию дляDateTime. |
| [StartDateTimeZone](../../aspose.email.mapi/mapicalendar/startdatetimezone) { get; set; } | Получает или задает информацию о часовом поясе, указывающую часовой пояс свойства StartDate |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Получает или задает тему сообщения. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Получает префикс темы, который обычно указывает на какое-либо действие над сообщением, например "FW:" для пересылки. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Получает вспомогательные хранилища. |
| [Uid](../../aspose.email.mapi/mapicalendar/uid) { get; set; } | Получает уникальный идентификатор |

## Методы

| Имя | Описание |
| --- | --- |
| override [Dispose](../../aspose.email.mapi/mapicalendar/dispose)() | Освобождает все ресурсы. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Получает свойство MAPI по дескриптору свойства. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Получает значение свойства, указанного тегом, как булев тип. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Получает строковое значение свойства, указанного тегом. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Получает значение свойства, указанного тегом, как тип DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Получает значение int32 свойства, указанного тегом. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Получает значение свойства, указанного тегом, типа Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Получает значение свойства, указанного тегом, типа Short. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Получает строковое значение свойства, указанного тегом. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Получает строковое значение свойства, указанного тегом. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Определяет, закодированы ли строковые свойства в Unicode или нет. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Обеспечивает корректное удаление свойства из всех коллекций. |
| [Save](../../aspose.email.mapi/mapicalendar/save#save)(Stream) | Сохраняет объект календаря в файл формата iCalendar, используя параметры сохранения по умолчанию |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_2)(string) | Сохраняет объект календаря в файл формата iCalendar, используя параметры сохранения по умолчанию |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_1)(Stream, AppointmentSaveFormat) | Сохраняет объект календаря в поток в указанном формате, используя параметры сохранения по умолчанию |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_3)(string, AppointmentSaveFormat) | Сохраняет объект календаря в файл с указанным форматом, используя параметры сохранения по умолчанию |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Устанавливает содержимое тела. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Устанавливает содержимое тела. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Получает или задает текст сообщения в формате RTF. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Устанавливает флаги сообщения. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Устанавливает свойство. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Устанавливает свойство MAPI. |
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
