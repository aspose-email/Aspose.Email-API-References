---
title: Appointment
second_title: Aspose.Email for Android via Java API Reference
description: Представляет календарь в электронном письме.
type: docs
weight: 26
url: /ru/androidjava/com.aspose.email/appointment/
---

**Inheritance:**
java.lang.Object
```
public class Appointment
```

Представляет календарь в электронном письме.

--------------------

> This example demonstrates how to add a calendar to an E-Mail message.
> 
> [Java]
> 
> ```
> MailMessage msg = new MailMessage();
> 
>      //attendees for the event
>      MailAddressCollection attendees = new MailAddressCollection();
>      attendees.add(new MailAddress("person1@domain.com"));
>      attendees.add(new MailAddress("person2@domain.com"));
>      attendees.add(new MailAddress("person3@domain.com"));
> 
>      //create appointment
>      Appointment app = new Appointment("Room 112",
>           new Date(2006,7,17,13,0,0), new Date(2006,7,17,14,0,0),
>           new MailAddress("somebody@domain.com"),
>           attendees );
>      app.setSummary("Release Meetting");
>      app.setDescription("Discuss for the next release");
> 
>      //add calendar to the message
>      msg.addAlternateView(app.requestApointment());
> ```
## Constructors

| Constructor | Описание |
| --- | --- |
| [Appointment(String location, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)](#Appointment-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-) | Инициализирует новый экземпляр класса [Appointment](../../com.aspose.email/appointment). |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-) | Инициализирует новый экземпляр класса [Appointment](../../com.aspose.email/appointment). |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-) | Инициализирует новый экземпляр класса [Appointment](../../com.aspose.email/appointment). |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, RecurrencePattern recurrencePattern)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-com.aspose.email.RecurrencePattern-) | Инициализирует новый экземпляр класса [Appointment](../../com.aspose.email/appointment). |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid, RecurrencePattern recurrencePattern)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-com.aspose.email.RecurrencePattern-) | Инициализирует новый экземпляр класса [Appointment](../../com.aspose.email/appointment). |
## Methods

| Method | Описание |
| --- | --- |
| [cancelAppointment()](#cancelAppointment--) | Отменяет встречу. |
| [cancelAppointment(int seqId)](#cancelAppointment-int-) | Отменяет встречу. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAppointmentClass()](#getAppointmentClass--) | Указывает классификацию доступа для встречи. |
| [getAppointmentHtml()](#getAppointmentHtml--) | Получает HTML календаря. |
| [getAppointmentText()](#getAppointmentText--) | Получает текст календаря. |
| [getAppointmentText(AppointmentFormattingOptions formattingOptions)](#getAppointmentText-com.aspose.email.AppointmentFormattingOptions-) | Получает текст календаря. |
| [getAttachments()](#getAttachments--) | Получает коллекцию вложений встречи. |
| [getAttendees()](#getAttendees--) | Получает или задает участников. |
| [getClass()](#getClass--) |  |
| [getCreatedDate()](#getCreatedDate--) | Получает или задаёт дату и время создания информации календаря. |
| [getDateTimeStamp()](#getDateTimeStamp--) | Получает или задает дату/время, когда был создан экземпляр объекта iCalendar.. |
| [getDescription()](#getDescription--) | Получает или задает описание. |
| [getEndDate()](#getEndDate--) | Получает или задает конечную дату. |
| [getEndTimeZone()](#getEndTimeZone--) | Конечный часовой пояс |
| [getFlags()](#getFlags--) | Получает или задает флаги встречи. |
| [getHtmlDescription()](#getHtmlDescription--) | Получает или задает HTML-представление описания. |
| [getLastModifiedDate()](#getLastModifiedDate--) | Получает или задает дату и время последнего изменения информации календаря. |
| [getLocation()](#getLocation--) | Получает или задает местоположение. |
| [getMethodType()](#getMethodType--) | Получает или задает тип метода объекта iCalendar, связанный с объектом календаря. |
| [getMicrosoftBusyStatus()](#getMicrosoftBusyStatus--) | Указывает статус BUSY (занят) встречи. |
| [getMicrosoftImportance()](#getMicrosoftImportance--) | Указывает важность встречи. |
| [getMicrosoftIntendedStatus()](#getMicrosoftIntendedStatus--) | Указывает статус INTENDED (предполагаемый) встречи. |
| [getOptionalAttendees()](#getOptionalAttendees--) | Получает необязательных участников. |
| [getOrganizer()](#getOrganizer--) | Получает или задает организатора. |
| [getRecurrence()](#getRecurrence--) | Получает или задает шаблон повторения. |
| [getReminders()](#getReminders--) | Содержит коллекцию объектов [AppointmentReminder](../../com.aspose.email/appointmentreminder). |
| [getSequenceId()](#getSequenceId--) | Получает идентификатор последовательности. |
| [getStartDate()](#getStartDate--) | Получает или задает дату начала. |
| [getStartTimeZone()](#getStartTimeZone--) | Начальный часовой пояс |
| [getStatus()](#getStatus--) | Получает или задает общий статус или подтверждение объекта. |
| [getSummary()](#getSummary--) | Получает или задает сводку. |
| [getTransparency()](#getTransparency--) | Указывает, должна ли эта встреча быть видна в поиске доступности. |
| [getUniqueId()](#getUniqueId--) | Получает или задает строковое значение, содержащее GUID элемента календаря. |
| [hashCode()](#hashCode--) |  |
| [isDescriptionHtml()](#isDescriptionHtml--) | Получает или задает значение, указывающее, находится ли описание в формате HTML. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Загружает [Appointment](../../com.aspose.email/appointment) из потока |
| [load(InputStream stream, boolean applyLocalTimeZone)](#load-java.io.InputStream-boolean-) | Загружает [Appointment](../../com.aspose.email/appointment) из потока |
| [load(InputStream stream, AppointmentLoadOptions options)](#load-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-) | Загружает [Appointment](../../com.aspose.email/appointment) из потока |
| [load(String filePath)](#load-java.lang.String-) | Загружает [Appointment](../../com.aspose.email/appointment) из файла. |
| [load(String filePath, AppointmentLoadOptions options)](#load-java.lang.String-com.aspose.email.AppointmentLoadOptions-) | Загружает [Appointment](../../com.aspose.email/appointment) из файла. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [requestApointment()](#requestApointment--) | Запрашивает встречу. |
| [requestApointment(int seqId)](#requestApointment-int-) | Запрашивает встречу. |
| [resetTimeZone()](#resetTimeZone--) | Установить локальный часовой пояс |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет встречу в файл в формате iCalendar, используя параметры сохранения по умолчанию |
| [save(OutputStream stream, AppointmentSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.AppointmentSaveOptions-) | Сохраняет встречу в поток с указанными параметрами сохранения |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Сохраняет встречу в поток в указанном формате, используя параметры сохранения по умолчанию |
| [save(String filePath)](#save-java.lang.String-) | Сохраняет встречу в файл в формате iCalendar, используя параметры сохранения по умолчанию |
| [save(String filePath, AppointmentSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.AppointmentSaveOptions-) | Сохраняет встречу в файл с указанными параметрами сохранения |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Сохраняет встречу в файл в указанном формате, используя параметры сохранения по умолчанию |
| [setAppointmentClass(int value)](#setAppointmentClass-int-) | Указывает классификацию доступа для встречи. |
| [setAttendees(MailAddressCollection value)](#setAttendees-com.aspose.email.MailAddressCollection-) | Получает или задает участников. |
| [setCreatedDate(Date value)](#setCreatedDate-java.util.Date-) | Получает или задаёт дату и время создания информации календаря. |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | Получает или задает дату/время, когда был создан экземпляр объекта iCalendar.. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Получает или задает описание. |
| [setDescriptionHtml(boolean value)](#setDescriptionHtml-boolean-) | Получает или задает значение, указывающее, находится ли описание в формате HTML. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Получает или задает конечную дату. |
| [setEndTimeZone(String value)](#setEndTimeZone-java.lang.String-) | Конечный часовой пояс |
| [setFlags(int value)](#setFlags-int-) | Получает или задает флаги встречи. |
| [setHtmlDescription(String value)](#setHtmlDescription-java.lang.String-) | Получает или задает HTML-представление описания. |
| [setLastModifiedDate(Date value)](#setLastModifiedDate-java.util.Date-) | Получает или задает дату и время последнего изменения информации календаря. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Получает или задает местоположение. |
| [setMethodType(int value)](#setMethodType-int-) | Получает или задает тип метода объекта iCalendar, связанный с объектом календаря. |
| [setMicrosoftBusyStatus(int value)](#setMicrosoftBusyStatus-int-) | Указывает статус BUSY (занят) встречи. |
| [setMicrosoftImportance(int value)](#setMicrosoftImportance-int-) | Указывает важность встречи. |
| [setMicrosoftIntendedStatus(int value)](#setMicrosoftIntendedStatus-int-) | Указывает статус INTENDED (предполагаемый) встречи. |
| [setOrganizer(MailAddress value)](#setOrganizer-com.aspose.email.MailAddress-) | Получает или задает организатора. |
| [setRecurrence(RecurrencePattern value)](#setRecurrence-com.aspose.email.RecurrencePattern-) | Получает или задает шаблон повторения. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Получает или задает дату начала. |
| [setStartTimeZone(String value)](#setStartTimeZone-java.lang.String-) | Начальный часовой пояс |
| [setStatus(int value)](#setStatus-int-) | Получает или задает общий статус или подтверждение объекта. |
| [setSummary(String value)](#setSummary-java.lang.String-) | Получает или задает сводку. |
| [setTimeZone(String tzName)](#setTimeZone-java.lang.String-) | Установить часовой пояс |
| [setTransparency(int value)](#setTransparency-int-) | Указывает, должна ли эта встреча быть видна в поиске доступности. |
| [setUniqueId(String value)](#setUniqueId-java.lang.String-) | Получает или задает строковое значение, содержащее GUID элемента календаря. |
| [toString()](#toString--) |  |
| [updateAppointment()](#updateAppointment--) | Обновляет встречу. |
| [updateAppointment(int seqId)](#updateAppointment-int-) | Обновляет встречу. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Appointment(String location, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees) {#Appointment-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-}
```
public Appointment(String location, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)
```


Инициализирует новый экземпляр класса [Appointment](../../com.aspose.email/appointment).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| местоположение | java.lang.String | Местоположение события календаря. |
| startDate | java.util.Date | Время начала события календаря. |
| endDate | java.util.Date | Время окончания события календаря. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | Организатор события календаря. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Участники события календаря. |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)
```


Инициализирует новый экземпляр класса [Appointment](../../com.aspose.email/appointment).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| местоположение | java.lang.String | Местоположение события календаря. |
| резюме | java.lang.String | Краткое содержание события календаря. |
| описание | java.lang.String | Описание события календаря. |
| startDate | java.util.Date | Время начала события календаря. |
| endDate | java.util.Date | Время окончания события календаря. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | Организатор события календаря. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Участники события календаря. |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid)
```


Инициализирует новый экземпляр класса [Appointment](../../com.aspose.email/appointment).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| местоположение | java.lang.String | Местоположение события календаря. |
| резюме | java.lang.String | Краткое содержание события календаря. |
| описание | java.lang.String | Описание события календаря. |
| startDate | java.util.Date | Время начала события календаря. |
| endDate | java.util.Date | Время окончания события календаря. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | Организатор события календаря. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Участники события календаря. |
| uid | java.lang.String | Уникальный идентификатор события календаря. |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, RecurrencePattern recurrencePattern) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-com.aspose.email.RecurrencePattern-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, RecurrencePattern recurrencePattern)
```


Инициализирует новый экземпляр класса [Appointment](../../com.aspose.email/appointment).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| местоположение | java.lang.String | Местоположение события календаря. |
| резюме | java.lang.String | Краткое содержание события календаря. |
| описание | java.lang.String | Описание события календаря. |
| startDate | java.util.Date | Время начала события календаря. |
| endDate | java.util.Date | Время окончания события календаря. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | Организатор события календаря. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Участники события календаря. |
| recurrencePattern | [RecurrencePattern](../../com.aspose.email/recurrencepattern) | Шаблон повторения. |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid, RecurrencePattern recurrencePattern) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-com.aspose.email.RecurrencePattern-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid, RecurrencePattern recurrencePattern)
```


Инициализирует новый экземпляр класса [Appointment](../../com.aspose.email/appointment).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| местоположение | java.lang.String | Местоположение события календаря. |
| резюме | java.lang.String | Краткое содержание события календаря. |
| описание | java.lang.String | Описание события календаря. |
| startDate | java.util.Date | Время начала события календаря. |
| endDate | java.util.Date | Время окончания события календаря. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | Организатор события календаря. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Участники события календаря. |
| uid | java.lang.String | Уникальный идентификатор события календаря. |
| recurrencePattern | [RecurrencePattern](../../com.aspose.email/recurrencepattern) | Шаблон повторения. |

### cancelAppointment() {#cancelAppointment--}
```
public final AlternateView cancelAppointment()
```


Отменяет встречу.

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### cancelAppointment(int seqId) {#cancelAppointment-int-}
```
public final AlternateView cancelAppointment(int seqId)
```


Отменяет встречу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| seqId | int | Идентификатор последовательности. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAppointmentClass() {#getAppointmentClass--}
```
public final int getAppointmentClass()
```


Указывает классификацию доступа для встречи.

**Returns:**
int
### getAppointmentHtml() {#getAppointmentHtml--}
```
public final String getAppointmentHtml()
```


Получает HTML календаря.

**Returns:**
java.lang.String - Строковое значение календаря в формате HTML.
### getAppointmentText() {#getAppointmentText--}
```
public final String getAppointmentText()
```


Получает текст календаря.

**Returns:**
java.lang.String - Строковое значение календаря в виде обычного текста.
### getAppointmentText(AppointmentFormattingOptions formattingOptions) {#getAppointmentText-com.aspose.email.AppointmentFormattingOptions-}
```
public final String getAppointmentText(AppointmentFormattingOptions formattingOptions)
```


Получает текст календаря.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| formattingOptions | [AppointmentFormattingOptions](../../com.aspose.email/appointmentformattingoptions) | [AppointmentFormattingOptions](../../com.aspose.email/appointmentformattingoptions) который представляет параметры форматирования встречи. |

**Returns:**
java.lang.String - Текстовое представление встречи.
### getAttachments() {#getAttachments--}
```
public final AttachmentCollection getAttachments()
```


Получает коллекцию вложений встречи.

**Returns:**
[AttachmentCollection](../../com.aspose.email/attachmentcollection)
### getAttendees() {#getAttendees--}
```
public final MailAddressCollection getAttendees()
```


Получает или задает участников.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreatedDate() {#getCreatedDate--}
```
public final Date getCreatedDate()
```


Получает или задаёт дату и время создания информации календаря.

Значение: java.util.Date, представляющий дату и время создания.

**Returns:**
java.util.Date
### getDateTimeStamp() {#getDateTimeStamp--}
```
public final Date getDateTimeStamp()
```


Получает или задает дату/время, когда был создан экземпляр объекта iCalendar..

**Returns:**
java.util.Date
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Получает или задает описание.

**Returns:**
java.lang.String
### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Получает или задает конечную дату.

**Returns:**
java.util.Date
### getEndTimeZone() {#getEndTimeZone--}
```
public final String getEndTimeZone()
```


Конечный часовой пояс

**Returns:**
java.lang.String
### getFlags() {#getFlags--}
```
public final int getFlags()
```


Получает или задает флаги встречи.

**Returns:**
int
### getHtmlDescription() {#getHtmlDescription--}
```
public final String getHtmlDescription()
```


Получает или задает HTML-представление описания.

**Returns:**
java.lang.String
### getLastModifiedDate() {#getLastModifiedDate--}
```
public final Date getLastModifiedDate()
```


Получает или задает дату и время последнего изменения информации календаря.

Значение: java.util.Date, представляющий дату и время изменения.

**Returns:**
java.util.Date
### getLocation() {#getLocation--}
```
public final String getLocation()
```


Получает или задает местоположение.

**Returns:**
java.lang.String
### getMethodType() {#getMethodType--}
```
public final int getMethodType()
```


Получает или задает тип метода объекта iCalendar, связанный с объектом календаря.

**Returns:**
int
### getMicrosoftBusyStatus() {#getMicrosoftBusyStatus--}
```
public final int getMicrosoftBusyStatus()
```


Указывает статус BUSY (занят) встречи.

**Returns:**
int
### getMicrosoftImportance() {#getMicrosoftImportance--}
```
public final int getMicrosoftImportance()
```


Указывает важность встречи.

**Returns:**
int
### getMicrosoftIntendedStatus() {#getMicrosoftIntendedStatus--}
```
public final int getMicrosoftIntendedStatus()
```


Указывает статус INTENDED (предполагаемый) встречи.

**Returns:**
int
### getOptionalAttendees() {#getOptionalAttendees--}
```
public final MailAddressCollection getOptionalAttendees()
```


Получает необязательных участников.

Значение: Коллекция адресов необязательных участников.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getOrganizer() {#getOrganizer--}
```
public final MailAddress getOrganizer()
```


Получает или задает организатора.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getRecurrence() {#getRecurrence--}
```
public final RecurrencePattern getRecurrence()
```


Получает или задает шаблон повторения.

Значение: Шаблон повторения.

**Returns:**
[RecurrencePattern](../../com.aspose.email/recurrencepattern)
### getReminders() {#getReminders--}
```
public final AppointmentReminderCollection getReminders()
```


Содержит коллекцию объектов [AppointmentReminder](../../com.aspose.email/appointmentreminder).

**Returns:**
[AppointmentReminderCollection](../../com.aspose.email/appointmentremindercollection)
### getSequenceId() {#getSequenceId--}
```
public final String getSequenceId()
```


Получает идентификатор последовательности.

Значение: идентификатор последовательности.

**Returns:**
java.lang.String
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Получает или задает дату начала.

**Returns:**
java.util.Date
### getStartTimeZone() {#getStartTimeZone--}
```
public final String getStartTimeZone()
```


Начальный часовой пояс

**Returns:**
java.lang.String
### getStatus() {#getStatus--}
```
public final int getStatus()
```


Получает или задает общий статус или подтверждение объекта.

**Returns:**
int
### getSummary() {#getSummary--}
```
public final String getSummary()
```


Получает или задает сводку.

**Returns:**
java.lang.String
### getTransparency() {#getTransparency--}
```
public final int getTransparency()
```


Указывает, должна ли эта встреча быть видна в поиске доступности.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


Получает или задает строковое значение, содержащее GUID элемента календаря. В MS Exchange это свойство mapi PidLidGlobalObjectId.

Значение: Уникальный идентификатор.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDescriptionHtml() {#isDescriptionHtml--}
```
public final boolean isDescriptionHtml()
```


Получает или задает значение, указывающее, находится ли описание в формате HTML.

**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Appointment load(InputStream stream)
```


Загружает [Appointment](../../com.aspose.email/appointment) из потока

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для загрузки из |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment)
### load(InputStream stream, boolean applyLocalTimeZone) {#load-java.io.InputStream-boolean-}
```
public static Appointment load(InputStream stream, boolean applyLocalTimeZone)
```


Загружает [Appointment](../../com.aspose.email/appointment) из потока

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для загрузки из |
| applyLocalTimeZone | boolean | Convert time to local timezone |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment)
### load(InputStream stream, AppointmentLoadOptions options) {#load-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-}
```
public static Appointment load(InputStream stream, AppointmentLoadOptions options)
```


Загружает [Appointment](../../com.aspose.email/appointment) из потока

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для загрузки из |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | Представляет параметры загрузки встречи |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment)
### load(String filePath) {#load-java.lang.String-}
```
public static Appointment load(String filePath)
```


Loads [Appointment](../../com.aspose.email/appointment) from the file. Supported file formats: iCalendar

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment)
### load(String filePath, AppointmentLoadOptions options) {#load-java.lang.String-com.aspose.email.AppointmentLoadOptions-}
```
public static Appointment load(String filePath, AppointmentLoadOptions options)
```


Loads [Appointment](../../com.aspose.email/appointment) from the file. Supported file formats: iCalendar

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | A file path. |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | Represents appointment load options[AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions). |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment).
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### requestApointment() {#requestApointment--}
```
public final AlternateView requestApointment()
```


Запрашивает встречу.

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### requestApointment(int seqId) {#requestApointment-int-}
```
public final AlternateView requestApointment(int seqId)
```


Запрашивает встречу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| seqId | int | Идентификатор последовательности. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### resetTimeZone() {#resetTimeZone--}
```
public final void resetTimeZone()
```


Установить локальный часовой пояс

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Сохраняет встречу в файл в формате iCalendar, используя параметры сохранения по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |

### save(OutputStream stream, AppointmentSaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.email.AppointmentSaveOptions-}
```
public final void save(OutputStream stream, AppointmentSaveOptions saveOptions)
```


Сохраняет встречу в поток с указанными параметрами сохранения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |
| saveOptions | [AppointmentSaveOptions](../../com.aspose.email/appointmentsaveoptions) | Параметры сохранения |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


Сохраняет встречу в поток в указанном формате, используя параметры сохранения по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |
| saveFormat | int | Формат сохранения |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Сохраняет встречу в файл в формате iCalendar, используя параметры сохранения по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу |

### save(String filePath, AppointmentSaveOptions saveOptions) {#save-java.lang.String-com.aspose.email.AppointmentSaveOptions-}
```
public final void save(String filePath, AppointmentSaveOptions saveOptions)
```


Сохраняет встречу в файл с указанными параметрами сохранения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу |
| saveOptions | [AppointmentSaveOptions](../../com.aspose.email/appointmentsaveoptions) | Параметры сохранения |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


Сохраняет встречу в файл в указанном формате, используя параметры сохранения по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу |
| saveFormat | int | Формат сохранения |

### setAppointmentClass(int value) {#setAppointmentClass-int-}
```
public final void setAppointmentClass(int value)
```


Указывает классификацию доступа для встречи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setAttendees(MailAddressCollection value) {#setAttendees-com.aspose.email.MailAddressCollection-}
```
public final void setAttendees(MailAddressCollection value)
```


Получает или задает участников.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setCreatedDate(Date value) {#setCreatedDate-java.util.Date-}
```
public final void setCreatedDate(Date value)
```


Получает или задаёт дату и время создания информации календаря.

Значение: java.util.Date, представляющий дату и время создания.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setDateTimeStamp(Date value) {#setDateTimeStamp-java.util.Date-}
```
public final void setDateTimeStamp(Date value)
```


Получает или задает дату/время, когда был создан экземпляр объекта iCalendar..

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Получает или задает описание.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setDescriptionHtml(boolean value) {#setDescriptionHtml-boolean-}
```
public final void setDescriptionHtml(boolean value)
```


Получает или задает значение, указывающее, находится ли описание в формате HTML.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Получает или задает конечную дату.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setEndTimeZone(String value) {#setEndTimeZone-java.lang.String-}
```
public final void setEndTimeZone(String value)
```


Конечный часовой пояс

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setFlags(int value) {#setFlags-int-}
```
public final void setFlags(int value)
```


Получает или задает флаги встречи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setHtmlDescription(String value) {#setHtmlDescription-java.lang.String-}
```
public final void setHtmlDescription(String value)
```


Получает или задает HTML-представление описания.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setLastModifiedDate(Date value) {#setLastModifiedDate-java.util.Date-}
```
public final void setLastModifiedDate(Date value)
```


Получает или задает дату и время последнего изменения информации календаря.

Значение: java.util.Date, представляющий дату и время изменения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Получает или задает местоположение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setMethodType(int value) {#setMethodType-int-}
```
public final void setMethodType(int value)
```


Получает или задает тип метода объекта iCalendar, связанный с объектом календаря.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setMicrosoftBusyStatus(int value) {#setMicrosoftBusyStatus-int-}
```
public final void setMicrosoftBusyStatus(int value)
```


Указывает статус BUSY (занят) встречи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setMicrosoftImportance(int value) {#setMicrosoftImportance-int-}
```
public final void setMicrosoftImportance(int value)
```


Указывает важность встречи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setMicrosoftIntendedStatus(int value) {#setMicrosoftIntendedStatus-int-}
```
public final void setMicrosoftIntendedStatus(int value)
```


Указывает статус INTENDED (предполагаемый) встречи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setOrganizer(MailAddress value) {#setOrganizer-com.aspose.email.MailAddress-}
```
public final void setOrganizer(MailAddress value)
```


Получает или задает организатора.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setRecurrence(RecurrencePattern value) {#setRecurrence-com.aspose.email.RecurrencePattern-}
```
public final void setRecurrence(RecurrencePattern value)
```


Получает или задает шаблон повторения.

Значение: Шаблон повторения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [RecurrencePattern](../../com.aspose.email/recurrencepattern) |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Получает или задает дату начала.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setStartTimeZone(String value) {#setStartTimeZone-java.lang.String-}
```
public final void setStartTimeZone(String value)
```


Начальный часовой пояс

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


Получает или задает общий статус или подтверждение объекта.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setSummary(String value) {#setSummary-java.lang.String-}
```
public final void setSummary(String value)
```


Получает или задает сводку.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setTimeZone(String tzName) {#setTimeZone-java.lang.String-}
```
public final void setTimeZone(String tzName)
```


Установить часовой пояс

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tzName | java.lang.String | The time zone name, for sample "America/New\_York" |

### setTransparency(int value) {#setTransparency-int-}
```
public final void setTransparency(int value)
```


Указывает, должна ли эта встреча быть видна в поиске доступности.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setUniqueId(String value) {#setUniqueId-java.lang.String-}
```
public final void setUniqueId(String value)
```


Получает или задает строковое значение, содержащее GUID элемента календаря. В MS Exchange это свойство mapi PidLidGlobalObjectId.

Значение: Уникальный идентификатор.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateAppointment() {#updateAppointment--}
```
public final AlternateView updateAppointment()
```


Обновляет встречу.

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### updateAppointment(int seqId) {#updateAppointment-int-}
```
public final AlternateView updateAppointment(int seqId)
```


Обновляет встречу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| seqId | int | Идентификатор последовательности. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

