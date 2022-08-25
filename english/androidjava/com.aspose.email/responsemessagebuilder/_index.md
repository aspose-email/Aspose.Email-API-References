---
title: ResponseMessageBuilder
second_title: Aspose.Email for Android via Java API Reference
description:  Provides creation and formatting the forwarding and replying messages.
type: docs
weight: 373
url: /java/com.aspose.email/responsemessagebuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ResponseMessageBuilder
```

Provides creation and formatting the forwarding and replying messages.
## Constructors

| Constructor | Description |
| --- | --- |
| [ResponseMessageBuilder()](#ResponseMessageBuilder--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAdditionMode()](#getAdditionMode--) | Gets or sets the format of response message. |
| [setAdditionMode(int value)](#setAdditionMode-int-) | Gets or sets the format of response message. |
| [getSender()](#getSender--) | Gets or sets the addres from which the response message will be sent. |
| [setSender(MailAddress value)](#setSender-com.aspose.email.MailAddress-) | Gets or sets the addres from which the response message will be sent. |
| [getResponseText()](#getResponseText--) | Gets or sets the body of response message. |
| [setResponseText(String value)](#setResponseText-java.lang.String-) | Gets or sets the body of response message. |
| [buildResponse(MailMessage msg)](#buildResponse-com.aspose.email.MailMessage-) | Builds the forwarding and replying messages. |
| [buildResponse(MapiMessage msg)](#buildResponse-com.aspose.email.MapiMessage-) | Builds the forwarding and replying messages. |
### ResponseMessageBuilder() {#ResponseMessageBuilder--}
```
public ResponseMessageBuilder()
```


### getAdditionMode() {#getAdditionMode--}
```
public final int getAdditionMode()
```


Gets or sets the format of response message.

**Returns:**
int
### setAdditionMode(int value) {#setAdditionMode-int-}
```
public final void setAdditionMode(int value)
```


Gets or sets the format of response message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSender() {#getSender--}
```
public final MailAddress getSender()
```


Gets or sets the addres from which the response message will be sent.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### setSender(MailAddress value) {#setSender-com.aspose.email.MailAddress-}
```
public final void setSender(MailAddress value)
```


Gets or sets the addres from which the response message will be sent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### getResponseText() {#getResponseText--}
```
public final String getResponseText()
```


Gets or sets the body of response message.

--------------------

Can contain html tags or rtf keywords if type of body of original message is HTML or RTF respectively.

**Returns:**
java.lang.String
### setResponseText(String value) {#setResponseText-java.lang.String-}
```
public final void setResponseText(String value)
```


Gets or sets the body of response message.

--------------------

Can contain html tags or rtf keywords if type of body of original message is HTML or RTF respectively.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### buildResponse(MailMessage msg) {#buildResponse-com.aspose.email.MailMessage-}
```
public abstract MailMessage buildResponse(MailMessage msg)
```


Builds the forwarding and replying messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MailMessage](../../com.aspose.email/mailmessage) | Original message [MailMessage](../../com.aspose.email/mailmessage). |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Resultant message [MailMessage](../../com.aspose.email/mailmessage).
### buildResponse(MapiMessage msg) {#buildResponse-com.aspose.email.MapiMessage-}
```
public abstract MapiMessage buildResponse(MapiMessage msg)
```


Builds the forwarding and replying messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | Original message [MapiMessage](../../com.aspose.email/mapimessage). |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Resultant message [MapiMessage](../../com.aspose.email/mapimessage).
