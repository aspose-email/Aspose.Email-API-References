---
title: ListContactsAsync
second_title: Aspose.Email for .NET API 参考
description: 列出服务器上指定文件夹中的联系人
type: docs
weight: 420
url: /zh/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listcontactsasync/
---
## IAsyncEwsClient.ListContactsAsync method

列出服务器上指定文件夹中的联系人。

```csharp
public Task<IEnumerable<MapiContact>> ListContactsAsync(string folderUri, 
    IEnumerable<PropertyDescriptor> mapiProperties = null, 
    CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderUri | String | 用于搜索联系人的文件夹。 |
| mapiProperties | IEnumerable`1 | 必需的其他 mapi 属性。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

读取数组[`MapiContact`](../../../aspose.email.mapi/mapicontact)代表联系信息。

### 也可以看看

* class [MapiContact](../../../aspose.email.mapi/mapicontact)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
