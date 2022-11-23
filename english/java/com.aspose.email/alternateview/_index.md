---
title: AlternateView
second_title: Aspose.Email for Java API Reference
description: Represents the format to view a message.
type: docs
weight: 15
url: /java/com.aspose.email/alternateview/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AttachmentBase](../../com.aspose.email/attachmentbase)
```
public class AlternateView extends AttachmentBase
```

Represents the format to view a message.
## Constructors

| Constructor | Description |
| --- | --- |
| [AlternateView(String fileName)](#AlternateView-java.lang.String-) | Initializes a new instance of the [AlternateView](../../com.aspose.email/alternateview) class. |
| [AlternateView(String fileName, String mediaType)](#AlternateView-java.lang.String-java.lang.String-) | Initializes a new instance of the [AlternateView](../../com.aspose.email/alternateview) class. |
| [AlternateView(String fileName, ContentType contentType)](#AlternateView-java.lang.String-com.aspose.email.ContentType-) | Initializes a new instance of the [AlternateView](../../com.aspose.email/alternateview) class. |
| [AlternateView(InputStream contentStream)](#AlternateView-java.io.InputStream-) | Initializes a new instance of the [AlternateView](../../com.aspose.email/alternateview) class. |
| [AlternateView(InputStream contentStream, String mediaType)](#AlternateView-java.io.InputStream-java.lang.String-) | Initializes a new instance of the [AlternateView](../../com.aspose.email/alternateview) class. |
| [AlternateView(InputStream contentStream, ContentType contentType)](#AlternateView-java.io.InputStream-com.aspose.email.ContentType-) | Initializes a new instance of the [AlternateView](../../com.aspose.email/alternateview) class. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [createAlternateViewFromString(String content)](#createAlternateViewFromString-java.lang.String-) | Creates a AlternateView of using the content specified in a string. |
| [createAlternateViewFromString(String content, ContentType contentType)](#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-) | Creates a AlternateView of using the content specified in a string. |
| [createAlternateViewFromString(String content, ContentType contentType, int transferencoding)](#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-int-) | Creates a AlternateView of using the content specified in a string. |
| [createAlternateViewFromString(String content, Charset contentEncoding, String mediaType)](#createAlternateViewFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-) | Creates a AlternateView of using the content specified in a string. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseUri()](#getBaseUri--) | Gets or sets the base URI. |
| [getClass()](#getClass--) |  |
| [getContentId()](#getContentId--) | Gets or sets the content id. |
| [getContentStream()](#getContentStream--) | Gets or sets the content stream. |
| [getContentType()](#getContentType--) | Gets or sets the type of the content. |
| [getHeaders()](#getHeaders--) | Gets headers collection of attachment. |
| [getLinkedResources()](#getLinkedResources--) | Gets the set of embedded resources referred to by this alternate view. |
| [getTransferEncoding()](#getTransferEncoding--) | Gets or sets the transfer encoding. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the specified stream. |
| [save(String fileName)](#save-java.lang.String-) | Saves the specified file name. |
| [setBaseUri(URI value)](#setBaseUri-java.net.URI-) | Gets or sets the base URI. |
| [setContentId(String value)](#setContentId-java.lang.String-) | Gets or sets the content id. |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | Gets or sets the content stream. |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | Gets or sets the type of the content. |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | Gets or sets the transfer encoding. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AlternateView(String fileName) {#AlternateView-java.lang.String-}
```
public AlternateView(String fileName)
```


Initializes a new instance of the [AlternateView](../../com.aspose.email/alternateview) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |

### AlternateView(String fileName, String mediaType) {#AlternateView-java.lang.String-java.lang.String-}
```
public AlternateView(String fileName, String mediaType)
```


Initializes a new instance of the [AlternateView](../../com.aspose.email/alternateview) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |
| mediaType | java.lang.String | Internet media type. |

### AlternateView(String fileName, ContentType contentType) {#AlternateView-java.lang.String-com.aspose.email.ContentType-}
```
public AlternateView(String fileName, ContentType contentType)
```


Initializes a new instance of the [AlternateView](../../com.aspose.email/alternateview) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | Content type. |

### AlternateView(InputStream contentStream) {#AlternateView-java.io.InputStream-}
```
public AlternateView(InputStream contentStream)
```


Initializes a new instance of the [AlternateView](../../com.aspose.email/alternateview) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | The content stream. |

### AlternateView(InputStream contentStream, String mediaType) {#AlternateView-java.io.InputStream-java.lang.String-}
```
public AlternateView(InputStream contentStream, String mediaType)
```


Initializes a new instance of the [AlternateView](../../com.aspose.email/alternateview) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | The content stream. |
| mediaType | java.lang.String | Internet media type. |

### AlternateView(InputStream contentStream, ContentType contentType) {#AlternateView-java.io.InputStream-com.aspose.email.ContentType-}
```
public AlternateView(InputStream contentStream, ContentType contentType)
```


Initializes a new instance of the [AlternateView](../../com.aspose.email/alternateview) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | The content stream. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | Content type. |

### close() {#close--}
```
public void close()
```




### createAlternateViewFromString(String content) {#createAlternateViewFromString-java.lang.String-}
```
public static AlternateView createAlternateViewFromString(String content)
```


Creates a AlternateView of using the content specified in a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The string that contains the content. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An AlternateView object that represents an alternate view.
### createAlternateViewFromString(String content, ContentType contentType) {#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-}
```
public static AlternateView createAlternateViewFromString(String content, ContentType contentType)
```


Creates a AlternateView of using the content specified in a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The string that contains the content. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | Content type. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An AlternateView object that represents an alternate view.
### createAlternateViewFromString(String content, ContentType contentType, int transferencoding) {#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-int-}
```
public static AlternateView createAlternateViewFromString(String content, ContentType contentType, int transferencoding)
```


Creates a AlternateView of using the content specified in a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The string that contains the content. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | Content type. |
| transferencoding | int | The transfer encoding. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An AlternateView object that represents an alternate view.
### createAlternateViewFromString(String content, Charset contentEncoding, String mediaType) {#createAlternateViewFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-}
```
public static AlternateView createAlternateViewFromString(String content, Charset contentEncoding, String mediaType)
```


Creates a AlternateView of using the content specified in a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The string that contains the content. |
| contentEncoding | java.nio.charset.Charset | The content encoding. |
| mediaType | java.lang.String | Internet media type. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - An AlternateView object that represents an alternate view.
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
### getBaseUri() {#getBaseUri--}
```
public final URI getBaseUri()
```


Gets or sets the base URI.

Value: The base URI.

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


Gets or sets the content id.

Value: The content id.

**Returns:**
java.lang.String
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
### getLinkedResources() {#getLinkedResources--}
```
public final LinkedResourceCollection getLinkedResources()
```


Gets the set of embedded resources referred to by this alternate view.

Value: The linked resources.

**Returns:**
[LinkedResourceCollection](../../com.aspose.email/linkedresourcecollection)
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

### setBaseUri(URI value) {#setBaseUri-java.net.URI-}
```
public final void setBaseUri(URI value)
```


Gets or sets the base URI.

Value: The base URI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.net.URI |  |

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

