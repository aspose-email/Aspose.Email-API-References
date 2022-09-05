---
title: AttachmentBase
second_title: Aspose.Email for Java API Reference
description:  Base class for mail attachment.
type: docs
weight: 65
url: /java/com.aspose.email/attachmentbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public abstract class AttachmentBase implements System.IDisposable, Closeable
```

Base class for mail attachment.
## Methods

| Method | Description |
| --- | --- |
| [getContentStream()](#getContentStream--) | Gets or sets the content stream. |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | Gets or sets the content stream. |
| [getContentId()](#getContentId--) | Gets or sets the content id. |
| [setContentId(String value)](#setContentId-java.lang.String-) | Gets or sets the content id. |
| [getHeaders()](#getHeaders--) | Gets headers collection of attachment. |
| [getContentType()](#getContentType--) | Gets or sets the type of the content. |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | Gets or sets the type of the content. |
| [getTransferEncoding()](#getTransferEncoding--) | Gets or sets the transfer encoding. |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | Gets or sets the transfer encoding. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the specified stream. |
| [save(String fileName)](#save-java.lang.String-) | Saves the specified file name. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [close()](#close--) |  |
### getContentStream() {#getContentStream--}
```
public final InputStream getContentStream()
```


Gets or sets the content stream.

Value: The content stream.

**Returns:**
java.io.InputStream
### setContentStream(InputStream value) {#setContentStream-java.io.InputStream-}
```
public final void setContentStream(InputStream value)
```


Gets or sets the content stream.

Value: The content stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

### getContentId() {#getContentId--}
```
public final String getContentId()
```


Gets or sets the content id.

Value: The content id.

**Returns:**
java.lang.String
### setContentId(String value) {#setContentId-java.lang.String-}
```
public final void setContentId(String value)
```


Gets or sets the content id.

Value: The content id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHeaders() {#getHeaders--}
```
public HeaderCollection getHeaders()
```


Gets headers collection of attachment.

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getContentType() {#getContentType--}
```
public final ContentType getContentType()
```


Gets or sets the type of the content.

Value: The type of the content.

**Returns:**
[ContentType](../../com.aspose.email/contenttype)
### setContentType(ContentType value) {#setContentType-com.aspose.email.ContentType-}
```
public final void setContentType(ContentType value)
```


Gets or sets the type of the content.

Value: The type of the content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ContentType](../../com.aspose.email/contenttype) |  |

### getTransferEncoding() {#getTransferEncoding--}
```
public final int getTransferEncoding()
```


Gets or sets the transfer encoding.

Value: The transfer encoding.

**Returns:**
int
### setTransferEncoding(int value) {#setTransferEncoding-int-}
```
public final void setTransferEncoding(int value)
```


Gets or sets the transfer encoding.

Value: The transfer encoding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Saves the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream. |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Saves the specified file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |

### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### close() {#close--}
```
public void close()
```




