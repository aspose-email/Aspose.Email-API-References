---
title: DailyRecurrencePattern
second_title: Aspose.Email for Android via Java API Reference
description: Представляет шаблон повторения ежедневного типа.
type: docs
weight: 93
url: /ru/androidjava/com.aspose.email/dailyrecurrencepattern/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.RecurrencePattern](../../com.aspose.email/recurrencepattern)
```
public class DailyRecurrencePattern extends RecurrencePattern
```

Представляет шаблон повторения ежедневного типа.
## Constructors

| Constructor | Описание |
| --- | --- |
| [DailyRecurrencePattern(Date endDate)](#DailyRecurrencePattern-java.util.Date-) | Инициализирует новый экземпляр класса [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern). |
| [DailyRecurrencePattern(int occurs)](#DailyRecurrencePattern-int-) | Инициализирует новый экземпляр класса [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern). |
| [DailyRecurrencePattern(Date endDate, int interval)](#DailyRecurrencePattern-java.util.Date-int-) | Инициализирует новый экземпляр класса [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern). |
| [DailyRecurrencePattern(int occurs, int interval)](#DailyRecurrencePattern-int-int-) | Инициализирует новый экземпляр класса [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEndDate()](#getEndDate--) | Получает или задает конечную дату. |
| [getInterval()](#getInterval--) | Получает или задает количество единиц повторения. |
| [getOccurs()](#getOccurs--) | Получает или задает количество повторений шаблона повторения. |
| [getWeekStart()](#getWeekStart--) | Получает или задает начало недели. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Получает или задает конечную дату. |
| [setInterval(int value)](#setInterval-int-) | Получает или задает количество единиц повторения. |
| [setOccurs(int value)](#setOccurs-int-) | Получает или задает количество повторений шаблона повторения. |
| [setWeekStart(int value)](#setWeekStart-int-) | Получает или задает начало недели. |
| [toString()](#toString--) | Возвращает строку, представляющую текущий объект. |
| [to_RecurrencePattern(String value)](#to-RecurrencePattern-java.lang.String-) | Преобразует строковое представление шаблона повторения в формате ICalendar в объект |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DailyRecurrencePattern(Date endDate) {#DailyRecurrencePattern-java.util.Date-}
```
public DailyRecurrencePattern(Date endDate)
```


Инициализирует новый экземпляр класса [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| endDate | java.util.Date | Конечная дата. |

### DailyRecurrencePattern(int occurs) {#DailyRecurrencePattern-int-}
```
public DailyRecurrencePattern(int occurs)
```


Инициализирует новый экземпляр класса [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| происходит | int | Значение Int32, представляющее количество повторений. |

### DailyRecurrencePattern(Date endDate, int interval) {#DailyRecurrencePattern-java.util.Date-int-}
```
public DailyRecurrencePattern(Date endDate, int interval)
```


Инициализирует новый экземпляр класса [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| endDate | java.util.Date | Конечная дата. |
| интервал | int | Количество единиц повторения. |

### DailyRecurrencePattern(int occurs, int interval) {#DailyRecurrencePattern-int-int-}
```
public DailyRecurrencePattern(int occurs, int interval)
```


Инициализирует новый экземпляр класса [DailyRecurrencePattern](../../com.aspose.email/dailyrecurrencepattern).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| происходит | int | Значение Int32, представляющее количество повторений. |
| интервал | int | Количество единиц повторения. |

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
### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Получает или задает конечную дату.

Значение: Конечная дата.

**Returns:**
java.util.Date
### getInterval() {#getInterval--}
```
public final int getInterval()
```


Получает или задает количество единиц повторения.

Значение: Количество единиц повторения.

**Returns:**
int
### getOccurs() {#getOccurs--}
```
public final int getOccurs()
```


Получает или задает количество повторений шаблона повторения.

Значение: число вхождений.

**Returns:**
int
### getWeekStart() {#getWeekStart--}
```
public final int getWeekStart()
```


Получает или задает начало недели.

Значение: начало недели.

**Returns:**
int
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




### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Получает или задает конечную дату.

Значение: Конечная дата.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setInterval(int value) {#setInterval-int-}
```
public final void setInterval(int value)
```


Получает или задает количество единиц повторения.

Значение: Количество единиц повторения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setOccurs(int value) {#setOccurs-int-}
```
public final void setOccurs(int value)
```


Получает или задает количество повторений шаблона повторения.

Значение: число вхождений.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setWeekStart(int value) {#setWeekStart-int-}
```
public final void setWeekStart(int value)
```


Получает или задает начало недели.

Значение: начало недели.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую текущий объект.

**Returns:**
java.lang.String — строка, представляющая текущий объект.
### to_RecurrencePattern(String value) {#to-RecurrencePattern-java.lang.String-}
```
public static RecurrencePattern to_RecurrencePattern(String value)
```


Преобразует строковое представление шаблона повторения в формате ICalendar в объект

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String | Возвращает объект RecurrencePattern |

**Returns:**
[RecurrencePattern](../../com.aspose.email/recurrencepattern)
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

