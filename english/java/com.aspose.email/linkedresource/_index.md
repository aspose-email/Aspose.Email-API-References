---
title: LinkedResource
second_title: Aspose.Email for Java API Reference
description: Represents an embedded resource such as an image or file that can be referenced by an  in an email message.
type: docs
weight: 369
url: /java/com.aspose.email/linkedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AttachmentBase](../../com.aspose.email/attachmentbase)
```
public class LinkedResource extends AttachmentBase
```

Represents an embedded resource (such as an image or file) that can be referenced by an [AlternateView](../../com.aspose.email/alternateview) in an email message. Linked resources are typically used to embed images, fonts, or other assets directly into HTML email content using Content-ID references.

Linked resources are added to [MailMessage.getLinkedResources()](../../com.aspose.email/mailmessage\#getLinkedResources--) and referenced in HTML content using the 'cid:' prefix (e.g., <img src='cid:resourceId'>). They differ from regular [Attachment](../../com.aspose.email/attachment) objects in that they are embedded within the message body rather than appearing as downloadable attachments.

The following example shows how to embed objects using LinkedResource into an Email.

```

 MailMessage eml = new MailMessage();
 eml.setFrom(MailAddress.to_MailAddress("AndrewIrwin@from.com"));
 eml.setTo(MailAddressCollection.to_MailAddressCollection("SusanMarc@to.com"));
 eml.setSubject("This is an email");

 // Create the plain text part It is viewable by those clients that don't support HTML
 AlternateView plainView =
         AlternateView.createAlternateViewFromString("This is my plain text content", null, "text/plain");

 // Create the HTML part.To embed images, we need to use the prefix 'cid' in the img src value.
 // The cid value will map to the Content-Id of a Linked resource. Thus 
 // will map to a LinkedResource with a ContentId of 'barcode'.
 AlternateView htmlView =
         AlternateView.createAlternateViewFromString("Here is an embedded image.", null,
                 "text/html");

 // Create the LinkedResource (embedded image) and Add the LinkedResource to the appropriate view
 LinkedResource barcode = new LinkedResource("1.jpg", "image/jpeg");
 barcode.setContentId("barcode");

 eml.getLinkedResources().addItem(barcode);
 eml.getAlternateViews().addItem(plainView);
 eml.getAlternateViews().addItem(htmlView);

 eml.save("EmbeddedImage_out.msg", SaveOptions.getDefaultMsgUnicode());
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [LinkedResource(String fileName)](#LinkedResource-java.lang.String-) | Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class with the content of a file. |
| [LinkedResource(String fileName, String mediaType)](#LinkedResource-java.lang.String-java.lang.String-) | Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class with the content of a file. |
| [LinkedResource(String fileName, ContentType contentType)](#LinkedResource-java.lang.String-com.aspose.email.ContentType-) | Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class with the content of a file. |
| [LinkedResource(InputStream contentStream)](#LinkedResource-java.io.InputStream-) | Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class with the content of a stream. |
| [LinkedResource(InputStream contentStream, String mediaType)](#LinkedResource-java.io.InputStream-java.lang.String-) | Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class with the content of a stream. |
| [LinkedResource(InputStream contentStream, ContentType contentType)](#LinkedResource-java.io.InputStream-com.aspose.email.ContentType-) | Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class with the content of a stream. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Releases the resources used by the part, including its content stream. |
| [createLinkedResourceFromString(String content)](#createLinkedResourceFromString-java.lang.String-) | Creates a linked resource from a string. |
| [createLinkedResourceFromString(String content, ContentType contentType)](#createLinkedResourceFromString-java.lang.String-com.aspose.email.ContentType-) | Creates a linked resource from a string. |
| [createLinkedResourceFromString(String content, Charset contentEncoding, String mediaType)](#createLinkedResourceFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-) | Creates a linked resource from a string. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | Gets the  Content-Disposition  header of the resource. |
| [getContentId()](#getContentId--) | Gets the content ID of the part, by which HTML refers to it with a  cid:  URL. |
| [getContentLink()](#getContentLink--) | Gets the URI by which the HTML refers to the resource, as an alternative to its content ID. |
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
| [setContentLink(URI value)](#setContentLink-java.net.URI-) | Sets the URI by which the HTML refers to the resource, as an alternative to its content ID. |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | Sets the stream that holds the content. |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | Sets the content type of the part: its media type, name and character set. |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | Sets how the content is encoded for transfer, such as Base64 or quoted-printable. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinkedResource(String fileName) {#LinkedResource-java.lang.String-}
```
public LinkedResource(String fileName)
```


Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class with the content of a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file that contains the resource. |

### LinkedResource(String fileName, String mediaType) {#LinkedResource-java.lang.String-java.lang.String-}
```
public LinkedResource(String fileName, String mediaType)
```


Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class with the content of a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file that contains the resource. |
| mediaType | java.lang.String | The MIME media type, such as  image/png . |

### LinkedResource(String fileName, ContentType contentType) {#LinkedResource-java.lang.String-com.aspose.email.ContentType-}
```
public LinkedResource(String fileName, ContentType contentType)
```


Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class with the content of a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file that contains the resource. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | The content type of the resource. |

### LinkedResource(InputStream contentStream) {#LinkedResource-java.io.InputStream-}
```
public LinkedResource(InputStream contentStream)
```


Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class with the content of a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | The stream that contains the resource. |

### LinkedResource(InputStream contentStream, String mediaType) {#LinkedResource-java.io.InputStream-java.lang.String-}
```
public LinkedResource(InputStream contentStream, String mediaType)
```


Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class with the content of a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | The stream that contains the resource. |
| mediaType | java.lang.String | The MIME media type, such as  image/png . |

### LinkedResource(InputStream contentStream, ContentType contentType) {#LinkedResource-java.io.InputStream-com.aspose.email.ContentType-}
```
public LinkedResource(InputStream contentStream, ContentType contentType)
```


Initializes a new instance of the [LinkedResource](../../com.aspose.email/linkedresource) class with the content of a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentStream | java.io.InputStream | The stream that contains the resource. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | The content type of the resource. |

### close() {#close--}
```
public void close()
```


Releases the resources used by the part, including its content stream.

### createLinkedResourceFromString(String content) {#createLinkedResourceFromString-java.lang.String-}
```
public static LinkedResource createLinkedResourceFromString(String content)
```


Creates a linked resource from a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content of the resource. |

**Returns:**
[LinkedResource](../../com.aspose.email/linkedresource) - The new linked resource.
### createLinkedResourceFromString(String content, ContentType contentType) {#createLinkedResourceFromString-java.lang.String-com.aspose.email.ContentType-}
```
public static LinkedResource createLinkedResourceFromString(String content, ContentType contentType)
```


Creates a linked resource from a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content of the resource. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | The content type of the resource. |

**Returns:**
[LinkedResource](../../com.aspose.email/linkedresource) - The new linked resource.
### createLinkedResourceFromString(String content, Charset contentEncoding, String mediaType) {#createLinkedResourceFromString-java.lang.String-java.nio.charset.Charset-java.lang.String-}
```
public static LinkedResource createLinkedResourceFromString(String content, Charset contentEncoding, String mediaType)
```


Creates a linked resource from a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content of the resource. |
| contentEncoding | java.nio.charset.Charset | The character encoding of the content. |
| mediaType | java.lang.String | The MIME media type of the content. |

**Returns:**
[LinkedResource](../../com.aspose.email/linkedresource) - The new linked resource.
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


Gets the  Content-Disposition  header of the resource.

**Returns:**
[ContentDisposition](../../com.aspose.email/contentdisposition)
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Gets the content ID of the part, by which HTML refers to it with a  cid:  URL.

**Returns:**
java.lang.String - The content ID.
### getContentLink() {#getContentLink--}
```
public final URI getContentLink()
```


Gets the URI by which the HTML refers to the resource, as an alternative to its content ID.

**Returns:**
java.net.URI
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

### setContentLink(URI value) {#setContentLink-java.net.URI-}
```
public final void setContentLink(URI value)
```


Sets the URI by which the HTML refers to the resource, as an alternative to its content ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.net.URI |  |

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

