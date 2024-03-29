---
title: IAsyncImapClient.GetFolderInfoAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Returns information about the specified folder without selecting it
type: docs
weight: 160
url: /net/aspose.email.clients.imap/iasyncimapclient/getfolderinfoasync/
---
## IAsyncImapClient.GetFolderInfoAsync method

Returns information about the specified folder without selecting it

```csharp
public Task<ImapFolderInfo> GetFolderInfoAsync(string folderName, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server |
| folderName | IConnection | Folder to retrieve information about |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

The specified folder information

### See Also

* class [ImapFolderInfo](../../imapfolderinfo/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


