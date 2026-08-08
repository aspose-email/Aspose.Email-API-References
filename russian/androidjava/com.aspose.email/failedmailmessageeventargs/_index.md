---
title: FailedMailMessageEventArgs
second_title: Aspose.Email for Android via Java API Reference
description: Предоставляет данные для событий MessageSending и MessageSent.
type: docs
weight: 129
url: /ru/androidjava/com.aspose.email/failedmailmessageeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.aspose.email.MailMessageEventArgs](../../com.aspose.email/mailmessageeventargs)
```
public class FailedMailMessageEventArgs extends MailMessageEventArgs
```

Предоставляет данные для событий MessageSending и MessageSent.
## Constructors

| Constructor | Описание |
| --- | --- |
| [FailedMailMessageEventArgs(MailMessage message, Throwable ex)](#FailedMailMessageEventArgs-com.aspose.email.MailMessage-java.lang.Throwable-) | Инициализирует новый экземпляр класса [FailedMailMessageEventArgs](../../com.aspose.email/failedmailmessageeventargs). |
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
| [getOperationError()](#getOperationError--) | Ошибка операции |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FailedMailMessageEventArgs(MailMessage message, Throwable ex) {#FailedMailMessageEventArgs-com.aspose.email.MailMessage-java.lang.Throwable-}
```
public FailedMailMessageEventArgs(MailMessage message, Throwable ex)
```


Инициализирует новый экземпляр класса [FailedMailMessageEventArgs](../../com.aspose.email/failedmailmessageeventargs).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Сообщение. |
| ex | java.lang.Throwable | Ошибка операции |

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
### getOperationError() {#getOperationError--}
```
public final Throwable getOperationError()
```


Ошибка операции

**Returns:**
java.lang.Throwable
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

