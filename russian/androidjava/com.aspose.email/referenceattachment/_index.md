---
title: ReferenceAttachment
second_title: Aspose.Email for Android via Java API Reference
description: Этот класс представляет ссылочное вложение
type: docs
weight: 364
url: /ru/androidjava/com.aspose.email/referenceattachment/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AttachmentBase](../../com.aspose.email/attachmentbase), [com.aspose.email.Attachment](../../com.aspose.email/attachment)
```
public class ReferenceAttachment extends Attachment
```

Этот класс представляет ссылочное вложение
## Constructors

| Constructor | Описание |
| --- | --- |
| [ReferenceAttachment()](#ReferenceAttachment--) | Инициализирует новый экземпляр [ReferenceAttachment](../../com.aspose.email/referenceattachment). |
| [ReferenceAttachment(URI uri)](#ReferenceAttachment-java.net.URI-) | Инициализирует новый экземпляр [ReferenceAttachment](../../com.aspose.email/referenceattachment). |
| [ReferenceAttachment(String uri)](#ReferenceAttachment-java.lang.String-) | Инициализирует новый экземпляр [ReferenceAttachment](../../com.aspose.email/referenceattachment). |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [createAttachmentFromString(String content, ContentType contentType)](#createAttachmentFromString-java.lang.String-com.aspose.email.ContentType-) | Создает вложение из строки. |
| [createAttachmentFromString(String content, String name)](#createAttachmentFromString-java.lang.String-java.lang.String-) | Создает вложение из строки. |
| [createAttachmentFromString(String content, String name, Charset contentEncoding, String mediaType)](#createAttachmentFromString-java.lang.String-java.lang.String-java.nio.charset.Charset-java.lang.String-) | Создает вложение из строки. |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | Получает заголовок Content-Disposition |
| [getContentId()](#getContentId--) | Получает или задаёт идентификатор содержимого. |
| [getContentStream()](#getContentStream--) | Получает или задаёт поток содержимого. |
| [getContentType()](#getContentType--) | Получает или задаёт тип содержимого. |
| [getHeaders()](#getHeaders--) | Получает коллекцию заголовков вложения. |
| [getName()](#getName--) | Получает или задает имя вложения |
| [getNameEncoding()](#getNameEncoding--) | Получает или задает кодировку имени вложения |
| [getPermissionType()](#getPermissionType--) | Указывает тип разрешения. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Получает или задает предпочтительную текстовую кодировку |
| [getProviderType()](#getProviderType--) | Указывает тип поставщика. |
| [getTransferEncoding()](#getTransferEncoding--) | Получает или задаёт кодировку передачи. |
| [getUri()](#getUri--) | Указывает Url поставщика конечной точки. |
| [hashCode()](#hashCode--) |  |
| [isEmbeddedMessage()](#isEmbeddedMessage--) | Возвращает значение, указывающее, является ли вложение встроенным сообщением. |
| [isUri()](#isUri--) | Возвращает значение, указывающее, является ли вложение URI‑вложением. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет указанный поток. |
| [save(String fileName)](#save-java.lang.String-) | Сохраняет указанное имя файла. |
| [setContentId(String value)](#setContentId-java.lang.String-) | Получает или задаёт идентификатор содержимого. |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | Получает или задаёт поток содержимого. |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | Получает или задаёт тип содержимого. |
| [setName(String value)](#setName-java.lang.String-) | Получает или задает имя вложения |
| [setNameEncoding(Charset value)](#setNameEncoding-java.nio.charset.Charset-) | Получает или задает кодировку имени вложения |
| [setPermissionType(int value)](#setPermissionType-int-) | Указывает тип разрешения. |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Получает или задает предпочтительную текстовую кодировку |
| [setProviderType(int value)](#setProviderType-int-) | Указывает тип поставщика. |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | Получает или задаёт кодировку передачи. |
| [setUri(URI value)](#setUri-java.net.URI-) | Указывает Url поставщика конечной точки. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ReferenceAttachment() {#ReferenceAttachment--}
```
public ReferenceAttachment()
```


Инициализирует новый экземпляр [ReferenceAttachment](../../com.aspose.email/referenceattachment).

### ReferenceAttachment(URI uri) {#ReferenceAttachment-java.net.URI-}
```
public ReferenceAttachment(URI uri)
```


Инициализирует новый экземпляр [ReferenceAttachment](../../com.aspose.email/referenceattachment).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| uri | java.net.URI | URL |

### ReferenceAttachment(String uri) {#ReferenceAttachment-java.lang.String-}
```
public ReferenceAttachment(String uri)
```


Инициализирует новый экземпляр [ReferenceAttachment](../../com.aspose.email/referenceattachment).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| uri | java.lang.String | string Url |

### close() {#close--}
```
public void close()
```




### createAttachmentFromString(String content, ContentType contentType) {#createAttachmentFromString-java.lang.String-com.aspose.email.ContentType-}
```
public static Attachment createAttachmentFromString(String content, ContentType contentType)
```


Создает вложение из строки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Строка, представляющая содержимое вложения. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | Тип содержимого ([AttachmentBase.getContentType](../../com.aspose.email/attachmentbase\#getContentType)/[AttachmentBase.setContentType(ContentType)](../../com.aspose.email/attachmentbase\#setContentType-ContentType-)). |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - Returns created attachment
### createAttachmentFromString(String content, String name) {#createAttachmentFromString-java.lang.String-java.lang.String-}
```
public static Attachment createAttachmentFromString(String content, String name)
```


Создает вложение из строки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Строка, представляющая содержимое вложения. |
| name | java.lang.String | Имя вложения. |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - Returns created attachment
### createAttachmentFromString(String content, String name, Charset contentEncoding, String mediaType) {#createAttachmentFromString-java.lang.String-java.lang.String-java.nio.charset.Charset-java.lang.String-}
```
public static Attachment createAttachmentFromString(String content, String name, Charset contentEncoding, String mediaType)
```


Создает вложение из строки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Строка, представляющая содержимое вложения. |
| name | java.lang.String | Имя вложения. |
| contentEncoding | java.nio.charset.Charset | Кодировка содержимого. |
| mediaType | java.lang.String | Имя медиа‑типа |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - Returns created attachment
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
### getName() {#getName--}
```
public final String getName()
```


Получает или задает имя вложения

**Returns:**
java.lang.String
### getNameEncoding() {#getNameEncoding--}
```
public final Charset getNameEncoding()
```


Получает или задает кодировку имени вложения

**Returns:**
java.nio.charset.Charset
### getPermissionType() {#getPermissionType--}
```
public final int getPermissionType()
```


Указывает тип разрешения.

**Returns:**
int
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


Получает или задает предпочтительную текстовую кодировку

**Returns:**
java.nio.charset.Charset
### getProviderType() {#getProviderType--}
```
public final int getProviderType()
```


Указывает тип поставщика.

**Returns:**
int
### getTransferEncoding() {#getTransferEncoding--}
```
public final int getTransferEncoding()
```


Получает или задаёт кодировку передачи.

Значение: Кодировка передачи.

**Returns:**
int
### getUri() {#getUri--}
```
public final URI getUri()
```


Указывает Url поставщика конечной точки.

**Returns:**
java.net.URI
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEmbeddedMessage() {#isEmbeddedMessage--}
```
public final boolean isEmbeddedMessage()
```


Возвращает значение, указывающее, является ли вложение встроенным сообщением.

**Returns:**
boolean
### isUri() {#isUri--}
```
public final boolean isUri()
```


Возвращает значение, указывающее, является ли вложение URI‑вложением.

**Returns:**
boolean
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

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Получает или задает имя вложения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameEncoding(Charset value) {#setNameEncoding-java.nio.charset.Charset-}
```
public final void setNameEncoding(Charset value)
```


Получает или задает кодировку имени вложения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPermissionType(int value) {#setPermissionType-int-}
```
public final void setPermissionType(int value)
```


Указывает тип разрешения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


Получает или задает предпочтительную текстовую кодировку

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setProviderType(int value) {#setProviderType-int-}
```
public final void setProviderType(int value)
```


Указывает тип поставщика.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

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

### setUri(URI value) {#setUri-java.net.URI-}
```
public final void setUri(URI value)
```


Указывает Url поставщика конечной точки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.net.URI |  |

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

