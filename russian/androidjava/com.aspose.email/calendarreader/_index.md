---
title: CalendarReader
second_title: Aspose.Email for Android via Java API Reference
description: Позволяет читать календарь с множеством событий в объект Appointment из файла или потока.
type: docs
weight: 68
url: /ru/androidjava/com.aspose.email/calendarreader/
---

**Inheritance:**
java.lang.Object
```
public class CalendarReader
```

Позволяет читать календарь с множеством событий в объект Appointment из файла или потока.
## Constructors

| Constructor | Описание |
| --- | --- |
| [CalendarReader(String path)](#CalendarReader-java.lang.String-) | Инициализирует новый экземпляр CalendarReader с исходным файлом и параметрами загрузки Appointment по умолчанию. |
| [CalendarReader(String path, AppointmentLoadOptions options)](#CalendarReader-java.lang.String-com.aspose.email.AppointmentLoadOptions-) | Инициализирует новый экземпляр CalendarReader с исходным файлом и параметрами загрузки Appointment. |
| [CalendarReader(InputStream stream)](#CalendarReader-java.io.InputStream-) | Инициализирует новый экземпляр CalendarReader с исходным потоком и параметрами загрузки Appointment по умолчанию. |
| [CalendarReader(InputStream stream, AppointmentLoadOptions options)](#CalendarReader-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-) | Инициализирует новый экземпляр CalendarReader с исходным потоком и параметрами загрузки Appointment. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCurrent()](#getCurrent--) | Текущее читаемое событие. |
| [hashCode()](#hashCode--) |  |
| [nextEvent()](#nextEvent--) | Считывает следующее событие Event из источника и сохраняет его в Current. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CalendarReader(String path) {#CalendarReader-java.lang.String-}
```
public CalendarReader(String path)
```


Инициализирует новый экземпляр CalendarReader с исходным файлом и параметрами загрузки Appointment по умолчанию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| путь | java.lang.String | Path to source file. |

### CalendarReader(String path, AppointmentLoadOptions options) {#CalendarReader-java.lang.String-com.aspose.email.AppointmentLoadOptions-}
```
public CalendarReader(String path, AppointmentLoadOptions options)
```


Инициализирует новый экземпляр CalendarReader с исходным файлом и параметрами загрузки Appointment.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| путь | java.lang.String | Path to source file. |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | Дополнительные LoadOptions. |

### CalendarReader(InputStream stream) {#CalendarReader-java.io.InputStream-}
```
public CalendarReader(InputStream stream)
```


Инициализирует новый экземпляр CalendarReader с исходным потоком и параметрами загрузки Appointment по умолчанию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Исходный поток. |

### CalendarReader(InputStream stream, AppointmentLoadOptions options) {#CalendarReader-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-}
```
public CalendarReader(InputStream stream, AppointmentLoadOptions options)
```


Инициализирует новый экземпляр CalendarReader с исходным потоком и параметрами загрузки Appointment.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Исходный поток. |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | Дополнительные LoadOptions. |

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
### getCurrent() {#getCurrent--}
```
public final Appointment getCurrent()
```


Текущее читаемое событие.

**Returns:**
[Appointment](../../com.aspose.email/appointment)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### nextEvent() {#nextEvent--}
```
public final boolean nextEvent()
```


Считывает следующее событие Event из источника и сохраняет его в Current.

**Returns:**
boolean — True, если успешно, иначе false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

