---
title: EmlLoadOptions
second_title: Aspose.Email for Java API Reference
description: Provides options for controlling how  instances are loaded from EML format.
type: docs
weight: 175
url: /java/com.aspose.email/emlloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.LoadOptions](../../com.aspose.email/loadoptions)
```
public class EmlLoadOptions extends LoadOptions
```

Provides options for controlling how [MailMessage](../../com.aspose.email/mailmessage) instances are loaded from EML format. This class allows you to customize the loading behavior for specific EML features such as TNEF attachment handling and embedded message preservation.

Use this class with [MailMessage.load(String, LoadOptions)](../../com.aspose.email/mailmessage\#load-String--LoadOptions-) to specify custom loading options. Inherits from [LoadOptions](../../com.aspose.email/loadoptions) and adds EML-specific configuration through properties like \#getPreserveTnefAttachments().getPreserveTnefAttachments().

The following example shows how to convert EML to MSG.

```

 // Initialize EmlLoadOptions
 EmlLoadOptions emlLoadOptions = new EmlLoadOptions();
 emlLoadOptions.setPreserveTnefAttachments(true);
 emlLoadOptions.setPreserveEmbeddedMessageFormat(true);

 // Initialize MailMessage with EmlLoadOptions
 try (MailMessage message = MailMessage.load("TestEml.eml", emlLoadOptions)) {
     // Convert EML to MSG
     message.save("output.msg", SaveOptions.getDefaultMsg());
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmlLoadOptions()](#EmlLoadOptions--) | Initializes a new instance of the [EmlLoadOptions](../../com.aspose.email/emlloadoptions) class with the default options. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMessageFormat()](#getMessageFormat--) | Gets the format this options object loads, as determined by its class: EML, MSG, MHTML, HTML and so on. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets the encoding used for the subject and the body regardless of what the message declares. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. |
| [getPreserveTnefAttachments()](#getPreserveTnefAttachments--) | Gets a value indicating whether a TNEF attachment (winmail.dat) is kept as it is instead of being decoded into its files. |
| [getRemoveSignature()](#getRemoveSignature--) | Gets a value indicating whether the digital signature is removed from a signed message while it is loaded. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Sets the encoding used for the subject and the body regardless of what the message declares. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Sets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. |
| [setPreserveTnefAttachments(boolean value)](#setPreserveTnefAttachments-boolean-) | Sets a value indicating whether a TNEF attachment (winmail.dat) is kept as it is instead of being decoded into its files. |
| [setRemoveSignature(boolean value)](#setRemoveSignature-boolean-) | Sets a value indicating whether the digital signature is removed from a signed message while it is loaded. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmlLoadOptions() {#EmlLoadOptions--}
```
public EmlLoadOptions()
```


Initializes a new instance of the [EmlLoadOptions](../../com.aspose.email/emlloadoptions) class with the default options.

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
### getPreserveTnefAttachments() {#getPreserveTnefAttachments--}
```
public final boolean getPreserveTnefAttachments()
```


Gets a value indicating whether a TNEF attachment (winmail.dat) is kept as it is instead of being decoded into its files. The default is  false .

Applies to an attachment with the MIME type  application/ms-tnef . When  false , the files and the body the TNEF attachment carries are extracted into the message.

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

### setPreserveTnefAttachments(boolean value) {#setPreserveTnefAttachments-boolean-}
```
public final void setPreserveTnefAttachments(boolean value)
```


Sets a value indicating whether a TNEF attachment (winmail.dat) is kept as it is instead of being decoded into its files. The default is  false .

Applies to an attachment with the MIME type  application/ms-tnef . When  false , the files and the body the TNEF attachment carries are extracted into the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to keep the TNEF attachment as it is. |

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

