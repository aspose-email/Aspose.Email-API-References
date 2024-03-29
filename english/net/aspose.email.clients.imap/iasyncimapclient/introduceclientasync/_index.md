---
title: IAsyncImapClient.IntroduceClientAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Introduces client information to a server
type: docs
weight: 210
url: /net/aspose.email.clients.imap/iasyncimapclient/introduceclientasync/
---
## IAsyncImapClient.IntroduceClientAsync method

Introduces client information to a server.

```csharp
public Task<ImapIdentificationInfo> IntroduceClientAsync(
    ImapIdentificationInfo clientIdentificationInfo, IConnection connection = null, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | ImapIdentificationInfo | Connection to a server |
| clientIdentificationInfo | IConnection | Client identification information |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns server identification information

### See Also

* class [ImapIdentificationInfo](../../imapidentificationinfo/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


