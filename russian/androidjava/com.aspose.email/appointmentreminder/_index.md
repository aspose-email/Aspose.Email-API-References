---
title: AppointmentReminder
second_title: Aspose.Email for Android via Java API Reference
description: Предоставляет группу свойств компонента, определяющих сигнализацию.
type: docs
weight: 35
url: /ru/androidjava/com.aspose.email/appointmentreminder/
---

**Inheritance:**
java.lang.Object
```
public class AppointmentReminder
```

Предоставляет группу свойств компонента, определяющих сигнализацию.
## Constructors

| Constructor | Описание |
| --- | --- |
| [AppointmentReminder()](#AppointmentReminder--) | Инициализирует новый экземпляр класса [AppointmentReminder](../../com.aspose.email/appointmentreminder). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Определяет действие, которое будет вызвано при срабатывании сигнала тревоги. |
| [getAttachments()](#getAttachments--) | Содержит коллекцию объектов ReminderAttachment [ReminderAttachment](../../com.aspose.email/reminderattachment). |
| [getAttendees()](#getAttendees--) | Содержит коллекцию объектов ReminderAttendee [ReminderAttendee](../../com.aspose.email/reminderattendee). |
| [getClass()](#getClass--) |  |
| [getDefault15MinReminder()](#getDefault15MinReminder--) | Получает напоминание по умолчанию на 15 минут. |
| [getDescription()](#getDescription--) | Предоставляет более полное описание сигнала тревоги. |
| [getDuration()](#getDuration--) | Указывает период задержки, после которой сигнал тревоги будет повторяться. |
| [getRepeat()](#getRepeat--) | Определяет количество раз, которое сигнал тревоги должен повторяться после первоначального срабатывания. |
| [getSummary()](#getSummary--) | Определяет краткое резюме или тему сигнала тревоги. |
| [getTrigger()](#getTrigger--) | Указывает, когда сработает тревога. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | Определяет действие, которое будет вызвано при срабатывании сигнала тревоги. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Предоставляет более полное описание сигнала тревоги. |
| [setDuration(ReminderDuration value)](#setDuration-com.aspose.email.ReminderDuration-) | Указывает период задержки, после которой сигнал тревоги будет повторяться. |
| [setRepeat(int value)](#setRepeat-int-) | Определяет количество раз, которое сигнал тревоги должен повторяться после первоначального срабатывания. |
| [setSummary(String value)](#setSummary-java.lang.String-) | Определяет краткое резюме или тему сигнала тревоги. |
| [setTrigger(ReminderTrigger value)](#setTrigger-com.aspose.email.ReminderTrigger-) | Указывает, когда сработает тревога. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AppointmentReminder() {#AppointmentReminder--}
```
public AppointmentReminder()
```


Инициализирует новый экземпляр класса [AppointmentReminder](../../com.aspose.email/appointmentreminder).

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


Определяет действие, которое будет вызвано при срабатывании сигнала тревоги.

**Returns:**
int
### getAttachments() {#getAttachments--}
```
public final ReminderAttachmentCollection getAttachments()
```


Содержит коллекцию объектов ReminderAttachment [ReminderAttachment](../../com.aspose.email/reminderattachment).

**Returns:**
[ReminderAttachmentCollection](../../com.aspose.email/reminderattachmentcollection)
### getAttendees() {#getAttendees--}
```
public final ReminderAttendeeCollection getAttendees()
```


Содержит коллекцию объектов ReminderAttendee [ReminderAttendee](../../com.aspose.email/reminderattendee).

**Returns:**
[ReminderAttendeeCollection](../../com.aspose.email/reminderattendeecollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault15MinReminder() {#getDefault15MinReminder--}
```
public static AppointmentReminder getDefault15MinReminder()
```


Получает напоминание по умолчанию на 15 минут.

**Returns:**
[AppointmentReminder](../../com.aspose.email/appointmentreminder)
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Предоставляет более полное описание сигнала тревоги.

**Returns:**
java.lang.String
### getDuration() {#getDuration--}
```
public final ReminderDuration getDuration()
```


Указывает период задержки, после которой сигнал тревоги будет повторяться.

**Returns:**
[ReminderDuration](../../com.aspose.email/reminderduration)
### getRepeat() {#getRepeat--}
```
public final int getRepeat()
```


Определяет количество раз, которое сигнал тревоги должен повторяться после первоначального срабатывания.

**Returns:**
int
### getSummary() {#getSummary--}
```
public final String getSummary()
```


Определяет краткое резюме или тему сигнала тревоги.

**Returns:**
java.lang.String
### getTrigger() {#getTrigger--}
```
public final ReminderTrigger getTrigger()
```


Указывает, когда сработает тревога.

**Returns:**
[ReminderTrigger](../../com.aspose.email/remindertrigger)
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


Определяет действие, которое будет вызвано при срабатывании сигнала тревоги.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Предоставляет более полное описание сигнала тревоги.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setDuration(ReminderDuration value) {#setDuration-com.aspose.email.ReminderDuration-}
```
public final void setDuration(ReminderDuration value)
```


Указывает период задержки, после которой сигнал тревоги будет повторяться.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [ReminderDuration](../../com.aspose.email/reminderduration) |  |

### setRepeat(int value) {#setRepeat-int-}
```
public final void setRepeat(int value)
```


Определяет количество раз, которое сигнал тревоги должен повторяться после первоначального срабатывания.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setSummary(String value) {#setSummary-java.lang.String-}
```
public final void setSummary(String value)
```


Определяет краткое резюме или тему сигнала тревоги.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setTrigger(ReminderTrigger value) {#setTrigger-com.aspose.email.ReminderTrigger-}
```
public final void setTrigger(ReminderTrigger value)
```


Указывает, когда сработает тревога.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [ReminderTrigger](../../com.aspose.email/remindertrigger) |  |

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

