---
title: LoadOptions
second_title: Aspose.Email for Java API Reference
description: Serves as the abstract base class for format-specific options when loading  from various email formats EML EMLX HTML MHTML etc..
type: docs
weight: 374
url: /java/com.aspose.email/loadoptions/
---

**Inheritance:**
java.lang.Object
```
public abstract class LoadOptions
```

Serves as the abstract base class for format-specific options when loading [MailMessage](../../com.aspose.email/mailmessage) from various email formats (EML, EMLX, HTML, MHTML, etc.). This class provides common configuration properties such as text encoding, embedded message format preservation, and signature handling.

This class is designed to be inherited by concrete format-specific classes like [EmlLoadOptions](../../com.aspose.email/emlloadoptions), [EmlxLoadOptions](../../com.aspose.email/emlxloadoptions), and [HtmlLoadOptions](../../com.aspose.email/htmlloadoptions). Do not instantiate this class directly. Use the format-specific subclasses to access format-specific loading options.
## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMessageFormat()](#getMessageFormat--) | Gets the format this options object loads, as determined by its class: EML, MSG, MHTML, HTML and so on. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets the encoding used for the subject and the body regardless of what the message declares. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. |
| [getRemoveSignature()](#getRemoveSignature--) | Gets a value indicating whether the digital signature is removed from a signed message while it is loaded. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Sets the encoding used for the subject and the body regardless of what the message declares. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Sets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. |
| [setRemoveSignature(boolean value)](#setRemoveSignature-boolean-) | Sets a value indicating whether the digital signature is removed from a signed message while it is loaded. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


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
### getMessageFormat() {#getMessageFormat--}
```
public final MessageFormat getMessageFormat()
```


Gets the format this options object loads, as determined by its class: EML, MSG, MHTML, HTML and so on.

**Returns:**
[MessageFormat](../../com.aspose.email/messageformat)
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


Gets the encoding used for the subject and the body regardless of what the message declares. The default is  null : the declared encoding is used.

**Returns:**
java.nio.charset.Charset
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Gets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. The default is  false .

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from EML to MSG and vice versa, embedded messages are also converted to the target format. Setting the property to  true  preserves the original format of embedded messages.

**Returns:**
boolean
### getRemoveSignature() {#getRemoveSignature--}
```
public final boolean getRemoveSignature()
```


Gets a value indicating whether the digital signature is removed from a signed message while it is loaded.

**Returns:**
boolean -  true  to remove the signature; otherwise,  false . The default is  false .
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




### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


Sets the encoding used for the subject and the body regardless of what the message declares. The default is  null : the declared encoding is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


Sets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. The default is  false .

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from EML to MSG and vice versa, embedded messages are also converted to the target format. Setting the property to  true  preserves the original format of embedded messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRemoveSignature(boolean value) {#setRemoveSignature-boolean-}
```
public final void setRemoveSignature(boolean value)
```


Sets a value indicating whether the digital signature is removed from a signed message while it is loaded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to remove the signature; otherwise,  false . The default is  false . |

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

