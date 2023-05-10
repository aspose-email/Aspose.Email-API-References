---
title: SmtpClient.CreateAsync
second_title: Aspose.Email for .NET API Reference
description: SmtpClient method. Creates a new instance of the SmtpClient class
type: docs
weight: 220
url: /net/aspose.email.clients.smtp/smtpclient/createasync/
---
## SmtpClient.CreateAsync method

Creates a new instance of the [`SmtpClient`](../) class

```csharp
public static Task<IAsyncSmtpClient> CreateAsync(string host, string username, 
    IAsyncTokenProvider asyncTokenProvider, int port = 25, 
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

* interface [IAsyncSmtpClient](../../iasyncsmtpclient/)
* interface [IAsyncTokenProvider](../../../aspose.email.clients/iasynctokenprovider/)
* enum [SecurityOptions](../../../aspose.email.clients/securityoptions/)
* class [SmtpClient](../)
* namespace [Aspose.Email.Clients.Smtp](../../smtpclient/)
* assembly [Aspose.Email](../../../)


