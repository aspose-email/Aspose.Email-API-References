---
title: IAsyncImapClient.SetQuotaAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Sets quota information
type: docs
weight: 350
url: /net/aspose.email.clients.imap/iasyncimapclient/setquotaasync/
---
## IAsyncImapClient.SetQuotaAsync method

Sets quota information

```csharp
public Task<ImapQuota[]> SetQuotaAsync(string quotaRootName, string resourceName, 
    int resourceLimit, IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server |
| quotaRootName | String | quota root name |
| resourceName | Int32 | resource name |
| resourceLimit | IConnection | resource limit |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Quota information

### See Also

* class [ImapQuota](../../imapquota/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


