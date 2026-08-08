---
title: MapiMessageReader
second_title: Aspose.Email for Android via Java API Reference
description: Представляет читатель, который может читать документ формата Microsoft Outlook Message.
type: docs
weight: 265
url: /ru/androidjava/com.aspose.email/mapimessagereader/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public final class MapiMessageReader implements System.IDisposable, Closeable
```

Представляет читатель, который может читать документ формата Microsoft Outlook Message.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MapiMessageReader(String path)](#MapiMessageReader-java.lang.String-) | Инициализирует новый экземпляр класса MapiMessageReader для указанного имени файла. |
| [MapiMessageReader(InputStream stream)](#MapiMessageReader-java.io.InputStream-) | Инициализирует новый экземпляр класса MapiMessageReader для указанного потока. |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Освобождает неуправляемые ресурсы, используемые MapiMessageReader. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readAttachments()](#readAttachments--) | Извлекает вложение из файлов Outlook Message. |
| [readMessage()](#readMessage--) | Разбирает текущий поток и возвращает данные в виде MapiMessage. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiMessageReader(String path) {#MapiMessageReader-java.lang.String-}
```
public MapiMessageReader(String path)
```


Инициализирует новый экземпляр класса MapiMessageReader для указанного имени файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| путь | java.lang.String | Полный путь к файлу, который будет прочитан. |

### MapiMessageReader(InputStream stream) {#MapiMessageReader-java.io.InputStream-}
```
public MapiMessageReader(InputStream stream)
```


Инициализирует новый экземпляр класса MapiMessageReader для указанного потока.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, который будет прочитан. |

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает неуправляемые ресурсы, используемые MapiMessageReader.

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




### readAttachments() {#readAttachments--}
```
public final MapiAttachmentCollection readAttachments()
```


Извлекает вложение из файлов Outlook Message.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The Attachment collection.
### readMessage() {#readMessage--}
```
public final MapiMessage readMessage()
```


Разбирает текущий поток и возвращает данные в виде MapiMessage.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The MapiMessage from the input stream.
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

