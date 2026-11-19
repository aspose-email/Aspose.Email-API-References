---
title: HtmlLoadOptions
second_title: Aspose.Email for Java API Reference
description: Provides options for controlling how  instances are loaded from HTML format.
type: docs
weight: 315
url: /java/com.aspose.email/htmlloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.LoadOptions](../../com.aspose.email/loadoptions)
```
public class HtmlLoadOptions extends LoadOptions
```

Provides options for controlling how [MailMessage](../../com.aspose.email/mailmessage) instances are loaded from HTML format. This class allows you to specify resource paths and control the generation of plain text views when converting HTML messages to MailMessage objects.

Use this class with [MailMessage.load(String, LoadOptions)](../../com.aspose.email/mailmessage\#load-String--LoadOptions-) to load HTML files and convert them to MailMessage objects. The \#getPathToResources().getPathToResources() property enables loading of external resources (images, CSS) referenced in the HTML, while \#shouldAddPlainTextView().shouldAddPlainTextView() controls whether to automatically generate a plain text alternate view.

The following example shows how to load an HTML file and preserve external resources.

```

 // Create HTML load options with path to resources
 HtmlLoadOptions loadOptions = new HtmlLoadOptions();
 loadOptions.setPathToResources("C:\\resources\\");
 loadOptions.shouldAddPlainTextView(true);

 // Load HTML file
 try (MailMessage message = MailMessage.load("sample.html", loadOptions)) {
     // Convert to EML format
     message.save("output.eml", SaveOptions.getDefaultEml());
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlLoadOptions()](#HtmlLoadOptions--) | Initializes a new instance of the [HtmlLoadOptions](../../com.aspose.email/htmlloadoptions) class with the default options. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMessageFormat()](#getMessageFormat--) | Gets the format this options object loads, as determined by its class: EML, MSG, MHTML, HTML and so on. |
| [getPathToResources()](#getPathToResources--) | Gets the folder that relative paths of images and other resources in the HTML are resolved against. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets the encoding used for the subject and the body regardless of what the message declares. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. |
| [getRemoveSignature()](#getRemoveSignature--) | Gets a value indicating whether the digital signature is removed from a signed message while it is loaded. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPathToResources(String value)](#setPathToResources-java.lang.String-) | Sets the folder that relative paths of images and other resources in the HTML are resolved against. |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Sets the encoding used for the subject and the body regardless of what the message declares. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Sets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. |
| [setRemoveSignature(boolean value)](#setRemoveSignature-boolean-) | Sets a value indicating whether the digital signature is removed from a signed message while it is loaded. |
| [shouldAddPlainTextView()](#shouldAddPlainTextView--) | Gets a value indicating whether a plain-text version of the body is added to the message. |
| [shouldAddPlainTextView(boolean value)](#shouldAddPlainTextView-boolean-) | Sets a value indicating whether a plain-text version of the body is added to the message. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlLoadOptions() {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```


Initializes a new instance of the [HtmlLoadOptions](../../com.aspose.email/htmlloadoptions) class with the default options.

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
### getPathToResources() {#getPathToResources--}
```
public final String getPathToResources()
```


Gets the folder that relative paths of images and other resources in the HTML are resolved against.

**Returns:**
java.lang.String
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




### setPathToResources(String value) {#setPathToResources-java.lang.String-}
```
public final void setPathToResources(String value)
```


Sets the folder that relative paths of images and other resources in the HTML are resolved against.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

### shouldAddPlainTextView() {#shouldAddPlainTextView--}
```
public final boolean shouldAddPlainTextView()
```


Gets a value indicating whether a plain-text version of the body is added to the message. The default is  false .

**Returns:**
boolean
### shouldAddPlainTextView(boolean value) {#shouldAddPlainTextView-boolean-}
```
public final void shouldAddPlainTextView(boolean value)
```


Sets a value indicating whether a plain-text version of the body is added to the message. The default is  false .

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

