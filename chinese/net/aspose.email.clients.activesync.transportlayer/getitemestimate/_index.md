---
title: GetItemEstimate
second_title: Aspose.Email for .NET API 参考
description: ActiveSync 协议的 GetItemEstimate 命名空间
type: docs
weight: 1300
url: /zh/net/aspose.email.clients.activesync.transportlayer/getitemestimate/
---
## GetItemEstimate enumeration

ActiveSync 协议的 GetItemEstimate 命名空间

```csharp
public enum GetItemEstimate
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| GetItemEstimate | `5` | GetItemEstimate 元素是 GetItemEstimate 命令请求和 GetItemEstimate 命令响应中的必需元素，它将 HTTP POST 的正文标识为包含 GetItemEstimate 命令（第 2.2.2.7 节）。 |
| Version | `6` | 只有在 MS-ASProtocolVersion 标头设置为 12.1. 时才支持版本标记 |
| Collections | `7` | 用作 1 到 300 个集合元素的容器。 |
| Collection | `8` | 包含适用于特定集合的元素。 |
| Class | `9` | 将 airsync:Options 容器中的过滤器分配给给定的类。 |
| CollectionId | `10` | 指定从中获取项目估计值的集合的服务器 ID。 |
| DateTime | `11` | 仅当 MS-ASProtocolVersion 标头设置为 12.1. 时才支持 DateTime 标记 |
| Estimate | `12` | 指定集合或文件夹中必须同步的估计项目数。 |
| Response | `13` | 包含描述估计变化的元素。 |
| Status | `14` | 指示命令请求失败的原因。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
