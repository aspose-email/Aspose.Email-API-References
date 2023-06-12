---
title: MapiConversionOptions
second_title: Aspose.Email for Java API Reference
description: This class allows the user to specify additional options when converting from MailMessage to MapiMessage.
type: docs
weight: 434
url: /java/com.aspose.email/mapiconversionoptions/
---

**Inheritance:**
java.lang.Object
```
public class MapiConversionOptions
```

This class allows the user to specify additional options when converting from MailMessage to MapiMessage.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiConversionOptions()](#MapiConversionOptions--) | Initializes a new instance of the [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) class. |
| [MapiConversionOptions(int format)](#MapiConversionOptions-int-) | Initializes a new instance of the [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) class with specified OutlookMessageFormat. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getASCIIFormat()](#getASCIIFormat--) | Returns MapiConversionOptions with OutlookMessageFormat is ASCII(PreserveSignature is False, UseBodyCompression is False). |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) |  |
| [getForcedRtfBodyForAppointment()](#getForcedRtfBodyForAppointment--) | Gets or sets a value indicating whether it is necessary to use forced RTF body for an appointment. |
| [getFormat()](#getFormat--) | Represents outlook message format. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets or sets a value indicating whether it is necessary to preserve EML format of embedded message at converting to MapiMessage. |
| [getPreserveEmptyDates()](#getPreserveEmptyDates--) | Gets or sets a value indicating whether it is necessary to keep empty dates when converting a message. |
| [getPreserveOriginalAddresses()](#getPreserveOriginalAddresses--) | Gets or sets a value indicating whether it is necessary to keep original value of mail addresses (without validation). |
| [getPreserveOriginalDates()](#getPreserveOriginalDates--) | Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when converting a message. |
| [getPreserveSignature()](#getPreserveSignature--) | Set to true, if signature is to be preserved. |
| [getUnicodeFormat()](#getUnicodeFormat--) | Returns MapiConversionOptions with OutlookMessageFormat is Unicode(PreserveSignature is False, UseBodyCompression is False). |
| [getUseBodyCompression()](#getUseBodyCompression--) | Set to true, if need RTF body compression. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) |  |
| [setForcedRtfBodyForAppointment(boolean value)](#setForcedRtfBodyForAppointment-boolean-) | Gets or sets a value indicating whether it is necessary to use forced RTF body for an appointment. |
| [setFormat(int value)](#setFormat-int-) | Represents outlook message format. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Gets or sets a value indicating whether it is necessary to preserve EML format of embedded message at converting to MapiMessage. |
| [setPreserveEmptyDates(boolean value)](#setPreserveEmptyDates-boolean-) | Gets or sets a value indicating whether it is necessary to keep empty dates when converting a message. |
| [setPreserveOriginalAddresses(boolean value)](#setPreserveOriginalAddresses-boolean-) | Gets or sets a value indicating whether it is necessary to keep original value of mail addresses (without validation). |
| [setPreserveOriginalDates(boolean value)](#setPreserveOriginalDates-boolean-) | Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when converting a message. |
| [setPreserveSignature(boolean value)](#setPreserveSignature-boolean-) | Set to true, if signature is to be preserved. |
| [setUseBodyCompression(boolean value)](#setUseBodyCompression-boolean-) | Set to true, if need RTF body compression. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiConversionOptions() {#MapiConversionOptions--}
```
public MapiConversionOptions()
```


Initializes a new instance of the [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) class.

### MapiConversionOptions(int format) {#MapiConversionOptions-int-}
```
public MapiConversionOptions(int format)
```


Initializes a new instance of the [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) class with specified OutlookMessageFormat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | int | Format of MapiMessage [OutlookMessageFormat](../../com.aspose.email/outlookmessageformat). |

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
### getASCIIFormat() {#getASCIIFormat--}
```
public static MapiConversionOptions getASCIIFormat()
```


Returns MapiConversionOptions with OutlookMessageFormat is ASCII(PreserveSignature is False, UseBodyCompression is False).

**Returns:**
[MapiConversionOptions](../../com.aspose.email/mapiconversionoptions)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public final ConversionProgressEventHandler getCustomProgressHandler()
```




**Returns:**
[ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler)
### getForcedRtfBodyForAppointment() {#getForcedRtfBodyForAppointment--}
```
public final boolean getForcedRtfBodyForAppointment()
```


Gets or sets a value indicating whether it is necessary to use forced RTF body for an appointment. Default value is true.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Represents outlook message format.

**Returns:**
int
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Gets or sets a value indicating whether it is necessary to preserve EML format of embedded message at converting to MapiMessage. By default the value is false.

--------------------

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from EML to MSG and vice versa, embedded messages are also converted to the target format. Setting the property to true preserves the original format of embedded messages.

**Returns:**
boolean
### getPreserveEmptyDates() {#getPreserveEmptyDates--}
```
public final boolean getPreserveEmptyDates()
```


Gets or sets a value indicating whether it is necessary to keep empty dates when converting a message.

**Returns:**
boolean
### getPreserveOriginalAddresses() {#getPreserveOriginalAddresses--}
```
public final boolean getPreserveOriginalAddresses()
```


Gets or sets a value indicating whether it is necessary to keep original value of mail addresses (without validation).

**Returns:**
boolean
### getPreserveOriginalDates() {#getPreserveOriginalDates--}
```
public final boolean getPreserveOriginalDates()
```


Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when converting a message.

**Returns:**
boolean
### getPreserveSignature() {#getPreserveSignature--}
```
public final boolean getPreserveSignature()
```


Set to true, if signature is to be preserved.

**Returns:**
boolean
### getUnicodeFormat() {#getUnicodeFormat--}
```
public static MapiConversionOptions getUnicodeFormat()
```


Returns MapiConversionOptions with OutlookMessageFormat is Unicode(PreserveSignature is False, UseBodyCompression is False).

**Returns:**
[MapiConversionOptions](../../com.aspose.email/mapiconversionoptions)
### getUseBodyCompression() {#getUseBodyCompression--}
```
public final boolean getUseBodyCompression()
```


Set to true, if need RTF body compression.

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




### setCustomProgressHandler(ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(ConversionProgressEventHandler value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setForcedRtfBodyForAppointment(boolean value) {#setForcedRtfBodyForAppointment-boolean-}
```
public final void setForcedRtfBodyForAppointment(boolean value)
```


Gets or sets a value indicating whether it is necessary to use forced RTF body for an appointment. Default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Represents outlook message format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


Gets or sets a value indicating whether it is necessary to preserve EML format of embedded message at converting to MapiMessage. By default the value is false.

--------------------

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from EML to MSG and vice versa, embedded messages are also converted to the target format. Setting the property to true preserves the original format of embedded messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveEmptyDates(boolean value) {#setPreserveEmptyDates-boolean-}
```
public final void setPreserveEmptyDates(boolean value)
```


Gets or sets a value indicating whether it is necessary to keep empty dates when converting a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveOriginalAddresses(boolean value) {#setPreserveOriginalAddresses-boolean-}
```
public final void setPreserveOriginalAddresses(boolean value)
```


Gets or sets a value indicating whether it is necessary to keep original value of mail addresses (without validation).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveOriginalDates(boolean value) {#setPreserveOriginalDates-boolean-}
```
public final void setPreserveOriginalDates(boolean value)
```


Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when converting a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveSignature(boolean value) {#setPreserveSignature-boolean-}
```
public final void setPreserveSignature(boolean value)
```


Set to true, if signature is to be preserved.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUseBodyCompression(boolean value) {#setUseBodyCompression-boolean-}
```
public final void setUseBodyCompression(boolean value)
```


Set to true, if need RTF body compression.

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

