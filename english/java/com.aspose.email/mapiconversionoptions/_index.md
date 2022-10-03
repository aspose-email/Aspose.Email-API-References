---
title: MapiConversionOptions
second_title: Aspose.Email for Java API Reference
description:  This class allows the user to specify additional options when converting from MailMessage to MapiMessage.
type: docs
weight: 431
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
| [getCustomProgressHandler()](#getCustomProgressHandler--) |  |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) |  |
| [getFormat()](#getFormat--) | Represents outlook message format. |
| [setFormat(int value)](#setFormat-int-) | Represents outlook message format. |
| [getPreserveSignature()](#getPreserveSignature--) | Set to true, if signature is to be preserved. |
| [setPreserveSignature(boolean value)](#setPreserveSignature-boolean-) | Set to true, if signature is to be preserved. |
| [getUseBodyCompression()](#getUseBodyCompression--) | Set to true, if need RTF body compression. |
| [setUseBodyCompression(boolean value)](#setUseBodyCompression-boolean-) | Set to true, if need RTF body compression. |
| [getPreserveOriginalDates()](#getPreserveOriginalDates--) | Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when converting a message. |
| [setPreserveOriginalDates(boolean value)](#setPreserveOriginalDates-boolean-) | Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when converting a message. |
| [getPreserveEmptyDates()](#getPreserveEmptyDates--) | Gets or sets a value indicating whether it is necessary to keep empty dates when converting a message. |
| [setPreserveEmptyDates(boolean value)](#setPreserveEmptyDates-boolean-) | Gets or sets a value indicating whether it is necessary to keep empty dates when converting a message. |
| [getPreserveOriginalAddresses()](#getPreserveOriginalAddresses--) | Gets or sets a value indicating whether it is necessary to keep original value of mail addresses (without validation). |
| [setPreserveOriginalAddresses(boolean value)](#setPreserveOriginalAddresses-boolean-) | Gets or sets a value indicating whether it is necessary to keep original value of mail addresses (without validation). |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets or sets a value indicating whether it is necessary to preserve EML format of embedded message at converting to MapiMessage. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Gets or sets a value indicating whether it is necessary to preserve EML format of embedded message at converting to MapiMessage. |
| [getASCIIFormat()](#getASCIIFormat--) | Returns MapiConversionOptions with OutlookMessageFormat is ASCII(PreserveSignature is False, UseBodyCompression is False). |
| [getUnicodeFormat()](#getUnicodeFormat--) | Returns MapiConversionOptions with OutlookMessageFormat is Unicode(PreserveSignature is False, UseBodyCompression is False). |
| [getForcedRtfBodyForAppointment()](#getForcedRtfBodyForAppointment--) | Gets or sets a value indicating whether it is necessary to use forced RTF body for an appointment. |
| [setForcedRtfBodyForAppointment(boolean value)](#setForcedRtfBodyForAppointment-boolean-) | Gets or sets a value indicating whether it is necessary to use forced RTF body for an appointment. |
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

### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public final ConversionProgressEventHandler getCustomProgressHandler()
```




**Returns:**
[ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler)
### setCustomProgressHandler(ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(ConversionProgressEventHandler value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### getFormat() {#getFormat--}
```
public final int getFormat()
```


Represents outlook message format.

**Returns:**
int
### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Represents outlook message format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPreserveSignature() {#getPreserveSignature--}
```
public final boolean getPreserveSignature()
```


Set to true, if signature is to be preserved.

**Returns:**
boolean
### setPreserveSignature(boolean value) {#setPreserveSignature-boolean-}
```
public final void setPreserveSignature(boolean value)
```


Set to true, if signature is to be preserved.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseBodyCompression() {#getUseBodyCompression--}
```
public final boolean getUseBodyCompression()
```


Set to true, if need RTF body compression.

**Returns:**
boolean
### setUseBodyCompression(boolean value) {#setUseBodyCompression-boolean-}
```
public final void setUseBodyCompression(boolean value)
```


Set to true, if need RTF body compression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPreserveOriginalDates() {#getPreserveOriginalDates--}
```
public final boolean getPreserveOriginalDates()
```


Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when converting a message.

**Returns:**
boolean
### setPreserveOriginalDates(boolean value) {#setPreserveOriginalDates-boolean-}
```
public final void setPreserveOriginalDates(boolean value)
```


Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when converting a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPreserveEmptyDates() {#getPreserveEmptyDates--}
```
public final boolean getPreserveEmptyDates()
```


Gets or sets a value indicating whether it is necessary to keep empty dates when converting a message.

**Returns:**
boolean
### setPreserveEmptyDates(boolean value) {#setPreserveEmptyDates-boolean-}
```
public final void setPreserveEmptyDates(boolean value)
```


Gets or sets a value indicating whether it is necessary to keep empty dates when converting a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPreserveOriginalAddresses() {#getPreserveOriginalAddresses--}
```
public final boolean getPreserveOriginalAddresses()
```


Gets or sets a value indicating whether it is necessary to keep original value of mail addresses (without validation).

**Returns:**
boolean
### setPreserveOriginalAddresses(boolean value) {#setPreserveOriginalAddresses-boolean-}
```
public final void setPreserveOriginalAddresses(boolean value)
```


Gets or sets a value indicating whether it is necessary to keep original value of mail addresses (without validation).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Gets or sets a value indicating whether it is necessary to preserve EML format of embedded message at converting to MapiMessage. By default the value is false.

--------------------

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from EML to MSG and vice versa, embedded messages are also converted to the target format. Setting the property to true preserves the original format of embedded messages.

**Returns:**
boolean
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

### getASCIIFormat() {#getASCIIFormat--}
```
public static MapiConversionOptions getASCIIFormat()
```


Returns MapiConversionOptions with OutlookMessageFormat is ASCII(PreserveSignature is False, UseBodyCompression is False).

**Returns:**
[MapiConversionOptions](../../com.aspose.email/mapiconversionoptions)
### getUnicodeFormat() {#getUnicodeFormat--}
```
public static MapiConversionOptions getUnicodeFormat()
```


Returns MapiConversionOptions with OutlookMessageFormat is Unicode(PreserveSignature is False, UseBodyCompression is False).

**Returns:**
[MapiConversionOptions](../../com.aspose.email/mapiconversionoptions)
### getForcedRtfBodyForAppointment() {#getForcedRtfBodyForAppointment--}
```
public final boolean getForcedRtfBodyForAppointment()
```


Gets or sets a value indicating whether it is necessary to use forced RTF body for an appointment. Default value is true.

**Returns:**
boolean
### setForcedRtfBodyForAppointment(boolean value) {#setForcedRtfBodyForAppointment-boolean-}
```
public final void setForcedRtfBodyForAppointment(boolean value)
```


Gets or sets a value indicating whether it is necessary to use forced RTF body for an appointment. Default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

