---
title: Settings
second_title: Aspose.Email for .NET API 参考
description: ActiveSync 协议的设置命名空间
type: docs
weight: 2050
url: /zh/net/aspose.email.clients.activesync.transportlayer/settings/
---
## Settings enumeration

ActiveSync 协议的设置命名空间

```csharp
public enum Settings
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Settings | `5` | 将 HTTP POST 的主体标识为包含设置命令（第 2.2.2.16 节）。 |
| Status | `6` | 表示操作的结果。 |
| Get | `7` | 在请求中，Get 元素使客户端能够从服务器检索信息设置。 在响应中，Get 元素包含从服务器检索的信息设置。 |
| Set | `8` | 在服务器上设置信息设置。 |
| Oof | `9` | 指定用于检索和设置外出 (OOF) 信息的命名属性节点。 |
| OofState | `10` | 指定 Oof 属性的可用性（第 2.2.3.112 节）。 |
| StartTime | `11` | 它与 EndTime 元素一起用于指定用户不在办公室的时间范围。 |
| EndTime | `12` | 它与 StartTime 元素一起用于指定用户不在办公室的时间范围。 |
| OofMessage | `13` | 为特定受众指定 OOF 消息。 |
| AppliesToInternal | `14` | 表示OOF消息适用于内部用户。 |
| AppliesToExternalKnown | `15` | 表示OOF消息适用于已知的外部用户。 |
| AppliesToExternalUnknown | `16` | 表示OOF消息适用于未知的外部用户。 |
| Enabled | `17` | 指定在发送用户为 OOF 时是否向此受众发送 OOF 消息。 |
| ReplyMessage | `18` | 指定当用户为 OOF 时要向特定受众显示的消息。 |
| BodyType | `19` | 指定 OOF 消息的格式。 |
| DevicePassword | `20` | 用于将客户端设备的恢复密码发送到服务器。 |
| Password | `21` | 指定客户端设备的恢复密码，由服务器存储。 |
| DeviceInformation | `22` | 用于将客户端设备的属性发送到服务器。 |
| Model | `23` | 指定通常描述客户端设备的名称。 |
| IMEI | `24` | 指定必须唯一标识设备的 15 个字符的代码。 |
| FriendlyName | `25` | 指定必须唯一描述客户端设备的名称。 |
| OS | `26` | 指定客户端设备的操作系统。 |
| OSLanguage | `27` | 指定客户端设备的操作系统使用的语言。 |
| PhoneNumber | `28` | 指定标识客户端设备的唯一编号。 |
| UserInformation | `29` | 用作容器节点，用于从服务器请求用户的电子邮件地址列表。 |
| EmailAddresses | `30` | 包含用户的一个或多个电子邮件地址。 |
| SMTPAddress | `31` | 指定用户的电子邮件地址之一。 |
| UserAgent | `32` | 指定用户代理。 |
| EnableOutboundSMS | `33` | 指定服务器是否将通过移动设备发送出站 SMS 消息。 |
| MobileOperator | `34` | 指定移动设备所连接的移动运营商的名称。 |
| PrimarySmtpAddress | `35` | 指定给定帐户的主 SMTP 地址。 |
| Accounts | `36` | 包含用户订阅的所有聚合帐户。 |
| Account | `37` | 包含与单个帐户关联的所有帐户信息。 |
| AccountId | `38` | 标识一个帐户。 |
| AccountName | `39` | 指定给定帐户的友好名称。 |
| UserDisplayName | `40` | 指定与给定帐户关联的用户的显示名称。 |
| SendDisabled | `41` | 指定客户端是否可以使用给定帐户发送消息。 |
| RightsManagementInformation | `43` | Settings 命令请求中，RightsManagementInformation 元素是一个容器节点，用于请求权限管理信息设置。 在设置命令响应中，RightsManagementInformation 元素是一个容器节点，其中包含从服务器检索的权限管理信息设置。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->