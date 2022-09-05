---
title: LinkedResource
second_title: Aspose.Email for Java API Reference
description:  Represents an embedded resource in a message.
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
| [getContentLink()](#getContentLink--) | Gets or sets a URI that the resource must match. |
| [setContentLink(URI value)](#setContentLink-java.net.URI-) | Gets or sets a URI that the resource must match. |
| [getContentDisposition()](#getContentDisposition--) | Gets Content-Disposition header |
| [createLinkedResourceFromString(String content)](#createLinkedResourceFromString-java.lang.String-) | Creates the linked resource from string. |
| [createLinkedResourceFromString(String content, Charset contentEncoding, String mediaType)](#createLinkedResourceFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-) | Creates the linked resource from string. |
| [createLinkedResourceFromString(String content, ContentType contentType)](#createLinkedResourceFromString-java.lang.String-com.aspose.email.ContentType-) | Creates the linked resource from string. |
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

### getContentLink() {#getContentLink--}
```
public final URI getContentLink()
```


Gets or sets a URI that the resource must match.

**Returns:**
java.net.URI
### setContentLink(URI value) {#setContentLink-java.net.URI-}
```
public final void setContentLink(URI value)
```


Gets or sets a URI that the resource must match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.net.URI |  |

### getContentDisposition() {#getContentDisposition--}
```
public final ContentDisposition getContentDisposition()
```


Gets Content-Disposition header

**Returns:**
[ContentDisposition](../../com.aspose.email/contentdisposition)
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
