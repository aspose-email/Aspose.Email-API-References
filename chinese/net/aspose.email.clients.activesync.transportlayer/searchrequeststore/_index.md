---
title: SearchRequestStore
second_title: Aspose.Email for .NET API 参考
description: 指定搜索的名称查询和选项
type: docs
weight: 1980
url: /zh/net/aspose.email.clients.activesync.transportlayer/searchrequeststore/
---
## SearchRequestStore class

指定搜索的名称、查询和选项。

```csharp
public class SearchRequestStore
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SearchRequestStore](searchrequeststore)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Name](../../aspose.email.clients.activesync.transportlayer/searchrequeststore/name) { get; set; } | 包含为操作指定位置的信息。 |
| [Options](../../aspose.email.clients.activesync.transportlayer/searchrequeststore/options) { get; set; } | 包含搜索选项。 用户名和密码只有在收到状态值 14 后才能在请求中发送。 服务器需要这些凭据才能访问请求的资源。 客户端必须仅通过安全或受信任的连接发送这些，并且仅响应状态值 14。 支持的选项因正在搜索的商店而异. 下表列出了每个商店的有效选项。 GAL:Range, UserName, Password, Picture Mailbox:Range, DeepTraversal, RebuildResults, BodyPreference, BodyPartPreference, RightsManagementSupport DocumentLibrary:Range, UserName, Password BodyPartPreference 仅在包含 ConversationId 的搜索命令请求中有效。 |
| [Query](../../aspose.email.clients.activesync.transportlayer/searchrequeststore/query) { get; set; } | 指定用于匹配正在搜索的商店中的条目的关键字。 Query 的值用作前缀字符串匹配模式，并返回匹配字符串开头的条目。 例如，搜索“John”将匹配“John Frum”或“Barry Johnson”，但不会匹配“James Littlejohn”。 GAL 中使用 ANR 索引的所有非空文本属性都与 Query 元素值进行比较。 搜索比较是通过使用不区分大小写的匹配来执行的。 对于 Windows SharePoint Services 文档库搜索，此协议支持以下形式的查询:LinkId == value, 其中 value 指定项目或文件夹的 URL，LinkId 表示该值将与链接 ID 属性进行比较。 对于邮箱搜索，查询语法如下: - 可以通过以下方式指定文件夹: 指定ID 指定文件夹和子文件夹 所有电子邮件文件夹，包括草稿、收件箱和子文件夹、发件箱和已发送邮件 - 基本关键字查询可以由以下内容组成: 基本运算符:And（第 2.2.3.10 节） 使用 GreaterThan（第 2.2.3.78 节）和 LessThan 元素（第 2.2.3.87 节）指定的 dateTime 过滤器 包含关键字 的 FreeText 元素（第 2.2.3.73 节）:针对所有索引属性执行基本关键字查询。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->