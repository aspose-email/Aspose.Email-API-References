---
title: IAsyncEwsClient.FetchItemAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Retrieves the complete item with attachments
type: docs
weight: 250
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/fetchitemasync/
---
## IAsyncEwsClient.FetchItemAsync method

Retrieves the complete item with attachments.

```csharp
public Task<MapiMessage> FetchItemAsync(string uri, 
    IEnumerable<PropertyDescriptor> extendedProperties = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uri | String | The item URI. |
| extendedProperties | IEnumerable`1 | Specified properties to retrieve. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

[`MapiMessage`](../../../aspose.email.mapi/mapimessage/) object.

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | The item URI is null or empty. |

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor/)
* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


