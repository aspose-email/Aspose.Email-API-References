---
title: IAsyncEwsClient.ListSubFoldersByPageAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Searches the specified folder in the given parent folder with paging Method supports paging
type: docs
weight: 490
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersbypageasync/
---
## IAsyncEwsClient.ListSubFoldersByPageAsync method

Searches the specified folder in the given parent folder with paging Method supports paging.

```csharp
public Task<ExchangeFolderPageInfo> ListSubFoldersByPageAsync(string parentFolderUri, 
    PageInfo page, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | String | A parent folder URI |
| page | PageInfo | A page info |
| cancellationToken | CancellationToken | The cancellation token. |

### Return Value

A [`ExchangeFolderPageInfo`](../../../aspose.email.clients.exchange/exchangefolderpageinfo/) containing the found folder if folder name is specified; otherwise, returns all subfolders

### See Also

* class [ExchangeFolderPageInfo](../../../aspose.email.clients.exchange/exchangefolderpageinfo/)
* class [PageInfo](../../../aspose.email.clients/pageinfo/)
* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


