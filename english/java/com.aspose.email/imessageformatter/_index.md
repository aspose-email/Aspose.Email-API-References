---
title: IMessageFormatter
second_title: Aspose.Email for Java API Reference
description: Formats a message for example by writing its headers into the body before it is saved.
type: docs
weight: 799
url: /java/com.aspose.email/imessageformatter/
---
```
public interface IMessageFormatter
```

Formats a message, for example by writing its headers into the body before it is saved.
## Methods

| Method | Description |
| --- | --- |
| [format(MailMessage message)](#format-com.aspose.email.MailMessage-) | Formats the message. |
| [getFormatTemplates()](#getFormatTemplates--) | Gets the formats of the individual headers. |
### format(MailMessage message) {#format-com.aspose.email.MailMessage-}
```
public abstract void format(MailMessage message)
```


Formats the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message to format. |

### getFormatTemplates() {#getFormatTemplates--}
```
public abstract System.Collections.Specialized.StringDictionary getFormatTemplates()
```


Gets the formats of the individual headers.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringDictionary - The format templates.
