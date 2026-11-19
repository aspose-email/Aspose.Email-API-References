---
title: IMessage
second_title: Aspose.Email for Java API Reference
description: The common interface of messages.
type: docs
weight: 798
url: /java/com.aspose.email/imessage/
---
```
public interface IMessage
```

The common interface of messages.
## Methods

| Method | Description |
| --- | --- |
| [getAttachments()](#getAttachments--) | Gets the attachments of the message. |
| [getBcc()](#getBcc--) | Gets the BCC recipients. |
| [getBody()](#getBody--) | Gets the plain-text body. |
| [getBodyType()](#getBodyType--) | Gets the format of the body: plain text, HTML or RTF. |
| [getCC()](#getCC--) | Gets the CC recipients. |
| [getDate()](#getDate--) | Gets the date and time of the message. |
| [getFrom()](#getFrom--) | Gets the author of the message. |
| [getHtmlBody()](#getHtmlBody--) | Gets the HTML body. |
| [getSubject()](#getSubject--) | Gets the subject. |
| [getTo()](#getTo--) | Gets the To recipients. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the message to a stream. |
| [save(String fileName)](#save-java.lang.String-) | Saves the message to a file. |
| [setBody(String value)](#setBody-java.lang.String-) | Sets the plain-text body. |
| [setFrom(IMailAddress value)](#setFrom-com.aspose.email.IMailAddress-) | Sets the author of the message. |
| [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Sets the HTML body. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject. |
### getAttachments() {#getAttachments--}
```
public abstract System.Collections.Generic.IGenericCollection<Attachment> getAttachments()
```


Gets the attachments of the message.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.Attachment>
### getBcc() {#getBcc--}
```
public abstract System.Collections.Generic.IGenericCollection<MailAddress> getBcc()
```


Gets the BCC recipients.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### getBody() {#getBody--}
```
public abstract String getBody()
```


Gets the plain-text body.

**Returns:**
java.lang.String
### getBodyType() {#getBodyType--}
```
public abstract int getBodyType()
```


Gets the format of the body: plain text, HTML or RTF.

**Returns:**
int
### getCC() {#getCC--}
```
public abstract System.Collections.Generic.IGenericCollection<MailAddress> getCC()
```


Gets the CC recipients.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### getDate() {#getDate--}
```
public abstract Date getDate()
```


Gets the date and time of the message.

**Returns:**
java.util.Date
### getFrom() {#getFrom--}
```
public abstract IMailAddress getFrom()
```


Gets the author of the message.

**Returns:**
[IMailAddress](../../com.aspose.email/imailaddress)
### getHtmlBody() {#getHtmlBody--}
```
public abstract String getHtmlBody()
```


Gets the HTML body.

**Returns:**
java.lang.String
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Gets the subject.

**Returns:**
java.lang.String
### getTo() {#getTo--}
```
public abstract System.Collections.Generic.IGenericCollection<MailAddress> getTo()
```


Gets the To recipients.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream stream)
```


Saves the message to a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |

### save(String fileName) {#save-java.lang.String-}
```
public abstract void save(String fileName)
```


Saves the message to a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to write. |

### setBody(String value) {#setBody-java.lang.String-}
```
public abstract void setBody(String value)
```


Sets the plain-text body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFrom(IMailAddress value) {#setFrom-com.aspose.email.IMailAddress-}
```
public abstract void setFrom(IMailAddress value)
```


Sets the author of the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMailAddress](../../com.aspose.email/imailaddress) |  |

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public abstract void setHtmlBody(String value)
```


Sets the HTML body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```


Sets the subject.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

