---
title: LoadOptions
second_title: Aspose.Email for .NET API 参考
description: 这是类的抽象基类允许用户在从特定格式加载 MailMessage 时指定其他选项
type: docs
weight: 17670
url: /zh/net/aspose.email/loadoptions/
---
## LoadOptions class

这是类的抽象基类，允许用户在从特定格式加载 MailMessage 时指定其他选项。

```csharp
public abstract class LoadOptions
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [MessageFormat](../../aspose.email/loadoptions/messageformat) { get; } | 表示邮件消息格式。可以是eml,msg 或mhtml 格式。 默认值为 Eml。 |
| [PrefferedTextEncoding](../../aspose.email/loadoptions/prefferedtextencoding) { get; set; } | 获取或设置消息的首选编码。 强制设置消息主题和正文的首选编码。 默认值为空。 |
| [PreserveEmbeddedMessageFormat](../../aspose.email/loadoptions/preserveembeddedmessageformat) { get; set; } | 获取或设置一个值，该值指示在 MailMessage 中加载时是否需要保留 嵌入消息的格式。 |

### 也可以看看

* 命名空间 [Aspose.Email](../../aspose.email)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->