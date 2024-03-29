---
title: BodyRtf
second_title: Aspose.Email for .NET API 参考
description: 获取或设置 RTF 格式的消息文本
type: docs
weight: 50
url: /zh/net/aspose.email.mapi/mapimessageitembase/bodyrtf/
---
## MapiMessageItemBase.BodyRtf property

获取或设置 RTF 格式的消息文本。

```csharp
public string BodyRtf { get; set; }
```

### 适当的价值

表示消息体 rtf 的字符串。

### 评论

设置值时，更新 PR_RTF_COMPRESSED、 PR_RTF_DECOMPRESSES、PR_BODY 属性的值。 设置的字符串值必须具有 RTF 格式。 因此，如果需要设置 HTML 格式的值， 该值必须首先在 RTF 中编码， 根据 RTF 扩展规范。 要快速设置 HTML 或纯文本格式的正文消息的内容， 请使用 SetBodyContent 方法。 设置空值或空字符串时， BodyRtf 和 Body 属性的值设置为空。

### 也可以看看

* class [MapiMessageItemBase](../../mapimessageitembase)
* 命名空间 [Aspose.Email.Mapi](../../mapimessageitembase)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
