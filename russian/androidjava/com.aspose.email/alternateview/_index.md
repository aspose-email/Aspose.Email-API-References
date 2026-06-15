---
title: AlternateView
second_title: Aspose.Email for Android via Java API Reference
description: Представляет формат отображения сообщения.
type: docs
weight: 11
url: /ru/androidjava/com.aspose.email/alternateview/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AttachmentBase](../../com.aspose.email/attachmentbase)
```
public class AlternateView extends AttachmentBase
```

Представляет формат отображения сообщения.
## Constructors

| Constructor | Описание |
| --- | --- |
| [AlternateView(String fileName)](#AlternateView-java.lang.String-) | Инициализирует новый экземпляр класса [AlternateView](../../com.aspose.email/alternateview). |
| [AlternateView(String fileName, String mediaType)](#AlternateView-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [AlternateView](../../com.aspose.email/alternateview). |
| [AlternateView(String fileName, ContentType contentType)](#AlternateView-java.lang.String-com.aspose.email.ContentType-) | Инициализирует новый экземпляр класса [AlternateView](../../com.aspose.email/alternateview). |
| [AlternateView(InputStream contentStream)](#AlternateView-java.io.InputStream-) | Инициализирует новый экземпляр класса [AlternateView](../../com.aspose.email/alternateview). |
| [AlternateView(InputStream contentStream, String mediaType)](#AlternateView-java.io.InputStream-java.lang.String-) | Инициализирует новый экземпляр класса [AlternateView](../../com.aspose.email/alternateview). |
| [AlternateView(InputStream contentStream, ContentType contentType)](#AlternateView-java.io.InputStream-com.aspose.email.ContentType-) | Инициализирует новый экземпляр класса [AlternateView](../../com.aspose.email/alternateview). |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [createAlternateViewFromString(String content)](#createAlternateViewFromString-java.lang.String-) | Создаёт AlternateView, используя содержимое, указанное в строке. |
| [createAlternateViewFromString(String content, ContentType contentType)](#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-) | Создаёт AlternateView, используя содержимое, указанное в строке. |
| [createAlternateViewFromString(String content, ContentType contentType, int transferencoding)](#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-int-) | Создаёт AlternateView, используя содержимое, указанное в строке. |
| [createAlternateViewFromString(String content, Charset contentEncoding, String mediaType)](#createAlternateViewFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-) | Создаёт AlternateView, используя содержимое, указанное в строке. |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseUri()](#getBaseUri--) | Получает или задаёт базовый URI. |
| [getClass()](#getClass--) |  |
| [getContentId()](#getContentId--) | Получает или задаёт идентификатор содержимого. |
| [getContentStream()](#getContentStream--) | Получает или задаёт поток содержимого. |
| [getContentType()](#getContentType--) | Получает или задаёт тип содержимого. |
| [getHeaders()](#getHeaders--) | Получает коллекцию заголовков вложения. |
| [getLinkedResources()](#getLinkedResources--) | Получает набор встроенных ресурсов, на которые ссылается это альтернативное представление. |
| [getTransferEncoding()](#getTransferEncoding--) | Получает или задаёт кодировку передачи. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет указанный поток. |
| [save(String fileName)](#save-java.lang.String-) | Сохраняет указанное имя файла. |
| [setBaseUri(URI value)](#setBaseUri-java.net.URI-) | Получает или задаёт базовый URI. |
| [setContentId(String value)](#setContentId-java.lang.String-) | Получает или задаёт идентификатор содержимого. |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | Получает или задаёт поток содержимого. |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | Получает или задаёт тип содержимого. |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | Получает или задаёт кодировку передачи. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AlternateView(String fileName) {#AlternateView-java.lang.String-}
```
public AlternateView(String fileName)
```


Инициализирует новый экземпляр класса [AlternateView](../../com.aspose.email/alternateview).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |

### AlternateView(String fileName, String mediaType) {#AlternateView-java.lang.String-java.lang.String-}
```
public AlternateView(String fileName, String mediaType)
```


Инициализирует новый экземпляр класса [AlternateView](../../com.aspose.email/alternateview).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| mediaType | java.lang.String | Тип медиа в интернете. |

### AlternateView(String fileName, ContentType contentType) {#AlternateView-java.lang.String-com.aspose.email.ContentType-}
```
public AlternateView(String fileName, ContentType contentType)
```


Инициализирует новый экземпляр класса [AlternateView](../../com.aspose.email/alternateview).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | Тип содержимого. |

### AlternateView(InputStream contentStream) {#AlternateView-java.io.InputStream-}
```
public AlternateView(InputStream contentStream)
```


Инициализирует новый экземпляр класса [AlternateView](../../com.aspose.email/alternateview).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| contentStream | java.io.InputStream | Поток содержимого. |

### AlternateView(InputStream contentStream, String mediaType) {#AlternateView-java.io.InputStream-java.lang.String-}
```
public AlternateView(InputStream contentStream, String mediaType)
```


Инициализирует новый экземпляр класса [AlternateView](../../com.aspose.email/alternateview).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| contentStream | java.io.InputStream | Поток содержимого. |
| mediaType | java.lang.String | Тип медиа в интернете. |

### AlternateView(InputStream contentStream, ContentType contentType) {#AlternateView-java.io.InputStream-com.aspose.email.ContentType-}
```
public AlternateView(InputStream contentStream, ContentType contentType)
```


Инициализирует новый экземпляр класса [AlternateView](../../com.aspose.email/alternateview).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| contentStream | java.io.InputStream | Поток содержимого. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | Тип содержимого. |

### close() {#close--}
```
public void close()
```




### createAlternateViewFromString(String content) {#createAlternateViewFromString-java.lang.String-}
```
public static AlternateView createAlternateViewFromString(String content)
```


Создаёт AlternateView, используя содержимое, указанное в строке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Строка, содержащая содержимое. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An AlternateView object that represents an alternate view.
### createAlternateViewFromString(String content, ContentType contentType) {#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-}
```
public static AlternateView createAlternateViewFromString(String content, ContentType contentType)
```


Создаёт AlternateView, используя содержимое, указанное в строке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Строка, содержащая содержимое. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | Тип содержимого. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An AlternateView object that represents an alternate view.
### createAlternateViewFromString(String content, ContentType contentType, int transferencoding) {#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-int-}
```
public static AlternateView createAlternateViewFromString(String content, ContentType contentType, int transferencoding)
```


Создаёт AlternateView, используя содержимое, указанное в строке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Строка, содержащая содержимое. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | Тип содержимого. |
| transferencoding | int | Кодировка передачи. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An AlternateView object that represents an alternate view.
### createAlternateViewFromString(String content, Charset contentEncoding, String mediaType) {#createAlternateViewFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-}
```
public static AlternateView createAlternateViewFromString(String content, Charset contentEncoding, String mediaType)
```


Создаёт AlternateView, используя содержимое, указанное в строке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Строка, содержащая содержимое. |
| contentEncoding | java.nio.charset.Charset | Кодировка содержимого. |
| mediaType | java.lang.String | Тип медиа в интернете. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An AlternateView object that represents an alternate view.
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
### getBaseUri() {#getBaseUri--}
```
public final URI getBaseUri()
```


Получает или задаёт базовый URI.

Значение: Базовый URI.

**Returns:**
java.net.URI
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
### getLinkedResources() {#getLinkedResources--}
```
public final LinkedResourceCollection getLinkedResources()
```


Получает набор встроенных ресурсов, на которые ссылается это альтернативное представление.

Значение: Связанные ресурсы.

**Returns:**
[LinkedResourceCollection](../../com.aspose.email/linkedresourcecollection)
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

### setBaseUri(URI value) {#setBaseUri-java.net.URI-}
```
public final void setBaseUri(URI value)
```


Получает или задаёт базовый URI.

Значение: Базовый URI.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.net.URI |  |

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

