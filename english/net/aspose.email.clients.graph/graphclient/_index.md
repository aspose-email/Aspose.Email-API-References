---
title: Class GraphClient
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Graph.GraphClient class. Provides access to MS Exchange Server Office365 by using REST API
type: docs
weight: 15960
url: /net/aspose.email.clients.graph/graphclient/
---
## GraphClient class

Provides access to MS Exchange Server (Office365) by using REST API.

```csharp
public abstract class GraphClient : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| virtual [MultipleServicesTokenProvider](../../aspose.email.clients.graph/graphclient/multipleservicestokenprovider/) { get; set; } | Gets or sets an object allows to retrieve OAuth access token. |
| virtual [Proxy](../../aspose.email.clients.graph/graphclient/proxy/) { get; set; } | Gets or sets data to proxy access to Exchange server. |
| virtual [Resource](../../aspose.email.clients.graph/graphclient/resource/) { get; set; } | Gets or sets resource type. |
| virtual [ResourceId](../../aspose.email.clients.graph/graphclient/resourceid/) { get; set; } | Gets or sets resource id. For instance for users it may be user principal name (UPN) or user id |
| virtual [TenantId](../../aspose.email.clients.graph/graphclient/tenantid/) { get; set; } | Gets or sets tenant identifier |
| virtual [Timeout](../../aspose.email.clients.graph/graphclient/timeout/) { get; set; } | Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds). |
| virtual [TokenProvider](../../aspose.email.clients.graph/graphclient/tokenprovider/) { get; set; } | Gets or sets an object allows to retrieve OAuth access token. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients.graph/graphclient/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| static [GetClient](../../aspose.email.clients.graph/graphclient/getclient/#getclient)(IMultipleServicesTokenProvider, string) | Initializes a new instance of the `GraphClient` based class |
| static [GetClient](../../aspose.email.clients.graph/graphclient/getclient/#getclient_1)(ITokenProvider, string) | Initializes a new instance of the `GraphClient` based class |

### See Also

* namespace [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph/)
* assembly [Aspose.Email](../../)


