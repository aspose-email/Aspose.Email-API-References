---
title: ReplyMessageBuilder
second_title: Aspose.Email for Android via Java API Reference
description:  Provides creation and formatting the replying messages.
type: docs
weight: 369
url: /java/com.aspose.email/replymessagebuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.ResponseMessageBuilder](../../com.aspose.email/responsemessagebuilder)
```
public class ReplyMessageBuilder extends ResponseMessageBuilder
```

Provides creation and formatting the replying messages.
## Constructors

| Constructor | Description |
| --- | --- |
| [ReplyMessageBuilder()](#ReplyMessageBuilder--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getReplyAll()](#getReplyAll--) | Provides automatic adding recipients in replying message. |
| [setReplyAll(boolean value)](#setReplyAll-boolean-) | Provides automatic adding recipients in replying message. |
| [buildResponse(MailMessage msg)](#buildResponse-com.aspose.email.MailMessage-) | Builds the replying messages. |
| [buildResponse(MapiMessage msg)](#buildResponse-com.aspose.email.MapiMessage-) | Builds the replying messages. |
### ReplyMessageBuilder() {#ReplyMessageBuilder--}
```
public ReplyMessageBuilder()
```


### getReplyAll() {#getReplyAll--}
```
public final boolean getReplyAll()
```


Provides automatic adding recipients in replying message.

**Returns:**
boolean
### setReplyAll(boolean value) {#setReplyAll-boolean-}
```
public final void setReplyAll(boolean value)
```


Provides automatic adding recipients in replying message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### buildResponse(MailMessage msg) {#buildResponse-com.aspose.email.MailMessage-}
```
public MailMessage buildResponse(MailMessage msg)
```


Builds the replying messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MailMessage](../../com.aspose.email/mailmessage) | Original message [MailMessage](../../com.aspose.email/mailmessage). |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Resultant message [MailMessage](../../com.aspose.email/mailmessage).
### buildResponse(MapiMessage msg) {#buildResponse-com.aspose.email.MapiMessage-}
```
public MapiMessage buildResponse(MapiMessage msg)
```


Builds the replying messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msg | [MapiMessage](../../com.aspose.email/mapimessage) | Original message [MapiMessage](../../com.aspose.email/mapimessage). |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Resultant message [MapiMessage](../../com.aspose.email/mapimessage).
