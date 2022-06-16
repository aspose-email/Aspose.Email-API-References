---
title: SearchResultProperties
second_title: Aspose.Email for .NET API 参考
description: 搜索命令响应属性是适用于与查询元素搜索字符串匹配的单个条目的属性的容器 例如Properties 元素为每个附加到匹配 GAL 条目的非空文本值 GAL 属性包含一个元素 仅返回附加到特定 GAL 条目的那些属性因此对于不同的匹配 GAL 条目可以在响应 XML 中返回不同的属性集 Properties 容器中的每个元素都限定在顶级 Search 元素中指定的适当命名空间
type: docs
weight: 2020
url: /zh/net/aspose.email.clients.activesync.transportlayer/searchresultproperties/
---
## SearchResultProperties class

搜索命令响应属性是适用于与查询元素搜索字符串匹配的单个条目的属性的容器。 例如，Properties 元素为每个附加到匹配 GAL 条目的非空文本值 GAL 属性包含一个元素。 仅返回附加到特定 GAL 条目的那些属性；因此，对于不同的匹配 GAL 条目，可以在响应 XML 中返回不同的属性集。 Properties 容器中的每个元素都限定在顶级 Search 元素中指定的适当命名空间。

```csharp
public class SearchResultProperties
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SearchResultProperties](searchresultproperties)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Body](../../aspose.email.clients.activesync.transportlayer/searchresultproperties/body) { get; } | 指定与服务器上存储的项目关联的自由格式、可变长度的数据字段。 |
| [BodyPart](../../aspose.email.clients.activesync.transportlayer/searchresultproperties/bodypart) { get; } | 指定响应中电子邮件消息部分的详细信息。 |
| [DataContainer](../../aspose.email.clients.activesync.transportlayer/searchresultproperties/datacontainer) { get; } | 包含来自内容类的数据元素。 |
| [Picture](../../aspose.email.clients.activesync.transportlayer/searchresultproperties/picture) { get; set; } | 包含与联系人照片相关的数据。 |
| [RightsManagementLicense](../../aspose.email.clients.activesync.transportlayer/searchresultproperties/rightsmanagementlicense) { get; set; } | 包含应用于正在同步的电子邮件的模板的权限策略模板设置。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->