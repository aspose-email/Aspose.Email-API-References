---
title: IGraphClientAsync.GetContactFolderAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Gets main contact folder. This method requires that at least one contact exists in the main contacts folder otherwise it will return null. https//learn.microsoft.com/enus/answers/questions/854621/howtogetfolderidofdefaultcontactsfolderwh
type: docs
weight: 260
url: /net/aspose.email.clients.graph/igraphclientasync/getcontactfolderasync/
---
## IGraphClientAsync.GetContactFolderAsync method

Gets main contact folder. This method requires that at least one contact exists in the main contacts folder, otherwise it will return null. https://learn.microsoft.com/en-us/answers/questions/854621/how-to-get-folder-id-of-default-contacts-folder-wh

```csharp
public Task<FolderInfo> GetContactFolderAsync(CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the main contact folder.

### See Also

* class [FolderInfo](../../folderinfo/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


