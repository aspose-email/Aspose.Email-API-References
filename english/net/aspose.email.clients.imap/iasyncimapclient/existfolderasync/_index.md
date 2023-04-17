---
title: IAsyncImapClient.ExistFolderAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Check whether this folder exists
type: docs
weight: 130
url: /net/aspose.email.clients.imap/iasyncimapclient/existfolderasync/
---
## IAsyncImapClient.ExistFolderAsync method

Check whether this folder exists

```csharp
public Task<bool> ExistFolderAsync(string folderName, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server |
| folderName | IConnection | Name of the folder |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns true if the folder is existing, otherwise returns false

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


