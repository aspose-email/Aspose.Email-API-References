---
title: MailConversionOptions
second_title: Aspose.Email for Java API Reference
description: Provides options for controlling how  instances are converted to  objects.
type: docs
weight: 387
url: /java/com.aspose.email/mailconversionoptions/
---

**Inheritance:**
java.lang.Object
```
public class MailConversionOptions
```

Provides options for controlling how [MapiMessage](../../com.aspose.email/mapimessage) instances are converted to [MailMessage](../../com.aspose.email/mailmessage) objects. This class allows you to customize the conversion behavior for TNEF handling, embedded message format preservation, RTF content, and email address management.

Use this class with [MapiMessage.toMailMessage(MailConversionOptions)](../../com.aspose.email/mapimessage\#toMailMessage-MailConversionOptions-) to specify custom conversion options. The \#setConvertAsTnef(boolean).setConvertAsTnef(boolean) property enables TNEF attachment preservation, \#setPreserveEmbeddedMessageFormat(boolean).setPreserveEmbeddedMessageFormat(boolean) maintains original embedded message formats, \#setPreserveRtfContent(boolean).setPreserveRtfContent(boolean) retains RTF body formatting, and \#setTimeout(int).setTimeout(int) controls the conversion time limit.

The following example shows how to use MailConversionOptions to convert a MapiMessage to MailMessage with custom settings.

```

 // Load a MapiMessage from file
 MapiMessage mapiMessage = MapiMessage.load("message.msg");

 // Create conversion options with custom settings
 MailConversionOptions conversionOptions = new MailConversionOptions();
 conversionOptions.setConvertAsTnef(true);
 conversionOptions.setPreserveEmbeddedMessageFormat(true);
 conversionOptions.setPreserveRtfContent(true);
 conversionOptions.setKeepOriginalEmailAddresses(true);
 conversionOptions.setTimeout(5000);

 // Handle timeout event
 conversionOptions.setTimeoutReachedHandler(new TimeoutReachedHandler() {
     public void invoke(Object sender, EventArgs e) {
         System.out.println("Conversion timed out");
     }
 });

 // Convert MapiMessage to MailMessage with custom options
 MailMessage mailMessage = mapiMessage.toMailMessage(conversionOptions);

 // Save as EML
 mailMessage.save("output.eml", SaveOptions.getDefaultEml());
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MailConversionOptions()](#MailConversionOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachmentCidTemplate()](#getAttachmentCidTemplate--) | Defines the template for generating MIME Content-ID (CID) values for attachments embedded into the message body. |
| [getClass()](#getClass--) |  |
| [getConvertAsTnef()](#getConvertAsTnef--) | Set to true to import the MapiMessage information into a MailMessage object with MapiMessage as TNEF attachment. |
| [getKeepOriginalEmailAddresses()](#getKeepOriginalEmailAddresses--) | Gets or sets a value indicating whether need keep original email address. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets or sets a value indicating whether it is necessary to preserve MSG format of embedded message at converting to MailMessage. |
| [getPreserveRtfContent()](#getPreserveRtfContent--) | Gets or sets a value indicating whether need keep rtf body in MailMessage. |
| [getTimeout()](#getTimeout--) | Limits the time in milliseconds of formatting message while converting. |
| [getTimeoutReachedHandler()](#getTimeoutReachedHandler--) | Raised if timed out while saving to MailMessage. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttachmentCidTemplate(String value)](#setAttachmentCidTemplate-java.lang.String-) | Defines the template for generating MIME Content-ID (CID) values for attachments embedded into the message body. |
| [setConvertAsTnef(boolean value)](#setConvertAsTnef-boolean-) | Set to true to import the MapiMessage information into a MailMessage object with MapiMessage as TNEF attachment. |
| [setKeepOriginalEmailAddresses(boolean value)](#setKeepOriginalEmailAddresses-boolean-) | Gets or sets a value indicating whether need keep original email address. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Gets or sets a value indicating whether it is necessary to preserve MSG format of embedded message at converting to MailMessage. |
| [setPreserveRtfContent(boolean value)](#setPreserveRtfContent-boolean-) | Gets or sets a value indicating whether need keep rtf body in MailMessage. |
| [setTimeout(int value)](#setTimeout-int-) | Limits the time in milliseconds of formatting message while converting. |
| [setTimeoutReachedHandler(TimeoutReachedHandler value)](#setTimeoutReachedHandler-com.aspose.email.TimeoutReachedHandler-) | Raised if timed out while saving to MailMessage. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailConversionOptions() {#MailConversionOptions--}
```
public MailConversionOptions()
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
### getAttachmentCidTemplate() {#getAttachmentCidTemplate--}
```
public final String getAttachmentCidTemplate()
```


Defines the template for generating MIME Content-ID (CID) values for attachments embedded into the message body.

The template may contain the "\{\#\}" placeholder, which will be substituted with the sequential attachment number.

Example:  "cid-\{\#\}"  ->  cid-1 ,  cid-2 , ... If  null  or empty, a default CID generation strategy is applied.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConvertAsTnef() {#getConvertAsTnef--}
```
public final boolean getConvertAsTnef()
```


Set to true to import the MapiMessage information into a MailMessage object with MapiMessage as TNEF attachment.

**Returns:**
boolean
### getKeepOriginalEmailAddresses() {#getKeepOriginalEmailAddresses--}
```
public final boolean getKeepOriginalEmailAddresses()
```


Gets or sets a value indicating whether need keep original email address.

**Returns:**
boolean
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Gets or sets a value indicating whether it is necessary to preserve MSG format of embedded message at converting to MailMessage. By default the value is false.

--------------------

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from MSG to EML and vice versa, embedded messages are also converted to the target format. Setting the property to true preserves the original format of the embedded messages.

**Returns:**
boolean
### getPreserveRtfContent() {#getPreserveRtfContent--}
```
public final boolean getPreserveRtfContent()
```


Gets or sets a value indicating whether need keep rtf body in MailMessage.

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


Raised if timed out while saving to MailMessage.

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




### setAttachmentCidTemplate(String value) {#setAttachmentCidTemplate-java.lang.String-}
```
public final void setAttachmentCidTemplate(String value)
```


Defines the template for generating MIME Content-ID (CID) values for attachments embedded into the message body.

The template may contain the "\{\#\}" placeholder, which will be substituted with the sequential attachment number.

Example:  "cid-\{\#\}"  ->  cid-1 ,  cid-2 , ... If  null  or empty, a default CID generation strategy is applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setConvertAsTnef(boolean value) {#setConvertAsTnef-boolean-}
```
public final void setConvertAsTnef(boolean value)
```


Set to true to import the MapiMessage information into a MailMessage object with MapiMessage as TNEF attachment.

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

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


Gets or sets a value indicating whether it is necessary to preserve MSG format of embedded message at converting to MailMessage. By default the value is false.

--------------------

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from MSG to EML and vice versa, embedded messages are also converted to the target format. Setting the property to true preserves the original format of the embedded messages.

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


Raised if timed out while saving to MailMessage.

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

