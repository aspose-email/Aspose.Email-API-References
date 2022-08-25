---
title: AmpMessage
second_title: Aspose.Email for Android via Java API Reference
description:  Message which allows senders to include AMP components inside emails.
type: docs
weight: 22
url: /java/com.aspose.email/ampmessage/
---
**Inheritance:**
java.lang.Object, com.aspose.email.IPreferredTextEncodingProviderInternal, [com.aspose.email.MailMessage](../../com.aspose.email/mailmessage)
```
public class AmpMessage extends MailMessage
```

Message which allows senders to include AMP components inside emails.
## Constructors

| Constructor | Description |
| --- | --- |
| [AmpMessage()](#AmpMessage--) | Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class |
## Methods

| Method | Description |
| --- | --- |
| [getAmpHtmlBody()](#getAmpHtmlBody--) | Gets the AmpHtml representation of message's body. |
| [setAmpHtmlBody(String value)](#setAmpHtmlBody-java.lang.String-) | Gets the AmpHtml representation of message's body. |
| [addAmpComponent(AmpComponent component)](#addAmpComponent-com.aspose.email.AmpComponent-) | Add Amp component to this message. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.email.SaveOptions-) | Save message as a stream |
### AmpMessage() {#AmpMessage--}
```
public AmpMessage()
```


Initializes a new instance of the [MailMessage](../../com.aspose.email/mailmessage) class

### getAmpHtmlBody() {#getAmpHtmlBody--}
```
public String getAmpHtmlBody()
```


Gets the AmpHtml representation of message's body.

**Returns:**
java.lang.String
### setAmpHtmlBody(String value) {#setAmpHtmlBody-java.lang.String-}
```
public void setAmpHtmlBody(String value)
```


Gets the AmpHtml representation of message's body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### addAmpComponent(AmpComponent component) {#addAmpComponent-com.aspose.email.AmpComponent-}
```
public final void addAmpComponent(AmpComponent component)
```


Add Amp component to this message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| component | [AmpComponent](../../com.aspose.email/ampcomponent) |  |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.email.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


Save message as a stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream into which message is saved |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | Additional options for saving[SaveOptions](../../com.aspose.email/saveoptions). |

