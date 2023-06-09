---
title: IAsyncEwsClient.CreateItemsAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Creates the specified items in the specified folder
type: docs
weight: 120
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/createitemsasync/
---
## IAsyncEwsClient.CreateItemsAsync method

Creates the specified items in the specified folder

```csharp
public Task<IEnumerable<ExchangeUploadItemResult>> CreateItemsAsync(
    IEnumerable<ExchangeStreamedItem> items, string parentFolderUri, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| items | IEnumerable`1 | The items to be uploaded |
| parentFolderUri | String | Specifies the folder in which to place the items |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

An array of [`ExchangeUploadItemResult`](../../exchangeuploaditemresult/)

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *items* is `null` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *items* is `empty` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *parentFolderUri* is `null` or `empty` |

### See Also

* class [ExchangeUploadItemResult](../../exchangeuploaditemresult/)
* class [ExchangeStreamedItem](../../exchangestreameditem/)
* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


