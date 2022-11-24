---
title: LinkedResource
second_title: Aspose.Email for Java API Reference
description: Represents an embedded resource in a message.
type: docs
weight: 348
url: /java/com.aspose.email/linkedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AttachmentBase](../../com.aspose.email/attachmentbase)
```
public class LinkedResource extends AttachmentBase
```

Represents an embedded resource in a message.
## Constructors

| Constructor | Description |
| --- | --- |
| [LinkedResource(String fileName)](#LinkedResource-java.lang.String-) | Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class. |
| [LinkedResource(String fileName, String mediaType)](#LinkedResource-java.lang.String-java.lang.String-) | Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class. |
| [LinkedResource(String fileName, ContentType contentType)](#LinkedResource-java.lang.String-com.aspose.email.ContentType-) | Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class. |
| [LinkedResource(InputStream contentStream)](#LinkedResource-java.io.InputStream-) | Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class. |
| [LinkedResource(InputStream contentStream, String mediaType)](#LinkedResource-java.io.InputStream-java.lang.String-) | Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class. |
| [LinkedResource(InputStream contentStream, ContentType contentType)](#LinkedResource-java.io.InputStream-com.aspose.email.ContentType-) | Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [createLinkedResourceFromString(String content)](#createLinkedResourceFromString-java.lang.String-) | Creates the linked resource from string. |
| [createLinkedResourceFromString(String content, ContentType contentType)](#createLinkedResourceFromString-java.lang.String-com.aspose.email.ContentType-) | Creates the linked resource from string. |
| [createLinkedResourceFromString(String content, Charset contentEncoding, String mediaType)](#createLinkedResourceFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-) | Creates the linked resource from string. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | Gets Content-Disposition header |
| [getContentId()](#getContentId--) | Gets or sets the content id. |
| [getContentLink()](#getContentLink--) | Gets or sets a URI that the resource must match. |
| [getContentStream()](#getContentStream--) | Gets or sets the content stream. |
| [getContentType()](#getContentType--) | Gets or sets the type of the content. |
| [getHeaders()](#getHeaders--) | Gets headers collection of attachment. |
| [getTransferEncoding()](#getTransferEncoding--) | Gets or sets the transfer encoding. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the specified stream. |
| [save(String fileName)](#save-java.lang.String-) | Saves the specified file name. |
| [setContentId(String value)](#setContentId-java.lang.String-) | Gets or sets the content id. |
| [setContentLink(URI value)](#setContentLink-java.net.URI-) | Gets or sets a URI that the resource must match. |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | Gets or sets the content stream. |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | Gets or sets the type of the content. |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | Gets or sets the transfer encoding. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinkedResource(String fileName) {#LinkedResource-java.lang.String-}
```
public LinkedResource(String fileName)
```


Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name that holds the content for this resource. |

### LinkedResource(String fileName, String mediaType) {#LinkedResource-java.lang.String-java.lang.String-}
```
public LinkedResource(String fileName, String mediaType)
```


Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name that holds the content for this resource. |
| mediaType | java.lang.String | Internet media type. |

### LinkedResource(String fileName, ContentType contentType) {#LinkedResource-java.lang.String-com.aspose.email.ContentType-}
```
public LinkedResource(String fileName, ContentType contentType)
```


Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name that holds the content for this resource. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | The type of content. |

### LinkedResource(InputStream contentStream) {#LinkedResource-java.io.InputStream-}
```
public LinkedResource(InputStream contentStream)
```


Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | A stream that contains the content for this resource. |

### LinkedResource(InputStream contentStream, String mediaType) {#LinkedResource-java.io.InputStream-java.lang.String-}
```
public LinkedResource(InputStream contentStream, String mediaType)
```


Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | A stream that contains the content for this resource. |
| mediaType | java.lang.String | Internet media type. |

### LinkedResource(InputStream contentStream, ContentType contentType) {#LinkedResource-java.io.InputStream-com.aspose.email.ContentType-}
```
public LinkedResource(InputStream contentStream, ContentType contentType)
```


Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | A stream that contains the content for this resource. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | The type of content. |

### close() {#close--}
```
public void close()
```




### createLinkedResourceFromString(String content) {#createLinkedResourceFromString-java.lang.String-}
```
public static LinkedResource createLinkedResourceFromString(String content)
```


Creates the linked resource from string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | A string that contains the resource to be included in the email attachment. |

**Returns:**
[LinkedResource](../../com.aspose.email/linkedresource) - A LinkedResource object that contains the embedded resource.
### createLinkedResourceFromString(String content, ContentType contentType) {#createLinkedResourceFromString-java.lang.String-com.aspose.email.ContentType-}
```
public static LinkedResource createLinkedResourceFromString(String content, ContentType contentType)
```


Creates the linked resource from string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | A string that contains the resource to be included in the email attachment. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | The type of the content. |

**Returns:**
[LinkedResource](../../com.aspose.email/linkedresource) - A LinkedResource object that contains the embedded resource.
### createLinkedResourceFromString(String content, Charset contentEncoding, String mediaType) {#createLinkedResourceFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-}
```
public static LinkedResource createLinkedResourceFromString(String content, Charset contentEncoding, String mediaType)
```


Creates the linked resource from string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | A string that contains the resource to be included in the email attachment. |
| contentEncoding | java.nio.charset.Charset | The content encoding. |
| mediaType | java.lang.String | The MIME media type of the content. |

**Returns:**
[LinkedResource](../../com.aspose.email/linkedresource) - A LinkedResource object that contains the embedded resource.
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
### getContentDisposition() {#getContentDisposition--}
```
public final ContentDisposition getContentDisposition()
```


Gets Content-Disposition header

**Returns:**
[ContentDisposition](../../com.aspose.email/contentdisposition)
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Gets or sets the content id.

Value: The content id.

**Returns:**
java.lang.String
### getContentLink() {#getContentLink--}
```
public final URI getContentLink()
```


Gets or sets a URI that the resource must match.

**Returns:**
java.net.URI
### getContentStream() {#getContentStream--}
```
public final InputStream getContentStream()
```


Gets or sets the content stream.

Value: The content stream.

**Returns:**
java.io.InputStream
### getContentType() {#getContentType--}
```
public final ContentType getContentType()
```


Gets or sets the type of the content.

Value: The type of the content.

**Returns:**
[ContentType](../../com.aspose.email/contenttype)
### getHeaders() {#getHeaders--}
```
public HeaderCollection getHeaders()
```


Gets headers collection of attachment.

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getTransferEncoding() {#getTransferEncoding--}
```
public final int getTransferEncoding()
```


Gets or sets the transfer encoding.

Value: The transfer encoding.

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

### setContentLink(URI value) {#setContentLink-java.net.URI-}
```
public final void setContentLink(URI value)
```


Gets or sets a URI that the resource must match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.net.URI |  |

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

