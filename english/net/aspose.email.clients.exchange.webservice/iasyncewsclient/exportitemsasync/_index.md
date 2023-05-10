---
title: IAsyncEwsClient.ExportItemsAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Exports the specified items from mailbox
type: docs
weight: 210
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/exportitemsasync/
---
## IAsyncEwsClient.ExportItemsAsync method

Exports the specified items from mailbox

```csharp
public Task<IEnumerable<ExchangeStreamedItem>> ExportItemsAsync(IEnumerable<string> itemIds, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| itemIds | IEnumerable`1 | Ids of items to be exported |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

An array of [`ExchangeStreamedItem`](../../exchangestreameditem/)

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *itemIds* is `null` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *itemIds* is `empty` |

### See Also

* class [ExchangeStreamedItem](../../exchangestreameditem/)
* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


