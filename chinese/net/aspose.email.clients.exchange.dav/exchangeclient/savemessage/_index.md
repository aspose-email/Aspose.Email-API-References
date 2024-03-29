---
title: SaveMessage
second_title: Aspose.Email for .NET API 参考
description: 将 uri 指定的邮件消息保存到本地文件系统邮件消息文件是符合 RFC 822 的格式 EML 如果要解析邮件消息文件请使用MailMessageaspose.email/mailmessage.
type: docs
weight: 360
url: /zh/net/aspose.email.clients.exchange.dav/exchangeclient/savemessage/
---
## SaveMessage(string, string) {#savemessage_1}

将 uri 指定的邮件消息保存到本地文件系统。邮件消息文件是符合 RFC 822 的格式 (EML)。 如果要解析邮件消息文件，请使用[`MailMessage`](../../../aspose.email/mailmessage).

```csharp
public void SaveMessage(string messageUri, string path)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageUri | String | 邮件消息的 Uri |
| path | String | 保存消息的目标路径 |

### 也可以看看

* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## SaveMessage(string, Stream) {#savemessage}

保存消息。

```csharp
public void SaveMessage(string messageUri, Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| messageUri | String | 消息 URI。 |
| stream | Stream | 流。 |

### 也可以看看

* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
