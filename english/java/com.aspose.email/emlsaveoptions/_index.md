---
title: EmlSaveOptions
second_title: Aspose.Email for Java API Reference
description: Provides options for controlling how  instances are saved to EML and EMLX format.
type: docs
weight: 176
url: /java/com.aspose.email/emlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions)
```
public class EmlSaveOptions extends SaveOptions
```

Provides options for controlling how [MailMessage](../../com.aspose.email/mailmessage) instances are saved to EML and EMLX format. This class allows you to customize the saving behavior for features such as embedded message format preservation, TNEF handling, signed message integrity, and boundary template configuration.

Use this class with [MailMessage.save(String, SaveOptions)](../../com.aspose.email/mailmessage\#save-String--SaveOptions-) to specify custom save options. Inherits from [SaveOptions](../../com.aspose.email/saveoptions) and adds EML/EMLX-specific configuration through properties like \#getPreserveEmbeddedMessageFormat().getPreserveEmbeddedMessageFormat(), \#getPreserveSignedContent().getPreserveSignedContent(), and \#getBoundariesTemplate().getBoundariesTemplate().

The following example shows how to load and save an EML message preserving the embedded message format.

```

 MailMessage mailMessage = MailMessage.load("source.eml");
 // Save as eml with preserved embedded message format
 EmlSaveOptions emlSaveOptions = new EmlSaveOptions(MailMessageSaveType.getEmlFormat());
 emlSaveOptions.setPreserveEmbeddedMessageFormat(true);
 mailMessage.save("target.eml", emlSaveOptions);
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmlSaveOptions(MailMessageSaveType saveType)](#EmlSaveOptions-com.aspose.email.MailMessageSaveType-) | Initializes a new instance of the [EmlSaveOptions](../../com.aspose.email/emlsaveoptions) class for the specified format. |
## Methods

| Method | Description |
| --- | --- |
| [createSaveOptions(MailMessageSaveType saveType)](#createSaveOptions-com.aspose.email.MailMessageSaveType-) | Creates save options of the class that matches the specified format. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBoundariesTemplate()](#getBoundariesTemplate--) | Gets the template for the MIME boundaries of the message;  null  (the default) uses generated boundaries. |
| [getCheckBodyContentEncoding()](#getCheckBodyContentEncoding--) | Gets a value indicating whether the encoding of the HTML body is checked before saving. |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | Gets a handler that is called as the saving progresses. |
| [getDefaultEml()](#getDefaultEml--) | Gets new options with the default settings for saving to EML. |
| [getDefaultEmlx()](#getDefaultEmlx--) | Gets new options with the default settings for saving to EMLX. |
| [getDefaultHtml()](#getDefaultHtml--) | Gets new options with the default settings for saving to HTML. |
| [getDefaultMhtml()](#getDefaultMhtml--) | Gets new options with the default settings for saving to MHTML. |
| [getDefaultMsg()](#getDefaultMsg--) | Gets new options with the default settings for saving to MSG with ANSI strings. |
| [getDefaultMsgUnicode()](#getDefaultMsgUnicode--) | Gets new options with the default settings for saving to MSG with Unicode strings. |
| [getDefaultOft()](#getDefaultOft--) | Gets new options with the default settings for saving to Outlook template (OFT). |
| [getFileCompatibilityMode()](#getFileCompatibilityMode--) | Gets conversions applied while saving, such as encoding the TNEF attachment again. |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | Gets the format the options save to. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Gets a value indicating whether embedded messages keep their original format (MSG) instead of being converted to EML. |
| [getPreserveSignedContent()](#getPreserveSignedContent--) | Gets a value indicating whether a signed message is saved exactly as it was loaded, so that its signature stays valid. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBoundariesTemplate(String value)](#setBoundariesTemplate-java.lang.String-) | Sets the template for the MIME boundaries of the message;  null  (the default) uses generated boundaries. |
| [setCheckBodyContentEncoding(boolean value)](#setCheckBodyContentEncoding-boolean-) | Sets a value indicating whether the encoding of the HTML body is checked before saving. |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | Sets a handler that is called as the saving progresses. |
| [setFileCompatibilityMode(int value)](#setFileCompatibilityMode-int-) | Sets conversions applied while saving, such as encoding the TNEF attachment again. |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | Sets the format the options save to. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Sets a value indicating whether embedded messages keep their original format (MSG) instead of being converted to EML. |
| [setPreserveSignedContent(boolean value)](#setPreserveSignedContent-boolean-) | Sets a value indicating whether a signed message is saved exactly as it was loaded, so that its signature stays valid. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmlSaveOptions(MailMessageSaveType saveType) {#EmlSaveOptions-com.aspose.email.MailMessageSaveType-}
```
public EmlSaveOptions(MailMessageSaveType saveType)
```


Initializes a new instance of the [EmlSaveOptions](../../com.aspose.email/emlsaveoptions) class for the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveType | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) | The format: [MailMessageSaveType.getEmlFormat()](../../com.aspose.email/mailmessagesavetype\#getEmlFormat--) or [MailMessageSaveType.getEmlxFormat()](../../com.aspose.email/mailmessagesavetype\#getEmlxFormat--). |

### createSaveOptions(MailMessageSaveType saveType) {#createSaveOptions-com.aspose.email.MailMessageSaveType-}
```
public static SaveOptions createSaveOptions(MailMessageSaveType saveType)
```


Creates save options of the class that matches the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveType | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) | The format to save to. |

**Returns:**
[SaveOptions](../../com.aspose.email/saveoptions) - A [EmlSaveOptions](../../com.aspose.email/emlsaveoptions), [MsgSaveOptions](../../com.aspose.email/msgsaveoptions), [MhtSaveOptions](../../com.aspose.email/mhtsaveoptions) or [HtmlSaveOptions](../../com.aspose.email/htmlsaveoptions) object.
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
### getBoundariesTemplate() {#getBoundariesTemplate--}
```
public final String getBoundariesTemplate()
```


Gets the template for the MIME boundaries of the message;  null  (the default) uses generated boundaries.

In the template,  \{\#\}  is replaced by the number of the boundary and  \{guid\}  by a GUID.

Example:  boundary--\{\#\}-\{guid\} 

**Returns:**
java.lang.String
### getCheckBodyContentEncoding() {#getCheckBodyContentEncoding--}
```
public final boolean getCheckBodyContentEncoding()
```


Gets a value indicating whether the encoding of the HTML body is checked before saving. The default is  false .

When  true  and the HTML body declares an encoding that differs from [MailMessage.getBodyEncoding()](../../com.aspose.email/mailmessage\#getBodyEncoding--), both [MailMessage.getBodyEncoding()](../../com.aspose.email/mailmessage\#getBodyEncoding--) and [MailMessage.getPreferredTextEncoding()](../../com.aspose.email/mailmessage\#getPreferredTextEncoding--) are set to UTF-8.

**Returns:**
boolean
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


Gets a handler that is called as the saving progresses.

**Returns:**
[ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler)
### getDefaultEml() {#getDefaultEml--}
```
public static EmlSaveOptions getDefaultEml()
```


Gets new options with the default settings for saving to EML.

**Returns:**
[EmlSaveOptions](../../com.aspose.email/emlsaveoptions)
### getDefaultEmlx() {#getDefaultEmlx--}
```
public static EmlSaveOptions getDefaultEmlx()
```


Gets new options with the default settings for saving to EMLX.

**Returns:**
[EmlSaveOptions](../../com.aspose.email/emlsaveoptions)
### getDefaultHtml() {#getDefaultHtml--}
```
public static HtmlSaveOptions getDefaultHtml()
```


Gets new options with the default settings for saving to HTML.

**Returns:**
[HtmlSaveOptions](../../com.aspose.email/htmlsaveoptions)
### getDefaultMhtml() {#getDefaultMhtml--}
```
public static MhtSaveOptions getDefaultMhtml()
```


Gets new options with the default settings for saving to MHTML.

**Returns:**
[MhtSaveOptions](../../com.aspose.email/mhtsaveoptions)
### getDefaultMsg() {#getDefaultMsg--}
```
public static MsgSaveOptions getDefaultMsg()
```


Gets new options with the default settings for saving to MSG with ANSI strings.

**Returns:**
[MsgSaveOptions](../../com.aspose.email/msgsaveoptions)
### getDefaultMsgUnicode() {#getDefaultMsgUnicode--}
```
public static MsgSaveOptions getDefaultMsgUnicode()
```


Gets new options with the default settings for saving to MSG with Unicode strings.

**Returns:**
[MsgSaveOptions](../../com.aspose.email/msgsaveoptions)
### getDefaultOft() {#getDefaultOft--}
```
public static MsgSaveOptions getDefaultOft()
```


Gets new options with the default settings for saving to Outlook template (OFT).

**Returns:**
[MsgSaveOptions](../../com.aspose.email/msgsaveoptions)
### getFileCompatibilityMode() {#getFileCompatibilityMode--}
```
public final int getFileCompatibilityMode()
```


Gets conversions applied while saving, such as encoding the TNEF attachment again. The default is  FileCompatibilityMode.None .

**Returns:**
int
### getMailMessageSaveType() {#getMailMessageSaveType--}
```
public final MailMessageSaveType getMailMessageSaveType()
```


Gets the format the options save to.

**Returns:**
[MailMessageSaveType](../../com.aspose.email/mailmessagesavetype)
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Gets a value indicating whether embedded messages keep their original format (MSG) instead of being converted to EML. The default is  false .

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from MSG to EML and vice versa, embedded messages are also converted to the target format. Setting the property to  true  preserves the original format of embedded messages.

**Returns:**
boolean
### getPreserveSignedContent() {#getPreserveSignedContent--}
```
public final boolean getPreserveSignedContent()
```


Gets a value indicating whether a signed message is saved exactly as it was loaded, so that its signature stays valid. The default is  false .

The property is only meaningful for signed messages; it has no effect on unsigned messages. This property is intended for some complex signed messages with detached signature generated by other clients, whose implementation differences prevent Aspose.Email from exactly replicating their MIME content generation. Saving such messages without using this property will cause the signature in the saved messages to fail. Some simple messages and messages with an attached signature can be saved correctly without using this property.

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




### setBoundariesTemplate(String value) {#setBoundariesTemplate-java.lang.String-}
```
public final void setBoundariesTemplate(String value)
```


Sets the template for the MIME boundaries of the message;  null  (the default) uses generated boundaries.

In the template,  \{\#\}  is replaced by the number of the boundary and  \{guid\}  by a GUID.

Example:  boundary--\{\#\}-\{guid\} 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCheckBodyContentEncoding(boolean value) {#setCheckBodyContentEncoding-boolean-}
```
public final void setCheckBodyContentEncoding(boolean value)
```


Sets a value indicating whether the encoding of the HTML body is checked before saving. The default is  false .

When  true  and the HTML body declares an encoding that differs from [MailMessage.getBodyEncoding()](../../com.aspose.email/mailmessage\#getBodyEncoding--), both [MailMessage.getBodyEncoding()](../../com.aspose.email/mailmessage\#getBodyEncoding--) and [MailMessage.getPreferredTextEncoding()](../../com.aspose.email/mailmessage\#getPreferredTextEncoding--) are set to UTF-8.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setCustomProgressHandler(ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(ConversionProgressEventHandler value)
```


Sets a handler that is called as the saving progresses.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setFileCompatibilityMode(int value) {#setFileCompatibilityMode-int-}
```
public final void setFileCompatibilityMode(int value)
```


Sets conversions applied while saving, such as encoding the TNEF attachment again. The default is  FileCompatibilityMode.None .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMailMessageSaveType(MailMessageSaveType value) {#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-}
```
public final void setMailMessageSaveType(MailMessageSaveType value)
```


Sets the format the options save to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


Sets a value indicating whether embedded messages keep their original format (MSG) instead of being converted to EML. The default is  false .

Generally, embedded messages have the same format (EML or MSG) as the underlying message. By default, when converting from MSG to EML and vice versa, embedded messages are also converted to the target format. Setting the property to  true  preserves the original format of embedded messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveSignedContent(boolean value) {#setPreserveSignedContent-boolean-}
```
public final void setPreserveSignedContent(boolean value)
```


Sets a value indicating whether a signed message is saved exactly as it was loaded, so that its signature stays valid. The default is  false .

The property is only meaningful for signed messages; it has no effect on unsigned messages. This property is intended for some complex signed messages with detached signature generated by other clients, whose implementation differences prevent Aspose.Email from exactly replicating their MIME content generation. Saving such messages without using this property will cause the signature in the saved messages to fail. Some simple messages and messages with an attached signature can be saved correctly without using this property.

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

