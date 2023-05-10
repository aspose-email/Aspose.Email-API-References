---
title: MsgLoadOptions
second_title: Aspose.Email for Java API Reference
description: Allows to specify additional options when loading MailMessage from Msg format.
type: docs
weight: 521
url: /java/com.aspose.email/msgloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.LoadOptions](../../com.aspose.email/loadoptions)
```
public class MsgLoadOptions extends LoadOptions
```

Allows to specify additional options when loading MailMessage from Msg format.
## Constructors

| Constructor | Description |
| --- | --- |
| [MsgLoadOptions()](#MsgLoadOptions--) | Initializes a new instance of this class that can be used to loading MailMessage from Msg format. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDecodeClearSignedContent()](#getDecodeClearSignedContent--) | Gets or sets a value indicating whether clear-signed message will be decoded. |
| [getDecodeSignedContent()](#getDecodeSignedContent--) | Gets or sets a value indicating whether signed message will be decoded. |
| [getKeepOriginalEmailAddresses()](#getKeepOriginalEmailAddresses--) | Gets or sets a value indicating whether need keep original email address. |
| [getMessageFormat()](#getMessageFormat--) | Represents the mail message format.It can be in eml,msg or mhtml format. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets or sets preferred encoding for message. |
| [getPrefferedTextEncoding()](#getPrefferedTextEncoding--) | Gets or sets preferred encoding for message. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. |
| [getPreserveRtfContent()](#getPreserveRtfContent--) | Gets or sets a value indicating whether need keep rtf body in MailMessage. |
| [getPreserveTnefAttachments()](#getPreserveTnefAttachments--) | Controls loading TNEF attachment behaviour. |
| [getTimeout()](#getTimeout--) | Limits the time in milliseconds of formatting message while converting. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDecodeClearSignedContent(boolean value)](#setDecodeClearSignedContent-boolean-) | Gets or sets a value indicating whether clear-signed message will be decoded. |
| [setDecodeSignedContent(boolean value)](#setDecodeSignedContent-boolean-) | Gets or sets a value indicating whether signed message will be decoded. |
| [setKeepOriginalEmailAddresses(boolean value)](#setKeepOriginalEmailAddresses-boolean-) | Gets or sets a value indicating whether need keep original email address. |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Gets or sets preferred encoding for message. |
| [setPrefferedTextEncoding(Charset value)](#setPrefferedTextEncoding-java.nio.charset.Charset-) | Gets or sets preferred encoding for message. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. |
| [setPreserveRtfContent(boolean value)](#setPreserveRtfContent-boolean-) | Gets or sets a value indicating whether need keep rtf body in MailMessage. |
| [setPreserveTnefAttachments(boolean value)](#setPreserveTnefAttachments-boolean-) | Controls loading TNEF attachment behaviour. |
| [setTimeout(int value)](#setTimeout-int-) | Limits the time in milliseconds of formatting message while converting. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MsgLoadOptions() {#MsgLoadOptions--}
```
public MsgLoadOptions()
```


Initializes a new instance of this class that can be used to loading MailMessage from Msg format.

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
### getDecodeClearSignedContent() {#getDecodeClearSignedContent--}
```
public final boolean getDecodeClearSignedContent()
```


Gets or sets a value indicating whether clear-signed message will be decoded.

Value:  true  if clear-signed message will be decoded; otherwise,  false .

**Returns:**
boolean
### getDecodeSignedContent() {#getDecodeSignedContent--}
```
public final boolean getDecodeSignedContent()
```


Gets or sets a value indicating whether signed message will be decoded.

Value:  true  if signed message will be decoded; otherwise,  false .

**Returns:**
boolean
### getKeepOriginalEmailAddresses() {#getKeepOriginalEmailAddresses--}
```
public final boolean getKeepOriginalEmailAddresses()
```


Gets or sets a value indicating whether need keep original email address.

**Returns:**
boolean
### getMessageFormat() {#getMessageFormat--}
```
public final MessageFormat getMessageFormat()
```


Represents the mail message format.It can be in eml,msg or mhtml format. The default value is Eml.

**Returns:**
[MessageFormat](../../com.aspose.email/messageformat)
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null.

**Returns:**
java.nio.charset.Charset
### getPrefferedTextEncoding() {#getPrefferedTextEncoding--}
```
public final Charset getPrefferedTextEncoding()
```


Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null.

**Returns:**
java.nio.charset.Charset
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. By default the value is false.

--------------------

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from EML to MSG and vice versa, embedded messages are also converted to the target format. Setting the property to true preserves the original format of embedded messages.

**Returns:**
boolean
### getPreserveRtfContent() {#getPreserveRtfContent--}
```
public final boolean getPreserveRtfContent()
```


Gets or sets a value indicating whether need keep rtf body in MailMessage.

**Returns:**
boolean
### getPreserveTnefAttachments() {#getPreserveTnefAttachments--}
```
public final boolean getPreserveTnefAttachments()
```


Controls loading TNEF attachment behaviour. By default the value is false.

--------------------

If a message contains a TNEF attachment (winmail.dat), then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is true.

**Returns:**
boolean
### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Limits the time in milliseconds of formatting message while converting. Default value 3 sec.

**Returns:**
int
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




### setDecodeClearSignedContent(boolean value) {#setDecodeClearSignedContent-boolean-}
```
public final void setDecodeClearSignedContent(boolean value)
```


Gets or sets a value indicating whether clear-signed message will be decoded.

Value:  true  if clear-signed message will be decoded; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDecodeSignedContent(boolean value) {#setDecodeSignedContent-boolean-}
```
public final void setDecodeSignedContent(boolean value)
```


Gets or sets a value indicating whether signed message will be decoded.

Value:  true  if signed message will be decoded; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setKeepOriginalEmailAddresses(boolean value) {#setKeepOriginalEmailAddresses-boolean-}
```
public final void setKeepOriginalEmailAddresses(boolean value)
```


Gets or sets a value indicating whether need keep original email address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPrefferedTextEncoding(Charset value) {#setPrefferedTextEncoding-java.nio.charset.Charset-}
```
public final void setPrefferedTextEncoding(Charset value)
```


Gets or sets preferred encoding for message. Forcibly sets the preferred encoding for message subject and body. The default value is null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. By default the value is false.

--------------------

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from EML to MSG and vice versa, embedded messages are also converted to the target format. Setting the property to true preserves the original format of embedded messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveRtfContent(boolean value) {#setPreserveRtfContent-boolean-}
```
public final void setPreserveRtfContent(boolean value)
```


Gets or sets a value indicating whether need keep rtf body in MailMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveTnefAttachments(boolean value) {#setPreserveTnefAttachments-boolean-}
```
public final void setPreserveTnefAttachments(boolean value)
```


Controls loading TNEF attachment behaviour. By default the value is false.

--------------------

If a message contains a TNEF attachment (winmail.dat), then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


Limits the time in milliseconds of formatting message while converting. Default value 3 sec.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

