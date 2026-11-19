---
title: AttachmentBase
second_title: Aspose.Email for Java API Reference
description: The base class of attachments alternate views and linked resources a MIME part with its content and headers.
type: docs
weight: 67
url: /java/com.aspose.email/attachmentbase/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public abstract class AttachmentBase implements System.IDisposable, Closeable
```

The base class of attachments, alternate views and linked resources: a MIME part with its content and headers.
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Releases the resources used by the part, including its content stream. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentId()](#getContentId--) | Gets the content ID of the part, by which HTML refers to it with a  cid:  URL. |
| [getContentStream()](#getContentStream--) | Gets the stream that holds the content. |
| [getContentType()](#getContentType--) | Gets the content type of the part: its media type, name and character set. |
| [getHeaders()](#getHeaders--) | Gets the MIME headers of the part. |
| [getTransferEncoding()](#getTransferEncoding--) | Gets how the content is encoded for transfer, such as Base64 or quoted-printable. |
| [getUniqueId()](#getUniqueId--) | Gets an identifier of the part that stays the same while the application runs. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the decoded content of the part to a stream. |
| [save(String fileName)](#save-java.lang.String-) | Saves the decoded content of the part to a file. |
| [setContentId(String value)](#setContentId-java.lang.String-) | Sets the content ID of the part, by which HTML refers to it with a  cid:  URL. |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | Sets the stream that holds the content. |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | Sets the content type of the part: its media type, name and character set. |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | Sets how the content is encoded for transfer, such as Base64 or quoted-printable. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### close() {#close--}
```
public void close()
```


Releases the resources used by the part, including its content stream.

### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Gets the content ID of the part, by which HTML refers to it with a  cid:  URL.

**Returns:**
java.lang.String - The content ID.
### getContentStream() {#getContentStream--}
```
public final InputStream getContentStream()
```


Gets the stream that holds the content.

**Returns:**
java.io.InputStream - The content stream.
### getContentType() {#getContentType--}
```
public final ContentType getContentType()
```


Gets the content type of the part: its media type, name and character set.

**Returns:**
[ContentType](../../com.aspose.email/contenttype) - The content type.
### getHeaders() {#getHeaders--}
```
public HeaderCollection getHeaders()
```


Gets the MIME headers of the part.

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getTransferEncoding() {#getTransferEncoding--}
```
public final int getTransferEncoding()
```


Gets how the content is encoded for transfer, such as Base64 or quoted-printable.

**Returns:**
int - The transfer encoding.
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


Gets an identifier of the part that stays the same while the application runs.

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




### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Saves the decoded content of the part to a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Saves the decoded content of the part to a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to write. |

### setContentId(String value) {#setContentId-java.lang.String-}
```
public final void setContentId(String value)
```


Sets the content ID of the part, by which HTML refers to it with a  cid:  URL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The content ID. |

### setContentStream(InputStream value) {#setContentStream-java.io.InputStream-}
```
public final void setContentStream(InputStream value)
```


Sets the stream that holds the content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream | The content stream. |

### setContentType(ContentType value) {#setContentType-com.aspose.email.ContentType-}
```
public final void setContentType(ContentType value)
```


Sets the content type of the part: its media type, name and character set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ContentType](../../com.aspose.email/contenttype) | The content type. |

### setTransferEncoding(int value) {#setTransferEncoding-int-}
```
public final void setTransferEncoding(int value)
```


Sets how the content is encoded for transfer, such as Base64 or quoted-printable.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The transfer encoding. |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

