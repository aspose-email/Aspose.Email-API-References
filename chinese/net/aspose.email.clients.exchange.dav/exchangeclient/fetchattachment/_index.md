---
title: FetchAttachment
second_title: Aspose.Email for .NET API 参考
description: 获取附件
type: docs
weight: 160
url: /zh/net/aspose.email.clients.exchange.dav/exchangeclient/fetchattachment/
---
## ExchangeClient.FetchAttachment method

获取附件

```csharp
public Attachment FetchAttachment(string attachmentUri)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| attachmentUri | String | 附件 uri。 （附件 uri 可以使用 ListMessages(folder, ExchangeListMessagesOptions.FetchAttachmentInformation) 方法检索） |

### 返回值

[`Attachment`](../../../aspose.email/attachment)那表示获取的附件

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| Email。AsposeArgumentException | *attachmentUri*为空或为空 |

### 也可以看看

* class [Attachment](../../../aspose.email/attachment)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->