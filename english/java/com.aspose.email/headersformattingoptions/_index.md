---
title: HeadersFormattingOptions
second_title: Aspose.Email for Java API Reference
description: Allows to specify headers formatting options when saving MailMessage to Mhtml or Html format.
type: docs
weight: 291
url: /java/com.aspose.email/headersformattingoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions)
```
public abstract class HeadersFormattingOptions extends SaveOptions
```

Allows to specify headers formatting options when saving MailMessage to Mhtml or Html format.
## Constructors

| Constructor | Description |
| --- | --- |
| [HeadersFormattingOptions()](#HeadersFormattingOptions--) | Initializes a new instance of this class that can be used to save a MailMessage in the Mhtml format. |
## Methods

| Method | Description |
| --- | --- |
| [createSaveOptions(MailMessageSaveType saveType)](#createSaveOptions-com.aspose.email.MailMessageSaveType-) | Creates a save options object of a class suitable for the specified save type. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAfterHeadersFormat()](#getAfterHeadersFormat--) | After headers format. |
| [getBeforeHeadersFormat()](#getBeforeHeadersFormat--) | Before headers format. |
| [getClass()](#getClass--) |  |
| [getCssStyles()](#getCssStyles--) | Gets or sets the additional css styles for the formatter. |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | Represents method that usually supplied by calling side and handles progress events. |
| [getDefaultEml()](#getDefaultEml--) | Gets options with default values for saving message to Eml format. |
| [getDefaultHeaderFormat()](#getDefaultHeaderFormat--) | Default header line format. |
| [getDefaultHtml()](#getDefaultHtml--) | Gets options with default values for saving message to Html format. |
| [getDefaultMhtml()](#getDefaultMhtml--) | Gets options with default values for saving message to Mhtml format. |
| [getDefaultMsg()](#getDefaultMsg--) | Gets options with default values for saving message to Msg(ASCII) format. |
| [getDefaultMsgUnicode()](#getDefaultMsgUnicode--) | Gets options with default values for saving message to Msg(Unicode) format. |
| [getDefaultPageHeaderFormat()](#getDefaultPageHeaderFormat--) | Default page header format. |
| [getFormatTemplates()](#getFormatTemplates--) | Gets the format templates. |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. |
| [getRenderedContactFields()](#getRenderedContactFields--) | Defines groups of Contact fields which will be included in output mhtml. |
| [getRenderingHeaders()](#getRenderingHeaders--) | Gets list of headers for rendering. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAfterHeadersFormat(String value)](#setAfterHeadersFormat-java.lang.String-) | After headers format. |
| [setBeforeHeadersFormat(String value)](#setBeforeHeadersFormat-java.lang.String-) | Before headers format. |
| [setCssStyles(String value)](#setCssStyles-java.lang.String-) | Gets or sets the additional css styles for the formatter. |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | Represents method that usually supplied by calling side and handles progress events. |
| [setDefaultHeaderFormat(String value)](#setDefaultHeaderFormat-java.lang.String-) | Default header line format. |
| [setDefaultPageHeaderFormat(String value)](#setDefaultPageHeaderFormat-java.lang.String-) | Default page header format. |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. |
| [setRenderedContactFields(int value)](#setRenderedContactFields-int-) | Defines groups of Contact fields which will be included in output mhtml. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HeadersFormattingOptions() {#HeadersFormattingOptions--}
```
public HeadersFormattingOptions()
```


Initializes a new instance of this class that can be used to save a MailMessage in the Mhtml format.

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
### getAfterHeadersFormat() {#getAfterHeadersFormat--}
```
public final String getAfterHeadersFormat()
```


After headers format.

Value: The styles to be injected into resulting html body.

**Returns:**
java.lang.String
### getBeforeHeadersFormat() {#getBeforeHeadersFormat--}
```
public final String getBeforeHeadersFormat()
```


Before headers format.

Value: The styles to be injected into resulting html body.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCssStyles() {#getCssStyles--}
```
public final String getCssStyles()
```


Gets or sets the additional css styles for the formatter.

Value: The styles to be injected into resulting html body.

**Returns:**
java.lang.String
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
### getDefaultHeaderFormat() {#getDefaultHeaderFormat--}
```
public final String getDefaultHeaderFormat()
```


Default header line format.

Value: The styles to be injected into resulting html body.

**Returns:**
java.lang.String
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
### getDefaultPageHeaderFormat() {#getDefaultPageHeaderFormat--}
```
public final String getDefaultPageHeaderFormat()
```


Default page header format.

Value: The styles to be injected into resulting html body.

**Returns:**
java.lang.String
### getFormatTemplates() {#getFormatTemplates--}
```
public final System.Collections.Specialized.StringDictionary getFormatTemplates()
```


Gets the format templates.

Value: The format templates.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringDictionary
### getMailMessageSaveType() {#getMailMessageSaveType--}
```
public final MailMessageSaveType getMailMessageSaveType()
```


Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. The default value is Eml.

**Returns:**
[MailMessageSaveType](../../com.aspose.email/mailmessagesavetype)
### getRenderedContactFields() {#getRenderedContactFields--}
```
public final int getRenderedContactFields()
```


Defines groups of Contact fields which will be included in output mhtml. Default value is ContactFieldsSet.AllExisting.

**Returns:**
int
### getRenderingHeaders() {#getRenderingHeaders--}
```
public final List<String> getRenderingHeaders()
```


Gets list of headers for rendering.

**Returns:**
java.util.List<java.lang.String>
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




### setAfterHeadersFormat(String value) {#setAfterHeadersFormat-java.lang.String-}
```
public final void setAfterHeadersFormat(String value)
```


After headers format.

Value: The styles to be injected into resulting html body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBeforeHeadersFormat(String value) {#setBeforeHeadersFormat-java.lang.String-}
```
public final void setBeforeHeadersFormat(String value)
```


Before headers format.

Value: The styles to be injected into resulting html body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCssStyles(String value) {#setCssStyles-java.lang.String-}
```
public final void setCssStyles(String value)
```


Gets or sets the additional css styles for the formatter.

Value: The styles to be injected into resulting html body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCustomProgressHandler(ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(ConversionProgressEventHandler value)
```


Represents method that usually supplied by calling side and handles progress events.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setDefaultHeaderFormat(String value) {#setDefaultHeaderFormat-java.lang.String-}
```
public final void setDefaultHeaderFormat(String value)
```


Default header line format.

Value: The styles to be injected into resulting html body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDefaultPageHeaderFormat(String value) {#setDefaultPageHeaderFormat-java.lang.String-}
```
public final void setDefaultPageHeaderFormat(String value)
```


Default page header format.

Value: The styles to be injected into resulting html body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMailMessageSaveType(MailMessageSaveType value) {#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-}
```
public final void setMailMessageSaveType(MailMessageSaveType value)
```


Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. The default value is Eml.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### setRenderedContactFields(int value) {#setRenderedContactFields-int-}
```
public final void setRenderedContactFields(int value)
```


Defines groups of Contact fields which will be included in output mhtml. Default value is ContactFieldsSet.AllExisting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

