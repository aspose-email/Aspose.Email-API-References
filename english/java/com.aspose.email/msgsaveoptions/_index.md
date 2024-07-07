---
title: MsgSaveOptions
second_title: Aspose.Email for Java API Reference
description: This class allows the user to specify additional settings when saving a MailMessage in the MsgASCII and MsgUnicode format.
type: docs
weight: 536
url: /java/com.aspose.email/msgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions)
```
public class MsgSaveOptions extends SaveOptions
```

This class allows the user to specify additional settings when saving a MailMessage in the Msg(ASCII) and Msg(Unicode) format.

--------------------

> The following example shows how to save as MSG with preserved dates.
> 
> [Java]
> 
> ```
> // Initialize and Load an existing EML file by specifying the MessageFormat
>  MailMessage eml = MailMessage.load("Message.eml");
> 
>  // Save as msg with preserved dates
>  MsgSaveOptions msgSaveOptions = new MsgSaveOptions(MailMessageSaveType.getOutlookMessageFormatUnicode())
>  msgSaveOptions.setPreserveOriginalDates(true);
> 
>  eml.save("outTest_out.msg", msgSaveOptions);
> ```

--------------------
## Constructors

| Constructor | Description |
| --- | --- |
| [MsgSaveOptions(MailMessageSaveType saveType)](#MsgSaveOptions-com.aspose.email.MailMessageSaveType-) | Initializes a new instance of this class that can be used to save a MailMessage in the Msg(ASCII) and Msg(Unicode) format. |
## Methods

| Method | Description |
| --- | --- |
| [createSaveOptions(MailMessageSaveType saveType)](#createSaveOptions-com.aspose.email.MailMessageSaveType-) | Creates a save options object of a class suitable for the specified save type. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | Represents method that usually supplied by calling side and handles progress events. |
| [getDefaultEml()](#getDefaultEml--) | Gets options with default values for saving message to Eml format. |
| [getDefaultEmlx()](#getDefaultEmlx--) | Gets options with default values for saving message to Emlx format. |
| [getDefaultHtml()](#getDefaultHtml--) | Gets options with default values for saving message to Html format. |
| [getDefaultMhtml()](#getDefaultMhtml--) | Gets options with default values for saving message to Mhtml format. |
| [getDefaultMsg()](#getDefaultMsg--) | Gets options with default values for saving message to Msg(ASCII) format. |
| [getDefaultMsgUnicode()](#getDefaultMsgUnicode--) | Gets options with default values for saving message to Msg(Unicode) format. |
| [getDefaultOft()](#getDefaultOft--) | Gets options with default values for saving message to Outlook template (Oft) format. |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. |
| [getPreserveOriginalDates()](#getPreserveOriginalDates--) | Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when saving a message. |
| [getPreserveSignature()](#getPreserveSignature--) | Set to true, if signature is to be preserved. |
| [getSaveAsTemplate()](#getSaveAsTemplate--) | Set to true, if need to be saved as Outlook File Template(OFT format). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | Represents method that usually supplied by calling side and handles progress events. |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. |
| [setPreserveOriginalDates(boolean value)](#setPreserveOriginalDates-boolean-) | Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when saving a message. |
| [setPreserveSignature(boolean value)](#setPreserveSignature-boolean-) | Set to true, if signature is to be preserved. |
| [setSaveAsTemplate(boolean value)](#setSaveAsTemplate-boolean-) | Set to true, if need to be saved as Outlook File Template(OFT format). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MsgSaveOptions(MailMessageSaveType saveType) {#MsgSaveOptions-com.aspose.email.MailMessageSaveType-}
```
public MsgSaveOptions(MailMessageSaveType saveType)
```


Initializes a new instance of this class that can be used to save a MailMessage in the Msg(ASCII) and Msg(Unicode) format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveType | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### createSaveOptions(MailMessageSaveType saveType) {#createSaveOptions-com.aspose.email.MailMessageSaveType-}
```
public static SaveOptions createSaveOptions(MailMessageSaveType saveType)
```


Creates a save options object of a class suitable for the specified save type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveType | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) | The  MailMessageSaveTypesave type (\#getMailMessageSaveType.getMailMessageSaveType/\#setMailMessageSaveType(MailMessageSaveType).setMailMessageSaveType(MailMessageSaveType)) for which to create a save options object. |

**Returns:**
[SaveOptions](../../com.aspose.email/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.email/saveoptions).
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
### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public final ConversionProgressEventHandler getCustomProgressHandler()
```


Represents method that usually supplied by calling side and handles progress events.

**Returns:**
[ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler)
### getDefaultEml() {#getDefaultEml--}
```
public static EmlSaveOptions getDefaultEml()
```


Gets options with default values for saving message to Eml format.

**Returns:**
[EmlSaveOptions](../../com.aspose.email/emlsaveoptions)
### getDefaultEmlx() {#getDefaultEmlx--}
```
public static EmlSaveOptions getDefaultEmlx()
```


Gets options with default values for saving message to Emlx format.

**Returns:**
[EmlSaveOptions](../../com.aspose.email/emlsaveoptions)
### getDefaultHtml() {#getDefaultHtml--}
```
public static HtmlSaveOptions getDefaultHtml()
```


Gets options with default values for saving message to Html format.

**Returns:**
[HtmlSaveOptions](../../com.aspose.email/htmlsaveoptions)
### getDefaultMhtml() {#getDefaultMhtml--}
```
public static MhtSaveOptions getDefaultMhtml()
```


Gets options with default values for saving message to Mhtml format.

**Returns:**
[MhtSaveOptions](../../com.aspose.email/mhtsaveoptions)
### getDefaultMsg() {#getDefaultMsg--}
```
public static MsgSaveOptions getDefaultMsg()
```


Gets options with default values for saving message to Msg(ASCII) format.

**Returns:**
[MsgSaveOptions](../../com.aspose.email/msgsaveoptions)
### getDefaultMsgUnicode() {#getDefaultMsgUnicode--}
```
public static MsgSaveOptions getDefaultMsgUnicode()
```


Gets options with default values for saving message to Msg(Unicode) format.

**Returns:**
[MsgSaveOptions](../../com.aspose.email/msgsaveoptions)
### getDefaultOft() {#getDefaultOft--}
```
public static MsgSaveOptions getDefaultOft()
```


Gets options with default values for saving message to Outlook template (Oft) format.

**Returns:**
[MsgSaveOptions](../../com.aspose.email/msgsaveoptions)
### getMailMessageSaveType() {#getMailMessageSaveType--}
```
public final MailMessageSaveType getMailMessageSaveType()
```


Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. The default value is Eml.

**Returns:**
[MailMessageSaveType](../../com.aspose.email/mailmessagesavetype)
### getPreserveOriginalDates() {#getPreserveOriginalDates--}
```
public final boolean getPreserveOriginalDates()
```


Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when saving a message. By default the value is true, meaning the creation and modification dates will be not set to DateTime.Now.

**Returns:**
boolean
### getPreserveSignature() {#getPreserveSignature--}
```
public final boolean getPreserveSignature()
```


Set to true, if signature is to be preserved.

**Returns:**
boolean
### getSaveAsTemplate() {#getSaveAsTemplate--}
```
public final boolean getSaveAsTemplate()
```


Set to true, if need to be saved as Outlook File Template(OFT format).

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


Represents method that usually supplied by calling side and handles progress events.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setMailMessageSaveType(MailMessageSaveType value) {#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-}
```
public final void setMailMessageSaveType(MailMessageSaveType value)
```


Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. The default value is Eml.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### setPreserveOriginalDates(boolean value) {#setPreserveOriginalDates-boolean-}
```
public final void setPreserveOriginalDates(boolean value)
```


Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when saving a message. By default the value is true, meaning the creation and modification dates will be not set to DateTime.Now.

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

### setSaveAsTemplate(boolean value) {#setSaveAsTemplate-boolean-}
```
public final void setSaveAsTemplate(boolean value)
```


Set to true, if need to be saved as Outlook File Template(OFT format).

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

