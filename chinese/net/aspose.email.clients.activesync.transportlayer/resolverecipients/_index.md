---
title: ResolveRecipients
second_title: Aspose.Email for .NET API 参考
description: ActiveSync 协议的 ResolveRecipients 命名空间
type: docs
weight: 1810
url: /zh/net/aspose.email.clients.activesync.transportlayer/resolverecipients/
---
## ResolveRecipients enumeration

ActiveSync 协议的 ResolveRecipients 命名空间

```csharp
public enum ResolveRecipients
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| ResolveRecipients | `5` | ResolveRecipients 元素是 ResolveRecipients 命令请求和响应中的必需元素，它将 HTTP POST 的正文标识为包含 ResolveRecipients 命令（第 2.2.2.13 节）。 |
| Response | `6` | 包含有关收件人是否已解析的信息。 |
| Status | `7` | 表示操作的结果。 |
| Type | `8` | 指示收件人的类型，联系人条目 (2) 或 GAL 条目 (1)。 |
| Recipient | `9` | 表示已解析的单个收件人。 |
| DisplayName | `10` | 包含收件人的显示名称。 |
| EmailAddress | `11` | 包含收件人的电子邮件地址，采用 SMTP 格式。 |
| Certificates | `12` | 包含有关收件人证书的信息。 |
| Certificate | `13` | 包含使用 base64 编码进行编码的 X509 证书二进制大对象 (BLOB)。 |
| MiniCertificate | `14` | 包含使用 base64 编码的迷你证书 BLOB。 |
| Options | `15` | 包含用于解析收件人列表的选项。 |
| To | `16` | 指定要解析的一个或多个收件人。 |
| CertificateRetrieval | `17` | 指定服务器是否应为每个已解析的收件人返回 S/MIME 证书。 |
| RecipientCount | `18` | 指定在 ResolveRecipients 命令响应中返回的收件人数。 |
| MaxCertificates | `19` | 限制服务器返回的证书总数。 |
| MaxAmbiguousRecipients | `20` | 限制为响应中每个不明确的接收节点返回的建议数。 |
| CertificateCount | `21` | 指定为收件人找到的有效证书的数量。 |
| Availability | `22` | 向服务器指示客户端正在请求空闲/忙碌数据，并标识要检索的空闲/忙碌数据的开始时间和结束时间。 |
| StartTime | `23` | 标识客户端请求的空闲/忙碌时间跨度的开始。 |
| EndTime | `24` | 标识客户端请求的空闲/忙碌时间跨度的结束。 |
| MergedFreeBusy | `25` | 指定请求中标识的用户或分发列表的忙/闲信息。 |
| Picture | `26` | 表示客户端请求在服务器响应中返回联系人照片。 |
| MaxSize | `27` | 限制服务器响应中返回的联系人照片的大小。 |
| Data | `28` | 包含联系人照片的二进制数据。 |
| MaxPictures | `29` | 限制服务器响应中返回的联系人照片数量。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
