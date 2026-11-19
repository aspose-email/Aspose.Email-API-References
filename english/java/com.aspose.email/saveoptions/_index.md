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

This class is designed to be inherited by concrete format-specific classes like [EmlSaveOptions](../../com.aspose.email/emlsaveoptions), [MsgSaveOptions](../../com.aspose.email/msgsaveoptions), [HtmlSaveOptions](../../com.aspose.email/htmlsaveoptions), and [MhtSaveOptions](../../com.aspose.email/mhtsaveoptions). Do not instantiate this class directly. Use the format-specific subclasses or the static factory methods like \#getDefaultEml().getDefaultEml(), \#getDefaultMsg().getDefaultMsg(), \#getDefaultHtml().getDefaultHtml(), etc.
## Methods

| Method | Description |
| --- | --- |
| [createSaveOptions(MailMessageSaveType saveType)](#createSaveOptions-com.aspose.email.MailMessageSaveType-) | Creates save options of the class that matches the specified format. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | Gets a handler that is called as the saving progresses. |
| [getDefaultEml()](#getDefaultEml--) | Gets new options with the default settings for saving to EML. |
| [getDefaultEmlx()](#getDefaultEmlx--) | Gets new options with the default settings for saving to EMLX. |
| [getDefaultHtml()](#getDefaultHtml--) | Gets new options with the default settings for saving to HTML. |
| [getDefaultMhtml()](#getDefaultMhtml--) | Gets new options with the default settings for saving to MHTML. |
| [getDefaultMsg()](#getDefaultMsg--) | Gets new options with the default settings for saving to MSG with ANSI strings. |
| [getDefaultMsgUnicode()](#getDefaultMsgUnicode--) | Gets new options with the default settings for saving to MSG with Unicode strings. |
| [getDefaultOft()](#getDefaultOft--) | Gets new options with the default settings for saving to Outlook template (OFT). |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | Gets the format the options save to. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | Sets a handler that is called as the saving progresses. |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | Sets the format the options save to. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getMailMessageSaveType() {#getMailMessageSaveType--}
```
public final MailMessageSaveType getMailMessageSaveType()
```


Gets the format the options save to.

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


Sets a handler that is called as the saving progresses.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setMailMessageSaveType(MailMessageSaveType value) {#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-}
```
public final void setMailMessageSaveType(MailMessageSaveType value)
```


Sets the format the options save to.

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

