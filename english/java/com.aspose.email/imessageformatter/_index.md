---
title: IMessageFormatter
second_title: Aspose.Email for Java API Reference
description: Provides a mechanism for retrieving an object to Message formatting.
type: docs
weight: 755
url: /java/com.aspose.email/imessageformatter/
---
```
public interface IMessageFormatter
```

Provides a mechanism for retrieving an object to Message formatting.
## Methods

| Method | Description |
| --- | --- |
| [format(MailMessage message)](#format-com.aspose.email.MailMessage-) | Formats the specified message. |
| [getFormatTemplates()](#getFormatTemplates--) | Gets the format templates. |
### format(MailMessage message) {#format-com.aspose.email.MailMessage-}
```
public abstract void format(MailMessage message)
```


Formats the specified message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message. |

### getFormatTemplates() {#getFormatTemplates--}
```
public abstract System.Collections.Specialized.StringDictionary getFormatTemplates()
```


Gets the format templates.

Value: The format templates.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringDictionary
