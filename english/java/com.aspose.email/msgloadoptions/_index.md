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

Use this class with [MailMessage.load(String, LoadOptions)](../../com.aspose.email/mailmessage\#load-String--LoadOptions-) to load Outlook MSG files and control various loading options. MSG is the native format for Outlook messages and can contain various Outlook-specific features. The \#setPreserveTnefAttachments(boolean).setPreserveTnefAttachments(boolean) property controls TNEF handling, \#setPreserveRtfContent(boolean).setPreserveRtfContent(boolean) preserves RTF body formatting, and \#setTimeout(int).setTimeout(int) limits the conversion time.

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
| [MsgLoadOptions()](#MsgLoadOptions--) | Initializes a new instance of this class that can be used to loading MailMessage from Msg format. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeferAttachmentContent()](#getDeferAttachmentContent--) | Gets or sets a value indicating whether attachment content is read on demand instead of being loaded into memory while the message is being loaded. |
| [getDeferralThreshold()](#getDeferralThreshold--) | Gets or sets the minimum content size, in bytes, for which  DeferAttachmentContent (\#getDeferAttachmentContent.getDeferAttachmentContent/\#setDeferAttachmentContent(boolean).setDeferAttachmentContent(boolean)) applies. |
| [getKeepOriginalEmailAddresses()](#getKeepOriginalEmailAddresses--) | Gets or sets a value indicating whether need keep original email address. |
| [getLeaveOpen()](#getLeaveOpen--) | Gets or sets a value indicating whether to keep the underlying stream open after load. |
| [getMessageFormat()](#getMessageFormat--) | Represents the mail message format.It can be in eml,msg or mhtml format. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets or sets preferred encoding for message. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. |
| [getPreserveRtfContent()](#getPreserveRtfContent--) | Gets or sets a value indicating whether need keep rtf body in MailMessage. |
| [getPreserveTnefAttachments()](#getPreserveTnefAttachments--) | Controls loading TNEF attachment behaviour. |
| [getRemoveSignature()](#getRemoveSignature--) | Gets or sets a value indicating whether signature will be removed while loading. |
| [getTimeout()](#getTimeout--) | Limits the time in milliseconds of formatting message while converting. |
| [getTimeoutReachedHandler()](#getTimeoutReachedHandler--) | Raised if timed out while saving. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDeferAttachmentContent(boolean value)](#setDeferAttachmentContent-boolean-) | Gets or sets a value indicating whether attachment content is read on demand instead of being loaded into memory while the message is being loaded. |
| [setDeferralThreshold(int value)](#setDeferralThreshold-int-) | Gets or sets the minimum content size, in bytes, for which  DeferAttachmentContent (\#getDeferAttachmentContent.getDeferAttachmentContent/\#setDeferAttachmentContent(boolean).setDeferAttachmentContent(boolean)) applies. |
| [setKeepOriginalEmailAddresses(boolean value)](#setKeepOriginalEmailAddresses-boolean-) | Gets or sets a value indicating whether need keep original email address. |
| [setLeaveOpen(boolean value)](#setLeaveOpen-boolean-) | Gets or sets a value indicating whether to keep the underlying stream open after load. |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Gets or sets preferred encoding for message. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Gets or sets a value indicating whether it is necessary to preserve format of embedded message at loading. |
| [setPreserveRtfContent(boolean value)](#setPreserveRtfContent-boolean-) | Gets or sets a value indicating whether need keep rtf body in MailMessage. |
| [setPreserveTnefAttachments(boolean value)](#setPreserveTnefAttachments-boolean-) | Controls loading TNEF attachment behaviour. |
| [setRemoveSignature(boolean value)](#setRemoveSignature-boolean-) | Gets or sets a value indicating whether signature will be removed while loading. |
| [setTimeout(int value)](#setTimeout-int-) | Limits the time in milliseconds of formatting message while converting. |
| [setTimeoutReachedHandler(TimeoutReachedHandler value)](#setTimeoutReachedHandler-com.aspose.email.TimeoutReachedHandler-) | Raised if timed out while saving. |
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
### getDeferAttachmentContent() {#getDeferAttachmentContent--}
```
public final boolean getDeferAttachmentContent()
```


Gets or sets a value indicating whether attachment content is read on demand instead of being loaded into memory while the message is being loaded. The default value is false.

--------------------

This makes the memory needed to load a message independent of the size of its attachments, which matters for messages with large attachments.

The source must stay readable until the message is disposed. For the file based overloads of [MapiMessage.load(String,LoadOptions)](../../com.aspose.email/mapimessage\#load-String-LoadOptions-) the library keeps the file open and closes it in [IDisposable.dispose](../../com.aspose.email.services.ews.core/idisposable\#dispose), so the message must be disposed. For the stream based overloads the caller keeps the stream open. Reading attachment content after the source has been closed throws.

Saving the message back over the file it was loaded from is still supported: the content is materialised first, because the source cannot be read and overwritten at once.

**Returns:**
boolean
### getDeferralThreshold() {#getDeferralThreshold--}
```
public final int getDeferralThreshold()
```


Gets or sets the minimum content size, in bytes, for which  DeferAttachmentContent (\#getDeferAttachmentContent.getDeferAttachmentContent/\#setDeferAttachmentContent(boolean).setDeferAttachmentContent(boolean)) applies. Smaller attachments are always loaded eagerly. The default value is 4096.

**Returns:**
int
### getKeepOriginalEmailAddresses() {#getKeepOriginalEmailAddresses--}
```
public final boolean getKeepOriginalEmailAddresses()
```


Gets or sets a value indicating whether need keep original email address.

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
### getRemoveSignature() {#getRemoveSignature--}
```
public final boolean getRemoveSignature()
```


Gets or sets a value indicating whether signature will be removed while loading.

Value:  true  if will be removed; otherwise,  false .

**Returns:**
boolean
### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Limits the time in milliseconds of formatting message while converting. Default value 3 sec.

**Returns:**
int
### getTimeoutReachedHandler() {#getTimeoutReachedHandler--}
```
public final TimeoutReachedHandler getTimeoutReachedHandler()
```


Raised if timed out while saving.

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


Gets or sets a value indicating whether attachment content is read on demand instead of being loaded into memory while the message is being loaded. The default value is false.

--------------------

This makes the memory needed to load a message independent of the size of its attachments, which matters for messages with large attachments.

The source must stay readable until the message is disposed. For the file based overloads of [MapiMessage.load(String,LoadOptions)](../../com.aspose.email/mapimessage\#load-String-LoadOptions-) the library keeps the file open and closes it in [IDisposable.dispose](../../com.aspose.email.services.ews.core/idisposable\#dispose), so the message must be disposed. For the stream based overloads the caller keeps the stream open. Reading attachment content after the source has been closed throws.

Saving the message back over the file it was loaded from is still supported: the content is materialised first, because the source cannot be read and overwritten at once.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDeferralThreshold(int value) {#setDeferralThreshold-int-}
```
public final void setDeferralThreshold(int value)
```


Gets or sets the minimum content size, in bytes, for which  DeferAttachmentContent (\#getDeferAttachmentContent.getDeferAttachmentContent/\#setDeferAttachmentContent(boolean).setDeferAttachmentContent(boolean)) applies. Smaller attachments are always loaded eagerly. The default value is 4096.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setKeepOriginalEmailAddresses(boolean value) {#setKeepOriginalEmailAddresses-boolean-}
```
public final void setKeepOriginalEmailAddresses(boolean value)
```


Gets or sets a value indicating whether need keep original email address.

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

### setRemoveSignature(boolean value) {#setRemoveSignature-boolean-}
```
public final void setRemoveSignature(boolean value)
```


Gets or sets a value indicating whether signature will be removed while loading.

Value:  true  if will be removed; otherwise,  false .

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

