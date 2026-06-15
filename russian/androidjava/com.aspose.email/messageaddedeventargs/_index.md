---
title: MessageAddedEventArgs
second_title: Aspose.Email for Android via Java API Reference
description: Предоставляет данные для события
type: docs
weight: 303
url: /ru/androidjava/com.aspose.email/messageaddedeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class MessageAddedEventArgs extends System.EventArgs
```

Предоставляет данные для события [FolderInfo.MessageAddedDelegate](../../com.aspose.email/folderinfo\#MessageAddedDelegate).
## Constructors

| Constructor | Описание |
| --- | --- |
| [MessageAddedEventArgs(String entryId, MapiMessage message)](#MessageAddedEventArgs-java.lang.String-com.aspose.email.MapiMessage-) | Инициализирует новый экземпляр класса [MessageAddedEventArgs](../../com.aspose.email/messageaddedeventargs). |
## Поля

| Поле | Описание |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEntryId()](#getEntryId--) | Получает строку, представляющую EntryId добавленного сообщения. |
| [getMessage()](#getMessage--) | Получает сообщение, которое было добавлено. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageAddedEventArgs(String entryId, MapiMessage message) {#MessageAddedEventArgs-java.lang.String-com.aspose.email.MapiMessage-}
```
public MessageAddedEventArgs(String entryId, MapiMessage message)
```


Инициализирует новый экземпляр класса [MessageAddedEventArgs](../../com.aspose.email/messageaddedeventargs).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | java.lang.String | Идентификатор записи. |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Сообщение. |

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
### getEntryId() {#getEntryId--}
```
public final String getEntryId()
```


Получает строку, представляющую EntryId добавленного сообщения.

Значение: Идентификатор записи.

**Returns:**
java.lang.String
### getMessage() {#getMessage--}
```
public final MapiMessage getMessage()
```


Получает сообщение, которое было добавлено.

Значение: Сообщение.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage)
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

