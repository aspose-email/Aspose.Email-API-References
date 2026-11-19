---
title: MsgLoadOptions
second_title: Aspose.Email for Java API Reference
description: Provides options for controlling how  instances are loaded from MSG format.
type: docs
weight: 553
url: /java/com.aspose.email/msgloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.LoadOptions](../../com.aspose.email/loadoptions)
```
public class MsgLoadOptions extends LoadOptions
```

Provides options for controlling how [MailMessage](../../com.aspose.email/mailmessage) instances are loaded from MSG format. This class allows you to customize the loading behavior for Outlook MSG files, including TNEF attachment handling, RTF body preservation, email address preservation, and timeout configuration.

Use this class with [MailMessage.load(String, LoadOptions)](../../com.aspose.email/mailmessage\#load-String--LoadOptions-) to load Outlook MSG files and control various loading options. MSG is the native format for Outlook messages and can contain various Outlook-specific features. The \#getPreserveTnefAttachments().getPreserveTnefAttachments() property controls TNEF handling, \#getPreserveRtfContent().getPreserveRtfContent() preserves RTF body formatting, and \#getTimeout().getTimeout() limits the conversion time.

The following example shows how to use MsgLoadOptions to load an Outlook MSG file with custom settings.

```

 // Create MSG load options with custom settings
 MsgLoadOptions loadOptions = new MsgLoadOptions();
 loadOptions.setPreserveTnefAttachments(true);
 loadOptions.setPreserveRtfContent(true);
 loadOptions.setKeepOriginalEmailAddresses(true);
 loadOptions.setTimeout(5000);

 // Handle timeout event
 loadOptions.setTimeoutReachedHandler(new TimeoutReachedHandler() {
     public void invoke(Object sender, EventArgs e) {
         System.out.println("Message loading timed out");
     }
 });

 // Load MSG file with custom options
 try (MailMessage message = MailMessage.load("message.msg", loadOptions)) {
     // Convert to EML format
     message.save("output.eml", SaveOptions.getDefaultEml());
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MsgLoadOptions()](#MsgLoadOptions--) | Initializes a new instance of the [MsgLoadOptions](../../com.aspose.email/msgloadoptions) class with the default options. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeferAttachmentContent()](#getDeferAttachmentContent--) | Gets a value indicating whether attachment content is read on demand instead of being loaded into memory while the message is being loaded. |
| [getDeferralThreshold()](#getDeferralThreshold--) | Gets the size, in bytes, from which \#getDeferAttachmentContent().getDeferAttachmentContent() applies; smaller attachments are always loaded at once. |
| [getKeepOriginalEmailAddresses()](#getKeepOriginalEmailAddresses--) | Gets a value indicating whether the sender and recipient addresses are taken from the transport headers of the message as they are. |
| [getLeaveOpen()](#getLeaveOpen--) | Gets or sets a value indicating whether to keep the underlying stream open after load. |
| [getMessageFormat()](#getMessageFormat--) | Gets the format this options object loads, as determined by its class: EML, MSG, MHTML, HTML and so on. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets the encoding used for the subject and the body regardless of what the message declares. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. |
| [getPreserveRtfContent()](#getPreserveRtfContent--) | Gets a value indicating whether the RTF body of the MSG file is kept in the loaded message. |
| [getPreserveTnefAttachments()](#getPreserveTnefAttachments--) | Gets a value indicating whether a TNEF attachment (winmail.dat) is kept as it is instead of being decoded into its files. |
| [getRemoveSignature()](#getRemoveSignature--) | Gets a value indicating whether the digital signature is removed from a signed message while it is loaded. |
| [getTimeout()](#getTimeout--) | Gets the time limit, in milliseconds, for formatting the body during the conversion. |
| [getTimeoutReachedHandler()](#getTimeoutReachedHandler--) | Gets the handler of the event that occurs when formatting the body takes longer than \#getTimeout().getTimeout(). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDeferAttachmentContent(boolean value)](#setDeferAttachmentContent-boolean-) | Sets a value indicating whether attachment content is read on demand instead of being loaded into memory while the message is being loaded. |
| [setDeferralThreshold(int value)](#setDeferralThreshold-int-) | Sets the size, in bytes, from which \#getDeferAttachmentContent().getDeferAttachmentContent() applies; smaller attachments are always loaded at once. |
| [setKeepOriginalEmailAddresses(boolean value)](#setKeepOriginalEmailAddresses-boolean-) | Sets a value indicating whether the sender and recipient addresses are taken from the transport headers of the message as they are. |
| [setLeaveOpen(boolean value)](#setLeaveOpen-boolean-) | Gets or sets a value indicating whether to keep the underlying stream open after load. |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Sets the encoding used for the subject and the body regardless of what the message declares. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Sets a value indicating whether embedded messages keep their original format (EML or MSG) when loaded. |
| [setPreserveRtfContent(boolean value)](#setPreserveRtfContent-boolean-) | Sets a value indicating whether the RTF body of the MSG file is kept in the loaded message. |
| [setPreserveTnefAttachments(boolean value)](#setPreserveTnefAttachments-boolean-) | Sets a value indicating whether a TNEF attachment (winmail.dat) is kept as it is instead of being decoded into its files. |
| [setRemoveSignature(boolean value)](#setRemoveSignature-boolean-) | Sets a value indicating whether the digital signature is removed from a signed message while it is loaded. |
| [setTimeout(int value)](#setTimeout-int-) | Sets the time limit, in milliseconds, for formatting the body during the conversion. |
| [setTimeoutReachedHandler(TimeoutReachedHandler value)](#setTimeoutReachedHandler-com.aspose.email.TimeoutReachedHandler-) | Raised if timed out while saving. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MsgLoadOptions() {#MsgLoadOptions--}
```
public MsgLoadOptions()
```


Initializes a new instance of the [MsgLoadOptions](../../com.aspose.email/msgloadoptions) class with the default options.

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
### getDeferAttachmentContent() {#getDeferAttachmentContent--}
```
public final boolean getDeferAttachmentContent()
```


Gets a value indicating whether attachment content is read on demand instead of being loaded into memory while the message is being loaded. The default value is  false .

This makes the memory needed to load a message independent of the size of its attachments, which matters for messages with large attachments.

The source must stay readable until the message is disposed. For the file based overloads of [MapiMessage.load(String, LoadOptions)](../../com.aspose.email/mapimessage\#load-String--LoadOptions-) the library keeps the file open and closes it in  close() , so the message must be disposed. For the stream based overloads the caller keeps the stream open. Reading attachment content after the source has been closed throws.

Saving the message back over the file it was loaded from is still supported: the content is materialised first, because the source cannot be read and overwritten at once.

**Returns:**
boolean
### getDeferralThreshold() {#getDeferralThreshold--}
```
public final int getDeferralThreshold()
```


Gets the size, in bytes, from which \#getDeferAttachmentContent().getDeferAttachmentContent() applies; smaller attachments are always loaded at once. The default is 4096.

**Returns:**
int
### getKeepOriginalEmailAddresses() {#getKeepOriginalEmailAddresses--}
```
public final boolean getKeepOriginalEmailAddresses()
```


Gets a value indicating whether the sender and recipient addresses are taken from the transport headers of the message as they are. When  false  (the default), they are rebuilt from the MAPI properties of the message.

**Returns:**
boolean
### getLeaveOpen() {#getLeaveOpen--}
```
public final boolean getLeaveOpen()
```


Gets or sets a value indicating whether to keep the underlying stream open after load. Default value is false.

**Returns:**
boolean
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
### getPreserveRtfContent() {#getPreserveRtfContent--}
```
public final boolean getPreserveRtfContent()
```


Gets a value indicating whether the RTF body of the MSG file is kept in the loaded message. The default is  false .

**Returns:**
boolean
### getPreserveTnefAttachments() {#getPreserveTnefAttachments--}
```
public final boolean getPreserveTnefAttachments()
```


Gets a value indicating whether a TNEF attachment (winmail.dat) is kept as it is instead of being decoded into its files. The default is  false .

If a message contains a TNEF attachment (winmail.dat), then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is  true .

**Returns:**
boolean
### getRemoveSignature() {#getRemoveSignature--}
```
public final boolean getRemoveSignature()
```


Gets a value indicating whether the digital signature is removed from a signed message while it is loaded.

**Returns:**
boolean -  true  to remove the signature; otherwise,  false . The default is  false .
### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Gets the time limit, in milliseconds, for formatting the body during the conversion. The default is 3000 (3 seconds).

**Returns:**
int
### getTimeoutReachedHandler() {#getTimeoutReachedHandler--}
```
public final TimeoutReachedHandler getTimeoutReachedHandler()
```


Gets the handler of the event that occurs when formatting the body takes longer than \#getTimeout().getTimeout().

**Returns:**
[TimeoutReachedHandler](../../com.aspose.email/timeoutreachedhandler)
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




### setDeferAttachmentContent(boolean value) {#setDeferAttachmentContent-boolean-}
```
public final void setDeferAttachmentContent(boolean value)
```


Sets a value indicating whether attachment content is read on demand instead of being loaded into memory while the message is being loaded. The default value is  false .

This makes the memory needed to load a message independent of the size of its attachments, which matters for messages with large attachments.

The source must stay readable until the message is disposed. For the file based overloads of [MapiMessage.load(String, LoadOptions)](../../com.aspose.email/mapimessage\#load-String--LoadOptions-) the library keeps the file open and closes it in  close() , so the message must be disposed. For the stream based overloads the caller keeps the stream open. Reading attachment content after the source has been closed throws.

Saving the message back over the file it was loaded from is still supported: the content is materialised first, because the source cannot be read and overwritten at once.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDeferralThreshold(int value) {#setDeferralThreshold-int-}
```
public final void setDeferralThreshold(int value)
```


Sets the size, in bytes, from which \#getDeferAttachmentContent().getDeferAttachmentContent() applies; smaller attachments are always loaded at once. The default is 4096.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setKeepOriginalEmailAddresses(boolean value) {#setKeepOriginalEmailAddresses-boolean-}
```
public final void setKeepOriginalEmailAddresses(boolean value)
```


Sets a value indicating whether the sender and recipient addresses are taken from the transport headers of the message as they are. When  false  (the default), they are rebuilt from the MAPI properties of the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setLeaveOpen(boolean value) {#setLeaveOpen-boolean-}
```
public final void setLeaveOpen(boolean value)
```


Gets or sets a value indicating whether to keep the underlying stream open after load. Default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### setPreserveRtfContent(boolean value) {#setPreserveRtfContent-boolean-}
```
public final void setPreserveRtfContent(boolean value)
```


Sets a value indicating whether the RTF body of the MSG file is kept in the loaded message. The default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveTnefAttachments(boolean value) {#setPreserveTnefAttachments-boolean-}
```
public final void setPreserveTnefAttachments(boolean value)
```


Sets a value indicating whether a TNEF attachment (winmail.dat) is kept as it is instead of being decoded into its files. The default is  false .

If a message contains a TNEF attachment (winmail.dat), then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is  true .

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

### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


Sets the time limit, in milliseconds, for formatting the body during the conversion. The default is 3000 (3 seconds).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTimeoutReachedHandler(TimeoutReachedHandler value) {#setTimeoutReachedHandler-com.aspose.email.TimeoutReachedHandler-}
```
public final void setTimeoutReachedHandler(TimeoutReachedHandler value)
```


Raised if timed out while saving.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeoutReachedHandler](../../com.aspose.email/timeoutreachedhandler) |  |

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

