---
title: ImapClient.CreateAsync
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Creates a new instance of the ImapClient class
type: docs
weight: 1330
url: /net/aspose.email.clients.imap/imapclient/createasync/
---
## ImapClient.CreateAsync method

Creates a new instance of the [`ImapClient`](../) class

```csharp
public static Task<IAsyncImapClient> CreateAsync(string host, string username, 
    IAsyncTokenProvider asyncTokenProvider, int port = 143, 
    SecurityOptions securityOptions = SecurityOptions.Auto, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The host name |
| port | String | The port number |
| username | IAsyncTokenProvider | The user name |
| asyncTokenProvider | Int32 | The access token provider. |
| securityOptions | SecurityOptions | Security mode for a mail client |
| cancellationToken | CancellationToken | The cancellation token. |

### See Also

* interface [IAsyncImapClient](../../iasyncimapclient/)
* interface [IAsyncTokenProvider](../../../aspose.email.clients/iasynctokenprovider/)
* enum [SecurityOptions](../../../aspose.email.clients/securityoptions/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


