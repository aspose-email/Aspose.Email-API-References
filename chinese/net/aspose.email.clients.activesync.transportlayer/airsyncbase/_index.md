---
title: AirSyncBase
second_title: Aspose.Email for .NET API 参考
description: ActiveSync 协议的 AirSyncBase 命名空间
type: docs
weight: 970
url: /zh/net/aspose.email.clients.activesync.transportlayer/airsyncbase/
---
## AirSyncBase enumeration

ActiveSync 协议的 AirSyncBase 命名空间

```csharp
public enum AirSyncBase
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| BodyPreference | `5` | 设置与搜索、同步或获取返回的信息的类型和大小相关的首选项信息的元素集合。 |
| Type | `6` | 项目正文内容的首选格式类型。 |
| TruncationSize | `7` | 指定客户端想要搜索、同步或获取的内容的大小（以字节为单位）。 |
| AllOrNone | `8` | 指定是否基于 TruncationSize 元素搜索、同步或检索全部内容或不检索任何内容。 |
| Body | `10` | 元素的集合，指定与服务器上存储的项目关联的自由格式、可变长度的数据字段。 |
| Data | `11` | 日历项目、联系人、文档、电子邮件或任务的正文。 |
| EstimatedDataSize | `12` | 与项目的 Body 元素关联的数据大小的信息估计。 |
| Truncated | `13` | 指定是否根据客户端指示的 BodyPartPreference 元素截断项目的主体。 |
| Attachments | `14` | 包含一个或多个附件项的元素集合。 |
| Attachment | `15` | 指定单个附件项的附件信息。 |
| DisplayName | `16` | 附件的显示名称。 |
| FileReference | `17` | 服务器分配给消息的每个附件的唯一标识符。 |
| Method | `18` | 标识附加附件的方法。 |
| ContentId | `19` | 包含附件的唯一对象 ID。 |
| ContentLocation | `20` | 包含附件的相对 URI，用于将 HTML 消息中对内联附件的引用与附件表中的附件相匹配。 |
| IsInline | `21` | 指定附件是否嵌入到邮件中。 |
| NativeBodyType | `22` | 项目的原始格式类型。 |
| ContentType | `23` | 内容类型 |
| Preview | `24` | 要返回给客户端的消息预览的首选长度。 |
| BodyPartPreference | `25` | 一组元素，用于设置与搜索、同步或获取 BodyPart 返回的信息的类型和大小相关的首选项信息。 |
| BodyPart | `26` | 包含电子邮件正文的消息部分的元素集合。 |
| Status | `27` | BodyPart 响应中数据元素的状态。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->