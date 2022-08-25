---
title: MailMessageEventArgs
second_title: Aspose.Email for Java API Reference
description:  Provides data for the MessageSending and MessageSent events.
type: docs
weight: 370
url: /java/com.aspose.email/mailmessageeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class MailMessageEventArgs extends System.EventArgs
```

Provides data for the MessageSending and MessageSent events.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailMessageEventArgs(MailMessage message)](#MailMessageEventArgs-com.aspose.email.MailMessage-) | Initializes a new instance of the [MailMessageEventArgs](../../com.aspose.email/mailmessageeventargs) class. |
## Methods

| Method | Description |
| --- | --- |
| [getMessage()](#getMessage--) | Gets the sending message. |
### MailMessageEventArgs(MailMessage message) {#MailMessageEventArgs-com.aspose.email.MailMessage-}
```
public MailMessageEventArgs(MailMessage message)
```


Initializes a new instance of the [MailMessageEventArgs](../../com.aspose.email/mailmessageeventargs) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message. |

### getMessage() {#getMessage--}
```
public final MailMessage getMessage()
```


Gets the sending message.

Value: The MailMessage.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
