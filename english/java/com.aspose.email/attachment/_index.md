---
title: Attachment
second_title: Aspose.Email for Java API Reference
description: Represents an e-mail attachment.
type: docs
weight: 64
url: /java/com.aspose.email/attachment/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.AttachmentBase](../../com.aspose.email/attachmentbase)

**All Implemented Interfaces:**
[com.aspose.email.IPreferredTextEncodingProvider](../../com.aspose.email/ipreferredtextencodingprovider), [com.aspose.email.IAttachment](../../com.aspose.email/iattachment)
```
public class Attachment extends AttachmentBase implements IPreferredTextEncodingProvider, IAttachment
```

Represents an e-mail attachment.
## Constructors

| Constructor | Description |
| --- | --- |
| [Attachment(String fileName)](#Attachment-java.lang.String-) | Initializes a new instance of the [Attachment](../../com.aspose.email/attachment) class. |
| [Attachment(String fileName, String mediaType)](#Attachment-java.lang.String-java.lang.String-) | Initializes a new instance of the [Attachment](../../com.aspose.email/attachment) class. |
| [Attachment(String fileName, ContentType contentType)](#Attachment-java.lang.String-com.aspose.email.ContentType-) | Initializes a new instance of the [Attachment](../../com.aspose.email/attachment) class. |
| [Attachment(InputStream contentStream, String name)](#Attachment-java.io.InputStream-java.lang.String-) | Initializes a new instance of the [Attachment](../../com.aspose.email/attachment) class. |
| [Attachment(InputStream contentStream, String name, String mediaType)](#Attachment-java.io.InputStream-java.lang.String-java.lang.String-) | Initializes a new instance of the [Attachment](../../com.aspose.email/attachment) class. |
| [Attachment(InputStream contentStream, ContentType contentType)](#Attachment-java.io.InputStream-com.aspose.email.ContentType-) | Initializes a new instance of the [Attachment](../../com.aspose.email/attachment) class. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [createAttachmentFromString(String content, ContentType contentType)](#createAttachmentFromString-java.lang.String-com.aspose.email.ContentType-) | Creates the attachment from string. |
| [createAttachmentFromString(String content, String name)](#createAttachmentFromString-java.lang.String-java.lang.String-) | Creates the attachment from string. |
| [createAttachmentFromString(String content, String name, Charset contentEncoding, String mediaType)](#createAttachmentFromString-java.lang.String-java.lang.String-java.nio.charset.Charset-java.lang.String-) | Creates the attachment from string. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | Gets Content-Disposition header |
| [getContentId()](#getContentId--) | Gets or sets the content id. |
| [getContentStream()](#getContentStream--) | Gets or sets the content stream. |
| [getContentType()](#getContentType--) | Gets or sets the type of the content. |
| [getHeaders()](#getHeaders--) | Gets headers collection of attachment. |
| [getName()](#getName--) | Gets or sets an attachment name |
| [getNameEncoding()](#getNameEncoding--) | Gets or sets an encoding of attachment name |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets or sets a preferred text encoding |
| [getTransferEncoding()](#getTransferEncoding--) | Gets or sets the transfer encoding. |
| [hashCode()](#hashCode--) |  |
| [isEmbeddedMessage()](#isEmbeddedMessage--) | Gets a value indicating whether the attachment is an embedded message. |
| [isUri()](#isUri--) | Gets a value indicating whether attachment is URI-attachment. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the specified stream. |
| [save(String fileName)](#save-java.lang.String-) | Saves the specified file name. |
| [setContentId(String value)](#setContentId-java.lang.String-) | Gets or sets the content id. |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | Gets or sets the content stream. |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | Gets or sets the type of the content. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets an attachment name |
| [setNameEncoding(Charset value)](#setNameEncoding-java.nio.charset.Charset-) | Gets or sets an encoding of attachment name |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Gets or sets a preferred text encoding |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | Gets or sets the transfer encoding. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Attachment(String fileName) {#Attachment-java.lang.String-}
```
public Attachment(String fileName)
```


Initializes a new instance of the [Attachment](../../com.aspose.email/attachment) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |

### Attachment(String fileName, String mediaType) {#Attachment-java.lang.String-java.lang.String-}
```
public Attachment(String fileName, String mediaType)
```


Initializes a new instance of the [Attachment](../../com.aspose.email/attachment) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |
| mediaType | java.lang.String | Type media type name. |

### Attachment(String fileName, ContentType contentType) {#Attachment-java.lang.String-com.aspose.email.ContentType-}
```
public Attachment(String fileName, ContentType contentType)
```


Initializes a new instance of the [Attachment](../../com.aspose.email/attachment) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | The  ContentType ([AttachmentBase.getContentType](../../com.aspose.email/attachmentbase\#getContentType)/[AttachmentBase.setContentType(ContentType)](../../com.aspose.email/attachmentbase\#setContentType-ContentType-)). |

### Attachment(InputStream contentStream, String name) {#Attachment-java.io.InputStream-java.lang.String-}
```
public Attachment(InputStream contentStream, String name)
```


Initializes a new instance of the [Attachment](../../com.aspose.email/attachment) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | The content stream of attachment. |
| name | java.lang.String | The attachment name. |

### Attachment(InputStream contentStream, String name, String mediaType) {#Attachment-java.io.InputStream-java.lang.String-java.lang.String-}
```
public Attachment(InputStream contentStream, String name, String mediaType)
```


Initializes a new instance of the [Attachment](../../com.aspose.email/attachment) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | The content stream of attachment. |
| name | java.lang.String | The attachment name. |
| mediaType | java.lang.String | The media type name. |

### Attachment(InputStream contentStream, ContentType contentType) {#Attachment-java.io.InputStream-com.aspose.email.ContentType-}
```
public Attachment(InputStream contentStream, ContentType contentType)
```


Initializes a new instance of the [Attachment](../../com.aspose.email/attachment) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | The content stream of attachment. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | The  ContentType ([AttachmentBase.getContentType](../../com.aspose.email/attachmentbase\#getContentType)/[AttachmentBase.setContentType(ContentType)](../../com.aspose.email/attachmentbase\#setContentType-ContentType-)). |

### close() {#close--}
```
public void close()
```




### createAttachmentFromString(String content, ContentType contentType) {#createAttachmentFromString-java.lang.String-com.aspose.email.ContentType-}
```
public static Attachment createAttachmentFromString(String content, ContentType contentType)
```


Creates the attachment from string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | A string that represents the content of attachment. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | The  ContentType ([AttachmentBase.getContentType](../../com.aspose.email/attachmentbase\#getContentType)/[AttachmentBase.setContentType(ContentType)](../../com.aspose.email/attachmentbase\#setContentType-ContentType-)). |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - Returns created attachment
### createAttachmentFromString(String content, String name) {#createAttachmentFromString-java.lang.String-java.lang.String-}
```
public static Attachment createAttachmentFromString(String content, String name)
```


Creates the attachment from string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | A string that represents the content of attachment. |
| name | java.lang.String | The attachment name. |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - Returns created attachment
### createAttachmentFromString(String content, String name, Charset contentEncoding, String mediaType) {#createAttachmentFromString-java.lang.String-java.lang.String-java.nio.charset.Charset-java.lang.String-}
```
public static Attachment createAttachmentFromString(String content, String name, Charset contentEncoding, String mediaType)
```


Creates the attachment from string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | A string that represents the content of attachment. |
| name | java.lang.String | The attachment name. |
| contentEncoding | java.nio.charset.Charset | The content encoding. |
| mediaType | java.lang.String | The media type name |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - Returns created attachment
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
### getName() {#getName--}
```
public final String getName()
```


Gets or sets an attachment name

**Returns:**
java.lang.String
### getNameEncoding() {#getNameEncoding--}
```
public final Charset getNameEncoding()
```


Gets or sets an encoding of attachment name

**Returns:**
java.nio.charset.Charset
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


Gets or sets a preferred text encoding

**Returns:**
java.nio.charset.Charset
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
### isEmbeddedMessage() {#isEmbeddedMessage--}
```
public final boolean isEmbeddedMessage()
```


Gets a value indicating whether the attachment is an embedded message.

**Returns:**
boolean
### isUri() {#isUri--}
```
public final boolean isUri()
```


Gets a value indicating whether attachment is URI-attachment.

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

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gets or sets an attachment name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameEncoding(Charset value) {#setNameEncoding-java.nio.charset.Charset-}
```
public final void setNameEncoding(Charset value)
```


Gets or sets an encoding of attachment name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


Gets or sets a preferred text encoding

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

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

