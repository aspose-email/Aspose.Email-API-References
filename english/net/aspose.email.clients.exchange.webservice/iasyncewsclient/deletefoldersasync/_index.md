---
title: IAsyncEwsClient.DeleteFoldersAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncEwsClient method. Deletes the folders
type: docs
weight: 170
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/deletefoldersasync/
---
## IAsyncEwsClient.DeleteFoldersAsync method

Deletes the folders

```csharp
public Task DeleteFoldersAsync(IEnumerable<string> folderUris, bool deletePermanently = false, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUris | IEnumerable`1 | The list of folder URIs |
| deletePermanently | Boolean | Indicates whether the folder should be deleted permanently or should be moved into DeletedItems folder |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *folderUris* is `null` |

### See Also

* interface [IAsyncEwsClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient/)
* assembly [Aspose.Email](../../../)


