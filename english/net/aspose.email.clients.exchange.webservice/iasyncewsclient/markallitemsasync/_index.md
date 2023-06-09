---
title: IAsyncEwsClient.MarkAllItemsAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Marks all items in specified folders
type: docs
weight: 540
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/markallitemsasync/
---
## IAsyncEwsClient.MarkAllItemsAsync method

Marks all items in specified folders.

```csharp
public Task MarkAllItemsAsync(IEnumerable<string> folderIds = null, bool read = true, 
    bool suppressReadReceipts = true, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| read | IEnumerable`1 | Sets the read/unread state to messages in specified folder. True to mark messages in the folder as read. False to mark messages as unread. |
| suppressReadReceipts | Boolean | True to suppress sending read receipts for messages; otherwise, false. |
| folderIds | Boolean | List of folder URIs for processing. Set to Inbox URI by default. |
| cancellationToken | CancellationToken | The cancellation token. |

### See Also

* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


