---
title: LoadOptions
second_title: Aspose.Email for Java API Reference
description:  This is an abstract base class for classes that allow the user to specify additional options when loading a MailMessage
 from a particular format.
type: docs
weight: 353
url: /java/com.aspose.email/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class LoadOptions
```

This is an abstract base class for classes that allow the user to specify additional options when loading a MailMessage from a particular format.
## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPrefferedTextEncoding()](#getPrefferedTextEncoding--) | Gets or sets preferred encoding for message. |
| [setPrefferedTextEncoding(Charset value)](#setPrefferedTextEncoding-java.nio.charset.Charset-) | Gets or sets preferred encoding for message. |
| [getMessageFormat()](#getMessageFormat--) | Represents the mail message format.It can be in eml,msg or mhtml format. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading in MailMessage. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading in MailMessage. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getPrefferedTextEncoding() {#getPrefferedTextEncoding--}
```
public final Charset getPrefferedTextEncoding()
```


Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null.

**Returns:**
java.nio.charset.Charset
### setPrefferedTextEncoding(Charset value) {#setPrefferedTextEncoding-java.nio.charset.Charset-}
```
public final void setPrefferedTextEncoding(Charset value)
```


Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### getMessageFormat() {#getMessageFormat--}
```
public final MessageFormat getMessageFormat()
```


Represents the mail message format.It can be in eml,msg or mhtml format. The default value is Eml.

**Returns:**
[MessageFormat](../../com.aspose.email/messageformat)
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading in MailMessage.

**Returns:**
boolean
### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading in MailMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

