---
title: MapiConversionOptions
second_title: Aspose.Email for Java API Reference
description: Options that control how a  is converted to a .
type: docs
weight: 455
url: /java/com.aspose.email/mapiconversionoptions/
---

**Inheritance:**
java.lang.Object
```
public class MapiConversionOptions
```

Options that control how a [MailMessage](../../com.aspose.email/mailmessage) is converted to a [MapiMessage](../../com.aspose.email/mapimessage).

Pass an instance to [MapiMessage.fromMailMessage(String)](../../com.aspose.email/mapimessage\#fromMailMessage-String-). \#getUnicodeFormat().getUnicodeFormat() and \#getASCIIFormat().getASCIIFormat() return ready-made options for the two MSG formats.

This example converts an EML file to a Unicode MSG file, keeping the original dates.

```

 MailMessage eml = MailMessage.load("message.eml");

 MapiConversionOptions options = MapiConversionOptions.getUnicodeFormat();
 options.setPreserveOriginalDates(true);

 try (MapiMessage msg = MapiMessage.fromMailMessage(eml, options)) {
     msg.save("message.msg");
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiConversionOptions()](#MapiConversionOptions--) | Initializes a new instance of the [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) class that produces an ANSI message. |
| [MapiConversionOptions(int format)](#MapiConversionOptions-int-) | Initializes a new instance of the [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) class that produces a message in the specified format. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getASCIIFormat()](#getASCIIFormat--) | Gets new options that produce a message in ANSI (8-bit) format. |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | Gets a handler that is called as the conversion progresses. |
| [getForcedRtfBodyForAppointment()](#getForcedRtfBodyForAppointment--) | Gets a value indicating whether an appointment or a meeting request gets an RTF body built from the body of the source message. |
| [getFormat()](#getFormat--) | Gets the format of the resulting message: Unicode or ANSI. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets a value indicating whether embedded messages stay in EML format instead of being converted to MSG. |
| [getPreserveEmptyDates()](#getPreserveEmptyDates--) | Gets a value indicating whether the creation and modification dates are left unset. |
| [getPreserveOriginalAddresses()](#getPreserveOriginalAddresses--) | Gets a value indicating whether the addresses are kept exactly as in the source message, without validation. |
| [getPreserveOriginalDates()](#getPreserveOriginalDates--) | Gets a value indicating whether the sent date of the source message is kept. |
| [getRemoveSignature()](#getRemoveSignature--) | Gets a value indicating whether the digital signature is removed from a signed message during the conversion. |
| [getUnicodeFormat()](#getUnicodeFormat--) | Gets new options that produce a message in Unicode format. |
| [getUseBodyCompression()](#getUseBodyCompression--) | Gets a value indicating whether the RTF body is stored compressed. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | Sets a handler that is called as the conversion progresses. |
| [setForcedRtfBodyForAppointment(boolean value)](#setForcedRtfBodyForAppointment-boolean-) | Sets a value indicating whether an appointment or a meeting request gets an RTF body built from the body of the source message. |
| [setFormat(int value)](#setFormat-int-) | Sets the format of the resulting message: Unicode or ANSI. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Sets a value indicating whether embedded messages stay in EML format instead of being converted to MSG. |
| [setPreserveEmptyDates(boolean value)](#setPreserveEmptyDates-boolean-) | Sets a value indicating whether the creation and modification dates are left unset. |
| [setPreserveOriginalAddresses(boolean value)](#setPreserveOriginalAddresses-boolean-) | Sets a value indicating whether the addresses are kept exactly as in the source message, without validation. |
| [setPreserveOriginalDates(boolean value)](#setPreserveOriginalDates-boolean-) | Sets a value indicating whether the sent date of the source message is kept. |
| [setRemoveSignature(boolean value)](#setRemoveSignature-boolean-) | Sets a value indicating whether the digital signature is removed from a signed message during the conversion. |
| [setUseBodyCompression(boolean value)](#setUseBodyCompression-boolean-) | Sets a value indicating whether the RTF body is stored compressed. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiConversionOptions() {#MapiConversionOptions--}
```
public MapiConversionOptions()
```


Initializes a new instance of the [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) class that produces an ANSI message.

### MapiConversionOptions(int format) {#MapiConversionOptions-int-}
```
public MapiConversionOptions(int format)
```


Initializes a new instance of the [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) class that produces a message in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | int | The format of the resulting message: Unicode or ANSI. |

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


Gets new options that produce a message in ANSI (8-bit) format.

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


Gets a handler that is called as the conversion progresses.

**Returns:**
[ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler)
### getForcedRtfBodyForAppointment() {#getForcedRtfBodyForAppointment--}
```
public final boolean getForcedRtfBodyForAppointment()
```


Gets a value indicating whether an appointment or a meeting request gets an RTF body built from the body of the source message. The default is  false .

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Gets the format of the resulting message: Unicode or ANSI. The default is ANSI.

**Returns:**
int
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Gets a value indicating whether embedded messages stay in EML format instead of being converted to MSG. The default is  false .

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from EML to MSG and vice versa, embedded messages are also converted to the target format. Setting the property to  true  preserves the original format of embedded messages.

**Returns:**
boolean
### getPreserveEmptyDates() {#getPreserveEmptyDates--}
```
public final boolean getPreserveEmptyDates()
```


Gets a value indicating whether the creation and modification dates are left unset. When  false  (the default), both are set to the time of the conversion.

**Returns:**
boolean
### getPreserveOriginalAddresses() {#getPreserveOriginalAddresses--}
```
public final boolean getPreserveOriginalAddresses()
```


Gets a value indicating whether the addresses are kept exactly as in the source message, without validation. The default is  false .

**Returns:**
boolean
### getPreserveOriginalDates() {#getPreserveOriginalDates--}
```
public final boolean getPreserveOriginalDates()
```


Gets a value indicating whether the sent date of the source message is kept. When  false , the time of the conversion is used. The default is  true .

**Returns:**
boolean
### getRemoveSignature() {#getRemoveSignature--}
```
public final boolean getRemoveSignature()
```


Gets a value indicating whether the digital signature is removed from a signed message during the conversion.

**Returns:**
boolean -  true  to remove the signature; otherwise,  false . The default is  false .
### getUnicodeFormat() {#getUnicodeFormat--}
```
public static MapiConversionOptions getUnicodeFormat()
```


Gets new options that produce a message in Unicode format.

**Returns:**
[MapiConversionOptions](../../com.aspose.email/mapiconversionoptions)
### getUseBodyCompression() {#getUseBodyCompression--}
```
public final boolean getUseBodyCompression()
```


Gets a value indicating whether the RTF body is stored compressed. The default is  false .

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


Sets a handler that is called as the conversion progresses.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setForcedRtfBodyForAppointment(boolean value) {#setForcedRtfBodyForAppointment-boolean-}
```
public final void setForcedRtfBodyForAppointment(boolean value)
```


Sets a value indicating whether an appointment or a meeting request gets an RTF body built from the body of the source message. The default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Sets the format of the resulting message: Unicode or ANSI. The default is ANSI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


Sets a value indicating whether embedded messages stay in EML format instead of being converted to MSG. The default is  false .

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from EML to MSG and vice versa, embedded messages are also converted to the target format. Setting the property to  true  preserves the original format of embedded messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveEmptyDates(boolean value) {#setPreserveEmptyDates-boolean-}
```
public final void setPreserveEmptyDates(boolean value)
```


Sets a value indicating whether the creation and modification dates are left unset. When  false  (the default), both are set to the time of the conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveOriginalAddresses(boolean value) {#setPreserveOriginalAddresses-boolean-}
```
public final void setPreserveOriginalAddresses(boolean value)
```


Sets a value indicating whether the addresses are kept exactly as in the source message, without validation. The default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveOriginalDates(boolean value) {#setPreserveOriginalDates-boolean-}
```
public final void setPreserveOriginalDates(boolean value)
```


Sets a value indicating whether the sent date of the source message is kept. When  false , the time of the conversion is used. The default is  true .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRemoveSignature(boolean value) {#setRemoveSignature-boolean-}
```
public final void setRemoveSignature(boolean value)
```


Sets a value indicating whether the digital signature is removed from a signed message during the conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to remove the signature; otherwise,  false . The default is  false . |

### setUseBodyCompression(boolean value) {#setUseBodyCompression-boolean-}
```
public final void setUseBodyCompression(boolean value)
```


Sets a value indicating whether the RTF body is stored compressed. The default is  false .

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

