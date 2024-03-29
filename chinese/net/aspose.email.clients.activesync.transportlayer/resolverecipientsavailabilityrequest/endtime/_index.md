---
title: EndTime
second_title: Aspose.Email for .NET API 参考
description: 标识客户端请求的空闲/忙碌时间跨度的结束 协议版本为 12.1 时不支持 EndTime 如果客户端发送无效的 EndTime 值则服务器在ResolveRecipients 命令响应 如果可用性请求中未包含 EndTime则服务器使用 StartTime 值后 7 天的默认结束时间值 如果请求中指定的 EndTime 值小于 StartTime 值加上 30 分钟或者 StartTime 值和 EndTime 值跨越的持续时间大于特定天数则服务器在ResolveRecipients 命令响应 Exchange 2010 和 Exchange 2013 使用 42 天 Exchange 2007 SP1 使用 62 天
type: docs
weight: 20
url: /zh/net/aspose.email.clients.activesync.transportlayer/resolverecipientsavailabilityrequest/endtime/
---
## ResolveRecipientsAvailabilityRequest.EndTime property

标识客户端请求的空闲/忙碌时间跨度的结束。 协议版本为 12.1 时不支持 EndTime。 如果客户端发送无效的 EndTime 值，则服务器在ResolveRecipients 命令响应。 如果可用性请求中未包含 EndTime，则服务器使用 StartTime 值后 7 天的默认结束时间值。 如果请求中指定的 EndTime 值小于 StartTime 值加上 30 分钟，或者 StartTime 值和 EndTime 值跨越的持续时间大于特定天数，则服务器在ResolveRecipients 命令响应。 Exchange 2010 和 Exchange 2013 使用 42 天； Exchange 2007 SP1 使用 62 天。

```csharp
public List<DateTime> EndTime { get; set; }
```

### 也可以看看

* class [ResolveRecipientsAvailabilityRequest](../../resolverecipientsavailabilityrequest)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../resolverecipientsavailabilityrequest)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
