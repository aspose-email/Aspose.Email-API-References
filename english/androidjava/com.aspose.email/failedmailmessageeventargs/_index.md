---
title: FailedMailMessageEventArgs
second_title: Aspose.Email for Android via Java API Reference
description:  Provides data for the MessageSending and MessageSent events.
type: docs
weight: 129
url: /java/com.aspose.email/failedmailmessageeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.aspose.email.MailMessageEventArgs](../../com.aspose.email/mailmessageeventargs)
```
public class FailedMailMessageEventArgs extends MailMessageEventArgs
```

Provides data for the MessageSending and MessageSent events.
## Constructors

| Constructor | Description |
| --- | --- |
| [FailedMailMessageEventArgs(MailMessage message, Throwable ex)](#FailedMailMessageEventArgs-com.aspose.email.MailMessage-java.lang.Throwable-) | Initializes a new instance of the [FailedMailMessageEventArgs](../../com.aspose.email/failedmailmessageeventargs) class. |
## Methods

| Method | Description |
| --- | --- |
| [getOperationError()](#getOperationError--) | Operation error |
### FailedMailMessageEventArgs(MailMessage message, Throwable ex) {#FailedMailMessageEventArgs-com.aspose.email.MailMessage-java.lang.Throwable-}
```
public FailedMailMessageEventArgs(MailMessage message, Throwable ex)
```


Initializes a new instance of the [FailedMailMessageEventArgs](../../com.aspose.email/failedmailmessageeventargs) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message. |
| ex | java.lang.Throwable | Operation error |

### getOperationError() {#getOperationError--}
```
public final Throwable getOperationError()
```


Operation error

**Returns:**
java.lang.Throwable
