---
title: ReferenceAttachment
second_title: Aspose.Email for Java API Reference
description: An attachment that is a link to a file in a cloud storage such as OneDrive instead of the file itself.
type: docs
weight: 627
url: /java/com.aspose.email/referenceattachment/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AttachmentBase](../../com.aspose.email/attachmentbase), [com.aspose.email.Attachment](../../com.aspose.email/attachment)
```
public class ReferenceAttachment extends Attachment
```

An attachment that is a link to a file in a cloud storage, such as OneDrive, instead of the file itself.
## Constructors

| Constructor | Description |
| --- | --- |
| [ReferenceAttachment()](#ReferenceAttachment--) | Initializes a new instance of [ReferenceAttachment](../../com.aspose.email/referenceattachment). |
| [ReferenceAttachment(URI uri)](#ReferenceAttachment-java.net.URI-) | Initializes a new instance of the [ReferenceAttachment](../../com.aspose.email/referenceattachment) class with the URL of the file. |
| [ReferenceAttachment(String uri)](#ReferenceAttachment-java.lang.String-) | Initializes a new instance of the [ReferenceAttachment](../../com.aspose.email/referenceattachment) class with the URL of the file. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Releases the resources used by the part, including its content stream. |
| [createAttachmentFromString(String content, ContentType contentType)](#createAttachmentFromString-java.lang.String-com.aspose.email.ContentType-) | Creates an attachment from a string with the specified content type. |
| [createAttachmentFromString(String content, String name)](#createAttachmentFromString-java.lang.String-java.lang.String-) | Creates a text attachment from a string. |
| [createAttachmentFromString(String content, String name, Charset contentEncoding, String mediaType)](#createAttachmentFromString-java.lang.String-java.lang.String-java.nio.charset.Charset-java.lang.String-) | Creates an attachment from a string with the specified encoding and media type. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | Gets the  Content-Disposition  header of the attachment, which tells whether it is shown inline or as a file, and holds its file name and dates. |
| [getContentId()](#getContentId--) | Gets the content ID of the part, by which HTML refers to it with a  cid:  URL. |
| [getContentStream()](#getContentStream--) | Gets the stream that holds the content. |
| [getContentType()](#getContentType--) | Gets the content type of the part: its media type, name and character set. |
| [getHeaders()](#getHeaders--) | Gets the MIME headers of the part. |
| [getName()](#getName--) | Gets the file name of the attachment. |
| [getNameEncoding()](#getNameEncoding--) | Gets the encoding used for the file name of the attachment in the headers. |
| [getPermissionType()](#getPermissionType--) | Gets who can view or edit the linked file. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets the encoding used for the text of the attachment when no other encoding is specified. |
| [getProviderType()](#getProviderType--) | Gets the cloud storage service that holds the file. |
| [getTransferEncoding()](#getTransferEncoding--) | Gets how the content is encoded for transfer, such as Base64 or quoted-printable. |
| [getUniqueId()](#getUniqueId--) | Gets an identifier of the part that stays the same while the application runs. |
| [getUri()](#getUri--) | Gets the URL of the file. |
| [hashCode()](#hashCode--) |  |
| [isEmbeddedMessage()](#isEmbeddedMessage--) | Gets a value indicating whether the attachment is an attached e-mail message ( message/rfc822 ). |
| [isTnef()](#isTnef--) | Gets a value indicating whether the attachment is a TNEF-encoded message (winmail.dat). |
| [isUri()](#isUri--) | Gets a value indicating whether the attachment is a link to content elsewhere rather than the content itself. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the decoded content of the part to a stream. |
| [save(String fileName)](#save-java.lang.String-) | Saves the decoded content of the part to a file. |
| [setContentId(String value)](#setContentId-java.lang.String-) | Sets the content ID of the part, by which HTML refers to it with a  cid:  URL. |
| [setContentStream(InputStream value)](#setContentStream-java.io.InputStream-) | Sets the stream that holds the content. |
| [setContentType(ContentType value)](#setContentType-com.aspose.email.ContentType-) | Sets the content type of the part: its media type, name and character set. |
| [setName(String value)](#setName-java.lang.String-) | Sets the file name of the attachment. |
| [setNameEncoding(Charset value)](#setNameEncoding-java.nio.charset.Charset-) | Sets the encoding used for the file name of the attachment in the headers. |
| [setPermissionType(int value)](#setPermissionType-int-) | Sets who can view or edit the linked file. |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Sets the encoding used for the text of the attachment when no other encoding is specified. |
| [setProviderType(int value)](#setProviderType-int-) | Sets the cloud storage service that holds the file. |
| [setTransferEncoding(int value)](#setTransferEncoding-int-) | Sets how the content is encoded for transfer, such as Base64 or quoted-printable. |
| [setUri(URI value)](#setUri-java.net.URI-) | Sets the URL of the file. |
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


Initializes a new instance of the [ReferenceAttachment](../../com.aspose.email/referenceattachment) class with the URL of the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uri | java.net.URI | The URL of the file. |

### ReferenceAttachment(String uri) {#ReferenceAttachment-java.lang.String-}
```
public ReferenceAttachment(String uri)
```


Initializes a new instance of the [ReferenceAttachment](../../com.aspose.email/referenceattachment) class with the URL of the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uri | java.lang.String | The URL of the file. |

### close() {#close--}
```
public void close()
```


Releases the resources used by the part, including its content stream.

### createAttachmentFromString(String content, ContentType contentType) {#createAttachmentFromString-java.lang.String-com.aspose.email.ContentType-}
```
public static Attachment createAttachmentFromString(String content, ContentType contentType)
```


Creates an attachment from a string with the specified content type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content of the attachment. |
| contentType | [ContentType](../../com.aspose.email/contenttype) | The content type of the attachment, including its name. |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - The new attachment.
### createAttachmentFromString(String content, String name) {#createAttachmentFromString-java.lang.String-java.lang.String-}
```
public static Attachment createAttachmentFromString(String content, String name)
```


Creates a text attachment from a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content of the attachment. |
| name | java.lang.String | The file name of the attachment. |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - The new attachment.
### createAttachmentFromString(String content, String name, Charset contentEncoding, String mediaType) {#createAttachmentFromString-java.lang.String-java.lang.String-java.nio.charset.Charset-java.lang.String-}
```
public static Attachment createAttachmentFromString(String content, String name, Charset contentEncoding, String mediaType)
```


Creates an attachment from a string with the specified encoding and media type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content of the attachment. |
| name | java.lang.String | The file name of the attachment. |
| contentEncoding | java.nio.charset.Charset | The character encoding of the content. |
| mediaType | java.lang.String | The MIME media type of the content, such as  text/html . |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - The new attachment.
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


Gets the  Content-Disposition  header of the attachment, which tells whether it is shown inline or as a file, and holds its file name and dates.

**Returns:**
[ContentDisposition](../../com.aspose.email/contentdisposition)
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
### getName() {#getName--}
```
public final String getName()
```


Gets the file name of the attachment.

**Returns:**
java.lang.String
### getNameEncoding() {#getNameEncoding--}
```
public final Charset getNameEncoding()
```


Gets the encoding used for the file name of the attachment in the headers.

**Returns:**
java.nio.charset.Charset
### getPermissionType() {#getPermissionType--}
```
public final int getPermissionType()
```


Gets who can view or edit the linked file.

**Returns:**
int
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


Gets the encoding used for the text of the attachment when no other encoding is specified.

**Returns:**
java.nio.charset.Charset
### getProviderType() {#getProviderType--}
```
public final int getProviderType()
```


Gets the cloud storage service that holds the file.

**Returns:**
int
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
### getUri() {#getUri--}
```
public final URI getUri()
```


Gets the URL of the file.

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


Gets a value indicating whether the attachment is an attached e-mail message ( message/rfc822 ).

**Returns:**
boolean
### isTnef() {#isTnef--}
```
public final boolean isTnef()
```


Gets a value indicating whether the attachment is a TNEF-encoded message (winmail.dat).

**Returns:**
boolean
### isUri() {#isUri--}
```
public final boolean isUri()
```


Gets a value indicating whether the attachment is a link to content elsewhere rather than the content itself.

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

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Sets the file name of the attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameEncoding(Charset value) {#setNameEncoding-java.nio.charset.Charset-}
```
public final void setNameEncoding(Charset value)
```


Sets the encoding used for the file name of the attachment in the headers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPermissionType(int value) {#setPermissionType-int-}
```
public final void setPermissionType(int value)
```


Sets who can view or edit the linked file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


Sets the encoding used for the text of the attachment when no other encoding is specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setProviderType(int value) {#setProviderType-int-}
```
public final void setProviderType(int value)
```


Sets the cloud storage service that holds the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTransferEncoding(int value) {#setTransferEncoding-int-}
```
public final void setTransferEncoding(int value)
```


Sets how the content is encoded for transfer, such as Base64 or quoted-printable.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The transfer encoding. |

### setUri(URI value) {#setUri-java.net.URI-}
```
public final void setUri(URI value)
```


Sets the URL of the file.

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

