---
title: LinkedResource
second_title: Aspose.Email for Android via Java API Reference
description: Представляет встроенный ресурс в сообщении.
type: docs
weight: 177
url: /ru/androidjava/com.aspose.email/linkedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AttachmentBase](../../com.aspose.email/attachmentbase)
```
public class LinkedResource extends AttachmentBase
```

Представляет встроенный ресурс в сообщении.
## Constructors

| Constructor | Описание |
| --- | --- |
| [LinkedResource(String fileName)](#LinkedResource-java.lang.String-) | Инициализирует новый экземпляр класса [LinkedResource](../../com.aspose.email/linkedresource). |
| [LinkedResource(String fileName, String mediaType)](#LinkedResource-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [LinkedResource](../../com.aspose.email/linkedresource). |
| [LinkedResource(String fileName, ContentType contentType)](#LinkedResource-java.lang.String-com.aspose.email.ContentType-) | Инициализирует новый экземпляр класса [LinkedResource](../../com.aspose.email/linkedresource). |
| [LinkedResource(InputStream contentStream)](#LinkedResource-java.io.InputStream-) | Инициализирует новый экземпляр класса [LinkedResource](../../com.aspose.email/linkedresource). |
| [LinkedResource(InputStream contentStream, String mediaType)](#LinkedResource-java.io.InputStream-java.lang.String-) | Инициализирует новый экземпляр класса [LinkedResource](../../com.aspose.email/linkedresource). |
| [LinkedResource(InputStream contentStream, ContentType contentType)](#LinkedResource-java.io.InputStream-com.aspose.email.ContentType-) | Инициализирует новый экземпляр класса [LinkedResource](../../com.aspose.email/linkedresource). |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [createLinkedResourceFromString(String content)](#createLinkedResourceFromString-java.lang.String-) | Создаёт связанный ресурс из строки. |
| [createLinkedResourceFromString(String content, ContentType contentType)](#createLinkedResourceFromString-java.lang.String-com.aspose.email.ContentType-) | Создаёт связанный ресурс из строки. |
| [createLinkedResourceFromString(String content, Charset contentEncoding, String mediaType)](#createLinkedResourceFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-) | Создаёт связанный ресурс из строки. |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | Получает заголовок Content-Disposition |
| [getContentId()](#getContentId--) | Получает или задаёт идентификатор содержимого. |
| [getContentLink()](#getContentLink--) | Получает или задаёт URI, которому должен соответствовать ресурс. |
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
| [setContentLink(URI value)](#setContentLink-java.net.URI-) | Получает или задаёт URI, которому должен соответствовать ресурс. |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | Получает или задаёт поток содержимого. |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | Получает или задаёт тип содержимого. |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | Получает или задаёт кодировку передачи. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinkedResource(String fileName) {#LinkedResource-java.lang.String-}
```
public LinkedResource(String fileName)
```


Инициализирует новый экземпляр класса [LinkedResource](../../com.aspose.email/linkedresource).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла, содержащего содержимое этого ресурса. |

### LinkedResource(String fileName, String mediaType) {#LinkedResource-java.lang.String-java.lang.String-}
```
public LinkedResource(String fileName, String mediaType)
```


Инициализирует новый экземпляр класса [LinkedResource](../../com.aspose.email/linkedresource).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла, содержащего содержимое этого ресурса. |
| mediaType | java.lang.String | Тип медиа в интернете. |

### LinkedResource(String fileName, ContentType contentType) {#LinkedResource-java.lang.String-com.aspose.email.ContentType-}
```
public LinkedResource(String fileName, ContentType contentType)
```


Инициализирует новый экземпляр класса [LinkedResource](../../com.aspose.email/linkedresource).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла, содержащего содержимое этого ресурса. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | Тип содержимого. |

### LinkedResource(InputStream contentStream) {#LinkedResource-java.io.InputStream-}
```
public LinkedResource(InputStream contentStream)
```


Инициализирует новый экземпляр класса [LinkedResource](../../com.aspose.email/linkedresource).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| contentStream | java.io.InputStream | Поток, содержащий содержимое этого ресурса. |

### LinkedResource(InputStream contentStream, String mediaType) {#LinkedResource-java.io.InputStream-java.lang.String-}
```
public LinkedResource(InputStream contentStream, String mediaType)
```


Инициализирует новый экземпляр класса [LinkedResource](../../com.aspose.email/linkedresource).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| contentStream | java.io.InputStream | Поток, содержащий содержимое этого ресурса. |
| mediaType | java.lang.String | Тип медиа в интернете. |

### LinkedResource(InputStream contentStream, ContentType contentType) {#LinkedResource-java.io.InputStream-com.aspose.email.ContentType-}
```
public LinkedResource(InputStream contentStream, ContentType contentType)
```


Инициализирует новый экземпляр класса [LinkedResource](../../com.aspose.email/linkedresource).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| contentStream | java.io.InputStream | Поток, содержащий содержимое этого ресурса. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | Тип содержимого. |

### close() {#close--}
```
public void close()
```




### createLinkedResourceFromString(String content) {#createLinkedResourceFromString-java.lang.String-}
```
public static LinkedResource createLinkedResourceFromString(String content)
```


Создаёт связанный ресурс из строки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Строка, содержащая ресурс, который будет включён в вложение электронной почты. |

**Returns:**
[LinkedResource](../../com.aspose.email/linkedresource) - A LinkedResource object that contains the embedded resource.
### createLinkedResourceFromString(String content, ContentType contentType) {#createLinkedResourceFromString-java.lang.String-com.aspose.email.ContentType-}
```
public static LinkedResource createLinkedResourceFromString(String content, ContentType contentType)
```


Создаёт связанный ресурс из строки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Строка, содержащая ресурс, который будет включён в вложение электронной почты. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | Тип содержимого. |

**Returns:**
[LinkedResource](../../com.aspose.email/linkedresource) - A LinkedResource object that contains the embedded resource.
### createLinkedResourceFromString(String content, Charset contentEncoding, String mediaType) {#createLinkedResourceFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-}
```
public static LinkedResource createLinkedResourceFromString(String content, Charset contentEncoding, String mediaType)
```


Создаёт связанный ресурс из строки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Строка, содержащая ресурс, который будет включён в вложение электронной почты. |
| contentEncoding | java.nio.charset.Charset | Кодировка содержимого. |
| mediaType | java.lang.String | MIME-тип медиа содержимого. |

**Returns:**
[LinkedResource](../../com.aspose.email/linkedresource) - A LinkedResource object that contains the embedded resource.
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
### getContentDisposition() {#getContentDisposition--}
```
public final ContentDisposition getContentDisposition()
```


Получает заголовок Content-Disposition

**Returns:**
[ContentDisposition](../../com.aspose.email/contentdisposition)
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Получает или задаёт идентификатор содержимого.

Значение: Идентификатор содержимого.

**Returns:**
java.lang.String
### getContentLink() {#getContentLink--}
```
public final URI getContentLink()
```


Получает или задаёт URI, которому должен соответствовать ресурс.

**Returns:**
java.net.URI
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

### setContentLink(URI value) {#setContentLink-java.net.URI-}
```
public final void setContentLink(URI value)
```


Получает или задаёт URI, которому должен соответствовать ресурс.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.net.URI |  |

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

