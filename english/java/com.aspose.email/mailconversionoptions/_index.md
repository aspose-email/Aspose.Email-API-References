---
title: MailConversionOptions
second_title: Aspose.Email for Java API Reference
description: Options that control how a  is converted to a .
type: docs
weight: 387
url: /java/com.aspose.email/mailconversionoptions/
---

**Inheritance:**
java.lang.Object
```
public class MailConversionOptions
```

Options that control how a [MapiMessage](../../com.aspose.email/mapimessage) is converted to a [MailMessage](../../com.aspose.email/mailmessage).

Pass an instance to [MapiMessage.toMailMessage(MailConversionOptions)](../../com.aspose.email/mapimessage\#toMailMessage-MailConversionOptions-).

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
| [getConvertAsTnef()](#getConvertAsTnef--) | Gets a value indicating whether the MAPI message is carried as a TNEF (winmail.dat) attachment of the resulting MailMessage, so that Outlook-specific data is kept. |
| [getKeepOriginalEmailAddresses()](#getKeepOriginalEmailAddresses--) | Gets a value indicating whether the sender and recipient addresses are taken from the transport headers of the message as they are. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets a value indicating whether embedded messages stay in MSG format instead of being converted to EML. |
| [getPreserveRtfContent()](#getPreserveRtfContent--) | Gets a value indicating whether the RTF body of the message is kept in the MailMessage. |
| [getTimeout()](#getTimeout--) | Gets the time limit, in milliseconds, for formatting the message body during the conversion. |
| [getTimeoutReachedHandler()](#getTimeoutReachedHandler--) | Gets the handler of the event that occurs when formatting the message body takes longer than \#getTimeout().getTimeout(). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttachmentCidTemplate(String value)](#setAttachmentCidTemplate-java.lang.String-) | Defines the template for generating MIME Content-ID (CID) values for attachments embedded into the message body. |
| [setConvertAsTnef(boolean value)](#setConvertAsTnef-boolean-) | Sets a value indicating whether the MAPI message is carried as a TNEF (winmail.dat) attachment of the resulting MailMessage, so that Outlook-specific data is kept. |
| [setKeepOriginalEmailAddresses(boolean value)](#setKeepOriginalEmailAddresses-boolean-) | Sets a value indicating whether the sender and recipient addresses are taken from the transport headers of the message as they are. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Sets a value indicating whether embedded messages stay in MSG format instead of being converted to EML. |
| [setPreserveRtfContent(boolean value)](#setPreserveRtfContent-boolean-) | Sets a value indicating whether the RTF body of the message is kept in the MailMessage. |
| [setTimeout(int value)](#setTimeout-int-) | Sets the time limit, in milliseconds, for formatting the message body during the conversion. |
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


Gets a value indicating whether the MAPI message is carried as a TNEF (winmail.dat) attachment of the resulting MailMessage, so that Outlook-specific data is kept. The default is  false .

**Returns:**
boolean
### getKeepOriginalEmailAddresses() {#getKeepOriginalEmailAddresses--}
```
public final boolean getKeepOriginalEmailAddresses()
```


Gets a value indicating whether the sender and recipient addresses are taken from the transport headers of the message as they are. When  false  (the default), they are rebuilt from the MAPI properties of the message.

**Returns:**
boolean
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Gets a value indicating whether embedded messages stay in MSG format instead of being converted to EML. The default is  false .

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from MSG to EML and vice versa, embedded messages are also converted to the target format. Setting the property to  true  preserves the original format of the embedded messages.

**Returns:**
boolean
### getPreserveRtfContent() {#getPreserveRtfContent--}
```
public final boolean getPreserveRtfContent()
```


Gets a value indicating whether the RTF body of the message is kept in the MailMessage. The default is  false .

**Returns:**
boolean
### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Gets the time limit, in milliseconds, for formatting the message body during the conversion. The default is 3000 (3 seconds).

When the limit is reached, \#getTimeoutReachedHandler.getTimeoutReachedHandler is raised.

**Returns:**
int
### getTimeoutReachedHandler() {#getTimeoutReachedHandler--}
```
public final TimeoutReachedHandler getTimeoutReachedHandler()
```


Gets the handler of the event that occurs when formatting the message body takes longer than \#getTimeout().getTimeout().

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


Sets a value indicating whether the MAPI message is carried as a TNEF (winmail.dat) attachment of the resulting MailMessage, so that Outlook-specific data is kept. The default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setKeepOriginalEmailAddresses(boolean value) {#setKeepOriginalEmailAddresses-boolean-}
```
public final void setKeepOriginalEmailAddresses(boolean value)
```


Sets a value indicating whether the sender and recipient addresses are taken from the transport headers of the message as they are. When  false  (the default), they are rebuilt from the MAPI properties of the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


Sets a value indicating whether embedded messages stay in MSG format instead of being converted to EML. The default is  false .

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from MSG to EML and vice versa, embedded messages are also converted to the target format. Setting the property to  true  preserves the original format of the embedded messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveRtfContent(boolean value) {#setPreserveRtfContent-boolean-}
```
public final void setPreserveRtfContent(boolean value)
```


Sets a value indicating whether the RTF body of the message is kept in the MailMessage. The default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


Sets the time limit, in milliseconds, for formatting the message body during the conversion. The default is 3000 (3 seconds).

When the limit is reached, \#getTimeoutReachedHandler.getTimeoutReachedHandler is raised.

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

