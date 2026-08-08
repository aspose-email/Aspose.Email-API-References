---
title: OlmMessageInfo
second_title: Aspose.Email for Android via Java API Reference
description: Представляет информацию о сообщении в хранилище OLM.
type: docs
weight: 338
url: /ru/androidjava/com.aspose.email/olmmessageinfo/
---

**Inheritance:**
java.lang.Object
```
public class OlmMessageInfo
```

Представляет информацию о сообщении в хранилище OLM.
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDate()](#getDate--) | Получает дату сообщения. |
| [getFrom()](#getFrom--) | Получает адрес отправителя. |
| [getMessageClass()](#getMessageClass--) | Получает чувствительную к регистру строку, идентифицирующую пользовательский класс сообщения, например IPM.Note. |
| [getModifiedDate()](#getModifiedDate--) | Получает дату сообщения. |
| [getSubject()](#getSubject--) | Gets the message subject. |
| [getTo()](#getTo--) | Получает коллекцию адресов, содержащую получателей сообщения. |
| [hasAttachments()](#hasAttachments--) | Получает или задает значение, указывающее, имеет ли сообщение вложения. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getDate() {#getDate--}
```
public final Date getDate()
```


Получает дату сообщения.

**Returns:**
java.util.Date
### getFrom() {#getFrom--}
```
public final MapiElectronicAddress getFrom()
```


Получает адрес отправителя.

**Returns:**
[MapiElectronicAddress](../../com.aspose.email/mapielectronicaddress)
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Возвращает чувствительную к регистру строку, идентифицирующую определённый отправителем класс сообщения, например IPM.Note. Класс сообщения указывает тип, назначение или содержание сообщения.

**Returns:**
java.lang.String
### getModifiedDate() {#getModifiedDate--}
```
public final Date getModifiedDate()
```


Получает дату сообщения.

**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the message subject.

**Returns:**
java.lang.String
### getTo() {#getTo--}
```
public final List<MapiElectronicAddress> getTo()
```


Получает коллекцию адресов, содержащую получателей сообщения.

**Returns:**
java.util.List<com.aspose.email.MapiElectronicAddress>
### hasAttachments() {#hasAttachments--}
```
public final boolean hasAttachments()
```


Получает или задает значение, указывающее, имеет ли сообщение вложения.

Значение:  true  если у этого экземпляра есть вложения; в противном случае,  false .

**Returns:**
boolean
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

