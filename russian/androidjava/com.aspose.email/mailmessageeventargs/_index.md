---
title: MailMessageEventArgs
second_title: Aspose.Email for Android via Java API Reference
description: Предоставляет данные для событий MessageSending и MessageSent.
type: docs
weight: 194
url: /ru/androidjava/com.aspose.email/mailmessageeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class MailMessageEventArgs extends System.EventArgs
```

Предоставляет данные для событий MessageSending и MessageSent.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MailMessageEventArgs(MailMessage message)](#MailMessageEventArgs-com.aspose.email.MailMessage-) | Инициализирует новый экземпляр класса [MailMessageEventArgs](../../com.aspose.email/mailmessageeventargs). |
## Поля

| Поле | Описание |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMessage()](#getMessage--) | Получает отправляемое сообщение. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailMessageEventArgs(MailMessage message) {#MailMessageEventArgs-com.aspose.email.MailMessage-}
```
public MailMessageEventArgs(MailMessage message)
```


Инициализирует новый экземпляр класса [MailMessageEventArgs](../../com.aspose.email/mailmessageeventargs).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Сообщение. |

### Empty {#Empty}
```
public static final System.EventArgs Empty
```


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
### getMessage() {#getMessage--}
```
public final MailMessage getMessage()
```


Получает отправляемое сообщение.

Значение: MailMessage.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
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

