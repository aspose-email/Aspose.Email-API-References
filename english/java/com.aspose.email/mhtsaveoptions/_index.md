---
title: MhtSaveOptions
second_title: Aspose.Email for Java API Reference
description: Provides options for controlling how  instances are saved to MHTML format.
type: docs
weight: 544
url: /java/com.aspose.email/mhtsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions), [com.aspose.email.HeadersFormattingOptions](../../com.aspose.email/headersformattingoptions)
```
public class MhtSaveOptions extends HeadersFormattingOptions
```

Provides options for controlling how [MailMessage](../../com.aspose.email/mailmessage) instances are saved to MHTML format. This class allows you to customize MHTML output formatting, attachment handling, header preservation, and resource rendering behavior when converting email messages to MHTML (MIME HTML) files.

Use this class with [MailMessage.save(String, SaveOptions)](../../com.aspose.email/mailmessage\#save-String--SaveOptions-) to save messages in MHTML format. MHTML is a web page archive format that combines HTML content and embedded resources into a single file. The [MhtFormatOptions](../../com.aspose.email/mhtformatoptions) property controls formatting options, \#getSaveAttachments().getSaveAttachments() determines whether attachments are included, and \#getSavedHeaders().getSavedHeaders() allows you to specify custom headers to include in the output.

The following example shows how to save MailMessage as MHTML.

```

 MailMessage eml = MailMessage.load("Message.eml");
 eml.save("target.mthml", SaveOptions.getDefaultMhtml());
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MhtSaveOptions()](#MhtSaveOptions--) | Initializes a new instance of the [MhtSaveOptions](../../com.aspose.email/mhtsaveoptions) class with the default options. |
## Methods

| Method | Description |
| --- | --- |
| [createSaveOptions(MailMessageSaveType saveType)](#createSaveOptions-com.aspose.email.MailMessageSaveType-) | Creates save options of the class that matches the specified format. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAfterHeadersFormat()](#getAfterHeadersFormat--) | Gets the HTML written after the block of headers. |
| [getBeforeHeadersFormat()](#getBeforeHeadersFormat--) | Gets the HTML written before the block of headers. |
| [getCheckBodyContentEncoding()](#getCheckBodyContentEncoding--) | Gets a value indicating whether the encoding of the HTML body is checked before saving. |
| [getClass()](#getClass--) |  |
| [getCssStyles()](#getCssStyles--) | Gets additional CSS styles added to the output. |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | Gets a handler that is called as the saving progresses. |
| [getDefaultEml()](#getDefaultEml--) | Gets new options with the default settings for saving to EML. |
| [getDefaultEmlx()](#getDefaultEmlx--) | Gets new options with the default settings for saving to EMLX. |
| [getDefaultHeaderFormat()](#getDefaultHeaderFormat--) | Gets the HTML format of a header line, from which the template of each header in \#getFormatTemplates().getFormatTemplates() is built;  \{0\}  stands for the name of the header. |
| [getDefaultHtml()](#getDefaultHtml--) | Gets new options with the default settings for saving to HTML. |
| [getDefaultMhtml()](#getDefaultMhtml--) | Gets new options with the default settings for saving to MHTML. |
| [getDefaultMsg()](#getDefaultMsg--) | Gets new options with the default settings for saving to MSG with ANSI strings. |
| [getDefaultMsgUnicode()](#getDefaultMsgUnicode--) | Gets new options with the default settings for saving to MSG with Unicode strings. |
| [getDefaultOft()](#getDefaultOft--) | Gets new options with the default settings for saving to Outlook template (OFT). |
| [getDefaultPageHeaderFormat()](#getDefaultPageHeaderFormat--) | Gets the HTML format of the page header. |
| [getExtractHTMLBodyResourcesAsAttachments()](#getExtractHTMLBodyResourcesAsAttachments--) | Gets a value indicating whether the resources of the HTML body, such as images, are also written as attachments. |
| [getFormatTemplates()](#getFormatTemplates--) | Gets the formats of individual headers, keyed by the names in [MhtTemplateName](../../com.aspose.email/mhttemplatename). |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | Gets the format the options save to. |
| [getMhtFormatOptions()](#getMhtFormatOptions--) | Gets options for the MHTML output. |
| [getPreserveOriginalBoundaries()](#getPreserveOriginalBoundaries--) | Gets a value indicating whether the MIME boundaries of the original message are kept. |
| [getPreserveOriginalDate()](#getPreserveOriginalDate--) | Gets a value indicating whether the original date of the message is kept. |
| [getRenderedContactFields()](#getRenderedContactFields--) | Gets the groups of contact fields written for a contact. |
| [getRenderingHeaders()](#getRenderingHeaders--) | Gets the headers written to the output, in order, as names from [MhtTemplateName](../../com.aspose.email/mhttemplatename). |
| [getResourceHtmlRenderingHandler()](#getResourceHtmlRenderingHandler--) | Gets the handler of the event that occurs for each attachment rendered into the HTML; set the properties of the event arguments to supply the content, file or caption to use for it. |
| [getSaveAllHeaders()](#getSaveAllHeaders--) | Gets a value indicating whether all headers of the message are written to the output. |
| [getSaveAttachments()](#getSaveAttachments--) | Gets a value indicating whether the attachments are saved into the MHTML file. |
| [getSavedHeaders()](#getSavedHeaders--) | Gets the headers of the message that are kept in the MIME headers of the MHTML file; the others are dropped. |
| [getSkipInlineImages()](#getSkipInlineImages--) | Gets a value indicating whether inline images are left out of the output. |
| [getTimeout()](#getTimeout--) | Gets the time limit, in milliseconds, for formatting the message. |
| [getTimeoutReachedHandler()](#getTimeoutReachedHandler--) | Gets the handler of the event that occurs when formatting the message takes longer than \#getTimeout().getTimeout(). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAfterHeadersFormat(String value)](#setAfterHeadersFormat-java.lang.String-) | Sets the HTML written after the block of headers. |
| [setBeforeHeadersFormat(String value)](#setBeforeHeadersFormat-java.lang.String-) | Sets the HTML written before the block of headers. |
| [setCheckBodyContentEncoding(boolean value)](#setCheckBodyContentEncoding-boolean-) | Sets a value indicating whether the encoding of the HTML body is checked before saving. |
| [setCssStyles(String value)](#setCssStyles-java.lang.String-) | Sets additional CSS styles added to the output. |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | Sets a handler that is called as the saving progresses. |
| [setDefaultHeaderFormat(String value)](#setDefaultHeaderFormat-java.lang.String-) | Sets the HTML format of a header line, from which the template of each header in \#getFormatTemplates().getFormatTemplates() is built;  \{0\}  stands for the name of the header. |
| [setDefaultPageHeaderFormat(String value)](#setDefaultPageHeaderFormat-java.lang.String-) | Sets the HTML format of the page header. |
| [setExtractHTMLBodyResourcesAsAttachments(boolean value)](#setExtractHTMLBodyResourcesAsAttachments-boolean-) | Sets a value indicating whether the resources of the HTML body, such as images, are also written as attachments. |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | Sets the format the options save to. |
| [setMhtFormatOptions(int value)](#setMhtFormatOptions-int-) | Sets options for the MHTML output. |
| [setPreserveOriginalBoundaries(boolean value)](#setPreserveOriginalBoundaries-boolean-) | Sets a value indicating whether the MIME boundaries of the original message are kept. |
| [setPreserveOriginalDate(boolean value)](#setPreserveOriginalDate-boolean-) | Sets a value indicating whether the original date of the message is kept. |
| [setRenderedContactFields(int value)](#setRenderedContactFields-int-) | Sets the groups of contact fields written for a contact. |
| [setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value)](#setResourceHtmlRenderingHandler-com.aspose.email.ResourceHtmlRenderingHandler-) | Provides customization of rendering resources in html. |
| [setSaveAllHeaders(boolean value)](#setSaveAllHeaders-boolean-) | Sets a value indicating whether all headers of the message are written to the output. |
| [setSaveAttachments(boolean value)](#setSaveAttachments-boolean-) | Sets a value indicating whether the attachments are saved into the MHTML file. |
| [setSkipInlineImages(boolean value)](#setSkipInlineImages-boolean-) | Sets a value indicating whether inline images are left out of the output. |
| [setTimeout(int value)](#setTimeout-int-) | Sets the time limit, in milliseconds, for formatting the message. |
| [setTimeoutReachedHandler(TimeoutReachedHandler value)](#setTimeoutReachedHandler-com.aspose.email.TimeoutReachedHandler-) | Raised if timed out while saving to Mhtml. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MhtSaveOptions() {#MhtSaveOptions--}
```
public MhtSaveOptions()
```


Initializes a new instance of the [MhtSaveOptions](../../com.aspose.email/mhtsaveoptions) class with the default options.

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
### getAfterHeadersFormat() {#getAfterHeadersFormat--}
```
public final String getAfterHeadersFormat()
```


Gets the HTML written after the block of headers.

**Returns:**
java.lang.String - The HTML fragment.
### getBeforeHeadersFormat() {#getBeforeHeadersFormat--}
```
public final String getBeforeHeadersFormat()
```


Gets the HTML written before the block of headers.

**Returns:**
java.lang.String - The HTML fragment.
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
### getCssStyles() {#getCssStyles--}
```
public final String getCssStyles()
```


Gets additional CSS styles added to the output.

**Returns:**
java.lang.String - The CSS styles.
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
### getDefaultHeaderFormat() {#getDefaultHeaderFormat--}
```
public final String getDefaultHeaderFormat()
```


Gets the HTML format of a header line, from which the template of each header in \#getFormatTemplates().getFormatTemplates() is built;  \{0\}  stands for the name of the header.

**Returns:**
java.lang.String - The format of a header line.
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
### getDefaultPageHeaderFormat() {#getDefaultPageHeaderFormat--}
```
public final String getDefaultPageHeaderFormat()
```


Gets the HTML format of the page header.

**Returns:**
java.lang.String - The format of the page header.
### getExtractHTMLBodyResourcesAsAttachments() {#getExtractHTMLBodyResourcesAsAttachments--}
```
public final boolean getExtractHTMLBodyResourcesAsAttachments()
```


Gets a value indicating whether the resources of the HTML body, such as images, are also written as attachments. The default is  false .

**Returns:**
boolean
### getFormatTemplates() {#getFormatTemplates--}
```
public final System.Collections.Specialized.StringDictionary getFormatTemplates()
```


Gets the formats of individual headers, keyed by the names in [MhtTemplateName](../../com.aspose.email/mhttemplatename).

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringDictionary - The format templates.
### getMailMessageSaveType() {#getMailMessageSaveType--}
```
public final MailMessageSaveType getMailMessageSaveType()
```


Gets the format the options save to.

**Returns:**
[MailMessageSaveType](../../com.aspose.email/mailmessagesavetype)
### getMhtFormatOptions() {#getMhtFormatOptions--}
```
public final int getMhtFormatOptions()
```


Gets options for the MHTML output. The default is  MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments .

**Returns:**
int
### getPreserveOriginalBoundaries() {#getPreserveOriginalBoundaries--}
```
public final boolean getPreserveOriginalBoundaries()
```


Gets a value indicating whether the MIME boundaries of the original message are kept. The default is  false .

**Returns:**
boolean
### getPreserveOriginalDate() {#getPreserveOriginalDate--}
```
public final boolean getPreserveOriginalDate()
```


Gets a value indicating whether the original date of the message is kept. The default is  true .

**Returns:**
boolean
### getRenderedContactFields() {#getRenderedContactFields--}
```
public final int getRenderedContactFields()
```


Gets the groups of contact fields written for a contact. The default is  ContactFieldsSet.AllExisting .

**Returns:**
int
### getRenderingHeaders() {#getRenderingHeaders--}
```
public final List<String> getRenderingHeaders()
```


Gets the headers written to the output, in order, as names from [MhtTemplateName](../../com.aspose.email/mhttemplatename). By default: From, Sent, To, Cc, Bcc, Subject, Attachments, Importance and Categories.

**Returns:**
java.util.List<java.lang.String>
### getResourceHtmlRenderingHandler() {#getResourceHtmlRenderingHandler--}
```
public final ResourceHtmlRenderingHandler getResourceHtmlRenderingHandler()
```


Gets the handler of the event that occurs for each attachment rendered into the HTML; set the properties of the event arguments to supply the content, file or caption to use for it.

**Returns:**
[ResourceHtmlRenderingHandler](../../com.aspose.email/resourcehtmlrenderinghandler)
### getSaveAllHeaders() {#getSaveAllHeaders--}
```
public final boolean getSaveAllHeaders()
```


Gets a value indicating whether all headers of the message are written to the output. The default is  false .

**Returns:**
boolean
### getSaveAttachments() {#getSaveAttachments--}
```
public final boolean getSaveAttachments()
```


Gets a value indicating whether the attachments are saved into the MHTML file.

**Returns:**
boolean -  true  to save the attachments; otherwise,  false . The default is  true .
### getSavedHeaders() {#getSavedHeaders--}
```
public final List<String> getSavedHeaders()
```


Gets the headers of the message that are kept in the MIME headers of the MHTML file; the others are dropped. The list is empty by default.

**Returns:**
java.util.List<java.lang.String>
### getSkipInlineImages() {#getSkipInlineImages--}
```
public final boolean getSkipInlineImages()
```


Gets a value indicating whether inline images are left out of the output. The default is  false .

**Returns:**
boolean
### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Gets the time limit, in milliseconds, for formatting the message. The default is 3000 (3 seconds).

**Returns:**
int
### getTimeoutReachedHandler() {#getTimeoutReachedHandler--}
```
public final TimeoutReachedHandler getTimeoutReachedHandler()
```


Gets the handler of the event that occurs when formatting the message takes longer than \#getTimeout().getTimeout().

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


Sets the HTML written after the block of headers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The HTML fragment. |

### setBeforeHeadersFormat(String value) {#setBeforeHeadersFormat-java.lang.String-}
```
public final void setBeforeHeadersFormat(String value)
```


Sets the HTML written before the block of headers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The HTML fragment. |

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

### setCssStyles(String value) {#setCssStyles-java.lang.String-}
```
public final void setCssStyles(String value)
```


Sets additional CSS styles added to the output.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The CSS styles. |

### setCustomProgressHandler(ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(ConversionProgressEventHandler value)
```


Sets a handler that is called as the saving progresses.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setDefaultHeaderFormat(String value) {#setDefaultHeaderFormat-java.lang.String-}
```
public final void setDefaultHeaderFormat(String value)
```


Sets the HTML format of a header line, from which the template of each header in \#getFormatTemplates().getFormatTemplates() is built;  \{0\}  stands for the name of the header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The format of a header line. |

### setDefaultPageHeaderFormat(String value) {#setDefaultPageHeaderFormat-java.lang.String-}
```
public final void setDefaultPageHeaderFormat(String value)
```


Sets the HTML format of the page header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The format of the page header. |

### setExtractHTMLBodyResourcesAsAttachments(boolean value) {#setExtractHTMLBodyResourcesAsAttachments-boolean-}
```
public final void setExtractHTMLBodyResourcesAsAttachments(boolean value)
```


Sets a value indicating whether the resources of the HTML body, such as images, are also written as attachments. The default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setMailMessageSaveType(MailMessageSaveType value) {#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-}
```
public final void setMailMessageSaveType(MailMessageSaveType value)
```


Sets the format the options save to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### setMhtFormatOptions(int value) {#setMhtFormatOptions-int-}
```
public final void setMhtFormatOptions(int value)
```


Sets options for the MHTML output. The default is  MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPreserveOriginalBoundaries(boolean value) {#setPreserveOriginalBoundaries-boolean-}
```
public final void setPreserveOriginalBoundaries(boolean value)
```


Sets a value indicating whether the MIME boundaries of the original message are kept. The default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPreserveOriginalDate(boolean value) {#setPreserveOriginalDate-boolean-}
```
public final void setPreserveOriginalDate(boolean value)
```


Sets a value indicating whether the original date of the message is kept. The default is  true .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRenderedContactFields(int value) {#setRenderedContactFields-int-}
```
public final void setRenderedContactFields(int value)
```


Sets the groups of contact fields written for a contact. The default is  ContactFieldsSet.AllExisting .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value) {#setResourceHtmlRenderingHandler-com.aspose.email.ResourceHtmlRenderingHandler-}
```
public final void setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value)
```


Provides customization of rendering resources in html.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ResourceHtmlRenderingHandler](../../com.aspose.email/resourcehtmlrenderinghandler) |  |

### setSaveAllHeaders(boolean value) {#setSaveAllHeaders-boolean-}
```
public final void setSaveAllHeaders(boolean value)
```


Sets a value indicating whether all headers of the message are written to the output. The default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSaveAttachments(boolean value) {#setSaveAttachments-boolean-}
```
public final void setSaveAttachments(boolean value)
```


Sets a value indicating whether the attachments are saved into the MHTML file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to save the attachments; otherwise,  false . The default is  true . |

### setSkipInlineImages(boolean value) {#setSkipInlineImages-boolean-}
```
public final void setSkipInlineImages(boolean value)
```


Sets a value indicating whether inline images are left out of the output. The default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


Sets the time limit, in milliseconds, for formatting the message. The default is 3000 (3 seconds).

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

