---
title: IAsyncEwsClient.ListSubFoldersAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Gets collection of child folders from parent
type: docs
weight: 480
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersasync/
---
## IAsyncEwsClient.ListSubFoldersAsync method

Gets collection of child folders from parent

```csharp
public Task<ExchangeFolderInfoCollection> ListSubFoldersAsync(string mailbox, 
    string parentFolderUri, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | String | The mailbox that is used to initialize the folder id class. |
| parentFolderUri | String | A parent folder |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

[`ExchangeFolderInfoCollection`](../../../aspose.email.clients.exchange/exchangefolderinfocollection/) that contains subfolders from the parent folder

### See Also

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection/)
* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


