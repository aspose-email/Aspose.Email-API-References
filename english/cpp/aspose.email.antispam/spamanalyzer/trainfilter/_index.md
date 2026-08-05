---
title: "Aspose::Email::AntiSpam::SpamAnalyzer::TrainFilter method"
linktitle: "TrainFilter"
articleTitle: "TrainFilter"
second_title: "Aspose.Email for C++"
description: "Learns from the specified messages as from spam or non-spam source."
type: docs
weight: 60
url: /cpp/aspose.email.antispam/spamanalyzer/trainfilter/
---

## TrainFilter (1 of 3) {#trainfilter_1}

Learns from the specified messages as from spam or non-spam source.

**Returns:** void Aspose::Email::AntiSpam::

```cpp
TrainFilter(System::ArrayPtr< System::SharedPtr < MailMessage >> ham, System::ArrayPtr< System::SharedPtr < MailMessage >> spam)
```

| Parameter | Description |
| --- | --- |
| ham | The array of MailMessage objects that is non-spam for training the Bayesian filter. |
| spam | The array of MailMessage objects that is spam for training the Bayesian filter. |

---

## TrainFilter (2 of 3) {#trainfilter_2}

Learns from the specified message as from spam or non-spam source.

**Returns:** void Aspose::Email::AntiSpam::

```cpp
TrainFilter(System::SharedPtr < MailMessage > message, bool isSpam)
```

| Parameter | Description |
| --- | --- |
| message | A reference to the MailMessage object representing the message to train the Bayesian filter. |
| isSpam | True if the message is a spam; false if it's a legitimate message. |

---

## TrainFilter (3 of 3) {#trainfilter_3}

Learns from the specified string as from spam or non-spam source.

**Returns:** void Aspose::Email::AntiSpam::

```cpp
TrainFilter(System::String text, bool isSpam)
```

| Parameter | Description |
| --- | --- |
| text | A string value to train the Bayesian filter. |
| isSpam | True if specified text is a spam; false if it's a legitimate text. |

