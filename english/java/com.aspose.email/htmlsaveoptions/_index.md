---
title: HtmlSaveOptions
second_title: Aspose.Email for Java API Reference
description: Allows to specify additional options when saving MailMessage to Html format.
type: docs
weight: 295
url: /java/com.aspose.email/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions), [com.aspose.email.HeadersFormattingOptions](../../com.aspose.email/headersformattingoptions)
```
public class HtmlSaveOptions extends HeadersFormattingOptions
```

Allows to specify additional options when saving MailMessage to Html format.
## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) | Initializes a new instance of this class that can be used to save a MailMessage in the Html format. |
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
| [getHtmlFormatOptions()](#getHtmlFormatOptions--) | Gets or sets additional options when saving in HTML format. |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. |
| [getRenderedContactFields()](#getRenderedContactFields--) | Defines groups of Contact fields which will be included in output mhtml. |
| [getRenderingHeaders()](#getRenderingHeaders--) | Gets list of headers for rendering. |
| [getResourceHtmlRenderingHandler()](#getResourceHtmlRenderingHandler--) | Provides customization of rendering resources in html. |
| [getResourceRenderingMode()](#getResourceRenderingMode--) | Provides set various modes of rendering resources in html. |
| [getUseRelativePathToResources()](#getUseRelativePathToResources--) | If true then resources will be saved in folder htmlFileName.files in the same folder that html file and the relative path to resources will be added in html content , otherwise absolute path from ResourceHtmlRenderingEventArgs.PathToResourceFile property will be used for saving resources and adding to html. |
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
| [setHtmlFormatOptions(int value)](#setHtmlFormatOptions-int-) | Gets or sets additional options when saving in HTML format. |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | Represents the mail message save type.It can be in eml,msg(ASCII or Unicode),mhtml or html format. |
| [setRenderedContactFields(int value)](#setRenderedContactFields-int-) | Defines groups of Contact fields which will be included in output mhtml. |
| [setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value)](#setResourceHtmlRenderingHandler-com.aspose.email.ResourceHtmlRenderingHandler-) | Provides customization of rendering resources in html. |
| [setResourceRenderingMode(int value)](#setResourceRenderingMode-int-) | Provides set various modes of rendering resources in html. |
| [setUseRelativePathToResources(boolean value)](#setUseRelativePathToResources-boolean-) | If true then resources will be saved in folder htmlFileName.files in the same folder that html file and the relative path to resources will be added in html content , otherwise absolute path from ResourceHtmlRenderingEventArgs.PathToResourceFile property will be used for saving resources and adding to html. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


Initializes a new instance of this class that can be used to save a MailMessage in the Html format.

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
### getHtmlFormatOptions() {#getHtmlFormatOptions--}
```
public final int getHtmlFormatOptions()
```


Gets or sets additional options when saving in HTML format. Default value is HtmlFormatOptions.None.

**Returns:**
int
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
### getResourceHtmlRenderingHandler() {#getResourceHtmlRenderingHandler--}
```
public final ResourceHtmlRenderingHandler getResourceHtmlRenderingHandler()
```


Provides customization of rendering resources in html.

**Returns:**
[ResourceHtmlRenderingHandler](../../com.aspose.email/resourcehtmlrenderinghandler)
### getResourceRenderingMode() {#getResourceRenderingMode--}
```
public final int getResourceRenderingMode()
```


Provides set various modes of rendering resources in html. Default value EmbedIntoHtml.

**Returns:**
int
### getUseRelativePathToResources() {#getUseRelativePathToResources--}
```
public final boolean getUseRelativePathToResources()
```


If true then resources will be saved in folder htmlFileName.files in the same folder that html file and the relative path to resources will be added in html content , otherwise absolute path from ResourceHtmlRenderingEventArgs.PathToResourceFile property will be used for saving resources and adding to html. It make sense if ResourceRenderingMode is ResourceRenderingMode.SaveToFile. Default value is false.

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

### setHtmlFormatOptions(int value) {#setHtmlFormatOptions-int-}
```
public final void setHtmlFormatOptions(int value)
```


Gets or sets additional options when saving in HTML format. Default value is HtmlFormatOptions.None.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

### setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value) {#setResourceHtmlRenderingHandler-com.aspose.email.ResourceHtmlRenderingHandler-}
```
public final void setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value)
```


Provides customization of rendering resources in html.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ResourceHtmlRenderingHandler](../../com.aspose.email/resourcehtmlrenderinghandler) |  |

### setResourceRenderingMode(int value) {#setResourceRenderingMode-int-}
```
public final void setResourceRenderingMode(int value)
```


Provides set various modes of rendering resources in html. Default value EmbedIntoHtml.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUseRelativePathToResources(boolean value) {#setUseRelativePathToResources-boolean-}
```
public final void setUseRelativePathToResources(boolean value)
```


If true then resources will be saved in folder htmlFileName.files in the same folder that html file and the relative path to resources will be added in html content , otherwise absolute path from ResourceHtmlRenderingEventArgs.PathToResourceFile property will be used for saving resources and adding to html. It make sense if ResourceRenderingMode is ResourceRenderingMode.SaveToFile. Default value is false.

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

