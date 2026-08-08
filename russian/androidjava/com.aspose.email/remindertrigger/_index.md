---
title: ReminderTrigger
second_title: Aspose.Email for Android via Java API Reference
description: Указывает, когда сработает тревога.
type: docs
weight: 372
url: /ru/androidjava/com.aspose.email/remindertrigger/
---

**Inheritance:**
java.lang.Object
```
public class ReminderTrigger
```

Указывает, когда сработает тревога.
## Constructors

| Constructor | Описание |
| --- | --- |
| [ReminderTrigger(Date dateTime)](#ReminderTrigger-java.util.Date-) | Инициализирует новый экземпляр класса [ReminderTrigger](../../com.aspose.email/remindertrigger). |
| [ReminderTrigger(ReminderDuration duration, int related)](#ReminderTrigger-com.aspose.email.ReminderDuration-int-) | Инициализирует новый экземпляр класса [ReminderTrigger](../../com.aspose.email/remindertrigger). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDateTime()](#getDateTime--) | Триггер, установленный на абсолютную дату/время. |
| [getDuration()](#getDuration--) | Указывает относительное время для триггера сигнала. |
| [getRelated()](#getRelated--) | Укажите взаимосвязь срабатывания тревоги относительно начала или окончания события. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDateTime(Date value)](#setDateTime-java.util.Date-) | Триггер, установленный на абсолютную дату/время. |
| [setDuration(ReminderDuration value)](#setDuration-com.aspose.email.ReminderDuration-) | Указывает относительное время для триггера сигнала. |
| [setRelated(int value)](#setRelated-int-) | Укажите взаимосвязь срабатывания тревоги относительно начала или окончания события. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ReminderTrigger(Date dateTime) {#ReminderTrigger-java.util.Date-}
```
public ReminderTrigger(Date dateTime)
```


Инициализирует новый экземпляр класса [ReminderTrigger](../../com.aspose.email/remindertrigger).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| dateTime | java.util.Date | Значение абсолютного DateTime. |

### ReminderTrigger(ReminderDuration duration, int related) {#ReminderTrigger-com.aspose.email.ReminderDuration-int-}
```
public ReminderTrigger(ReminderDuration duration, int related)
```


Инициализирует новый экземпляр класса [ReminderTrigger](../../com.aspose.email/remindertrigger).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| duration | [ReminderDuration](../../com.aspose.email/reminderduration) | Для указания относительного времени для триггера сигнала. |
| связано | int | Для указания отношения триггера сигнала относительно начала или окончания события. |

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
### getDateTime() {#getDateTime--}
```
public final Date getDateTime()
```


Триггер, установленный на абсолютную дату/время.

**Returns:**
java.util.Date
### getDuration() {#getDuration--}
```
public final ReminderDuration getDuration()
```


Указывает относительное время для триггера сигнала.

**Returns:**
[ReminderDuration](../../com.aspose.email/reminderduration)
### getRelated() {#getRelated--}
```
public final int getRelated()
```


Укажите взаимосвязь срабатывания тревоги относительно начала или окончания события.

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




### setDateTime(Date value) {#setDateTime-java.util.Date-}
```
public final void setDateTime(Date value)
```


Триггер, установленный на абсолютную дату/время.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setDuration(ReminderDuration value) {#setDuration-com.aspose.email.ReminderDuration-}
```
public final void setDuration(ReminderDuration value)
```


Указывает относительное время для триггера сигнала.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [ReminderDuration](../../com.aspose.email/reminderduration) |  |

### setRelated(int value) {#setRelated-int-}
```
public final void setRelated(int value)
```


Укажите взаимосвязь срабатывания тревоги относительно начала или окончания события.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

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

