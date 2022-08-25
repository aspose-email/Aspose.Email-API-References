---
title: EmlSaveOptions
second_title: Aspose.Email for Android via Java API Reference
description:  Allows to specify additional options when saving MailMessage to Eml and Emlx format.
type: docs
weight: 118
url: /java/com.aspose.email/emlsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions)
```
public class EmlSaveOptions extends SaveOptions
```

Allows to specify additional options when saving MailMessage to Eml and Emlx format.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmlSaveOptions(MailMessageSaveType saveType)](#EmlSaveOptions-com.aspose.email.MailMessageSaveType-) | Initializes a new instance of this class that can be used to save a MailMessage in the Eml and Emlx format. |
## Methods

| Method | Description |
| --- | --- |
| [getFileCompatibilityMode()](#getFileCompatibilityMode--) | Defines inner conversions,that are necessarily to be done when saving a message. |
| [setFileCompatibilityMode(int value)](#setFileCompatibilityMode-int-) | Defines inner conversions,that are necessarily to be done when saving a message. |
| [getPreserveSignedContent()](#getPreserveSignedContent--) | Gets or sets a value indicating whether it is necessary to save signed message without changes of content to provide correctly structure of digital sign. |
| [setPreserveSignedContent(boolean value)](#setPreserveSignedContent-boolean-) | Gets or sets a value indicating whether it is necessary to save signed message without changes of content to provide correctly structure of digital sign. |
| [getCheckBodyContentEncoding()](#getCheckBodyContentEncoding--) | Defines whether need check message body content encoding when saving. |
| [setCheckBodyContentEncoding(boolean value)](#setCheckBodyContentEncoding-boolean-) | Defines whether need check message body content encoding when saving. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at converting to MailMessage. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at converting to MailMessage. |
### EmlSaveOptions(MailMessageSaveType saveType) {#EmlSaveOptions-com.aspose.email.MailMessageSaveType-}
```
public EmlSaveOptions(MailMessageSaveType saveType)
```


Initializes a new instance of this class that can be used to save a MailMessage in the Eml and Emlx format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveType | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### getFileCompatibilityMode() {#getFileCompatibilityMode--}
```
public final int getFileCompatibilityMode()
```


Defines inner conversions,that are necessarily to be done when saving a message. The default value is FileCompatibilityMode.None.

**Returns:**
int
### setFileCompatibilityMode(int value) {#setFileCompatibilityMode-int-}
```
public final void setFileCompatibilityMode(int value)
```


Defines inner conversions,that are necessarily to be done when saving a message. The default value is FileCompatibilityMode.None.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPreserveSignedContent() {#getPreserveSignedContent--}
```
public final boolean getPreserveSignedContent()
```


Gets or sets a value indicating whether it is necessary to save signed message without changes of content to provide correctly structure of digital sign.

**Returns:**
boolean
### setPreserveSignedContent(boolean value) {#setPreserveSignedContent-boolean-}
```
public final void setPreserveSignedContent(boolean value)
```


Gets or sets a value indicating whether it is necessary to save signed message without changes of content to provide correctly structure of digital sign.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCheckBodyContentEncoding() {#getCheckBodyContentEncoding--}
```
public final boolean getCheckBodyContentEncoding()
```


Defines whether need check message body content encoding when saving.

**Returns:**
boolean
### setCheckBodyContentEncoding(boolean value) {#setCheckBodyContentEncoding-boolean-}
```
public final void setCheckBodyContentEncoding(boolean value)
```


Defines whether need check message body content encoding when saving.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Gets or sets a value indicating whether it is necessary to preserve format of embedded message at converting to MailMessage.

**Returns:**
boolean
### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


Gets or sets a value indicating whether it is necessary to preserve format of embedded message at converting to MailMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

