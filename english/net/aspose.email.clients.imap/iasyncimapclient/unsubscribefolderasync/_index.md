---
title: IAsyncImapClient.UnsubscribeFolderAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Sent the UNSUBSCRIBE command that removes the specified mailbox name from the servers set of active mailboxes
type: docs
weight: 420
url: /net/aspose.email.clients.imap/iasyncimapclient/unsubscribefolderasync/
---
## IAsyncImapClient.UnsubscribeFolderAsync method

Sent the UNSUBSCRIBE command that removes the specified mailbox name from the server's set of "active" mailboxes

```csharp
public Task UnsubscribeFolderAsync(string folderName, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server |
| folderName | IConnection | Name of the folder |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


