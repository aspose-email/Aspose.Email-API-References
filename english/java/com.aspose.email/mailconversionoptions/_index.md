---
title: MailConversionOptions
second_title: Aspose.Email for Java API Reference
description: Specify additional options when converting from MapiMessage to MailMessage.
type: docs
weight: 366
url: /java/com.aspose.email/mailconversionoptions/
---

**Inheritance:**
java.lang.Object
```
public class MailConversionOptions
```

Specify additional options when converting from MapiMessage to MailMessage.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailConversionOptions()](#MailConversionOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
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

