---
title: FetchMapiMessages
second_title: Aspose.Email for .NET API 参考
description: 获取指定的消息
type: docs
weight: 780
url: /zh/net/aspose.email.clients.exchange.webservice/iewsclient/fetchmapimessages/
---
## FetchMapiMessages(IEnumerable&lt;string&gt;) {#fetchmapimessages}

获取指定的消息

```csharp
public MapiMessage[] FetchMapiMessages(IEnumerable<string> uris)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uris | IEnumerable`1 | AIEnumerable&lt;string&gt; "/&gt; 包含要检索的消息 uri |

### 返回值

Mapi的数组。MapiMessage包含获取的消息

### 也可以看看

* class [MapiMessage](../../../aspose.email.mapi/mapimessage)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## FetchMapiMessages(IEnumerable&lt;string&gt;, IEnumerable&lt;PropertyDescriptor&gt;) {#fetchmapimessages_1}

获取指定消息

```csharp
public MapiMessage[] FetchMapiMessages(IEnumerable<string> uris, 
    IEnumerable<PropertyDescriptor> extendedProperties)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uris | IEnumerable`1 | AStringCollection包含要检索的消息 uri |
| extendedProperties | IEnumerable`1 | 扩展属性的枚举 |

### 返回值

一个数组[`MapiMessage`](../../../aspose.email.mapi/mapimessage)包含获取的消息

### 也可以看看

* class [MapiMessage](../../../aspose.email.mapi/mapimessage)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->