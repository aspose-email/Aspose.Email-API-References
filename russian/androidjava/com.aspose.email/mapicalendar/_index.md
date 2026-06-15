---
title: MapiCalendar
second_title: Aspose.Email for Android via Java API Reference
description: Представляет объект календаря mapi.
type: docs
weight: 206
url: /ru/androidjava/com.aspose.email/mapicalendar/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public final class MapiCalendar extends MapiMessageItemBase
```

Представляет объект календаря mapi.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MapiCalendar()](#MapiCalendar--) | Инициализирует новый экземпляр класса [MapiCalendar](../../com.aspose.email/mapicalendar) |
| [MapiCalendar(String location, String summary, String description, Date startDate, Date endDate)](#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-) | Инициализирует новый экземпляр класса [MapiCalendar](../../com.aspose.email/mapicalendar). |
| [MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, String organizer, MapiRecipientCollection attendees)](#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-java.lang.String-com.aspose.email.MapiRecipientCollection-) | Инициализирует новый экземпляр класса [MapiCalendar](../../com.aspose.email/mapicalendar). |
| [MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, MapiElectronicAddress organizer, MapiRecipientCollection attendees)](#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MapiElectronicAddress-com.aspose.email.MapiRecipientCollection-) | Инициализирует новый экземпляр класса [MapiCalendar](../../com.aspose.email/mapicalendar). |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Создает узел mapi. |
| [dispose()](#dispose--) | Освобождает все ресурсы. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAppointmentCounterProposal()](#getAppointmentCounterProposal--) | Получает или задает значение, указывающее, является ли объект Meeting Response контрпредложением. |
| [getAttachments()](#getAttachments--) | Получает вложения в сообщении. |
| [getAttendees()](#getAttendees--) | Получает или задает участников |
| [getBilling()](#getBilling--) | Содержит информацию о выставлении счета, связанную с элементом. |
| [getBody()](#getBody--) | Получает текст сообщения. |
| [getBodyHtml()](#getBodyHtml--) | Получает BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) сообщения, преобразованного в HTML, если присутствует, иначе пустую строку. |
| [getBodyRtf()](#getBodyRtf--) | Получает или задает текст сообщения в формате RTF. |
| [getBodyType()](#getBodyType--) | Получает тип тела. |
| [getBusyStatus()](#getBusyStatus--) | Получает или задает статус занятости |
| [getCategories()](#getCategories--) | Содержит ключевые слова или категории для объекта сообщения. |
| [getClass()](#getClass--) |  |
| [getClientIntent()](#getClientIntent--) | Получает или задает действия, которые пользователь предпринял в отношении этого объекта Meeting. |
| [getCodePage()](#getCodePage--) | Получает кодовую страницу. |
| [getCompanies()](#getCompanies--) | Содержит названия компаний, связанных с элементом. |
| [getEndDate()](#getEndDate--) | Получает или задает дату и время окончания события. |
| [getEndDateTimeZone()](#getEndDateTimeZone--) | Получает или задает информацию о часовом поясе, указывающую часовой пояс свойства EndDate |
| [getItemId()](#getItemId--) | Идентификатор элемента, используется с сервером. |
| [getKeyWords()](#getKeyWords--) | Получает или задает категории объекта календаря |
| [getLocation()](#getLocation--) | Получает или задает место проведения события |
| [getMessageClass()](#getMessageClass--) | Получает чувствительную к регистру строку, идентифицирующую пользовательский класс сообщения, например IPM.Note. |
| [getMileage()](#getMileage--) | Содержит информацию о пробеге, связанную с элементом. |
| [getNamedProperties()](#getNamedProperties--) | Получает именованные свойства сообщения. |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | Получает сопоставление именованных свойств. |
| [getOrganizer()](#getOrganizer--) | Получает или задает организатора. |
| [getProperties()](#getProperties--) | Получает коллекцию свойств. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Получает свойство MAPI по дескриптору свойства. |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | Получает значение свойства, указанного тегом, в виде типа Boolean. |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | Получает строковое значение свойства, указанного тегом. |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | Получает значение свойства, указанного тегом, в виде типа DateTime. |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | Получает значение int32 свойства, указанного тегом. |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | Получает значение свойства, указанного тегом, в виде типа Long (int64). |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | Получает значение свойства, указанного тегом, в виде типа Short. |
| [getPropertyStream()](#getPropertyStream--) | Получает поток свойства. |
| [getPropertyString(long tag)](#getPropertyString-long-) | Получает строковое значение свойства, указанного тегом. |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | Получает строковое значение свойства, указанного тегом. |
| [getRecipients()](#getRecipients--) | Получает получателей сообщения. |
| [getRecurrence()](#getRecurrence--) | Получает или задает свойства повторения |
| [getReminderDelta()](#getReminderDelta--) | Получает или задает интервал в минутах между моментом, когда напоминание впервые просрочивается, и временем начала объекта Calendar |
| [getReminderFileParameter()](#getReminderFileParameter--) | Указывает полный путь к звуку, который клиент ДОЛЖЕН воспроизводить, когда напоминание просрочено. |
| [getReminderSet()](#getReminderSet--) | Получает или задает значение, указывающее, установлено ли напоминание для объекта. |
| [getSensitivity()](#getSensitivity--) | Gets the Sensitivity. |
| [getSequence()](#getSequence--) | Получает или задает номер последовательности |
| [getStartDate()](#getStartDate--) | Получает или задает дату и время начала события. |
| [getStartDateTimeZone()](#getStartDateTimeZone--) | Получает или задает информацию о часовом поясе, указывающую часовой пояс свойства StartDate |
| [getSubStorages()](#getSubStorages--) | Получает вложенные хранилища. |
| [getSubject()](#getSubject--) | Получает или задает тему сообщения. |
| [getSubjectPrefix()](#getSubjectPrefix--) | Получает префикс темы, который обычно указывает на действие с сообщением, например \"FW: \" для пересылки. |
| [getUid()](#getUid--) | Получает уникальный идентификатор |
| [hashCode()](#hashCode--) |  |
| [isAllDay()](#isAllDay--) | Получает или задает значение, указывающее, является ли событие целодневным |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Определяет, закодированы ли строковые свойства в Unicode. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(long tag)](#removeProperty-long-) | Обеспечивает корректное удаление свойства из всех коллекций. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет объект календаря в файл в формате iCalendar, используя параметры сохранения по умолчанию |
| [save(OutputStream stream, MapiCalendarSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.MapiCalendarSaveOptions-) | Сохраняет календарь в поток с указанными параметрами сохранения |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Сохраняет объект календаря в поток в указанном формате, используя параметры сохранения по умолчанию |
| [save(String filePath)](#save-java.lang.String-) | Сохраняет объект календаря в файл в формате iCalendar, используя параметры сохранения по умолчанию |
| [save(String filePath, MapiCalendarSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.MapiCalendarSaveOptions-) | Сохраняет объект календаря в файл в указанном формате, используя параметры сохранения по умолчанию |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Сохраняет объект календаря в файл в указанном формате, используя параметры сохранения по умолчанию |
| [setAllDay(boolean value)](#setAllDay-boolean-) | Получает или задает значение, указывающее, является ли событие целодневным |
| [setAppointmentCounterProposal(boolean value)](#setAppointmentCounterProposal-boolean-) | Получает или задает значение, указывающее, является ли объект Meeting Response контрпредложением. |
| [setAttendees(MapiCalendarAttendees value)](#setAttendees-com.aspose.email.MapiCalendarAttendees-) | Получает или задает участников |
| [setBilling(String value)](#setBilling-java.lang.String-) | Содержит информацию о выставлении счета, связанную с элементом. |
| [setBody(String value)](#setBody-java.lang.String-) | Получает текст сообщения. |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | Устанавливает содержимое тела. |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | Устанавливает содержимое тела. |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | Получает или задает текст сообщения в формате RTF. |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | Получает или задает текст сообщения в формате RTF. |
| [setBusyStatus(int value)](#setBusyStatus-int-) | Получает или задает статус занятости |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | Содержит ключевые слова или категории для объекта сообщения. |
| [setClientIntent(int value)](#setClientIntent-int-) | Получает или задает действия, которые пользователь предпринял в отношении этого объекта Meeting. |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | Содержит названия компаний, связанных с элементом. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Получает или задает дату и время окончания события. |
| [setEndDateTimeZone(MapiCalendarTimeZone value)](#setEndDateTimeZone-com.aspose.email.MapiCalendarTimeZone-) | Получает или задает информацию о часовом поясе, указывающую часовой пояс свойства EndDate |
| [setKeyWords(String value)](#setKeyWords-java.lang.String-) | Получает или задает категории объекта календаря |
| [setLocation(String value)](#setLocation-java.lang.String-) | Получает или задает место проведения события |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | Получает чувствительную к регистру строку, идентифицирующую пользовательский класс сообщения, например IPM.Note. |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | Устанавливает флаги сообщения. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Содержит информацию о пробеге, связанную с элементом. |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | Устанавливает сопоставление именованных свойств. |
| [setOrganizer(MapiElectronicAddress value)](#setOrganizer-com.aspose.email.MapiElectronicAddress-) | Получает или задает организатора. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Устанавливает свойство. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Устанавливает свойство MAPI. |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | Получает получателей сообщения. |
| [setRecurrence(MapiCalendarEventRecurrence value)](#setRecurrence-com.aspose.email.MapiCalendarEventRecurrence-) | Получает или задает свойства повторения |
| [setReminderDelta(int value)](#setReminderDelta-int-) | Получает или задает интервал в минутах между моментом, когда напоминание впервые просрочивается, и временем начала объекта Calendar |
| [setReminderFileParameter(String value)](#setReminderFileParameter-java.lang.String-) | Указывает полный путь к звуку, который клиент ДОЛЖЕН воспроизводить, когда напоминание просрочено. |
| [setReminderSet(boolean value)](#setReminderSet-boolean-) | Получает или задает значение, указывающее, установлено ли напоминание для объекта. |
| [setSensitivity(int value)](#setSensitivity-int-) | Gets the Sensitivity. |
| [setSequence(int value)](#setSequence-int-) | Получает или задает номер последовательности |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Получает или задает дату и время начала события. |
| [setStartDateTimeZone(MapiCalendarTimeZone value)](#setStartDateTimeZone-com.aspose.email.MapiCalendarTimeZone-) | Получает или задает информацию о часовом поясе, указывающую часовой пояс свойства StartDate |
| [setSubject(String value)](#setSubject-java.lang.String-) | Получает или задает тему сообщения. |
| [setUid(String value)](#setUid-java.lang.String-) | Получает уникальный идентификатор |
| [toString()](#toString--) |  |
| [tryGetPropertyData(long tag)](#tryGetPropertyData-long-) | Попробуйте получить данные свойства с указанным ключом тега. |
| [tryGetPropertyDateTime(long tag, Date[] value)](#tryGetPropertyDateTime-long-java.util.Date---) | Получает значение указанного свойства как тип DateTime. |
| [tryGetPropertyInt32(long tag, int[] value)](#tryGetPropertyInt32-long-int---) | Получает значение указанного свойства как тип Int32. |
| [tryGetPropertyLong(long tag, long[] value)](#tryGetPropertyLong-long-long---) | Получает значение указанного свойства как тип Long. |
| [tryGetPropertyString(long tag)](#tryGetPropertyString-long-) | Попробуйте получить данные свойства в виде строки с указанным тегом. |
| [tryGetPropertyString(long tag, int codepage)](#tryGetPropertyString-long-int-) | Попробуйте получить данные свойства в виде строки с указанным тегом и кодовой страницей. |
| [tryGetPropertyString(long tag, String[] value)](#tryGetPropertyString-long-java.lang.String---) | Получает значение указанного свойства как тип String. |
| [tryGetPropertyString(long tag, String[] value, int codepage)](#tryGetPropertyString-long-java.lang.String---int-) | Получает значение указанного свойства как тип String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiCalendar() {#MapiCalendar--}
```
public MapiCalendar()
```


Инициализирует новый экземпляр класса [MapiCalendar](../../com.aspose.email/mapicalendar)

### MapiCalendar(String location, String summary, String description, Date startDate, Date endDate) {#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-}
```
public MapiCalendar(String location, String summary, String description, Date startDate, Date endDate)
```


Инициализирует новый экземпляр класса [MapiCalendar](../../com.aspose.email/mapicalendar).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| местоположение | java.lang.String | Местоположение встречи. |
| резюме | java.lang.String | Краткое описание встречи. |
| описание | java.lang.String | Описание встречи. |
| startDate | java.util.Date | Дата начала. |
| endDate | java.util.Date | Конечная дата. |

### MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, String organizer, MapiRecipientCollection attendees) {#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-java.lang.String-com.aspose.email.MapiRecipientCollection-}
```
public MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, String organizer, MapiRecipientCollection attendees)
```


Инициализирует новый экземпляр класса [MapiCalendar](../../com.aspose.email/mapicalendar).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| местоположение | java.lang.String | Местоположение совещания. |
| резюме | java.lang.String | Краткое описание совещания. |
| описание | java.lang.String | Описание совещания. |
| startDate | java.util.Date | Дата начала. |
| endDate | java.util.Date | Конечная дата. |
| организатор | java.lang.String | Адрес организатора совещания. |
| attendees | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) | Участники совещания. |

### MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, MapiElectronicAddress organizer, MapiRecipientCollection attendees) {#MapiCalendar-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MapiElectronicAddress-com.aspose.email.MapiRecipientCollection-}
```
public MapiCalendar(String location, String summary, String description, Date startDate, Date endDate, MapiElectronicAddress organizer, MapiRecipientCollection attendees)
```


Инициализирует новый экземпляр класса [MapiCalendar](../../com.aspose.email/mapicalendar).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| местоположение | java.lang.String | Местоположение совещания. |
| резюме | java.lang.String | Краткое описание совещания. |
| описание | java.lang.String | Описание совещания. |
| startDate | java.util.Date | Дата начала. |
| endDate | java.util.Date | Конечная дата. |
| organizer | [MapiElectronicAddress](../../com.aspose.email/mapielectronicaddress) | Организатор совещания. |
| attendees | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) | Участники совещания. |

### close() {#close--}
```
public void close()
```




### createMapiNode(String key) {#createMapiNode-java.lang.String-}
```
public IMapiNode createMapiNode(String key)
```


Создает узел mapi.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Ключ узла. |

**Returns:**
com.aspose.email.IMapiNode - Интерфейс IMapiNode.
### dispose() {#dispose--}
```
public void dispose()
```


Освобождает все ресурсы.

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
### getAppointmentCounterProposal() {#getAppointmentCounterProposal--}
```
public final boolean getAppointmentCounterProposal()
```


Получает или задает значение, указывающее, является ли объект Meeting Response контрпредложением.

**Returns:**
boolean
### getAttachments() {#getAttachments--}
```
public final MapiAttachmentCollection getAttachments()
```


Получает вложения в сообщении.

Значение: Коллекция вложений.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection)
### getAttendees() {#getAttendees--}
```
public final MapiCalendarAttendees getAttendees()
```


Получает или задает участников

**Returns:**
[MapiCalendarAttendees](../../com.aspose.email/mapicalendarattendees)
### getBilling() {#getBilling--}
```
public final String getBilling()
```


Содержит информацию о выставлении счета, связанную с элементом.

**Returns:**
java.lang.String
### getBody() {#getBody--}
```
public String getBody()
```


Получает текст сообщения.

Значение: Строка, представляющая тело сообщения.

**Returns:**
java.lang.String
### getBodyHtml() {#getBodyHtml--}
```
public final String getBodyHtml()
```


Получает BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) сообщения, преобразованного в HTML, если присутствует, иначе пустую строку.

**Returns:**
java.lang.String
### getBodyRtf() {#getBodyRtf--}
```
public final String getBodyRtf()
```


Получает или задает текст сообщения в формате RTF.

Значение: Строка, представляющая тело сообщения в формате rtf.

--------------------

При установке значения обновляются свойства PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY. Устанавливаемое строковое значение должно иметь формат RTF. Поэтому, если необходимо задать значение в формате HTML, его сначала нужно закодировать в RTF в соответствии со спецификацией RTF Extensions. Чтобы быстро задать содержимое тела сообщения в форматах HTML или обычного текста, используйте метод SetBodyContent. При установке null или пустой строки свойства BodyRtf и Body устанавливаются в null.

**Returns:**
java.lang.String
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Получает тип тела.

Значение: Тип тела.

**Returns:**
int
### getBusyStatus() {#getBusyStatus--}
```
public final int getBusyStatus()
```


Получает или задает статус занятости

**Returns:**
int
### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


Содержит ключевые слова или категории для объекта сообщения.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClientIntent() {#getClientIntent--}
```
public final int getClientIntent()
```


Получает или задает действия, которые пользователь предпринял в отношении этого объекта Meeting.

**Returns:**
int
### getCodePage() {#getCodePage--}
```
public int getCodePage()
```


Получает кодовую страницу.

Значение: Кодовая страница.

**Returns:**
int
### getCompanies() {#getCompanies--}
```
public final String[] getCompanies()
```


Содержит названия компаний, связанных с элементом.

**Returns:**
java.lang.String[]
### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Получает или задает дату и время окончания события. Если дата не установлена, возвращается значение по умолчанию для java.util.Date.

**Returns:**
java.util.Date
### getEndDateTimeZone() {#getEndDateTimeZone--}
```
public final MapiCalendarTimeZone getEndDateTimeZone()
```


Получает или задает информацию о часовом поясе, указывающую часовой пояс свойства EndDate

**Returns:**
[MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone)
### getItemId() {#getItemId--}
```
public String getItemId()
```


Идентификатор элемента, используется с сервером.

**Returns:**
java.lang.String
### getKeyWords() {#getKeyWords--}
```
public final String getKeyWords()
```


Получает или задает категории объекта календаря

**Returns:**
java.lang.String
### getLocation() {#getLocation--}
```
public final String getLocation()
```


Получает или задает место проведения события

**Returns:**
java.lang.String
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Возвращает чувствительную к регистру строку, идентифицирующую определённый отправителем класс сообщения, например IPM.Note. Класс сообщения указывает тип, назначение или содержание сообщения.

Значение: Строка, представляющая класс сообщения.

**Returns:**
java.lang.String
### getMileage() {#getMileage--}
```
public final String getMileage()
```


Содержит информацию о пробеге, связанную с элементом.

**Returns:**
java.lang.String
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Получает именованные свойства сообщения.

Значение: Коллекция именованных свойств.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getNamedPropertyMapping() {#getNamedPropertyMapping--}
```
public final MapiNamedPropertyMappingStorage getNamedPropertyMapping()
```


Получает сопоставление именованных свойств.

Значение: Сопоставление именованных свойств.

**Returns:**
[MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage)
### getOrganizer() {#getOrganizer--}
```
public final MapiElectronicAddress getOrganizer()
```


Получает или задает организатора.

**Returns:**
[MapiElectronicAddress](../../com.aspose.email/mapielectronicaddress)
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


Получает коллекцию свойств.

Значение: Свойства.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


Получает свойство MAPI по дескриптору свойства.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Дескриптор свойства для искомого свойства. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - Mapi property if it is found, otherwise null.
### getPropertyBoolean(long tag) {#getPropertyBoolean-long-}
```
public final Boolean getPropertyBoolean(long tag)
```


Получает значение свойства, указанного тегом, в виде типа Boolean.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |

**Returns:**
java.lang.Boolean — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyBytes(long tag) {#getPropertyBytes-long-}
```
public final byte[] getPropertyBytes(long tag)
```


Получает строковое значение свойства, указанного тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |

**Returns:**
byte[] — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyDateTime(long key) {#getPropertyDateTime-long-}
```
public final Date getPropertyDateTime(long key)
```


Получает значение свойства, указанного тегом, в виде типа DateTime.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ключ | long | Тег свойства MAPI. |

**Returns:**
java.util.Date — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyInt32(long tag) {#getPropertyInt32-long-}
```
public final Integer getPropertyInt32(long tag)
```


Получает значение int32 свойства, указанного тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |

**Returns:**
java.lang.Integer — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyLong(long tag) {#getPropertyLong-long-}
```
public final Long getPropertyLong(long tag)
```


Получает значение свойства, указанного тегом, в виде типа Long (int64).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |

**Returns:**
java.lang.Long — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyShort(long tag) {#getPropertyShort-long-}
```
public final Short getPropertyShort(long tag)
```


Получает значение свойства, указанного тегом, в виде типа Short.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |

**Returns:**
java.lang.Short — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


Получает поток свойства.

Значение: Поток свойства.

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream)
### getPropertyString(long tag) {#getPropertyString-long-}
```
public final String getPropertyString(long tag)
```


Получает строковое значение свойства, указанного тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |

**Returns:**
java.lang.String — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyString(long tag, int codepage) {#getPropertyString-long-int-}
```
public final String getPropertyString(long tag, int codepage)
```


Получает строковое значение свойства, указанного тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |
| кодовая страница | int | Указанная кодовая страница, используемая для получения строкового значения. |

**Returns:**
java.lang.String — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getRecipients() {#getRecipients--}
```
public final MapiRecipientCollection getRecipients()
```


Получает получателей сообщения.

Значение: Коллекция получателей.

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection)
### getRecurrence() {#getRecurrence--}
```
public final MapiCalendarEventRecurrence getRecurrence()
```


Получает или задает свойства повторения

**Returns:**
[MapiCalendarEventRecurrence](../../com.aspose.email/mapicalendareventrecurrence)
### getReminderDelta() {#getReminderDelta--}
```
public final int getReminderDelta()
```


Получает или задает интервал в минутах между моментом, когда напоминание впервые просрочивается, и временем начала объекта Calendar

**Returns:**
int
### getReminderFileParameter() {#getReminderFileParameter--}
```
public final String getReminderFileParameter()
```


Указывает полный путь к звуку, который клиент ДОЛЖЕН воспроизводить, когда напоминание просрочено.

**Returns:**
java.lang.String
### getReminderSet() {#getReminderSet--}
```
public final boolean getReminderSet()
```


Получает или задает значение, указывающее, установлено ли напоминание для объекта.

**Returns:**
boolean
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets the Sensitivity.

Значение: Чувствительность.

**Returns:**
int
### getSequence() {#getSequence--}
```
public final int getSequence()
```


Получает или задает номер последовательности

**Returns:**
int
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Получает или задает дату и время начала события. Если дата не установлена, возвращается значение по умолчанию для java.util.Date.

**Returns:**
java.util.Date
### getStartDateTimeZone() {#getStartDateTimeZone--}
```
public final MapiCalendarTimeZone getStartDateTimeZone()
```


Получает или задает информацию о часовом поясе, указывающую часовой пояс свойства StartDate

**Returns:**
[MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone)
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


Получает вложенные хранилища.

Значение: Подхранилища.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Получает или задает тему сообщения.

Значение: Строка, представляющая тему сообщения.

--------------------

При установке значения также обновляются значения свойств SubjectPrefix(PR\_SUBJECT\_PREFIX) и NormalizedSubject(PR\_NORMALIZED\_SUBJECT). Если у Subject нет префикса, значение свойства SubjectPrefix устанавливается в null. При установке значения null или пустой строки значения свойств Subject, SubjectPrefix, NormalizedSubject устанавливаются в null.

**Returns:**
java.lang.String
### getSubjectPrefix() {#getSubjectPrefix--}
```
public final String getSubjectPrefix()
```


Получает префикс темы, который обычно указывает на действие с сообщением, например \"FW: \" для пересылки.

Значение: Строка, представляющая префикс темы.

**Returns:**
java.lang.String
### getUid() {#getUid--}
```
public final String getUid()
```


Получает уникальный идентификатор

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAllDay() {#isAllDay--}
```
public final boolean isAllDay()
```


Получает или задает значение, указывающее, является ли событие целодневным

**Returns:**
boolean
### isStoreUnicodeOk() {#isStoreUnicodeOk--}
```
public final boolean isStoreUnicodeOk()
```


Определяет, закодированы ли строковые свойства в Unicode.

**Returns:**
boolean — True, если строковые свойства закодированы в Unicode.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


Обеспечивает корректное удаление свойства из всех коллекций.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег MapiProperty. |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Сохраняет объект календаря в файл в формате iCalendar, используя параметры сохранения по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |

### save(OutputStream stream, MapiCalendarSaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.email.MapiCalendarSaveOptions-}
```
public final void save(OutputStream stream, MapiCalendarSaveOptions saveOptions)
```


Сохраняет календарь в поток с указанными параметрами сохранения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |
| saveOptions | [MapiCalendarSaveOptions](../../com.aspose.email/mapicalendarsaveoptions) | Параметры сохранения |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


Сохраняет объект календаря в поток в указанном формате, используя параметры сохранения по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |
| saveFormat | int | Формат сохранения |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Сохраняет объект календаря в файл в формате iCalendar, используя параметры сохранения по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу |

### save(String filePath, MapiCalendarSaveOptions saveOptions) {#save-java.lang.String-com.aspose.email.MapiCalendarSaveOptions-}
```
public final void save(String filePath, MapiCalendarSaveOptions saveOptions)
```


Сохраняет объект календаря в файл в указанном формате, используя параметры сохранения по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу |
| saveOptions | [MapiCalendarSaveOptions](../../com.aspose.email/mapicalendarsaveoptions) | Параметры сохранения |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


Сохраняет объект календаря в файл в указанном формате, используя параметры сохранения по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу |
| saveFormat | int | Формат сохранения |

### setAllDay(boolean value) {#setAllDay-boolean-}
```
public final void setAllDay(boolean value)
```


Получает или задает значение, указывающее, является ли событие целодневным

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setAppointmentCounterProposal(boolean value) {#setAppointmentCounterProposal-boolean-}
```
public final void setAppointmentCounterProposal(boolean value)
```


Получает или задает значение, указывающее, является ли объект Meeting Response контрпредложением.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setAttendees(MapiCalendarAttendees value) {#setAttendees-com.aspose.email.MapiCalendarAttendees-}
```
public final void setAttendees(MapiCalendarAttendees value)
```


Получает или задает участников

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiCalendarAttendees](../../com.aspose.email/mapicalendarattendees) |  |

### setBilling(String value) {#setBilling-java.lang.String-}
```
public final void setBilling(String value)
```


Содержит информацию о выставлении счета, связанную с элементом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public void setBody(String value)
```


Получает текст сообщения.

Значение: Строка, представляющая тело сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyContent(String content, int contentType) {#setBodyContent-java.lang.String-int-}
```
public void setBodyContent(String content, int contentType)
```


Устанавливает содержимое тела.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Содержимое. |
|  | contentType | int | Тип содержимого. |

--------------------

Предназначено для установки содержимого основного сообщения в форматах RTF, HTML или Plain Text. При установке значения также обновляются значения свойств PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY. Обратите внимание, после установки значения в формате HTML свойство BodyRtf возвращает значение, закодированное в RTF. |

### setBodyContent(String content, int contentType, boolean compression) {#setBodyContent-java.lang.String-int-boolean-}
```
public void setBodyContent(String content, int contentType, boolean compression)
```


Устанавливает содержимое тела.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Содержимое. |
| contentType | int | Тип содержимого. |
|  | compression | boolean | Указывает, что содержимое должно быть сжато. |

--------------------

Предназначено для установки содержимого основного сообщения в форматах RTF, HTML или Plain Text. При установке значения также обновляются значения свойств PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY. Обратите внимание, после установки значения в формате HTML свойство BodyRtf возвращает значение, закодированное в RTF. |

### setBodyRtf(String value) {#setBodyRtf-java.lang.String-}
```
public final void setBodyRtf(String value)
```


Получает или задает текст сообщения в формате RTF.

Значение: Строка, представляющая тело сообщения в формате rtf.

--------------------

При установке значения обновляются свойства PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY. Устанавливаемое строковое значение должно иметь формат RTF. Поэтому, если необходимо задать значение в формате HTML, его сначала нужно закодировать в RTF в соответствии со спецификацией RTF Extensions. Чтобы быстро задать содержимое тела сообщения в форматах HTML или обычного текста, используйте метод SetBodyContent. При установке null или пустой строки свойства BodyRtf и Body устанавливаются в null.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyRtf(String value, boolean compression) {#setBodyRtf-java.lang.String-boolean-}
```
public final void setBodyRtf(String value, boolean compression)
```


Получает или задает текст сообщения в формате RTF.

Значение: Строка, представляющая тело сообщения в формате rtf.

--------------------

При установке значения обновляются свойства PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY. Устанавливаемое строковое значение должно иметь формат RTF. Поэтому, если необходимо задать значение в формате HTML, его сначала нужно закодировать в RTF в соответствии со спецификацией RTF Extensions. Чтобы быстро задать содержимое тела сообщения в форматах HTML или обычного текста, используйте метод SetBodyContent. При установке null или пустой строки свойства BodyRtf и Body устанавливаются в null.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
| compression | boolean | Указывает, что содержимое должно быть сжато. |

### setBusyStatus(int value) {#setBusyStatus-int-}
```
public final void setBusyStatus(int value)
```


Получает или задает статус занятости

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setCategories(String[] value) {#setCategories-java.lang.String---}
```
public final void setCategories(String[] value)
```


Содержит ключевые слова или категории для объекта сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setClientIntent(int value) {#setClientIntent-int-}
```
public final void setClientIntent(int value)
```


Получает или задает действия, которые пользователь предпринял в отношении этого объекта Meeting.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


Содержит названия компаний, связанных с элементом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Получает или задает дату и время окончания события. Если дата не установлена, возвращается значение по умолчанию для java.util.Date.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setEndDateTimeZone(MapiCalendarTimeZone value) {#setEndDateTimeZone-com.aspose.email.MapiCalendarTimeZone-}
```
public final void setEndDateTimeZone(MapiCalendarTimeZone value)
```


Получает или задает информацию о часовом поясе, указывающую часовой пояс свойства EndDate

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone) |  |

### setKeyWords(String value) {#setKeyWords-java.lang.String-}
```
public final void setKeyWords(String value)
```


Получает или задает категории объекта календаря

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Получает или задает место проведения события

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setMessageClass(String value) {#setMessageClass-java.lang.String-}
```
public final void setMessageClass(String value)
```


Возвращает чувствительную к регистру строку, идентифицирующую определённый отправителем класс сообщения, например IPM.Note. Класс сообщения указывает тип, назначение или содержание сообщения.

Значение: Строка, представляющая класс сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setMessageFlags(long flags) {#setMessageFlags-long-}
```
public final void setMessageFlags(long flags)
```


Устанавливает флаги сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| flags | long | Флаги сообщения. |

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Содержит информацию о пробеге, связанную с элементом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setNamedPropertyMapping(MapiNamedPropertyMappingStorage value) {#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-}
```
public final void setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)
```


Устанавливает сопоставление именованных свойств.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) | Эта MapiNamedPropertyMappingStorage. |

### setOrganizer(MapiElectronicAddress value) {#setOrganizer-com.aspose.email.MapiElectronicAddress-}
```
public final void setOrganizer(MapiElectronicAddress value)
```


Получает или задает организатора.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiElectronicAddress](../../com.aspose.email/mapielectronicaddress) |  |

### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


Устанавливает свойство.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | Свойство. |

### setProperty(PropertyDescriptor pd, Object value) {#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-}
```
public void setProperty(PropertyDescriptor pd, Object value)
```


Устанавливает свойство MAPI.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Дескриптор свойства. |
| value | java.lang.Object | Данные свойства. |

### setRecipients(MapiRecipientCollection value) {#setRecipients-com.aspose.email.MapiRecipientCollection-}
```
public final void setRecipients(MapiRecipientCollection value)
```


Получает получателей сообщения.

Значение: Коллекция получателей.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) |  |

### setRecurrence(MapiCalendarEventRecurrence value) {#setRecurrence-com.aspose.email.MapiCalendarEventRecurrence-}
```
public final void setRecurrence(MapiCalendarEventRecurrence value)
```


Получает или задает свойства повторения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiCalendarEventRecurrence](../../com.aspose.email/mapicalendareventrecurrence) |  |

### setReminderDelta(int value) {#setReminderDelta-int-}
```
public final void setReminderDelta(int value)
```


Получает или задает интервал в минутах между моментом, когда напоминание впервые просрочивается, и временем начала объекта Calendar

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setReminderFileParameter(String value) {#setReminderFileParameter-java.lang.String-}
```
public final void setReminderFileParameter(String value)
```


Указывает полный путь к звуку, который клиент ДОЛЖЕН воспроизводить, когда напоминание просрочено.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setReminderSet(boolean value) {#setReminderSet-boolean-}
```
public final void setReminderSet(boolean value)
```


Получает или задает значение, указывающее, установлено ли напоминание для объекта.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setSensitivity(int value) {#setSensitivity-int-}
```
public final void setSensitivity(int value)
```


Gets the Sensitivity.

Значение: Чувствительность.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setSequence(int value) {#setSequence-int-}
```
public final void setSequence(int value)
```


Получает или задает номер последовательности

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Получает или задает дату и время начала события. Если дата не установлена, возвращается значение по умолчанию для java.util.Date.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setStartDateTimeZone(MapiCalendarTimeZone value) {#setStartDateTimeZone-com.aspose.email.MapiCalendarTimeZone-}
```
public final void setStartDateTimeZone(MapiCalendarTimeZone value)
```


Получает или задает информацию о часовом поясе, указывающую часовой пояс свойства StartDate

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiCalendarTimeZone](../../com.aspose.email/mapicalendartimezone) |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Получает или задает тему сообщения.

Значение: Строка, представляющая тему сообщения.

--------------------

При установке значения также обновляются значения свойств SubjectPrefix(PR\_SUBJECT\_PREFIX) и NormalizedSubject(PR\_NORMALIZED\_SUBJECT). Если у Subject нет префикса, значение свойства SubjectPrefix устанавливается в null. При установке значения null или пустой строки значения свойств Subject, SubjectPrefix, NormalizedSubject устанавливаются в null.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setUid(String value) {#setUid-java.lang.String-}
```
public final void setUid(String value)
```


Получает уникальный идентификатор

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
### tryGetPropertyData(long tag) {#tryGetPropertyData-long-}
```
public final byte[] tryGetPropertyData(long tag)
```


Попробуйте получить данные свойства с указанным ключом тега.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Ключ тега. |

**Returns:**
byte[] — Данные свойства.
### tryGetPropertyDateTime(long tag, Date[] value) {#tryGetPropertyDateTime-long-java.util.Date---}
```
public final boolean tryGetPropertyDateTime(long tag, Date[] value)
```


Получает значение указанного свойства как тип DateTime. Возвращаемое значение указывает, удалось ли выполнить операцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |
| value | java.util.Date[] | При возврате этого метода содержит значение указанного свойства, если свойство существует. Этот параметр передаётся неинициализированным. |

**Returns:**
boolean - true, если s был успешно преобразован; иначе false.
### tryGetPropertyInt32(long tag, int[] value) {#tryGetPropertyInt32-long-int---}
```
public final boolean tryGetPropertyInt32(long tag, int[] value)
```


Получает значение указанного свойства как тип Int32. Возвращаемое значение указывает, удалось ли выполнить операцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |
| value | int[] | При возврате этого метода содержит значение указанного свойства, если свойство существует. Этот параметр передаётся неинициализированным. |

**Returns:**
boolean - true, если s был успешно преобразован; иначе false.
### tryGetPropertyLong(long tag, long[] value) {#tryGetPropertyLong-long-long---}
```
public final boolean tryGetPropertyLong(long tag, long[] value)
```


Получает значение указанного свойства как тип Long. Возвращаемое значение указывает, удалось ли выполнить операцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |
| value | long[] | При возврате этого метода содержит значение указанного свойства, если свойство существует. Этот параметр передаётся неинициализированным. |

**Returns:**
boolean - true, если s был успешно преобразован; иначе false.
### tryGetPropertyString(long tag) {#tryGetPropertyString-long-}
```
public final String tryGetPropertyString(long tag)
```


Попробуйте получить данные свойства в виде строки с указанным тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Ключ тега свойства. |

**Returns:**
java.lang.String — строка, содержащая данные свойства.
### tryGetPropertyString(long tag, int codepage) {#tryGetPropertyString-long-int-}
```
public final String tryGetPropertyString(long tag, int codepage)
```


Попробуйте получить данные свойства в виде строки с указанным тегом и кодовой страницей.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Ключ тега свойства. |
| кодовая страница | int | Кодовая страница. |

**Returns:**
java.lang.String — строка, содержащая данные свойства.
### tryGetPropertyString(long tag, String[] value) {#tryGetPropertyString-long-java.lang.String---}
```
public final boolean tryGetPropertyString(long tag, String[] value)
```


Получает значение указанного свойства как тип String. Возвращаемое значение указывает, удалось ли выполнить операцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |
| value | java.lang.String[] | При возврате этого метода содержит значение указанного свойства, если свойство существует. Этот параметр передаётся неинициализированным. |

**Returns:**
boolean - true, если s был успешно преобразован; иначе false.
### tryGetPropertyString(long tag, String[] value, int codepage) {#tryGetPropertyString-long-java.lang.String---int-}
```
public final boolean tryGetPropertyString(long tag, String[] value, int codepage)
```


Получает значение указанного свойства как тип String. Возвращаемое значение указывает, удалось ли выполнить операцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |
| value | java.lang.String[] | При возврате этого метода содержит значение указанного свойства, если свойство существует. Этот параметр передаётся неинициализированным. |
| кодовая страница | int | Указанная кодовая страница, используемая для получения строкового значения. |

**Returns:**
boolean - true, если s был успешно преобразован; иначе false.
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

