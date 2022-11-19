---
title: EmlLoadOptions
second_title: Aspose.Email for Java API Reference
description: Allows to specify additional options when loading MailMessage from Eml format.
type: docs
weight: 170
url: /java/com.aspose.email/emlloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.LoadOptions](../../com.aspose.email/loadoptions)
```
public class EmlLoadOptions extends LoadOptions
```

Allows to specify additional options when loading MailMessage from Eml format.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmlLoadOptions()](#EmlLoadOptions--) | Initializes a new instance of this class that can be used to loading MailMessage from Eml format. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMessageFormat()](#getMessageFormat--) | Represents the mail message format.It can be in eml,msg or mhtml format. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets or sets preferred encoding for message. |
| [getPrefferedTextEncoding()](#getPrefferedTextEncoding--) | Gets or sets preferred encoding for message. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. |
| [getPreserveTnefAttachments()](#getPreserveTnefAttachments--) | Controls TNEF attachment loading behaviour. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Gets or sets preferred encoding for message. |
| [setPrefferedTextEncoding(Charset value)](#setPrefferedTextEncoding-java.nio.charset.Charset-) | Gets or sets preferred encoding for message. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. |
| [setPreserveTnefAttachments(boolean value)](#setPreserveTnefAttachments-boolean-) | Controls TNEF attachment loading behaviour. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmlLoadOptions() {#EmlLoadOptions--}
```
public EmlLoadOptions()
```


Initializes a new instance of this class that can be used to loading MailMessage from Eml format.

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
### getPreserveTnefAttachments() {#getPreserveTnefAttachments--}
```
public final boolean getPreserveTnefAttachments()
```


Controls TNEF attachment loading behaviour. By default the value is false.

--------------------

If a message contains a TNEF attachment (winmail.dat) and has the MIME type application/ms-tnef, then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is true.

**Returns:**
boolean
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

### setPreserveTnefAttachments(boolean value) {#setPreserveTnefAttachments-boolean-}
```
public final void setPreserveTnefAttachments(boolean value)
```


Controls TNEF attachment loading behaviour. By default the value is false.

--------------------

If a message contains a TNEF attachment (winmail.dat) and has the MIME type application/ms-tnef, then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

