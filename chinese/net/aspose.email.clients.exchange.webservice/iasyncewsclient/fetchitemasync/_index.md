---
title: FetchItemAsync
second_title: Aspose.Email for .NET API 参考
description: 检索带有附件的完整项目
type: docs
weight: 250
url: /zh/net/aspose.email.clients.exchange.webservice/iasyncewsclient/fetchitemasync/
---
## IAsyncEwsClient.FetchItemAsync method

检索带有附件的完整项目。

```csharp
public Task<MapiMessage> FetchItemAsync(string uri, 
    IEnumerable<PropertyDescriptor> extendedProperties = null, 
    CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uri | String | 项目 URI。 |
| extendedProperties | IEnumerable`1 | 要检索的指定属性。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

[`MapiMessage`](../../../aspose.email.mapi/mapimessage)对象.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | 项目 URI 为 null 或为空。 |

### 也可以看看

* class [MapiMessage](../../../aspose.email.mapi/mapimessage)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
