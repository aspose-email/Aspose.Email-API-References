---
title: TrainFilter
second_title: Aspose.Email for .NET API 参考
description: 从指定的邮件中学习来自垃圾邮件或非垃圾邮件来源
type: docs
weight: 60
url: /zh/net/aspose.email.antispam/spamanalyzer/trainfilter/
---
## TrainFilter(MailMessage[], MailMessage[]) {#trainfilter_1}

从指定的邮件中学习来自垃圾邮件或非垃圾邮件来源。

```csharp
public void TrainFilter(MailMessage[] ham, MailMessage[] spam)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ham | MailMessage[] | 用于训练贝叶斯过滤器的非垃圾邮件对象数组。 |
| spam | MailMessage[] | MailMessage 对象数组，用于训练贝叶斯过滤器的垃圾邮件。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 如果*ham*或*spam*为空。 |

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SpamAnalyzer](../../spamanalyzer)
* 命名空间 [Aspose.Email.AntiSpam](../../spamanalyzer)
* 部件 [Aspose.Email](../../../)

---

## TrainFilter(MailMessage, bool) {#trainfilter}

从指定的邮件中学习来自垃圾邮件或非垃圾邮件来源。

```csharp
public void TrainFilter(MailMessage message, bool isSpam)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| message | MailMessage | MailMessage 对象的引用，表示训练贝叶斯过滤器的消息。 |
| isSpam | Boolean | 如果邮件是垃圾邮件则为真；如果是合法消息，则为 false。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 如果*message*为空。 |

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SpamAnalyzer](../../spamanalyzer)
* 命名空间 [Aspose.Email.AntiSpam](../../spamanalyzer)
* 部件 [Aspose.Email](../../../)

---

## TrainFilter(string, bool) {#trainfilter_2}

从指定的字符串中学习来自垃圾邮件或非垃圾邮件源。

```csharp
public void TrainFilter(string text, bool isSpam)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 用于训练贝叶斯过滤器的字符串值。 |
| isSpam | Boolean | 如果指定的文本是垃圾邮件，则为真；如果它是合法文本，则为 false。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 如果*text*为空。 |

### 也可以看看

* class [SpamAnalyzer](../../spamanalyzer)
* 命名空间 [Aspose.Email.AntiSpam](../../spamanalyzer)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->