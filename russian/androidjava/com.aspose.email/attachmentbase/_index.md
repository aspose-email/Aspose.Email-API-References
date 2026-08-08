---
title: AttachmentBase
second_title: Aspose.Email for Android via Java API Reference
description: Базовый класс для вложения письма.
type: docs
weight: 53
url: /ru/androidjava/com.aspose.email/attachmentbase/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public abstract class AttachmentBase implements System.IDisposable, Closeable
```

Базовый класс для вложения письма.
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentId()](#getContentId--) | Получает или задаёт идентификатор содержимого. |
| [getContentStream()](#getContentStream--) | Получает или задаёт поток содержимого. |
| [getContentType()](#getContentType--) | Получает или задаёт тип содержимого. |
| [getHeaders()](#getHeaders--) | Получает коллекцию заголовков вложения. |
| [getTransferEncoding()](#getTransferEncoding--) | Получает или задаёт кодировку передачи. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет указанный поток. |
| [save(String fileName)](#save-java.lang.String-) | Сохраняет указанное имя файла. |
| [setContentId(String value)](#setContentId-java.lang.String-) | Получает или задаёт идентификатор содержимого. |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | Получает или задаёт поток содержимого. |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | Получает или задаёт тип содержимого. |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | Получает или задаёт кодировку передачи. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов.

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
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Получает или задаёт идентификатор содержимого.

Значение: Идентификатор содержимого.

**Returns:**
java.lang.String
### getContentStream() {#getContentStream--}
```
public final InputStream getContentStream()
```


Получает или задаёт поток содержимого.

Значение: Поток содержимого.

**Returns:**
java.io.InputStream
### getContentType() {#getContentType--}
```
public final ContentType getContentType()
```


Получает или задаёт тип содержимого.

Значение: Тип содержимого.

**Returns:**
[ContentType](../../com.aspose.email/contenttype)
### getHeaders() {#getHeaders--}
```
public HeaderCollection getHeaders()
```


Получает коллекцию заголовков вложения.

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getTransferEncoding() {#getTransferEncoding--}
```
public final int getTransferEncoding()
```


Получает или задаёт кодировку передачи.

Значение: Кодировка передачи.

**Returns:**
int
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




### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Сохраняет указанный поток.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток. |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Сохраняет указанное имя файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |

### setContentId(String value) {#setContentId-java.lang.String-}
```
public final void setContentId(String value)
```


Получает или задаёт идентификатор содержимого.

Значение: Идентификатор содержимого.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setContentStream(InputStream value) {#setContentStream-java.io.InputStream-}
```
public final void setContentStream(InputStream value)
```


Получает или задаёт поток содержимого.

Значение: Поток содержимого.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.io.InputStream |  |

### setContentType(ContentType value) {#setContentType-com.aspose.email.ContentType-}
```
public final void setContentType(ContentType value)
```


Получает или задаёт тип содержимого.

Значение: Тип содержимого.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [ContentType](../../com.aspose.email/contenttype) |  |

### setTransferEncoding(int value) {#setTransferEncoding-int-}
```
public final void setTransferEncoding(int value)
```


Получает или задаёт кодировку передачи.

Значение: Кодировка передачи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

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

