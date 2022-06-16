---
title: Appointment
second_title: Справочник по Aspose.Email для .NET API
description: Представляет календарь электронной почте.
type: docs
weight: 430
url: /ru/net/aspose.email.calendar/appointment/
---
## Appointment class

Представляет календарь электронной почте.

```csharp
public class Appointment
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Appointment](appointment#constructor)(string, DateTime, DateTime, MailAddress, MailAddressCollection) | Инициализировать новый экземпляр класса[`Appointment`](../appointment). |
| [Appointment](appointment#constructor_1)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection) | Инициализировать новый экземпляр класса[`Appointment`](../appointment). |
| [Appointment](appointment#constructor_2)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, RecurrencePattern) | Инициализировать новый экземпляр класса[`Appointment`](../appointment). |
| [Appointment](appointment#constructor_3)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string) | Инициализировать новый экземпляр класса[`Appointment`](../appointment). |
| [Appointment](appointment#constructor_4)(string, string, string, DateTime, DateTime, MailAddress, MailAddressCollection, string, RecurrencePattern) | Инициализировать новый экземпляр класса[`Appointment`](../appointment). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Attachments](../../aspose.email.calendar/appointment/attachments) { get; } | Получает коллекцию вложений встречи. |
| [Attendees](../../aspose.email.calendar/appointment/attendees) { get; set; } | Получает или задает участников. |
| [Class](../../aspose.email.calendar/appointment/class) { get; set; } | Указывает классификацию доступа для встречи. |
| [CreatedDate](../../aspose.email.calendar/appointment/createddate) { get; set; } | Получает или задает дату и время создания данных календаря. |
| [Description](../../aspose.email.calendar/appointment/description) { get; set; } | Получает или задает описание. |
| [EndDate](../../aspose.email.calendar/appointment/enddate) { get; set; } | Получает или задает дату окончания. |
| [EndTimeZone](../../aspose.email.calendar/appointment/endtimezone) { get; set; } | Конечный часовой пояс |
| [Flags](../../aspose.email.calendar/appointment/flags) { get; set; } | Получает или устанавливает флаги встречи. |
| [HtmlDescription](../../aspose.email.calendar/appointment/htmldescription) { get; set; } | Получает или задает HTML-представление описания. |
| [LastModifiedDate](../../aspose.email.calendar/appointment/lastmodifieddate) { get; set; } | Получает или задает дату и время последнего изменения данных календаря. |
| [Location](../../aspose.email.calendar/appointment/location) { get; set; } | Получает или задает местоположение. |
| [MethodType](../../aspose.email.calendar/appointment/methodtype) { get; set; } | Получает или задает тип метода объекта iCalendar, связанный с объектом календаря. |
| [MicrosoftBusyStatus](../../aspose.email.calendar/appointment/microsoftbusystatus) { get; set; } | Указывает статус встречи «ЗАНЯТ». |
| [MicrosoftImportance](../../aspose.email.calendar/appointment/microsoftimportance) { get; set; } | Указывает важность встречи. |
| [MicrosoftIntendedStatus](../../aspose.email.calendar/appointment/microsoftintendedstatus) { get; set; } | Определяет НАМЕРЕННЫЙ статус встречи. |
| [OptionalAttendees](../../aspose.email.calendar/appointment/optionalattendees) { get; } | Получает необязательных участников. |
| [Organizer](../../aspose.email.calendar/appointment/organizer) { get; set; } | Получает или задает органайзер. |
| [Recurrence](../../aspose.email.calendar/appointment/recurrence) { get; set; } | Получает или задает шаблон повторения. |
| [Reminders](../../aspose.email.calendar/appointment/reminders) { get; } | Содержит коллекцию объектов AppointmentReminder[`AppointmentReminder`](../appointmentreminder). |
| [SequenceId](../../aspose.email.calendar/appointment/sequenceid) { get; } | Получает идентификатор последовательности. |
| [StartDate](../../aspose.email.calendar/appointment/startdate) { get; set; } | Получает или задает начальную дату. |
| [StartTimeZone](../../aspose.email.calendar/appointment/starttimezone) { get; set; } | Начальный часовой пояс |
| [Status](../../aspose.email.calendar/appointment/status) { get; set; } | Получает или задает общий статус или подтверждение для объекта. |
| [Summary](../../aspose.email.calendar/appointment/summary) { get; set; } | Получает или задает сводку. |
| [Transparency](../../aspose.email.calendar/appointment/transparency) { get; set; } | Указывает, должна ли эта встреча отображаться при поиске доступности. |
| [UniqueId](../../aspose.email.calendar/appointment/uniqueid) { get; set; } | Получает или задает строковое значение, содержащее GUID элемента календаря. В MS Exchange это свойство карты PidLidGlobalObjectId. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Load](../../aspose.email.calendar/appointment/load#load)(Stream) | Загружает[`Appointment`](../appointment)из потока |
| static [Load](../../aspose.email.calendar/appointment/load#load_3)(string) | Загружает[`Appointment`](../appointment)из файла. Поддерживаемые форматы файлов:iCalendar |
| static [Load](../../aspose.email.calendar/appointment/load#load_1)(Stream, AppointmentLoadOptions) | Загружает[`Appointment`](../appointment)из потока |
| static [Load](../../aspose.email.calendar/appointment/load#load_2)(Stream, bool) | Загружает[`Appointment`](../appointment)из потока |
| static [Load](../../aspose.email.calendar/appointment/load#load_4)(string, AppointmentLoadOptions) | Загружает[`Appointment`](../appointment)из файла. Поддерживаемые форматы файлов:iCalendar  Путь к файлу. Представляет параметры загрузки встречи[`AppointmentLoadOptions`](../appointmentloadoptions). A read[`Appointment`](../appointment). |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment)() | Отменяет встречу. |
| [CancelAppointment](../../aspose.email.calendar/appointment/cancelappointment#cancelappointment_1)(int) | Отменяет встречу. |
| [GetAppointmentHtml](../../aspose.email.calendar/appointment/getappointmenthtml)() | Получает HTML-код календаря. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext)() | Получает текст календаря. |
| [GetAppointmentText](../../aspose.email.calendar/appointment/getappointmenttext#getappointmenttext_1)(AppointmentFormattingOptions) | Получает текст календаря. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment)() | Запрашивает встречу. |
| [RequestApointment](../../aspose.email.calendar/appointment/requestapointment#requestapointment_1)(int) | Запрашивает встречу. |
| [ResetTimeZone](../../aspose.email.calendar/appointment/resettimezone)() | Установить местный часовой пояс |
| [Save](../../aspose.email.calendar/appointment/save#save)(Stream) | Сохраняет встречу в файл формата iCalendar, используя параметры сохранения по умолчанию |
| [Save](../../aspose.email.calendar/appointment/save#save_3)(string) | Сохраняет встречу в файл формата iCalendar, используя параметры сохранения по умолчанию |
| [Save](../../aspose.email.calendar/appointment/save#save_1)(Stream, AppointmentSaveFormat) | Сохраняет встречу в потоке в указанном формате, используя параметры сохранения по умолчанию |
| [Save](../../aspose.email.calendar/appointment/save#save_2)(Stream, AppointmentSaveOptions) | Сохраняет встречу в потоке с указанными параметрами сохранения |
| [Save](../../aspose.email.calendar/appointment/save#save_4)(string, AppointmentSaveFormat) | Сохраняет встречу в файл в указанном формате, используя параметры сохранения по умолчанию |
| [Save](../../aspose.email.calendar/appointment/save#save_5)(string, AppointmentSaveOptions) | Сохраняет встречу в файл с указанными параметрами сохранения |
| [SetTimeZone](../../aspose.email.calendar/appointment/settimezone)(string) | Установить часовой пояс |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment)() | Обновляет встречу. |
| [UpdateAppointment](../../aspose.email.calendar/appointment/updateappointment#updateappointment_1)(int) | Обновляет встречу. |

### Примеры

В этом примере показано, как добавить календарь в сообщение электронной почты.

[C#]

```csharp
MailMessage msg = new MailMessage();

//участники event
MailAddressCollection attendees = new MailAddressCollection();
attendees.Add(new MailAddress("person1@domain.com"));
attendees.Add(new MailAddress("person2@domain.com"));
attendees.Add(new MailAddress("person3@domain.com"));

 //создать встречу
Appointment app = new Appointment("Room 112",new DateTime(2006,7,17,13,0,0),new DateTime(2006,7,17,14,0,0),new MailAddress("somebody@domain.com"), attendees );
cal.Summary = "Release Meetting";
cal.Description = "Discuss for the next release";

 //добавляем календарь в message
msg.AddAlternateView(app.RequestApointment());

 //отправить электронное письмо message
SmtpClient smtp= new SmtpClient("smtp.server.com", 25, "user", "password");
smtp.Send(msg);
```

[Visual Basic]

```csharp
Dim msg As MailMessage = New MailMessage()

'посетители события
 attendees As MailAddressCollection =  New MailAddressCollection()
attendees.Add(New MailAddress("person1@domain.com"))
attendees.Add(New MailAddress("person2@domain.com"))
attendees.Add(New MailAddress("person3@domain.com"))

'создать календарь
Dim cal As Appointment =  New Appointment("Room 112",New DateTime(2006,7,17,13,0,0),New DateTime(2006,7,17,14,0,0),New MailAddress("somebody@domain.com"),attendees)
cal.Summary = "Release Meetting"
cal.Description = "Discuss for the next release"

'добавляем календарь в сообщение
msg.AddAlternateView(app.RequestApointment())
```

### Смотрите также

* пространство имен [Aspose.Email.Calendar](../../aspose.email.calendar)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
