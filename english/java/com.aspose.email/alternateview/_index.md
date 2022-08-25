---
title: AlternateView
second_title: Aspose.Email for Java API Reference
description:  Represents the format to view a message.
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
| [getLinkedResources()](#getLinkedResources--) | Gets the set of embedded resources referred to by this alternate view. |
| [getBaseUri()](#getBaseUri--) | Gets or sets the base URI. |
| [setBaseUri(URI value)](#setBaseUri-java.net.URI-) | Gets or sets the base URI. |
| [createAlternateViewFromString(String content)](#createAlternateViewFromString-java.lang.String-) | Creates a AlternateView of using the content specified in a string. |
| [createAlternateViewFromString(String content, Charset contentEncoding, String mediaType)](#createAlternateViewFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-) | Creates a AlternateView of using the content specified in a string. |
| [createAlternateViewFromString(String content, ContentType contentType)](#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-) | Creates a AlternateView of using the content specified in a string. |
| [createAlternateViewFromString(String content, ContentType contentType, int transferencoding)](#createAlternateViewFromString-java.lang.String-com.aspose.email.ContentType-int-) | Creates a AlternateView of using the content specified in a string. |
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

### getLinkedResources() {#getLinkedResources--}
```
public final LinkedResourceCollection getLinkedResources()
```


Gets the set of embedded resources referred to by this alternate view.

Value: The linked resources.

**Returns:**
[LinkedResourceCollection](../../com.aspose.email/linkedresourcecollection)
### getBaseUri() {#getBaseUri--}
```
public final URI getBaseUri()
```


Gets or sets the base URI.

Value: The base URI.

**Returns:**
java.net.URI
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
