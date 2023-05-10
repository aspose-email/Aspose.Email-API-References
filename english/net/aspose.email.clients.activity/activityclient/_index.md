---
title: Class ActivityClient
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Activity.ActivityClient class. Provides access to MS Exchange Server Office365 by using REST API
type: docs
weight: 2360
url: /net/aspose.email.clients.activity/activityclient/
---
## ActivityClient class

Provides access to MS Exchange Server (Office365) by using REST API.

```csharp
public abstract class ActivityClient : IActivityClient
```

## Properties

| Name | Description |
| --- | --- |
| virtual [MultipleServicesTokenProvider](../../aspose.email.clients.activity/activityclient/multipleservicestokenprovider/) { get; set; } | Gets or sets an object allows to retrieve OAuth access token. |
| virtual [Proxy](../../aspose.email.clients.activity/activityclient/proxy/) { get; set; } | Gets or sets data to proxy access to Exchange server. |
| virtual [ResourceId](../../aspose.email.clients.activity/activityclient/resourceid/) { get; set; } | Gets or sets resource id. For instance for users it may be user principal name (UPN) or user id |
| virtual [TenantId](../../aspose.email.clients.activity/activityclient/tenantid/) { get; set; } | Gets or sets tenant identifier |
| virtual [Timeout](../../aspose.email.clients.activity/activityclient/timeout/) { get; set; } | Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds). |
| virtual [TokenProvider](../../aspose.email.clients.activity/activityclient/tokenprovider/) { get; set; } | Gets or sets an object allows to retrieve OAuth access token. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients.activity/activityclient/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [FetchContent](../../aspose.email.clients.activity/activityclient/fetchcontent/)(string) |  |
| [ListContent](../../aspose.email.clients.activity/activityclient/listcontent/#listcontent)(string) |  |
| [ListContent](../../aspose.email.clients.activity/activityclient/listcontent/#listcontent_1)(string, DateTime?, DateTime?) |  |
| [ListFriendlyNames](../../aspose.email.clients.activity/activityclient/listfriendlynames/)() |  |
| [ListSubscriptions](../../aspose.email.clients.activity/activityclient/listsubscriptions/)() |  |
| [StartSubscription](../../aspose.email.clients.activity/activityclient/startsubscription/)(string, Webhook) |  |
| [StopSubscription](../../aspose.email.clients.activity/activityclient/stopsubscription/)(string) |  |
| static [GetClient](../../aspose.email.clients.activity/activityclient/getclient/#getclient)(IMultipleServicesTokenProvider, string) | Initializes a new instance of the `ActivityClient` based class |
| static [GetClient](../../aspose.email.clients.activity/activityclient/getclient/#getclient_1)(ITokenProvider, string) | Initializes a new instance of the `ActivityClient` based class |

### See Also

* interface [IActivityClient](../iactivityclient/)
* namespace [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity/)
* assembly [Aspose.Email](../../)


