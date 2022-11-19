---
title: ReferenceAttachment
second_title: Aspose.Email for Java API Reference
description: This class represents a reference attachment
type: docs
weight: 587
url: /java/com.aspose.email/referenceattachment/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AttachmentBase](../../com.aspose.email/attachmentbase), [com.aspose.email.Attachment](../../com.aspose.email/attachment)
```
public class ReferenceAttachment extends Attachment
```

This class represents a reference attachment
## Constructors

| Constructor | Description |
| --- | --- |
| [ReferenceAttachment()](#ReferenceAttachment--) | Initializes a new instance of [ReferenceAttachment](../../com.aspose.email/referenceattachment). |
| [ReferenceAttachment(URI uri)](#ReferenceAttachment-java.net.URI-) | Initializes a new instance of [ReferenceAttachment](../../com.aspose.email/referenceattachment). |
| [ReferenceAttachment(String uri)](#ReferenceAttachment-java.lang.String-) | Initializes a new instance of [ReferenceAttachment](../../com.aspose.email/referenceattachment). |
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
| [getPermissionType()](#getPermissionType--) | Specifies the permission type. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets or sets a preferred text encoding |
| [getProviderType()](#getProviderType--) | Specifies the provider type. |
| [getTransferEncoding()](#getTransferEncoding--) | Gets or sets the transfer encoding. |
| [getUri()](#getUri--) | Specifies the Url of the provider endpoint. |
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
| [setPermissionType(int value)](#setPermissionType-int-) | Specifies the permission type. |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Gets or sets a preferred text encoding |
| [setProviderType(int value)](#setProviderType-int-) | Specifies the provider type. |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | Gets or sets the transfer encoding. |
| [setUri(URI value)](#setUri-java.net.URI-) | Specifies the Url of the provider endpoint. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ReferenceAttachment() {#ReferenceAttachment--}
```
public ReferenceAttachment()
```


Initializes a new instance of [ReferenceAttachment](../../com.aspose.email/referenceattachment).

### ReferenceAttachment(URI uri) {#ReferenceAttachment-java.net.URI-}
```
public ReferenceAttachment(URI uri)
```


Initializes a new instance of [ReferenceAttachment](../../com.aspose.email/referenceattachment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uri | java.net.URI | Url |

### ReferenceAttachment(String uri) {#ReferenceAttachment-java.lang.String-}
```
public ReferenceAttachment(String uri)
```


Initializes a new instance of [ReferenceAttachment](../../com.aspose.email/referenceattachment).

**Parameters:**
| Parameter | Type | Description |
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
### getPermissionType() {#getPermissionType--}
```
public final int getPermissionType()
```


Specifies the permission type.

**Returns:**
int
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


Gets or sets a preferred text encoding

**Returns:**
java.nio.charset.Charset
### getProviderType() {#getProviderType--}
```
public final int getProviderType()
```


Specifies the provider type.

**Returns:**
int
### getTransferEncoding() {#getTransferEncoding--}
```
public final int getTransferEncoding()
```


Gets or sets the transfer encoding.

Value: The transfer encoding.

**Returns:**
int
### getUri() {#getUri--}
```
public final URI getUri()
```


Specifies the Url of the provider endpoint.

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

### setPermissionType(int value) {#setPermissionType-int-}
```
public final void setPermissionType(int value)
```


Specifies the permission type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


Gets or sets a preferred text encoding

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setProviderType(int value) {#setProviderType-int-}
```
public final void setProviderType(int value)
```


Specifies the provider type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

### setUri(URI value) {#setUri-java.net.URI-}
```
public final void setUri(URI value)
```


Specifies the Url of the provider endpoint.

**Parameters:**
| Parameter | Type | Description |
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

