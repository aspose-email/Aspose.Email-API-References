---
title: SpamAnalyzer.Test
second_title: Aspose.Email for .NET API Reference
description: SpamAnalyzer method. Analyses the message and returns the probability of the message being spam
type: docs
weight: 50
url: /net/aspose.email.antispam/spamanalyzer/test/
---
## SpamAnalyzer.Test method

Analyses the message and returns the probability of the message being spam.

```csharp
public double Test(MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | MailMessage for test the probability of the message being spam. |

### Return Value

A double value in 0-1 range, where 0 corresponds to "definitely non-spam" (0% spam probability) and 1 corresponds to "definitely spam" (100% spam probability).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *message* is null. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SpamAnalyzer](../)
* namespace [Aspose.Email.AntiSpam](../../spamanalyzer/)
* assembly [Aspose.Email](../../../)


