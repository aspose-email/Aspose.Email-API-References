---
title: IAsyncEwsClient.MarkAsJunkAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender
type: docs
weight: 550
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/markasjunkasync/
---
## IAsyncEwsClient.MarkAsJunkAsync method

The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

```csharp
public Task<IEnumerable<string>> MarkAsJunkAsync(IEnumerable<string> messageUris, 
    bool isJunk = true, bool moveItem = false, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageUris | IEnumerable`1 | Enumeration of message uri |
| isJunk | Boolean | Indicates, whether messages are marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| moveItem | Boolean | Indicates, whether messages is moved to the junk mail folder. |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

The set of identifiers of moved items

### Exceptions

| exception | condition |
| --- | --- |
| [EwsMarkAsJunkException](../../../aspose.email.clients.exchange.webservice.exceptions/ewsmarkasjunkexception/) | There where failed items. |

### See Also

* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


