---
title: MhtSaveOptions
second_title: Aspose.Email for Java API Reference
description: Allows to specify additional options when saving MailMessage to Mhtml format.
type: docs
weight: 526
url: /java/com.aspose.email/mhtsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions), [com.aspose.email.HeadersFormattingOptions](../../com.aspose.email/headersformattingoptions)
```
public class MhtSaveOptions extends HeadersFormattingOptions
```

Allows to specify additional options when saving MailMessage to Mhtml format.

--------------------

> The following example shows how to save MailMessage as MHTML.
> 
> [Java]
> 
> ```
> MailMessage eml = MailMessage.load("Message.eml");
>  eml.save("target.mthml", SaveOptions.getDefaultMhtml());
> ```

--------------------
## Constructors

| Constructor | Description |
| --- | --- |
| [MhtSaveOptions()](#MhtSaveOptions--) | Initializes a new instance of this class that can be used to save a MailMessage in the Mhtml format. |
## Methods

| Method | Description |
| --- | --- |
| [createSaveOptions(MailMessageSaveType saveType)](#createSaveOptions-com.aspose.email.MailMessageSaveType-) | Creates a save options object of a class suitable for the specified save type. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAfterHeadersFormat()](#getAfterHeadersFormat--) | After headers format. |
| [getBeforeHeadersFormat()](#getBeforeHeadersFormat--) | Before headers format. |
| [getCheckBodyContentEncoding()](#getCheckBodyContentEncoding--) | Defines whether need check message body content encoding when saving. |
| [getClass()](#getClass--) |  |
| [getCssStyles()](#getCssStyles--) | Gets or sets the additional css styles for the formatter. |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | Represents method that usually supplied by calling side and handles progress events. |
| [getDefaultEml()](#getDefaultEml--) | Gets options with default values for saving message to Eml format. |
| [getDefaultEmlx()](#getDefaultEmlx--) | Gets options with default values for saving message to Emlx format. |
| [getDefaultHeaderFormat()](#getDefaultHeaderFormat--) | Default header line format. |
| [getDefaultHtml()](#getDefaultHtml--) | Gets options with default values for saving message to Html format. |
| [getDefaultMhtml()](#getDefaultMhtml--) | Gets options with default values for saving message to Mhtml format. |
| [getDefaultMsg()](#getDefaultMsg--) | Gets options with default values for saving message to Msg(ASCII) format. |
| [getDefaultMsgUnicode()](#getDefaultMsgUnicode--) | Gets options with default values for saving message to Msg(Unicode) format. |
| [getDefaultOft()](#getDefaultOft--) | Gets options with default values for saving message to Outlook template (Oft) format. |
| [getDefaultPageHeaderFormat()](#getDefaultPageHeaderFormat--) | Default page header format. |
| [getFormatTemplates()](#getFormatTemplates--) | Gets the format templates. |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. |
| [getMhtFormatOptions()](#getMhtFormatOptions--) | Defines additional options when saving in MHTML format. |
| [getPreserveOriginalBoundaries()](#getPreserveOriginalBoundaries--) | Defines whether need keep original boundaries in mail message when saving or not. |
| [getPreserveOriginalDate()](#getPreserveOriginalDate--) | Defines whether need keep original date in mail message when saving or not. |
| [getRenderedContactFields()](#getRenderedContactFields--) | Defines groups of Contact fields which will be included in output mhtml. |
| [getRenderingHeaders()](#getRenderingHeaders--) | Gets list of headers for rendering. |
| [getSaveAllHeaders()](#getSaveAllHeaders--) | Defines whether need to save all headers in output mhtml or not. |
| [getSaveAttachments()](#getSaveAttachments--) | Gets or sets a value indicating whether to save attachments. |
| [getSavedHeaders()](#getSavedHeaders--) | Gets list of headers which will be present in saved mhtml content. |
| [getSkipInlineImages()](#getSkipInlineImages--) | Defines whether skip references on images at saving in mhtml or not. |
| [getTimeout()](#getTimeout--) | Limits the time in milliseconds of formatting message while saving in Mht. |
| [getTimeoutReachedHandler()](#getTimeoutReachedHandler--) | Raised if timed out while saving to Mhtml. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAfterHeadersFormat(String value)](#setAfterHeadersFormat-java.lang.String-) | After headers format. |
| [setBeforeHeadersFormat(String value)](#setBeforeHeadersFormat-java.lang.String-) | Before headers format. |
| [setCheckBodyContentEncoding(boolean value)](#setCheckBodyContentEncoding-boolean-) | Defines whether need check message body content encoding when saving. |
| [setCssStyles(String value)](#setCssStyles-java.lang.String-) | Gets or sets the additional css styles for the formatter. |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | Represents method that usually supplied by calling side and handles progress events. |
| [setDefaultHeaderFormat(String value)](#setDefaultHeaderFormat-java.lang.String-) | Default header line format. |
| [setDefaultPageHeaderFormat(String value)](#setDefaultPageHeaderFormat-java.lang.String-) | Default page header format. |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. |
| [setMhtFormatOptions(int value)](#setMhtFormatOptions-int-) | Defines additional options when saving in MHTML format. |
| [setPreserveOriginalBoundaries(boolean value)](#setPreserveOriginalBoundaries-boolean-) | Defines whether need keep original boundaries in mail message when saving or not. |
| [setPreserveOriginalDate(boolean value)](#setPreserveOriginalDate-boolean-) | Defines whether need keep original date in mail message when saving or not. |
| [setRenderedContactFields(int value)](#setRenderedContactFields-int-) | Defines groups of Contact fields which will be included in output mhtml. |
| [setSaveAllHeaders(boolean value)](#setSaveAllHeaders-boolean-) | Defines whether need to save all headers in output mhtml or not. |
| [setSaveAttachments(boolean value)](#setSaveAttachments-boolean-) | Gets or sets a value indicating whether to save attachments. |
| [setSkipInlineImages(boolean value)](#setSkipInlineImages-boolean-) | Defines whether skip references on images at saving in mhtml or not. |
| [setTimeout(int value)](#setTimeout-int-) | Limits the time in milliseconds of formatting message while saving in Mht. |
| [setTimeoutReachedHandler(TimeoutReachedHandler value)](#setTimeoutReachedHandler-com.aspose.email.TimeoutReachedHandler-) | Raised if timed out while saving to Mhtml. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MhtSaveOptions() {#MhtSaveOptions--}
```
public MhtSaveOptions()
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
### getCheckBodyContentEncoding() {#getCheckBodyContentEncoding--}
```
public final boolean getCheckBodyContentEncoding()
```


Defines whether need check message body content encoding when saving. By default the value is false.

--------------------

If true, it will be check whether the  MailMessage.HtmlBody ([MailMessage.getHtmlBody](../../com.aspose.email/mailmessage\#getHtmlBody)/[MailMessage.setHtmlBody(String)](../../com.aspose.email/mailmessage\#setHtmlBody-String-)) content encoding matches to the encoding specified by the  MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) property. If the HtmlBody content encoding doesn't match BodyEncoding property, the  MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) and  MailMessage.PreferredTextEncoding ([MailMessage.getPreferredTextEncoding](../../com.aspose.email/mailmessage\#getPreferredTextEncoding)/[MailMessage.setPreferredTextEncoding(Encoding)](../../com.aspose.email/mailmessage\#setPreferredTextEncoding-Encoding-)) properties will be changed to default  System.Text.Encoding.UTF8 (java.nio.charset.Charset\#getUTF8.getUTF8).

**Returns:**
boolean
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
### getDefaultEmlx() {#getDefaultEmlx--}
```
public static EmlSaveOptions getDefaultEmlx()
```


Gets options with default values for saving message to Emlx format.

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
### getDefaultOft() {#getDefaultOft--}
```
public static MsgSaveOptions getDefaultOft()
```


Gets options with default values for saving message to Outlook template (Oft) format.

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
### getMhtFormatOptions() {#getMhtFormatOptions--}
```
public final int getMhtFormatOptions()
```


Defines additional options when saving in MHTML format. Default value is MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments.

**Returns:**
int
### getPreserveOriginalBoundaries() {#getPreserveOriginalBoundaries--}
```
public final boolean getPreserveOriginalBoundaries()
```


Defines whether need keep original boundaries in mail message when saving or not.

**Returns:**
boolean
### getPreserveOriginalDate() {#getPreserveOriginalDate--}
```
public final boolean getPreserveOriginalDate()
```


Defines whether need keep original date in mail message when saving or not. Default value is true.

**Returns:**
boolean
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
### getSaveAllHeaders() {#getSaveAllHeaders--}
```
public final boolean getSaveAllHeaders()
```


Defines whether need to save all headers in output mhtml or not. Default value is false.

**Returns:**
boolean
### getSaveAttachments() {#getSaveAttachments--}
```
public final boolean getSaveAttachments()
```


Gets or sets a value indicating whether to save attachments.

Value:  true  if attachments should be saved; otherwise,  false .

**Returns:**
boolean
### getSavedHeaders() {#getSavedHeaders--}
```
public final List<String> getSavedHeaders()
```


Gets list of headers which will be present in saved mhtml content. Default value is empty list.

**Returns:**
java.util.List<java.lang.String>
### getSkipInlineImages() {#getSkipInlineImages--}
```
public final boolean getSkipInlineImages()
```


Defines whether skip references on images at saving in mhtml or not. Default value is false.

**Returns:**
boolean
### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Limits the time in milliseconds of formatting message while saving in Mht. Default value 3 sec.

**Returns:**
int
### getTimeoutReachedHandler() {#getTimeoutReachedHandler--}
```
public final TimeoutReachedHandler getTimeoutReachedHandler()
```


Raised if timed out while saving to Mhtml.

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

### setCheckBodyContentEncoding(boolean value) {#setCheckBodyContentEncoding-boolean-}
```
public final void setCheckBodyContentEncoding(boolean value)
```


Defines whether need check message body content encoding when saving. By default the value is false.

--------------------

If true, it will be check whether the  MailMessage.HtmlBody ([MailMessage.getHtmlBody](../../com.aspose.email/mailmessage\#getHtmlBody)/[MailMessage.setHtmlBody(String)](../../com.aspose.email/mailmessage\#setHtmlBody-String-)) content encoding matches to the encoding specified by the  MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) property. If the HtmlBody content encoding doesn't match BodyEncoding property, the  MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) and  MailMessage.PreferredTextEncoding ([MailMessage.getPreferredTextEncoding](../../com.aspose.email/mailmessage\#getPreferredTextEncoding)/[MailMessage.setPreferredTextEncoding(Encoding)](../../com.aspose.email/mailmessage\#setPreferredTextEncoding-Encoding-)) properties will be changed to default  System.Text.Encoding.UTF8 (java.nio.charset.Charset\#getUTF8.getUTF8).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### setMhtFormatOptions(int value) {#setMhtFormatOptions-int-}
```
public final void setMhtFormatOptions(int value)
```


Defines additional options when saving in MHTML format. Default value is MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPreserveOriginalBoundaries(boolean value) {#setPreserveOriginalBoundaries-boolean-}
```
public final void setPreserveOriginalBoundaries(boolean value)
```


Defines whether need keep original boundaries in mail message when saving or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveOriginalDate(boolean value) {#setPreserveOriginalDate-boolean-}
```
public final void setPreserveOriginalDate(boolean value)
```


Defines whether need keep original date in mail message when saving or not. Default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRenderedContactFields(int value) {#setRenderedContactFields-int-}
```
public final void setRenderedContactFields(int value)
```


Defines groups of Contact fields which will be included in output mhtml. Default value is ContactFieldsSet.AllExisting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSaveAllHeaders(boolean value) {#setSaveAllHeaders-boolean-}
```
public final void setSaveAllHeaders(boolean value)
```


Defines whether need to save all headers in output mhtml or not. Default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSaveAttachments(boolean value) {#setSaveAttachments-boolean-}
```
public final void setSaveAttachments(boolean value)
```


Gets or sets a value indicating whether to save attachments.

Value:  true  if attachments should be saved; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSkipInlineImages(boolean value) {#setSkipInlineImages-boolean-}
```
public final void setSkipInlineImages(boolean value)
```


Defines whether skip references on images at saving in mhtml or not. Default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


Limits the time in milliseconds of formatting message while saving in Mht. Default value 3 sec.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTimeoutReachedHandler(TimeoutReachedHandler value) {#setTimeoutReachedHandler-com.aspose.email.TimeoutReachedHandler-}
```
public final void setTimeoutReachedHandler(TimeoutReachedHandler value)
```


Raised if timed out while saving to Mhtml.

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

