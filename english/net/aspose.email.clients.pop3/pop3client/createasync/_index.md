---
title: Pop3Client.CreateAsync
second_title: Aspose.Email for .NET API Reference
description: Pop3Client method. Creates a new instance of the Pop3Client class
type: docs
weight: 410
url: /net/aspose.email.clients.pop3/pop3client/createasync/
---
## Pop3Client.CreateAsync method

Creates a new instance of the [`Pop3Client`](../) class

```csharp
public static Task<IAsyncPop3Client> CreateAsync(string host, string username, 
    IAsyncTokenProvider asyncTokenProvider, int port = 110, 
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

* interface [IAsyncPop3Client](../../iasyncpop3client/)
* interface [IAsyncTokenProvider](../../../aspose.email.clients/iasynctokenprovider/)
* enum [SecurityOptions](../../../aspose.email.clients/securityoptions/)
* class [Pop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../pop3client/)
* assembly [Aspose.Email](../../../)


