---
title: IAsyncImapClient.MoveFolderAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Moves specified folder and its subfolders to new location
type: docs
weight: 260
url: /net/aspose.email.clients.imap/iasyncimapclient/movefolderasync/
---
## IAsyncImapClient.MoveFolderAsync method

Moves specified folder and its subfolders to new location.

```csharp
public Task MoveFolderAsync(string newParentFolder, string folderName, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newParentFolder | String | New location for moved folder |
| folderName | String | Folder to move |
| connection | IConnection | Connection to a server |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


