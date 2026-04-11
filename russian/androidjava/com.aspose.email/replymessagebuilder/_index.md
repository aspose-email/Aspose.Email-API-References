---
title: ReplyMessageBuilder
second_title: Aspose.Email for Android via Java API Reference
description: Обеспечивает создание и форматирование сообщений‑ответов.
type: docs
weight: 373
url: /ru/androidjava/com.aspose.email/replymessagebuilder/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.ResponseMessageBuilder](../../com.aspose.email/responsemessagebuilder)
```
public class ReplyMessageBuilder extends ResponseMessageBuilder
```

Обеспечивает создание и форматирование сообщений‑ответов.
## Constructors

| Constructor | Описание |
| --- | --- |
| [ReplyMessageBuilder()](#ReplyMessageBuilder--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [buildResponse(MailMessage msg)](#buildResponse-com.aspose.email.MailMessage-) | Создает сообщения-ответы. |
| [buildResponse(MapiMessage msg)](#buildResponse-com.aspose.email.MapiMessage-) | Создает сообщения-ответы. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdditionMode()](#getAdditionMode--) | Получает или задаёт формат сообщения-ответа. |
| [getClass()](#getClass--) |  |
| [getReplyAll()](#getReplyAll--) | Обеспечивает автоматическое добавление получателей в сообщение-ответ. |
| [getResponseText()](#getResponseText--) | Получает или задаёт тело сообщения-ответа. |
| [getSender()](#getSender--) | Получает или задаёт адрес, с которого будет отправлено сообщение-ответ. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdditionMode(int value)](#setAdditionMode-int-) | Получает или задаёт формат сообщения-ответа. |
| [setReplyAll(boolean value)](#setReplyAll-boolean-) | Обеспечивает автоматическое добавление получателей в сообщение-ответ. |
| [setResponseText(String value)](#setResponseText-java.lang.String-) | Получает или задаёт тело сообщения-ответа. |
| [setSender(MailAddress value)](#setSender-com.aspose.email.MailAddress-) | Получает или задаёт адрес, с которого будет отправлено сообщение-ответ. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ReplyMessageBuilder() {#ReplyMessageBuilder--}
```
public ReplyMessageBuilder()
```


### buildResponse(MailMessage msg) {#buildResponse-com.aspose.email.MailMessage-}
```
public MailMessage buildResponse(MailMessage msg)
```


Создает сообщения-ответы.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| msg | [MailMessage](../../com.aspose.email/mailmessage) | Исходное сообщение [MailMessage](../../com.aspose.email/mailmessage). |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Resultant message [MailMessage](../../com.aspose.email/mailmessage).
### buildResponse(MapiMessage msg) {#buildResponse-com.aspose.email.MapiMessage-}
```
public MapiMessage buildResponse(MapiMessage msg)
```


Создает сообщения-ответы.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | Исходное сообщение [MapiMessage](../../com.aspose.email/mapimessage). |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Resultant message [MapiMessage](../../com.aspose.email/mapimessage).
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
### getAdditionMode() {#getAdditionMode--}
```
public final int getAdditionMode()
```


Получает или задаёт формат сообщения-ответа.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getReplyAll() {#getReplyAll--}
```
public final boolean getReplyAll()
```


Обеспечивает автоматическое добавление получателей в сообщение-ответ.

**Returns:**
boolean
### getResponseText() {#getResponseText--}
```
public final String getResponseText()
```


Получает или задаёт тело сообщения-ответа.

--------------------

Может содержать HTML‑теги или ключевые слова RTF, если тип тела исходного сообщения — HTML или RTF соответственно.

**Returns:**
java.lang.String
### getSender() {#getSender--}
```
public final MailAddress getSender()
```


Получает или задаёт адрес, с которого будет отправлено сообщение-ответ.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
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




### setAdditionMode(int value) {#setAdditionMode-int-}
```
public final void setAdditionMode(int value)
```


Получает или задаёт формат сообщения-ответа.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setReplyAll(boolean value) {#setReplyAll-boolean-}
```
public final void setReplyAll(boolean value)
```


Обеспечивает автоматическое добавление получателей в сообщение-ответ.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setResponseText(String value) {#setResponseText-java.lang.String-}
```
public final void setResponseText(String value)
```


Получает или задаёт тело сообщения-ответа.

--------------------

Может содержать HTML‑теги или ключевые слова RTF, если тип тела исходного сообщения — HTML или RTF соответственно.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setSender(MailAddress value) {#setSender-com.aspose.email.MailAddress-}
```
public final void setSender(MailAddress value)
```


Получает или задаёт адрес, с которого будет отправлено сообщение-ответ.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

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

