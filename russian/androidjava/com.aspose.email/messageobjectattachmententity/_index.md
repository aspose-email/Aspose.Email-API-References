---
title: MessageObjectAttachmentEntity
second_title: Aspose.Email for Android via Java API Reference
description: Представляет сущность вложения.
type: docs
weight: 310
url: /ru/androidjava/com.aspose.email/messageobjectattachmententity/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IMessageObjectPropertyContainer](../../com.aspose.email/imessageobjectpropertycontainer)
```
public final class MessageObjectAttachmentEntity implements IMessageObjectPropertyContainer
```

Представляет сущность вложения.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MessageObjectAttachmentEntity()](#MessageObjectAttachmentEntity--) | Инициализирует новый экземпляр класса [MessageObjectAttachmentEntity](../../com.aspose.email/messageobjectattachmententity). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomAttachmentStorageData()](#getCustomAttachmentStorageData--) | Получает или задает пользовательские данные хранилища вложения. Может быть null. |
| [getEmbeddedMessage()](#getEmbeddedMessage--) | Получает или задает хранилище встроенного объекта сообщения, если присутствует. Может быть null. |
| [getProperties()](#getProperties--) | Получает свойства вложения. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomAttachmentStorageData(CustomAttachmentStorage value)](#setCustomAttachmentStorageData-com.aspose.email.CustomAttachmentStorage-) | Получает или задает пользовательские данные хранилища вложения. Может быть null. |
| [setEmbeddedMessage(MessageObject value)](#setEmbeddedMessage-com.aspose.email.MessageObject-) | Получает или задает хранилище встроенного объекта сообщения, если присутствует. Может быть null. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageObjectAttachmentEntity() {#MessageObjectAttachmentEntity--}
```
public MessageObjectAttachmentEntity()
```


Инициализирует новый экземпляр класса [MessageObjectAttachmentEntity](../../com.aspose.email/messageobjectattachmententity).

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
### getCustomAttachmentStorageData() {#getCustomAttachmentStorageData--}
```
public final CustomAttachmentStorage getCustomAttachmentStorageData()
```


Получает или задает пользовательские данные хранилища вложения. Может быть null.

Значение: Пользовательские данные хранилища вложения.

--------------------

Взаимоисключает с MessageObjectAttachmentEntity.EmbeddedMessage (\\#getEmbeddedMessage.getEmbeddedMessage/\\#setEmbeddedMessage(MessageObject).setEmbeddedMessage(MessageObject)) или оба могут быть null.

**Returns:**
[CustomAttachmentStorage](../../com.aspose.email/customattachmentstorage)
### getEmbeddedMessage() {#getEmbeddedMessage--}
```
public final MessageObject getEmbeddedMessage()
```


Получает или задает хранилище встроенного объекта сообщения, если присутствует. Может быть null.

Значение: Встроенное сообщение.

--------------------

Взаимоисключает с MessageObjectAttachmentEntity.CustomAttachmentStorageData (\\#getCustomAttachmentStorageData.getCustomAttachmentStorageData/\\#setCustomAttachmentStorageData(CustomAttachmentStorage).setCustomAttachmentStorageData(CustomAttachmentStorage)) или оба могут быть null.

**Returns:**
[MessageObject](../../com.aspose.email/messageobject)
### getProperties() {#getProperties--}
```
public final MessageObjectPropertiesCollection getProperties()
```


Получает свойства вложения.

Значение: Коллекция свойств.

**Returns:**
[MessageObjectPropertiesCollection](../../com.aspose.email/messageobjectpropertiescollection)
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




### setCustomAttachmentStorageData(CustomAttachmentStorage value) {#setCustomAttachmentStorageData-com.aspose.email.CustomAttachmentStorage-}
```
public final void setCustomAttachmentStorageData(CustomAttachmentStorage value)
```


Получает или задает пользовательские данные хранилища вложения. Может быть null.

Значение: Пользовательские данные хранилища вложения.

--------------------

Взаимоисключает с MessageObjectAttachmentEntity.EmbeddedMessage (\\#getEmbeddedMessage.getEmbeddedMessage/\\#setEmbeddedMessage(MessageObject).setEmbeddedMessage(MessageObject)) или оба могут быть null.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [CustomAttachmentStorage](../../com.aspose.email/customattachmentstorage) |  |

### setEmbeddedMessage(MessageObject value) {#setEmbeddedMessage-com.aspose.email.MessageObject-}
```
public final void setEmbeddedMessage(MessageObject value)
```


Получает или задает хранилище встроенного объекта сообщения, если присутствует. Может быть null.

Значение: Встроенное сообщение.

--------------------

Взаимоисключает с MessageObjectAttachmentEntity.CustomAttachmentStorageData (\\#getCustomAttachmentStorageData.getCustomAttachmentStorageData/\\#setCustomAttachmentStorageData(CustomAttachmentStorage).setCustomAttachmentStorageData(CustomAttachmentStorage)) или оба могут быть null.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MessageObject](../../com.aspose.email/messageobject) |  |

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

