---
title: IAsyncImapClient.SubscribeFolderAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Sent the SUBSCRIBE command that adds the specified mailbox name to the servers set of active mailboxes
type: docs
weight: 390
url: /net/aspose.email.clients.imap/iasyncimapclient/subscribefolderasync/
---
## IAsyncImapClient.SubscribeFolderAsync method

Sent the SUBSCRIBE command that adds the specified mailbox name to the server's set of "active" mailboxes.

```csharp
public Task SubscribeFolderAsync(string folderName, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server |
| folderName | IConnection | Name of the folder |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


