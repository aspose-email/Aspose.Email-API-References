---
title: Class SpamAnalyzer
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.AntiSpam.SpamAnalyzer class. Class which allows applications to detect spam emails with selflearning Bayesian filter
type: docs
weight: 250
url: /net/aspose.email.antispam/spamanalyzer/
---
## SpamAnalyzer class

Class which allows applications to detect spam e-mails with self-learning Bayesian filter.

```csharp
public class SpamAnalyzer
```

## Constructors

| Name | Description |
| --- | --- |
| [SpamAnalyzer](spamanalyzer/#constructor)() | Initialize a new instance of the `SpamAnalyzer` class. |
| [SpamAnalyzer](spamanalyzer/#constructor_1)(Stream) | Initialize a new instance of the `SpamAnalyzer` class. |
| [SpamAnalyzer](spamanalyzer/#constructor_2)(string) | Initialize a new instance of the `SpamAnalyzer` class. |

## Methods

| Name | Description |
| --- | --- |
| [LoadDatabase](../../aspose.email.antispam/spamanalyzer/loaddatabase/#loaddatabase)(Stream) | Loads Bayesian database from stream. |
| [LoadDatabase](../../aspose.email.antispam/spamanalyzer/loaddatabase/#loaddatabase_1)(string) | Loads Bayesian database from file. |
| [Reset](../../aspose.email.antispam/spamanalyzer/reset/)() | Clears all statistics (Bayesian database). |
| [SaveDatabase](../../aspose.email.antispam/spamanalyzer/savedatabase/#savedatabase)(Stream) | Saves the Bayesian database to stream. |
| [SaveDatabase](../../aspose.email.antispam/spamanalyzer/savedatabase/#savedatabase_1)(string) | Saves the Bayesian database to file. |
| [Test](../../aspose.email.antispam/spamanalyzer/test/)(MailMessage) | Analyses the message and returns the probability of the message being spam. |
| [TrainFilter](../../aspose.email.antispam/spamanalyzer/trainfilter/#trainfilter)(MailMessage, bool) | Learns from the specified message as from spam or non-spam source. |
| [TrainFilter](../../aspose.email.antispam/spamanalyzer/trainfilter/#trainfilter_1)(MailMessage[], MailMessage[]) | Learns from the specified messages as from spam or non-spam source. |
| [TrainFilter](../../aspose.email.antispam/spamanalyzer/trainfilter/#trainfilter_2)(string, bool) | Learns from the specified string as from spam or non-spam source. |

### See Also

* namespace [Aspose.Email.AntiSpam](../../aspose.email.antispam/)
* assembly [Aspose.Email](../../)


