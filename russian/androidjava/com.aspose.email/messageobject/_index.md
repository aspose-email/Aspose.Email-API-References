---
title: MessageObject
second_title: Aspose.Email for Android via Java API Reference
description: Представляет объект сообщения Outlook.
type: docs
weight: 309
url: /ru/androidjava/com.aspose.email/messageobject/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IMessageObjectPropertyContainer](../../com.aspose.email/imessageobjectpropertycontainer)
```
public final class MessageObject implements IMessageObjectPropertyContainer
```

Представляет объект сообщения Outlook. Ограничения оценки: при загрузке сообщения читается только 1 вложение и 1 получатель, при сохранении будет добавлен водяной знак.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MessageObject(InputStream stream, int loadFormat)](#MessageObject-java.io.InputStream-int-) | Инициализирует новый экземпляр класса [MessageObject](../../com.aspose.email/messageobject). |
| [MessageObject(String fileName, int loadFormat)](#MessageObject-java.lang.String-int-) | Инициализирует новый экземпляр класса [MessageObject](../../com.aspose.email/messageobject). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachments()](#getAttachments--) | Получает вложения объекта [MessageObject](../../com.aspose.email/messageobject). |
| [getClass()](#getClass--) |  |
| [getCodepage()](#getCodepage--) | Получает кодовую страницу, используемую для кодирования/декодирования строковых свойств в случае, когда используется тип [MapiType.PT\_STRING8](../../com.aspose.email/mapitype\#PT-STRING8). |
| [getIdForNamedProperty()](#getIdForNamedProperty--) | Получает идентификатор, который будет использоваться для именованного свойства; именованные свойства являются специальными свойствами и их идентификаторы должны находиться в диапазоне [0x8000,0xfffe], выравниваясь последовательно, начиная с 0x8000. |
| [getProperties()](#getProperties--) | Получает свойства объекта [MessageObject](../../com.aspose.email/messageobject). |
| [getRecipients()](#getRecipients--) | Получает получателей объекта [MessageObject](../../com.aspose.email/messageobject). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Сохраняет текущий объект сообщения в указанный поток. |
| [save(String fileName, int format)](#save-java.lang.String-int-) | Сохраняет текущий объект сообщения в указанный файл. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageObject(InputStream stream, int loadFormat) {#MessageObject-java.io.InputStream-int-}
```
public MessageObject(InputStream stream, int loadFormat)
```


Инициализирует новый экземпляр класса [MessageObject](../../com.aspose.email/messageobject).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого инициализируется этот объект. |
| loadFormat | int | Формат исходного сообщения, в котором хранится объект сообщения. |

### MessageObject(String fileName, int loadFormat) {#MessageObject-java.lang.String-int-}
```
public MessageObject(String fileName, int loadFormat)
```


Инициализирует новый экземпляр класса [MessageObject](../../com.aspose.email/messageobject).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла, из которого читается. |
|  | loadFormat | int | Формат исходного сообщения, в котором хранится объект сообщения. |

--------------------

Кроме того, может быть выброшен тот же набор исключений, что и при вызове File\#open(String,int).open(String,int). |

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
### getAttachments() {#getAttachments--}
```
public final MessageObjectAttachmentsCollection getAttachments()
```


Получает вложения объекта [MessageObject](../../com.aspose.email/messageobject).

Значение: Вложения.

**Returns:**
[MessageObjectAttachmentsCollection](../../com.aspose.email/messageobjectattachmentscollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodepage() {#getCodepage--}
```
public final int getCodepage()
```


Получает кодовую страницу, используемую для кодирования/декодирования строковых свойств в случае, когда используется тип [MapiType.PT\_STRING8](../../com.aspose.email/mapitype\#PT-STRING8).

Значение: Кодовая страница.

**Returns:**
int
### getIdForNamedProperty() {#getIdForNamedProperty--}
```
public final int getIdForNamedProperty()
```


Получает идентификатор, который будет использоваться для именованного свойства; именованные свойства являются специальными свойствами и их идентификаторы должны находиться в диапазоне [0x8000,0xfffe], выравниваясь последовательно, начиная с 0x8000. Используйте этот метод, чтобы найти доступный идентификатор, так как вычислить его самостоятельно может быть сложно.

**Returns:**
int — доступный идентификатор для именованного свойства.
### getProperties() {#getProperties--}
```
public final MessageObjectPropertiesCollection getProperties()
```


Получает свойства объекта [MessageObject](../../com.aspose.email/messageobject).

Значение: Свойства.

**Returns:**
[MessageObjectPropertiesCollection](../../com.aspose.email/messageobjectpropertiescollection)
### getRecipients() {#getRecipients--}
```
public final MessageObjectRecipientsCollection getRecipients()
```


Получает получателей объекта [MessageObject](../../com.aspose.email/messageobject).

Значение: Получатели.

**Returns:**
[MessageObjectRecipientsCollection](../../com.aspose.email/messageobjectrecipientscollection)
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




### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


Сохраняет текущий объект сообщения в указанный поток.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в который производится запись. |
| формат | int | Формат выходных данных. |

### save(String fileName, int format) {#save-java.lang.String-int-}
```
public final void save(String fileName, int format)
```


Сохраняет текущий объект сообщения в указанный файл.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
|  | формат | int | Формат выходных данных. |

--------------------

Кроме того, может быть выброшен тот же набор исключений, что и при вызове File\#openWrite(String).openWrite(String). |

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

