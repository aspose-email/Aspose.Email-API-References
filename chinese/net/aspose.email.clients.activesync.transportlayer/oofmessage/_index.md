---
title: OOFMessage
second_title: Aspose.Email for .NET API 参考
description: 为特定受众指定 OOF 消息 Exchange 2007Exchange 2010 和 Exchange 2013 要求未知外部受众和已知外部受众的回复消息相同 该属性支持 OOF 消息的以下三种受众 内部 - 与发送用户在同一组织中的用户 已知外部 - 在发送用户的组织之外但在发送用户的联系人中表示的用户 未知外部 - 在发送用户的组织之外的用户组织并且不在发送用户的联系人中表示
type: docs
weight: 1610
url: /zh/net/aspose.email.clients.activesync.transportlayer/oofmessage/
---
## OOFMessage class

为特定受众指定 OOF 消息。 Exchange 2007、Exchange 2010 和 Exchange 2013 要求未知外部受众和已知外部受众的回复消息相同。 该属性支持 OOF 消息的以下三种受众： 内部 - 与发送用户在同一组织中的用户。 已知外部 - 在发送用户的组织之外但在发送用户的联系人中表示的用户。 未知外部 - 在发送用户的组织之外的用户组织并且不在发送用户的联系人中表示。

```csharp
public class OOFMessage
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [OOFMessage](oofmessage)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AppliesToExternalKnown](../../aspose.email.clients.activesync.transportlayer/oofmessage/appliestoexternalknown) { get; set; } | 表示 OOF 消息适用于已知的外部用户。 |
| [AppliesToExternalUnknown](../../aspose.email.clients.activesync.transportlayer/oofmessage/appliestoexternalunknown) { get; set; } | 表示OOF消息适用于未知的外部用户。 |
| [AppliesToInternal](../../aspose.email.clients.activesync.transportlayer/oofmessage/appliestointernal) { get; set; } | 表示OOF消息适用于内部用户。 |
| [BodyType](../../aspose.email.clients.activesync.transportlayer/oofmessage/bodytype) { get; set; } | 指定 OOF 消息的格式。 以下是 BodyType 元素的允许值： - Text - HTML |
| [Enabled](../../aspose.email.clients.activesync.transportlayer/oofmessage/enabled) { get; set; } | 指定在发送用户为 OOF 时是否向此受众发送 OOF 消息。 |
| [ReplyMessage](../../aspose.email.clients.activesync.transportlayer/oofmessage/replymessage) { get; set; } | 指定当用户为 OOF 时要向特定受众显示的消息。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
