---
title: IActivityClient
second_title: Aspose.Email for .NET API 参考
description: 表示 Exchange REST 客户端的接口
type: docs
weight: 2570
url: /zh/net/aspose.email.clients.activity/iactivityclient/
---
## IActivityClient interface

表示 Exchange REST 客户端的接口。

```csharp
public interface IActivityClient : IDisposable
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [MultipleServicesTokenProvider](../../aspose.email.clients.activity/iactivityclient/multipleservicestokenprovider) { get; set; } | 获取或设置允许检索 OAuth 访问令牌的对象。 |
| [Proxy](../../aspose.email.clients.activity/iactivityclient/proxy) { get; set; } | 获取或设置数据以代理访问 Exchange 服务器。 |
| [ResourceId](../../aspose.email.clients.activity/iactivityclient/resourceid) { get; set; } | 获取或设置资源ID。 例如对于用户，它可能是用户主体名称 (UPN) 或用户 ID |
| [TenantId](../../aspose.email.clients.activity/iactivityclient/tenantid) { get; set; } | 获取或设置租户标识符 |
| [Timeout](../../aspose.email.clients.activity/iactivityclient/timeout) { get; set; } | 获取或设置操作超时前等待的毫秒数。 默认值为 100,000 毫秒（100 秒）。 |
| [TokenProvider](../../aspose.email.clients.activity/iactivityclient/tokenprovider) { get; set; } | 获取或设置允许检索 OAuth 访问令牌的对象。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [FetchContent](../../aspose.email.clients.activity/iactivityclient/fetchcontent)(string) | 此操作获取当前可用于检索指定内容 ID 的内容。 |
| [ListContent](../../aspose.email.clients.activity/iactivityclient/listcontent#listcontent)(string) | 此操作列出当前可用于检索的指定内容类型的内容。 内容是从跨多个数据中心的多个服务器收集的操作和事件的聚合。 内容将按照聚合可用的顺序列出， 但不保证聚合中的事件和操作是连续的。 默认情况下，省略 startTime 和 endTime 时，返回过去 24 小时内可用的内容。 |
| [ListContent](../../aspose.email.clients.activity/iactivityclient/listcontent#listcontent_1)(string, DateTime?, DateTime?) | 此操作列出当前可用于检索的指定内容类型的内容。 内容是从跨多个数据中心的多个服务器收集的操作和事件的聚合。 内容将按照聚合可用的顺序列出， 但不保证聚合中的事件和操作是连续的。 |
| [ListFriendlyNames](../../aspose.email.clients.activity/iactivityclient/listfriendlynames)() | 此操作检索由 guid 标识的数据馈送中的对象的友好名称。 |
| [ListSubscriptions](../../aspose.email.clients.activity/iactivityclient/listsubscriptions)() | 此操作返回当前订阅的集合以及关联的 webhook。 |
| [StartSubscription](../../aspose.email.clients.activity/iactivityclient/startsubscription)(string, Webhook) | 开始订阅指定的内容类型。 如果已存在对指定内容类型的订阅，则此操作用于: - 更新活动 webhook 的属性 - 启用 webhook由于过多的失败通知而被禁用 - 通过指定较晚的或空的到期日期重新启用过期的 webhook - 删除 webhook |
| [StopSubscription](../../aspose.email.clients.activity/iactivityclient/stopsubscription)(string) | 此操作停止对指定内容类型的订阅。 订阅停止后，您将不再收到通知，并且您将无法检索可用内容。 如果订阅稍后重新启动，您将可以从那时起访问新内容。 您将无法检索在订阅停止和重新启动之间可用的内容。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->