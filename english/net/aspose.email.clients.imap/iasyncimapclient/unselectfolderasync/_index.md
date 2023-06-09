---
title: IAsyncImapClient.UnselectFolderAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Unselects folder which are currently selected. if doNotExpunge property is true all messages are marked as deleted are removed otherwise deletion canceled. Please note this operation works only in case if server supports RFC3691 See more https//tools.ietf.org/html/rfc3691
type: docs
weight: 410
url: /net/aspose.email.clients.imap/iasyncimapclient/unselectfolderasync/
---
## IAsyncImapClient.UnselectFolderAsync method

Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(bool doNotExpunge = false, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | Boolean | Connection to a server |
| doNotExpunge | IConnection | Specifies whether messages marked as deleted should be removed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


