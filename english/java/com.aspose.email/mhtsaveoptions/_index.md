---
title: MhtSaveOptions
second_title: Aspose.Email for Java API Reference
description: Allows to specify additional options when saving MailMessage to Mhtml format.
type: docs
weight: 510
url: /java/com.aspose.email/mhtsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions), [com.aspose.email.HeadersFormattingOptions](../../com.aspose.email/headersformattingoptions)
```
public class MhtSaveOptions extends HeadersFormattingOptions
```

Allows to specify additional options when saving MailMessage to Mhtml format.
## Constructors

| Constructor | Description |
| --- | --- |
| [MhtSaveOptions()](#MhtSaveOptions--) | Initializes a new instance of this class that can be used to save a MailMessage in the Mhtml format. |
## Methods

| Method | Description |
| --- | --- |
| [getTimeoutReachedHandler()](#getTimeoutReachedHandler--) | Raised if timed out while saving to Mhtml. |
| [setTimeoutReachedHandler(TimeoutReachedHandler value)](#setTimeoutReachedHandler-com.aspose.email.TimeoutReachedHandler-) | Raised if timed out while saving to Mhtml. |
| [getTimeout()](#getTimeout--) | Limits the time in milliseconds of formatting message while saving in Mht. |
| [setTimeout(int value)](#setTimeout-int-) | Limits the time in milliseconds of formatting message while saving in Mht. |
| [getMhtFormatOptions()](#getMhtFormatOptions--) | Defines additional options when saving in MHTML format. |
| [setMhtFormatOptions(int value)](#setMhtFormatOptions-int-) | Defines additional options when saving in MHTML format. |
| [getPreserveOriginalBoundaries()](#getPreserveOriginalBoundaries--) | Defines whether need keep original boundaries in mail message when saving or not. |
| [setPreserveOriginalBoundaries(boolean value)](#setPreserveOriginalBoundaries-boolean-) | Defines whether need keep original boundaries in mail message when saving or not. |
| [getCheckBodyContentEncoding()](#getCheckBodyContentEncoding--) | Defines whether need check message body content encoding when saving. |
| [setCheckBodyContentEncoding(boolean value)](#setCheckBodyContentEncoding-boolean-) | Defines whether need check message body content encoding when saving. |
| [getSaveAttachments()](#getSaveAttachments--) | Gets or sets a value indicating whether to save attachments. |
| [setSaveAttachments(boolean value)](#setSaveAttachments-boolean-) | Gets or sets a value indicating whether to save attachments. |
| [getPreserveOriginalDate()](#getPreserveOriginalDate--) | Defines whether need keep original date in mail message when saving or not. |
| [setPreserveOriginalDate(boolean value)](#setPreserveOriginalDate-boolean-) | Defines whether need keep original date in mail message when saving or not. |
| [getSkipInlineImages()](#getSkipInlineImages--) | Defines whether skip references on images at saving in mhtml or not. |
| [setSkipInlineImages(boolean value)](#setSkipInlineImages-boolean-) | Defines whether skip references on images at saving in mhtml or not. |
### MhtSaveOptions() {#MhtSaveOptions--}
```
public MhtSaveOptions()
```


Initializes a new instance of this class that can be used to save a MailMessage in the Mhtml format.

### getTimeoutReachedHandler() {#getTimeoutReachedHandler--}
```
public final TimeoutReachedHandler getTimeoutReachedHandler()
```


Raised if timed out while saving to Mhtml.

**Returns:**
[TimeoutReachedHandler](../../com.aspose.email/timeoutreachedhandler)
### setTimeoutReachedHandler(TimeoutReachedHandler value) {#setTimeoutReachedHandler-com.aspose.email.TimeoutReachedHandler-}
```
public final void setTimeoutReachedHandler(TimeoutReachedHandler value)
```


Raised if timed out while saving to Mhtml.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeoutReachedHandler](../../com.aspose.email/timeoutreachedhandler) |  |

### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Limits the time in milliseconds of formatting message while saving in Mht. Default value 3 sek.

**Returns:**
int
### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


Limits the time in milliseconds of formatting message while saving in Mht. Default value 3 sek.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMhtFormatOptions() {#getMhtFormatOptions--}
```
public final int getMhtFormatOptions()
```


Defines additional options when saving in MHTML format. Default value is MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments.

**Returns:**
int
### setMhtFormatOptions(int value) {#setMhtFormatOptions-int-}
```
public final void setMhtFormatOptions(int value)
```


Defines additional options when saving in MHTML format. Default value is MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPreserveOriginalBoundaries() {#getPreserveOriginalBoundaries--}
```
public final boolean getPreserveOriginalBoundaries()
```


Defines whether need keep original boundaries in mail message when saving or not.

**Returns:**
boolean
### setPreserveOriginalBoundaries(boolean value) {#setPreserveOriginalBoundaries-boolean-}
```
public final void setPreserveOriginalBoundaries(boolean value)
```


Defines whether need keep original boundaries in mail message when saving or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCheckBodyContentEncoding() {#getCheckBodyContentEncoding--}
```
public final boolean getCheckBodyContentEncoding()
```


Defines whether need check message body content encoding when saving. By default the value is false.

--------------------

If true, it will be check whether the  MailMessage.HtmlBody ([MailMessage.getHtmlBody](../../com.aspose.email/mailmessage\#getHtmlBody)/[MailMessage.setHtmlBody(String)](../../com.aspose.email/mailmessage\#setHtmlBody-String-)) content encoding matches to the encoding specified by the  MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) property. If the HtmlBody content encoding doesn't match BodyEncoding property, the  MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) and  MailMessage.PreferredTextEncoding ([MailMessage.getPreferredTextEncoding](../../com.aspose.email/mailmessage\#getPreferredTextEncoding)/[MailMessage.setPreferredTextEncoding(Encoding)](../../com.aspose.email/mailmessage\#setPreferredTextEncoding-Encoding-)) properties will be changed to default  System.Text.Encoding.UTF8 (java.nio.charset.Charset\#getUTF8.getUTF8).

**Returns:**
boolean
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

### getSaveAttachments() {#getSaveAttachments--}
```
public final boolean getSaveAttachments()
```


Gets or sets a value indicating whether to save attachments.

Value:  true  if attachments should be saved; otherwise,  false .

**Returns:**
boolean
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

### getPreserveOriginalDate() {#getPreserveOriginalDate--}
```
public final boolean getPreserveOriginalDate()
```


Defines whether need keep original date in mail message when saving or not. Default value is true.

**Returns:**
boolean
### setPreserveOriginalDate(boolean value) {#setPreserveOriginalDate-boolean-}
```
public final void setPreserveOriginalDate(boolean value)
```


Defines whether need keep original date in mail message when saving or not. Default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSkipInlineImages() {#getSkipInlineImages--}
```
public final boolean getSkipInlineImages()
```


Defines whether skip references on images at saving in mhtml or not. Default value is false.

**Returns:**
boolean
### setSkipInlineImages(boolean value) {#setSkipInlineImages-boolean-}
```
public final void setSkipInlineImages(boolean value)
```


Defines whether skip references on images at saving in mhtml or not. Default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

