---
title: SpamAnalyzer.TrainFilter
second_title: Aspose.Email for .NET API Reference
description: SpamAnalyzer method. Learns from the specified messages as from spam or nonspam source
type: docs
weight: 60
url: /net/aspose.email.antispam/spamanalyzer/trainfilter/
---
## TrainFilter(MailMessage[], MailMessage[]) {#trainfilter_1}

Learns from the specified messages as from spam or non-spam source.

```csharp
public void TrainFilter(MailMessage[] ham, MailMessage[] spam)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ham | MailMessage[] | The array of MailMessage objects that is non-spam for training the Bayesian filter. |
| spam | MailMessage[] | The array of MailMessage objects that is spam for training the Bayesian filter. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *ham* or *spam* is null. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SpamAnalyzer](../)
* namespace [Aspose.Email.AntiSpam](../../spamanalyzer/)
* assembly [Aspose.Email](../../../)

---

## TrainFilter(MailMessage, bool) {#trainfilter}

Learns from the specified message as from spam or non-spam source.

```csharp
public void TrainFilter(MailMessage message, bool isSpam)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | A reference to the MailMessage object representing the message to train the Bayesian filter. |
| isSpam | Boolean | True if the message is a spam; false if it's a legitimate message. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *message* is null. |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [SpamAnalyzer](../)
* namespace [Aspose.Email.AntiSpam](../../spamanalyzer/)
* assembly [Aspose.Email](../../../)

---

## TrainFilter(string, bool) {#trainfilter_2}

Learns from the specified string as from spam or non-spam source.

```csharp
public void TrainFilter(string text, bool isSpam)
```

| Parameter | Type | Description |
| --- | --- | --- |
| text | String | A string value to train the Bayesian filter. |
| isSpam | Boolean | True if specified text is a spam; false if it's a legitimate text. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *text* is null. |

### See Also

* class [SpamAnalyzer](../)
* namespace [Aspose.Email.AntiSpam](../../spamanalyzer/)
* assembly [Aspose.Email](../../../)


