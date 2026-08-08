---
title: Календарь
second_title: Aspose.Email for Android via Java API Reference
description: Набор метаданных, например описание одного календаря.
type: docs
weight: 65
url: /ru/androidjava/com.aspose.email/calendar/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.BaseDataObject](../../com.aspose.email/basedataobject)
```
public class Calendar extends BaseDataObject
```

Набор метаданных, таких как описание, для одного календаря.
## Constructors

| Constructor | Описание |
| --- | --- |
| [Calendar()](#Calendar--) | Инициализирует новый экземпляр класса Calendar. |
| [Calendar(String summary)](#Calendar-java.lang.String-) | Инициализирует новый экземпляр класса Calendar. |
| [Calendar(String id, String summary)](#Calendar-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса Calendar. |
| [Calendar(String summary, String description, String location, String timeZone)](#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса Calendar. |
| [Calendar(String id, String summary, String description, String location, String timeZone)](#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса Calendar. |
| [Calendar(String id, String eTag, String summary, String description, String location, String timeZone)](#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса Calendar. |
## Поля

| Поле | Описание |
| --- | --- |
| [CALENDAR_KIND](#CALENDAR-KIND) | Тип ресурса 'calendar\#calendar'. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConferenceProperties()](#getConferenceProperties--) | Получает свойства конференций для этого календаря. |
| [getDescription()](#getDescription--) | Описание календаря. |
| [getETag()](#getETag--) | ETag или entity tag — один из нескольких механизмов, которые HTTP предоставляет для проверки веб‑кэша, и который позволяет клиенту выполнять условные запросы. |
| [getId()](#getId--) | Идентификатор ресурса. |
| [getKind()](#getKind--) | Тип ресурса |
| [getLocation()](#getLocation--) | Географическое расположение календаря в виде свободного текста. |
| [getSummary()](#getSummary--) | Заголовок календаря. |
| [getTimeZone()](#getTimeZone--) | Часовой пояс календаря. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | Описание календаря. |
| [setETag(String value)](#setETag-java.lang.String-) | ETag или entity tag — один из нескольких механизмов, которые HTTP предоставляет для проверки веб‑кэша, и который позволяет клиенту выполнять условные запросы. |
| [setId(String value)](#setId-java.lang.String-) | Идентификатор ресурса. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Географическое расположение календаря в виде свободного текста. |
| [setSummary(String value)](#setSummary-java.lang.String-) | Заголовок календаря. |
| [setTimeZone(String value)](#setTimeZone-java.lang.String-) | Часовой пояс календаря. |
| [toString()](#toString--) | Возвращает строку, представляющую экземпляр объекта. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Calendar() {#Calendar--}
```
public Calendar()
```


Инициализирует новый экземпляр класса Calendar.

### Calendar(String summary) {#Calendar-java.lang.String-}
```
public Calendar(String summary)
```


Инициализирует новый экземпляр класса Calendar.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| резюме | java.lang.String | Заголовок календаря. |

### Calendar(String id, String summary) {#Calendar-java.lang.String-java.lang.String-}
```
public Calendar(String id, String summary)
```


Инициализирует новый экземпляр класса Calendar.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| id | java.lang.String | Идентификатор ресурса. |
| резюме | java.lang.String | Заголовок календаря. |

### Calendar(String summary, String description, String location, String timeZone) {#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public Calendar(String summary, String description, String location, String timeZone)
```


Инициализирует новый экземпляр класса Calendar.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| резюме | java.lang.String | Заголовок календаря. |
| описание | java.lang.String | Описание календаря. |
| местоположение | java.lang.String | Географическое расположение календаря в виде свободного текста. |
| timeZone | java.lang.String | Часовой пояс календаря. |

### Calendar(String id, String summary, String description, String location, String timeZone) {#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public Calendar(String id, String summary, String description, String location, String timeZone)
```


Инициализирует новый экземпляр класса Calendar.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| id | java.lang.String | Идентификатор ресурса. |
| резюме | java.lang.String | Заголовок календаря. |
| описание | java.lang.String | Описание календаря. |
| местоположение | java.lang.String | Географическое расположение календаря в виде свободного текста. |
| timeZone | java.lang.String | Часовой пояс календаря. |

### Calendar(String id, String eTag, String summary, String description, String location, String timeZone) {#Calendar-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public Calendar(String id, String eTag, String summary, String description, String location, String timeZone)
```


Инициализирует новый экземпляр класса Calendar.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| id | java.lang.String | Идентификатор ресурса. |
| eTag | java.lang.String | Тег сущности |
| резюме | java.lang.String | Заголовок календаря. |
| описание | java.lang.String | Описание календаря. |
| местоположение | java.lang.String | Географическое расположение календаря в виде свободного текста. |
| timeZone | java.lang.String | Часовой пояс календаря. |

### CALENDAR_KIND {#CALENDAR-KIND}
```
public static final String CALENDAR_KIND
```


Тип ресурса 'calendar\#calendar'.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConferenceProperties() {#getConferenceProperties--}
```
public ConferenceProperties getConferenceProperties()
```


Получает свойства конференций для этого календаря.

**Returns:**
[ConferenceProperties](../../com.aspose.email/conferenceproperties)
### getDescription() {#getDescription--}
```
public String getDescription()
```


Описание календаря.

**Returns:**
java.lang.String
### getETag() {#getETag--}
```
public String getETag()
```


ETag или entity tag — один из нескольких механизмов, которые HTTP предоставляет для проверки веб‑кэша, и который позволяет клиенту выполнять условные запросы. Это делает кэши более эффективными и экономит пропускную способность, поскольку веб‑серверу не нужно отправлять полный ответ, если содержимое не изменилось. ETag также могут использоваться для оптимистичного контроля конкурентности, как способ помочь предотвратить перезапись друг друга при одновременных обновлениях ресурса.

**Returns:**
java.lang.String
### getId() {#getId--}
```
public String getId()
```


Идентификатор ресурса.

**Returns:**
java.lang.String
### getKind() {#getKind--}
```
public String getKind()
```


Тип ресурса

**Returns:**
java.lang.String
### getLocation() {#getLocation--}
```
public String getLocation()
```


Географическое расположение календаря в виде свободного текста.

**Returns:**
java.lang.String
### getSummary() {#getSummary--}
```
public String getSummary()
```


Заголовок календаря.

**Returns:**
java.lang.String
### getTimeZone() {#getTimeZone--}
```
public String getTimeZone()
```


Часовой пояс календаря.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Описание календаря.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setETag(String value) {#setETag-java.lang.String-}
```
public void setETag(String value)
```


ETag или entity tag — один из нескольких механизмов, которые HTTP предоставляет для проверки веб‑кэша, и который позволяет клиенту выполнять условные запросы. Это делает кэши более эффективными и экономит пропускную способность, поскольку веб‑серверу не нужно отправлять полный ответ, если содержимое не изменилось. ETag также могут использоваться для оптимистичного контроля конкурентности, как способ помочь предотвратить перезапись друг друга при одновременных обновлениях ресурса.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setId(String value) {#setId-java.lang.String-}
```
public void setId(String value)
```


Идентификатор ресурса.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setLocation(String value) {#setLocation-java.lang.String-}
```
public void setLocation(String value)
```


Географическое расположение календаря в виде свободного текста.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setSummary(String value) {#setSummary-java.lang.String-}
```
public void setSummary(String value)
```


Заголовок календаря.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setTimeZone(String value) {#setTimeZone-java.lang.String-}
```
public void setTimeZone(String value)
```


Часовой пояс календаря.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую экземпляр объекта.

**Returns:**
java.lang.String - Возвращает строку, представляющую экземпляр объекта.
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

