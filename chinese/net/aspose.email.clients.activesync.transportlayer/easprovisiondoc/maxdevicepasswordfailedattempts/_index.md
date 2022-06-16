---
title: MaxDevicePasswordFailedAttempts
second_title: Aspose.Email for .NET API 参考
description: 指定允许的最大失败密码登录尝试次数 如果达到最大失败密码登录尝试次数客户端应该执行本地擦除或进入超时锁定模式 MaxDevicePasswordFailedAttempts 可以为 null 或具有 4 到 16 范围内的值 如果该属性为 null则客户端将其解释为没有最大失败密码次数登录尝试已由安全策略设置 如果 DevicePasswordEnabled 的值设置为 FALSE则客户端忽略此属性
type: docs
weight: 280
url: /zh/net/aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxdevicepasswordfailedattempts/
---
## EASProvisionDoc.MaxDevicePasswordFailedAttempts property

指定允许的最大失败密码登录尝试次数。 如果达到最大失败密码登录尝试次数，客户端应该执行本地擦除或进入超时锁定模式。 MaxDevicePasswordFailedAttempts 可以为 null 或具有 4 到 16 范围内的值。 如果该属性为 null，则客户端将其解释为没有最大失败密码次数登录尝试已由安全策略设置。 如果 DevicePasswordEnabled 的值设置为 FALSE，则客户端忽略此属性。

```csharp
public int? MaxDevicePasswordFailedAttempts { get; set; }
```

### 也可以看看

* class [EASProvisionDoc](../../easprovisiondoc)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../easprovisiondoc)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->