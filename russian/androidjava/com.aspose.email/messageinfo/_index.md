---
title: MessageInfo
second_title: Aspose.Email for Android via Java API Reference
description: Представляет информацию о сообщении в PST.
type: docs
weight: 306
url: /ru/androidjava/com.aspose.email/messageinfo/
---

**Inheritance:**
java.lang.Object
```
public final class MessageInfo
```

Представляет информацию о сообщении в PST.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MessageInfo()](#MessageInfo--) | Initializes a new instance of the [MessageInfo](../../com.aspose.email/messageinfo) class. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisplayCC()](#getDisplayCC--) | Gets the CC: line. |
| [getDisplayTo()](#getDisplayTo--) | Gets the To: line. |
| [getEntryId()](#getEntryId--) | Gets the entry ID. |
| [getEntryIdString()](#getEntryIdString--) | Gets string representation of entry ID. |
| [getImportance()](#getImportance--) | Gets the Importance. |
| [getMessageClass()](#getMessageClass--) | Gets the Message class. |
| [getProperties()](#getProperties--) | Gets the MessageInfo properties. |
| [getSenderRepresentativeName()](#getSenderRepresentativeName--) | Gets the sender representative name. |
| [getSensitivity()](#getSensitivity--) | Gets the Sensitivity. |
| [getSubject()](#getSubject--) | Gets the message subject. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageInfo() {#MessageInfo--}
```
public MessageInfo()
```


Initializes a new instance of the [MessageInfo](../../com.aspose.email/messageinfo) class.

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
### getDisplayCC() {#getDisplayCC--}
```
public final String getDisplayCC()
```


Gets the CC: line.

Value: The display cc.

**Returns:**
java.lang.String
### getDisplayTo() {#getDisplayTo--}
```
public final String getDisplayTo()
```


Gets the To: line.

Значение: Отображение к.

**Returns:**
java.lang.String
### getEntryId() {#getEntryId--}
```
public final byte[] getEntryId()
```


Gets the entry ID.

Значение: Идентификатор записи.

**Returns:**
byte[]
### getEntryIdString() {#getEntryIdString--}
```
public final String getEntryIdString()
```


Gets string representation of entry ID.

Значение: Строка идентификатора записи.

**Returns:**
java.lang.String
### getImportance() {#getImportance--}
```
public final int getImportance()
```


Gets the Importance.

Значение: Важность.

**Returns:**
int
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Gets the Message class.

Значение: Класс сообщения.

**Returns:**
java.lang.String
### getProperties() {#getProperties--}
```
public final MapiPropertyCollection getProperties()
```


Gets the MessageInfo properties.

Значение: Свойства MessageInfo.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getSenderRepresentativeName() {#getSenderRepresentativeName--}
```
public final String getSenderRepresentativeName()
```


Gets the sender representative name.

Значение: Имя представителя отправителя.

**Returns:**
java.lang.String
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets the Sensitivity.

Значение: Чувствительность.

**Returns:**
int
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the message subject.

Значение: Тема.

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

