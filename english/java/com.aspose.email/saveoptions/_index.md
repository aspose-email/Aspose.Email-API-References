---
title: SaveOptions
second_title: Aspose.Email for Java API Reference
description: Serves as the abstract base class for format-specific options when saving  to various email formats EML EMLX MSG MHTML HTML etc..
type: docs
weight: 653
url: /java/com.aspose.email/saveoptions/
---

**Inheritance:**
java.lang.Object
```
public abstract class SaveOptions
```

Serves as the abstract base class for format-specific options when saving [MailMessage](../../com.aspose.email/mailmessage) to various email formats (EML, EMLX, MSG, MHTML, HTML, etc.). This class provides common configuration properties such as custom progress handlers and save type configuration.

--------------------

This class is designed to be inherited by concrete format-specific classes like [EmlSaveOptions](../../com.aspose.email/emlsaveoptions), [MsgSaveOptions](../../com.aspose.email/msgsaveoptions), [HtmlSaveOptions](../../com.aspose.email/htmlsaveoptions), and [MhtSaveOptions](../../com.aspose.email/mhtsaveoptions). Do not instantiate this class directly. Use the format-specific subclasses or the static factory methods like  DefaultEml ([getDefaultEml](../../com.aspose.email/saveoptions\#getDefaultEml)),  DefaultMsg ([getDefaultMsg](../../com.aspose.email/saveoptions\#getDefaultMsg)),  DefaultHtml ([getDefaultHtml](../../com.aspose.email/saveoptions\#getDefaultHtml)), etc.
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
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | Represents method that usually supplied by calling side and handles progress events. |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

