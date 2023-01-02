---
title: IMessage
second_title: Aspose.Email for Java API Reference
description: Represents a common message interface
type: docs
weight: 746
url: /java/com.aspose.email/imessage/
---
```
public interface IMessage
```

Represents a common message interface
## Methods

| Method | Description |
| --- | --- |
| [getAttachments()](#getAttachments--) | Gets message attachments |
| [getBcc()](#getBcc--) | Gets BCC recipients |
| [getBody()](#getBody--) | Gets or sets a message body |
| [getBodyType()](#getBodyType--) | Gets the type of the body. |
| [getCC()](#getCC--) | Gets CC recipients |
| [getDate()](#getDate--) | Gets the date and time when message was delivered |
| [getFrom()](#getFrom--) | Gets or sets a from address |
| [getHtmlBody()](#getHtmlBody--) | Gets or sets a html formatted message body |
| [getSubject()](#getSubject--) | Gets or sets a message subject |
| [getTo()](#getTo--) | Gets recipients |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves message to the specified stream |
| [save(String fileName)](#save-java.lang.String-) | Saves message to the specified file |
| [setBody(String value)](#setBody-java.lang.String-) | Gets or sets a message body |
| [setFrom(IMailAddress value)](#setFrom-com.aspose.email.IMailAddress-) | Gets or sets a from address |
| [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Gets or sets a html formatted message body |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets or sets a message subject |
### getAttachments() {#getAttachments--}
```
public abstract System.Collections.Generic.IGenericCollection<Attachment> getAttachments()
```


Gets message attachments

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.Attachment>
### getBcc() {#getBcc--}
```
public abstract System.Collections.Generic.IGenericCollection<MailAddress> getBcc()
```


Gets BCC recipients

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### getBody() {#getBody--}
```
public abstract String getBody()
```


Gets or sets a message body

**Returns:**
java.lang.String
### getBodyType() {#getBodyType--}
```
public abstract int getBodyType()
```


Gets the type of the body.

**Returns:**
int
### getCC() {#getCC--}
```
public abstract System.Collections.Generic.IGenericCollection<MailAddress> getCC()
```


Gets CC recipients

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### getDate() {#getDate--}
```
public abstract Date getDate()
```


Gets the date and time when message was delivered

**Returns:**
java.util.Date
### getFrom() {#getFrom--}
```
public abstract IMailAddress getFrom()
```


Gets or sets a from address

**Returns:**
[IMailAddress](../../com.aspose.email/imailaddress)
### getHtmlBody() {#getHtmlBody--}
```
public abstract String getHtmlBody()
```


Gets or sets a html formatted message body

**Returns:**
java.lang.String
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Gets or sets a message subject

**Returns:**
java.lang.String
### getTo() {#getTo--}
```
public abstract System.Collections.Generic.IGenericCollection<MailAddress> getTo()
```


Gets recipients

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream stream)
```


Saves message to the specified stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to |

### save(String fileName) {#save-java.lang.String-}
```
public abstract void save(String fileName)
```


Saves message to the specified file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | A file name |

### setBody(String value) {#setBody-java.lang.String-}
```
public abstract void setBody(String value)
```


Gets or sets a message body

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFrom(IMailAddress value) {#setFrom-com.aspose.email.IMailAddress-}
```
public abstract void setFrom(IMailAddress value)
```


Gets or sets a from address

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMailAddress](../../com.aspose.email/imailaddress) |  |

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public abstract void setHtmlBody(String value)
```


Gets or sets a html formatted message body

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```


Gets or sets a message subject

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

