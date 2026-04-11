---
title: AppointmentIcsSaveOptions
second_title: Aspose.Email for Android via Java API Reference
description: Представляет параметры сохранения iCalendar
type: docs
weight: 31
url: /ru/androidjava/com.aspose.email/appointmenticssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AppointmentSaveOptions](../../com.aspose.email/appointmentsaveoptions)
```
public final class AppointmentIcsSaveOptions extends AppointmentSaveOptions
```

Представляет параметры сохранения iCalendar
## Constructors

| Constructor | Описание |
| --- | --- |
| [AppointmentIcsSaveOptions()](#AppointmentIcsSaveOptions--) | Инициализирует новый экземпляр класса [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) |
| [AppointmentIcsSaveOptions(int method)](#AppointmentIcsSaveOptions-int-) | Инициализирует новый экземпляр класса [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions) |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Получает или задает действие встречи |
| [getClass()](#getClass--) |  |
| [getCreateNew()](#getCreateNew--) | Получает или задает значение, указывающее, нужно ли создавать новый календарь или добавлять события в существующий календарь. |
| [getDefault()](#getDefault--) | Получает параметры сохранения Ics по умолчанию |
| [getEndTimeZone()](#getEndTimeZone--) | Получает или задает часовой пояс окончания. |
| [getMethodType()](#getMethodType--) | Получает или задает тип метода объекта iCalendar, связанный с объектом календаря. |
| [getProductId()](#getProductId--) | Получает или задает идентификатор продукта, создавшего объект iCalendar. |
| [getSaveFormat()](#getSaveFormat--) | Получает формат сохранения |
| [getSequenceId()](#getSequenceId--) | Получает или задает идентификатор последовательности. |
| [getStartTimeZone()](#getStartTimeZone--) | Получает или задает часовой пояс начала. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | Получает или задает действие встречи |
| [setCreateNew(boolean value)](#setCreateNew-boolean-) | Получает или задает значение, указывающее, нужно ли создавать новый календарь или добавлять события в существующий календарь. |
| [setEndTimeZone(String value)](#setEndTimeZone-java.lang.String-) | Получает или задает часовой пояс окончания. |
| [setMethodType(int value)](#setMethodType-int-) | Получает или задает тип метода объекта iCalendar, связанный с объектом календаря. |
| [setProductId(String value)](#setProductId-java.lang.String-) | Получает или задает идентификатор продукта, создавшего объект iCalendar. |
| [setSequenceId(int value)](#setSequenceId-int-) | Получает или задает идентификатор последовательности. |
| [setStartTimeZone(String value)](#setStartTimeZone-java.lang.String-) | Получает или задает часовой пояс начала. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AppointmentIcsSaveOptions() {#AppointmentIcsSaveOptions--}
```
public AppointmentIcsSaveOptions()
```


Инициализирует новый экземпляр класса [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions)

### AppointmentIcsSaveOptions(int method) {#AppointmentIcsSaveOptions-int-}
```
public AppointmentIcsSaveOptions(int method)
```


Инициализирует новый экземпляр класса [AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions)

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| метод | int | Метод встречи |

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
### getAction() {#getAction--}
```
public final int getAction()
```


Получает или задает действие встречи

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreateNew() {#getCreateNew--}
```
public final boolean getCreateNew()
```


Получает или задает значение, указывающее, нужно ли создавать новый календарь или добавлять события в существующий календарь. Значение по умолчанию — true.

**Returns:**
boolean
### getDefault() {#getDefault--}
```
public static AppointmentIcsSaveOptions getDefault()
```


Получает параметры сохранения Ics по умолчанию

**Returns:**
[AppointmentIcsSaveOptions](../../com.aspose.email/appointmenticssaveoptions)
### getEndTimeZone() {#getEndTimeZone--}
```
public final String getEndTimeZone()
```


Получает или задает часовой пояс окончания.

**Returns:**
java.lang.String
### getMethodType() {#getMethodType--}
```
public final int getMethodType()
```


Получает или задает тип метода объекта iCalendar, связанный с объектом календаря.

**Returns:**
int
### getProductId() {#getProductId--}
```
public final String getProductId()
```


Получает или задает идентификатор продукта, создавшего объект iCalendar.

Значение: идентификатор продукта.

**Returns:**
java.lang.String
### getSaveFormat() {#getSaveFormat--}
```
public final int getSaveFormat()
```


Получает формат сохранения

**Returns:**
int
### getSequenceId() {#getSequenceId--}
```
public final int getSequenceId()
```


Получает или задает идентификатор последовательности.

Значение: идентификатор последовательности.

**Returns:**
int
### getStartTimeZone() {#getStartTimeZone--}
```
public final String getStartTimeZone()
```


Получает или задает часовой пояс начала.

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




### setAction(int value) {#setAction-int-}
```
public final void setAction(int value)
```


Получает или задает действие встречи

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setCreateNew(boolean value) {#setCreateNew-boolean-}
```
public final void setCreateNew(boolean value)
```


Получает или задает значение, указывающее, нужно ли создавать новый календарь или добавлять события в существующий календарь. Значение по умолчанию — true.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setEndTimeZone(String value) {#setEndTimeZone-java.lang.String-}
```
public final void setEndTimeZone(String value)
```


Получает или задает часовой пояс окончания.

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

### setProductId(String value) {#setProductId-java.lang.String-}
```
public final void setProductId(String value)
```


Получает или задает идентификатор продукта, создавшего объект iCalendar.

Значение: идентификатор продукта.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setSequenceId(int value) {#setSequenceId-int-}
```
public final void setSequenceId(int value)
```


Получает или задает идентификатор последовательности.

Значение: идентификатор последовательности.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setStartTimeZone(String value) {#setStartTimeZone-java.lang.String-}
```
public final void setStartTimeZone(String value)
```


Получает или задает часовой пояс начала.

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

