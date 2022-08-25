---
title: Attachment
second_title: Aspose.Email for Java API Reference
description:  Represents an e-mail attachment.
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
| [isEmbeddedMessage()](#isEmbeddedMessage--) | Gets a value indicating whether the attachment is an embedded message. |
| [getName()](#getName--) | Gets or sets an attachment name |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets an attachment name |
| [getNameEncoding()](#getNameEncoding--) | Gets or sets an encoding of attachment name |
| [setNameEncoding(Charset value)](#setNameEncoding-java.nio.charset.Charset-) | Gets or sets an encoding of attachment name |
| [getContentDisposition()](#getContentDisposition--) | Gets Content-Disposition header |
| [isUri()](#isUri--) | Gets a value indicating whether attachment is URI-attachment. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets or sets a preferred text encoding |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Gets or sets a preferred text encoding |
| [createAttachmentFromString(String content, String name)](#createAttachmentFromString-java.lang.String-java.lang.String-) | Creates the attachment from string. |
| [createAttachmentFromString(String content, String name, Charset contentEncoding, String mediaType)](#createAttachmentFromString-java.lang.String-java.lang.String-java.nio.charset.Charset-java.lang.String-) | Creates the attachment from string. |
| [createAttachmentFromString(String content, ContentType contentType)](#createAttachmentFromString-java.lang.String-com.aspose.email.ContentType-) | Creates the attachment from string. |
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
| contentType | [ContentType](../../com.aspose.email/contenttype) | The \`\`\` ContentType \`\`\`([AttachmentBase\#getContentType](../../com.aspose.email/attachmentbase\#getContentType)/[AttachmentBase\#setContentType(ContentType)](../../com.aspose.email/attachmentbase\#setContentType-ContentType-)). |

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
| contentType | [ContentType](../../com.aspose.email/contenttype) | The \`\`\` ContentType \`\`\`([AttachmentBase\#getContentType](../../com.aspose.email/attachmentbase\#getContentType)/[AttachmentBase\#setContentType(ContentType)](../../com.aspose.email/attachmentbase\#setContentType-ContentType-)). |

### isEmbeddedMessage() {#isEmbeddedMessage--}
```
public final boolean isEmbeddedMessage()
```


Gets a value indicating whether the attachment is an embedded message.

**Returns:**
boolean
### getName() {#getName--}
```
public final String getName()
```


Gets or sets an attachment name

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gets or sets an attachment name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNameEncoding() {#getNameEncoding--}
```
public final Charset getNameEncoding()
```


Gets or sets an encoding of attachment name

**Returns:**
java.nio.charset.Charset
### setNameEncoding(Charset value) {#setNameEncoding-java.nio.charset.Charset-}
```
public final void setNameEncoding(Charset value)
```


Gets or sets an encoding of attachment name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### getContentDisposition() {#getContentDisposition--}
```
public final ContentDisposition getContentDisposition()
```


Gets Content-Disposition header

**Returns:**
[ContentDisposition](../../com.aspose.email/contentdisposition)
### isUri() {#isUri--}
```
public final boolean isUri()
```


Gets a value indicating whether attachment is URI-attachment.

**Returns:**
boolean
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


Gets or sets a preferred text encoding

**Returns:**
java.nio.charset.Charset
### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


Gets or sets a preferred text encoding

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

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
### createAttachmentFromString(String content, ContentType contentType) {#createAttachmentFromString-java.lang.String-com.aspose.email.ContentType-}
```
public static Attachment createAttachmentFromString(String content, ContentType contentType)
```


Creates the attachment from string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | A string that represents the content of attachment. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | The \`\`\` ContentType \`\`\`([AttachmentBase\#getContentType](../../com.aspose.email/attachmentbase\#getContentType)/[AttachmentBase\#setContentType(ContentType)](../../com.aspose.email/attachmentbase\#setContentType-ContentType-)). |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - Returns created attachment
