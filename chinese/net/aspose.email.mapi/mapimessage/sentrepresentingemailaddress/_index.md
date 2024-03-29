---
title: SentRepresentingEmailAddress
second_title: Aspose.Email for .NET API 参考
description: 获取或设置发件人代表的消息传递用户的电子邮件地址
type: docs
weight: 270
url: /zh/net/aspose.email.mapi/mapimessage/sentrepresentingemailaddress/
---
## MapiMessage.SentRepresentingEmailAddress property

获取或设置发件人代表的消息传递用户的电子邮件地址。

```csharp
public string SentRepresentingEmailAddress { get; set; }
```

### 适当的价值

表示已发送的字符串，代表电子邮件地址。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果电子邮件地址不是可识别的格式，则抛出。 |

### 评论

设置值时，PR_SENT_REPRESENTING_SEARCH_KEY 和 PR_SENT_REPRESENTING_ENTRYID 属性的值也会更新。 设置空值或空字符串时，属性的值设置为空。

### 也可以看看

* class [MapiMessage](../../mapimessage)
* 命名空间 [Aspose.Email.Mapi](../../mapimessage)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
