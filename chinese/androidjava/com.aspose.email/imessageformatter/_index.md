---
title: IMessageFormatter
second_title: Aspose.Email for Android via Java API 参考
description: 提供检索用于消息格式化的对象的机制。
type: docs
weight: 460
url: /zh/androidjava/com.aspose.email/imessageformatter/
---
```
public interface IMessageFormatter
```

提供检索用于消息格式化的对象的机制。
## 方法

| 方法 | 描述 |
| --- | --- |
| [format(MailMessage message)](#format-com.aspose.email.MailMessage-) | 格式化指定的消息。 |
| [getFormatTemplates()](#getFormatTemplates--) | 获取格式模板。 |
### format(MailMessage message) {#format-com.aspose.email.MailMessage-}
```
public abstract void format(MailMessage message)
```


格式化指定的消息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | 消息。 |

### getFormatTemplates() {#getFormatTemplates--}
```
public abstract System.Collections.Specialized.StringDictionary getFormatTemplates()
```


获取格式模板。

值：格式模板。

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringDictionary
